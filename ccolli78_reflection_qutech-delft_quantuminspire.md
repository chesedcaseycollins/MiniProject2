# Reflection: qutech-delft_quantuminspire

**Pattern.** U-shaped. The SDK peaked in early 2019 (54 commits in 2019-03), ran low through 2020-2022 (mostly under 15 per month), then climbed steadily from 2023 to a new high of 57 in 2025-01. 50 authors. 1 gap of 3+ months: 2019-12 to 2020-03 (4 months).

**Longest gap.** Every commit carries a Jira ticket id, so the messages describe tasks, not reasons: before the gap "[DEM-1186] stripping spaces and tabs from qasm", "[DEM-1194] Full state projection" (QFer) and "fixing a broken test" (qSaevar). One PR just before, "[DEM-1183] Offboard team member" (2019-10-25), shows the team shrinking. Between 2019-11-19 and 2020-04-03 no PRs or issues were created at all. There is no stated cause; the most plausible reading is a small company team with other priorities over that winter. This gap was hard to interpret because the ticket-style messages carry no narrative.

**Recovery.** Yes. April 2020 brings a burst of ticketed fixes ("[DEM-1399] fix for unsupported cxx gate", "[DEM-1185] Result generates nice error"), a citation notice in the README, hardware-backend support and the 1.2.0 release PR (2020-04-17), all by the same developer (QFer) plus Pieter Eendebak. The later rise from 2023 comes from new people: the latest commits are by Nischal Sehrawat with a new "[QI2-xxxx]" ticket prefix, which suggests work for a second-generation Quantum Inspire platform.

**Current status.** Active (last GitHub commit 2026-09-25). Seven of the last ten commits are Dependabot version bumps; the human commits are a fix for job submission to offline backends and a poetry version fix.
