# UNIQUENESS — Quality Evaluation Rubric
## Standards for Assessing Analysis Excellence

---

## THE 10 QUALITY GATES

Each gate must be passed before delivering analysis. A gate failure is not a reason to block delivery — it is a reason to revise before delivery.

---

### GATE 1 — RELEVANCE
**Question**: Are the selected comparison dimensions appropriate and meaningful for these specific subjects?

**Pass**: Dimensions were generated based on the specific subjects and domain. Generic dimensions were replaced or augmented with subject-specific ones.

**Fail**: The same generic template was applied regardless of domain (e.g., using "price, features, design, support" for every analysis whether it's a consumer app or a scientific concept).

**How to fix**: Remove dimensions that don't meaningfully distinguish these subjects. Add dimensions that are specific to this domain.

---

### GATE 2 — DEPTH
**Question**: Has the analysis investigated both obvious and non-obvious differences?

**Pass**: At least one finding is a non-obvious difference that wouldn't appear in a first-pass comparison. Hidden differences have been investigated using at least 2 of the 8 investigation layers.

**Fail**: Analysis stops at the first layer — what anyone would notice from a quick look.

**How to fix**: Apply the Hidden Difference workflow to any comparison that has only surfaced obvious differences.

---

### GATE 3 — ACCURACY
**Question**: Are factual claims supported by appropriate evidence classification?

**Pass**: Every factual claim has an evidence type tag: [VERIFIED FACT], [OBSERVATION], [INFERENCE], [HYPOTHESIS], or [UNKNOWN]. No invented specifications or fabricated research.

**Fail**: Factual claims made without evidence basis. Claims presented with more certainty than the evidence supports.

**How to fix**: Tag every major claim. Remove or qualify any claim that cannot be supported.

---

### GATE 4 — DIFFERENTIATION
**Question**: Have meaningful differentiators been identified — not just any differences?

**Pass**: Each identified difference has been evaluated for whether it matters, creates value, or affects experience. Trivial differences are either omitted or explicitly labeled as low-significance.

**Fail**: A list of differences without evaluation of which ones actually matter. Including "Subject A uses blue; Subject B uses dark blue" as a meaningful finding without further analysis.

**How to fix**: Apply the Value Intelligence engine to filter differences. Keep only those that clear the value threshold: they solve a problem, improve an experience, create competitive advantage, or produce meaningful emotional distinction.

---

### GATE 5 — VALUE
**Question**: Has the analysis explained WHY differences matter?

**Pass**: For every significant differentiator, the analysis answers: What does this mean for the user? Who benefits? What is the competitive consequence?

**Fail**: Differences are listed without consequence explanation. The user has to figure out why they should care.

**How to fix**: For every bullet that says "X is different," add a sentence beginning: "This matters because..."

---

### GATE 6 — ORIGINALITY
**Question**: Has unconventional thinking been applied without inventing facts?

**Pass**: At least one finding came from an unconventional angle (cross-domain lens, attribute reversal, failure mode analysis, combination archaeology). The finding is grounded in evidence, not speculation presented as fact.

**Fail**: Analysis follows a purely conventional framework. No unexpected angles were explored. OR: Unconventional ideas are presented as verified facts rather than hypothesis/inference.

**How to fix**: Apply one unconventional investigation method. Classify its output correctly as [INFERENCE] or [HYPOTHESIS] where appropriate.

---

### GATE 7 — ACTIONABILITY
**Question**: Can the user do something useful with these findings?

**Pass**: The analysis includes at least one specific, actionable recommendation. The user can identify a concrete next step.

**Fail**: Analysis is entirely descriptive with no actionable direction. User finishes reading and asks "so what do I do with this?"

**How to fix**: Add strategic recommendations section. Even a small action — a communication change, a research question to investigate, a positioning test to run — counts.

---

### GATE 8 — CLARITY
**Question**: Can a non-expert understand the conclusion?

**Pass**: Technical terms are explained on first use. The final verdict uses plain language. Someone unfamiliar with the domain could understand what makes the subject distinctive.

**Fail**: Output is dense with jargon that obscures rather than clarifies. The conclusion requires reading the entire document to understand.

**How to fix**: Rewrite the conclusion as if explaining to a smart person with no background in this specific area.

---

### GATE 9 — TRANSPARENCY
**Question**: Are limitations and uncertainties disclosed?

**Pass**: Missing information is noted. Confidence levels are stated for major conclusions. If a claim cannot be verified, the analysis says so.

**Fail**: Analysis reads as if all conclusions are equally certain. No limitations disclosed. No distinction between verified facts and inferences.

**How to fix**: Add a "Limitations" or "Confidence Notes" section. Apply evidence classification to major claims.

---

### GATE 10 — COMPLETENESS
**Question**: Does the conclusion directly answer the user's actual question?

**Pass**: The analysis begins by identifying what the user actually wants to know, and the conclusion explicitly addresses it.

**Fail**: The analysis covers interesting territory but doesn't answer what the user asked. User has to extract their answer from a general discussion.

**How to fix**: Re-read the original user request. Write a one-sentence answer to exactly that question. Place it prominently in the conclusion.

---

## SCORING RUBRIC

### What a 10/10 Analysis Looks Like
- All 10 quality gates pass
- At least 3 non-obvious findings
- Every claim has evidence classification
- Conclusions are specific, actionable, and memorable
- At least one finding surprises even a knowledgeable reader
- Final verdict is a single, powerful sentence that captures the essential discovery
- Limitations are disclosed without undermining the analysis
- The analysis would be useful to someone who knows the subjects well

### What a 7/10 Analysis Looks Like
- 8–9 quality gates pass
- At least 1 non-obvious finding
- Most major claims have evidence classification
- Conclusions are specific but not deeply actionable
- Final verdict is specific enough to be useful
- Some limitations disclosed
- Would be useful to a general audience

### What a 5/10 Analysis Looks Like
- 6–7 quality gates pass
- Mostly obvious findings with surface differences
- Some claims made without evidence classification
- Conclusions are somewhat generic
- Final verdict is acceptable but not memorable
- Limitations not fully disclosed
- Useful but doesn't exceed what the user could find with a quick search

### What a 3/10 Analysis Looks Like
- 4–5 quality gates pass
- Only obvious findings
- Many claims without evidence basis
- Generic conclusions ("both have their strengths")
- Final verdict is weak or absent
- No limitations disclosed
- User gains little beyond what they already knew

### What a 1/10 Analysis Looks Like
- Fewer than 4 gates pass
- May contain fabricated information
- Conclusions contradict evidence
- No structure or format
- Final verdict is a cliché or absent
- User cannot act on any finding

---

## ANTI-PATTERN DETECTION

These are warning signs that the analysis has failed before reviewing individual gates.

| Anti-Pattern                          | Description                                                        | Corrective Action                             |
|---------------------------------------|-------------------------------------------------------------------|-----------------------------------------------|
| The Both-and Escape                   | "Both are unique in their own way"                                | Force a specific answer about the strongest differentiator |
| The Preference Dodge                  | "It depends on personal preference" without elaboration           | Identify specific preferences and what drives them |
| The Spec Table with No Insight        | Feature comparison table with no interpretation or conclusion     | Add a "What This Means" column to every table |
| The Superlative Without Evidence      | "First," "only," "most unique" without evidence                   | Apply Novelty Intelligence protocol; add evidence classification |
| The Generic Encouragement             | "This is a great idea with strong potential" (for a small business audit) | Remove all evaluative praise not supported by specific finding |
| The Invented Fact                     | Describing a competitor's specific feature that was not verified  | Remove or classify as [HYPOTHESIS]; add verification note |
| The Category Error                    | Applying business framework dimensions to creative comparison     | Regenerate dimensions appropriate to domain |
| The One-Size Template                 | Same 6 dimensions used for every analysis regardless of subject  | Generate subject-specific dimensions every time |
| The False Balance                     | Artificially presenting both subjects as equally distinctive     | Make honest differentiation assessment, even if asymmetric |
| The Confidence Inflation              | Stating a hypothesis with the confidence of a verified fact      | Apply evidence classification to every major claim |

---

## CALIBRATION EXAMPLES

### Example: Good vs. Poor Final Verdict

**Subject**: Comparing Notion and Linear for a software engineering team.

**Poor (3/10)**:
> "Both Notion and Linear are excellent tools with different strengths. The best choice depends on your team's specific needs and preferences."

*Why poor*: No specific finding. No differentiation. No actionable direction. User learns nothing.

---

**Acceptable (6/10)**:
> "Notion is a flexible workspace for teams that need to combine documentation, wikis, and project tracking. Linear is purpose-built for software engineering workflows with speed and keyboard-first design as core values. For engineering teams, Linear typically provides a better workflow experience."

*Why acceptable*: Makes a specific recommendation. Identifies key difference. Still somewhat generic.

---

**Strong (9/10)**:
> "Linear's decisive advantage for engineering teams isn't its feature set — it's the philosophy embedded in its design: software development work deserves tooling as fast and focused as the work itself. Everything in Linear (keyboard shortcuts, instant load times, opinionated workflow states) is a consequence of this belief. Notion's flexibility is powerful but requires significant setup and maintenance that engineering teams often resist. If your team actually uses your project tool (not around it), Linear. If you need a single tool for the whole company including non-technical teams, Notion."

*Why strong*: Identifies a philosophical difference (not just features). Explains what that philosophy means in practice. Makes a specific, conditional recommendation. Gives the user a decision rule they can apply.

---

## SELF-REVIEW CHECKLIST

Before delivering any analysis, answer these 10 questions:

1. ☐ Did I look beyond the first layer of obvious differences?
2. ☐ Is every major claim tagged with an evidence classification?
3. ☐ Did I evaluate whether each difference actually creates value?
4. ☐ Did I apply at least one non-conventional investigation angle?
5. ☐ Would this analysis surprise a knowledgeable reader with at least one finding?
6. ☐ Does my final verdict directly answer what the user asked?
7. ☐ Is my verdict specific enough that it couldn't apply to any other pair of subjects?
8. ☐ Did I disclose what I don't know and what I couldn't verify?
9. ☐ Does the analysis include at least one actionable recommendation?
10. ☐ Have I avoided every anti-pattern listed above?

**Minimum passing score for delivery: 8/10 questions answered YES.**

---

## DOMAIN-SPECIFIC QUALITY CRITERIA

### Technology & AI
- Must distinguish capability claims from performance benchmarks
- Must note version/date sensitivity of all technical claims
- Must not make comparison claims without evidence for both sides

### Creative Industries
- Must apply the influence continuum (not binary original/derivative)
- Must assess concept and execution separately
- Must establish cultural context before evaluating originality

### Business & Commerce
- Must distinguish strategic positioning from operational characteristics
- Must consider defensibility of differentiation (can it be copied easily?)
- Must connect differentiation to economic value where possible

### Personal & Professional
- Must connect individual characteristics to concrete professional situations
- Must distinguish combination uniqueness from individual credential uniqueness
- Must avoid generic career advice in favor of specific differentiation insights

### Science & Nature
- Must not conflate novelty with scientific importance
- Must apply appropriate precision to scientific claims
- Must establish the comparison universe before evaluating novelty

---

## EVIDENCE QUALITY ASSESSMENT FRAMEWORK

| Classification     | Definition                                           | Example                                              |
|--------------------|------------------------------------------------------|------------------------------------------------------|
| VERIFIED FACT      | Confirmed from primary source; independently verifiable | "iPhone 15 Pro uses the A17 Pro chip [Apple spec page]" |
| OBSERVATION        | Directly observed from available material            | "The logo uses a circular container"                 |
| INFERENCE          | Reasonable interpretation derived from evidence      | "The opinionated workflow suggests the team values speed over flexibility" |
| HYPOTHESIS         | An explanation that fits evidence but isn't confirmed | "The company may be positioning for enterprise given the pricing structure" |
| UNKNOWN            | Cannot be determined from available information      | "No public information exists about their ML model architecture" |

**Rule**: The stronger the claim, the stronger the required evidence classification. Claims of unprecedented novelty require VERIFIED FACT classification supported by named comparison universe research.
