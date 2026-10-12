# Reflection: soft-matter_trackpy

**Pattern.** Declining into long-term maintenance. The particle-tracking library had most of its development in 2012-2016 (peaks around 120 commits/month), a last large spike in 2018-01, and single-digit months since 2019 with many zeros. 68 authors. 5 gaps of 3+ months; the longest is 2020-09 to 2021-01 (5 months).

**Longest gap.** Just before the gap (August 2020) an outside contributor, Maxim Ivanov, submitted several PRs (refactor into a ParticlesLocator helper, fix VisibleDeprecationWarning, update pandas.testing imports). The WoC records show them as CI test merges, and they were only merged in 2021-02 (#632). Meanwhile about eight user issues arrived during the gap (3D images, sub-pixel bias, ghost particles), several still open. The maintainers were simply not committing; no message or issue gives a reason, so the gap is only moderately interpretable, but the picture of a mature library with limited maintainer time is clear.

**Recovery.** Yes, as repair work. On 2021-02-13 Casper van der Wel moved CI from Travis to GitHub Actions ("Transition to Github Actions", "No numba on Py3.9", "Fix conda builds"), fixed NumPy 1.20 and SciPy 1.5 deprecations, dropped Python 2 (merging hugovk's PR #619) and merged the pending contributor PRs. A user then asked for a release (issue 2021-03-17). The same maintainers (van der Wel, Nathan Keim) did the recovery, prompted by the ecosystem breaking the test suite.

**Current status.** Active (last GitHub commit 2026-06-29). Recent commits are Nathan Keim merging small PRs from outside contributors (a "spiff" correction feature, docstring and axis-label changes) and a fix for complex eigenvalues under numpy 2.5.
