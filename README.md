# the-corner-case

**What happens if the corner three disappears from the NBA?**

This project explores a simple question with big implications:  
How would the game change—on the court, on the stat sheet, and in player value—if the corner three-point shot didn’t exist?

## Motivation

- The corner three is one of the game’s most efficient and controversial shots.
- NBA legends (see: “Mind the Game” podcast) have wondered about its impact.
- This project uses real data to ground that debate: What would modern basketball look like if the corner three was gone?

## Approach

1. **Data Collection**
    - Gather NBA shot location data (last 10 years).
    - Identify and remove all corner threes (defined as X-Y coordinates within NBA corner zone).
2. **Analysis**
    - Recalculate player / team scoring with corner threes zeroed out
    - Visualize changes in shot charts, scoring averages, and 3P% by player/team/league
    - Discuss ripple effects: Who is most / least affected? How do strategies change?
3. **Counterfactual Scenarios**
    - (Stretch goal) Simulate re-allocated shots: If a player couldn’t shoot from the corner, where would those shots go? How does efficiency change?
4. **Visualization**
    - High-quality charts: before/after shot maps, player impact tables, league-wide trends.
5. **Writeup**
    - Executive summary for non-technical readers.
    - Technical appendix for process, code, and assumptions.

## Repo Structure

- `/data` — Raw and processed NBA shot data
- `/notebooks` — Jupyter notebooks: data cleaning, analysis, visualization
- `/output` — Figures, tables, final charts
- `README.md` — This file
- `requirements.txt` — Package dependencies

## Status

**Phase 1:** Data collection & baseline analysis.  
**Next up:** Visualization and expanded scenarios.

## Contributors

- **Abhay Puri** (UT Austin MSBA)

## Acknowledgements

- Built with NBA shot data, open-source tools, and inspiration from the “Mind the Game” podcast.

