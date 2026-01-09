# Outreach Engine Prompts

Universal AI prompts that work with ChatGPT, Claude.ai, Gemini, or any AI tool. Copy-paste ready for founders who need to find and talk to customers.

---

## What This Is

A system of prompts that helps founders do customer outreach without being salespeople. Each prompt is designed to:

- Work standalone (no special tools required)
- Produce immediately usable output
- Build on previous outputs for a complete workflow

---

## Quick Start

**If you have 30 minutes:** Use just two prompts:
1. `finder/find-communities.prompt.md` - Find where your customers hang out
2. `opener/cold-dm.prompt.md` - Craft a message that gets responses

**If you have 2 hours:** Complete the full Finder + Opener workflow, then track in a spreadsheet.

**If you're doing 10+ conversations:** Add the Synthesizer prompts to extract patterns.

---

## Which AI Tool Works Best?

| Tool | Best For | Notes |
|------|----------|-------|
| **ChatGPT (GPT-4)** | General use, all prompts | Reliable, good at following structure |
| **Claude** | Long conversations, synthesis | Better memory, more nuanced responses |
| **Gemini** | Research-heavy tasks | Good at pulling in web context |
| **Perplexity** | Finding communities | Built-in search makes Finder prompts shine |

All prompts work with any tool. Choose based on what you have access to.

---

## Workflow Order

### Stage 1: The Finder

Find where your target customers gather and what signals indicate buying intent.

| Prompt | Purpose | Time |
|--------|---------|------|
| `find-communities.prompt.md` | Identify relevant communities | 15 min |
| `identify-signals.prompt.md` | Know what buying signals look like | 10 min |
| `build-list.prompt.md` | Create prioritized target list | 20 min |

**Output:** 10-20 qualified targets with context for personalization

### Stage 2: The Opener

Craft messages that get responses by framing outreach as research, not selling.

| Prompt | Purpose | Time |
|--------|---------|------|
| `cold-dm.prompt.md` | Direct outreach (LinkedIn, Twitter) | 10 min |
| `warm-intro.prompt.md` | Leverage mutual connections | 10 min |
| `community-post.prompt.md` | Posts that invite responses | 15 min |
| `personalization.prompt.md` | Customize templates for specific targets | 5 min each |

**Output:** Ready-to-send messages tailored to each target

### Stage 3: The Conversation

Scripts and questions for actual customer conversations.

| Prompt | Purpose | Time |
|--------|---------|------|
| `validation-interview.prompt.md` | Problem validation questions | 15 min |
| `sales-discovery.prompt.md` | Qualification and pain quantification | 15 min |
| `follow-up.prompt.md` | Post-conversation messages | 5 min |

**Output:** Interview scripts, discovery frameworks, follow-up templates

### Stage 4: The Synthesizer

Extract patterns and make decisions from conversation data.

| Prompt | Purpose | Time |
|--------|---------|------|
| `single-conversation.prompt.md` | Synthesize one conversation | 10 min |
| `pattern-extraction.prompt.md` | Extract patterns from multiple conversations | 30 min |

**Output:** Key quotes, patterns, segments, confidence levels, recommendations

---

## File Format

Each prompt file follows this structure:

```
1. Title and Purpose
2. Context Requirements (what to provide)
3. The Prompt (copy-pasteable)
4. Example Output
5. Tips for Best Results
```

---

## Tips for Best Results

### Before You Start

1. **Write down your problem hypothesis** - One sentence: "I believe [target customers] struggle with [problem] when trying to [goal]."
2. **Know your stage** - Are you validating the problem exists? Or selling a solution?
3. **Set a conversation target** - 10 conversations is the minimum for patterns.

### Using the Prompts

1. **Copy the entire prompt** - Including the context section. Fill in your specifics.
2. **Provide real examples** - The more context you give, the better the output.
3. **Iterate in the same chat** - AI tools remember context. Refine outputs in conversation.

### After Each Conversation

1. **Take notes immediately** - Memory fades fast. Capture quotes verbatim.
2. **Run the single-conversation synthesizer** - Extracts signal while fresh.
3. **Update your tracker** - Momentum comes from seeing progress.

---

## The 10 Conversation Rule

Everything in this system points toward one goal: **10 real conversations with potential customers.**

Why 10?
- Less than 5 = anecdotes, not patterns
- More than 20 = diminishing returns without action
- 10 = enough signal to make a decision

After 10 conversations, you should know:
- Is this problem real and painful?
- Who experiences it most intensely?
- What would they pay to solve it?
- What should you build first?

---

## What This Won't Do

- Replace the actual conversation (that's on you)
- Find phone numbers or emails (use Apollo, LinkedIn, etc.)
- Send messages automatically (stay human)
- Give you guaranteed response rates (but it helps)

---

## Tracking Progress

Use this simple tracker format:

| # | Name | Source | Signal | Reached | Replied | Booked | Notes |
|---|------|--------|--------|---------|---------|--------|-------|
| 1 | Jane S. | r/startups | Asked about customer discovery | 01/05 | 01/06 | 01/08 | Engineering background |
| 2 | Mike R. | LinkedIn | Posted about validation | 01/05 | - | - | No response yet |

**Key metrics:**
- Response rate target: 20-30%
- Booking rate target: 10-15%
- Conversations completed: X / 10

---

## Next Steps

Start with `finder/find-communities.prompt.md` and work through the stages.

The goal isn't perfect messages. It's conversations. Every message you don't send is a conversation you don't have.

---

*Part of the Outreach Engine by MYRS.ai*
