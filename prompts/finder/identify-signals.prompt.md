# Identify Buying Signals Prompt

**Purpose:** Learn to recognize posts, comments, and behaviors that indicate someone is actively experiencing your problem and might be open to a conversation.

---

## Context to Provide

Before using this prompt, prepare:

1. **Community name** - Which community are you analyzing?
2. **Problem area** - What specific problem are you solving?
3. **Target customer profile** - Who are you looking for?

---

## The Prompt

Copy everything below the line and paste into your AI tool:

---

I'm looking for people in [COMMUNITY NAME] who are experiencing [PROBLEM].

My target customer is: [BRIEF DESCRIPTION - role, situation, what they're trying to accomplish]

Help me identify the signals that indicate someone is:
1. Actively experiencing this problem
2. Frustrated enough to want a solution
3. Potentially open to a conversation

**Provide:**

### Signal Categories

For each category, give me:
- What it looks like (specific language, post types)
- Example phrases or keywords to search for
- How to distinguish real pain from casual mention

**Categories to cover:**

1. **Direct Problem Statements**
   Posts where someone explicitly states they have this problem

2. **Frustration Signals**
   Venting, complaints, rants that indicate emotional pain

3. **Solution-Seeking Behavior**
   Asking for recommendations, comparing options, requesting advice

4. **Workaround Descriptions**
   Describing hacky solutions, manual processes, or "we just do X for now"

5. **Time/Money References**
   Mentions of wasted time, budget for solutions, cost of the problem

6. **Urgency Indicators**
   Deadlines, pressure, "need this ASAP" language

7. **Decision-Making Position**
   Signals that this person can actually make or influence buying decisions

### Search Queries

Give me 10-15 specific search queries I can use in [COMMUNITY NAME] to find posts matching these signals.

Format: `"exact phrase"` for exact matches, `keyword1 keyword2` for general search

### Red Flags (Who to Skip)

What signals indicate someone is NOT a good target:
- Tire-kickers or perpetual researchers
- People too early in their journey
- Wrong company size/type for my solution
- Just venting without intent to solve

### Signal Scoring

Create a simple scoring system I can use:
- Strong signal (worth reaching out immediately)
- Medium signal (worth monitoring/engaging first)
- Weak signal (note but don't prioritize)

---

## Example Output

**Community:** r/startups
**Problem:** Founders struggle to validate ideas before building
**Target:** First-time founders with side projects

### Direct Problem Statements

**What it looks like:**
- "How do I know if my idea is worth building?"
- "Should I validate before coding?"
- "I've been building for 3 months and have no users"

**Search queries:**
- `"how do I validate"`
- `"before I build"`
- `"is my idea worth"`
- `"nobody wants"`
- `"customer discovery"`
- `validation advice

**Distinguishing real pain:**
Real pain includes emotional words (frustrated, stuck, worried, wasted) or specific time investments ("spent 6 months building"). Casual mentions are theoretical ("I've heard you should validate").

### Frustration Signals

**What it looks like:**
- "I've talked to 20 people and still don't know if this is worth building"
- "Launched to crickets again"
- "Why is it so hard to find people to talk to?"

**Search queries:**
- `"launched to crickets"`
- `"no signups"`
- `"nobody responded"`
- `"wasted time building"`
- `frustrated customer discovery`

**Distinguishing real pain:**
Look for specific numbers (hours, attempts, money spent) and past-tense language indicating they've tried and failed.

### Solution-Seeking Behavior

**What it looks like:**
- "What tools do you use for customer discovery?"
- "Has anyone tried [competitor]?"
- "Best way to find beta testers?"

**Search queries:**
- `"tools for validation"`
- `"best way to find"`
- `"has anyone tried"`
- `recommend customer discovery`

**Distinguishing real pain:**
Asking about specific features or comparing options = high intent. General "what do you think about" = low intent.

### Workaround Descriptions

**What it looks like:**
- "I just use Google Forms and manually analyze responses"
- "I've been DMing people on Twitter one by one"
- "Excel spreadsheet to track everyone I've talked to"

**Search queries:**
- `"I just use"`
- `"my process for"`
- `spreadsheet tracking`
- `manual outreach`

### Time/Money References

**What it looks like:**
- "Spent 6 months building before talking to anyone"
- "Would pay for a tool that does this"
- "This is eating all my free time"

**Search queries:**
- `"spent months"`
- `"would pay"`
- `"wasted"`
- `"hours every week"`

### Signal Scoring

| Score | Criteria | Example | Action |
|-------|----------|---------|--------|
| **Strong (3)** | Explicit problem + frustration + solution-seeking | "I've spent 3 months trying to validate and still don't know. What tools actually work?" | Reach out within 24 hours |
| **Medium (2)** | Problem mention + some frustration OR solution-seeking | "Thinking about how to validate before I start coding" | Engage with helpful comment first, then reach out |
| **Weak (1)** | Single signal without context | "Customer discovery is hard" | Note for later, don't prioritize |

### Red Flags (Skip These)

- **Students or hobbyists**: "For my class project..." or "Just learning..."
- **Already solved**: "What I ended up doing was..." (unless outcome was poor)
- **Enterprise/wrong scale**: "At my company of 500 people..."
- **Tire-kickers**: Post history shows asking same question for 6+ months with no action
- **Ideators without commitment**: "I have 10 ideas and can't decide..."

---

## Tips for Best Results

1. **Search historically** - Don't just look at new posts. Search back 3-6 months for patterns.

2. **Check post history** - Before reaching out, look at their other posts. Are they actually building? Or just talking?

3. **Note the repliers too** - Sometimes the best targets are in the comments, not the original post.

4. **Save your searches** - Bookmark or save search URLs. Check weekly for new posts matching your signals.

5. **Quality over quantity** - One strong signal is worth more than ten weak ones.

---

## Follow-Up Prompts

**"For [COMMUNITY], write me a comment I could leave on a post showing [SIGNAL TYPE] that provides value without being promotional."**

**"I found this post: [PASTE POST]. Score the signals and suggest whether to reach out."**

**"Create a daily routine I can follow to monitor these signals in 15 minutes or less."**

---

*Next step: Use `build-list.prompt.md` to compile your targets into a prioritized outreach list.*
