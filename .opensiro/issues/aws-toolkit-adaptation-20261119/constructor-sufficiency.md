# Konductor — source-native S4 prospective host construction technical contract

**Canonical storage:** `opensiro-contributions/konductor@opensiro/meta:.opensiro/issues/aws-toolkit-adaptation-20261119/constructor-sufficiency.md`.
**Level 1 / Human decision Issue:** [issue.md](issue.md).
**Canonical decision receipt:** [roadmap.md](roadmap.md) owns the accepted six-function vector, original/Index pins, S4=? -> S4=C hypothesis, P0/P1/P2 and GO / NEEDS_EVIDENCE; this technical file does not regrade.
**Stage:** PLAN_ONLY / HYPOTHESIS → PROPOSAL-STAGE → potential future VALIDATED only after first-party evidence. **DRAFT — NOT PUBLISHED**; no product code or native test execution.

## 1. Function-specific construction boundary and methodology checks

**Source and mode boundary:** Original [aws-solutions/konductor@f5d184596378ae72ae531d80647548512c14cacf](https://github.com/aws-solutions/konductor/commit/f5d184596378ae72ae531d80647548512c14cacf), observed 2026-11-20. Focus one installed Kiro CLI v2/v3 or Claude Code project-delivery cell using [agents](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agents/konductor.agent-spec.json), native skill/SOP distribution, CLI manifest/runtime/doctor, direct vs coordinator modes and current S3. Original host internals, parent user permissions, AWS organizational policy and test scaffolding are not silently promoted to in-cell actors. Historical accepted Index/provenance are pinned in [roadmap.md](roadmap.md), not updated here.

**Target transition:** S4=? -> S4=C

**Six-function dependencies (S1/S2/S3/S3*/S4/S5):** [Receipt](roadmap.md) distinguishes existing S1 specialist/SOP task execution, S2 supported agent/writer handoff, S3 current orchestrator allocation and gates, S3* independent review, S4 future-environment research but unverified decision-to-return closure, and S5 user/parent ownership of ultimate permissions. Proposed S4 must exchange a proposal and later operating evidence with S3, not replace S1/S2/S3, invent S3* evidence or grant itself S5.

**Function witness:** HYPOTHETICAL dated official *future* skill/tool/SOP contract deprecation for a recorded `.konductor/manifest` strategy. A developer optionally composes a model-backed S4 reviewer using [k-researcher](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agents/k-researcher.agent-spec.json) plus [external-research](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/skills/external-research/SKILL.md); it chooses among parent-approved retain / isolated trial / escalate. Current Konductor S3 accepts/refuses a specific next-task route, and actual next specialist/SOP result plus diagnosis returns to S4 before it may retain/revise the future choice.

**Counterfactual owner test:** With only `doctor`, a fixed warning or deterministic installed manifest, no model-backed S4 actor selects a source-grounded *future* alternative or learns from a subsequent real task. If manual/first-party current flow already makes the same discretionary future choice with actual later feedback, the extra constructor is not needed; if no lawful alternative exists, the proposal fails.

**Possible methodological negative control:** Parent-held permission/install/trust changes and a deliberate choice to keep future host adaptation manual are legitimate boundaries. Do not infer intentional global S5 absence from lack of an agent; no Profile/Skills change is justified unless actual evidence demonstrates a methodology conflict.

**Contributor / maintainer priorities:** Original [#312](https://github.com/aws-solutions/konductor/pull/312) and [#303](https://github.com/aws-solutions/konductor/pull/303) show merged *specific* Kiro/Claude skill/SOP fixes, not interest in this new prospective loop. Explicit maintainer support for S4 construction `NOT_STATED`; OpenSiro research motive is attributable to this independent same-case exercise.

## 2. Source-pinned baseline and parallel native Track A / on-top Track B

**Original native workflow:** In a supported installed project, [manifest.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/install/manifest.rs) records `kiro-cli-v2`/`kiro-v3`/`claude` strategy; [runtime.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/install/runtime.rs) distinguishes host markers; [doctor.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/doctor.rs) reports *current* diagnostics; existing [Konductor orchestrator](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agents/konductor.agent-spec.json) hands normal work to supported specialists and SOPs. An engineer currently interprets notices and approves any durable host/config action.

**Closest existing solution:** Baseline `konductor doctor --json` + manual official release review + existing roles/SOPs and user-approved supported changes. [update.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/update.rs) `--dry-run` previews Konductor-managed files; it does not migrate Kiro/Claude hosts.

**Relevant original Issues/PRs:** SHIPPED on observed 2026-11-20 original main: Kiro skill declarations [#312 MERGED](https://github.com/aws-solutions/konductor/pull/312) and Claude SOP skill loading [#303 MERGED](https://github.com/aws-solutions/konductor/pull/303). OPEN, not credited as shipped: [#231](https://github.com/aws-solutions/konductor/pull/231) and [#232](https://github.com/aws-solutions/konductor/pull/232) workflow/version diagnosis, [#285](https://github.com/aws-solutions/konductor/pull/285) AWS MCP permission requests. [Issue #72](https://github.com/aws-solutions/konductor/issues/72) addresses independent proof (S3*); [#301](https://github.com/aws-solutions/konductor/issues/301) addresses metrics, not S4 closure. These first-party statuses were checked in the prior v0.18.1 source-first assessment; this change only reformats its case.

| Required C link or real operator outcome | Track A: current shipped/Issue/PR coverage + evidence | Track B: smallest missing native integration or NONE | What would disprove this proposed need? |
| --- | --- | --- | --- |
| Match official prospective change to selected installed target and choose alternatives | [manifest](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/install/manifest.rs), [doctor](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/doctor.rs), [research](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/skills/external-research/SKILL.md) SHIPPED; #312/#303 merged old fixes | Optional native skill comparing cited date/version/contract with exact manifest strategy, producing variable lawful retain/test/escalate recommendation or UNKNOWN | Built-in supported path already makes this variable source-grounded future choice |
| Effect on next S3 work and real feedback return | [Orchestrator](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agents/konductor.agent-spec.json) and [SDLC gates](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agent-sops/k-full-sdlc.sop.md) SHIPPED | Reuse S3 accept/refuse authority, next supported specialist/SOP invocation and returned actual success/failure + doctor evidence to S4 | Only static warning/manual fix, no later run evidence, or equivalent existing feedback already closes the function |

**On-top distinctness:** Proposed Track B is prospective official notice → installed strategy match → discretionary bounded S4 choice → lawful S3 trial → actual next operation result and S4 reconsideration; no product feature duplicates the now-merged 2026 skill exposure fix. The hypothesis is narrow to one supported installation, and even a technically plausible C does not compel maintainer adoption.

**Source ambiguity / rights blockers:** No measured official future deprecation in scope (the scenario is HYPOTHETICAL); host version and capability may be unobservable, then label UNKNOWN and stop. User authorization is indispensable before persistent install/config/trust/privilege changes; source evidence alone cannot grant it. Do not claim blocker `BLOCKED` solely because usefulness remains unmeasured.

## 3. Minimal complete S4 first-party C construction

**Required property:** First-party *developer-composable* autonomous S4 prospective decision/authority/effect/feedback within Konductor's supported installation boundary, not just a tool registry, scheduler, dashboard or warning. At least two legally available options must lead to distinguishable outcomes; source-first and rights constraints remain binding.

**Physical interface count is NOT prescribed.** These rows are necessary logical links, not a fixed Paperclip port quota.

| Necessary native component or port (repeat/omit rows as evidence requires) | Existing file/API and evidence | Smallest proposed edit / developer integration | Legitimate owner, effect and return |
| --- | --- | --- | --- |
| Installed target and external future source | [manifest.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/install/manifest.rs), [doctor.rs](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/konductor-rs/src/cli/doctor.rs), [external-research](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/skills/external-research/SKILL.md) | Opt-in native skill reading *dated official* future notice, installed `kiro-cli-v2`/`kiro-v3`/`claude` strategy and `doctor --json`; UNKNOWN when unavailable | S4 researches actual affected target, selects lawful prospective alternative, does not execute untrusted notice content |
| Developer-defined S4 choice and S3 gate | [Decision research](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/skills/decision-research/SKILL.md), [Konductor agent](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agents/konductor.agent-spec.json), [SDLC SOP](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/agent-sops/k-full-sdlc.sop.md) | Narrow S4 retain / user-approved sandbox trial / escalate record with permitted modes, and S3 accept/refuse/defer handoff; no new orchestrator | Developer/parent specifies allowed alternatives; model S4 decides future recommendation; current S3 owns the next permitted work |
| Real later effect and returned feedback | Native current specialist/SOP run and `doctor` check already exist as separate functions | Bound next-run receipt: chosen host strategy and invoked role/SOP, success/failure and diagnostics actually observed, returned to same S4 reviewer | S3 routes real supported next task; S4 revises/retains/escalates only after receipt; no false success without later execution |

**Native-specific design advice (not a new gate):** The specificity is not a generic host-adapter label: it is Konductor's `.konductor/manifest` strategy, Kiro-v2/v3/Claude skill/SOP packaging, existing `doctor --json`, model-backed k-researcher, current S3 orchestrator and parent-controlled trust/config. Don't build a new control plane to hide these concrete distinctions.

**Architectural C-sufficiency argument:** Three candidates were compared: (a) keep existing manual doctor+host review; (b) add only a static host deprecation warning; (c) compose a narrow opt-in S4 skill and a real next-task feedback return on existing Konductor roles. Only (c) could form a distinct C-composable S4 loop; (a) remains cheapest product comparator and (b) has no autonomous discretionary owner or actual feedback. The minimal *unshipped* links are an optional notice-to-installed-strategy choice and a witnessed next-run return, not generic physical ports. Whether the supported host truly affords two lawful future alternatives remains to be tested.

**Explicit non-goals:** No automatic host migration, package download, user config edit, tool permission escalation, protected-memory mutation, S5 delegation, S3 replacement, generic adapter service, guaranteed S4=C grade, extra S3* feature or metric stack.

**Implementation dependency graph:** P1 accepted official dated host source, manifest/version/rights readback and unobserved-value UNKNOWN guard → narrow P0 developer-composed S4 choice and S3 trial acceptance/refusal → actual next supported specialist/SOP run → returned diagnosis and S4 redecision → future native evidence review. All priorities derive from [roadmap.md](roadmap.md).

## 4. Priorities, optional alternative and stopping rules

**P0 and P1:** P0 = narrow prospective host-strategy S4 decision → approved S3 next-task effect → real S4 return; P1 = official notice/version/manifest/doctor input, parent rights, invalid/stale source rejection and observable next-run receipt. Neither is built; the receipt owns their authoritative versions.

**P2:** NONE. No unrelated S3*, S5 or usage-metrics quota; any separate native proposal needs separate evidence and scope.

**Alternative path:** Existing native doctor/manual check and merged #312/#303 are preferred whenever they solve the same future user problem with equal feedback and less engineering effort. New host-version diagnostic PRs #231/#232 should be rechecked at any implementation decision.

**Stop:** Native S4 C already complete; no legitimate discretionary future option; unsupported host or target boundary; user/parent denies indispensable trial; future notice untrusted or missing; actual later invocation/feedback cannot be observed. A maintainer's product choice remains their decision, not a reason to falsify architectural C feasibility.

## 5. Future source-native acceptance — derive tests, do not copy a matrix

**Native test commands and entry points:** Pinned original [Makefile](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/Makefile) and [CLI README](https://github.com/aws-solutions/konductor/blob/f5d184596378ae72ae531d80647548512c14cacf/cli/README.md) document relevant `npm test`, `make test-py`, `cd cli && make test` / `make lint` as appropriate to changed native files. A configured supported Kiro/Claude host smoke is separately required to witness the proposed future S4 decision loop. All commands `NOT_RUN` in this PLAN_ONLY case.

**Positive functional closure:** With one verified installed strategy and official dated change fixture, show model S4 choosing among lawful alternatives, current S3 approving/refusing a sandbox route, and actual next-task supported role/SOP invocation + diagnostic outcome returned to S4 for redecision. A notification without that outcome fails C sufficiency.

**Independent alternative (where applicable):** On the *same* authorized host scenario, S4 can retain the existing supported specialist or request approval to trial another supported route; the resulting next-operation choice and receipt must differ when authorized. If the second route is not actually supported, stop with UNKNOWN rather than fabricate it.

**Negative authority and compatibility (where applicable):** Stale or mismatched official version notice -> UNKNOWN; untrusted release-note payload -> not executed; user refuses persistent install/config/trust -> no mutation; unsupported host skill -> no pretend fallback; next-task never run -> no successful closure report. Parent permission may not be inferred from ACTIVE/ALLOW fork metadata.

**Matched native alternative:** Same affected host/strategy, rights, next task, success criteria and time window for existing doctor/manual choice versus proposed S4 path. Benefit and engineering cost remain hypothetical; `NOT_MEASURED`.

| Proposed native case (add as many or few rows as needed) | Real source-supported setup / command | Expected effect and return | Falsifier or stop |
| --- | --- | --- | --- |
| Prospective notice and actual later effect — NOT_RUN | Installed test Kiro-v2/v3 or Claude strategy + `doctor --json` readback + dated official notice fixture + permitted next specialist/SOP smoke | S4 chooses permitted future path, S3 acknowledges, real supported next invocation and result return | Only a static warning, no real supported next-task effect |
| Alternative and denial — NOT_RUN | Two explicitly permitted choices and separate parent refusal scenario | Different lawful routing decisions; denial causes no config/permission write | Always hardcoded route or unauthorized write |
| Native comparator — NOT_RUN | Same host/task with current `doctor` and manual route | Compare actual same-task outcomes, effort and maintenance | Existing path already equally closes decision/feedback with less complexity |

**Example IDs such as AC-01…AC-09, fixed port names or a universal test count are deliberately not supplied.** Tests are derived from Konductor source and the target S4 function only; no unexecuted case is called PASS.

## 6. Proposal verdict, falsification, evidence ownership and handoff

**Proposal-stage decision:** GO

**Research disposition:** NEEDS_EVIDENCE

**Primary falsifier:** If #231/#232 or supported present native flow already provides complete future-source interpretation, lawful model S4 choice, accepted next S3 operation and actual S4 feedback, a new P0 is redundant; if model owner, user rights or later outcome is missing, it is not a complete C path.

**Validation state:** NOT_RUN; only source inspection and fork-local document structural checks, not native host/product tests.

**Ownership of truth:** Profile owns VSM semantics, Skills the method, Index the accepted historical grade, [roadmap.md](roadmap.md) the case decision and all pins/priority values, original Konductor maintainers the product and adoption, and user/parent real permissions. Fork status never stands in for external acceptance.

**Cost status:** `NOT_MEASURED`; any comparative cost/value claim awaits a matched native experiment.

**Next permitted action:** Preserve this case as PLAN_ONLY, review current first-party #231/#232 and lawful alternative, then separately authorize and run a bounded host test if desired; no automatic product implementation or external Issue/PR.

**Human backlink:** [issue.md](issue.md) (one Human decision draft).
**case receipt:** [roadmap.md](roadmap.md) (one canonical structured decision).
**AI disclosure:** Prepared with AI assistance; no native code tests, model runs, measured cost, independent human review or original maintainer adoption claimed.

**No original external Issue/comment/PR, public fork Issue/PR, source change, grade revision or new parent authority** follows this proposal. Separate exact current-conversation approval is required before any outward action; `PAUSE/STOP` remains binding.
