# Workflow: Synthesize Insights

> **Purpose:** Turn conversations into actionable insights and a clear proceed/pivot/kill recommendation.
>
> **Use when:** Completed 3+ conversations, need to decide direction, or presenting findings to stakeholders.

---

## Prerequisites

**Load these files BEFORE starting:**

1. `knowledge/outreach-principles.md` - For synthesis philosophy
2. `knowledge/validation-vs-acquisition.md` - For stage-specific signals
3. All conversation notes from previous conversations

---

## Workflow Overview

```
Step 1: Extract Key Quotes → Pull verbatim language
    ↓
Step 2: Assess Problem Intensity → Score the pain
    ↓
Step 3: Identify WTP Signals → Would they pay?
    ↓
Step 4: Pattern Recognition → What repeats?
    ↓
Step 5: Generate Recommendation → Proceed / Pivot / Kill
```

---

## Step 1: Extract Key Quotes

Real signal lives in exact words, not summaries. Pull the most important quotes from all conversations.

### Quote Categories

Organize quotes into these categories:

| Category | What to Pull | Why It Matters |
|----------|--------------|----------------|
| **Problem descriptions** | How they describe the pain | Their language = your copy |
| **Emotional language** | Frustration, excitement, fear | Intensity indicator |
| **Current solutions** | What they use now | Competition and switching costs |
| **Desired outcomes** | What good looks like | Feature prioritization |
| **Objections** | Concerns, hesitations | Blockers to address |
| **Price signals** | What they'd pay, comparisons | Monetization signal |
| **Referral signals** | Who else to talk to | Market expansion |

### Quote Extraction Template

```markdown
## Quote Bank

### Problem Descriptions
> "[Quote]" - [Name], [Context]
> "[Quote]" - [Name], [Context]

### Emotional Language
> "[Quote]" - [Name], [Context]

### Current Solutions
> "[Quote]" - [Name], [Context]

### Desired Outcomes
> "[Quote]" - [Name], [Context]

### Objections
> "[Quote]" - [Name], [Context]

### Price Signals
> "[Quote]" - [Name], [Context]

### Referral Signals
> "[Quote]" - [Name], [Context]
```

---

## Step 2: Assess Problem Intensity

Not all problems are worth solving. Score the intensity across conversations.

### Problem Intensity Scorecard

For each conversation, score 1-5 on these dimensions:

| Dimension | 1 (Weak) | 3 (Moderate) | 5 (Strong) |
|-----------|----------|--------------|------------|
| **Existence** | "Not really a problem" | "Sometimes annoying" | "Major pain point" |
| **Frequency** | Rarely/never | Monthly | Daily/weekly |
| **Severity** | Minor inconvenience | Meaningful impact | Business-critical |
| **Current effort** | No workaround | Simple workaround | Complex DIY solution |
| **Urgency** | "Someday" | "This quarter" | "Yesterday" |

### Intensity Summary Table

```markdown
## Problem Intensity

| Person | Existence | Frequency | Severity | Effort | Urgency | Total |
|--------|-----------|-----------|----------|--------|---------|-------|
| [Name] | [1-5] | [1-5] | [1-5] | [1-5] | [1-5] | [Sum] |
| [Name] | [1-5] | [1-5] | [1-5] | [1-5] | [1-5] | [Sum] |
| [Name] | [1-5] | [1-5] | [1-5] | [1-5] | [1-5] | [Sum] |

**Average:** [Calculate]
**Range:** [Min] - [Max]
```

### Intensity Interpretation

| Average Score | Interpretation |
|---------------|----------------|
| 20-25 | Strong signal - problem is real and painful |
| 15-19 | Moderate signal - worth exploring further |
| 10-14 | Weak signal - problem may not be severe enough |
| < 10 | Very weak - likely not a real problem |

---

## Step 3: Identify Willingness-to-Pay Signals

Separate "nice to have" from "must have" by looking at payment signals.

### WTP Signal Types

| Signal Type | What It Looks Like | Strength |
|-------------|-------------------|----------|
| **Already paying** | "We spend $X on [alternative]" | Very strong |
| **Budget exists** | "We have budget for tools like this" | Strong |
| **Price anchoring** | "I'd expect to pay around $X" | Strong |
| **Time investment** | "I spend X hours/week on this" | Moderate (time = money) |
| **Urgency language** | "We need to solve this this quarter" | Moderate |
| **Hypothetical** | "I would probably pay..." | Weak |
| **Avoidance** | Changes subject when price comes up | Negative |

### WTP Assessment Table

```markdown
## Willingness to Pay

| Person | Signal | Quote | Strength |
|--------|--------|-------|----------|
| [Name] | [Type] | "[Quote]" | [Very Strong/Strong/Moderate/Weak/Negative] |
| [Name] | [Type] | "[Quote]" | [Strength] |
| [Name] | [Type] | "[Quote]" | [Strength] |

**Summary:**
- [N] Very Strong/Strong signals
- [N] Moderate signals
- [N] Weak/Negative signals
```

### Price Point Patterns

If multiple people anchored on prices, note the range:

```markdown
## Price Signals

| Person | Anchored Price | Context |
|--------|---------------|---------|
| [Name] | $[X]/mo | "[How they framed it]" |
| [Name] | $[X]/mo | "[How they framed it]" |

**Range:** $[Low] - $[High]
**Most common:** $[Mode]
**Currently paying for alternatives:** $[Range]
```

---

## Step 4: Pattern Recognition

Look across all conversations for what repeats.

### Pattern Categories

**4.1 Problem Patterns**

What problems came up multiple times?

```markdown
## Problem Patterns

| Pattern | Occurrences | Key Quotes |
|---------|-------------|------------|
| [Problem 1] | [N of Total] | "[Quote]", "[Quote]" |
| [Problem 2] | [N of Total] | "[Quote]" |
```

**4.2 Segment Patterns**

Are certain types of people more affected?

```markdown
## Segment Patterns

| Segment | Problem Intensity | WTP Signal | Notes |
|---------|-------------------|------------|-------|
| [Segment 1] | [Avg score] | [Avg strength] | [Observation] |
| [Segment 2] | [Avg score] | [Avg strength] | [Observation] |
```

**4.3 Solution Patterns**

What solution elements resonated?

```markdown
## Solution Patterns

| Feature/Approach | Positive Reactions | Negative Reactions |
|------------------|-------------------|-------------------|
| [Feature 1] | [N people, quotes] | [N people, quotes] |
| [Feature 2] | [N people, quotes] | [N people, quotes] |
```

**4.4 Objection Patterns**

What concerns came up repeatedly?

```markdown
## Objection Patterns

| Objection | Occurrences | Representative Quote |
|-----------|-------------|---------------------|
| [Objection 1] | [N of Total] | "[Quote]" |
| [Objection 2] | [N of Total] | "[Quote]" |
```

### The Convergence Test

Strong validation shows convergence:

| Convergence Level | What It Looks Like | Interpretation |
|-------------------|-------------------|----------------|
| **High** | 70%+ say similar things | Clear signal, proceed |
| **Moderate** | 50-70% alignment | Promising, need more data |
| **Low** | < 50% agreement | Divergent needs, consider segmenting |
| **None** | Everyone says different things | Wrong problem or wrong segment |

---

## Step 5: Generate Recommendation

Based on all evidence, make a clear recommendation.

### Decision Framework

Score each dimension, then apply the matrix:

| Dimension | Score (1-5) | Evidence |
|-----------|-------------|----------|
| Problem intensity | [Score] | [Summary of Step 2] |
| WTP signals | [Score] | [Summary of Step 3] |
| Pattern convergence | [Score] | [Summary of Step 4] |
| Segment clarity | [Score] | [How clear is who this is for?] |
| Solution fit | [Score] | [How well does your approach match needs?] |

### Recommendation Matrix

| Total Score | Recommendation | What to Do |
|-------------|----------------|------------|
| **20-25** | **PROCEED** | Build MVP, start with most intense segment |
| **15-19** | **ITERATE** | More conversations, refine hypothesis |
| **10-14** | **PIVOT** | Different problem or different segment |
| **< 10** | **KILL** | Move to different idea entirely |

### PROCEED Criteria

Only recommend PROCEED if:

- [ ] 70%+ experienced the problem
- [ ] Average problem intensity > 18
- [ ] At least 50% showed WTP signals (Strong or better)
- [ ] Clear segment identified
- [ ] No fatal objection pattern

### ITERATE Signals

Recommend ITERATE if:

- [ ] Problem exists but intensity unclear
- [ ] WTP signals mixed
- [ ] Patterns emerging but not converged
- [ ] Need larger sample size (< 10 conversations)

### PIVOT Signals

Recommend PIVOT if:

- [ ] Problem not consistently painful
- [ ] WTP signals weak or negative
- [ ] Patterns point to different problem than hypothesized
- [ ] Different segment more promising

### KILL Signals

Recommend KILL if:

- [ ] Problem doesn't exist or isn't painful
- [ ] No WTP signals across multiple conversations
- [ ] No pattern convergence
- [ ] Every conversation surface new objections

---

## Output: Insight Synthesis Report

Produce this report at the end of the workflow.

```markdown
# Insight Synthesis Report

**Date:** [Date]
**Conversations Analyzed:** [N]
**Problem Hypothesis:** [What you were testing]
**Target Segment:** [Who you talked to]

---

## Executive Summary

[2-3 sentences: What did we learn? What's the recommendation?]

**Recommendation:** [PROCEED / ITERATE / PIVOT / KILL]

---

## Problem Validation

### Does the Problem Exist?
[Yes/Partially/No] - [Brief evidence]

### Problem Intensity
| Metric | Value |
|--------|-------|
| Average Intensity Score | [X/25] |
| Highest Scoring Dimension | [Dimension] |
| Lowest Scoring Dimension | [Dimension] |

### Key Problem Quotes
> "[Most compelling quote about the problem]"
> "[Second most compelling]"
> "[Third]"

---

## Willingness to Pay

### WTP Summary
| Strength | Count |
|----------|-------|
| Very Strong/Strong | [N] |
| Moderate | [N] |
| Weak/Negative | [N] |

### Price Signals
[Summary of price anchoring and current spend]

### Key WTP Quotes
> "[Most compelling WTP quote]"
> "[Second]"

---

## Patterns

### Problems (Top 3)
1. **[Pattern]** - [N/Total] mentioned
2. **[Pattern]** - [N/Total] mentioned
3. **[Pattern]** - [N/Total] mentioned

### Segments (If Relevant)
[Which segment shows strongest signal?]

### Objections (Top 3)
1. **[Objection]** - [N/Total] raised
2. **[Objection]** - [N/Total] raised
3. **[Objection]** - [N/Total] raised

---

## Decision Scorecard

| Dimension | Score | Evidence |
|-----------|-------|----------|
| Problem Intensity | [X/5] | [Brief] |
| WTP Signals | [X/5] | [Brief] |
| Pattern Convergence | [X/5] | [Brief] |
| Segment Clarity | [X/5] | [Brief] |
| Solution Fit | [X/5] | [Brief] |
| **Total** | **[X/25]** | |

---

## Recommendation

### [PROCEED / ITERATE / PIVOT / KILL]

**Rationale:**
[2-3 sentences explaining why]

### If PROCEED:
- Target segment: [Specific description]
- Core problem to solve: [One sentence]
- Must-have features: [List]
- Price point: [Range based on signals]
- Next step: [Specific action]

### If ITERATE:
- Questions to answer: [List]
- Additional conversations needed: [N]
- Hypothesis to refine: [What]
- Next step: [Specific action]

### If PIVOT:
- What's promising: [From the conversations]
- New hypothesis: [Based on patterns]
- New segment to explore: [Who]
- Next step: [Specific action]

### If KILL:
- Why it failed: [Brief]
- What we learned: [Reusable insights]
- Next idea to explore: [If any]

---

## Appendix: Full Quote Bank

[Include complete quote bank from Step 1]

---

## Appendix: Individual Conversation Summaries

### [Name 1]
- Intensity Score: [X/25]
- WTP Signal: [Strength]
- Key insight: [One line]

### [Name 2]
[Repeat format]
```

---

## Disconfirmation Check

Before finalizing, actively challenge your recommendation.

### If Recommending PROCEED

Ask yourself:
- What evidence would make me doubt this?
- Which conversations were weakest? Why?
- Am I discounting negative signals?
- Is there selection bias in who I talked to?

### If Recommending KILL

Ask yourself:
- Did I talk to the right people?
- Did I ask the right questions?
- Is there a segment I missed?
- Could I have biased against this idea?

### Disconfirmation Template

```markdown
## Disconfirmation Analysis

**My recommendation:** [PROCEED/ITERATE/PIVOT/KILL]

**Strongest evidence against this recommendation:**
1. [Evidence]
2. [Evidence]
3. [Evidence]

**Why I'm still confident:**
[Response to each piece of disconfirming evidence]

**What would change my mind:**
[Specific evidence or finding that would flip the recommendation]
```

---

## Iteration

After synthesis:

- **Recommendation unclear?** Need more conversations
- **Patterns contradictory?** May need to segment differently
- **Strong signal for different problem?** Run new find-targets for that problem
- **PROCEED but unclear on features?** Run additional solution-focused conversations
