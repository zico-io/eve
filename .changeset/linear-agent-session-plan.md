---
"eve": patch
---

`updateLinearAgentSession` now types `plan` as an array of `LinearAgentPlanStep` (`{ content, status }`), matching Linear's API, so plans render in Linear agent sessions without casting or patching eve.
