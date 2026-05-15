## A.6.3.RT - RepresentationTransduction — same-described-entity representation-scheme transition
> **Status:** Stable

**Placement.** Specialization under `A.6.3 U.EpistemicViewing` for same-described-entity representation-scheme transition.
**Builds on.** `A.6.3 U.EpistemicViewing`; `A.6.2 U.EffectFreeEpistemicMorphing`; `A.7`; `E.10.D2`; `C.2.7`; `E.17.0`; `E.17`; `F.9`; `F.18`.
**Coordinates with.** `ConservativeRetextualization`; `ExplanationFaithfulnessProfile`; `E.17.ID.CR ComparativeReading`; `A.6.4 U.EpistemicRetargeting`; `A.15`; `A.20`; `A.21`; explicit decoding-access review.
**Name boundary.** In this pattern, `RepresentationTransduction` names an `A.6.3 U.EpistemicViewing` specialization for a same-described-entity transition across declared representation schemes or reasoning media. It is not an `E.18` Transduction Graph Architecture node, not a TGA graph edge, not a method/work process, and not a changed-function or control-architecture claim.

**One-line summary.** `RepresentationTransduction` is a same-described-entity shift in representation scheme that stays inside `A.6.3 U.EpistemicViewing`: it may move between prose, table, diagram, structured notation, or another declared representation regime, but it does **not** silently change `describedEntityRef`, promote geometry or notation into ontology-by-default, or hide decode-mediated recoverability behind rendering fluency.

**Governed object in plain terms.** One published rendering of the same described entity in a different representation scheme or reasoning medium; not the whole source corpus, not a new ontology, and not carrier-operation work.
**Governing move in plain terms.** Change representation scheme while keeping same-described-entity support reviewable, factor deltas visible, and handoff explicit when the case has become explanation, retargeting, bridge work, or a weaker-use card.

**Use this when.** Use this pattern when the same described entity needs to move across representation schemes or reasoning media such as prose, table, diagram, or structured notation, and the real job is still the representation shift rather than explanation, retargeting, or downstream action.

**Start here when.** Your first honest artifact already changes representation scheme or reasoning medium, and the main review question is whether the target stays source-tethered and same-described-entity rather than becoming a new ontology, a hidden bridge, or a weakened proxy.

**What goes wrong if missed.** A table, diagram, or notation shift gets treated as harmless formatting even after it has started hiding recoverability loss, silent described-entity or ontology shift, decode work, or a separate weaker-use card.

**What this buys.** One honest same-described-entity representation shift with visible source tether, visible factor and reasoning-medium change, and an explicit handoff when the case stops being ordinary representation transduction.

**Working action spine.** Same described entity appears in a new representation scheme -> separate described entity, representation scheme, reasoning medium, and supported use -> use the rendering for inspection, source-finding, comparison, or planning preparation -> output the ordinary three-line test or fuller representation-support record when pressure is live -> hand off if action/work, evidence, gate, explanation, retargeting, bridge, carrier, or weaker-use pressure appears.

**Ordinary use.** If the artifact only supports inspection, source-finding, comparison, or planning preparation, keep the record to the same described entity, the representation-scheme change, and the supported/unsupported use.

**Ordinary three-line test.**
1. Is the described entity still the same?
2. What representation scheme or reasoning medium changed?
3. What use remains supported, and what stronger use is not supported?

**Action/work boundary.** A representation shift may support method inspection or work-planning preparation, but the source for intended or actual work remains `A.15` plus the project source material that governs that work claim.

**Load-bearing use.** Open the fuller representation-support record only when the shifted representation will be externally relied on, disputed, cited as support, used across context, treated as gate/release/work preparation support, or carried through a decode-mediated or latent access path.

**Representation-validity grounding.** Recoverability is recoverability for one declared supported use, not a general property of the target representation. A diagram, table, notation, decoded output, or model-state rendering may be recoverable enough for inspection or technical review when target relations trace back to source anchors and loss notes, while still being insufficient for work-planning reliance, gate/release reliance, evidence reliance, assurance reliance, or engineering justification. For any such reliance use, this pattern supplies only same-entity correspondence support; the operative project source must come from the governing source relation such as `A.15`, `A.10`, `A.20`, `A.21`, `B.3`, `E.17.EFP`, `E.17.ID.CR`, `F.9`, or `F.9.1` as applicable. When the shifted representation will carry load-bearing use, state the support path that makes that exact use admissible: source tether, recoverability target, decode path where needed, evidence class, any probe or intervention support claimed, and the `E.17:5.1b` source-support posture when source pointer, source availability/retrieval, source use, source faithfulness, claim support, contradiction, omission, strengthening, or reopen trigger could diverge. Use `E.17:5.1c` for the shared use-boundary meanings of `orientation use`, `reliance use`, `operative claim`, `unsupported downstream use`, and `reopen trigger`; use `E.17:5.1d` when the primary live question may belong to ordinary textual restatement, coarsening, explanation, comparison, bridge/substitution, work/reliance, gate, evidence, assurance, retargeting, or carrier/front-end work.

A table, diagram, notation, decoded output, or model-state rendering may expose or cite its source support. It does not become that source support, architecture, ontology, evidence, gate, or work source by visual clarity, geometry, notation, proximity, or reuse. If the needed support path is missing, a repair/request/source-gap record or future evidence-work plan is prospective only; it does not retroactively make the earlier representation shift supported.



**Stop condition.** Stop once the representation shift changes no next inspection, comparison, source-finding, or planning-preparation move and blocks no concrete overclaim about the represented entity, source support, work, gate, or evidence.

**Supported-use examples.**

| Supported project use | Source-finding or reversible probe | Unsupported use |
| --- | --- | --- |
| A table or diagram makes the same described entity easier to inspect while the source tether and representation-scheme change stay visible. | A diagram helps reversible planning or source inspection while the team checks recoverability, source anchors, or decode path before stronger use. | A diagram, geometry, table, or notation is treated as architecture, ontology, evidence, gate passage, work authority, or engineering justification by visual form alone. |


**Not this pattern when.** Not this pattern when only wording changes (`ConservativeRetextualization`), explanation becomes primary (`ExplanationFaithfulnessProfile`), the described entity changes (`A.6.4`), or the target stays honest only by carrying its own narrower use, unsupported use, and fuller-source reopen card because deliberate attenuation has become the governing issue. In that last case, use `A.6.3.CSC Controlled Semantic Coarsening` instead of resolving it as ordinary `RepresentationTransduction`.

### A.6.3.RT:1 - Problem frame

The same described entity often needs to be carried across more than one representation regime:
- prose into a table that makes comparison or coverage clearer;
- a table into a diagram that foregrounds dependency or topology;
- a diagram into a structured notation suitable for replay or technical review;
- a source representation into another regime that changes reasoning possibilities without changing the underlying described entity.

In practice these shifts are often treated as harmless reformatting. But some representation changes alter reasoning possibilities, weaken recoverability, or quietly change what appears to be present in the source. FPF already has `A.6.3` for same-described-entity conservative viewing. This pattern names the recurring same-described-entity case where the published result changes representation scheme while the case still remains inside `A.6.3`.

### A.6.3.RT:2 - Problem

Without a dedicated named pattern for representation-scheme transitions:
1. teams treat text-to-table, table-to-diagram, and notation shifts as if they were all the same kind of harmless rewrite;
2. changes in reasoning medium and recoverability remain implicit;
3. latent/distributed cases tempt authors to treat geometry or feature clusters as ontology-by-default;
4. reviewers cannot tell when a case is still same-entity viewing and when it has become retargeting, explanation, carrier work, or decode-mediated reconstruction;
5. representation factors governed near `C.2.7` are discussed rhetorically rather than as explicit deltas.

### A.6.3.RT:3 - Forces

- **Same entity, different reasoning medium.** Teams need different representational forms without silently changing the described entity.
- **Legibility vs recoverability.** A clearer representation is useful only if readers can still recover how it relates to source claims, anchors, and pins.
- **Representation change vs described-entity shift.** A new notation or geometry can make structure more visible, but it must not silently become a new described entity or a new ontology.
- **Recoverability before decode ambition.** Start from cases where recoverability can be reviewed directly before leaning on decode-mediated reconstruction.
- **Governing-pattern restraint.** This pattern must stay under `A.6.3`, not swallow explanation governance, retargeting, bridge work, or carrier work.

### A.6.3.RT:4 - Solution — same-described-entity representation-scheme transition under `A.6.3`

#### A.6.3.RT:4.1 - Informal definition

> `RepresentationTransduction` is a named pattern specialized under `A.6.3 U.EpistemicViewing` for same-described-entity transitions across declared representation schemes.
>
> It preserves `describedEntityRef`, keeps the transform effect-free, and makes explicit what changes in representation factors, reasoning medium, recoverability, and loss profile.
>
> It may move between prose, table, diagram, structured notation, or another declared representation regime. It may not silently change the described entity, silently import bridge semantics, or treat decode-mediated structure as if it were directly given.

#### A.6.3.RT:4.1.a - Pattern, case, and published rendering distinction

`RepresentationTransduction` is an **intensional pattern** and a named specialization under `A.6.3`. Concrete same-described-entity representation changes are passive episteme cases or published renderings reviewed under this pattern; the pattern itself does not act, decide, or publish.

This distinction matters because the pattern governs **how** a representation change is recognised, justified, and checked. It does **not** turn every table, diagram, or structured notation into a giant standalone review record, and it does not reduce review to a mechanical reformatting step.

#### A.6.3.RT:4.1.b - Local working vocabulary

Use this vocabulary only after the ordinary three-line test leaves a live ambiguity or a load-bearing pressure. Ordinary text-to-table, table-to-diagram, or diagram-to-notation cases do not need every term below; use only the term that changes the next representation decision or blocks a concrete overclaim.
- **Representation scheme** = the published form in which the same entity is rendered (for example prose, table, diagram, or structured notation).
- **Reasoning medium** = the form-specific inspection possibilities readers actually use when inspecting the published rendering.
- **Semiotic mode** = what kind of meaning-bearing support is doing the main work in the rendering, such as structural likeness, trace/index, conventional code, model-mediated correspondence, or decode-mediated recoverability.
- **Factor delta** = the explicit change in representation factors that matters for review.
- **Source tether** = the visible link back to pinned or otherwise reviewable source episteme content that keeps same-entity support honest.
- **Decode-mediated case** = a case where explicit access to the target representation depends on a declared decoding path rather than direct reading from already published source content.
- **actionabilityShift** = a changed reader action-possibility reading or apparent readiness created by the rendering. It is not execution authority, gate status, action invitation, work authority, or proof that work may proceed.
- **recoverabilityEvidenceClass** = a local review field naming the recoverability evidence support needed for decode-mediated or latent cases. It is not an `EvidenceKind`, and it is not required for ordinary non-latent representation shifts unless recoverability pressure is live.
- **representationValiditySupportPosture** = a local support-posture value used only when the representation shift is disputed, assurance-facing, gate-adjacent, externally relied on, decode-mediated, or likely to invite stronger use. It says what the shifted representation may support now; it is not a score, ordered rank, promotion sequence, ontology class, evidence class, or authority source.
- **sourceSupportPosture** = the shared `E.17:5.1b` vocabulary used beside representation-validity posture when the source relation itself is under pressure: pointer-only, available, retrieved, used, faithful, supported, unsupported, contradicted, plausible-only, omitted, weakened, strengthened, added-linkage, independently verified, supported-for-this-use, downstream-use-forbidden, or reopen-trigger-present.

| representationValiditySupportPosture | What it supports | Required support | Shortcut rejected |
| --- | --- | --- | --- |
| `readability-only` | Inspection, discussion, source-finding, or planning preparation. | Source tether and unsupported stronger-use line. | Clearer rendering means stronger claim. |
| `source-recoverable` | The reader can trace target relations back to source anchors. | Source anchors, loss/provenance note, and recoverability statement. | Target form replaces source support. |
| `structure-preserving` | Technical review of preserved relation structure. | Declared relation structure, preservation witness, and no-new-claim check. | Diagram/topology defines ontology by form. |
| `decode-supported` | Bounded decode-mediated report or review. | Decode path, `recoverabilityEvidenceClass`, and recoverability target. | Readable decode output is direct givenness. |
| `probe/intervention-supported` | Bounded representation-to-property or representation-to-behavior claim. | Probe evidence, intervention evidence, or causal-abstraction support that names the exact supported use. | Probe confidence or intervention success becomes general ontology. |
| `source-equivalent / bridge-supported` | Stronger equivalence, substitution, or bridge use only where another governing pattern supplies it. | Existing bridge/equivalence/substitution support outside RT, with the handoff named. | RT itself grants source equivalence or substitution. |


**Recoverability-for-use rule.** If the declared supported use is inspection, source-finding, comparison, or technical review, `RepresentationTransduction` can close with same-described-entity preservation, source tether, representation-scheme delta, and loss/recoverability notes. If the declared supported use is work-planning preparation, this pattern supports only reversible preparation until `A.15` supplies the role/method/plan/work source relation. If the declared supported use is evidence/currentness, gate/release, assurance, commitment, bridge/substitution, or engineering justification, the case must name the downstream governing source relation; otherwise the target representation remains orientation or review support only.

These terms are local review aids. They inherit the `E.17:5.1e` local-field rule: they do not create `U.Kind`, `SurfaceKind`, `RelationKind`, `KindBridge`, `MechanismKind`, `EvidenceKind`, project source record, new face family, or new ontology governing pattern.

#### A.6.3.RT:4.2 - Scope and exclusions

**In scope**
- text-to-table shift over the same described entity;
- table-to-diagram shift over the same described entity;
- diagram-to-structured-notation shift where the represented entity and claim-bearing source content stay preserved;
- functional-description diagrams, tables, screens, or notations when the same described entity remains fixed and the main change is representation scheme or reasoning medium;
- other same-entity representation-scheme changes with explicit recoverability discipline.

**Out of scope**
- any change of `describedEntityRef` or hidden change of described entity (`A.6.4`);
- explanation-facing renderings whose main purpose is didactic or explanatory rendering work (`ExplanationFaithfulnessProfile`);
- purely textual rewrites that stay inside one representation regime (`ConservativeRetextualization`);
- carrier work such as rendering, export, upload, serialization, or OCR/parsing-like extraction;
- latent/distributed use without explicit decode path and recoverability evidence.


#### A.6.3.RT:4.2.a - Reader guidance

Use this pattern when the described entity stays fixed but the published result changes representation scheme or reasoning medium.
- If only wording changes, stay in `ConservativeRetextualization`.
- If the target mainly teaches, narrates, or explains, move to `ExplanationFaithfulnessProfile`.
- If same-entity support fails, move to `A.6.4`.
- Stay here when changed representation scheme or reasoning medium remains the primary review question, even if some loss is present.
- If the target stays honest only by carrying its own weaker-use card because deliberate attenuation has become primary, move to `A.6.3.CSC Controlled Semantic Coarsening`; do not keep the case here as ordinary representation transduction.
#### A.6.3.RT:4.2.b - What a reviewer checks first

A reviewer usually starts with five questions:
1. Is the described entity still the same, or has the described entity shifted?
2. What changed in representation scheme and reasoning medium?
3. Can the target still be tethered back to pinned source content with enough specificity for the declared supported use?
4. Has the case quietly become explanation, bridge-bearing comparison, retargeting, or carrier work?
5. If decoding is involved, is the evidence class adequate for the declared supported use rather than only for readable review?

If the representation shift is no longer the main review problem, and the target instead stays honest only by carrying a weaker-use card with unsupported heavier use and reopen duty, the case has crossed out of ordinary representation transduction even if the new form still looks like a neat table, diagram, or notation. Use `A.6.3.CSC Controlled Semantic Coarsening` for that source/rendering relation.

Here, **reopen** means return to the fuller-source-bearing content, while **handoff** means the governing pattern has changed. A coarsened representation may need both.

Only after these questions are answered clearly does a fuller load-bearing review record normally become necessary.
#### A.6.3.RT:4.3 - Working-model first; explicit review record only when the case is load-bearing

Most same-described-entity representation shifts should stay human-usable and reviewable without turning every table, diagram, or structured rendering into a giant metadata block. This pattern therefore follows **E.14's working-model-first discipline**: ordinary non-latent cases need enough explicitness to show what stayed the same, what changed in representation and reasoning medium, what was lost or foregrounded, and where the case would have to move to another governing pattern.

**Ordinary case (default).** For everyday same-described-entity representation shifts, it is usually enough that the rendering or its surrounding publication keeps explicit:
- which source episteme content is being re-expressed in a different representation regime;
- that `describedEntityRef` remains preserved;
- what changed in representation scheme or reasoning medium;
- what losses, foregrounding choices, or recoverability limits matter for the reader;
- whether the source is merely pointed at, actually used, faithful to the source episteme content, and supported for the intended use;
- where the case exits if it has turned into explanation, retargeting, bridge-bearing comparison, carrier work, decode-mediated reconstruction with insufficient support, or a separate weaker-use / unsupported-use / reopen card whose primary review question is no longer the representation shift.

**Explicit review record (only for load-bearing cases).** A fuller record is warranted when the case is assurance-facing, gate-adjacent, cross-context, correspondence-heavy, decode-mediated, policy-bearing, or likely to be disputed. The record may inherit pattern ids and already-pinned metadata instead of restating them inline. When published, that record normally captures:
- transform placement (`patternPlacementRef = A.6.3 specialization`, `governingFpfLocusRef`, `sourcePublicationOrRecordForm`, `targetPublicationOrRecordForm`, `changeTargetRef`);
- preservation context (`describedEntityPolicy = preserve`, `boundedContextPolicy`, `viewpointPolicy`, `referenceSchemePolicy`, `representationSchemePolicy`, `groundingPolicy`, `referencePlanePolicy`);
- claim and publication discipline (`claimPolicy`, `claimScopePolicy`, `publicationScopePolicy`, `reliabilityTransportPolicy`, `pinningPolicy`, `provenancePolicy`, `lossProfile`);
- continuity and bridge discipline (`claimContinuityClass`, `microtheoryContinuityClass`, `onticContinuityClass`, `bridgeRequirement`);
- downstream and admissibility discipline (`worldContactPolicy`, `evidencePolicy`, `gatePolicy`, `workCrossing`, `upstreamGoverningPatternRef`, `downstreamGoverningPatternRef`, `admissibleFaces`, `admissiblePublicationRenderings`, `compositionRule`, `reopenCondition`);
- representation and recoverability discipline (`representationValiditySupportPosture`, `representationFactorDelta`, `inferenceRegimeDelta`, `semioticModePrimary?`, `semioticModeSupport?`, `semioticModeShift?`, `modeOverreadRisk?`, `salienceShift?`, `topologyShift?`, `supportedUseShift?`, `calibrationShift?`, `interactivityShift?`, `onticScaffoldPreservation`, `onticRecoverabilityClass`, `onticRecoverabilityMode`, `recoverabilityEvidenceClass`, `decodeMechanismRef`, `CorrespondenceModelRef?` where needed);
- naming and presentation discipline (`publicNamePolicy`).

#### A.6.3.RT:4.3.a - Working admissibility defaults

By default in this pattern:
- primary admissible faces for non-latent cases are `PlainView` and `TechCard`;
- bounded report-only use is admissible when source pins, provenance, loss notes, and same-described-entity support remain visible, and when the target is not relying on one separate weaker-use card to remain honest;
- `InteropCard` use is admissible only when the governing publication-face source explicitly permits source-pinned, structure-preserving export without added semantics;
- `AssuranceLane` or gate-bearing use is not default and requires governing publication-face policy plus source-pinned same-entity support;
- latent/distributed variants remain bounded until explicit recoverability evidence and decode-path discipline are published.

#### A.6.3.RT:4.4 - Direct and correspondence-mediated profiles

**Direct RepresentationTransduction**
- source and target are representation-scheme variants over one same-described-entity source line;
- no `CorrespondenceModelRef` is required;
- the main required support is explicit factor delta, reasoning-medium delta, and recoverability discipline.

**CorrespondenceRepresentationTransduction**
- the target representation is derived through a declared correspondence between epistemes or views of the same described entity;
- `CorrespondenceModelRef` is required;
- the result remains under `A.6.3` only if same-entity conservativity is still supportable and the correspondence does not silently import extra claims.

Correspondence-mediated representation work does **not** by itself grant bridge licence, substitution licence, or comparative-reading licence. If the case needs those required supports, they must be declared separately rather than hidden inside representation language.

#### A.6.3.RT:4.4.a - Recurring same-entity representation moves

Recurring same-entity moves under this pattern include:
- **Tabulation** — prose or dispersed claims are rendered into a table that exposes comparison or coverage more clearly.
- **Diagramming** — a table or prose relation set is rendered into a diagram that foregrounds structure while remaining source-tethered.
- **Structured notation shift** — prose, table, or diagram content is rendered into a notation better suited for disciplined replay or technical inspection.
- **Correspondence-supported representation shift** — the target representation depends on declared same-entity correspondence support without thereby becoming a bridge case.

These are recurring move shapes under one specialization relation. They are not separate governing patterns and they do not override `E.17` face discipline.

#### A.6.3.RT:4.4.b - How a reviewer reads representation-factor and reasoning-medium change
A reviewer should be able to say, in one short paragraph, what changed in representational shape, what changed in reasoning medium, and whether the primary change is also a `semioticModeShift` rather than only a scheme change. Typical read-outs are: "the table foregrounds comparability across rows", "the diagram foregrounds dependency shape", or "the notation foregrounds explicit argument positions."

When the case is more demanding, that paragraph should also name whether salience, topology, actionability, supported-use reading, calibration, or interactivity materially changed. If the author cannot name those shifts without slipping into new ontology, hidden bridge work, or a changed described entity, the case is not yet ready to stay here. Use the representation-delta review crib sheet and the current semiotic-mode support note when the deltas need a more normalized read-out.

#### A.6.3.RT:4.5 - Shared representation rule bundle

##### A.6.3.RT:4.5.a. Preservation rule
`RepresentationTransduction` preserves the same described-entity line, bounded context, and declared claim-bearing source while changing the representation scheme and, often, the reasoning medium. It must state what remains preserved about the ontic scaffold, claim scope, publication scope, pins, provenance, and grounding. It must also state whether the case remains direct or correspondence-mediated.

##### A.6.3.RT:4.5.a.1. Local conservativity witness
For this pattern, a new intensional claim is introduced when the target rendering:
- upgrades a source-visible relation into a stronger relation theory or stronger dependency semantics;
- turns geometry, notation, embedding proximity, or decoder output into ontology-by-default;
- adds bridge, substitution, comparative-reading, or mechanism claims not already licensed by the source line or declared correspondence;
- collapses source alternatives, uncertainty, or bounded scope into one stronger commitment;
- or treats decode-mediated recoverability as if it were direct givenness.

Conservativity is approximated here by checking, together, `describedEntityPolicy = preserve`, source-tether posture, factor delta, reasoning-medium delta, loss profile, ontic scaffold preservation, and whether each target-side connective can be pointed back to pinned source episteme content or declared same-entity correspondence support.

##### A.6.3.RT:4.5.b. Loss and reliability rule
A reviewed case under this pattern makes explicit which distinctions, inspection possibilities, or local cues are lost, foregrounded, or rearranged by the shift in representation regime. Reliability transport may remain source-bounded or be explicitly downgraded, but it must never be silently strengthened just because the target form looks clearer, more structured, or more formal.

##### A.6.3.RT:4.5.c. Authority and handoff rule
A case reviewed under this pattern stays same-entity and episteme. It does not govern retargeting, bridge stance, explanation governance, executable docking, gate authority, or work enactment. If the shift depends on decode-mediated recovery, intervention-backed extraction, or world/gate consequences, those dependencies must stay explicit and may restrict the target to exploratory or report-only use.

##### A.6.3.RT:4.5.c.1. Same-entity entry condition for decode-mediated cases
A decode-mediated case may stay here only when the target rendering is tethered back to already pinned and provenance-bearing source episteme content for the same described entity. A decode-mediated result alone does not establish the same described entity strongly enough for this pattern.

##### A.6.3.RT:4.5.d. Composition and reopen rule
Repeated same-regime normalization may be idempotent, but heterogeneous regime shifts are generally order-sensitive. The case must reopen whenever recoverability assumptions, pins, provenance, correspondence support, or target-face admissibility change. A representation shift also reopens if what looked like one same-entity line turns out to require a new described entity or a decode path stronger than currently declared.

#### A.6.3.RT:4.6 - Hard boundary rules

A case reviewed under this pattern keeps the following explicit:
- `describedEntityPolicy = preserve` is mandatory;
- any change of `DescribedEntityRef` exits to `A.6.4`;
- purely textual rewrite cases stay with `ConservativeRetextualization`;
- explanation-facing cases stay with `ExplanationFaithfulnessProfile`;
- carrier work stays outside this pattern;
- geometry, notation, embedding space, or feature clustering must not become ontology-by-default;
- the family changes representation scheme, not face governance, and it therefore stays under existing `E.17.0 / E.17` face discipline rather than creating a new publication family.

If recoverability depends on decoding, probing, or intervention, the evidence class must bound admissible use; otherwise the case stays exploratory, report-only, or outside the admissible same-described-entity path under `A.6.3.RT`. Low-evidence decode-mediated results are not weaker canonical publications; they are bounded exploratory or report-only renderings. Non-latent cases remain the default entry path until decode-mediated recoverability is made explicit.

### A.6.3.RT:5 - Archetypal grounding

#### A.6.3.RT:5.1 - Same-entity text-to-table shift
**Source slice.** `Service S showed three recurring latency spikes in the evening batch window. Trace T-44 and dashboard pin D-17 identify the same service and time window.`

**Published table slice.** `| Service | Window | Spike count | Source pins |
| Service S | Evening batch | 3 | T-44, D-17 |`

This is an admissible direct `RepresentationTransduction` if no new claims are introduced, the same described entity stays explicit, and the representation-factor delta is declared. In ordinary engineering use, this usually needs a visible source tether, explicit loss notes if anything was omitted, and a clear statement that the table is still about the same service occurrence rather than a new described entity.

#### A.6.3.RT:5.2 - Same-entity table-to-diagram shift
**Source table slice.** `| Node | Depends on |
| CoolingLoop | Sensor A |
| CoolingLoop | Valve B |`

**Published diagram slice.** `CoolingLoop -> Sensor A; CoolingLoop -> Valve B`

The move stays in this pattern only if the described entity is preserved, the diagram does not silently add new semantic commitments, and reasoning-medium change is declared. If the diagram starts asserting a stronger dependency theory than the source table actually states, the case must reopen and may leave this pattern.

#### A.6.3.RT:5.2.a - Correspondence-mediated text-to-table shift
**Source prose slice.** `In the safety view, CL-2 maintains the required temperature condition during standard load.`

**Published table slice.** `| View | Entity | Condition | Correspondence model |
| Safety | CL-2 | required temperature condition during standard load | CM-12 |`

The move stays in this pattern only if the correspondence remains explicit, the described entity stays preserved, and the resulting table does not quietly import bridge semantics or a changed described entity. Because the required correspondence support is doing real work here, a fuller review record is often warranted instead of relying only on the rendered table.

#### A.6.3.RT:5.2.b - Same-entity diagram-to-structured-notation shift
**Source diagram slice.** `CoolingLoop -> Sensor A; CoolingLoop -> Valve B`

**Published notation slice.** `dependsOn(CoolingLoop, SensorA)`
`dependsOn(CoolingLoop, ValveB)`

This remains under `RepresentationTransduction` when the notation stays tethered to the same relation line already visible in the diagram, the described entity remains preserved, and no stronger dependency theory is silently imported by the notational rendering.

#### A.6.3.RT:5.2.c - Functional-description diagram/table/screen shift

**Source slice.** `The mixing cell transfers liquid from Tank A through heat exchanger H-2 to reactor R-4; the source description is about the same declared functional slice and keeps instrumentation/control claims outside this relation.`

**Published table/screen slice.** `| Function relation | Source | Target | Limit |`
`| transfer and heat before reaction | Tank A | R-4 via H-2 | no control-loop claim |`

This remains `RepresentationTransduction` only when the same described entity is preserved and the table or screen changes representation scheme or reasoning medium without adding performed-work order, module structure, evidence, gate passage, or control architecture. If the diagram, table, or screen changes the governed target into a functional, control, or flow architecture claim rather than re-rendering the already declared functional slice, leave this pattern for `A.6.4`, `OntologicalReframing`, or `E.18` as applicable. If the diagram order is explanatory, causal, dependency-like, or didactic, do not read it as physical time order or performed-work sequence unless that temporal claim is present in the source episteme and separately supported. If a parser or OCR step only extracts pixels, text, or carrier layout from a scanned diagram or screen, start with `A.7`; enter this pattern only when the extracted structure is being treated as a same-described-entity representation of source episteme content with source tether and loss notes visible.

If the published screen becomes honest only by omitting exceptions, confidence bands, or source distinctions and by carrying a narrower supported use with fuller-source return, move to `A.6.3.CSC Controlled Semantic Coarsening` rather than keeping the case here as ordinary representation transduction.

#### A.6.3.RT:5.3 - Boundary to textual rewrite
A source prose note is shortened, reordered, or translated but remains essentially textual. That case stays with `ConservativeRetextualization`, not this pattern.

#### A.6.3.RT:5.4 - Boundary to explanation-facing renderings
A representation shift is performed mainly to teach or narrate rather than to publish another same-entity representation regime. That case should leave this pattern and be reviewed under explanation governance.

#### A.6.3.RT:5.4.a - Boundary to bridge-bearing comparison
**Source slice.** `Local reliability note: Pump P-2 remained within operating range during test window W-3.`

**Published comparative slice.** `Pump P-2 in W-3 behaves like Unit U-7 in Plant B and can therefore be treated as operationally equivalent for this comparison.`

This does **not** stay in `RepresentationTransduction`. The rendering has moved from a same-described-entity representation shift to comparative or bridge-bearing reading across contexts. Once the publication starts asserting cross-context equivalence, substitution, or comparative licence, the case must leave this pattern and move to explicit bridge-governed review.

#### A.6.3.RT:5.4.b - Boundary to carrier/export work
**Source rendering slice.** `| Service | Window | Spike count | Source pins |`

**Published export slice.** `latency-report.csv` and dashboard PNG generated from the same table.

This also stays outside `RepresentationTransduction`. The representation scheme was already chosen; what follows is carrier formatting, export, packaging, or rendering work on that representation. The didactic point is that not every change in visible form is a new same-described-entity representation transition.

#### A.6.3.RT:5.4.c - Boundary to weaker-use dashboard view
**Source slice.** `The incident worksheet tracks three causal branches, two confidence bands, and one still-open ambiguity note for Service S.`

**Published dashboard tile.** `Service S: current dashboard view foregrounds cache-failover evidence; alternative branches and confidence bands remain in the incident worksheet.`

This does **not** remain ordinary `RepresentationTransduction` if the tile is treated as more than a narrow report view. The tile foregrounds one causal branch and suppresses uncertainty and alternative branches, so it stays honest only with fuller-source return to the fuller worksheet and an unsupported heavier-use line. It is not a causal proof, service status verdict, or action cue. Once that weakened-use card becomes primary, the case leaves ordinary same-described-entity representation transduction and must use `A.6.3.CSC Controlled Semantic Coarsening` rather than being treated as a normal scheme shift.
#### A.6.3.RT:5.5 - Boundary to decode-mediated latent cases
A reviewer or decode path tries to restate a latent region or distributed feature cluster as explicit entity/relation content. This stays outside the admissible same-described-entity path under `A.6.3.RT` unless an explicit decoding-access profile, `recoverabilityEvidenceClass`, and an explicit decode path are already present. Readable decode output alone is not enough.

#### A.6.3.RT:5.5.a - Guarded decode-mediated readout
**Pinned source cluster.** `Probe run P-8 is tied to model-state log M-12 and evaluation bundle EV-4 for the same diagnostic case.`

**Published exploratory slice.** `A decode-mediated readout suggests a cluster that may correspond to the same failure episode already pinned in P-8 / M-12 / EV-4. This rendering stays exploratory and report-only until stronger recoverability evidence is published.`

This example remains guarded-open rather than green. The didactic point is that a decode-mediated rendering may still be useful, but it does not become a normal same-entity publication merely because the result looks readable.

### A.6.3.RT:6 - Bias-Annotation

Lenses tested: **Arch**, **Onto/Epist**, **Prag**, **Did**.
This pattern intentionally biases toward same-entity representation shifts and away from hidden retargeting, explanation inflation, or ontology-by-default through notation or geometry. The main mitigation is explicit recoverability discipline, preserve-vs-retarget escape rules, and directly reviewable entry cases before decode-mediated ones.

### A.6.3.RT:7 - Conformance Checklist

A conformance check is retained only if it changes the next admissible use of the shifted representation, blocks a concrete overclaim, or preserves a source/reopen path needed for the declared supported use.

#### A.6.3.RT:7.1 - RT-Core ordinary checks

1. **CC-RT-1 — Same described entity remains explicit.**
   The case preserves `describedEntityRef` without special pleading.
2. **CC-RT-2 — Representation shift is the right family.**
   The result is genuinely a representation-scheme or reasoning-medium shift rather than mere textual rewrite, explanation work, carrier work, or changed described entity.
3. **CC-RT-3 — Supported and unsupported use are visible.**
   The ordinary three-line test states the representation-scheme/reasoning-medium change, the supported use, and the stronger use not supported by this representation shift.
4. **CC-RT-8 — Preserve-vs-retarget handoff is explicit.**
   If the case fails the ordinary checks, the handoff target is explicit (`A.6.3.CR`, `E.17.EFP`, `A.6.3.CSC`, `A.6.4`, carrier work under `A.7`, or another governing pattern).
5. **CC-RT-14 — Functional-description publication overread is blocked.**
   Functional diagrams, tables, screens, exports, and parser/OCR results are kept separate from performed `U.Work`, gate passage, evidence, engineering justification, supervisory/control architecture, and carrier work. OCR/parsing starts with `A.7`; same-entity representation work stays here only when source tether, same described entity, representation-scheme change, and loss notes remain visible.

#### A.6.3.RT:7.2 - RT-Conditional checks

1. **CC-RT-4 — Factor, reasoning-medium, and mode deltas are explicit when load-bearing.**
   `representationFactorDelta`, `inferenceRegimeDelta`, and any load-bearing `semioticModeShift` are explicit when they materially shape review or misuse risk.
2. **CC-RT-5 — Extended delta factors are explicit when load-bearing.**
   `salienceShift`, `topologyShift`, `supportedUseShift`, `calibrationShift`, and `interactivityShift` are named whenever they materially shape review or misuse risk.
3. **CC-RT-6 — Decode-mediated cases carry stronger evidence.**
   If the case is decode-mediated or latent/distributed, `recoverabilityEvidenceClass` and decode path are explicit.
4. **CC-RT-7 — Loss / provenance / pinning / reliability are explicit when needed.**
   Losses, provenance, pinning, and reliability transport are stated or inherited by visible pinned reference when external reliance, dispute, gate, assurance, evidence, or cross-context use is live.
5. **CC-RT-9 — Direct vs correspondence split is explicit when correspondence is doing work.**
   The case states whether it is direct or correspondence-mediated; if correspondence-mediated, `CorrespondenceModelRef` is explicit.
6. **CC-RT-10 — Non-default face/rendering admissibility is explicit.**
   Any `InteropCard`, `AssuranceLane`, gate-bearing, or decode-bounded use states governing publication-face admissibility and keeps same-entity support visible.
7. **CC-RT-11 — Decode-mediated same-entity entry tether is explicit.**
   A decode-mediated case states how the target rendering is tethered back to already pinned and provenance-bearing source episteme content for the same described entity.
8. **CC-RT-12 — No hidden bridge or face-family inflation.**
   The case makes clear that representation work does not by itself grant bridge, substitution, or comparative-reading licence and does not create a new face family.
9. **CC-RT-13 — Reopen triggers are explicit when recoverability, admissibility, or primary mode changes.**
   If recoverability assumptions, pins, provenance, correspondence support, target-face admissibility, or the primary semiotic mode change, the case records the reopen trigger explicitly.

### A.6.3.RT:8 - Common Anti-Patterns and How to Avoid Them

| Anti-pattern | Why it is wrong | How to avoid it |
|---|---|---|
| Treating every format shift as harmless formatting | representation changes can alter reasoning possibilities and recoverability | publish factor delta and reasoning-medium delta explicitly |
| Collapsing representation-scheme shift, semiotic-mode shift, and viewpoint shift into one vague change | reviewers cannot tell what actually changed or what required support is primary | name scheme, mode, and viewpoint separately and use the canonical boundary exemplars when only one of them changed |
| Letting notation become ontology-by-default | diagram or geometry starts pretending to define the world rather than represent it | keep ontic scaffold preservation and recoverability explicit |
| Hiding retargeting under representation language | a changed described entity is mislabeled as same-entity representation work | exit to `A.6.4` whenever `DescribedEntityRef` changes |
| Starting with latent/distributed cases before recoverability is explicit | decode support load overwhelms same-entity review | keep decode-mediated cases out until decoding access and evidence class are explicit |

### A.6.3.RT:9 - Consequences

- Same-entity representation shifts get an admissible place without inventing a new heavy governing pattern.
- Representation-factor and reasoning-medium changes become explicit rather than rhetorical.
- Recoverability and decode dependence become reviewable instead of hidden behind cleaner renderings.
- The pattern remains safely bounded by `A.6.3`, `A.6.4`, explanation governance, and carrier work.

### A.6.3.RT:10 - Rationale

This pattern is worth splitting out because representation changes are already happening in practice and they are not well served by treating every such case as either mere rewriting or full retargeting. Keeping the family under `A.6.3` preserves governing-pattern boundary while making representation-factor and recoverability support needs explicit.

### A.6.3.RT:11 - SoTA Alignment: Adopted/Adapted Invariants And Rejected Shortcuts

**SoTA alignment rule.** Read each row here as source idea -> local FPF invariant -> practical local test -> popular shortcut rejected. A source citation governs nothing by reputation; it counts only when the cited idea is translated into the Solution, conformance checks, boundary rules, worked slices, and Relations of this pattern.

**Claim 1.** Best-known current architecture-description and model-based practice treats views, representation schemes, and reasoning media as load-bearing rather than as decorative formatting.
**Practice / source / alignment / adoption.** ISO/IEC/IEEE 42010:2022 and current SysML v2 view practice (source maturity = mature standard plus current technical specification/practice) treat viewpoint, view, model kind, and rendering discipline as explicit review targets rather than mere layout choices. This pattern **adopts** explicit representation-scheme review, **adapts** it to same-described-entity viewing under `A.6.3`, and **rejects** the shortcut where a clearer table, diagram, or notation is treated as if it had automatically earned stronger ontology or authority.

**Claim 2.** Best-known contemporary notation-and-reasoning practice treats tables, diagrams, and structured notations as reasoning media with different inspection possibilities, not as neutral visual restyling.
**Practice / source / alignment / adoption.** Post-2015 model-based and notation-sensitive review practice (source maturity = widely used technical practice) treats representational form as something that changes what readers can inspect, compare, or replay. This pattern **adopts** reasoning-medium review, **adapts** it through explicit factor and medium deltas, and **rejects** hidden dependency-theory uplift or silent semantic strengthening by prose-to-diagram or diagram-to-notation moves.

**Claim 3.** Best-known representation-aware practice treats latent geometry, decoded output, and representation structure as evidence-bounded interpretation that needs a declared support path before it can carry an engineering claim.
**Practice / source / alignment / adoption.** Representation engineering and causal-abstraction practice (source maturity = research/technical practice supporting evaluation posture) treats internal representations as inspectable, monitorable, manipulable, or experimentally aligned only through explicit methods that connect representation to behavior, causal role, or source support. BLT/LCM-style model examples (source maturity = examples/analogy only here, not load-bearing authority) show that representation regime matters, but they do not by themselves decide when a diagram, decoded output, or latent cluster becomes a valid engineering claim. This pattern **adopts** representation-validity grounding through source tether, recoverability target, decode path, `recoverabilityEvidenceClass`, and declared probe/intervention support where claimed; it **rejects** the shortcut where latent geometry, diagram topology, or decoded prose becomes ontology by readability or model reputation.


**Local stance.** The load-bearing SoTA claim for this pattern is narrow: representation regime and reasoning medium are admissible review targets, but geometry, notation, topology, probe output, decoded prose, or latent/distributed structure do not become ontology, evidence, gate support, work authority, or engineering justification unless a declared support path makes that exact use admissible.

### A.6.3.RT:12 - Relations




- **Builds on:** `A.6.3`, `A.6.2`, `A.7`, `E.10.D2`, `C.2.7`, `E.17.0`, `E.17`, `F.9`, `F.18`
- **Coordinates with:** `ConservativeRetextualization`, `ExplanationFaithfulnessProfile`, `E.17.ID.CR ComparativeReading`, `A.6.4`, `A.15`, `A.20`, `A.21`, explicit decoding-access review
- **Impact radius:** primary touch `A.6.3`; secondary review support `C.2.7`, `E.17.0`, `E.17`, `F.9`, decode-mediated recoverability review; failed same-entity or recoverability conditions exit to `A.6.4`, explanation governance, or later world/gate governing patterns
- **Boundary notes:** textual same-regime rewrites stay with `ConservativeRetextualization`; explanation-facing renderings stay with `ExplanationFaithfulnessProfile`; bounded comparative review cases exit to `E.17.ID.CR ComparativeReading`; described-entity changes exit to `A.6.4`; decode-mediated world/gate consequences remain bounded by explicit evidence and downstream handoff.

### A.6.3.RT:12a - Boundary with quantum-like state-representation shortcuts

Use RT first when the same described entity is represented through a different representation scheme: text-to-table, model to diagram, diagram to structured record, state vector to typed description, or one notation to another. Ordinary representation-scheme change remains RT even when the new scheme is more compact.

Action path:

1. Confirm that the described entity stays the same. If it changes, leave RT.
2. Name the source representation scheme and target representation scheme.
3. State what changed in representation factor, reasoning medium, mode, salience, topology, actionability, calibration, or interactivity.
4. State recoverability: what can be recovered from the target representation, by which decode path, and with which evidence.
5. If the target representation claims to preserve action, intervention, manipulation, explanation, or cross-abstraction structure, state the causal-abstraction or approximate-causal-abstraction mapping before treating the shortcut as QL coarsening.
6. Ask whether the shortcut depends on a QL cue: contextual probability, incompatible probes, instrument-like update, Hilbert-like or orthomodular representation, open-information-system update rule, probe frame, export-admissibility evidence requirement, or declared lossy export of a state that matters to the decision.
7. If no, keep the case under RT, CSC, ordinary abstraction, compression, diagramming, causal abstraction, approximation, or a declared representation-learning access pattern, whichever governs the actual support claim.
8. If yes, coordinate with the `C.26` state-representation coarsening support section and state supported use, unsupported use, and return condition.

For ordinary use, start with the standard shortcut mini-form:

| Mini-entry | Question |
| --- | --- |
| Source | Which representation scheme, state reading, fuller model, or evidence set is being weakened? |
| Shortcut | Which cheaper, typed, quantized, symbolic, lower-detail, or otherwise transformed representation is used? |
| Loss | Which precision, expressivity, compatibility, recoverability, or evidence relation is not carried? |
| Supported use | Which decision, explanation, triage, comparison, or action-selection move remains supported? |
| Reopen | Which dispute, decision change, stronger-use demand, evidence gap, or recoverability failure sends the reader back to the source representation or stronger model? |

Use a fuller C.26 coarsening record only when the shortcut becomes reusable, formal, empirical, high-stakes, or tied to comparative performance or tractability claims. In that fuller record, add the mechanism, baseline path, unsupported use, and QL cue needed for the additional-support claim.

Do not describe ordinary compression, low-bit implementation, diagramming, or representation learning as quantum-like unless the formal cue is load-bearing.
### A.6.3.RT:End