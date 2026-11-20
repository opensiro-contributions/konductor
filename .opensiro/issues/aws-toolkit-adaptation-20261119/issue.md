# Konductor — host capability drift S4 constructor (OpenSiro independent roadmap)

**PLAN_ONLY · v0.18.1 native-specific same-case refinement · proposed GO · research NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**

**One-sentence proposal:** For one installed Kiro-v2/Kiro-v3/Claude Konductor manifest strategy, compose an opt-in S4 reviewer that matches an official *future* host contract change to the actual installation, chooses among user-authorized retain/test/escalate options, and learns from the next real specialist/SOP outcome; no automatic host or permission change.

**Canonical decision receipt:** [roadmap.md](roadmap.md).
**AI technical companion:** [constructor-sufficiency.md](constructor-sufficiency.md).
**Target transition:** S4=? -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

## Starting point — accepted historical Index

**Not a current source regrade:** `S1=A · S2=A · S3=A · S3*=A · S4=? · S5=—`. [Accepted assessment](https://github.com/opensiro/vsm-harness-index/blob/59b99775d049a19fa29e7cc410a840bb5bf1ecc7/assessments/ko/konductor.md) at Index 59b99775d049a19fa29e7cc410a840bb5bf1ecc7, blob 01e846897ae499497ffd65a2be0d359187f2e866, review_ref 09c34858ca2e704fb8572c91389a87255b1e1075, reviewed 2026-11-18, Profile 0.2.4 / Skills methodology 0.3.8. [Current original](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/README.md) pinned 783603d485727654fa1ab51fefbd9d1169fefa86 (21 commits later). Accepted status `included` and exact catalog row 1253 checked independently.

**System in focus:** Installed project-delivery cell of Konductor roles, skills, SOPs, CLI and diagnostics under Kiro CLI / Claude Code. Host internals, maintainer organization and AWS governance excluded. Current source reviewed across runtime/API, configuration, operating modes, tests/CI, docs and contributor policies.

| Function / role | Historical | Current source-backed owner and closure | Candidate priority |
| --- | --- | --- | --- |
| **S1 · Operations** | A | [Developer and related specialist roles](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agents/konductor.agent-spec.json) act on engineering work; direct-work mode also supported. | DEFER: no arbitrary replacement of operational agents. |
| **S2 · Coordination** | A | [Delegation and file ownership](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/delegation-protocol/SKILL.md) constrain conflicting writers; model-backed orchestrator selects split/sequence. | DEFER: existing coordination, optional modes. |
| **S3 · Current management** | A | [Full SDLC](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agent-sops/k-full-sdlc.sop.md) governs assignments/gates, [gate_eval](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/gate_eval.rs) enforces recorded states. | DEFER: avoid duplicate current manager. |
| **S3* · Independent review** | A | [Separate generators and fresh checking](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agent-sops/k-adversarial-pull-request-review.sop.md) return independent findings. | DEFER: native issue [#72](https://github.com/aws-solutions/konductor/issues/72) exists, not S4. |
| **S4 · Future adaptation** | ? | [External research](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/external-research/SKILL.md) and [doctor](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/doctor.rs) provide signals; complete forward decision/return not verified. | P0: qualified *proposed* C constructor, not an assumed absent current S4. |
| **S5 · Identity/policy** | — | User/parent owns ultimate scope and permissions; [original merged #299](https://github.com/aws-solutions/konductor/pull/299) requires genuine user confirmation. | NO_TARGET: parent boundary; no agent S5 mandate. |

**Why P0:** [Original open PR #312](https://github.com/aws-solutions/konductor/pull/312) describes an observed Kiro-versus-Claude skill availability difference, not an imagined requirement. The native direct fix and manual skill selection may already suffice; the independent hypothesis adds only a prospective, bounded choice-and-return loop. Other five functions have more directly adequate/legitimate owners or no authorized new C need. S4 uncertainty is not an asserted defect. Contributor interest: NOT_STATED; maintainer interest in fixing the specific Kiro skill mismatch is evidenced by #312, but interest in this additional constructor is not.

## Selected S4 constructor and native alternatives

**Environmental disturbance:** A supported host version/config changes discoverable skills or SOP availability before a later engineering task. The native baseline is a user running `konductor doctor`, checking skill availability, selecting a supported path, and applying the eventual targeted #312 fix if it merges; no new controller is assumed needed.

**Proposed developer-composable owner (P0):** The installed cell optionally invokes an S4 capability-adaptation skill with a versioned observation from `doctor` or the host skill registry. The model-backed k-researcher/agent selects between at least two source-supported, developer-allowed alternatives (e.g. keep known working role/path vs route the next eligible task to another available supported mode) and cites actual host compatibility. Konductor's S3 accepts/rejects a per-session trial under user policy, receives the next specialist's actual result, and returns success/failure to the S4 decision receipt to retain, revise or escalate. No unattended install, user config edit or new tool permission is granted.

| C-sufficiency link | Track A present/native | Track B missing/proposed |
| --- | --- | --- |
| External observation and alternatives | [doctor checks](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/doctor.rs), [external research](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/external-research/SKILL.md), concrete [#312](https://github.com/aws-solutions/konductor/pull/312) branch fix | An opt-in prospective host-capability evidence contract and choice among lawful future-compatible paths |
| Decision ownership and rights | [orchestration mode](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/orchestration_mode.rs) is user-owned; agent and skill registry exist | Explicit composition envelope for per-session S4 options; preserve parent rights, record why each option is permitted |
| S3 dialogue and future feedback | [orchestrator](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agents/konductor.agent-spec.json) and [SOP gates](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agent-sops/k-full-sdlc.sop.md) run current tasks | S3 accepts/refuses trial, next actual operating result returns to S4 receipt, rollback or halt when missing evidence |

**Track A at 2026-11-19 observation:** PR #312 and #303 were then OPEN for Kiro role-skill exposure and Claude SOP availability, respectively; both are now MERGED on current original main. Separate [PR #207](https://github.com/aws-solutions/konductor/pull/207) and [issue #301](https://github.com/aws-solutions/konductor/issues/301) concern usage metrics; CLI `metrics` is a stub at current main. No imagined merged feature or API.

**Falsifier:** If ordinary diagnostics/manual selection or #312 already handles the matched future task equally, if the model only repeats static advice, or if no lawful S3→future-task→S4 feedback exists, drop P0 and keep native alternatives.

## Priorities, tests and rights

**P0:** Source-native S4 host-capability decision→S3 trial→future-result adaptation loop, not a new standalone controller or generic future scanner.

**P1:** Validate actual supported Kiro/Claude capability evidence, lawful fallback alternatives, S3 return/rollback, negative user-rights and unsupported-mode behavior. Product behavior NOT_RUN; source review only.

**P2:** Optional post-merge usage metrics relevance check; not required and not treated as shipped.

**Future positive test:** With a pinned Kiro skill inaccessible but Claude counterpart available, choose between two permitted operating alternatives, execute next task and record S3/S4 feedback; compare with native manual response.

**Future negative test:** A missing tool, untrusted source, or ungranted install/config right must halt or ask the user, without silent user configuration, role file, or protected memory mutation.

**Validation state:** NOT_RUN. No original model runs, Kiro/Claude host tests, native unit suite, cost experiment or independent maintainer validation performed. **Cost status: NOT_MEASURED.** Compare same task, same host rights and objective across native/manual and proposal, counting engineering and runtime costs.

## Historical comparison and bounded outcome

The previously stored [AWS toolkit adaptation case](https://github.com/opensiro-contributions/konductor/blob/8975ba9f4165388c7ada9da4a8bf9caa6479880c/.opensiro/issues/aws-toolkit-adaptation-20261119/issue.md) had **NO_GO** to a different extra AWS-change S4 controller under native [#39](https://github.com/aws-solutions/konductor/issues/39). This source-first six-function re-run independently selected host-compatibility drift rather than importing that old target. **The new GO is not a reversal of the old AWS decision or a new Index grade.** The stable case folder retains historical identity/provenance; original old commit remains accessible.

**Decision / handoff:** **Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

Complete design is in [constructor-sufficiency.md](constructor-sufficiency.md) with [receipt](roadmap.md). Architecture hypothesis is source-grounded; benefit and closure remain unverified. Before code: test matched native alternative, preserve parent rights and ask maintainer for exact external-publication consent if any new outside contact is contemplated.

**Rights:** Apache-2.0 source with NOTICE, original [CONTRIBUTING](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/CONTRIBUTING.md) asks for significant-feature discussion, licensing confirmation and possible larger-change CLA. Owner metadata is ACTIVE / ALLOW for internal research and fork metadata, **not** original/fork public Issue/PR approval. This document is DRAFT — NOT PUBLISHED; AI assistance disclosed. No native tests, grade change, PR to original or measured cost saving claimed.


## 2026-11-20 · v0.18.1 native-specific same-case amendment

**Current original [main@f5d184596378ae72ae531d80647548512c14cacf](https://github.com/aws-solutions/konductor/commit/f5d184596378ae72ae531d80647548512c14cacf)**; accepted Index remains [included@5dbb51b2ddad0f29a84e10b4b5009c8989159165](https://github.com/opensiro/vsm-harness-index/blob/5dbb51b2ddad0f29a84e10b4b5009c8989159165/assessments/ko/konductor.md), blob 01e846897ae499497ffd65a2be0d359187f2e866; review ref 09c34858ca2e704fb8572c91389a87255b1e1075; 2026-11-18 Profile 0.2.4 / Skills 0.3.8. The six-row table above is the **historical accepted** six-function classification, not a new score. Its original file links are the frozen 2026-11-19 observation, updated source-native details live in the [receipt](roadmap.md) and [AI contract](constructor-sufficiency.md).

**What is already solved:** [PR #312](https://github.com/aws-solutions/konductor/pull/312) and [#303](https://github.com/aws-solutions/konductor/pull/303) are **MERGED**. Their concrete Kiro skill visibility and Claude SOP loading corrections should be reused; the earlier draft's OPEN labels were historical. [#231](https://github.com/aws-solutions/konductor/pull/231) and [#232](https://github.com/aws-solutions/konductor/pull/232) are **OPEN** native workflow/host-version work, not an already shipped S4 feedback loop.

**Proposed operator outcome (hypothetical):** before a *future* Kiro or Claude skill/SOP/tool-interface retirement, the developer enables an optional review for one installed `kiro-cli-v2`, `kiro-v3` or `claude` strategy recorded in `.konductor/manifest`. Konductor's model-backed S4 reviewer verifies an official dated upstream notice against that strategy and present `doctor --json` status, proposes **retain / test after explicit approval / escalate**, then receives the next real supported specialist/SOP invocation and diagnostic result from current S3. This does **not** migrate hosts, change config, grant tools or replace the Konductor orchestrator.

**Track A:** present diagnostics, managed manifests, manual transitions, merged native fixes. **Track B:** only the *missing* optional official-future-evidence → bounded model choice → parent-approved S3 trial → later observed outcome return. **Falsifier:** existing or soon-merged host implementation demonstrates this same complete decision and feedback for that exact future task, or no legal discretionary alternative exists.

**Priorities:** P0 this one native prospective host-strategy decision and return; P1 trustworthy source/version/permission and subsequent real-run evidence; P2 NONE. **Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Not proven:** no implementation, Kiro/Claude smoke, benefit measurement or native test run. Public fork/original Issue and PR **NOT PUBLISHED**; maintainer makes the product adoption decision. Full host-specific positive/negative tests and source pins are in [constructor-sufficiency.md](constructor-sufficiency.md). This is the same `aws-toolkit-adaptation-20261119` case folder with attributed history, **not** a new independent rerun or reversal of the earlier different AWS Toolkit NO_GO.
