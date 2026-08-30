---
title: Accurate, and Still Misleading
short_title: Accurate, and Still Misleading
published: 2026-08-27
platform: LinkedIn (Gaia Nexus Online)
type: article with accompanying post
series: AI Value and Governance (part 2)
url: https://www.linkedin.com/pulse/accurate-still-misleading-sue-broughton-ela8c/
post_url: https://www.linkedin.com/feed/update/urn:li:ugcPost:7498589026292150273/
frameworks: [CCG]
emerging_themes: [evidence not transferring across state transitions, organisational absorption as the binding constraint on AI scaling]
record: accurate-and-still-misleading.pdf
---

# Accurate, and Still Misleading

**Accurate, and Still Misleading**
Published 27 August 2026 · [Read on LinkedIn](https://www.linkedin.com/pulse/accurate-still-misleading-sue-broughton-ela8c/)

Second in the AI value and governance series: Value → Representation → Redistribution → Continuing Reliance.

The full record — post, image, article text and the public discussion that followed — is in the accompanying PDF.

---

## What this article argues

A figure on an executive dashboard is correctly calculated, auditable, and drawn from sound data. The problem is not whether the number is true. It is what management takes the number to mean — and the same failure can run in opposite directions.

**Case one.** AI removes the equivalent of $5 million of work. The hours are genuinely released, but the employees remain and are still paid. Some released capacity converts into identifiable value — an avoided hire, additional output, an earlier product launch. Some disappears into existing workloads and work already waiting. Meanwhile AI creates new work: review, exception handling, workflow redesign, supervision, increased governance requirements. The dashboard accurately reports $5 million removed while the business retains considerably less. The organisation **overestimates what it gained**.

**Case two.** A system provisioned for 1,000 requests per second runs at about a third of that. Read as an efficiency measure the conclusion looks obvious — capacity is being paid for and not used, so reduce it. But average demand does not explain why the headroom exists. Demand arrives unevenly; peaks, exceptions and recovery all matter, and a system near its limit behaves differently from one under average load. The headroom is not necessarily slack. It may be the control. The organisation **underestimates what it needs**.

The article's central move is to put these side by side and show they are the same error. Both occur because the organisation can see the number without seeing the conditions surrounding it. Stated as a principle: an organisation can optimise away a control because its measurement system cannot distinguish necessary resilience from waste.

From there the argument extends to redistribution. AI is usually described as subtractive — it removes tasks, hours, manual processes. At organisational level it also redistributes demand, and the new demand does not necessarily appear where the saving occurred. A customer-service team may release thousands of hours while assurance workload rises elsewhere; a finance process may accelerate while exception handling concentrates among a handful of experienced people. So hours saved and organisational capacity gained are not the same thing — and the additional demand may land precisely in the functions the organisation depends upon to keep AI safe and bounded.

The article closes on the practical reframing: an accurate number can still support the wrong decision, and the most important information is sometimes hidden not because nobody measured it, but because one part of the system was measured and assumed to describe the whole.

---

## Where this connects

**Coherence Centric Governance.** This is the article that gives CCG its economic argument. It states the framework's commercial question directly: what demand is AI creating across the organisation, what capacity exists to absorb it, how heavily is that capacity being used, and where is the organisation approaching saturation? That is Coherence Utilization (skill 87) and Saturation Detection (skill 88) expressed as a board-level question, and the closing "can the organisation scale with it?" is Load Forecasting (skill 90) — projecting demand before new work is committed.

The article also does something the first one did not: it argues the *positive* case for visibility. Governance is usually sold through prevention — avoid the failure, stop the bad decision. Here better visibility may equally support proceeding with greater confidence, preserving capacity the next expansion will need, adding capacity to an overloaded review function before deployment, or scaling faster than expected. The objective is neither maximum nor minimum automation but better allocation of capital. That is a materially different sales argument for CCG and worth noting as the place it first appears.

**The measurement discipline is formalised here.** Article 1 stated it in a comment reply; this article develops it into method. Measure released capacity once, then follow what it becomes. A thousand released hours establish a capacity gain and not a financial return. If they avoid a planned hire, measure the avoided cost; if they enable output, measure the output; if they shorten a cycle with identifiable economic value, measure that. If they simply return to existing workload, acknowledge the productivity benefit but do not quietly convert the wage-equivalent into cash savings never realised. And measure the new demand separately — where review increased, where exception handling rose, where governance load appeared, where human attention concentrated.

The rejection of a single composite figure is deliberate and worth preserving: a single "AI value" number risks recreating the problem the article is describing.

**Absorption ceiling.** Ravi Shankar NRK's concept from the Article 1 discussion is named in the body here and becomes load-bearing. Within the corpus it is covered by CCG skills 87, 88 and 90 rather than being an open question.

Not materially connected to RCD, HRA, the Signature Principle, or BRIDGE and BREAKTHROUGH.

---

## Notes for technical readers

Both cases are constructed illustrations. The 1,000-requests-per-second system and the one-third utilisation figure come from Ravi Shankar NRK's Governance Tax work as characterised in the article, not from a measured deployment. Nothing here is a case study.

The mirror-image claim is the article's strongest analytical move and also its least tested. Overestimating retained value and underestimating required headroom are presented as economically symmetric because both stem from reading a number without its surrounding conditions. That symmetry is asserted rather than demonstrated, and the two errors may not be equally tractable — the first is a measurement discipline problem, while the second requires valuing capacity that only shows its worth when it is needed. The article does not resolve the second, and the valuation gap it leaves open is picked up in part four.

The reserve-capacity argument has a boundary the article does not draw. "The headroom is not necessarily slack, it may be the control" is a caution against assuming idle capacity is waste. It is not evidence that any particular idle capacity is a control, and used carelessly it would justify any level of overprovisioning. The article's own answer is the right one — the organisation should be able to show what the capacity protects, what demand it absorbs and what happens without it — but that requirement is stated once and could be missed.

---

## Emerging themes

**Evidence not transferring across state transitions.** Raised by Ricardo Muro, who read the measurement discipline as an architectural principle: a measurement can stay perfectly valid while the standing of conclusions drawn from it weakens further along the decision chain. He proposed keeping the transitions separate — work removed, capacity released, capacity actually available, capacity reallocated, value produced, value retained — on the basis that evidence establishing one does not automatically establish the next. This is more general than the article's own framing and is the strongest candidate here for formal treatment. It recurs in part four as indicator meaning drift.

**Organisational absorption as the binding constraint on AI scaling.** Emerged in exchange with Mo Johnson, who observed that released capacity and retained value diverge most sharply when the organisation itself becomes the constraint. The reply developed it further: once that happens, further AI capability can increase technical capacity while reducing the organisation's ability to convert it into value — so the next constraint in AI scaling may not be the model at all, but organisational absorption capacity. That is a claim about where the industry's limiting factor sits, broader than any single framework currently covers.

Ricardo Muro also raised the temporal question — what happens when verification load, exception demand or absorption capacity changes between the approval and the next scaling decision, so that the number remains true while the conditions that made it decision-relevant no longer hold. That is not recorded as an open theme because part four takes it up directly as continuing reliance.

---

## The discussion

Credited in the article, from the part one discussion:

- **Commander Ravi Shankar NRK** — the Governance Tax, which supplied the counter-example of apparently unused capacity performing a necessary control function, and the absorption ceiling concept that extends the argument into scaling
- **Olga Kalinina** — the question about measuring kept value against reallocated capacity, which prompted the measurement discipline developed here

Public discussion following publication:

- **Mo Johnson** — released capacity and retained value as distinct, particularly once the organisation becomes the constraint
- **Ricardo Muro** — the transition chain and the standing of derived conclusions; the reserve-capacity inverse, where optimisation can remove a control while accurately reporting improved efficiency; and the temporal question

---

## Provenance note

Published 27 August 2026. This is the dated public statement of the mirror-image problem — that overestimating captured value and underestimating necessary headroom are the same measurement failure in opposite directions — of the principle that an organisation can optimise away a control its measurement system cannot distinguish from waste, and of the measurement discipline of following released capacity to what it becomes rather than converting it directly into claimed savings.

---

*Gaia Nexus · Sue Broughton · 2026*
