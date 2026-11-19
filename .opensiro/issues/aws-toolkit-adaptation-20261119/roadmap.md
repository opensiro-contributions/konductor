# Konductor independent six-function roadmap receipt — 2026-11-19

## Identity and pins

- Original repository: aws-solutions/konductor
- Original HEAD: 783603d485727654fa1ab51fefbd9d1169fefa86
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/59b99775d049a19fa29e7cc410a840bb5bf1ecc7/assessments/ko/konductor.md
- Accepted assessment blob SHA: 01e846897ae499497ffd65a2be0d359187f2e866
- Accepted review ref: 09c34858ca2e704fb8572c91389a87255b1e1075
- Accepted reviewed at: 2026-11-18
- System in focus: One installed Konductor project-delivery cell using supported Kiro CLI or Claude Code, with the orchestrator, specialist agents, skills, SOPs, installation and diagnostics; host internals, upstream maintainers and AWS organization governance are outside.
- Index commit: 59b99775d049a19fa29e7cc410a840bb5bf1ecc7
- Accepted Index catalog: https://github.com/opensiro/vsm-harness-index/blob/59b99775d049a19fa29e7cc410a840bb5bf1ecc7/data/catalog.psv — row 1253, harness_id konductor, exact repository and review_ref matched.
- Profile / Methodology: 0.2.4 / 0.3.8
- Independent protocol: https://github.com/opensiro/upstream/blob/be03ced5ed5d3b7210762df612dc4b3f452c1a73/docs/ROADMAP_INDEPENDENT_RERUN.md (v0.18.0 main).
- Receipt contract: proposal-gate
- Accepted VSM vector: S1=A · S2=A · S3=A · S3*=A · S4=? · S5=—
- Original source drift: 21 commits after historical review_ref, including orchestration prompt, SOP, skill exposure and install/CLI changes; prior Index labels are frozen, not current-HEAD grades.
- Source map scope: default main 783603d485727654fa1ab51fefbd9d1169fefa86; first-party installed prompts, skills, SOPs, CLI and tests/CI plus original Issues/PR heads reviewed. No live Kiro/Claude model run was executed.

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
- Priority rationale: S4 wins only as a bounded experimental constructor because PR #312 documents a real environment/host drift with differing operational outcomes, shipped doctor/skill/routing primitives can be reused, S3 accepts/rejects trial routing, and user S5 rights can be preserved. S1/S2/S3/S3* are already A, and S5 belongs to parent. This does NOT assert that historical S4=? is absent or defective.
- Target transition: S4=? -> S4=C
- P0: Developer-composable host-capability adaptation loop for supported Kiro/Claude sessions; prospective capability evidence → model-backed candidate choice within a preapproved alternatives envelope → S3 accepts/rejects a per-session trial route → next actual specialist invocation → diagnostic/result feedback → retained bounded decision receipt, or honest halt.
- P1 dependencies: Provide versioned capability observation from currently shipped `doctor`/skill registration (including failure and ambiguity); define permitted per-session routing alternatives without changing user-level orchestration.mode; hook S4 advice to S3 trial and actual result evidence; validate on both supported hosts with negative permission tests. No automatic install/source mutation.
- P2 optional: Reevaluate whether post-merge metrics #204–207 adds a useful cost observation only if evidence later supports it; not required for P0 and never pretend open PR code is shipped.
- Proposed C construction: One opt-in installed host-compatibility adaptation skill/contract called by Konductor when the selected host exposes a capability mismatch; k-researcher/agent mode chooses between source-verified supported fallback routes and explicitly logs uncertainty; current Konductor S3 may trial only allowed alternative on a subsequent task, collect real success/failure and return it to the adapting owner for revise/retain/escalate. Developer can compose the allowable alternatives and observation policy. On incompatible capability or missing rights, halt or ask the parent.
- C sufficiency falsifier: If baseline manual doctor/skill selection or merged PR #312 already resolves the matched future task just as well, or proposed skill merely issues a static recommendation without a lawful variable choice, S3 action and later evidence, additional S4 C construction is not qualified.
- Scenario basis: OBSERVED
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Execute paired Kiro and Claude test tasks with the same pinned host capability difference: evaluate two legal routes, capture S4 option/rights, S3 acknowledgement and the next run's actual skill/result; include absent skill, invalid authority and rollback/stop; compare baseline native manual response. NOT yet executed.
- Validation state: NOT_RUN
- Proposal falsifier: Any of no independent prospective distinction, host-invalid adaptation, unapproved persistent mutation, absent S3↔S4 return, or no incremental outcome over native baseline defeats this P0 even if static tests pass.

## Parallel contribution-on-top review

- Evaluation object: One possible first-party future-proof host capability adaptation constructor for an installed Konductor cell, not a feature request to port AWS skills, and not the earlier #39 historical evaluation object.
- Existing-work overlap: Current diagnosis, manually selected orchestration, existing skill research, PR #312 (OPEN) and #303 (OPEN) already address their specific tool/skill incompatibilities. They do not show a complete prospective decision→S3 trial→future operational feedback loop.
- Our on-top contribution: Extend only the original-native installed skill/routing surfaces with a developer-composable, rights-bounded capability-drift decision/return contract; reuse doctor/config/skills, do not invent a standing service, independent scheduler or universal S5.
- Incremental benefit: HYPOTHETICAL reduced silent skill-availability failures on *later* tasks and auditable adaptation, conditional on a matched host cross-mode test. No user demand, cost reduction or improved quality is established.
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
