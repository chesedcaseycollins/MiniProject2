# Reflection: oxfordcontrol_cosmo.jl

**Pattern.** Declining. The Julia solver was developed heavily in 2018-2020 (up to 97 commits/month), then dropped to a trickle from 2021 with occasional spikes (2024-04). 31 authors. 2 gaps of 3+ months; the longest is 2023-11 to 2024-03 (5 months).

**Longest gap.** The commits before the gap (July to October 2023) are almost all by people outside the core team: Benoit Legat removing VectorOfVariables and LessThan support and replacing PSDTriangle in the MathOptInterface wrapper (#181, #182), Oscar Dowson fixing MOI.TimeLimitSec, then Documenter.jl builds and a CompatHelper bot PR. The maintainers (Michael Garstka, Paul Goulart) made no commits in this period. Two issues from September 2023 were closed, so the repo was not ignored, but nobody was driving it. I read the gap as low maintainer attention on a mature package; no message states a reason, so it is only moderately easy to interpret.

**Recovery.** Yes, modestly (52 commits after). It starts with Paul Goulart's crash fix "force include diagonal in aggregate sparsity" (PR #187, 2024-04-14), then on 2024-05-04 Michael Garstka adds documentation sections, a reference to examples, a how-to-develop guide and bumps the version to 0.8.9. The recovery is the same maintainers doing a documentation and release pass.

**Current status.** Active. GitHub shows version bumps 0.8.10 (2026-05), 0.8.11 (2026-07) and 0.8.12 (2026-10-05) with small fixes (a stray println, a liblapack reference) and an external MOI refactor PR (#198). The project is in steady low-volume maintenance.
