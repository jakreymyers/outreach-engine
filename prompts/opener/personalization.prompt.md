# Personalization Prompt

**Purpose:** Take a message template and customize it for a specific target using their public profile, posts, and context.

---

## Context to Provide

Before using this prompt, prepare:

1. **Your message template** - The base message you want to personalize
2. **Target profile info** - Paste their LinkedIn summary, Twitter bio, or relevant posts
3. **Personalization goal** - What should the personalization accomplish?

---

## The Prompt

Copy everything below the line and paste into your AI tool:

---

I have a message template that I want to personalize for a specific target.

**My template:**
```
[PASTE YOUR MESSAGE TEMPLATE HERE]
```

**Target profile/posts:**
```
[PASTE RELEVANT INFO: LinkedIn summary, Twitter bio, recent posts, comments, etc.]
```

**What I'm looking for in personalization:**
- Reference something specific they said/did
- Connect my outreach to their actual situation
- Feel like I wrote this message just for them, not batch-sent to 50 people

**Provide:**

### 1. Personalization Hooks
Identify 3-5 specific things I could reference that would make this feel personalized:
- Direct quotes or ideas they've shared
- Specific projects/products they've worked on
- Challenges they've mentioned
- Achievements worth acknowledging
- Connections between what they're doing and what I'm working on

### 2. Personalized Message
Rewrite my template incorporating the best 1-2 personalization hooks.
- Keep the overall structure
- Make the personalization feel natural, not forced
- Don't over-personalize (creepy is worse than generic)

### 3. Alternative Opening Lines
Give me 3 alternative opening lines using different hooks, so I can choose what feels right.

### 4. Personalization Quality Check
Rate the personalization on:
- Relevance (1-5): Does this hook actually relate to my outreach topic?
- Specificity (1-5): Would they know I did real research vs. surface-level look?
- Natural tone (1-5): Does it sound like a real person, not a template?

### 5. Danger Zones
Flag anything that might:
- Come across as stalker-ish
- Reference something too personal
- Be inaccurate based on the info provided
- Feel like try-hard flattery

---

## Example Output

**Template:**
```
Hey [NAME] -

I noticed you're building in the [SPACE] space.

I'm researching how founders validate ideas before building. Would you be open to a 15-minute call to share your experience?

Not pitching anything - just trying to understand the patterns.
```

**Target profile (Twitter bio + recent tweets):**
```
Bio: "Building @TaskFlow | Previously eng at Stripe | Writing about the chaos of going from employee to founder | DMs open"

Recent tweets:
- "Month 6 of building TaskFlow: finally talked to users instead of just building. Should have done this day 1."
- "The hardest part of being a founder isn't the building. It's deciding what to build."
- "Hiring is 100x harder than I expected. Currently: team of 1.5"
```

---

### 1. Personalization Hooks

| Hook | Source | Relevance |
|------|--------|-----------|
| "Finally talked to users instead of just building" tweet | Twitter | High - directly about validation |
| "Deciding what to build is hardest" tweet | Twitter | High - exactly my research topic |
| Stripe engineering background | Bio | Medium - engineering-first founder |
| "Chaos of employee to founder" positioning | Bio | Medium - transition story |
| "Team of 1.5" / resource constraints | Twitter | Medium - solo founder struggles |

**Best hooks:** The two tweets about talking to users and deciding what to build are perfect - they directly relate to validation and show he's already thinking about this.

---

### 2. Personalized Message

```
Hey Alex -

Your tweet about "finally talking to users instead of just building" hit close to home. I've been there - Month 4 of my last project before I realized I was solving a problem I'd invented.

I'm researching how founders navigate that "deciding what to build" part (stealing your phrasing because it's exactly right). Specifically trying to understand what makes some founders validate early vs. skip straight to building.

Would you be open to a 15-minute call to share what shifted for you at Month 6?

Not pitching anything - genuinely trying to understand the pattern.
```

**Changes made:**
- Opened with specific tweet reference (shows I actually read his content)
- Connected my experience to his (peer framing)
- Used his exact phrasing about "deciding what to build" (validation of his thinking)
- Specific question about "Month 6" (shows attention to detail)
- Kept the rest of the structure intact

---

### 3. Alternative Opening Lines

**Option A (shared struggle):**
```
Hey Alex - your "deciding what to build is hardest" tweet is the truest thing I've read this week. I'm living that right now.
```

**Option B (acknowledging growth):**
```
Hey Alex - I saw your thread about Month 6 at TaskFlow. The shift from building to talking to users is one I wish I'd made earlier on my last project.
```

**Option C (Stripe background connection):**
```
Hey Alex - fellow ex-big-tech-turned-founder here. Your tweets about the transition chaos are validating my own experience.
```

---

### 4. Personalization Quality Check

| Dimension | Score | Notes |
|-----------|-------|-------|
| Relevance | 5/5 | Both hooks directly relate to validation topic |
| Specificity | 4/5 | References specific tweets and timeframe |
| Natural tone | 4/5 | Sounds like genuine recognition, not flattery |

**Overall:** Strong personalization. The tweet references are specific enough to stand out but not so deep that it feels like you've been digging through his entire timeline.

---

### 5. Danger Zones

- **Safe:** Referencing public tweets is fair game
- **Safe:** Acknowledging the Stripe background (it's in his bio)
- **Avoid:** Don't reference specific TaskFlow customer numbers or revenue if he's shared them - feels like you're sizing him up
- **Caution:** The "team of 1.5" could feel like you're noting he's struggling. Don't reference unless relevant to your topic.

---

## Batch Personalization Mode

For multiple targets at once, use this format:

```
I have a template and 5 targets. For each, provide:
1. Best personalization hook (one sentence)
2. Personalized opening line
3. One thing to avoid

**Template:**
[YOUR TEMPLATE]

**Target 1:**
[PROFILE INFO]

**Target 2:**
[PROFILE INFO]

[etc.]
```

This gives you fast, actionable personalization for batch outreach while keeping quality high.

---

## Tips for Best Results

1. **2 minutes max per target** - If it takes longer, you're over-personalizing. Quick reference is better than deep research.

2. **One strong hook > three weak ones** - Don't cram multiple references into one message. Pick the best one.

3. **Recent > old** - Something they posted this week is better than something from 6 months ago.

4. **Don't fake connections** - If you don't actually relate to their experience, don't pretend you do.

5. **Test generic vs. personalized** - Track response rates. Some audiences respond better to brief and direct; others need personalization.

---

## Follow-Up Prompts

**"This person has no public profile. What's the minimum viable personalization?"**

**"Personalize this for 3 targets in the same company (different roles)."**

**"The personalization feels forced. Make it more subtle."**

**"I only have their name and company. What can I personalize?"**

---

*Next step: After sending, use `conversation/validation-interview.prompt.md` to prepare for the actual conversation.*
