# Chris Gibbs

I trained as a mechanical engineer and spent 17 years in manufacturing: building
materials, aerospace composites, steel and medical devices, much of it in process
engineering and operational excellence (Six Sigma Black Belt). In 2023 I moved into
data science. I am now a data scientist on the enterprise AI team at NYU Langone
Health, where I build and evaluate LLM agents and retrieval systems. That work is
internal; this profile holds personal and hackathon projects.

I have an MS in Data Science from Drew University, where I also teach database
management as an adjunct.

## Featured project

**[Race Engineer Adaptive Harness](https://github.com/TallGibbs/race-engineer-adaptive-harness)**
([project page](https://tallgibbs.github.io/race-engineer-adaptive-harness/))

Built at the MongoDB NYC hackathon, September 2026. Three role agents (race
engineer, statistician, data engineer) write briefs from public Formula 1 timing
data. The harness records every run in MongoDB Atlas and runs a DMAIC cycle on its
own records: it finds root causes of its defects, stores them as lessons retrieved
with Atlas Vector Search, and proposes changes to its own configuration. A fixed
evaluator, committed before any harness code, decides whether a change is kept,
under five acceptance rules that include no regression on control cases. Three
experiments ran; the evaluator rejected all three candidates, and the reports
record why.

## Other projects

- **[World Cup Tracker](https://github.com/TallGibbs/World_Cup_Tracker)**: a static
  site for the 2026 men's World Cup, refreshed by a scheduled Claude Code routine.
  All data lives in one file, a validator gates every commit, and Cloudflare Pages
  deploys from `main`.
- **[Accessible Airbnb finder](https://github.com/TallGibbs/Databricks_Hackathon_RA)**:
  a five-hour team hackathon build of a tool-calling agent on Databricks that finds
  listings whose reviews mention wheelchair access.
- **[Relay team grocery list](https://github.com/TallGibbs/team_grocery_list)**: a
  no-login shared list on Cloudflare Pages with a small serverless API.
