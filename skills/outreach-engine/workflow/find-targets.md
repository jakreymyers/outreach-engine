# Workflow: Find Targets

> **Purpose:** Identify where target customers gather and who to reach out to.
>
> **Use when:** Starting validation, expanding target list, current targets not responding, or pivoting to new segment.

---

## Prerequisites

**Load these files BEFORE starting:**

1. `knowledge/outreach-principles.md` - For targeting philosophy
2. `knowledge/channel-guide.md` - For platform-specific tactics
3. `knowledge/validation-vs-acquisition.md` - For stage-appropriate targeting

---

## Workflow Overview

```
Step 1: Define the Problem → What are you validating?
    ↓
Step 2: Map Communities → Where do these people gather?
    ↓
Step 3: Find Signals → Who is actively experiencing the problem?
    ↓
Step 4: Generate Targets → Build list with context
    ↓
Step 5: Prioritize → Rank and prepare for outreach
```

---

## Step 1: Define the Problem You're Validating

Before finding targets, get crystal clear on what you're testing.

### Required Inputs

| Input | Description | Example |
|-------|-------------|---------|
| **Problem Statement** | The pain you believe exists | "First-time founders waste months building without validation" |
| **Target User** | Who experiences this problem | "Solo founders with day jobs building side projects" |
| **Current Solution** | How they solve it today | "Guessing, asking friends, reading blog posts" |
| **Hypothesis** | What you believe about their behavior | "They would pay for structured validation workflows" |

### Problem Definition Template

```markdown
## Problem Definition

**Problem:** [One sentence describing the pain]

**Who experiences it:** [Specific description of target user]

**When it happens:** [Trigger moment or context]

**Current workarounds:** [How they handle it today]

**What I'm testing:** [Specific hypothesis to validate]
```

### Quality Check

Before proceeding, verify:

- [ ] Problem is specific, not vague ("founders struggle" is too broad)
- [ ] Target user is identifiable (you could recognize them)
- [ ] Current solution describes real behavior, not assumed behavior
- [ ] Hypothesis is falsifiable (could be proven wrong)

---

## Step 2: Identify Communities

Find where your target users naturally gather online and offline.

### Community Discovery Process

**2.1 Direct Search**

Search for communities using WebSearch:
- "[target user] + reddit"
- "[target user] + slack community"
- "[target user] + discord"
- "[problem] + forum"
- "[target user] + twitter"
- "[target user] + linkedin group"

**2.2 Adjacent Community Mapping**

Your target users also belong to adjacent communities:

| If Target Is | Also Check |
|--------------|------------|
| Solo founders | Indie hackers, bootstrappers, side project communities |
| Developers building products | Programming subreddits, dev Twitter |
| Small business owners | Local business groups, industry associations |
| B2B buyers | Professional LinkedIn groups, industry Slacks |

**2.3 Competitor Communities**

Where do users of similar products gather?

- Product review sites (G2, Capterra for B2B; Reddit for consumer)
- Alternative-to sites ("X alternatives")
- Competitor social media followers

### Community Evaluation Criteria

| Criteria | Good Sign | Bad Sign |
|----------|-----------|----------|
| **Activity** | Daily posts, recent activity | Ghost town, last post months ago |
| **Relevance** | Problem discussed regularly | Off-topic for your focus |
| **Accessibility** | Can observe or join | Closed, requires approval you won't get |
| **Size** | 1,000-50,000 members | Too small (<500) or too large (>100K diluted) |
| **Culture** | Help-seeking, discussion-oriented | Self-promotional, hostile to questions |

### Output: Community Map

```markdown
## Community Map

### Primary Communities (High Signal)
1. [Community name] - [Platform] - [Why relevant]
2. [Community name] - [Platform] - [Why relevant]
3. [Community name] - [Platform] - [Why relevant]

### Secondary Communities (Worth Monitoring)
1. [Community name] - [Platform] - [Why relevant]
2. [Community name] - [Platform] - [Why relevant]

### Competitor Adjacent
1. [Community/channel] - [What competitor] - [Access method]
```

---

## Step 3: Find Signals

Within communities, look for people actively experiencing the problem.

### Signal Types

| Signal | What It Looks Like | Why It's Valuable |
|--------|-------------------|-------------------|
| **Complaints** | "I hate when..." "So frustrating that..." | Problem is real and painful |
| **Questions** | "How do you handle...?" "Any tips for...?" | Actively seeking solution |
| **Workarounds** | "I built a spreadsheet to..." "My hack is..." | Problem important enough to DIY |
| **Recommendations** | "Looking for a tool that..." | Ready to buy/try |
| **Failures** | "I tried X but it didn't work because..." | Gap in current solutions |

### Signal Discovery Tactics

**Reddit:**
```
site:reddit.com "[problem keywords]"
site:reddit.com/r/[subreddit] "[problem keywords]"
```

Sort by: New (for recent signals), Top (for common patterns)

**Twitter/X:**
```
"[problem keywords]" -filter:links
"anyone else struggle with [problem]"
"looking for [solution type]"
```

**LinkedIn:**
```
Search posts for: "[problem keywords]"
Filter by: Your network → 2nd degree
```

**Communities (Slack/Discord):**
```
Search channel history for problem keywords
Look at #introductions for relevant people
Monitor #help or #questions channels
```

### Signal Quality Assessment

| High-Quality Signal | Low-Quality Signal |
|--------------------|-------------------|
| Recent (within 30 days) | Old (6+ months) |
| Detailed description | Vague complaint |
| Engaged responses | Ignored post |
| Clear target match | Unclear if target user |
| Emotional language | Casual mention |

---

## Step 4: Generate Qualified Targets

Build a list of 10-20 qualified targets with personalization context.

### Target Qualification Criteria

**Must Have:**
- [ ] Matches target user profile
- [ ] Shows signal of experiencing the problem
- [ ] Reachable (can find contact method)

**Nice to Have:**
- [ ] Recent activity (engaged, responsive)
- [ ] Influence (others might follow)
- [ ] Accessible (not too senior/busy)

### Target Research Checklist

For each potential target, gather:

| Field | Purpose | Where to Find |
|-------|---------|---------------|
| **Name** | Personalization | Profile |
| **Role/Title** | Confirm target fit | LinkedIn, bio |
| **Company/Project** | Context | LinkedIn, personal site |
| **Signal Found** | Why they're a target | The post/comment you found |
| **Platform** | Where to reach them | Where signal was found |
| **Personalization Hook** | Opener material | Recent post, shared interest, mutual connection |
| **Contact Method** | How to reach | LinkedIn, Twitter, email |

### Target List Template

```markdown
## Target List

**Generated:** [Date]
**Problem:** [Problem being validated]
**Target Profile:** [Target user description]

---

### Target 1: [Name]

| Field | Value |
|-------|-------|
| **Role** | [Title/Role] |
| **Company/Project** | [Organization or project] |
| **Signal** | "[Quote or description of signal]" |
| **Source** | [Platform and link] |
| **Hook** | [Personalization angle] |
| **Contact** | [Best way to reach] |
| **Priority** | [High/Medium/Low] |

---

### Target 2: [Name]
[Repeat format]
```

---

## Step 5: Prioritize and Prepare

Rank targets and prepare context for outreach.

### Prioritization Matrix

| Factor | Weight | Scoring |
|--------|--------|---------|
| Signal strength | 40% | 5=complained+asked for help, 3=mentioned problem, 1=fits profile only |
| Accessibility | 30% | 5=responded to others, 3=active recently, 1=dormant |
| Relevance fit | 30% | 5=exact match, 3=close match, 1=adjacent |

**Score each target 1-5 on each factor, weight and sum.**

### Prioritized List

Organize targets into tiers:

```markdown
## Prioritized Targets

### Tier 1: Start Here (Score 4-5)
High signal, accessible, strong fit. Reach out first.

1. [Name] - [Score] - [One-line reason]
2. [Name] - [Score] - [One-line reason]
3. [Name] - [Score] - [One-line reason]

### Tier 2: Second Wave (Score 3-4)
Good fit but weaker signal or less accessible.

1. [Name] - [Score] - [One-line reason]
2. [Name] - [Score] - [One-line reason]

### Tier 3: If Needed (Score 2-3)
Backup targets or require more effort.

1. [Name] - [Score] - [One-line reason]
```

### Pre-Outreach Context Prep

For each Tier 1 target, prepare:

1. **Read their recent content** - Last 5 posts/comments
2. **Identify shared context** - Mutual connections, shared interests, similar experience
3. **Note their communication style** - Formal/casual, detailed/brief
4. **Choose platform** - Match where they're most active

---

## Output: Complete Target Package

At the end of this workflow, you should have:

```markdown
# Target Package: [Problem/Validation Focus]

## Problem Definition
[From Step 1]

## Community Map
[From Step 2]

## Signal Patterns
[Summary of signal types found, common themes]

## Target List
[From Step 4, full details]

## Prioritized Outreach Order
[From Step 5]

## Notes
- [Any observations about the target market]
- [Patterns noticed during research]
- [Concerns or questions to resolve]
```

---

## Quick Reference: Find Targets Checklist

```markdown
## Find Targets Checklist

**Problem Definition**
- [ ] Problem statement is specific and falsifiable
- [ ] Target user is identifiable
- [ ] Current solution/workaround documented
- [ ] Hypothesis is clear

**Community Mapping**
- [ ] 3+ primary communities identified
- [ ] Communities evaluated for quality
- [ ] Access method confirmed

**Signal Finding**
- [ ] Searched across platforms
- [ ] Multiple signal types found
- [ ] Signals are recent and relevant

**Target Generation**
- [ ] 10-20 targets identified
- [ ] Each target has personalization context
- [ ] Signal source documented for each

**Prioritization**
- [ ] Targets scored and ranked
- [ ] Tier 1 targets ready for outreach
- [ ] Context prep complete for top targets
```

---

## Iteration

After initial outreach:

- **Low response rate?** Return to Step 2-3, find different communities/signals
- **Wrong people responding?** Refine target profile in Step 1
- **Conversations not useful?** Check if problem definition is accurate
- **Need more targets?** Repeat Step 3-4 with new signals
