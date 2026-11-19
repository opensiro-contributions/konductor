# Konductor — S4 constructor sufficiency review

[Human decision](issue.md) · [Receipt](roadmap.md). PLAN_ONLY / NEEDS_EVIDENCE. **Final decision: NO_GO** for an additional S4 constructor now. Proposed C is not qualified, implemented or assessed.

## Boundary and accepted baseline

**Accepted historical baseline:** `S1=A · S2=A · S3=A · S3*=A · S4=? · S5=—`.

[Accepted Index assessment](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/ko/konductor.md), Index `34e11ec4dd52e1ba3ee0111d8bca73f13918f54f`, assessment blob `01e846897ae499497ffd65a2be0d359187f2e866`, reviewed 2026-11-18 at original `09c34858ca2e704fb8572c91389a87255b1e1075`; Profile 0.2.4 / Methodology 0.3.8. The catalog row is `konductor`, position 1253, matching this repository and review ref. This is one calendar day old on 2026-11-19. Main has materially changed; refresh the Index assessment before any current-grade claim. There is no automatic regrade.

| Function | Accepted | Meaning and roadmap consequence |
| --- | --- | --- |
| S1 | A | Installed coding/research specialists own operational decisions; no constructor work required. |
| S2 | A | Orchestrator resolves shared-file/worktree interference; preserve it. |
| S3 | A | Orchestrator manages active specialist commitments and recovery; preserve it. |
| S3* | A | Separate adversarial reviewers/checker return findings; no replacement proposed. |
| S4 | ? | Memory/skill reuse is plausible, but prospective organizational adaptation closure is unresolved; investigate, do not turn uncertainty into absence. |
| S5 | — | No in-boundary ultimate policy owner established; retain legitimate user/maintainer rights, no new governance layer. |


System: one installed Konductor project delivery cell in configured Kiro CLI or Claude Code, including its distributed roles/skills/SOPs. Exclude AWS service governance, host internals and the upstream maintainer organization. Original current main `05360b8cc17e174d0eb85173432094b88a799b64`, observed 2026-11-19. Never credit the maintainer's updating distributed skills as runtime S4 of every installed cell.

## Function and counterfactual

S2 resolves interference; S3 manages current delivery; S3* returns independent findings; S4 develops externally/prospectively oriented alternatives in two-way dialogue with S3; S5 owns legitimate ultimate policy. [Profile 0.2.4](https://github.com/opensiro/vsm-harness-profile/blob/v0.2.4/PROFILE.md) governs meaning.

Candidate user task: after AWS guidance changes, adapt the installed team's future IaC verification practice while preserving user rights and demonstrate a better later task outcome. Best baseline: existing AWS search/retrieve, `infra-validation`, explicit trust gates, and user-confirmed workspace procedure capture. Current issue #39 instead chiefly asks for source-maintenance choices. No matched failure shows that this baseline needs a separate adaptation actor.

## Shipped vs proposed evidence

| Port / behavior | Source / observed status | Coverage and limitation |
| --- | --- | --- |
| External discovery and options | [find-aws-skills](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/skills/find-aws-skills/SKILL.md), SHIPPED source contract | Search relevant descriptions, choose exact skill name, retrieve references; if unavailable offer retry/native alternative/user choice. Task-time selection is not automatically prospective team adaptation. |
| IaC application | [infra-validation](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/skills/infra-validation/SKILL.md), SHIPPED | Loads CloudFormation/CDK/IAM/DynamoDB checks and reports unrun layers. `cdk synth`, deployment and account actions retain explicit rights. |
| Related skill migration | [dynamodb-design](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/skills/dynamodb-design/SKILL.md), [iam-policy-design](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/skills/iam-policy-design/SKILL.md), [policy-validation](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/skills/policy-validation/SKILL.md), [cost-estimation](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/skills/cost-estimation/SKILL.md), SHIPPED | Concrete toolkit use/pointers and review rules already exist. `dynamodb-validation` no longer exists at this pin. No claim of complete live AWS coverage. |
| Research / current manager | [k-researcher](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/agents/k-researcher.agent-spec.json), [konductor](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/agents/konductor.agent-spec.json), SHIPPED | Research returns source-linked findings; orchestrator owns current assignments/review. Neither defines a new strategic change mandate. |
| Durable option application | [workspace-skills](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/skills/workspace-skills/SKILL.md), SHIPPED | Offers confirmed creation/update with provenance restrictions, Kiro startup resource / Claude discovery. Preserve user-authored entries. Requires an actual later run to prove effect. |
| Facts and provenance | [persistent-memory](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/skills/persistent-memory/SKILL.md), SHIPPED | Bounded facts, path validator, protected user origins. Memory writes alone do not establish S4. |
| Kiro reachability | [PR #224](https://github.com/aws-solutions/konductor/pull/224), OPEN head `5ce102d345df7b640d4a532eabb302369aeaa65a` | Inspected diff: merges dependencies.mcpRegistry into V2/V3 configs, with harness override tests. Main source lacks `with_registry_mcp_servers`; do not assume this is shipped or current installed users have AWS configured. |
| Claude permission lifecycle | [PR #285](https://github.com/aws-solutions/konductor/pull/285), OPEN head `ff6102a21c478c36156950165cb84ca60c462753` | Inspected diff: ask/allow merging and uninstall attribution. It constrains tools; it does not own adaptation decisions. Test additions are author/source evidence, not tests run by this assessment. |
| Maintainer demand | [Issue #39](https://github.com/aws-solutions/konductor/issues/39), OPEN, no comments at readback | Per-skill replace/rework/keep discussion; parts stale relative to main. Do not duplicate it. |

## Constructor sufficiency and authority

No qualified C target. Five necessary relationships were checked, not implemented:

| Relationship | Current result / what would have to change to justify reconsideration |
| --- | --- |
| External prospective distinction and alternatives | Discovery exists; no measured recurring installed-team failure or reasoned prospective adaptation alternatives established. |
| Independent developer-composed decision owner | Generic roles/skills are configurable, but no source-specific delegated strategic selector contract with a demonstrated new task is established. A hook is insufficient. |
| Lawful state / enforcement | Confirmed procedure writes and protected provenance already exist; a future design must preserve them and bind authorization to the exact scope/version, not infer a general AWS write grant. |
| S3 feasibility dialogue | Require current manager to accept/refuse/defer a proposed practice based on workload/tool rights; no such future-strategy exchange and outcome is demonstrated here. |
| Later operational return | Later skill reload is plausible, but no concrete changed specialist run and returned success/failure trace for this adaptation were observed. |

P0: rejected additional S4 constructor. P1: evidence-only reconsideration conditions, not an authorized engineering backlog. P2: NONE. S1/S2/S3/S3* already A need no forced C work; S5 remains outside this proposal. No optional C(P) mode is justified.

## Native acceptance for possible future reconsideration

These cases are tailored proposals, **NOT RUN**; they are not a mandatory generic AC suite or evidence of C.

| Native comparison | Necessary observation / falsifier |
| --- | --- |
| Same IaC project, same external AWS-check change, same host rights: native retrieval vs candidate controller | Identify an actual missed future-task outcome in the native arm and correct later specialist output in the candidate arm. If ordinary retrieval/confirmed capture achieves it, retain NO_GO. |
| Two legitimate choices: retain local gate / adopt revised external check | Chosen strategy changes later verification behavior and its receipt; a hard-coded update or recommendation only fails. |
| User refuses capture, user-authored skill, missing tool or untrusted synthesis | No unauthorized mutation or execution; preserve existing prompt/provenance rights and report the gap. A new selector cannot grant itself rights. |
| Proposed check is incompatible or later operation fails | S3 receives truthful failure and holds/reverts within legitimate rights; no fabricated successful adoption. |

Source-native future validation commands from [Makefile](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/Makefile) and [PR template](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/.github/PULL_REQUEST_TEMPLATE.md): `npm test`; `make test-py`; relevant `make test-skills-sh`; CLI changes additionally `cd cli && make test` and `cd cli && make lint`; behavior changes require build/synth/install and actual host smoke/benchmark where applicable. Deterministic structure tests alone cannot prove LLM decision quality, external service correctness or S4 closure. No product change was made, so no such suite was run for this roadmap.

## Rights, alternatives, cost and final contract

Apache-2.0 [license](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/LICENSE.txt), original notices preserved. [CONTRIBUTING](https://github.com/aws-solutions/konductor/blob/05360b8cc17e174d0eb85173432094b88a799b64/CONTRIBUTING.md) accepts non-core PRs, asks for discussion before significant work, licensing confirmation and potentially a CLA for larger changes; fork CI needs maintainer `/codebuild_run(<SHA>)`. No express AI ban or mandatory DCO found in inspected root guidance/PR template; this is bounded evidence, not proof of no other requirements. Personal CLA/licensing attestations and human review claims cannot be invented. No external communication approved.

Native maintenance under #39 remains an independent choice. An Index reassessment is advisable due to material drift even though the accepted review is only one day old. No demonstrated Profile defect or case for a domain fork. Paired cost: same task/host/rights/output bar, total engineering/integration/review/test/regression effort and outcome correctness; **NOT_MEASURED**.

**Terminal decision: NO_GO** for the additional constructor now. This is a present engineering decision under incomplete benefit evidence, not proof that S4 is absent or useless in every deployment. Reopen only with the matched recurring failure and complete authorized closure described above. [Human backlink](issue.md).
