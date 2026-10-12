# Reflection: jackwasey_icd

**Pattern.** Declining in cycles. Intense work in 2014-2016 and again 2018-2020 (peaks of ~200 commits/month), a short 2020-2021 tail, then 36 zero-commit months from 2021-12 to 2024-11. 36 authors, but the project is dominated by Jack Wasey. 3 gaps of 3+ months.

**Longest gap.** The last real work before the gap (March 2021) is a string of CRAN/R-hub check commits: "rhub simpler checks for speed", "rhub wip", "drop some data-building dependencies, so xml2 and RODBC can be removed from Suggested", "don't build package with data development tests". After that only a CodeQL workflow file (2021-11-20). During the gap four issues were opened (E-valued ICD-10 codes returning wrong descriptions, expand_range failing, two install problems); three are still open with no maintainer response. The GitHub description now begins "*New maintainer/owner needed*". Together these make the gap easy to interpret: a single maintainer burned out or moved on after a hard CRAN-check cycle, and nobody picked the package up.

**Recovery.** Partial. In WoC data only one commit follows the gap ("Update README.md", 2024-12-20). GitHub shows a real burst on 2026-09-14 by the same author: PR #219 "fix-modern-r-check" replaces Travis and AppVeyor with GitHub Actions, adds an R-hub v2 workflow, swaps sprintf for snprintf, fixes S3 method warnings and removes dead code. That is a modernisation pass to make the package check cleanly on current R, not new features. No new maintainer has appeared.

**Current status.** Active by the six-month rule (last GitHub commit 2026-09-14), but effectively a one-person package looking for an owner.
