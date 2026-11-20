# Konductor independent six-function roadmap receipt — 2026-11-19; v0.18.1 continuation 2026-11-20

## Identity and pins

- Original repository: aws-solutions/konductor
- Original HEAD: f5d184596378ae72ae531d80647548512c14cacf
- Observed at: 2026-11-20
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/5dbb51b2ddad0f29a84e10b4b5009c8989159165/assessments/ko/konductor.md
- Accepted assessment blob SHA: 01e846897ae499497ffd65a2be0d359187f2e866
- Accepted review ref: 09c34858ca2e704fb8572c91389a87255b1e1075
- Accepted reviewed at: 2026-11-18
- System in focus: One installed Konductor project-delivery cell using supported Kiro CLI or Claude Code, with the orchestrator, specialist agents, skills, SOPs, installation and diagnostics; host internals, upstream maintainers and AWS organization governance are outside.
- Index commit: 5dbb51b2ddad0f29a84e10b4b5009c8989159165
- Accepted Index catalog: https://github.com/opensiro/vsm-harness-index/blob/5dbb51b2ddad0f29a84e10b4b5009c8989159165/data/catalog.psv — row 1253; exact original repository and review_ref verified; prior index pin 59b99775d049a19fa29e7cc410a840bb5bf1ecc7 remains immutable history
- Profile / Methodology: 0.2.4 / 0.3.8
- Independent protocol: https://github.com/opensiro/upstream/blob/ae7a8a6d32b4da1c5fd97c6862821460503bf9e2/docs/ROADMAP_INDEPENDENT_RERUN.md (integrated Upstream v0.18.1 main, readback 2026-11-20)
- Receipt contract: proposal-gate
- Accepted VSM vector: S1=A · S2=A · S3=A · S3*=A · S4=? · S5=—
- Original source drift: Current original main f5d184596378ae72ae531d80647548512c14cacf after historical reviewed `review_ref`; original 2026-11-19 rerun pin 783603d485727654fa1ab51fefbd9d1169fefa86 retained in prior fork commit dbf51caf; regrading NOT_PERFORMED
- Source map scope: Current original main f5d184596378ae72ae531d80647548512c14cacf; installed role prompts, Kiro v2/v3 and Claude synth/install runtime strategies, deterministic doctor/manifest/update, skills/SOPs, tests and original Issues and actual PR statuses; no Kiro/Claude live model invocation

## Rights and authority

- Original license: Apache-2.0, root LICENSE.txt and NOTICE.txt; do not claim that code changes have been made.
- Original contributing policy: CONTRIBUTING.md asks for an original Issue before significant work, licensing confirmation and possible larger-change CLA; fork PR CI requires maintainer /codebuild_run(SHA). No specific mandatory AI prohibition or DCO found in the inspected root policy; this is a bounded finding, not a universal absence claim.
- Verified fork: opensiro-contributions/konductor, parent aws-solutions/konductor; opensiro/meta state on 2026-11-19 records ACTIVE / ALLOW (owner event 20261119T182226Z--owner-upstream58-active).
- Authority boundary: S4 may choose only preauthorized per-session, non-destructive routing/diagnostic alternatives; installation, permission elevation, user configuration, trust prompts, protected memory and source changes still require their actual user/parent decision. A model cannot grant itself this authority.
- Interest: original maintainers have an observed Kiro/Claude skill exposure issue in PR #312; explicit interest in this proposed S4 constructor NOT_STATED. OpenSiro interest is hypothesis research, not owner demand.
- Communication: no fork-public Issue/PR, original Issue/comment/PR, or product change authorized by this receipt.

## Existing work / overlap

- Track A shipped: https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/doctor.rs checks installation/runtime/config and reports diagnostics; https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/orchestration_mode.rs reads user-set auto/coordinator mode; https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/config.rs reads layered configuration; https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agents/konductor.agent-spec.json and https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/context/k-direct-work.md expose direct-work/delegation rules; https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/external-research/SKILL.md supports version-sensitive research. None alone demonstrates a deployed prospective S4→S3→later-outcome closure for host capability drift.
- Track A native active work: https://github.com/aws-solutions/konductor/pull/312 (OPEN, observed Kiro skill discovery failure and fixed declarations on an unmerged branch); https://github.com/aws-solutions/konductor/pull/303 (OPEN, SOP skill exposure); https://github.com/aws-solutions/konductor/pull/207 (OPEN, end of metrics stack) and https://github.com/aws-solutions/konductor/issues/301 (OPEN, per-turn attribution). These are separate first-party changes, not installed S4 closure. Current CLI README explicitly calls metrics a stub.
- Track A best low-cost alternative: manually inspect `konductor doctor`, use valid host-specific skill discovery, adopt PR #312's native fix when actually merged/released, and let the engineer manually select a supported workflow. This may be fully sufficient; that is the matched comparator.
- No invented rival controller or shipped metrics; the newer original HEAD and PR heads are distinct.
- Historical comparison is recorded only below, after this independent six-function target and verdict were selected.

## Function ownership

- S1 disposition: Historical A; installed model-backed developer/architect/QA roles and current direct-work agent produce code/research/test outcomes, https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agents/konductor.agent-spec.json; no unmet operational constructor selected.
- S2 disposition: Historical A; model-backed orchestrator coordinates writer handoffs, ownership and worktree modes, https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/delegation-protocol/SKILL.md, https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/context/k-orchestrator-shared.md; preserve mode-dependent scope, no mandatory S2 C.
- S3 disposition: Historical A; Konductor assigns current work and phase gates; deterministic evaluator enforces recorded constraints (https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agent-sops/k-full-sdlc.sop.md, https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/gate_eval.rs); constructor not selected because this is already supported decision ownership.
- S3* disposition: Historical A; separate adversarial k-developer passes and fresh k-architect checking can return corrective findings (https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agent-sops/k-adversarial-pull-request-review.sop.md); user-proposed proof receipts in original issue #72 are parallel native work, not automatic priority.
- S4 disposition: Historical ? (not negative); native external research and deterministic diagnosis exist but no verified installed feedback from prospective host capability change into a future S3 decision. Candidate first-party composeable S4 C path scoped to recurring host capability drift, not to ordinary one-task planning; P0.
- S5 disposition: Historical —; legitimate identity and rights remain with user/maintainer/host parent; user-scope confirmation fix was merged in original PR #299; no independent in-boundary S5 mandate is inferred. Deliberate parent authority for changing permissions is supported; claim of deliberate total S5 omission is UNKNOWN.

## Capability priority

- Repository-wide source map: Installed agent specs and routing prompts, full SDLC and adversarial review SOPs, diagnostic/config and synth/skill runtime, optional Kiro/Claude host modes, tests/CI and contributor policy; observed original PRs #299, #303, #312, #207 and original Issues #72, #176, #203, #301.
- Priority rationale: Optional per-installed-target future host compatibility is a bounded falsifiable S4 constructor research case; the 2026-11-19 skill visibility comparator is now fixed in merged original PR #312 (Kiro) and #303 (Claude), so that resolved task is not an outstanding user need. Shipped doctor/manifest and research skills may be reused for a different hypothetical later host interface retirement. S1/S2/S3/S3* accepted A and legitimate parent S5 remain intact. Maintainer preference NOT_STATED; proposal is neutral to product adoption.
- Target transition: S4=? -> S4=C
- P0: An opt-in S4 prospective compatibility review for exactly one recorded Konductor installation strategy (kiro-cli-v2, kiro-v3 or claude): official dated host skill/tool/SOP contract change -> installed .konductor/manifest strategy + current doctor --json readback -> discretionary retain / prepare parent-approved sandbox transition / escalate -> current Konductor S3 acknowledgement -> next supported specialist or SOP invocation and diagnostic outcome returned to same S4 reviewer. No generic updater, automatic host migration or tool-permission changes.
- P1 dependencies: Confirm target-scoped manifest strategy and source/release date and host version without guessing; where doctor lacks an observed capability probe use explicit UNKNOWN. Reuse the existing external-research + decision-research skills and Konductor routing/verification contract, plus minimal opt-in native skill/SOP and a bounded later-operation receipt. Require genuine user approval and k-developer ownership for any install, update, config, role or trust mutation; negative test denied/stale notice, unsupported host, missing next-run return.
- P2 optional: NONE — metrics PR #207 and related work are separate, not required for the S4 choice/feedback path.
- Proposed C construction: Small developer-composable opt-in compatibility-review skill in the existing Konductor skill distribution (not an always-on daemon): k-researcher reads official prospective Kiro/Claude change and records date/version/source; Konductor S4 reviewing agent compares it with the selected installed manifest strategy and current doctor result, then chooses among developer-authorized future options. S3 accepts/refuses a lawful sandbox trial under existing phase/role gates, with any persisted installation or permission action delegated to k-developer and explicitly approved by the parent. Later real agent/SOP invocation plus doctor result returns to the S4 reviewer to retain/revise/escalate. An unsupported or unobserved capability remains UNKNOWN.
- C sufficiency falsifier: A first-party merged host workflow or existing configured skill already supplies this complete official-future-notice -> discretionary bounded S4 choice -> S3-approved future operating effect -> returned actual invocation result loop, or the only change is a static warning/manual correction; such proof defeats a distinct new C constructor.
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Paired matched next-task runs in an explicitly configured Kiro-v2 or v3 target and Claude target, pinned original/host versions: prospective official change fixture, verify manifest scope and doctor --json, produce two lawful S4 alternatives, approve sandbox route through parent, invoke an actually supported existing specialist/SOP, collect and return outcome to S4. Negative stale/untrusted source, wrong strategy, refused privilege and absent feedback must not claim success. Compare with current native doctor/manual fix and merged #312/#303; native tests NOT_RUN.
- Validation state: NOT_RUN
- Proposal falsifier: If native manual/merged path solves the same future scenario with equal decision+return, no lawful agent-composable future choice exists, a direct S3/S4 return is not observed, or the design silently changes host/permission/user config, then abandon P0 without changing Index.

## Parallel contribution-on-top review

- Evaluation object: One future Kiro-v2/Kiro-v3/Claude installed-host interface deprecation and one specific recorded Konductor target, not resolved Kiro skill exposure PR #312, merged Claude SOP PR #303 or the historical AWS Toolkit issue #39.
- Existing-work overlap: Merged original #312 and #303 resolve observed skill/SOP availability defects. Current doctor/manifest/update cover present install health and manual transitions. Open original #231/#232 add workflow-host version diagnostics on unmerged branches and #285 rights constraints; none establish the entire prospective external change -> S4 decision -> S3 outcome -> later real run return loop. Native existing/manual path is the first falsifier, not an automatic veto.
- Our on-top contribution: Only a bounded, opt-in native compatibility research/choice-and-return contract on existing Konductor skills/orchestrator and selected manifest strategy, with host-specific official evidence and a real subsequent supported invocation result; no new control plane, automatic update, extra grade or per-run Upstream PR.
- Incremental benefit: HYPOTHETICAL: a developer may compose a prospective response to a future supported-host contract break and verify whether the later task still works, compared on the SAME specific host scenario with doctor/manual intervention. Neither real avoided breakage nor cost improvement has been demonstrated.
- Decision scope: GO for designing and testing this bounded S4 hypothesis only; not acceptance of a concrete patch, maintainer demand, Index regrade or any external publication.

## Implementation options

- Preferred: small optional skill plus model/diagnostic input and S3 trial protocol, in existing installed distribution; use https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/doctor.rs diagnostics as evidence, https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/context/k-direct-work.md for legitimate handoff and https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/persistent-memory/SKILL.md provenance rules. Keep user-level mode and install grants untouched.
- Simpler native control: keep the current diagnosis and manual specialist/skill selection; if no distinct later-run result emerges, do not build the new constructor.
- Source-bound future tests: https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/Makefile and https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/README.md describe `npm test`, `make test-py`, and `cd cli && make test` / `make lint` for applicable code changes, plus an actual configured Kiro/Claude smoke for the decision witness. Native tests NOT_RUN; runner behavior and results not invented.
- Attribution: original maintainers own #312/#303 code and merges, developer/user owns authorization, Index owns assessments; OpenSiro's proposal is neither a native PR nor accepted code.

## Specification and domain alternatives

- Profile 0.2.4 defines S4 as prospective external adaptation with two-way current S3 exchange; mere memory or docs is insufficient: https://github.com/opensiro/vsm-harness-profile/blob/main/PROFILE.md.
- A future methodology inquiry could ask whether user-driven host migration alone is parent S4 or external maintenance; no current Skills/Profile defect established.
- Independent lawful domain fork is optional only with new evidence and proper attribution; not P0.

## Cost experiment

- Cost status: NOT_MEASURED
- Matched comparator: two identical future Kiro/Claude capability-change tasks, one using baseline native doctor/manual choice and the other using the bounded S4 proposal, with equivalent rights, host versions, success criteria and logs. Record implementation, integration, added prompt/runtime overhead, tests, human interventions, correctness and maintenance. Do not infer savings from hypothetical outcomes.

## Delivery and publication

- Result: NEEDS_EVIDENCE
- Decision summary: GO — proposed C architecture source-informed and bounded; S4 closure, value and costs remain untested. Proposal-only, not shipping.
- Research disposition: NEEDS_EVIDENCE
- External issue: DRAFT — NOT PUBLISHED
- Public fork Issue: DRAFT — NOT PUBLISHED
- Persistence: fork-local opensiro/meta Human/AI/receipt refreshed after remote write/readback; existing original feature case preserved at its old immutable commit.
- Validation source: scripts/validate_capability_roadmap.py (structural only; native tests NOT_RUN).
- Historical comparison, consulted only AFTER independent P0 and GO: prior case at https://github.com/opensiro-contributions/konductor/blob/8975ba9f4165388c7ada9da4a8bf9caa6479880c/.opensiro/issues/aws-toolkit-adaptation-20261119/roadmap.md concluded NO_GO to an extra AWS toolkit-change S4 controller on original 05360b8. This fresh six-function rerun asks a DIFFERENT, narrower original-native installed-host adaptation question at 783603d485727654fa1ab51fefbd9d1169fefa86 and proposes GO + NEEDS_EVIDENCE; this is not evidence the AWS feature decision was wrong. The old NO_GO remains attributable and should not be overwritten as a claim about #39.
- Next: internal review of this case and real host paired tests; any public fork/original communication needs separate current-conversation exact text/destination approval, no outside publication here.

## v0.18.1 original-native continuation — 2026-11-20

**Same-case provenance, not a second independent first pass.** The 2026-11-19 v0.18.0 case was persisted at [dbf51caf](https://github.com/opensiro-contributions/konductor/commit/dbf51caf99521ffafe125a4cd5cb89ad61af137a), and the preceding *different evaluation object* AWS Toolkit NO_GO is preserved at [8975ba9f](https://github.com/opensiro-contributions/konductor/commit/8975ba9f4165388c7ada9da4a8bf9caa6479880c). On 2026-11-20 the independent source-first v0.18.1 refinement hypothesis was sealed in [#58 comment 7045300922](https://github.com/opensiro/upstream/issues/58#issuecomment-7045300922) before the previous fork-local dossier was opened. The v0.18.1 refinement is **not** another independent initial re-run, new Index grade or product decision.

### Current original-native reality and the old-case correction

- **SHIPPED on current original main:** [PR #312](https://github.com/aws-solutions/konductor/pull/312) merged; Konductor now declares the role skills needed by the single-writer Kiro agent. [PR #303](https://github.com/aws-solutions/konductor/pull/303) merged and adds Claude SOP skill loading. Older passages below saying these PRs were OPEN reflect the 2026-11-19 historical snapshot; they are **not current claims**. Reintroducing their narrow fixes is expressly out of scope.
- **Current installed target seam:** [manifest.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/install/manifest.rs) records strategy per selected target, including `kiro-cli-v2` / `kiro-v3` / `claude`. [runtime.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/install/runtime.rs) detects configured host markers, while [doctor.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/doctor.rs) checks present health; `doctor --json` is a diagnostic, not a future-change owner. [update.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/update.rs) offers a preview with `--dry-run` of managed Konductor files, **not an automatic Kiro/Claude host migration**.
- **OPEN work, not shipped:** [PR #231](https://github.com/aws-solutions/konductor/pull/231) includes Kiro workflow execution and doctor version reporting; [PR #232](https://github.com/aws-solutions/konductor/pull/232) adds Claude stages/version doctor. [PR #285](https://github.com/aws-solutions/konductor/pull/285) changes AWS MCP permission asks. Their PR bodies and current OPEN statuses were checked, but no merged future S4 loop is credited from an open branch.
- **First-party model owner:** existing [k-researcher](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agents/k-researcher.agent-spec.json) plus [external-research](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/skills/external-research/SKILL.md) can inspect official prospective host release notes and version constraints. [Konductor orchestrator](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agents/konductor.agent-spec.json) owns current specialist scheduling (S3) and existing verification. Proposed S4 is a **new composable bounded decision/return contract inside those native surfaces**. A host-version advisory alone is S1 research or diagnostics, not S4 closure.

### Track A ↔ Track B, exact missing C and falsifier

| Actual future task | Native Track A (what exists) | Minimum optional Track B (what is not established) | Disproof |
| --- | --- | --- | --- |
| A dated official Kiro or Claude future skill/SOP/tool contract retirement affects one installed strategy | External research, manifest, doctor and currently user-mediated install/update; #312/#303 already fix old exposures | Opt-in source-verified *prospective* notice-to-specific-strategy matching, with UNKNOWN when host capability cannot be observed | Existing installed supported path already composes that future matching and authorized variable choice |
| Decide before the next eligible engineering task | Current orchestrator's S3 and human-controlled role/permissions; manual update is available | Developer-composed S4 reviewer chooses **retain / parent-approved isolated test / escalate** and returns choice to S3; do not install/update autonomously | Only a fixed warning, no discretionary future choice, or parent rights unavailable |
| Learn whether the future choice worked | Native doctor checks present health; real specialist/SOP results exist in normal current-task verification | Explicit return of *actual next invocation* (selected host/skill, success/failure, doctor result) into S4 so it can revise or stop | Only a note with no actual later run, or the manual native path already delivers equivalent feedback |

**Current decision:** proposal-stage **GO / NEEDS_EVIDENCE**, conditional **S4=? -> S4=C**, **PLAN_ONLY / HYPOTHETICAL**. P0 is the complete native decision/action/feedback loop; P1 is legitimate source/version and rights-bounded return; P2 **NONE**. Not implemented, no product native runs, not measured, no external or public-fork Issue/PR. Any optional external proposal follows the exact publication-consent gate. Maintainers alone decide whether this belongs in Konductor; an existing repair is not proof of their final design intent.

**Negative tests needed before any adoption:** a stale or malicious release note cannot trigger tools; unsupported host strategy means UNKNOWN/hold; an unauthorized persistent install, permission or config change must be refused; if the next task was not actually run, S4 must not claim closure. Any first-party comparable complete C loop, including after #231/#232 merge, makes this separate P0 unnecessary. No self-approval and no S5 transfer.

**Status source:** [Human issue draft](issue.md), [AI native contract](constructor-sufficiency.md), this canonical receipt, and the attributed fork event. Structural validation is not semantic validation; code/host tests NOT_RUN, costs NOT_MEASURED, original maintainer publication NOT_PUBLISHED. Per merged Upstream reporting hygiene, no individual Upstream PR or Markdown run report.
