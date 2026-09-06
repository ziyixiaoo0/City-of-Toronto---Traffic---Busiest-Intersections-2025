# City-of-Toronto---Traffic---Busiest-Intersections-2025
An analysis of the top 10 most busy intersections

## Exploratory Data Analysis: Limitations & Findings

### Data Quality Note
The [Traffic Volumes at Intersections for All Modes](https://open.toronto.ca/dataset/traffic-volumes-at-intersections-for-all-modes/) 
dataset from Open Data Toronto is collected on an **ad-hoc basis** — individual intersections 
are surveyed on different days, not continuously monitored. This introduces several constraints:

- **No consistent time series is possible.** Since each intersection's count reflects a single 
  (or a few) sampled day(s) rather than continuous monitoring, trends over time (daily, weekly, 
  seasonal) cannot be reliably extracted or compared across intersections.
- **Weekday vs. weekend bias.** Because collection days vary by location, some intersections may 
  only have weekday counts while others only have weekend counts — direct comparisons between 
  intersections can conflate "busyness" with "which day it happened to be surveyed."
- **Snapshot, not a trend.** Volume figures represent a snapshot in time for that location, not 
  a representative annual average.

### Approach
Intersections are ranked by total recorded volume (all modes) for 2025 survey 
dates, acknowledging that:

1. Rankings reflect the day(s) each intersection happened to be surveyed, not a true annual average.
2. Rankings **may shift** if resurveyed on a different day (e.g., weekday vs weekend).
3. This should be read as "busiest among sampled days in 2025," not "busiest every day of 2025."

### Top 10 Busiest Intersections (by recorded volume, 2025)

<img src="Top%2010%20Intersections.png" alt="Lineup" width="600" height="600"/>

*Note: rankings are based on single-day counts and should be interpreted as indicative rather 
than definitive, given inconsistent sampling across intersections.*

### Caveats
- Results may be sensitive to which day of the week each intersection was sampled.
- Total volume combines all modes (vehicles, cyclists, pedestrians) — consider whether a 
  mode-specific breakdown better serves your question.
