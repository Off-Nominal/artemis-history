# Artemis Architecture Changes

## March 13, 2020 - Gateway Removed from Critical Path

Doug Loverro, NASA Associate Administrator for Human Exploration and
Operations, announces that the Lunar Gateway is no longer on the
"critical path" for the first crewed lunar landing.

### Rationale
The original Artemis III architecture required Gateway as a waypoint:
- Crew launches on SLS/Orion to lunar orbit
- Docks with Gateway in Near-Rectilinear Halo Orbit (NRHO)
- Transfers to Human Landing System docked at Gateway
- Descends to lunar surface

This stacked approximately 34 critical operations on the first landing
mission, with about 25 of them never having been performed before.

### New Architecture (Artemis III)
- Crew launches on SLS/Orion
- Starship HLS pre-positions itself in NRHO (uncrewed)
- Orion docks directly with Starship HLS in NRHO
- Crew transfers to HLS and descends to surface
- No Gateway required for initial landing

### Impact
- Reduces complexity and risk for Artemis III
- Gateway preserved for Artemis IV and sustained exploration
- Allows Gateway development to proceed on its own timeline
- Loverro: "If it's not mandatory, it's not necessary"
