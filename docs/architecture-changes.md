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

## February 27, 2026 - SLS Block 1B and Block 2 Cancelled

As part of the sweeping Artemis restructuring, Administrator Isaacman
cancels the SLS Block 1B and Block 2 upgrade path.

### What Was Cancelled
- **Exploration Upper Stage (EUS)**: Four RL-10 engines, would have replaced
  the ICPS for greater payload capacity
- **SLS Block 1B**: Would have debuted on Artemis IV with co-manifested
  payload capability (~105 metric tons to LEO)
- **SLS Block 2**: Advanced boosters, ~130 metric tons to LEO
- **Mobile Launcher 2 (ML-2)**: Required for the taller Block 1B, built by
  Bechtel at spiraling cost (estimated up to $2.7B, not ready until 2029)

### New Approach
NASA will standardize on a "near Block 1" SLS configuration for all future
missions, using the existing ICPS upper stage or minor variants.

### Rationale
- Block 1B development added years and billions to the program
- ML-2 alone was tracking toward $2.7B and wouldn't be ready until 2029
- Launching SLS "every three years is not a path to success" - Isaacman
- Standardizing on Block 1 enables faster launch cadence (~10 months)
- Each flight builds incrementally rather than stacking many "firsts"

### Schedule Impact
Eliminates a major schedule dependency. The original plan required ML-2
for Artemis IV, but ML-2 wouldn't have been ready until 2029. Now Artemis IV
can use the existing ML-1, targeting early 2028.
