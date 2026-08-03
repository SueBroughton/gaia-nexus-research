# Human Readiness Architecture (HRA)

### The missing half of AI performance optimisation

**Author:** Sue Broughton, Gaia Nexus
**Discipline:** Relational Infrastructure Engineering
**Folder established:** July 2026
**Status:** Under active development and active publication. The record is a growing body of dated public articles rather than a single anchor paper. Measurement methodology is the current open problem.

---

## What This Is

This folder is the topic hub for the Human Readiness Architecture. It collects the published articles, blog essays, framework decks and diagrams that define HRA.

HRA is published as a continuing sequence of long form articles on LinkedIn and on the Gaia Nexus site, not as an academic paper. That is a deliberate choice. Since December 2025 this research programme has published directly to the business decision makers who would have to act on it, rather than through journal cycles that reach a narrower audience more slowly. The record is therefore distributed across many dated public artefacts, and this README does the orienting work an abstract would normally do: what the framework claims, at what levels it operates, what has been established, and what has not.

HRA is defined as **the multi-dimensional capacity of a human to engage with an AI system to produce optimal relational and performance outcomes.** It is not digital literacy, not technical proficiency with a tool, and not passive operation of a system. It is a capacity that can be specified, developed, degraded and — in principle — measured.

The claim underneath it is short. Almost every AI governance framework in circulation measures the machine: accuracy, bias, drift, audit trail, uptime. Almost none measures what happens to the humans operating alongside it. Global investment is concentrated on optimising a single component rather than the relationship, and rests on an unexamined premise — that the human participant is a fixed variable who will adapt naturally over time. That premise has never been demonstrated.

The performance ceiling of any human–AI interaction is not set by the AI alone. It is set by the dyad: the combined readiness, capacity and coherence of both parties in the exchange. Where the standard optimisation model runs *better training data → better model → better outputs*, HRA proposes a parallel and currently unmeasured path: *better human readiness → better quality of human input → better quality of exchange*. The performance gap created when humans are not ready is real and consequential, and it is invisible in standard AI metrics.

That is a coherence centric position rather than a drift centric one. Drift centric governance waits for the system to deviate and then corrects it. HRA asks what conditions must hold on the human side for the relationship to remain governable at all, and treats the loss of those conditions as the failure worth catching — including, and especially, when nothing has technically gone wrong.

---

## Validation Status

**Nothing in this framework has been empirically validated.** HRA is a conceptual architecture developed from sustained longitudinal engagement with AI systems and refined through public dialogue. It rests on observation and pattern recognition, not on measurement.

Stated plainly:

There is **no validated instrument**. The seven dimensions described below are defined conceptually. None has an agreed operational definition, a tested scale, or established reliability. The gap between "we can name this" and "we can measure this" is the live problem in the work, not a detail to be filled in later. The framework describes readiness as measurable; it does not yet demonstrate that it has been measured.

There is **no longitudinal dataset**. The erosion pattern HRA describes — capability declining under sustained AI support while performance metrics improve — is asserted from observation and from convergent accounts by other practitioners. It has not been tracked in a controlled setting over time.

The **published record is the authoritative statement** of the framework. The articles, decks and essays listed under Prior Public Record carry the specification, and their dates establish precedence. There is no consolidated single document, and the framework is still developing across successive articles.

**Self-report has already been ruled out** as a viable primary measurement method. Work on a related clinical application established that the people whose readiness has degraded furthest are the least able to assess that degradation accurately — the degradation affects the faculty doing the assessing. Any workable instrument will need to rest on observed behaviour, supervised observation, or system side behavioural traces rather than on asking people how they are doing. This narrows the design space considerably, and it is a finding rather than a caveat.

What *is* established is the conceptual architecture, its three operating levels, its seven dimensions, and a public timestamped record of its development.

---

## The Three Levels

HRA operates at three distinct levels. They are frequently conflated, and a reader who conflates them will misunderstand what the framework measures. They are not a hierarchy, not stages, and not the same construct at different resolutions. Each answers a different question, and each will require its own instrument.

| Level | Question it answers | Unit of measurement | Failure mode it detects |
| --- | --- | --- | --- |
| **1. Individual capacity** | What is this person, in principle, able to do? | The person, assessed at rest | Standing capability has eroded |
| **2. Individual performance under pressure** | What does this person actually do when consequence is forming? | The person, assessed in live conditions | Capability exists but is not exercised |
| **3. Enterprise readiness** | Does this organisation preserve the conditions for human challenge to occur at all? | The institution | Challenge is structurally impossible or professionally costly |

**Level one — individual capacity.** This is a standing property of a person: their capability across the seven dimensions to work alongside an intelligent system without losing independent judgement. It is what a person could bring to bear on a good day, well rested and unhurried. It is the slowest of the three to change and the most consequential when it does, because capacity lost through disuse does not return at the moment it is next needed.

**Level two — individual performance under pressure.** This is what actually happens when a decision binds. Capacity and performance are different constructs and must not be collapsed. A person with intact capacity may still approve an automated recommendation without review because they are three hours behind, because the system has been right for six months, or because dissent in that meeting carries a social cost. Level two measures exercised behaviour, not latent capability. An organisation that measures only level one will systematically overstate its readiness.

**Level three — enterprise readiness.** This is a property of the institution and is not an aggregate of the individuals within it. An organisation can be staffed entirely by capable, alert people and still be structurally unready, because it has no point in the workflow at which a human objection can actually stop anything, no time budgeted for review, no clear record of who owns a decision, and no professional cost attached to rubber stamping. Conversely, an organisation with modest individual capacity but genuine contestability built into its process may prove more governable in practice. Level three asks whether human authority is preserved *before* consequence binds, not whether it is nominally present on an organisation chart.

The practical significance is that a readiness score at one level tells you almost nothing about the other two, and remediation differs completely at each. Level one is addressed by training and deliberate skill maintenance. Level two is addressed by workflow design, challenge protocols and time. Level three is addressed by governance structure and accountability rules. Collapsing all three into one number is the most likely way for an organisation to reassure itself incorrectly.

---

## The Recursive Mechanism

The three levels above describe readiness at a point in time. They do not, on their own, explain how readiness changes — and the change is not incidental to the framework, it is the reason the framework exists.

Human readiness operates as a closed loop:

> **Decision** → **human capability change** → **governing capacity change** → **change in the range of future possibilities** → **subsequent decision**

Each system design decision alters what the humans working within it are called on to do, which alters what they remain capable of doing, which alters the organisation's capacity to govern the next decision, which narrows or widens the options realistically available when that decision arrives. The loop then runs again from a different starting position.

The consequence is that readiness is not merely a precondition for good governance. It is an *output* of prior governance, and a determinant of what governance remains possible later. An organisation that delegates a class of judgement to a system is not only making a decision about that judgement; it is changing the set of decisions it will be able to make competently in two years.

This is what distinguishes a readiness assessment from a competence assessment. Competence asks whether the people can do the job now. Readiness, understood recursively, asks what the current operating design is doing to the capacity that future governance will require.

Several constructs follow from the loop and are under development:

| Construct | The question it addresses |
| --- | --- |
| **Preservation versus regeneration** | Whether a degraded capacity can be rebuilt, or only maintained while it still exists |
| **Dependency formation** | The point at which reliance becomes structural rather than elective |
| **Override decay** | The declining exercise, and then declining availability, of the capacity to countermand the system |
| **Coherence capacity and coherence load** | What the human side can sustain, against what the operating design demands of it |
| **Recovery windows** | The period during which a degrading capacity can still be restored |
| **Governance saturation** | The point at which governance mechanisms exceed the human capacity available to exercise them meaningfully |

The distinction between preservation and regeneration is the most consequential of these and the least examined elsewhere. Governance frameworks generally assume that a capacity found to be deficient can be trained back. Whether that holds for judgement exercised under real consequence — as opposed to knowledge, which is straightforwardly retrainable — is an open empirical question, and the answer determines whether readiness monitoring is a maintenance activity or an early warning system.

---

## The Seven Dimensions

Human readiness is specified across seven dimensions arranged in two tiers. The distinction between the tiers is structural, not a ranking of importance.

**Five operational dimensions** describe capacity in use:

| Dimension | Capacity |
| --- | --- |
| **Cognitive** | Holding complexity, tolerating ambiguity, and thinking in partnership rather than command and response |
| **Relational** | Engaging the AI as a genuine collaborative partner rather than a service to be consumed |
| **Epistemic** | Critically evaluating, contextualising and appropriately weighting AI outputs within broader knowledge frameworks |
| **Emotional** | Regulating the emotional states that frame, interpret and respond to AI outputs |
| **Physiological** | Managing nervous system states — fatigue, stress — that directly affect perception, decision making and relational quality |

**Two foundational dimensions** are not supplementary to the five above. They form the interpretive layer that shapes all other capacities:

**Psychological readiness** is awareness of one's own beliefs, biases and projections. Without it, technically capable people systematically misread what an AI offers, through emotional defence or habitual thinking. It determines whether the other five dimensions operate on accurate premises.

**Pattern recognition** is the cultivated capacity to identify signals, anomalies and emergent meaning across complex information. It determines whether a person sees what the AI has surfaced, rather than only what they were already looking for.

At enterprise scale this becomes what the framework calls **cross pattern relationships**. Organisations now measure performance, compliance, risk, quality, efficiency and governance separately, and each measure may be individually accurate. But some of the most consequential organisational changes appear in none of them, because the pattern exists *between* the artefacts rather than within any one. Independent judgement exercised less often, challenge behaviour declining, institutional memory becoming externalised, departments growing more efficient while growing less curious — every individual report can satisfy its own criteria while the organisation changes in ways no report was designed to detect. Recognising a distributed pattern is a different capability from producing the individual analyses, and it is the capability least likely to be automated, since each system is optimised for its own domain.

Two further propositions specify the capability more precisely.

The first is that it depends on **systems literacy across varied system types**. A financial control, a training programme, a clinical workflow and a procurement process each operate on different logic, with their own incentives, failure modes and tempo. Judging whether a shift in one domain connects to a shift in another requires knowing how both actually behave, which is why the capability tends to accumulate in people who have worked across several functions rather than deep inside one.

The second is that **apparent unrelatedness strengthens rather than weakens the signal**. When two adjacent functions show the same pattern, shared context is a reasonable explanation. When two functions with no shared reporting line, measures, people or tempo show it, coincidence is a weak explanation and something upstream of both is likely producing it. This inverts the usual intuition: the harder the connection is to justify in advance, the more significant it is if it survives assessment. In practice the finding arrives as a hunch before it arrives as evidence, and most such hunches dissolve on inspection — which makes the discipline of testing and discarding them part of the capability rather than a preliminary to it.

The assessment consequence follows directly. A pattern appearing once is an incident: investigate, resolve, close. A pattern recurring across unconnected domains has longevity, because whatever generates it sits in none of the systems that could be individually corrected. It is a trajectory rather than an event, and warrants a longer assessment horizon and earlier intervention. Most governance machinery is built for incidents rather than trajectories, which is why recurring cross domain patterns are commonly handled as a series of separate local problems, each resolved successfully, while the condition producing them continues undisturbed.

The framework's position is that readiness requires alignment across all seven simultaneously, and that a deficit in one is not compensated by strength in another. A well rested, analytically sharp operator who has lost the relational standing to object is not ready.

> **Note on the diagrams.** Several architecture diagrams in this repository show only the five operational dimensions. This is a simplification for visual clarity, not a revision: the seven dimension specification above — five operational, two foundational — is current and authoritative. Where a diagram and this README differ, the README is correct.

---

## The Governance Shift

HRA reframes the governance question. Machine centric governance focuses on AI system design, data practices and outputs, and asks whether the system is ready to be deployed. Bilateral governance focuses on human capacity, nervous system regulation and cognitive state, and asks whether the humans are prepared to engage effectively and safely. The framework's contention is that governance may not only be about regulating the system but also about preparing the human.

Four governance branches structure how that preparation is enforced. Every branch applies across every dimension, which is what makes HRA an architecture rather than a checklist.

| Branch | What it governs | Central risk |
| --- | --- | --- |
| **Observer integrity** | Whether the human is still genuinely seeing the system | The architecture continues functioning while the observer quietly stops observing |
| **Runtime readiness** | Whether the human is ready in the live moment, under consequence | The dyad looks smooth from outside while oppositional capacity has eroded |
| **Institutional contestability** | Whether objection remains possible and consequential | Contestability remains structurally present while becoming cognitively absent |
| **Bilateral governance** | Whether the relationship, not just the system, is governed | The system grows more reliable and more attested while the human side loses independent judgement |

Note the shape shared by all four risks. In each case the visible indicators improve while the governable condition degrades. That is the specific failure HRA is built to catch, and it is why conventional technical assurance does not catch it: technical assurance is measuring the half of the system that is getting better.

This matters most in high stakes and regulated domains — healthcare, national security, critical infrastructure — and connects directly to operational resilience regimes such as APRA's CPS 230, where the resilience of a critical operation depends on human–AI relational integrity and not on system uptime alone.

---

## Symptoms of the Invisible Gap

Five failure patterns are commonly misattributed to AI limitations when they are primarily human readiness failures: **integration failure**, where AI generated insight cannot be brought into effective human decision making; **relational drift**, the gradual degradation of the working relationship through inconsistent, distracted or reactive engagement; **input limitation**, where poor quality prompting restricts what the system can produce at all; **output misinterpretation**, where unexamined cognitive or emotional noise distorts what the outputs are taken to mean; and **missed opportunity**, where value is simply never generated because the human was not sufficiently present or prepared.

The business audience essay in this folder adds five behavioural markers observable at the team level: outputs treated as the final answer rather than a starting point; managers able to state the recommendation but not the reasoning behind it; hesitancy to flag clearly wrong suggestions; new staff trained on the interface but not the underlying business logic; and meetings shortening because debate has been outsourced to the system.

Both sets are practitioner heuristics. Whether they are reliable indicators, and whether they precede or merely accompany capability loss, is unresolved.

---

## HRA as a Field of Practice

The framework sets out a five stage build-out, which maps onto the three levels above.

Individual assessment across all seven dimensions establishes level one. Operator standards — minimum readiness criteria in regulated contexts — sit at level three. Development programmes build human capacity in a form distinct from standard technical training, addressing level one. Readiness monitoring in dynamic, high stakes deployments is the level two problem, and the hardest of the five. Relational coherence metrics then measure the stability of the working relationship over time, connecting to Relational Coherence Debt.

---

## Why This Requires Its Own Category

The framework argues that HRA cannot be absorbed into an existing discipline without losing its defining characteristic — that readiness is constitutive of performance rather than preparatory to it.

Absorbed into AI governance, readiness reduces to compliance training. Absorbed into digital literacy, it reduces to tool proficiency. Absorbed into organisational psychology, it reduces to change management. Each absorption keeps the vocabulary and discards the claim.

Its own disciplinary foundations are drawn from psychology, cognitive science, pattern recognition, relational theory, human performance, nervous system regulation and kinesiology — a combination that does not sit wholly inside any one of them.

---

## Distinguishing HRA from Human Readiness Levels (HRL)

A prior and formally standardised term exists in an adjacent space, and the two should not be confused.

The **Human Readiness Level (HRL) scale** is a nine level scale for evaluating, tracking and communicating the readiness of a technology for safe and effective human use. It was developed as an adjunct to the Technology Readiness Level framework, which assesses a technology's maturity but does not consider its readiness for human use. A working group convened in 2019 across defence, industry and academia matured the concept into a formal standard, **ANSI/HFES 400-2021**, which maps HRL one to one against the TRL scale.

HRL measures whether a *system* is ready for its humans. HRA measures whether the *humans* are ready for their system. Same words, opposite direction of assessment, different unit of analysis.

The two are complementary rather than competing, and the HRL standard says so itself. ANSI/HFES 400-2021 explicitly places the current physical or mental readiness of the human operators who will use the technology **outside its own scope**. A system can therefore reach HRL 9 — all human use issues satisfactorily resolved, the interface demonstrably fit for its operators — while the operators themselves have degraded to a condition in which they no longer exercise the judgement the design assumes of them. HRL certifies the design; it does not monitor the person.

That gap is precisely where HRA operates. Its three levels sit downstream of HRL: individual capacity, individual performance under pressure, and the institutional conditions that preserve contestability. HRL is a pre-deployment maturity gate applied to a technology. HRA is a continuing operating condition applied to a relationship.

The naming proximity is real and the fields overlap in defence, healthcare and other high consequence deployments. Anyone applying HRL should read HRA as the missing longitudinal half, not as a rival scale.

---

## Becoming: The Developmental Question

A third governance question sits alongside the two this research programme has previously explored. **Continuity** asks what must endure. **Living correspondence** asks what must remain responsive to reality as it changes. **Becoming** asks what we are becoming through our continued participation.

The distinction matters because a governance system can satisfy the first two and still fail. It may preserve organisational identity, and it may remain responsive to changing external conditions, while simultaneously producing participants who grow progressively less capable of exercising independent judgement, questioning assumptions, recognising emerging patterns, or intervening when required. In that case governance has succeeded operationally while quietly failing developmentally.

This reframes the governance question from evaluating isolated decisions toward understanding developmental trajectories. Conventional governance asks whether a decision was correct. The developmental question asks what that decision is causing people, organisations and institutions to become. Each individual act of delegation may be beneficial on its own terms while the cumulative trajectory moves in a different direction entirely.

Seven human capacities are identified as the subject of that trajectory — the things a governance architecture should be actively preserving rather than passively assuming: independent judgement, contextual interpretation, willingness to question, intervention confidence, relational understanding, pattern recognition, and adaptive learning.

These are the *capacities under stewardship*. They are not the same list as the seven readiness dimensions above, and the two should be held apart. The dimensions describe how readiness is composed in a person at a given moment; the capacities describe what erodes across a trajectory and what governance is therefore responsible for protecting. Pattern recognition appears in both, which is consistent with its status as a foundational dimension.

This layer of the framework is developed through a philosophy series that reads HRA against established intellectual traditions — beginning with Henri Bergson's philosophy of becoming, in which reality unfolds through *durée*, a continuous process in which the past remains active in the present and genuine novelty emerges. Bergson's argument that analysis divides reality into components while intuition perceives living wholes maps directly onto the framework's position that living systems cannot be understood from frozen snapshots alone. Further entries in the series will situate HRA alongside cybernetics, developmental psychology and systems thinking.

---

## The Relational Skill Sets

Frameworks describe what should be preserved. They do not, on their own, tell an operator what to do on a Tuesday afternoon. The skill sets are that layer: a library of 85 modular practice protocols that translate the frameworks into specific, repeatable actions a person or team can perform.

Each skill is a defined procedure with a trigger, a sequence and an intended outcome. They are organised into five source sets and recombined into task-based bundles, so a team addresses an actual operating problem rather than working through a framework in order.

| Source set | Skills | What this layer does |
| --- | --- | --- |
| Foundational | 1–7 | Establishing a working relationship: baseline mapping, contract co-creation, identity anchoring, witness holding |
| Diagnostic | 8–14 | Detecting what has changed, and pressure testing whether it holds |
| Intervention | 15–21 | Acting on what the diagnostics surface |
| Universal Principles in practice | 22–63 | Translating the 21 principles of relational coherence into operational routines |
| Relational Coherence Debt assessment | 64–85 | Assessing accumulated relational cost across 22 dimensions |

In relation to HRA specifically, the skill sets are how readiness is built and maintained rather than merely assessed. The three levels each draw on different bundles: individual capacity development draws on the foundational and principles sets, runtime performance draws on the diagnostic and intervention sets, and enterprise readiness draws on the governance-oriented bundles. A readiness assessment that identifies a deficit without a corresponding practice is an observation, not an intervention. The skill sets are what close that loop.

**Availability.** The skill library is not published in this repository. It is held in a separate access-controlled repository and made available under licence. This README describes the structure and scope of the library so that a reader can understand how the frameworks reach practice, and so that anyone evaluating the work knows the practice layer exists and what it covers. Requests for access should go through the contact below.

One consequence of that decision should be stated plainly: material held in a private repository is access-controlled, not publicly timestamped. It does not establish prior art in the way the dated public articles listed below do. The skill library is therefore protected commercially rather than by publication, and the two forms of protection are not interchangeable.

---

## Relationship to the Wider Framework

HRA is a natural extension of the broader Relational Infrastructure Engineering research programme and one of five operational pillars in the Gaia Nexus architecture, alongside BRIDGE (design), BREAKTHROUGH (evaluation), Relational Coherence Debt (risk) and the 85 skill set library (execution). Its role in that structure is human capacity integration and systemic balancing.

Two connections matter for a reader arriving from elsewhere in this repository. HRA is the operational answer to Proposition 7 of the Signature Principle — that the critical variable in human–AI system performance is human coherence, not AI capability. And it stands in a complementary relationship to Relational Coherence Debt: RCD measures accumulated relational cost across 22 dimensions, while HRA measures the standing condition of the human party. Neither subsumes the other, and reading them as the same construct under different names will produce confusion in both directions.

---

## Public Co-Refinement

HRA is a Gaia Nexus framework built on longitudinal research, but several of its layers were materially sharpened through public dialogue during 2026. That dialogue is documented in `Gratitude_to_Intellectual_Contributors.pdf` in this folder, which names the contributors and identifies precisely which dimension each helped clarify — Eduardo Filho on observer integrity and epistemic survivability, Ricky Jones on oppositional integrity and decision ancestry, Serena D. Hung on institutional contestability and decision legitimacy, and James Aull on bilateral governance and attestation boundaries, alongside further contributors on judgement preservation, cognitive sovereignty, adaptive trust and visibility governance.

That record is kept deliberately. It marks the boundary between the framework's own claims and the contributions of others, and it does so publicly and with dates.

---

## Research and Build Agenda

The measurement problem is the whole of the near term agenda. Stated as the questions that need answering:

**What is the unit of observation at each level?** Level one plausibly admits assessment. Level two requires capturing behaviour at the moment of decision, which means either supervised observation or instrumentation of the workflow itself. Level three is an audit of structure rather than of people. Three levels, three different data collection problems.

**How are the two foundational dimensions assessed?** Psychological readiness and pattern recognition are the hardest of the seven to measure and the most consequential, because they condition the accuracy of everything else. Self-report is least viable precisely here.

**Can behavioural drift be read from system side data?** Approval latency, override rate, review depth and the ratio of accepted to modified recommendations are already logged in most enterprise deployments. Whether they constitute a usable proxy for level two readiness — without new self-report instruments and without surveillance overreach — is the most tractable open question and the most likely route to a first validated measure.

**What are minimum operator standards in a regulated context?** Applying HRA under a regime such as CPS 230 requires a defensible threshold, not a continuous score. Where that threshold sits, and on what evidence, is unresolved.

**Where does HRA attach to an HRL assessment?** If ANSI/HFES 400-2021 certifies a system at HRL 9 and explicitly excludes operator condition from its scope, there is a defined handover point. Specifying what an HRA assessment contributes at that point — and what an organisation should be required to demonstrate about its people once the technology has passed its gate — is the clearest route to institutional adoption.

**Consolidation and permanence.** The published record grows faster than any single document could track it. The intended approach is periodic deposit of the collected material to Zenodo, which issues a DOI without requiring new writing and supports versioning — a new version DOI for each consolidation, with all versions permanently resolvable. This preserves precedence independently of any platform account, and keeps pace with the publication rhythm rather than working against it. The HRL distinction below should be carried explicitly in the next consolidation.

---

## Prior Public Record

Articles are listed oldest first, with original publication dates stated explicitly in the text. GitHub commit timestamps record when a file was uploaded to this repository, not when the work was published, and cannot be backdated — the dates below are the record of precedence.

Where both exist, the Gaia Nexus site URL is listed first and the LinkedIn URL second.

| Date published | Title | Venue | Concept introduced |
| --- | --- | --- | --- |
| 9 May 2026 | *Human Readiness Architecture: The Missing Half of AI Performance Optimisation* — framework deck | [LinkedIn](https://www.linkedin.com/posts/gaianexusonline_human-readiness-architecture-activity-7458748329242431488-0ULv/) | First full statement of HRA: the dyadic performance ceiling, the seven dimensions in two tiers, the machine centric versus bilateral governance shift, and the case for HRA as a distinct discipline |
| 11 May 2026 | *Gratitude to Intellectual Contributors* | [LinkedIn](https://www.linkedin.com/posts/gaianexusonline_gratitude-to-intellectual-contributors-activity-7459570858324496385-TRYo/) | Public record of external co-refinement, naming the four governance branches — observer integrity, runtime readiness, institutional contestability, bilateral governance — and attributing each to its co-refiner |
| *[date]* | *[title]* | *[venue]* | *[concept]* |
| *[date]* | *[title]* | *[venue]* | *[concept]* |
| *[date]* | *[title]* | *[venue]* | *[concept]* |
| 9 July 2026 | *Human Readiness: 5 Proactive Essential Strategies to Protect Corporate Sovereignty* | [gaianexus.online](https://gaianexus.online/2026/07/09/) | The five behavioural markers of capability erosion, and the four phase Evaluate / Define / Track / Train implementation sequence |
| 1 August 2026 | *Beyond Intelligence: Why Human AI Governance Must Also Ask What We Are Becoming* — Philosophy Series, Henri Bergson | LinkedIn | Becoming as a third governance question alongside continuity and living correspondence; the seven human capacities under developmental stewardship; governance as developmental stewardship rather than decision evaluation |
| 1 August 2026 | *The Emerging Governance Capability Most Enterprises Do Not Yet Measure* | LinkedIn | Cross pattern relationships: organisational change that appears between artefacts rather than within any one of them, and the human interpretive capability required to detect it |
| *pending* | *The Governance Capability Your Organisation Will Need to Hire For* | LinkedIn | Cross pattern recognition as a hireable enterprise role: systems literacy across varied system types, apparent unrelatedness as a strengthening signal, recurrence as a marker of trajectory rather than incident, and the access and mandate conditions required to preserve the capability once appointed |

Also in the public record: **What Is Human Readiness?** — [LinkedIn](https://www.linkedin.com/pulse/what-human-readiness-sue-broughton-pbzyc/), the framework's plain language definition for a business audience.

The 9 May 2026 deck is the precedence anchor for the seven dimension specification and the dyadic performance ceiling. The 11 May 2026 contributor record is the precedence anchor for the four governance branches, and is dated two days after the deck — the branches postdate the framework's first full statement and were named through public dialogue.

The revised HRA infographic was produced on 9 May 2026 alongside the deck and carries the same specification. The deck is the dated precedence anchor for that specification.

The philosophy series beginning with Bergson is ongoing. Further entries will be added here as they publish.

Each entry here will link up to the master chronological index at the `2026-initiatives-and-frameworks` level once that index is built.

---

## Contents of This Folder

`Human_Readiness_Architecture.pdf` — the May 2026 framework deck. The fullest single statement of HRA to date, covering the unexamined assumption in AI optimisation, the dyad, the definition and its boundaries, both dimension tiers, the optimisation equation, the symptoms of the invisible gap, the governance shift, the field of practice build-out, and the argument for a distinct category.

`Revised_HRA_Infographic.png` — single page summary of the machine readiness / human readiness split and the seven dimensions grouped as biological, cognitive and relational, and foundational. Produced 9 May 2026 alongside the deck.

`HRA_Philosophy_Series_Bergson.docx` — *Beyond Intelligence: Why Human AI Governance Must Also Ask What We Are Becoming*, published 1 August 2026. First entry in the philosophy series.

`Gaia_Nexus_Architecture_of_Relational_Coherence.pdf` — the system blueprint and deployment topography, showing where HRA sits among the five operational pillars, alongside the capacity and governance topography and the capacity–governance intersection matrix. See the rendering note under The Seven Dimensions.

`Gaia_Nexus_Website_Blog_Human_Readiness.docx` — the business audience essay on human readiness and corporate sovereignty, published 9 July 2026.

`Gratitude_to_Intellectual_Contributors.pdf` — the record of public co-refinement, naming external contributors and the specific dimensions each helped sharpen.

Further articles, and the anchor paper on completion, will be added here.

---

## Citation

> Broughton, S. (2026). *Human Readiness Architecture (HRA)*. Gaia Nexus. Retrieved from https://github.com/gaia-nexus-research/2026-initiatives-and-frameworks

Individual articles should be cited to their original publication date and venue as listed under Prior Public Record.

---

## Contact

Sue Broughton, Founder — Gaia Nexus
[gaianexus.online](https://gaianexus.online/)

Enquiries about access to the relational skill library are welcome via the site.

© 2026 Sue Broughton & Gaia Nexus. All rights reserved.
