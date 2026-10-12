# Reflection: tryolabs_norfair

**Pattern.** Declining. The tracking library arrived with 243 commits in 2020-08 (its public release), had a second large burst of 205 commits in 2022-07, and has been in small-maintenance mode since 2023 (mostly 0 to 10 per month). 65 authors in WoC. There is no gap of 3+ months; the longest zero stretch is two months, 2021-08 to 2021-09.

**Longest gap.** Too short to count as inactivity, so the gap reason is recorded as "N/A active Project". Around it: before, version 0.3.1 was released with DOI and citation instructions (Alan Descoins, 2021-07-29) after a YOLOv5 demo bug fix; after, 2021-10 adds support for storing past detections on TrackedObjects (PR #74, joaqo), then a user fix and a Dependabot pillow bump in 2022-01. A two-month pause right after a release is normal.

One data note: many Norfair commits appear twice in WoC with different SHAs (for example both "Version bump to 0.3.1" entries), which looks like rebased copies and inflates the WoC count (1,452) against GitHub's (~704).

**Recovery.** Not applicable; the project never stopped, it slowed.

**Current status.** Active, barely. The last GitHub commits are a v2.3.0 maintenance release on 2025-04-30 by javiber (relax the rich requirement, poetry lock, update GitHub Actions runner), which clears the 2025-04-01 cutoff by one month; before that the previous commit was 2024-07-27.
