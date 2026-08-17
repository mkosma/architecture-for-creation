# Chironic Deck Proof DAG
## Draft 01, revised same day to a DAG per the 2026-08-17 dialogue's closing amendment

- **Audience:** seed investors (the deck this map governs is the investor deck; customer and recruit artifacts derive separately)
- **Built against:** Kernel draft 0.2 (`09-kernel/architecture-kernel.md`)
- **Sources:** Discovery Session 001; the three-way deck dialogue of 2026-08-17 (`00-discovery-sessions/discover-session-002.md`, and the ChatGPT-side session pending capture as 003); the 2026-08-15 deck held as primary artifact in `04-case-studies/`
- **Method:** this is a directed acyclic graph, not a tree. Every node is a proposition; every edge is a "therefore"; and load-bearing nodes deliberately feed multiple downstream conclusions (see the cross-edge table), so that a single proposition can support product, GTM, and moat without duplication. Slides are then projections of connected regions of the DAG, laid out from the graph, never the reverse.
- **Two completion tests.** (1) *Discharge:* every open branch must be closed by a product layer; a node that discharges into nothing gets cut. (2) *Lineage:* every product feature, GTM choice, and moat claim must trace back through the DAG to one or more observed facts with no hidden "therefore." When both tests pass, the narrative is ready; "does it feel persuasive" is not the standard.

---

## The graph

```
     N1  Executives begin legal reasoning with AI
            │
            ▼
     N2  This has two independent causes
            │
    ┌───────┴────────┐
    ▼                ▼
   N3a              N3b
ECONOMICS         PREFERENCE
Most questions    Even at zero price,
were rationally   AI is chosen first:
unasked (Hand).   immediate, iterative,
AI collapses B;   candid, no social
the feasible set  friction. An inter-
expands; latent   active reasoning
demand surfaces.  partner.
    │                │
    └───────┬────────┘
            ▼
     N4  WHAT'S SO: the legal dialogue has
         already relocated to AI
            │
    ┌───────┴────────┐
    ▼                ▼
   N5a              N5b
DEFICIENCY 1      DEFICIENCY 2
The forum is      The forum is
discoverable;     unsupervised;
the transcript    residual error the
is evidence and   asker cannot price;
candor is         reliance is unsafe.
punished.
    │                │
    └───────┬────────┘
            ▼
     N6  UNIQUENESS: privilege and professional
         accountability attach only through a
         licensed attorney. No AI company can
         supply either.
            │
            ▼
     N7  DESIGN PRINCIPLE: every question should
         receive exactly as much expertise as its
         expected value justifies. Known since
         1947; newly satisfiable.
            │
            ▼
     N8  ARCHITECTURE = workspace + triage + attorney
         (each layer discharges one open branch)
            │
            ▼
     N9  Product (the architecture, implemented)
            │
            ▼
     N10 Attorneys will distribute it
         (incentive premise for GTM)
            │
            ▼
     N11 GTM  →  N12 Business model  →  N13 Market
            │
            ▼
     N14 Moat (institutional, not generic)
            │
            ▼
     N15 Team (the explanation)  →  N16 Ask
```

## Cross-edges (what makes this a DAG rather than a tree)

The spine above shows the primary "therefore" chain. These additional edges are equally real, and they are why the load-bearing propositions must not be duplicated slide-by-slide: each is established once and then projected wherever it is needed.

| From | Also feeds | Why |
| --- | --- | --- |
| N3a Economics (Hand) | N7 design principle; N12 business model; N13 market | The same formula sets the triage threshold, the pricing logic, and the latent-demand sizing |
| N3b Preference (reasoning partner) | N8 workspace layer; N13 why-now | The preference dictates the workspace's design constraints and predates model quality, anchoring durability |
| N5a Discoverable (Krafton) | N14 moat | The discoverability defect is also the permanent differentiation against every non-attorney vendor |
| N6 Uniqueness (privilege, Upjohn/Hickman; ownership rules) | N8 architecture; N11 GTM; N14 moat | One institution simultaneously forces the attorney layer, blesses the firm channel, and bars AI-company entry |
| N7 Design principle | N8 triage layer; N12 pricing; N9 product spec | One sentence, three implementations |
| N10 Attorney incentives (the mirror) | N11 GTM; N12 business model; N14 moat | The same escalation event is distribution motive, revenue mechanic, and switching cost |
| N13 Why-now (feasible set expands with model quality) | N14 moat; N16 ask | Long-AI-progress positioning underwrites both defensibility and the milestone plan |

Projection rule for slides: a slide may render any connected region of the DAG, but every proposition it asserts must appear as a node here first. If slide copy needs a claim with no node, the DAG is incomplete; add the node before writing the copy.

## The discharge test (why the reveal is an "of course")

The three product layers are the proof's merge point. Each exists because one open branch demands it:

| Product layer | Discharges | How |
| --- | --- | --- |
| Cognitive workspace | N3b (preference) | Keeps everything the user already chose AI for: immediacy, iteration, candor |
| Intelligent triage | N7 (design principle) | Allocates expertise in proportion to expected value; the Hand formula operationalized |
| Attorney judgment | N5a + N5b, via N6 | Privilege cures discoverability; supervision cures unpriced error; only an attorney can supply both |

If a proposed slide or feature discharges no branch, it is decoration. If a branch reaches the architecture undischarged, the proof is broken.

---

## Node metadata

Columns per node: proposition · evidence · likely objection · transition ("therefore") · candidate visual · Kernel element expressed.

### N1 — Executives begin legal reasoning with AI

- **Proposition:** The first conversation about a legal question increasingly happens with an AI, not a lawyer.
- **Evidence:** Krafton (Del. Ch. 2026, chat logs reconstructed and quoted); Ronen's client behavior; the HR-manager pattern. `[NEED: Larry Tu observation and the law-school observation, currently uncaptured — see TODO]`
- **Objection:** "Anecdotes." Counter: the Krafton opinion is a court record; add usage data from Breeze pilots as it accrues.
- **Transition:** Something changed; what?
- **Visual:** The Krafton opening line as pull-quote.
- **Kernel:** Step 0 (What's Surprising?) / Step 1 (What's So?).

### N2 — Two independent causes

- **Proposition:** No single mechanism explains N1; there are exactly two, and they are separable.
- **Evidence:** The zero-marginal-cost preference (N3b) is invisible to the fee model (N3a); each observation set fits one branch.
- **Objection:** "Isn't this just 'AI is cheap and convenient'?" Counter: cheapness cannot explain preference at zero price; convenience cannot explain the volume expansion. Two claims, two proofs.
- **Transition:** Take each in turn.
- **Visual:** None; this is a section pivot, likely a headline on N3a's slide.
- **Kernel:** Step 2 (What Is Changing?).

### N3a — Economics (the extensive margin)

- **Proposition:** Under hourly billing, most small-business legal questions were rationally unasked: the fee exceeded the risk a review removes (Hand formula, Carroll Towing). AI collapses B, the feasible set expands, and latent demand surfaces.
- **Evidence:** The Hand-formula chart pair from the 2026-08-15 deck (Shaun MaGruder: right not to call at $69k break-even; calls at a tenth the cost; the two findable defects). This pair survives any redesign.
- **Objection:** "Your break-even parameters are assumptions." Counter: the deck already sets them out to be argued with; keep that posture.
- **Transition:** But cost cannot be the whole story, because...
- **Visual:** The existing before/after Hand curves, unchanged.
- **Kernel:** Production Function distinction; Step 2.

### N3b — Preference (the interactive reasoning partner)

- **Proposition:** Even where counsel is effectively free, people go to the AI first: it is immediate, endlessly iterative, psychologically safe, and available without scheduling or social friction. What is being consumed is not answers but counsel in the old sense: a partner for thinking, exploring, drafting, comparing, rehearsing.
- **Evidence:** Krafton CEO (counsel on retainer, asked the bot); Ronen's executives; the HR manager drafting. `[NEED: capture the non-anecdotal version if any exists — in-house counsel utilization data, pilot telemetry]`
- **Objection:** "This is a fad / model quality will disappoint." Counter: better models strengthen the thesis (see N13's why-now); the behavior predates good models.
- **Naming:** open decision — "cognitive workspace" vs. "interactive reasoning partner" vs. reclaiming **counsel**. Current recommendation: counsel. `[NEED: Monty's call]`
- **Transition:** So the dialogue has already moved. Where did it move to?
- **Visual:** Side-by-side: what the AI conversation offers vs. what a scheduled call offers.
- **Kernel:** Step 1; the Attention distinction.

### N4 — What's So: the dialogue has relocated

- **Proposition:** The combination of N3a and N3b means the first-pass legal conversation now happens, at volume, inside AI chat windows. This is the behavior; it will not reverse.
- **Evidence:** "This is not a behavior change. It is the behavior" (2026-08-15 deck, slide 4).
- **Objection:** "Enterprises will ban it." Counter: bans against economically rational, privately conducted behavior fail; see shadow IT generally.
- **Transition:** And the forum it moved to has two defects.
- **Visual:** Possibly none; strong headline.
- **Kernel:** Step 1; Reality comes before theory.

### N5a — Deficiency 1: discoverable

- **Proposition:** The AI transcript is evidence. Candor in the new forum is punished exactly where it matters most.
- **Evidence:** Krafton: logs deleted, reconstructed anyway, quoted as affirmative proof of pretext; CEO's candid exploration became the plaintiff's case.
- **Objection:** "Vendors will offer confidentiality." Counter: contractual confidentiality is not privilege; discovery reaches it. Only N6 cures this.
- **Transition:** And even a safe transcript could be wrong...
- **Visual:** The Krafton slide, essentially as-is.
- **Kernel:** Step 5 (how the legal system responds to the new behavior); Institutions distinction.

### N5b — Deficiency 2: unsupervised

- **Proposition:** The DIY answer carries residual error the asker cannot assess or price; relying on it is unsafe in precisely the cases that matter.
- **Evidence:** Shaun's two defects: cheap to fix, findable, missed.
- **Objection:** "Models will get accurate enough." Counter: accuracy without accountability still leaves the asker holding unpriced tail risk; and the better the model, the higher the stakes of the questions users trust it with.
- **Transition:** Both defects have a single available cure.
- **Visual:** The two defects, named, with their fix cost vs. exposure.
- **Kernel:** Step 5; Reality remains the final judge.

### N6 — Uniqueness: only through an attorney

- **Proposition:** Privilege and professional accountability attach only through a licensed attorney. No AI company, at any scale, can supply either. The doctrine's own rationale is the point: privilege exists to enable full and frank communication (Upjohn), and work-product doctrine protects a zone of private thought (Hickman). The law already assumes candid inquiry needs protection; AI finally makes the protected version continuously available.
- **Evidence:** Upjohn v. United States, 449 U.S. 383 (1981); Hickman v. Taylor, 329 U.S. 495 (1947); state ownership rules (49 states) as the structural barrier to AI companies acquiring firms. `[NEED: cite-check both cases and the 49-state count before shipping]`
- **Objection:** "Privilege could be legislated for AI." Counter: no such statute exists or is proposed; the trend (Krafton) runs the other way; and if one ever passed, Chironic's triage-and-supervision layer still discharges N5b.
- **Transition:** Given the cure is attorneys, the design question becomes allocation...
- **Visual:** Perimeter-of-privilege diagram (from the existing deck's slide 6, upgraded).
- **Kernel:** Property Rights and Institutions distinctions; Resistance reveals architecture.

### N7 — Design principle

- **Proposition:** Every question should receive exactly as much expertise as its expected value justifies. This is the Hand formula generalized from precaution to expertise. The rule has been optimal since 1947; it was unsatisfiable at old prices. AI expands the feasible set, so the optimum moves.
- **Evidence:** Follows from N3a; Carroll Towing citation already in the deck.
- **Objection:** "Sounds academic." Counter: it is one sentence, and it is the sentence the whole product implements; investors who dislike theory get it as the triage layer's spec.
- **Transition:** An architecture that satisfies this principle, under N6's constraint, looks like...
- **Visual:** One line of type. This is a header, not a diagram.
- **Kernel:** the two Enduring Questions, jointly; Production Function.

### N8 — Architecture

- **Proposition:** Workspace + intelligent triage + attorney judgment. Each layer discharges one open branch (see discharge table). The architecture is therefore not a design choice among many; it is the unique shape that closes the proof.
- **Objection:** "Why won't incumbент legal-AI vendors add supervision?" Counter: their customer is the firm's existing billable work (efficiency), not the unserved client; and N6's ownership rules bar them from becoming firms. Defer full version to N14.
- **Transition:** Implemented, it is...
- **Visual:** The three layers with the branch each discharges, literally annotated. This diagram is the deck's centerpiece.
- **Kernel:** Step 4 (What Might We Create?); Form and function should embody one another.

### N9 — Product

- **Proposition:** The architecture exists as software today: privileged client channels, supervision console, attorney workflows, practice knowledge. Alpha now, partner beta next month.
- **Evidence:** 2026-08-15 deck slide 7; zero-data-retention agreements; SOC 2 timeline.
- **Objection:** "Demo or it didn't happen." Counter: screens, and Breeze usage as it lands.
- **Visual:** Product screens.
- **Kernel:** the Threshold (this is below-the-line work meeting reality).

### N10 — Attorneys will distribute it (GTM premise)

- **Proposition:** Lawyers adopt what raises their revenue, deepens client relationships, and defends them from the BigLaw-plus-DIY squeeze; the same triage event that serves the client creates the attorney's billable review and early visibility. The routing of a question is the routing of a customer: the incentive mirror.
- **Evidence:** Session 001's Step 5 harvest (recurring revenue, more interesting work, closer relationships, protection, visibility); Breeze's live fractional-GC conversions.
- **Objection:** "Lawyers are technophobic and slow." Counter: the buyer's alternative is marginalization; and the first cohort is hand-picked law-and-economics literate firms.
- **Transition:** Which makes the channel...
- **Visual:** The mirror: question-routing and customer-routing as one diagram.
- **Kernel:** Step 5; Incentives distinction; Resistance reveals architecture (incumbent enrollment).

### N11 — GTM

- **Proposition:** Trusted-attorney relationships are the distribution channel; the Chicago law-and-economics network primes it; partner-firm referral economics sustain it. Structurally advantaged because the incumbent is enrolled, not fought.
- **Evidence:** Existing deck slide 12 (+ its [NEED]s, which stand until filled).
- **Kernel:** Step 5.

### N12 — Business model

- **Proposition:** Subscription (client) + billable review (firm) + the incentive mirror of N10; everyone's payoff rises with usage.
- **Evidence:** Existing deck slide 8; pricing `[NEED: price per seat]`.
- **Kernel:** Value Creation vs. Value Capture.

### N13 — Market

- **Proposition:** Size the market the new equilibrium creates (latent demand surfaced), not existing legal spend; ~700K small-firm attorneys as the seat ceiling, with the assumption chain stated honestly. Why now, stated as feasible-set expansion: better models lower the DIY ceiling further and concentrate residual value in supervision, so Chironic is long AI progress, not exposed to it.
- **Evidence:** Existing deck slide 11 and its sourcing discipline; keep every [NEED] visible.
- **Kernel:** What Is Changing?; the honesty norms (reality as judge).

### N14 — Moat

- **Proposition:** The moat is institutional, not generic: attorney-client privilege; attorney supervision; regulatory ownership rules (49 states); incumbent enrollment (the objectors become the channel); DIY as the real substitute while Harvey/CoCounsel sell efficiency on already-billed work; small-firm linchpin incentives. Workflow lock-in and data effects are consequences, not the moat.
- **Evidence:** Existing deck slide 13 + Session 001 Step 5 discoveries.
- **Objection:** "BigLaw comes down-market." Counter: that threat is the sales pitch to small firms (the squeeze), and BigLaw's cost structure prevents serving this segment at these prices.
- **Kernel:** Step 5; Institutions.

### N15 — Team

- **Proposition:** The team is the explanation, not the résumé: a law-and-economics founder who spent a decade running system-response analysis on mergers, a 500-deal startup lawyer, a platform CTO, practicing-attorney vertical leads. The deck's argument is the way this team thinks; the team slide shows why that argument occurred to them first.
- **Evidence:** Existing deck slide 14, reframed.
- **Kernel:** the Origin (the Architecture as the founder's method).

### N16 — Ask

- **Proposition:** Up to $1M SAFE to prove the motion repeats outside Breeze; gating milestone; use of funds. One restrained line, at most, on the Level 1 generalization (the architecture applies wherever expertise is expensive, an institution protects candor, and incumbents can be enrolled), and no more.
- **Evidence:** Existing deck slide 15.
- **Kernel:** Conviction → Declaration → Creation; claims must not outrun the Kernel.

---

## Open decisions and [NEED]s

1. **Naming of N3b's capability** (workspace / reasoning partner / counsel). Recommendation on the table: counsel. Monty decides.
2. **Larry Tu, law-school, GC/founder/salesperson observations**: uncaptured evidence; only Krafton, Ronen, and the HR manager are usable until the source conversations are exported (session 003).
3. **Cite-check** Upjohn and Hickman quotes and the 49-state ownership figure before any external use.
4. **All inherited [NEED]s** from the 2026-08-15 deck (price per seat, market multipliers, GTM funnel counts) remain open and remain visibly bracketed.
5. **Level 1 material** (general architecture: reasoning partner + trust institution + incumbent enrollment) is deliberately excluded from this deck beyond N16's single line; it enters the repository through `06`/`07`/`09` before appearing in any artifact. Not yet written.
6. **Timebox honored:** this map supersedes the four-layer stack and the six-column table (their columns are absorbed as node metadata), and the DAG amendment of 2026-08-17 is incorporated above as a refinement of this artifact, not a replacement of it. Next artifact is slides, laid out as projections of this DAG. No further ontology revision before the slide pass; new propositions discovered while drafting slides enter as nodes here first, per the projection rule.
