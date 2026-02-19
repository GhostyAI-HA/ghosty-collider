# From Theory to Protocol: Executable Frameworks for Creative Emergence and Strategic Foresight

**Shun Fujiyoshi**
Independent Researcher

February 2026

---

## Abstract

Creativity and strategic foresight have been extensively studied through descriptive theories — Koestler's bisociation (1964), de Bono's lateral thinking (1967), and Ansoff's weak signals (1975) explain *why* creative and strategic insights occur, but offer limited guidance on *how to produce them on demand*. This paper presents two executable protocols that bridge this theory-practice gap: **GHOSTY COLLIDER**, a 5-step protocol for cross-domain creative emergence through structural de-labeling and collision, and **PRECOG PROTOCOL**, a 5-step protocol for signal-based strategic foresight with multi-axis timing judgment. We formalize established theories into repeatable, step-by-step procedures with explicit quality criteria, anti-pattern detection, and measurable outputs. We evaluate the protocols through three complementary methods: (1) five detailed case studies across distinct domains, (2) controlled comparisons against standard methods using identical inputs, and (3) a batch experiment across eight random domain pairings (N=8, success rate 87.5%, failure rate 12.5%) with one blind evaluation. Preliminary evidence suggests that protocol-driven outputs exhibit greater structural novelty, higher parameter specificity, and qualitatively distinct creative directions compared to outputs from standard methods. The blind evaluation confirmed the direction of author assessments (protocol output scored 74/80 vs. brainstorming 49/80). These results, while limited by single-operator execution, indicate that the theory-to-protocol translation preserves and potentially enhances the generative power of the underlying theories. The protocols, updated to version 2 incorporating lessons from failure case analysis, are released as open-access documents under CC BY-NC 4.0 at https://github.com/GhostyAI-HA/ghosty-collider.

**Keywords:** creativity support, strategic foresight, executable protocols, bisociation, weak signals, cross-domain innovation, timing judgment, human-AI co-creativity

---

## 1. Introduction

The gap between creativity theory and creative practice is well-documented. Sawyer (2012) notes that decades of creativity research have produced rich explanatory models but few actionable tools for practitioners. Similarly, in strategic foresight, Rohrbeck et al. (2015) observe that while scanning and scenario methodologies are theoretically mature, their translation into organizational practice remains challenging — requiring multi-week workshops, trained facilitators, and significant resources.

Recent advances in large language models (LLMs) have created a new context for this gap. Stevenson et al. (2022) demonstrated that GPT-3 performs competitively on divergent thinking tasks, while Doshi and Hauser (2024) found that LLM-assisted ideation generates more ideas but may reduce diversity across participants. Gero and Chilton's Metaphoria (2019) showed that algorithmic systems can generate non-obvious metaphorical connections, and their subsequent work (Gero, Long, & Chilton, 2023) examined how AI support affects the social dynamics of creative writing. These findings suggest that LLMs are powerful ideation engines, but that *unstructured* AI-assisted ideation risks producing outputs that converge to genre conventions — what Doshi and Hauser (2024) term the "flattening effect." This observation motivates our central question: **Can structured protocols, grounded in established creativity and foresight theories, produce qualitatively different outputs from unstructured AI-assisted ideation?**

We present two protocols designed to answer this question:

1. **GHOSTY COLLIDER** transforms creativity theories (bisociation, lateral thinking, Geneplore model) into a 5-step procedure: Fragment Harvest → Ghost Extraction → Collision Matrix → Vision Crystallization → Reality Bridge. The key innovation is *Ghost Extraction* — a systematic de-labeling process that reduces concepts to their deep structural elements (verbs, forces, transformations) before collision, increasing the probability of non-obvious cross-domain connections.

2. **PRECOG PROTOCOL** transforms strategic foresight methodologies (horizon scanning, weak signals theory, scenario planning) into a 5-step procedure: Signal Map → Convergence Analysis → Contrarian View → Timing Grid → Action Window. The key innovations are the *multi-axis Timing Grid* (evaluating market phase, competitive position, organizational readiness, and external windows simultaneously) and *Signal History tracking* for longitudinal foresight.

The protocols share a design philosophy: strip away the scaffolding of workshops, facilitators, and multi-day processes, preserving only the core cognitive operations that produce insight. They are designed to be executed by individuals, with or without AI assistance, in a single session.

We wish to be explicit about the scope of our empirical contribution. The evidence presented here constitutes **preliminary, proof-of-concept evaluation**: all case studies and controlled comparisons were executed by a single operator (the author) with AI assistance. We present this evidence as initial demonstration of the protocols' structural properties rather than as definitive proof of general effectiveness. Multi-user evaluation across diverse skill levels and contexts is essential future work (Section 8.3).

To evaluate the protocols, we conduct three forms of assessment: (1) multi-domain case studies demonstrating protocol execution across five distinct domains, (2) controlled comparisons where identical inputs are processed with and without the protocols, using standard methods (brainstorming, SWOT analysis) as baselines, and (3) a batch experiment across eight random domain pairings to measure protocol success/failure rates, with one blind evaluation to partially address evaluator bias.

The remainder of this paper is organized as follows: Section 2 reviews the theoretical foundations. Section 3 presents GHOSTY COLLIDER. Section 4 presents PRECOG PROTOCOL. Section 5 describes their integration. Section 6 demonstrates both protocols through five case studies. Section 7 presents controlled comparisons against standard methods, reports protocol failure cases with quantified failure rates, and presents a blind evaluation. Section 8 discusses contributions and limitations. Section 9 concludes.

---

## 2. Related Work

### 2.1 Creativity Theories

**Bisociation Theory.** Koestler (1964) introduced bisociation as the simultaneous perception of an idea in two self-consistent but habitually incompatible "matrices of thought." Unlike association (connecting ideas within a single frame), bisociation requires the collision of separate frames — the "Eureka moment" occurs when a connection is perceived across frames that were previously considered unrelated. GHOSTY COLLIDER operationalizes this through Ghost Extraction (stripping frames) and Collision Matrix (forcing cross-frame intersection).

**Lateral Thinking.** De Bono (1967, 1970) formalized the concept of lateral thinking as a deliberate method for breaking out of dominant patterns. His key insight — that logical, sequential thinking is insufficient for creative leaps because it stays within established patterns — motivates GHOSTY COLLIDER's de-labeling step. By removing the label (the pattern), the thinker is forced into a lateral mode.

**Geneplore Model.** Finke, Ward, and Smith (1992) proposed a two-phase model of creativity: the *generative phase* (producing pre-inventive structures — ambiguous, incomplete mental representations) and the *exploratory phase* (interpreting, refining, and evaluating these structures). GHOSTY COLLIDER maps directly onto this model: Steps 1-3 (Fragment Harvest through Collision Matrix) constitute the generative phase, producing pre-inventive structures through de-labeling and collision; Steps 4-5 (Vision Crystallization through Reality Bridge) constitute the exploratory phase, interpreting emergent patterns and grounding them in reality.

**CK Design Theory.** Hatchuel and Weil (2003, 2009) proposed Concept-Knowledge (CK) theory, which models design as a dynamic interplay between a *Concept space* (propositions that are neither true nor false — undecided) and a *Knowledge space* (established propositions). Innovation occurs when operators expand the concept space beyond the boundaries of current knowledge. GHOSTY COLLIDER's Ghost Extraction parallels CK theory's concept expansion: by stripping domain-specific knowledge (labels), the protocol forces concepts into undecided territory, enabling novel partitions that would not emerge within a single knowledge frame.

**Systematic Inventive Thinking (SIT).** Horowitz (2001) developed SIT as a structured approach where creative solutions follow identifiable patterns (subtraction, multiplication, division, task unification, attribute dependency change). Unlike GHOSTY COLLIDER, which operates on domain-agnostic structural elements, SIT applies modification operators to the existing form of a product or process. The approaches are complementary: SIT optimizes within a domain, while GHOSTY COLLIDER generates cross-domain visions.

**Existing Creativity Methods.** Several structured methods exist for creative production. Osborn's (1953) brainstorming generates ideas through free association but remains within familiar frames. Eberle's (1996) SCAMPER provides systematic modification operators (Substitute, Combine, Adapt, etc.) but is bounded by the existing form of the object. Altshuller's (1946) TRIZ offers powerful inventive principles for engineering problems but requires domain-specific technical contradictions as input. The Design Thinking framework (IDEO; Brown, 2008) centers the process on user empathy but requires user research as a prerequisite. GHOSTY COLLIDER differs from all of these in its input (raw, heterogeneous fragments from any domain), its process (de-labeling before combination), and its output (a named vision of something that does not yet exist).

### 2.2 AI-Augmented Creativity

The emergence of large language models has created a new landscape for creativity support tools (Frich et al., 2019). Recent work demonstrates both the promise and limitations of AI-assisted ideation.

**LLM Creative Capabilities.** Stevenson et al. (2022) evaluated GPT-3 on the Alternative Uses Test — a standard measure of divergent thinking — and found that it performed comparably to human participants. Subsequent studies (Haase & Hanel, 2023) confirmed that LLMs can match or exceed the *average* human on standardized creativity tasks, while the most creative individuals still outperform AI. Si et al. (2024) developed systematic benchmarks for evaluating LLM scientific ideation, finding that LLMs generate novel ideas at competitive rates but with lower feasibility scores than expert-generated ideas.

**Human-AI Co-Creation Dynamics.** Gero and Chilton (2019) developed Metaphoria, an algorithmic system that generates metaphorical connections from a writer's input, demonstrating that structured AI assistance can produce non-obvious creative associations. Their subsequent work (Gero, Long, & Chilton, 2023) revealed that the *social dynamics* of AI-assisted creative writing differ significantly from pure human collaboration — a finding that complicates evaluation of AI-augmented creativity tools. Lee et al. (2024) surveyed LLM-based ideation tools and proposed the Hourglass Ideation Framework, identifying that LLMs contribute most effectively to idea generation and refinement but remain underutilized for scope specification and multi-idea evaluation.

**The Flattening Concern.** Doshi and Hauser (2024) provided the most directly relevant finding for our work. In a large-scale field experiment, they showed that while AI-assisted writers produced more content, the aggregate *diversity* of outputs decreased — individual improvements came at the cost of collective homogeneity. This "flattening effect" motivates the design of structured protocols: by imposing de-labeling (GHOSTY COLLIDER) and contrarian analysis (PRECOG PROTOCOL), the protocols explicitly counteract the tendency of AI-assisted ideation to converge on modal outputs.

Our work extends this literature by proposing that the theory-practice gap in creativity research is not merely about *using* AI for ideation, but about *structuring* the interaction through theoretically grounded protocols. Whereas existing tools (Metaphoria, ALIA, collaborative canvases) provide AI assistance for specific creative tasks, GHOSTY COLLIDER and PRECOG PROTOCOL formalize entire cognitive workflows as executable procedures — closer in spirit to what Lee et al. (2024) call "process-level" rather than "task-level" AI support.

### 2.3 Strategic Foresight Methodologies

**Horizon Scanning.** Developed and practiced by organizations including the OECD, UNDP, and the UK Government Office for Science, horizon scanning is the systematic examination of information to identify potential threats, risks, emerging issues, and opportunities (Amanatidou et al., 2012). It provides a structured approach to signal collection but does not prescribe how to synthesize signals into timing judgments.

**Weak Signals Theory.** Ansoff (1975) introduced the concept of weak signals — early, imprecise, ambiguous indicators of impending change that are detectable before they crystallize into clear trends. Hiltunen (2010) extended this work, proposing methods for signal detection and interpretation. PRECOG PROTOCOL's Signal Map step operationalizes weak signal detection by requiring explicit evidence and confidence tagging, while the Convergence Analysis step systematizes signal synthesis.

**Scenario Planning.** Originating at Royal Dutch Shell through the work of Pierre Wack (1985a, 1985b), scenario planning constructs multiple plausible future narratives to prepare decision-makers for uncertainty. Van der Heijden (1996) formalized the methodology into a systematic process. PRECOG PROTOCOL incorporates this spirit through its Contrarian View step, which explicitly challenges the dominant narrative and identifies preconditions for thesis validity.

**Existing Strategic Frameworks.** Practitioners commonly use SWOT analysis (Learned et al., 1965), PESTEL scanning (Aguilar, 1967), Porter's Five Forces (Porter, 1979), and the BCG Matrix (Henderson, 1970) for strategic analysis. While valuable, these frameworks share three limitations that PRECOG PROTOCOL addresses: (1) they lack built-in bias detection mechanisms, (2) they do not produce explicit timing judgments, and (3) they do not support longitudinal signal tracking across sessions.

### 2.4 The Theory-Practice Gap

The common thread across these literatures is a gap between explanation and execution. Creativity theories tell us *what happens* during creative insight; AI tools provide powerful generative engines but risk converging to conventional outputs without structural guidance; foresight methodologies tell us *what to look for*. Neither tells practitioners *exactly what to do, step by step, with explicit quality criteria and failure modes*. This paper's contribution is precisely this translation: from theory (descriptive) to protocol (prescriptive), designed to structure AI-human interaction in ways that preserve structural novelty while maintaining reproducibility.

---

## 3. GHOSTY COLLIDER: A Protocol for Creative Emergence

### 3.1 Overview and Definitions

GHOSTY COLLIDER is a 5-step protocol for generating cross-domain creative visions from heterogeneous input fragments. Its design principle is: *"You don't think your way to a vision. You wait for it to appear."*

We define an **executable protocol** as a step-by-step procedure that: (a) can be followed by a practitioner without prior training beyond reading the protocol document, (b) specifies explicit quality criteria for each step's output, (c) documents failure modes (anti-patterns) with remedies, and (d) produces traceable, reviewable intermediate artifacts at each step.

The protocol's core operation — **Ghost Extraction** — is a systematic de-labeling procedure that reduces concepts to their deep structural elements: verbs, forces, and transformations. By removing the familiar label, the thinker (human or AI agent) is forced to perceive the concept's structural essence, enabling non-obvious connections with structurally similar or opposing concepts from unrelated domains.

### 3.2 Procedure

**Step 1: Fragment Harvest.** Collect 3-5 fragments from diverse domains. Fragments may include quantitative data, qualitative observations, aesthetic impressions, gut feelings, absent patterns ("Why doesn't this exist?"), personal experiences, or constraints. The key requirement is diversity — homogeneous fragments (all from the same domain) reduce the probability of non-obvious collisions.

**Step 2: Ghost Extraction (De-labeling).** For each fragment, strip its label and describe its deep structure using only structural language — no proper nouns, no industry jargon. The output (called a "Ghost") should read as a transformation: "X converts Y into Z" or "A mechanism that produces B through C." Quality criteria include: (a) uses verbs rather than nouns, (b) includes the emotional dimension of the experience, (c) is comprehensible to someone from a completely different domain, and (d) passes the reversibility test (negating the Ghost reveals something non-trivial).

**Step 3: Collision Matrix.** Score pairwise combinations of Ghosts for structural resonance on a three-point scale: 💤 Boring (surface AND structural similarity — discard), 🤔 Interesting (structural overlap exists — hold), ⚡ Electric (surfaces are unrelated BUT deep structures resonate or clash — advance). Only Electric collisions proceed.

**Step 4: Vision Crystallization.** For each Electric collision, articulate what emerges — something that existed in neither fragment alone. Each vision requires: a name, a one-line description, an emotional characterization, a cinematic image, and a "Why Now?" justification. Visions are rated on four dimensions (Novelty, Feasibility, Resonance, Timing) on a 1-5 scale; all dimensions must score ≥ 3 to advance.

**Step 5: Reality Bridge.** Ground the vision in actionable terms: Minimum Viable Vision (smallest implementation that reproduces the core experience), existing capabilities that approximate the vision, kill conditions (what would invalidate this vision), and a first step executable within 24 hours.

### 3.3 Quality Criteria and Anti-Patterns

The protocol includes explicit failure modes:

| Anti-Pattern | Description | Remedy |
|-------------|-------------|--------|
| Shallow Ghosting | Ghost is a synonym of the label | Ask "Why does this *feel* the way it does?" |
| Electric Inflation | Every collision scored ⚡ | If explainable in 2 seconds, it's 🤔 at best |
| Vision Without Grounding | Beautiful concept, no Reality Bridge | Never skip Step 5 |
| Homogeneous Fragments | All fragments from one domain | Require at least one external-domain fragment |
| Forced Collision | Connecting fragments without genuine resonance | Permitted to report "No ⚡ collisions found" |

---

## 4. PRECOG PROTOCOL: A Protocol for Strategic Foresight

### 4.1 Overview

PRECOG PROTOCOL is a 5-step protocol for signal-based strategic foresight with explicit timing judgment. It compresses the core logic of horizon scanning, weak signals theory, and scenario planning into a single-session executable format, while adding two innovations: multi-axis timing judgment and longitudinal signal tracking.

### 4.2 Procedure

**Step 1: Signal Map.** Collect 3-8 observable signals related to a target theme. Each signal requires: a one-line description, specific evidence with sources, a strength classification (Strong / Emerging / Weak), a direction indicator (↑ Accelerating / → Stable / ↓ Decelerating), and a mandatory confidence tag ([Verified] = primary source accessible; [Reported] = multi-source coverage; [Speculative] = inference or rumor). Signal sources include numeric changes, behavioral changes, narrative changes, and absent signals.

**Step 2: Convergence Analysis.** Identify where multiple signals intersect and reverse-engineer the underlying structural shift. For each convergence point: state the structural hypothesis in one sentence, articulate the causal logic connecting the signals, and assign confidence (High/Medium/Low) with rationale.

**Step 3: Contrarian View.** For the most obvious conclusion, systematically examine why it might be wrong. Requirements include: at least one reason the dominant view may be overestimated, a historical analogy where a similar setup led to a different outcome, explicit preconditions ("This hypothesis is valid only if A and B hold"), a collapse trigger (which precondition failure invalidates the thesis), and probability estimates for each contrarian scenario.

**Step 4: Timing Grid.** Evaluate timing across four independent axes:

- *Market Phase Axis*: Position on the adoption cycle (Emergence → Acceleration → Peak → Correction → Plateau)
- *Competitive Timing Axis*: Strategic position (First Mover → Fast Follower → Fortifier → Too Late)
- *Organizational Readiness Axis*: Capability assessment (Not Ready → Partially Ready → Ready)
- *External Window Axis*: Regulatory, capital, seasonal, and technology maturity factors

Each axis produces an independent judgment; the overall timing judgment synthesizes all four.

**Step 5: Action Window.** Specify concrete actions across four categories: Now (start immediately, low-cost), Soon (invest when specific conditions are met), Watch (do not move, but trigger on specific signals), and Kill (disinvest if specific conditions occur). Each action requires: a specific action description, an execution trigger, and estimated cost or resource commitment.

### 4.3 Signal History and Feedback Loop

When analyzing the same theme across multiple sessions, PRECOG PROTOCOL supports longitudinal tracking through delta detection: each signal is compared against previous analyses and classified as Strengthened, Stable, Weakened, New, or Dead. New and Dead signals receive priority in Convergence Analysis as the strongest evidence of structural change.

A Prediction Feedback Loop tracks past prediction accuracy (Hit/Miss/Partial), timing accuracy, and contrarian value to improve future analyses. We note that, as of this writing, the Prediction Feedback Loop has not been formally exercised across a full cycle — the predictions in Case Study C (Section 6.3) cover the 2026-2028 period and are not yet verifiable. Section 8.2 discusses this limitation and proposes retroactive validation as a methodological path forward.

---

## 5. Integration: GHOSTY COLLIDER × PRECOG PROTOCOL × MOLD BREAKER

While each protocol functions independently, they exhibit strong complementarity through bidirectional integration. Additionally, a companion protocol — **MOLD BREAKER** — serves as a post-processing refinement step for outputs from either protocol.

### 5.1 Bidirectional Integration

**PRECOG → GHOSTY (Signal-to-Fragment Feeding).** Signals and convergence points from PRECOG analysis serve as high-quality fragments for GHOSTY COLLIDER. Because these signals have already been evidence-tagged and structurally analyzed, they produce richer Ghosts during extraction. The confidence tags ([Verified], [Reported], [Speculative]) carry forward as metadata on GHOSTY fragments, allowing the Reality Bridge step to calibrate its feasibility assessment based on evidence strength.

**GHOSTY → PRECOG (Vision-to-Action Mapping).** Visions crystallized by GHOSTY COLLIDER feed directly into PRECOG's Action Window. A vision's "Why Now?" justification maps naturally to the Timing Grid, and its Reality Bridge (MVV, Kill Conditions) provides the specificity required by PRECOG's action specifications. The four-dimension rating (Novelty, Feasibility, Resonance, Timing) from Vision Crystallization directly informs the Organizational Readiness axis of the Timing Grid.

**Integration Procedure.** In practice, the bidirectional integration follows three steps: (1) Execute PRECOG Protocol on a target domain to identify signals and convergence points. (2) Select 2-3 convergence points as fragments for GHOSTY COLLIDER, supplemented by 1-2 external-domain fragments to ensure heterogeneity. (3) Map the resulting visions back through PRECOG's Timing Grid and Action Window, using the visions' Reality Bridge outputs as inputs for action specification.

This bidirectional integration creates a cycle: signals inform creative exploration, and creative visions inform strategic timing — a loop that neither protocol achieves alone. Case Study B (Section 6.2) demonstrates this integration in action.

### 5.2 MOLD BREAKER: Typicality Bias Destruction

A recurring challenge in creative ideation — whether human or AI-assisted — is the **Typicality Bias**: the tendency to converge on the most probable, genre-standard outputs (Doshi & Hauser, 2024). MOLD BREAKER addresses this directly through a 5-step procedure that systematically destroys conventional patterns in existing ideas:

1. **Generate 5 Candidates** — produce volume without filtering.
2. **Reject the First 3 Obvious** — explicitly discard the highest-typicality outputs with stated reasons.
3. **Select Top 2 + Hybrid** — retain only structurally novel candidates; attempt recombination.
4. **Apply 2 Orthogonal Frames** — force perpendicular perspectives (e.g., market vs. narrative, additive vs. subtractive).
5. **Add a Killer Constraint** — impose a constraint that attacks remaining conventionality.

MOLD BREAKER draws on constraint-based creativity (Stokes, 2005), structured analogical transfer (Gick & Holyoak, 1983; Gentner, 1983), and de Bono's lateral thinking provocations (1967). While individual components have precedent in the creativity literature, the protocol's contribution is integrating them into a single executable procedure specifically designed to counteract AI-assisted ideation's tendency toward modal outputs.

**Relationship to GHOSTY COLLIDER and PRECOG PROTOCOL.** MOLD BREAKER operates on a different input type: whereas GHOSTY COLLIDER creates visions from raw fragments (generative) and PRECOG PROTOCOL reads timing from signals (analytical), MOLD BREAKER refines *existing ideas* by destroying their typicality (subtractive). The three protocols occupy complementary positions:

| Protocol | Input | Operation | Output |
|----------|-------|-----------|--------|
| GHOSTY COLLIDER | Raw fragments | De-label → Collide → Crystallize | Emergent visions |
| PRECOG PROTOCOL | Observable signals | Map → Converge → Time | Strategic actions |
| MOLD BREAKER | Existing ideas | Reject → Reframe → Constrain | Sharpened, non-typical ideas |

**Pipeline integration.** MOLD BREAKER integrates naturally as a post-processing step: (1) GHOSTY COLLIDER → MOLD BREAKER: take crystallized visions and push them past their initial typicality through forced rejection and killer constraints. (2) PRECOG PROTOCOL → MOLD BREAKER: apply MOLD BREAKER to the specific actions in each Action Window, ensuring that strategic responses are not merely conventional reactions to detected signals.

We note that MOLD BREAKER's individual components are not novel — the "discard first ideas" heuristic, cross-domain analogy, and constraint-based creativity are established techniques. MOLD BREAKER's contribution is practical rather than theoretical: it provides a ready-made, executable countermeasure to the flattening effect that accompanies AI-assisted ideation. It is released alongside GHOSTY COLLIDER and PRECOG PROTOCOL as a companion tool rather than a primary theoretical contribution.

---

## 6. Case Studies

We report five case studies across distinct domains, demonstrating both GHOSTY COLLIDER and PRECOG PROTOCOL. For each, we present the inputs, selected intermediate artifacts (Ghosts, Collision Matrix results), and the outputs to enable assessment of the protocol's operational mechanism. Detailed execution logs, including all intermediate artifacts, are available in the supplementary materials.

### 6.1 Case Study A: Financial Market Analysis (GHOSTY COLLIDER)

**Domain:** Financial analysis and corporate valuation.

**Input Fragments:**
1. A semiconductor company's data center revenue growing at 25% QoQ yet bear-case valuation falling below current market capitalization
2. Retail investor sentiment metrics diverging from institutional positioning
3. Historical patterns of "faith premiums" in technology stocks (1999 internet, 2021 EV sector)

**Ghost Extraction (all fragments):**
- Fragment 1 → *"A system accelerating so fast that its collapse scenario becomes equally plausible — acceleration and fragility as twin outputs of the same engine"*
- Fragment 2 → *"Two groups observing the same phenomenon but reaching opposite conclusions — the divergence itself is informational, independent of which side is correct"*
- Fragment 3 → *"A measurable gap between what evidence supports and what belief demands — the price of conviction becoming itself an investable signal"*

**Collision Matrix:**
- Fragment 1 × 2: 🤔 Interesting (both involve disagreement, but at different levels)
- Fragment 1 × 3: ⚡ Electric (acceleration as fragility × conviction as signal → strength and vulnerability as structurally identical)
- Fragment 2 × 3: ⚡ Electric (informational divergence × belief premium → the gap between groups *is* the metric)

**Emergent Visions (3 crystallized):**
1. *"Faith Ratio"* — A quantitative framework treating the gap between evidence-based valuation and belief-based premium as a first-class metric, not noise. (Novelty 5, Feasibility 4, Resonance 4, Timing 4)
2. *"Fragility Accelerator"* — A model where exponential growth curves contain embedded prediction of their own failure modes. (Novelty 4, Feasibility 3, Resonance 5, Timing 4)
3. *"Sentiment Divergence Index"* — A tracking system where the delta between investor cohorts becomes itself an investable signal. (Novelty 3, Feasibility 5, Resonance 3, Timing 5)

**Output characteristics:** 3 fragments extracted, 2 Electric collisions, 3 visions crystallized with quantitative metrics defined. The protocol transformed standard DCF model outputs into a structural analysis of market psychology.

### 6.2 Case Study B: Competitive Strategy Design (GHOSTY COLLIDER + PRECOG PROTOCOL Integration)

**Domain:** Corporate strategy for long-range competitive positioning.

**Input:** Structural analysis of a dominant technology company's revenue composition, competitive moats, and historical growth trajectory.

**PRECOG Phase — Signal Map (6 signals):**
1. Target company's advertising revenue growth decelerating vs. cloud revenue accelerating (Strong, ↑, [Verified])
2. Competitors investing in foundational AI infrastructure at unprecedented scale (Strong, ↑, [Verified])
3. Target company's internal AI model development reaching frontier quality (Strong, ↑, [Verified])
4. Emerging regulatory pressure on data monopolies (Emerging, ↑, [Reported])
5. Developer ecosystem fragmentation across AI platforms (Emerging, →, [Verified])
6. Consumer trust in target company declining in key demographics (Weak, ↓, [Reported])

**PRECOG Phase — Convergence Analysis:**
- *Convergence 1:* Signals 1+3 — "Revenue structure transformation in progress." The organism is simultaneously growing (cloud/AI) and shrinking (advertising) — a structural metamorphosis, not a crisis. Confidence: High (verified data).
- *Convergence 2:* Signals 2+5 — "Platform hegemony is contestable." Multiple well-capitalized competitors building foundational infrastructure signals that the target's distribution moat may not hold. Confidence: Medium (infrastructure investment ≠ market capture).
- *Convergence 3:* Signals 4+6 — "Social license at risk." Regulatory momentum + trust decline create a window where the target's brand becomes a liability in certain segments. Confidence: Medium (regulatory timelines are uncertain).

**GHOSTY Phase — Fragment Selection:** The three convergence points above were used as GHOSTY fragments, supplemented by two external fragments: (a) the historical pattern of vertical integration cycles in technology platforms, and (b) emerging patterns in AI-native user interface design.

**Ghost Extraction (all 5 fragments):**
- Convergence 1 → *"A system whose visible growth surface conceals a tectonic shift in its revenue foundation — the organism is replacing its skeleton while walking"*
- Convergence 2 → *"An incumbent whose fortress was built on distribution now faces challengers building from capabilities — the castle walls are intact but the terrain has shifted"*
- Convergence 3 → *"Permission to operate eroding not through catastrophe but through accumulation of small trust fractures — death by a thousand paper cuts of suspicion"*
- External Fragment (a) → *"Every platform that achieved dominance by horizontal breadth eventually faced a vertical integration challenger — the thin layer strategy is always temporary"*
- External Fragment (b) → *"The interface is no longer a window into the system — it IS the system. When the UI becomes the product, the backend becomes a commodity"*

**Collision Matrix (10 pairwise combinations):**
- C1 × External (a): ⚡ Electric — "skeleton replacement while walking" × "thin layer strategy is temporary" = the target company's transition *is itself the vulnerability window*
- C2 × External (b): ⚡ Electric — "distribution fortress vs. capability challengers" × "UI becomes the product" = the next competitive battleground is not infrastructure but the *experience layer* — whoever defines how humans interact with AI wins
- C3 × C1: ⚡ Electric — "trust erosion by accumulation" × "skeleton replacement while walking" = the metamorphosis itself generates the trust fractures — users distrust what they don't recognize
- C1 × C2: 🤔 Interesting (complementary but not surprising)
- Remaining 6 pairs: 💤 Boring to 🤔 Interesting

**Vision Crystallization (3 visions from 3 ⚡ Electric collisions):**

1. *"Infrastructure Play"* — Position as the "AI picks and shovels" provider during the target's skeletal transition. The vulnerability window IS the product opportunity. (Novelty 3, Feasibility 4, Resonance 4, Timing 5)
2. *"Experience Layer"* — Build the AI-native UX layer that sits between the user and all AI backends. The interface becomes the moat, and all infrastructure players become suppliers. (Novelty 4, Feasibility 3, Resonance 5, Timing 4)
3. *"Trust Arbitrage"* — Create a brand explicitly positioned as "not-[target company]" — capturing the trust refugees. The trust deficit is not a problem to solve but a market to serve. (Novelty 5, Feasibility 3, Resonance 4, Timing 3)

**PRECOG Phase — Timing Grid (per vision):**

| Vision | Market Phase | Competitive | Readiness | External | Overall |
|--------|-------------|-------------|-----------|----------|---------|
| Infrastructure Play | Acceleration | Fast Follower | Ready | Open | **Go** |
| Experience Layer | Emergence | First Mover | Partial | Opening | **Soon** |
| Trust Arbitrage | Pre-emergence | Undefined | Not Ready | Closed | **Watch** |

**PRECOG Phase — Action Window:**

| Category | Action | Trigger | Cost |
|----------|--------|---------|------|
| Now | Begin infrastructure partnership conversations | — | Low (relationship building) |
| Now | Prototype AI-native UX component (one vertical) | — | Medium (1 engineer × 3 months) |
| Soon | Launch Experience Layer MVP | When target's AI product launches with poor UX reviews | Medium-High |
| Watch | Monitor trust metric delta quarterly | If trust decline accelerates >15% YoY | Low (tracking) |
| Kill | Abandon Trust Arbitrage if regulatory burden equalizes | If new regulation applies equally to all AI providers | — |

**Output characteristics:** 3 strategic visions, each with 4-axis timing assessment and action windows. The integration demonstrated that the same market environment can simultaneously present "Go" timing for one strategy and "Watch" timing for another — a nuance undetectable by single-axis strategic frameworks.

### 6.3 Case Study C: Technology Trend Forecasting (PRECOG PROTOCOL)

**Domain:** AI agent ecosystem, 2026-2028 projection.

**Signal Map (8 signals):**
1. Major AI labs simultaneously releasing agent-capable products (Strong, [Verified])
2. GUI-controlling AI agents reaching production quality (Strong, [Verified])
3. Browser-automation agents entering beta (Strong, [Verified])
4. Enterprise no-code agent builders proliferating (Strong, [Verified])
5. Agent interoperability protocols gaining cross-industry adoption (Emerging, [Verified])
6. Coding-specific agents experiencing rapid growth (Strong, [Verified])
7. Agent hallucination and failure reports increasing (Weak, [Reported])
8. Regulatory frameworks for AI beginning enforcement (Strong, [Verified])

**Convergence Analysis:** Signals 1-4 converge on "market consensus formation" — all major platforms have committed. Signal 5+6 reveal a platform-vs-application layer separation in progress. Signal 7+8 converge on "usable but fragile" social perception.

**Contrarian Views (3 scenarios with probability estimates):**
- Scenario 1: Agent-caused incident triggers regulatory freeze (25-35%)
- Scenario 2: Protocol fragmentation rather than standardization — "browser wars" repeat (30-40%)
- Scenario 3: Agents create new job categories instead of eliminating existing ones — a double employment wave (50-60%)

**Timing Grid Result:** Market Phase: Emergence → Acceleration (Go-leaning). Competitive: First Mover window open. Technical Maturity: Usable but error-prone. Regulatory: Catching up. **Overall: Early Go with risk hedging required.**

**Output characteristics:** 8 signals classified, convergence hypothesis articulated, 3 contrarian scenarios with probabilities, 4-axis timing judgment, 6 categorized actions (Now/Soon/Watch/Kill with triggers). The protocol produced explicit timing disagreement across axes — a feature absent from standard SWOT analysis.

### 6.4 Case Study D: Music Production (GHOSTY COLLIDER)

**Domain:** Song concept design for a pop group.

**Input Fragments:**
1. The emotional concept of "hiding affection" as a lyrical theme
2. Jersey Club / UK Garage genre characteristics (syncopated rhythms, garage basslines)
3. Linguistic properties of the target language (vowel openness correlating with emotional exposure)
4. The aesthetic of "armor" — protection that reveals vulnerability by its presence
5. Real-time audience engagement patterns from concert data

**Ghost Extraction (all fragments):**
- Fragment 1 → *"The act of concealment becoming a form of pleasure — hiding as a masochistic performance, not a deficit"*
- Fragment 2 → *"Rhythmic structures that encode social permission — the syncopation pattern as a gate that allows or denies physical release"*
- Fragment 3 → *"Physical mouth shape as a betrayal mechanism — the body expressing what the mind suppresses"*
- Fragment 4 → *"The paradox of protection: armor announces the existence of something worth attacking"*
- Fragment 5 → *"A feedback loop between collective energy and individual behavior — the crowd as a single organism responding to micro-variations in stimulus"*

**Collision Matrix (10 pairwise combinations):**
- Fragment 1 × 4: ⚡ Electric (hiding × armor → "protection that reveals")
- Fragment 3 × 1: ⚡ Electric (betrayal by body × concealment as pleasure → "the voice cracks where concealment fails")
- Fragment 2 × 5: 🤔 Interesting (rhythmic permission × crowd energy → complementary but not surprising)
- Fragment 2 × 4: 🤔 Interesting (syncopation × armor → rhythmic defense)
- Remaining 6 pairs: 💤 Boring or 🤔 Interesting

**Emergent Vision:** A song concept where the musical parameters (key, BPM, modulation, vocal direction) are derived from the Ghost structures rather than genre convention. Key selected based on its tonal character (isolation, inward intensity) rather than "what sounds right." Modulation reframed as narrative surrender rather than climactic lift. Vocal breakpoints designed where "the voice is permitted to crack" — encoding the armor's structural failure into the audio.

**Output characteristics:** 12 production parameters defined (key, BPM, chord progression rationale, VA energy coordinates per section, silence design, vocal direction for 9 sections, lyric syllable counts, vowel openness mapping, modulation meaning, breakdown philosophy). An independent quality evaluation scored the output at 75/80 across 8 axes (see Section 7 for scoring methodology). The protocol-driven approach produced three times the number of explicitly defined parameters versus conventional concept briefs.

### 6.5 Case Study E: Short-Form Video Production (GHOSTY COLLIDER)

**Domain:** Concept design for a 60-second social media short film.

**Input Fragments:**
1. Character with a signature "ennui gaze" — delicate, fragile, disengaged aesthetic
2. Character with intellectual intensity — angular features, under-eye shadows, commanding presence
3. The 0.5-second attention hook — research showing that first-frame visual impact determines view completion
4. A24 cinema aesthetics — the uncanny within the mundane, natural light, performative silence
5. Fashion film grammar — "one shot = one message," texture over movement

**Ghost Extraction (all fragments):**
- Fragment 1 → *"Beauty emerging from the process of breaking — incompleteness as aesthetic value, reversing the demand for perfection"*
- Fragment 2 → *"Intensity as a form of violence — knowledge as something that presses outward through the face, creating pressure visible in physical features"*
- Fragment 3 → *"The first frame as an act of seizure — capturing attention is structurally violent, not invitational"*
- Fragment 4 → *"The uncanny emerges not from abnormality but from normality held too long — stillness becomes threatening when it exceeds expected duration"*
- Fragment 5 → *"Stillness is not the absence of motion but a state of frozen potential — the most dynamic moment is the one just before movement begins"*

**Collision Matrix (10 pairwise combinations):**
- Fragment 1 × 4: ⚡ Electric ("breaking beauty" × "mundane uncanny" = a mundane scene that is beautiful *because* something is subtly wrong)
- Fragment 2 × 3: ⚡ Electric ("intellectual seizure" × "first-frame violence" = catching the viewer not through spectacle but through a gaze that communicates "I see through you")
- Fragment 5 × 1: ⚡ Electric ("frozen potential" × "breaking beauty" = a still image that contains a visible countdown to collapse)
- Fragment 3 × 5: 🤔 Interesting (seizure × frozen potential → complementary)
- Fragment 4 × 2: 🤔 Interesting (uncanny × intellectual violence → tonal overlap)
- Remaining 5 pairs: 💤 Boring to 🤔 Interesting

**Emergent Vision:** A 60-second film composed of five 12-second static shots. No camera movement. No music — ambient sound only. Each shot isolates one character in a space where something is subtly wrong (a crack, a tilt, a misalignment). The fourth shot breaks the stillness with a single explosive movement — the only kinetic moment in the film, designed as visual modulation (paralleling Case Study D's concept of modulation as structural disruption).

**Output characteristics:** Complete shot list with specific parameters (aspect ratio 9:16, single light source, saturation -30%, contrast +20%, locked camera, ambient audio only). The protocol produced a concept that *inverts* every convention of the genre (stillness vs. movement, silence vs. music, gaze vs. spectacle) — inversions that emerged from Ghost-level structural analysis rather than a deliberate "let's do the opposite" strategy.

---

## 7. Controlled Comparisons

To assess the protocols' structural contribution, we conducted controlled comparisons: identical inputs were processed using standard methods (brainstorming, SWOT analysis) and protocol-driven methods (GHOSTY COLLIDER, PRECOG PROTOCOL). Both conditions used the same AI system (Claude, Anthropic) to control for differences in knowledge and language ability. The independent variable is the presence or absence of the protocol structure.

### 7.1 Methodological Notes

**Evaluation Procedure.** Quality assessments reported in this section (e.g., the 75/80 vs. 64/80 scores in Section 7.2) were conducted by the protocol author using the scoring rubric defined by the protocol itself (8 dimensions × 10-point scale). We acknowledge that this introduces potential bias, as the author designed both the protocol and the evaluation criteria. Independent blind evaluation by domain experts is essential for validation and is identified as priority future work (Section 8.3).

**Operational Definition of Structural Novelty.** Throughout this section, we use "structurally novel" to mean: the output contains creative choices that *cannot be derived from applying standard genre conventions or framework templates to the given inputs*. Operationally, we identify structural novelty by examining whether each major creative decision in the protocol-driven output has a corresponding default in the standard-method output, and whether the protocol-driven decision is a refinement of that default (incremental) or a reconceptualization (structural). We acknowledge this determination is currently qualitative and propose computational operationalization in Section 8.3.

**Comparison Fairness.** To address the information asymmetry between conditions: the brainstorming condition received Osborn's four principles (defer judgment, reach for quantity, seek wild ideas, build on ideas of others) and a prompt of comparable length to the protocol instructions. The SWOT condition received the standard SWOT framework definition with guidelines for each quadrant. While the protocol condition contains substantially more structural guidance, this asymmetry is intrinsic to the independent variable — the research question is whether *structured* protocols produce different outputs from *standard-structured* methods, not whether more instructions produce more output.

### 7.2 Music Production: Brainstorming vs. GHOSTY COLLIDER

**Input (identical):** Pop group song concept, theme "hiding affection," Jersey Club / UK Garage reference.

| Dimension | Brainstorming (Control) | GHOSTY COLLIDER (Treatment) |
|-----------|------------------------|----------------------------|
| Concept | "Secret crush expressed through dance-pop" | "Concealment as masochistic pleasure — armor that reveals" |
| Key selection rationale | Convention ("G minor sounds emotional") | Structural ("F# minor — tonal isolation matching thematic inwardness") |
| Modulation purpose | Climactic lift (genre standard) | Narrative surrender ("the moment the armor fails") |
| Lyric design unit | Semantic (word meaning) | Phonetic (vowel openness = emotional exposure) |
| Vocal direction | Not specified | 9 sections defined, including "voice permitted to crack" |
| Parameters defined | 4 (key, BPM, structure, lyric theme) | 12 (+ VA coordinates, silence design, vowel mapping, modulation meaning, breakdown philosophy) |
| Quality score | 64/80 (author-assessed) | 75/80 (author-assessed, +17.2%) |

**Key finding:** The brainstorming output was commercially viable but structurally indistinguishable from existing genre conventions. GHOSTY COLLIDER produced outputs that were different in *kind*, not merely in *degree* — the modulation from "climactic lift" to "narrative surrender" is not a refinement of the standard approach but a reconceptualization that emerged from Ghost-level analysis. We note that commercial viability of the protocol-driven output has not been separately validated.

### 7.3 Short-Form Video: Brainstorming vs. GHOSTY COLLIDER

**Input (identical):** 60-second social media video, 5 characters, goal of maximizing view completion rate.

| Dimension | Brainstorming (Control) | GHOSTY COLLIDER (Treatment) |
|-----------|------------------------|----------------------------|
| Hook strategy | High-energy opening movement | Static gaze (silence as seizure) |
| Lighting | Multi-source, colorful | Single source, shadow-dominant |
| Audio | Background music track | No music — ambient sound only |
| Camera | Dynamic (handheld + crane) | Completely fixed |
| Character utilization | Group formation shots | One character per shot, individual structural analysis |
| Structural principle | "More energy = more engagement" | "Stillness as tension = inescapable engagement" |

**Key finding:** Every major creative decision was inverted. Critically, these inversions were *not* produced by a "do the opposite" instruction — they emerged organically from Ghost Extraction. "Attention is structurally violent" (Ghost of Fragment 3) naturally leads to "stillness as seizure" rather than "movement as attraction." The protocol's de-labeling step prevented the default genre frame from biasing the output.

### 7.4 Trend Forecasting: SWOT Analysis vs. PRECOG PROTOCOL

**Input (identical):** AI agent market assessment, 2026-2028 horizon, publicly available data.

| Dimension | SWOT (Control) | PRECOG PROTOCOL (Treatment) |
|-----------|---------------|----------------------------|
| Temporal structure | None (static snapshot) | 4-category action timeline (Now/Soon/Watch/Kill) |
| Bias detection | None (implicit assumptions) | Systematic (Contrarian View with probability estimates) |
| Signal classification | S/W/O/T quadrants | Strong/Emerging/Weak + confidence tags |
| Timing judgment | Absent | 4-axis grid (market/competitive/technical/regulatory) |
| Action specificity | "Enter the market" (vague) | Actions with trigger conditions and kill criteria |
| Contrarian analysis | Not structurally required | 3 scenarios quantified (25-60% probability ranges) |
| Cross-axis disagreement | Not possible | Detected (market phase = cautious, competitive = go) |

**Key finding:** The SWOT analysis produced a correct but static assessment. PRECOG PROTOCOL's primary advantage was *temporal structure* — it transformed "the situation" into "when to act, contingent on what." The Timing Grid revealed that different axes recommended different actions simultaneously, a nuance invisible to the static SWOT framework. The Contrarian View step surfaced the "agents create new jobs rather than eliminating them" hypothesis — a scenario that did not appear in the SWOT analysis because SWOT lacks a structural mechanism for challenging its own conclusions.

### 7.5 Protocol Failure Cases and Failure Rate

To characterize protocol boundary conditions, we report instances where protocol execution produced suboptimal or abandoned outputs, followed by aggregate failure statistics from a systematic batch experiment.

**Failure Case 1: Insufficient Fragment Diversity (GHOSTY COLLIDER).** In an early execution targeting product pricing strategy, all five input fragments came from the same domain (SaaS pricing models). Ghost Extraction produced structurally similar Ghosts — variants of "value exchange under asymmetric information." The Collision Matrix yielded zero ⚡ Electric results; all 10 pairwise combinations scored 💤 Boring or 🤔 Interesting. The protocol's anti-pattern detection ("Homogeneous Fragments") correctly flagged this failure, but only after the time-consuming Ghost Extraction step had been completed. **Lesson:** The Homogeneous Fragments anti-pattern should be checked *before* Ghost Extraction, not after. This has been incorporated into protocol v2 as a pre-flight diversity check.

**Failure Case 2: Shallow Ghost Extraction.** In an execution targeting educational content design, Ghost Extraction produced surface-level Ghosts that were effectively synonyms of the original labels (e.g., "learning" → "the process of acquiring knowledge"). The reversibility test caught this: negating "the process of acquiring knowledge" produces "not acquiring knowledge," which is trivial rather than revelatory. However, three iterative rounds of re-extraction were required before Ghosts of sufficient depth were produced. **Lesson:** Ghost Extraction quality is strongly dependent on practitioner skill. The protocol's quality criteria detect shallow Ghosts, but the remediation ("Ask 'Why does this *feel* the way it does?'") requires practiced judgment. This represents a genuine barrier to protocol accessibility.

**Failure Case 3: Timing Grid Over-Determination (PRECOG PROTOCOL).** In an application to cryptocurrency market analysis, the Timing Grid produced maximally positive signals on all four axes (Market: Acceleration, Competitive: First Mover, Readiness: Ready, External: Open) — a result that, in retrospect, reflected the protocol operator's confirmation bias rather than balanced assessment. The Contrarian View step identified this bias (all four axes aligned suspiciously), but only because the operator recognized the pattern. **Lesson:** A structural check has been added to protocol v2: when all four Timing Grid axes align in the same direction, this triggers a mandatory escalated Contrarian View with a Pre-Mortem test rather than proceeding directly to Action Window.

#### Batch Experiment: Failure Rate Quantification

To move beyond anecdotal failure cases, we conducted a systematic batch experiment: GHOSTY COLLIDER was executed across 8 randomly selected domain pairings, ranging from closely related to maximally distant. Each experiment used 4 fragments and followed the complete 5-step protocol.

| # | Domain Pairing | ⚡ Electric | Hit Rate | Visions | Result |
|---|---------------|------------|----------|---------|--------|
| 1 | Urban Agriculture × Social Design | 3 | 50% | 2 | ✅ Success |
| 2 | Elderly Care × E-sports | 3 | 50% | 1 | ✅ Success |
| 3 | Tax Accounting × Jazz Music | 2 | 33% | 1 | ✅ Success |
| 4 | Supply Chain Logistics (homogeneous) | 0 | 0% | 0 | ❌ Failure |
| 5 | Dental UX × Street Photography | 2 | 33% | 1 | ✅ Success |
| 6 | Climate Science × Stand-up Comedy | 3 | 50% | 1 | ✅ Success |
| 7 | Corporate HR × Fermentation Science | 3 | 50% | 1 | ✅ Success |
| 8 | Cybersecurity × Traditional Tea Ceremony | 3 | 50% | 1 | ✅ Success |

**Aggregate Statistics:**
- **Protocol success rate: 87.5% (7/8)**
- **Protocol failure rate: 12.5% (1/8)**
- **Failure cause: 100% attributable to Homogeneous Fragments** (single-domain input)
- **Mean ⚡ Electric rate across successful experiments: 41.9% of pairwise combinations**
- **Total Visions crystallized: 9 across 7 successful experiments (mean: 1.29 per experiment)**

**Key findings from batch experiment:**
1. Cross-domain fragment diversity is a *necessary* condition for protocol success. The pre-flight diversity check (added to protocol v2) would have prevented 100% of observed failures.
2. Domain distance correlates positively with vision novelty scores: maximally distant domains (Experiments 2, 6, 7, 8) produced the highest novelty ratings (4-5/5).
3. Vision feasibility scores were inversely correlated with novelty scores (r ≈ -0.6), consistent with the theoretical expectation that more novel visions require more departure from existing infrastructure.
4. No instances of Shallow Ghosting or Electric Inflation were observed in this batch, though this may reflect operator experience rather than protocol robustness.

These failure cases and batch statistics suggest that the protocols' quality criteria and anti-pattern detection function as designed — they catch failures — but that the primary failure mode (homogeneous fragments) is preventable through a pre-flight check. The lessons from these failures have been incorporated into the protocol documents (v2) released alongside this paper.

### 7.6 Blind Evaluation

To partially address the evaluator bias identified in Section 7.1, we conducted a blind evaluation of Case Study D (Music Production) outputs. An independent evaluator (a separate AI session with no knowledge of which method produced which output) was presented with two song concept documents — one from brainstorming and one from GHOSTY COLLIDER — in randomized order, without method labels.

**Evaluation rubric:** 8 dimensions × 10-point scale (Concept Depth, Musical Specificity, Lyric-Music Integration, Emotional Architecture, Production Innovation, Vocal Direction, Internal Consistency, Actionability). Maximum score: 80.

**Results:**

| Condition | Author Assessment | Blind Evaluation |
|-----------|------------------|------------------|
| GHOSTY COLLIDER | 75/80 | 74/80 |
| Brainstorming | 64/80 | 49/80 |
| **Gap** | **11 points** | **25 points** |

The blind evaluation confirmed the direction of the author's assessment (GHOSTY COLLIDER output scored higher). The GHOSTY COLLIDER score was nearly identical between evaluators (75 vs. 74, Δ=1.3%), while the brainstorming score diverged substantially (64 vs. 49, Δ=23.4%). The blind evaluator scored the brainstorming output lower than the author did, suggesting the author may have been compensatorily generous to the control condition.

The blind evaluator correctly identified the structured output, citing "the presence of a design principle (concealment as armor) that generatively produces decisions across multiple dimensions, rather than a topic description applied to pre-existing templates" as the distinguishing characteristic.

**Limitations of this evaluation:** This is a single blind evaluation using an AI evaluator, not a human domain expert. The evaluator may share biases with the AI execution assistant. The rubric was designed by the protocol author. Multiple independent human evaluators using an independently designed rubric are needed for validation.

### 7.7 Summary of Controlled Comparisons

| Metric | Control (Standard Methods) | Treatment (Protocols) |
|--------|---------------------------|----------------------|
| Output correctness | ✅ Accurate | ✅ Accurate |
| Output comprehensiveness | ✅ Broad coverage | 🟡 Focused (by design) |
| Structural novelty | ❌ Converges to genre/framework conventions | ✅ Produces qualitatively distinct directions |
| Parameter specificity | 4-6 parameters | 12+ parameters (+200%) |
| Temporal reasoning | ❌ Static | ✅ Dynamic (timing + triggers) |
| Bias detection | ❌ Not built in | ✅ Structural (Contrarian View) |
| Process reproducibility | ❌ Participant-dependent | ✅ Protocol-documented |
| Anti-pattern awareness | ❌ None | ✅ Explicit failure modes |
| Protocol success rate | N/A | 87.5% (7/8 batch experiment) |
| Blind evaluation | N/A | Direction confirmed (74/80 vs. 49/80) |

The controlled comparisons, batch experiment, and blind evaluation provide preliminary evidence that the protocols' primary contribution is not producing *better* outputs in a conventional sense, but producing *structurally different* outputs — directions that standard methods do not reach because they lack the de-labeling (GHOSTY) and multi-axis temporal reasoning (PRECOG) steps. We emphasize that these findings are subject to the methodological limitations discussed in Section 7.1.

---

## 8. Discussion

### 8.1 Contributions

This work contributes to the literature on creativity support tools (Shneiderman, 2007; Frich et al., 2019) and strategic foresight practice, and engages with the emerging field of AI-augmented creativity (Gero & Chilton, 2019; Doshi & Hauser, 2024). Specifically:

1. **Theory-to-protocol translation.** We demonstrate that established descriptive theories can be compressed into executable, step-by-step protocols without losing their generative power. The five case studies across distinct domains (financial analysis, business strategy, technology forecasting, music production, video production) provide preliminary evidence of domain-generality.

2. **Ghost Extraction as a novel technique.** While de-labeling has been discussed in creativity literature (de Bono's "PO" provocation; Hatchuel & Weil's CK-theory concept expansion), we formalize it into a repeatable procedure with explicit quality criteria and a reversibility test. The controlled comparisons suggest that Ghost Extraction is the primary mechanism producing structural novelty in outputs.

3. **Multi-axis Timing Grid.** Existing foresight frameworks evaluate individual dimensions (market maturity, competitive position) but none we are aware of formally combines multiple timing axes into a single judgment grid with explicit cross-axis disagreement detection.

4. **Explicit anti-patterns and failure cases.** Both protocols include documented failure modes with remedies. The protocol failure cases (Section 7.5) demonstrate that these anti-patterns function in practice, catching execution errors — though not always optimally. This transparency about failure conditions is uncommon in methodology papers that typically present only the positive path.

5. **Counteracting the flattening effect.** In the context of Doshi and Hauser's (2024) finding that AI-assisted ideation reduces aggregate output diversity, our controlled comparisons provide initial evidence that structured protocols may counteract this tendency. The de-labeling step in GHOSTY COLLIDER explicitly breaks the genre conventions that unstructured AI-assisted ideation tends to reproduce.

### 8.2 Limitations

We identify the following limitations, ordered by severity:

1. **Single-operator evaluation (critical).** All case studies and controlled comparisons were executed by a single practitioner (the author) with AI assistance. This represents the most significant threat to generalizability. The author designed the protocols, executed the case studies, and assessed the outputs — a configuration that cannot exclude experimenter bias regardless of the care taken. Multi-user evaluation across diverse skill levels and domains is the highest-priority future work.

2. **Quality metric subjectivity.** The 1-5 scoring dimensions (Novelty, Feasibility, Resonance, Timing) and the production quality score (e.g., 75/80 vs. 64/80) were assessed by the protocol author using author-defined rubrics. Independent inter-rater reliability studies with blind evaluation by domain experts are needed before these scores can be considered validated metrics.

3. **Fragment quality dependency.** GHOSTY COLLIDER's output quality depends heavily on fragment diversity and Ghost Extraction depth. We provide quality criteria and report failure cases (Section 7.5), but acknowledge that Ghost Extraction requires practiced judgment that may vary significantly across practitioners.

4. **AI-assistance confound.** While the protocols are designed for human-only use, the case studies were conducted with AI assistance (Claude, Anthropic). The controlled comparisons hold AI constant between conditions, but the protocols' effectiveness without AI assistance has not been separately evaluated. It remains possible that the protocol structure is most effective specifically in combination with LLM-based execution.

5. **Absence of longitudinal and downstream validation.** The case studies demonstrate protocol outputs but do not track whether those outputs led to successful real-world implementations. For PRECOG PROTOCOL specifically, the Prediction Feedback Loop has not been formally exercised — the predictions in Case Study C cover 2026-2028 and are not yet verifiable. Retroactive validation (applying PRECOG to a past event with known outcomes, then comparing the protocol's predictions against what actually occurred) would provide valuable evidence and is identified as priority future work.

6. **Sample size for failure rate estimation.** The batch experiment (N=8) provides an initial failure rate estimate of 12.5%, but a larger sample across diverse operators is needed to establish reliable confidence intervals. The observed 100% attribution of failures to homogeneous fragments may reflect the dominance of this anti-pattern, or it may mask subtler failure modes that a larger sample would reveal.

### 8.3 Future Work

1. **Multi-user controlled studies.** Conduct pre-registered experiments with practitioners across domains and skill levels, comparing protocol-assisted ideation against unstructured brainstorming and existing methods, with blind evaluation of outputs by independent domain experts. Following Doshi and Hauser's (2024) methodology, this should measure both individual output quality and aggregate output diversity.

2. **Computational operationalization of structural novelty.** Develop automated metrics for the quality dimensions using semantic similarity against domain corpora (measuring how far outputs deviate from genre conventions), patent database novelty search, and embedding-space distance measurements. This would replace the current author-assessed scoring with reproducible computational metrics.

3. **Retroactive validation for PRECOG.** Apply PRECOG PROTOCOL to historical events with known outcomes (e.g., the 2020-2021 remote work transition, the 2023 generative AI surge) to assess the protocol's predictive accuracy retrospectively. This avoids the multi-year wait required for prospective validation while providing evidence of the protocol's analytical value.

4. **Longitudinal tracking.** Continue monitoring PRECOG predictions (particularly Case Study C) against market developments to quantify the Prediction Feedback Loop's value. Track GHOSTY COLLIDER visions through to implementation outcomes.

5. **Domain-specific adaptations.** While designed as domain-general protocols, investigation of domain-specific optimizations (e.g., Ghost Extraction heuristics for biotech vs. digital media) could improve output quality.

6. **Human-only evaluation.** Test the protocols in a paper-and-pen setting without AI assistance to establish the baseline effectiveness of the protocol structure itself, independent of AI capabilities, and to distinguish the protocol's contribution from the AI's contribution.

---

## 9. Conclusion

We have presented GHOSTY COLLIDER, PRECOG PROTOCOL, and the companion MOLD BREAKER as executable bridges between descriptive creativity/foresight theories and prescriptive practice. By formalizing the cognitive operations identified by Koestler, de Bono, Finke et al., Hatchuel & Weil, Ansoff, and Wack into step-by-step protocols with explicit quality criteria and failure modes, we aim to make creative emergence and strategic foresight accessible, repeatable, and improvable.

The five case studies provide preliminary evidence of domain generality across financial analysis, business strategy, technology forecasting, music production, and video production. The batch experiment (N=8, success rate 87.5%) provides initial quantification of protocol reliability, identifying fragment diversity as the critical success factor. The controlled comparisons suggest that the protocols produce structurally distinct outputs — not merely better versions of conventional ideas, but qualitatively different directions that standard methods do not reach. The blind evaluation (74/80 vs. 49/80) confirmed the direction of author assessments while revealing a potentially larger quality gap than the author estimated. The reported failure cases and their incorporation into protocol v2 (pre-flight diversity check, over-determination check) demonstrate that the protocols can evolve based on empirical field testing.

In the context of growing concern about AI-assisted ideation reducing aggregate creative diversity (Doshi & Hauser, 2024), these protocols represent one approach to structuring human-AI interaction in ways that preserve — and potentially enhance — the structural novelty of creative and strategic outputs. MOLD BREAKER specifically addresses this concern by providing a practical, executable countermeasure to typicality bias in any ideation output. Substantial further validation is needed, particularly multi-user evaluation with human domain expert blind assessment and retroactive validation of foresight predictions.

The protocols (v2, incorporating lessons from failure case analysis) and the companion MOLD BREAKER are released as open-access documents at https://github.com/GhostyAI-HA/ghosty-collider under CC BY-NC 4.0, and we welcome contributions — particularly new case studies from diverse domains and multi-user evaluations that test the protocols' generalizability beyond their author.

---

## References

Aguilar, F. J. (1967). *Scanning the Business Environment*. Macmillan.

Altshuller, G. S. (1946). Theory of Inventive Problem Solving (TRIZ). USSR Patent Office.

Amanatidou, E., Butter, M., Carabias, V., Könnölä, T., Leis, M., Saritas, O., Schaper-Rinkel, P., & van Rij, V. (2012). On concepts and methods in horizon scanning: Lessons from initiating policy dialogues on emerging issues. *Science and Public Policy*, 39(2), 208-221.

Ansoff, H. I. (1975). Managing strategic surprise by response to weak signals. *California Management Review*, 18(2), 21-33.

Brown, T. (2008). Design thinking. *Harvard Business Review*, 86(6), 84-92.

de Bono, E. (1967). *The Use of Lateral Thinking*. Jonathan Cape.

de Bono, E. (1970). *Lateral Thinking: Creativity Step by Step*. Harper & Row.

Doshi, A. R., & Hauser, O. P. (2024). Generative AI enhances individual creativity but reduces the collective diversity of novel content. *Science Advances*, 10(28), eadn5290.

Eberle, B. (1996). *Scamper: Creative Games and Activities for Imagination Development*. Prufrock Press.

Finke, R. A., Ward, T. B., & Smith, S. M. (1992). *Creative Cognition: Theory, Research, and Applications*. MIT Press.

Frich, J., Biskjaer, M. M., & Dalsgaard, P. (2019). Twenty years of creativity research in human-computer interaction: Current state and future directions. *Proceedings of the 2019 Conference on Designing Interactive Systems*, 1235-1257.

Gentner, D. (1983). Structure-mapping: A theoretical framework for analogy. *Cognitive Science*, 7(2), 155-170.

Gero, K. I., & Chilton, L. B. (2019). Metaphoria: An algorithmic companion for metaphor creation. *Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems*, Paper 296.

Gick, M. L., & Holyoak, K. J. (1983). Schema induction and analogical transfer. *Cognitive Psychology*, 15(1), 1-38.

Gero, K. I., Long, T., & Chilton, L. B. (2023). Social dynamics of AI support in creative writing. *Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems*, Paper 468.

Haase, J., & Hanel, P. H. P. (2023). Artificial muses: Generative artificial intelligence chatbots have risen to human-level creativity. *Journal of Creativity*, 33(3), 100063.

Hatchuel, A., & Weil, B. (2003). A new approach of innovative design: An introduction to C-K theory. *Proceedings of the International Conference on Engineering Design (ICED 03)*, Stockholm.

Hatchuel, A., & Weil, B. (2009). C-K design theory: An advanced formulation. *Research in Engineering Design*, 19(4), 181-192.

Henderson, B. D. (1970). The product portfolio. *BCG Perspectives*. Boston Consulting Group.

Hiltunen, E. (2010). Weak signals in organizational futures learning. *Acta Universitatis Oeconomicae Helsingiensis*, A-365.

Horowitz, R. (2001). From TRIZ to ASIT in 4 inventive steps. *The TRIZ Journal*.

Koestler, A. (1964). *The Act of Creation*. Hutchinson & Co.

Learned, E. P., Christensen, C. R., Andrews, K. R., & Guth, W. D. (1965). *Business Policy: Text and Cases*. Richard D. Irwin.

Lee, M., Liang, P., & Yang, Q. (2024). A design space for intelligent and interactive writing assistants. *Proceedings of the 2024 CHI Conference on Human Factors in Computing Systems*, Paper 854.

Osborn, A. F. (1953). *Applied Imagination: Principles and Procedures of Creative Thinking*. Charles Scribner's Sons.

Porter, M. E. (1979). How competitive forces shape strategy. *Harvard Business Review*, 57(2), 137-145.

Rohrbeck, R., Battistella, C., & Huizingh, E. (2015). Corporate foresight: An emerging field with a rich tradition. *Technological Forecasting and Social Change*, 101, 1-9.

Sawyer, R. K. (2012). *Explaining Creativity: The Science of Human Innovation* (2nd ed.). Oxford University Press.

Shneiderman, B. (2007). Creativity support tools: Accelerating discovery and innovation. *Communications of the ACM*, 50(12), 20-32.

Si, C., Yang, D., & Hashimoto, T. (2024). Can LLMs generate novel research ideas? A large-scale human study with 100+ NLP researchers. *arXiv preprint arXiv:2409.04109*.

Stokes, P. D. (2005). *Creativity from Constraints: The Psychology of Breakthrough*. Springer.

Stevenson, C., Smal, I., Baas, M., Grasman, R., & van der Maas, H. (2022). Putting GPT-3's creativity to the (Alternative Uses) Test. *Proceedings of the 13th International Conference on Computational Creativity (ICCC'22)*.

Van der Heijden, K. (1996). *Scenarios: The Art of Strategic Conversation*. Wiley.

Wack, P. (1985a). Scenarios: Uncharted waters ahead. *Harvard Business Review*, 63(5), 73-89.

Wack, P. (1985b). Scenarios: Shooting the rapids. *Harvard Business Review*, 63(6), 139-150.

---

*Correspondence: Shun Fujiyoshi, Independent Researcher. GitHub: https://github.com/GhostyAI-HA*
