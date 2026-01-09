# Pattern Extraction Prompt

**Purpose:** Analyze multiple customer conversations to extract patterns, segments, and actionable insights for product and go-to-market decisions.

---

## Context to Provide

Before using this prompt, prepare:

1. **Conversation summaries** - Syntheses from individual conversations (use single-conversation.prompt.md)
2. **Number of conversations** - How many are you analyzing?
3. **Key questions** - What decisions are you trying to make?

---

## The Prompt

Copy everything below the line and paste into your AI tool:

---

I've had [NUMBER] customer conversations and need to extract patterns to inform product and go-to-market decisions.

**The decisions I need to make:**
1. [e.g., "Is this problem worth solving?"]
2. [e.g., "Who experiences it most intensely?"]
3. [e.g., "What should I build first?"]
4. [e.g., "How should I position this?"]

**My conversation summaries:**

---
**Conversation 1:** [Name, role]
[Paste summary or key points]

---
**Conversation 2:** [Name, role]
[Paste summary or key points]

---
[Continue for all conversations...]

---

**Analyze these conversations and provide:**

### 1. Pattern Summary
What clear patterns emerge across conversations?
- Things most people said or experienced
- Consistent language or framing
- Recurring pain points
- Common current solutions

### 2. Customer Segments
Do distinct segments emerge? For each segment:
- Profile description
- Problem intensity (high/medium/low)
- Willingness to pay
- Number of conversations in this segment
- Best messaging approach

### 3. Problem Validation Matrix
| Aspect | Evidence For | Evidence Against | Confidence |
|--------|-------------|------------------|------------|
| Problem exists | | | High/Med/Low |
| Problem is painful | | | |
| Problem is urgent | | | |
| People will pay to solve | | | |

### 4. Unexpected Insights
What surprised you? What challenges initial assumptions?

### 5. Key Quotes Library
Organize the best quotes by category:
- Problem awareness
- Emotional pain
- Current solutions
- Willingness to pay
- Feature requests
- Objections

### 6. Feature/Solution Priorities
Based on conversations, what should be built first?
| Feature/Capability | Mentioned by | Intensity | Recommendation |
|-------------------|--------------|-----------|----------------|
| | | | |

### 7. Messaging Insights
- Language that resonates (exact words they used)
- Framing that works
- Positioning angles supported by evidence

### 8. Gaps in Research
What don't we know yet? What questions remain unanswered?

### 9. Decision Recommendations
For each decision I listed:
- Recommendation
- Confidence level
- Key supporting evidence
- What would change this recommendation

### 10. Next Steps
- Should I do more conversations? How many? With whom?
- What to test or build next?
- What to stop doing based on this data?

---

## Example Output

**Conversations:** 10 validation interviews
**Decisions:** Is validation painful? Who needs it most? What to build first? How to position?

---

### 1. Pattern Summary

**Strong patterns (7+ out of 10):**
- All had built something that didn't get traction (10/10)
- Most skipped validation because "I have this problem too" assumption (8/10)
- Felt validation was "amorphous" or hard to know when done (8/10)
- Currently use combination of Reddit, Twitter, and talking to friends (7/10)
- Would pay to avoid repeating the failed launch experience (7/10)

**Moderate patterns (4-6 out of 10):**
- Fear of starting next project due to past failure (6/10)
- Previously tried Typeform/Google Forms for surveys, didn't help (5/10)
- Wanted "a system" or "structure" (5/10)
- Had budget concerns but would pay if value clear (5/10)

**Weak/emerging patterns (1-3 out of 10):**
- Some interested in team features (2/10)
- Some wanted AI to do the validation for them (3/10)
- Interest in community of other founders (2/10)

---

### 2. Customer Segments

**Segment A: The Burned Launcher (4/10 conversations)**

| Dimension | Detail |
|-----------|--------|
| Profile | Founder who launched something that failed. Now gun-shy. |
| Problem intensity | Very High (5/5) |
| Willingness to pay | High - "I'd pay to not repeat that" |
| Key quotes | "Terrified to start building again" |
| Best messaging | Loss avoidance: "Don't waste another 6 months" |

**Segment B: The Methodical Researcher (3/10 conversations)**

| Dimension | Detail |
|-----------|--------|
| Profile | Founder who knows validation matters but doesn't know how |
| Problem intensity | Medium-High (4/5) |
| Willingness to pay | Medium - needs to see clear process |
| Key quotes | "I know I should talk to people but it feels random" |
| Best messaging | Process and structure: "A system for validation" |

**Segment C: The Time-Constrained Builder (2/10 conversations)**

| Dimension | Detail |
|-----------|--------|
| Profile | Has a day job, building on side, limited hours |
| Problem intensity | Medium (3/5) |
| Willingness to pay | Medium-Low - very budget conscious |
| Key quotes | "I don't have time to do proper research" |
| Best messaging | Efficiency: "Compress weeks into hours" |

**Segment D: The Idea Collector (1/10 conversations)**

| Dimension | Detail |
|-----------|--------|
| Profile | Multiple ideas, can't decide, hasn't committed to any |
| Problem intensity | Low (2/5) |
| Willingness to pay | Low - not serious enough yet |
| Key quotes | "I have 10 ideas and can't figure out which one" |
| Best messaging | May not be target customer - too early |

**Recommendation:** Focus on Segment A (Burned Launchers) first. Highest intensity, clearest willingness to pay, most acute pain.

---

### 3. Problem Validation Matrix

| Aspect | Evidence For | Evidence Against | Confidence |
|--------|-------------|------------------|------------|
| Problem exists | 10/10 experienced it directly | None | **High** |
| Problem is painful | 8/10 used emotional language; 4 described as "devastating" | 2/10 seemed more intellectually interested than pained | **High** |
| Problem is urgent | 7/10 are between projects now, actively deciding | 3/10 are still building current project | **Medium-High** |
| People will pay to solve | 7/10 stated explicit willingness; amounts ranged $20-100/mo | 3/10 had budget concerns or wanted free | **Medium-High** |

**Overall problem validation confidence: High**

---

### 4. Unexpected Insights

1. **Fear is more motivating than aspiration**
   - Expected: "I want to build something successful"
   - Actual: "I'm terrified of wasting another 6 months"
   - Implication: Loss-avoidance messaging may outperform gain-seeking

2. **"Done with validation" is undefined**
   - Expected: People want better tools for validation
   - Actual: People don't know what "validated" even means
   - Implication: Clear signal of "you're ready to build" is valuable

3. **They've tried surveys - they don't work**
   - Expected: Survey tools are the competition
   - Actual: Surveys are seen as useless - "I got responses but didn't learn anything"
   - Implication: Position against surveys, not as a survey tool

4. **The "I have this problem" assumption is pervasive**
   - 8/10 explicitly mentioned assuming their own experience was enough
   - Implication: This is a strong hook for content/messaging

---

### 5. Key Quotes Library

**Problem awareness:**
- "I figured if I have this problem, others must too." (Sarah)
- "I never really validated. I just built it." (Mike)
- "I know validation matters but I don't know how to do it." (Alex)

**Emotional pain:**
- "Devastating." (Sarah, on launch day)
- "I spent the whole weekend refreshing Product Hunt." (Sarah)
- "I don't want to go through that again." (Jake)
- "Terrified to start building." (Sarah)

**Current solutions:**
- "It feels random and scattered." (Sarah, on Reddit research)
- "I talk to friends and they say it's a good idea." (Multiple)
- "I tried surveys but didn't learn anything useful." (Lisa)

**Willingness to pay:**
- "I'd pay $50/month for something that would have saved me 6 months." (Sarah)
- "If it could tell me whether to keep going, I'd pay for that." (Mike)
- "I'd pay to not waste another year." (Jake)

**Feature requests:**
- "I wish I had a system." (Multiple)
- "Something that tells me when I'm done." (Alex)
- "A way to organize what I'm learning from conversations." (Lisa)

**Objections:**
- "I can just talk to people on Reddit." (Jake, before describing it as scattered)
- "I'm not sure I need a tool for this." (Initial reaction from 3/10)

---

### 6. Feature/Solution Priorities

| Feature/Capability | Mentioned by | Intensity | Recommendation |
|-------------------|--------------|-----------|----------------|
| Clear "validation complete" signal | 6/10 | High | Build first - key differentiator |
| Conversation/interview guidance | 5/10 | High | Build first - immediate value |
| Research synthesis/pattern extraction | 4/10 | Medium | Build second |
| Community finding | 3/10 | Medium | Build second |
| Survey alternative | 3/10 | Low | Deprioritize - not seen as valuable |
| AI doing research for you | 2/10 | Low | Deprioritize - not validated |
| Team/collaboration | 2/10 | Low | Deprioritize - most are solo |

---

### 7. Messaging Insights

**Language that resonates (actual words used):**
- "System" (multiple)
- "Scattered" (negative - what they have now)
- "Devastating" (emotional hook)
- "Terrified" (emotional hook)
- "Another 6 months" (loss framing)

**Framing that works:**
- Loss avoidance > Gain seeking
- "Process" and "structure" > "Tools"
- "Confidence" and "clarity" > "Data"

**Positioning angles supported:**
1. **Against repeating failure:** "Don't waste another 6 months"
2. **For the burned founder:** "You've been there. Never again."
3. **System/structure:** "A system for validation, not more guesswork"
4. **Knowing when you're done:** "Know when to build. Know when to stop."

---

### 8. Gaps in Research

**Still don't know:**
1. Price sensitivity specifics - What's the ceiling? (tested $20-100 range but not systematically)
2. B2B vs. B2C founder differences - Is pain the same?
3. How technical founders differ from non-technical
4. Whether agency/consulting model would be preferred over self-serve
5. Long-term retention - Will they keep using after initial validation?

**Questions for next conversations:**
- "If this were $99/month instead of $49, would that change your decision?"
- "Would you rather pay more for someone to do this for you, or less to do it yourself with guidance?"

---

### 9. Decision Recommendations

**Decision 1: Is this problem worth solving?**
- **Recommendation:** Yes
- **Confidence:** High
- **Evidence:** 10/10 experienced it, 7/10 would pay, high emotional intensity
- **What would change this:** If willingness to pay doesn't convert to actual payment

**Decision 2: Who experiences it most intensely?**
- **Recommendation:** "Burned Launchers" - founders who've shipped something that failed
- **Confidence:** High
- **Evidence:** Highest intensity, clearest willingness to pay, most specific pain
- **What would change this:** If this segment is too small to build a business on

**Decision 3: What should I build first?**
- **Recommendation:** Conversation guidance + clear "done" signal
- **Confidence:** Medium-High
- **Evidence:** Most requested, addresses "scattered" pain, differentiates from surveys
- **What would change this:** If early users prioritize something else

**Decision 4: How should I position this?**
- **Recommendation:** Lead with loss-avoidance ("Don't waste another 6 months"), position as system/process, target burned founders
- **Confidence:** Medium-High
- **Evidence:** Emotional language, "system" requests, fear > aspiration pattern
- **What would change this:** A/B testing of actual messaging

---

### 10. Next Steps

**Do I need more conversations?**
- For problem validation: No - sufficient confidence
- For pricing: Yes - 3-5 more with explicit price testing
- For feature prioritization: Maybe - could start building and validate with beta users

**Who to target next:**
- More "Burned Launchers" to confirm segment
- A few B2B founders to check if pattern holds
- 2-3 from different channels to avoid selection bias

**What to build:**
- MVP focused on conversation guidance + progress tracking
- Clear signal of "you have enough evidence to decide"
- Simple, not comprehensive

**What to stop doing:**
- Stop trying to reach "Idea Collectors" - not ready to pay
- Stop positioning against surveys - they don't see surveys as the problem
- Stop worrying about team features - solo founders are the core

---

## Tips for Best Results

1. **Need at least 5 conversations** - Patterns don't emerge reliably with fewer

2. **10 is the sweet spot** - Enough for patterns, not so many that synthesis is overwhelming

3. **Include negative data** - The conversations that didn't go well are as informative as the wins

4. **Look for contradictions** - Where people disagree tells you where to dig deeper

5. **Update as you go** - Re-run this prompt after each batch of 3-5 conversations

---

## Follow-Up Prompts

**"I have 5 more conversations since this analysis. Update the patterns with new data: [PASTE]"**

**"My initial assumption was [X]. Based on this data, is that validated or invalidated?"**

**"Help me create an ICP (Ideal Customer Profile) document based on these patterns."**

**"Turn these insights into a one-page product spec."**

**"Generate marketing copy using the exact language from these quotes."**

---

*You've completed the Outreach Engine workflow. Return to the README for guidance on next iterations.*
