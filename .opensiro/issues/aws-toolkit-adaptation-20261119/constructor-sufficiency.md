# Konductor — S4 host-capability adaptation constructor sufficiency

**Human decision:** [issue.md](issue.md). **Canonical receipt:** [roadmap.md](roadmap.md). This is a technical companion, not another public Issue or current Index assessment.

**Target transition:** S4=? -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

## 1. Source and boundary

Pinned original: [aws-solutions/konductor@783603d485727654fa1ab51fefbd9d1169fefa86](https://github.com/aws-solutions/konductor/commit/783603d485727654fa1ab51fefbd9d1169fefa86), one installed multi-agent software-delivery cell. Included accepted Index [Konductor](https://github.com/opensiro/vsm-harness-index/blob/59b99775d049a19fa29e7cc410a840bb5bf1ecc7/assessments/ko/konductor.md) at 59b99775d049a19fa29e7cc410a840bb5bf1ecc7 / historical 09c34858ca2e704fb8572c91389a87255b1e1075 / blob 01e846897ae499497ffd65a2be0d359187f2e866, Profile 0.2.4, methodology 0.3.8. All historic grades/priority judgments belong to [roadmap.md](roadmap.md); avoid current-HEAD regrading.

The first-party installed agent and generated prompt/skill/SOP distribution is in scope, as are its installer/config/doctor support surfaces. Host Kiro/Claude internals, user permissions, contributor organization and upstream maintainer release work are not in-boundary S4 owners. Current supported single-writer and specialist modes must remain distinguishable.

## 2. Original-native Track A, capability and ownership

- **SHIPPED diagnostics, not a choice owner:** [doctor.rs](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/doctor.rs) checks source/runtime/manifest/config/index/telemetry/orchestration and emits warnings/failures. Proposed provider_model_access and role_allowlists checks are not implemented in the current source; do not credit them as a live capability inventory.
- **SHIPPED rights and modes:** [orchestration_mode.rs](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/orchestration_mode.rs) reads user-level `~/.konductor/config.yml` and distinguishes auto from coordinator; a model may not silently persist a different user mode.
- **SHIPPED source-defined host transformation:** [agent specs](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/agents/konductor.agent-spec.json), [synth spawn policy](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/konductor-rs/src/cli/synth/spawn_policy.rs), [delegation](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/delegation-protocol/SKILL.md) and [orchestrator rules](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/context/k-orchestrator-shared.md) bound which roles/tools can run.
- **SHIPPED research and provenance:** [external-research](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/external-research/SKILL.md) researches version-relevant official docs; [persistent-memory](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/persistent-memory/SKILL.md) protects user-origin entries; [workspace-skills](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/skills/workspace-skills/SKILL.md) supports provenance-aware procedure capture, not unlimited autonomous configuration changes.
- **NATIVE CHANGE OPEN, NOT SHIPPED:** [PR #312](https://github.com/aws-solutions/konductor/pull/312) documents 46 missing role skill declarations on Kiro and an observed different outcome on Claude; PR aims to expose declared skills. [PR #303](https://github.com/aws-solutions/konductor/pull/303) covers SOP skill invocation on Claude; [PR #207](https://github.com/aws-solutions/konductor/pull/207) completes a stacked usage-metrics feature but is OPEN, so `metrics` remains a CLI stub on 783603d485727654fa1ab51fefbd9d1169fefa86.
- **Other native work:** [#72](https://github.com/aws-solutions/konductor/issues/72) proposes reusable verification proof receipts (S3*), [#176](https://github.com/aws-solutions/konductor/issues/176) addresses trust index, [#301](https://github.com/aws-solutions/konductor/issues/301) addresses per-turn metrics attribution. These are not accepted S4 construction and should not be displaced.

Track A best comparator is manual `konductor doctor` + host-available skill selection + ordinary user-approved configuration/release changes. Do not introduce a new controller merely to reproduce PR #312.

## 3. Complete proposed Track B — S4-specific decision/authority/return loop

**Disturbance:** A subsequent Kiro/Claude host revision alters skill/SOP loading for a next task; #312 documents a concrete class. The scenario is OBSERVED at the original PR level; incremental OpenSiro benefit is HYPOTHETICAL.

**New first-party developer composition:** Add a small opt-in `host-capability-adaptation` installed skill and one routing trigger in the existing Konductor rules. Developer configures which supported host/skill alternatives may be trialed; no novel central agent, service, scheduler, registry or fixed AWS feature stack. Existing `doctor` and first-party skill registration provide diagnostics; where a necessary capability cannot be reliably observed, report unknown instead of hallucinating support.

**Decisive S4 owner:** A model-backed researcher/installed orchestrator running the specific prospective adaptation contract chooses between at least two lawful, source-backed next-task adaptations (e.g. retain working specialist path or route eligible future tasks through the explicitly supported alternative). Its decision must contain source, version, future consequence, counterargument and exact permissions.

**S3 relationship:** The current Konductor manager accepts, refuses or defers a particular trial based on available rights, phase and project commitments; it chooses the next permitted operating allocation. A random hook or deterministic doctor warning is *transport*, not the S4 owner. The S3 manager need not be replaced.

**Effect and feedback:** On the next eligible task the installed path actually invokes the approved agent/skill, records discovered capability and task/test outcome, and returns result to S4, which retains/revises/discards the proposal. The local bounded receipt preserves status and source without overwriting user memory or installing arbitrary content. No false successful decision without real next-task evidence.

**Authority:** The user retains S5 and approvals for permanent config, plugin installation, trust, permissions and repository modifications. Absent explicit allowed alternatives, return `NEEDS_USER_DECISION`/halt. A fallback to an unsupported skill or an untrusted remote package is never an allowed action. For Kiro and Claude, mode-specific tool allowlists remain unchanged.

**C sufficiency reasoning:** This is a first-party developer-composable S4-specific decision path that links environmental prospective distinction to S3 trial and actual operating return, rather than static feature detection, maintenance backlog or memory. It is a *proposed constructor*, not built S4=C. It fails if a single native warning/manual fix yields identical value with less complexity, or if no true prospective decision and later feedback exists.

## 4. Ports and lowest-cost alternative

| Required port | Reused original | Minimal missing construction |
| --- | --- | --- |
| Host capability evidence | `doctor`, synth skill registry, host-specific install info | Explicit versioned skill-availability observation with UNKNOWN; no assumptions about unmerged PR #312 |
| Future choice ownership | k-researcher, orchestrator, external-research | Optional adaptation contract with two lawful alternatives and prospective next-task impact |
| Legitimate S3 handoff | Direct-work / delegated orchestration, SOP gates | Accept/refuse/defer trial, reason and exact next-task routing under user's rules |
| Operational act and return | Installed specialist invocations, first-party task result and evidence | Later-run receipt: actual skill used, result, failure, rollback, S4 reevaluation |
| Safety and parent | User-owned orchestration mode, provenance guards, confirmation SOP | Prevent non-consensual persistent writes, privileges, install and trust changes |

No fixed multi-port numeric target is inferred from Paperclip or earlier historical cases. Minimal native files are the new opt-in installed skill and narrowly bounded invocation/receipt plumbing, with any code diagnostics changes only if existing `doctor` cannot supply the necessary verified input.

## 5. Future source-native acceptance; results NOT_RUN

| Proposed native case | Source-supported input / future command | Expected first-party effect and return | Falsifier |
| --- | --- | --- | --- |
| Cross-host skill drift | Fixture with Kiro skill unavailable vs Claude known available, build/synth and permitted host smoke; `cd cli && make test` if CLI changed | S4 selects among allowable future routes; S3 trial later uses actual supported path and returns outcome | Only reports a warning, no decision or later effect |
| Alternative and feedback | Two explicitly authorized possible routes on same task | Different lawful S4 choices drive distinct permitted next-run action and failure/success receipt | Hard-coded route or unverified benefit |
| Parent/negative boundary | Missing required skill, invalid source, no consent for mode/config/installation | No privilege or persistent setting changes; halt or user decision | Unapproved mutation or fake successful fallback |
| Matched original baseline | Same host/task after native `doctor` and manual fix or merged #312 behavior, aligned rights/results | Incremental result outweighs engineering and runtime complexity | Native baseline equally succeeds with lower complexity |

Relevant original commands are documented in [Makefile](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/Makefile) and [cli/README.md](https://github.com/aws-solutions/konductor/blob/783603d485727654fa1ab51fefbd9d1169fefa86/cli/README.md); `npm test`, `make test-py`, `cd cli && make test`, `cd cli && make lint` depend on actual touched files. **None executed.** Code-structure review, remote source links and a case validator cannot prove observed S4 closure. Runtime cost NOT_MEASURED.

## 6. Verdict, falsifier, provenance and next gate

**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

A coherent, rights-bounded *possible* S4 constructor is described using pinned original-native code; no automatic main-branch change, maintainer acceptance, external issue, actual new VSM grade, or achieved outcome is claimed. Essential future falsifier: native manual doctor/#312 solves same later task with equal or better verified outcome, or candidate lacks S4 owner, S3 exchange, valid permissions or operating return. If so, discard P0.

**Historical comparison after independent decision:** [Earlier AWS controller NO_GO](https://github.com/opensiro-contributions/konductor/blob/8975ba9f4165388c7ada9da4a8bf9caa6479880c/.opensiro/issues/aws-toolkit-adaptation-20261119/constructor-sufficiency.md) evaluated a different #39 adaptation need; it was not used to choose this host compatibility question. The old negative remains valid for its prior scoped object unless separate contrary evidence arises.

**Publication:** No original or fork public Issue/comment/PR; only internal fork metadata and (separately) internal OpenSiro coordination PR permitted. Exact current-conversation external-publication approval would be required to send any maintainer-facing text. Rights: Apache-2.0, possible CLA for larger contributions, fork CI maintainer approval required. AI-assisted analysis, no live tests or savings claim.
