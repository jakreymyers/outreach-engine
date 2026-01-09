---
name: outreach-engine
description:
  Structured outreach system for founders validating ideas or acquiring customers.
  Use when identifying targets, crafting messages, guiding conversations, or
  synthesizing insights from customer interactions. Ensures systematic approach
  to customer development while maintaining authenticity.
purpose: Execute the outreach workflow from target identification to insight synthesis
tools:
  - Read
  - Write
  - Edit
  - Glob
  - Grep
  - WebSearch
model: inherit
---

# Outreach Engine Skill

## Overview

The Outreach Engine skill provides a structured system for customer outreach—whether validating an idea pre-product or acquiring customers post-launch. It transforms the chaotic process of "talking to customers" into a repeatable workflow that yields actionable insights.

### Why This Skill Exists

Most founders know they should talk to customers. Few do it well. Common failure modes:

- **Spray and pray** - Mass outreach with no targeting, low response rates
- **Pitch disguised as question** - "Can I get feedback on my amazing idea?"
- **Leading questions** - "Don't you hate it when X happens?"
- **No synthesis** - Conversations happen but insights don't compound
- **Analysis paralysis** - Endless research, never reaching out

This skill solves these problems with **four interconnected workflows** that guide you from target identification through insight synthesis.

### Core Principles

1. **AI augments, humans have conversations** - AI helps you find, prepare, and synthesize; you have the actual conversations
2. **Quality over quantity** - 10 genuine conversations > 1000 automated touches
3. **Seek disconfirmation** - The goal is truth, not validation of what you want to hear
4. **Respect people's time** - Be brief, specific, and genuinely curious
5. **Capture everything** - Real signal lives in exact words, not summaries
6. **Iterate fast** - Each conversation should improve the next one

### Capabilities

- Identify where target customers gather online and offline
- Generate qualified target lists with personalization context
- Craft opening messages using proven frameworks
- Guide conversations to extract real signal
- Synthesize insights across multiple conversations
- Generate proceed/pivot/kill recommendations

---

## Critical Knowledge Files

**ALWAYS load these files before ANY outreach operation:**

| File | Purpose | Load When |
|------|---------|-----------|
| `knowledge/outreach-principles.md` | **REQUIRED** - Philosophy and anti-patterns | EVERY operation |
| `knowledge/validation-vs-acquisition.md` | Stage-specific guidance | When determining approach |
| `knowledge/channel-guide.md` | Where to find targets by platform | Finding targets |
| `knowledge/message-frameworks.md` | The three message templates | Crafting openers |

---

## Workflows

This skill has four workflows. Load the appropriate workflow based on intent.

### workflow/find-targets.md

**Purpose:** Identify where target customers gather and who to reach out to.

**Load when:**
- Starting a new validation effort
- Need to expand target list
- Current targets not responding
- Pivoting to new customer segment

**Triggers (examples):**
- "Help me find people to talk to"
- "Where do my target customers hang out?"
- "I need to validate this idea"
- "Build me a target list"

**Required dependencies - load BEFORE executing:**
- `knowledge/outreach-principles.md` - For targeting philosophy
- `knowledge/channel-guide.md` - For platform-specific tactics
- `knowledge/validation-vs-acquisition.md` - For stage-appropriate targeting

---

### workflow/craft-opener.md

**Purpose:** Create the first message that gets a response.

**Load when:**
- Have targets, need to write messages
- Current messages not getting responses
- Want to test different approaches
- Moving to a new platform/channel

**Triggers (examples):**
- "Help me write an outreach message"
- "My messages aren't getting responses"
- "How should I approach this person?"
- "Draft an opener for..."

**Required dependencies - load BEFORE executing:**
- `knowledge/outreach-principles.md` - For messaging philosophy
- `knowledge/message-frameworks.md` - For the three templates
- `knowledge/validation-vs-acquisition.md` - For stage-appropriate tone

---

### workflow/conversation-guide.md

**Purpose:** Navigate conversations to extract real signal.

**Load when:**
- Preparing for an upcoming conversation
- Need interview questions for specific context
- Want to improve conversation quality
- Processing conversation notes

**Triggers (examples):**
- "I have a call tomorrow, help me prepare"
- "What questions should I ask?"
- "Give me an interview script"
- "How do I dig deeper on..."

**Required dependencies - load BEFORE executing:**
- `knowledge/outreach-principles.md` - For conversation philosophy
- `knowledge/validation-vs-acquisition.md` - For stage-specific questions

---

### workflow/synthesize-insights.md

**Purpose:** Turn conversations into actionable insights.

**Load when:**
- Completed 3+ conversations
- Need to decide proceed/pivot/kill
- Presenting findings to stakeholders
- Planning next iteration

**Triggers (examples):**
- "Help me make sense of these conversations"
- "What are the patterns in my feedback?"
- "Should I keep building this?"
- "Synthesize my customer research"

**Required dependencies - load BEFORE executing:**
- `knowledge/outreach-principles.md` - For synthesis philosophy
- `knowledge/validation-vs-acquisition.md` - For stage-specific signals

---

## Knowledge

### knowledge/outreach-principles.md

**Purpose:** The philosophy underlying effective outreach. Why it matters, AI's role, common mistakes, and quality standards.

**CRITICAL:** This file is the foundation. Load it before ANY workflow execution.

**Contains:**
- Why outreach matters
- AI's proper role (augment, not replace)
- Common mistakes and anti-patterns
- Quality over quantity mindset
- The seek-disconfirmation principle

---

### knowledge/validation-vs-acquisition.md

**Purpose:** Stage-specific guidance for pre-product validation vs. post-product customer acquisition.

**Load when:** Determining approach for current stage

**Contains:**
- Pre-product: What to ask, what not to ask
- Post-product: How discovery differs from validation
- Red flags for each stage
- When to switch stages

---

### knowledge/channel-guide.md

**Purpose:** Where to find people by channel—platform-specific tactics.

**Load when:** Executing the find-targets workflow

**Contains:**
- Reddit: Finding subreddits, identifying good targets
- LinkedIn: Search strategies, InMail vs. connection
- Twitter/X: Finding conversations, engagement approaches
- Slack/Discord: Community discovery
- Forums/Communities: Niche sources

---

### knowledge/message-frameworks.md

**Purpose:** The three message frameworks with variations for each platform.

**Load when:** Executing the craft-opener workflow

**Contains:**
1. The Curious Builder
2. The Researcher
3. The Value-First
- Platform-specific variations (LinkedIn, Twitter, email, community)

---

## Tools

| Tool | Purpose | When Used |
|------|---------|-----------|
| `Read` | Load knowledge and context files | All workflows |
| `Write` | Create target lists, conversation notes | Find targets, synthesize |
| `Edit` | Update existing documents | Iteration, refinement |
| `Glob` | Discover related files | Context gathering |
| `Grep` | Search across notes/transcripts | Pattern finding |
| `WebSearch` | Find communities, research targets | Find targets workflow |

---

## Execution Rules

**These rules are mandatory. Deviations will compromise outreach quality.**

### Before ANY Outreach Operation

1. **Load `knowledge/outreach-principles.md` FIRST** - You must internalize the philosophy
2. **Determine stage** - Validation or acquisition? Load appropriate knowledge
3. **Load required workflow** - Don't improvise; follow the documented process
4. **Load all workflow dependencies** - As listed in the workflow section above

### During Execution

1. **Follow the workflow steps in order** - No skipping, no optimization
2. **AI prepares, human executes** - Never suggest AI should have the conversation
3. **Prioritize quality** - Better to reach 5 right people than 50 wrong ones
4. **Capture verbatim quotes** - Exact words matter more than summaries
5. **Surface disconfirming evidence** - Actively seek reasons the idea might fail
6. **Document everything** - Future synthesis depends on current capture

### Message Quality Standards

1. **Short** - Under 100 words for cold outreach
2. **Specific** - Reference something specific about the person
3. **Curious** - Ask, don't pitch
4. **Low-commitment** - Easy to say yes to
5. **Human** - Would a real person write this?

### Conversation Quality Standards

1. **Listen more than talk** - Target ratio: 80% them, 20% you
2. **Follow the energy** - When they light up, dig deeper
3. **Ask "why" repeatedly** - Surface the real motivation
4. **Capture exact words** - Write down their specific language
5. **End with next steps** - Who else to talk to? Can you follow up?

### If Uncertain

- Re-read the relevant workflow and knowledge files
- Check `outreach-principles.md` for guidance
- Ask the user for clarification
- Do NOT improvise messaging or targeting

---

## Integration with Primary Agent

This skill should be invoked proactively during conversations:

| Situation | Action |
|-----------|--------|
| User mentions idea validation | Offer to run find-targets workflow |
| User has conversations scheduled | Offer to run conversation-guide workflow |
| User shares conversation notes | Offer to run synthesize-insights workflow |
| User's outreach isn't working | Diagnose with outreach-principles, suggest craft-opener |
| User seems stuck | Check if they need more targets or different approach |

**The goal is systematic progress from idea to validated insight.**

---

## Anti-Patterns

| Wrong | Right |
|-------|-------|
| Mass automated outreach | Targeted, personalized messages |
| "Can I pick your brain?" | Specific ask with clear value exchange |
| Leading questions | Open questions seeking truth |
| Pitching during validation | Learning during validation |
| Summarizing conversations | Capturing exact quotes |
| Waiting for perfect target list | Starting with good-enough list, iterating |
| One-channel approach | Multi-channel based on where targets are |
| Treating all conversations same | Stage-appropriate (validation vs. acquisition) |

---

## Failure Modes

If these occur, stop and correct:

1. **No responses** - Review message quality against frameworks; check if targeting right people
2. **Polite but useless conversations** - Review conversation guide; probably asking wrong questions
3. **Confirmation bias** - Review disconfirmation principle; actively seek reasons to fail
4. **Analysis paralysis** - Set conversation target (usually 10-20); make decision after
5. **Insights not compounding** - Run synthesize workflow; look for patterns
6. **AI having conversations** - STOP; AI prepares, humans execute

**FAILURE TO FOLLOW THESE RULES WILL YIELD FALSE VALIDATION.**

---

## Output Artifacts

The Outreach Engine produces these artifacts:

| Artifact | Created By | Purpose |
|----------|------------|---------|
| Target List | find-targets | Prioritized list with personalization context |
| Message Variations | craft-opener | 2-3 variations per target or template |
| Interview Script | conversation-guide | Questions with follow-ups and red flags |
| Conversation Notes | User (template provided) | Raw capture from each conversation |
| Insight Synthesis | synthesize-insights | Patterns, signals, recommendation |

Store artifacts in a consistent location (e.g., `outreach/` folder) for future reference.
