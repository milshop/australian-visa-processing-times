# Australian visa processing times (Home Affairs), recorded daily

Data behind [AusVisaClock](https://ausvisaclock.com): the Department of Home Affairs' global visa processing times for every visa subclass and stream, SkillSelect 189 invitation rounds, state and territory nominations and the skilled occupation list. Updated automatically every day; last updated 2026-11-13.

Latest processing time release: 2026-11-09, covering applications decided in the period ending 2026-09-30.

| File | Rows | What it holds |
|---|---|---|
| `processing_times_current.csv` | 74 | Current 25th, 50th, 75th and 90th percentile processing times for each visa and stream, as published and in days |
| `processing_times_history.csv` | 74 | Every release recorded since November 2026, in days |
| `invitation_rounds_189.csv` | 734 | Minimum points and tie-break date by occupation for each 189 round since November 2024 |
| `state_nominations.csv` | 8 | 190 and 491 nominations by state and territory, current program year |
| `skilled_occupation_list.csv` | 714 | Every occupation with ANZSCO codes, lists (MLTSSL, STSOL, ROL, CSOL), visas, assessing authority and latest 189 cut-off |

## What the numbers mean

Processing times are the time within which 25%, 50%, 75% and 90% of recently decided applications were finalised, measured from lodgement to decision. They describe applications already decided, so they lag behind changes in the queue. Days are converted from the department's months at 30.44 days a month.

## Sources and licence

Source: Department of Home Affairs, Australian Government (global visa processing times, SkillSelect invitation rounds, skilled occupation list). Compiled by AusVisaClock. You may reuse this data with attribution to "AusVisaClock (ausvisaclock.com), from Department of Home Affairs data" and a link. AusVisaClock is not affiliated with the Australian Government and this is not immigration advice.

Per-visa pages with charts and a decision date estimator: https://ausvisaclock.com
