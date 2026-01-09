# Find Communities Prompt

**Purpose:** Identify relevant online and offline communities where your target customers gather and discuss their problems.

---

## Context to Provide

Before using this prompt, prepare:

1. **Problem description** - What problem are you solving? (1-2 sentences)
2. **Target audience** - Who experiences this problem? Be specific about role, industry, or situation.
3. **Keywords** - 3-5 words or phrases your target customers might use when discussing this problem.

---

## The Prompt

Copy everything below the line and paste into your AI tool:

---

I'm building a product that solves [PROBLEM] for [TARGET AUDIENCE].

Help me find online communities where my target customers gather and discuss problems related to [PROBLEM].

**What I know about my audience:**
- Role/identity: [e.g., "first-time founders," "DevOps engineers," "fitness coaches"]
- Industry/niche: [e.g., "SaaS startups," "e-commerce," "personal training"]
- Keywords they might use: [e.g., "customer discovery," "validation," "churn"]

**For each community, provide:**

1. **Community name and URL** (or how to find it)
2. **Platform type** (subreddit, Discord, Slack, forum, Facebook group, Twitter space, etc.)
3. **Estimated size** (members/subscribers if known)
4. **Activity level** (high/medium/low - based on post frequency)
5. **Relevance score** (1-10, where 10 = highly relevant to my problem)
6. **Why it's relevant** (1 sentence)
7. **Best way to participate** (lurk first, answer questions, introduce yourself, etc.)
8. **Potential risks** (strict self-promotion rules, invite-only, etc.)

**Organize the results into three tiers:**

**Tier 1 - Primary Communities** (relevance 8-10)
These are "must-join" communities where my exact target customer congregates.

**Tier 2 - Secondary Communities** (relevance 5-7)
Related communities where I might find some target customers mixed with broader audience.

**Tier 3 - Niche/Hidden Gems** (variable relevance)
Smaller, harder-to-find communities that could be high-signal despite lower numbers.

**Also suggest:**
- 3-5 Twitter/X accounts to follow (thought leaders my audience follows)
- 2-3 podcasts my target audience listens to
- 2-3 newsletters my target audience reads
- Any offline communities (meetups, conferences, local groups)

---

## Example Output

**Problem:** Founders struggle to validate ideas before building
**Target:** First-time founders building side projects

### Tier 1 - Primary Communities

| Community | Platform | Size | Activity | Relevance | Why |
|-----------|----------|------|----------|-----------|-----|
| r/startups | Reddit | 1.2M | High | 9/10 | Direct discussions about validation, customer discovery |
| r/Entrepreneur | Reddit | 2M | High | 8/10 | Broad but frequent validation questions |
| Indie Hackers | Forum | 100K+ | High | 10/10 | Exact target audience, validation is core topic |
| r/SideProject | Reddit | 150K | Medium | 8/10 | Side project builders seeking feedback |

**Best approach for Indie Hackers:** Answer questions in the forum for 2 weeks before posting anything about your own project. Build reputation first.

### Tier 2 - Secondary Communities

| Community | Platform | Size | Activity | Relevance | Why |
|-----------|----------|------|----------|-----------|-----|
| Startup School forum | YC | 50K+ | Medium | 7/10 | More advanced founders, but validation discussions |
| r/SaaS | Reddit | 80K | Medium | 6/10 | Overlaps with SaaS builders specifically |
| Hacker News | Forum | Large | High | 6/10 | Show HN posts get feedback, but harsh crowd |

### Tier 3 - Hidden Gems

| Community | Platform | Size | Activity | Relevance | Why |
|-----------|----------|------|----------|-----------|-----|
| Lenny's Newsletter Slack | Slack (paid) | 10K | High | 7/10 | Premium product/growth community |
| WIP.co | Forum | 5K | Medium | 9/10 | Makers building in public, very supportive |
| Pioneer.app | Community | Small | Medium | 8/10 | Founders in early validation stage |

### Thought Leaders to Follow
- @Julian (Julian Shapiro) - Startup growth
- @paborenstein - Indie hacker building in public
- @mijustin - MicroConf community, bootstrapping

### Podcasts
- Indie Hackers Podcast
- My First Million
- The Bootstrapped Founder

### Newsletters
- Lenny's Newsletter
- The Bootstrapped Founder
- Product Hunt Daily

---

## Tips for Best Results

1. **Be specific about your audience** - "Founders" is too broad. "First-time founders with day jobs building B2B SaaS side projects" is better.

2. **Add industry context** - If your solution is industry-specific, mention it. Communities vary wildly by vertical.

3. **Ask for lurker tips** - After getting the list, ask: "What should I look for when lurking in [community name]? What posts or comments indicate someone who has my problem?"

4. **Validate the results** - AI can hallucinate communities. Verify each one exists before investing time.

5. **Update monthly** - Communities change. New ones emerge. Run this prompt again periodically.

---

## Follow-Up Prompts

After finding communities, use these prompts to dig deeper:

**"What specific search queries should I use in [community name] to find people discussing [problem]?"**

**"What are the unwritten rules of [community name] that I should know before participating?"**

**"Based on this community list, which 3 should I prioritize and why?"**

---

*Next step: Use `identify-signals.prompt.md` to learn what buying signals look like in these communities.*
