# AI Capabilities & Limitations — A Marketing Officer's Reality Check

> **Author:** Ken Tam | Marketing Officer, Sydney  
> **Context:** Documented as part of my Claude Certified Architect – Foundations (CCA-F) learning journey  
> **Framework:** Based on the AI Fluency 4D Framework (Anthropic, Dakan & Feller, 2025)  
> **Last updated:** April 2026

🌐 **[View Interactive Version →](https://kentammm.github.io/claude-learning-journey/projects/03-ai-reality-check/ai-reality-check.html)**

---

## Overview

This document records my honest, first-hand experience using AI tools in day-to-day marketing work. It is not a theoretical review — every example reflects something I actually tried, observed, and learned from.

The goal is simple: **know what AI is genuinely good at, know where it falls short, and know how to respond when it does.**

---

## ✅ Where AI Genuinely Helped Me

### 1. Writing Copy & Captions

**What I did:** Used AI to generate first drafts of Instagram captions, email subject lines, and product descriptions at scale.

**What worked:**
- Generated 10–20 variations in seconds, giving me real options to choose from
- Strong at matching tone when given clear examples (few-shot prompting)
- Significantly reduced time spent on first drafts — I focused my energy on editing and judgment instead

**The lesson:** AI is a prolific first-drafter. My job shifted from *writing* to *editing and deciding* — which is actually higher-value work.

---

### 2. Analysing Data & Finding Patterns

**What I did:** Pasted campaign performance data (engagement rates, reach, CTR) and asked AI to identify trends and anomalies.

**What worked:**
- Quickly spotted patterns I might have missed or taken much longer to find
- Generated hypotheses for why certain posts outperformed others
- Produced structured summaries I could share with stakeholders directly

**The lesson:** AI excels at processing structured data and surfacing patterns. It dramatically speeds up the "so what?" stage of analysis.

---

### 3. Brainstorming Creative Ideas

**What I did:** Used AI as a thinking partner for campaign concepts, content pillars, and audience messaging angles.

**What worked:**
- Generated a wide range of directions quickly — even bad ideas helped clarify what I actually wanted
- Useful for breaking creative blocks and challenging my assumptions
- Best in Augmentation mode: back-and-forth dialogue rather than one-shot requests

**The lesson:** AI is a great brainstorming *sparring partner*, not a creative director. The best ideas came from human-AI iteration, not AI alone.

---

## ⚠️ Where AI Disappointed Me (And What I Learned)

### Limitation 1: Hallucination — Confident But Wrong

**What happened:** AI cited specific engagement statistics for a competitor brand. The numbers sounded credible and were formatted professionally. They were fabricated.

**Why it happens:** LLMs generate plausible-sounding text based on patterns — they don't actually "look things up." When specific facts aren't in their training data, they fill in the gap convincingly.

**My fix:**
- Treat all AI-generated statistics, dates, and proper nouns as *unverified until confirmed*
- Use AI for structure and framing; source all specific facts independently (Semrush, Google Analytics, brand websites)
- Ask AI to flag when it is uncertain: *"If you're not sure about a specific number, say so"*

---

### Limitation 2: No Brand Voice Without Clear Direction

**What happened:** Asked AI to write captions "in our brand voice." The output was polished but generic — it could have been for any brand in our category.

**Why it happens:** AI has no knowledge of your brand unless you tell it. It defaults to averaged, category-appropriate language — competent but forgettable.

**My fix:**
- Always include 3–5 examples of on-brand copy in the prompt (few-shot learning)
- Define tone explicitly: *"Direct, slightly witty, never corporate, uses second person"*
- Create a reusable brand voice prompt block I paste into every copy request

---

### Limitation 3: Generic Output With No Personality

**What happened:** Campaigns brainstormed by AI felt safe and predictable. They hit all the right marketing checkboxes but lacked the unexpected angle that makes campaigns memorable.

**Why it happens:** AI is trained on vast amounts of existing content — it is very good at producing *average-of-what-exists*, not *genuinely original*.

**My fix:**
- Use AI to generate 10 conventional ideas, then explicitly ask: *"Now give me 5 ideas that break these conventions"*
- Bring the unexpected angle myself; use AI to develop and execute it
- Treat AI brainstorm output as a starting constraint to push against, not a final answer

---

### Limitation 4: Knowledge Cutoff — AI Doesn't Know "Now"

**What happened:** Asked AI to analyse a competitor's recent social media strategy. It gave a confident, structured answer based on what the brand was doing 12–18 months ago — completely missing recent changes.

**Why it happens:** LLMs have a training cutoff date. They genuinely do not know what happened after that point, but they don't always volunteer this caveat.

**My fix:**
- For anything time-sensitive (competitor moves, platform algorithm changes, industry news), use real-time tools: Semrush, Sprout Social, Google Trends, LinkedIn
- Ask AI to state its knowledge cutoff when answering market-related questions
- Use AI for frameworks and historical context; use live tools for current data

---

## 🧠 The Mental Model I Now Use

Before any AI task, I ask myself two questions:

```
1. Does this task require current, verified, or proprietary information?
   → If YES: I provide that information, or verify AI output against real sources

2. Does this task require my brand's specific voice, culture, or relationships?
   → If YES: I give AI explicit examples and context before asking it to write
```

If both answers are NO — I delegate freely and focus my energy on reviewing the output.

---

## 📊 Summary Table

| Task | AI Value | Key Risk | My Mitigation |
|------|----------|----------|---------------|
| Writing captions / copy | ⭐⭐⭐⭐⭐ | Generic voice | Provide brand examples + tone guide |
| Campaign data analysis | ⭐⭐⭐⭐ | Fabricated stats | Verify all numbers independently |
| Creative brainstorming | ⭐⭐⭐⭐ | Safe, predictable ideas | Push for unconventional after conventional |
| Competitor research | ⭐⭐⭐ | Outdated information | Supplement with live tools |
| Strategy decisions | ⭐⭐ | No business context | Human-led, AI-assisted only |
| Client relationship comms | ⭐ | No relationship awareness | Human only |

---

## 🔗 Related Portfolio Projects

- [Project 1: Instagram Campaign Performance Analysis](../instagram-campaign-analysis/)
- [Project 2: AI Tools Stack for Marketing](../ai-tools-stack/)

---

## 📚 References

- Dakan, R. & Feller, J. (2025). *The AI Fluency Framework*. Anthropic.
- Anthropic (2025). *AI Fluency: Framework and Foundations* [Online Course].

---

*Part of my [Claude Learning Journey](https://github.com/KenTammm/claude-learning-journey) — documenting my path to CCA-F certification.*
---

*Part of my [Claude Learning Journey](https://github.com/KenTammm/claude-learning-journey) — documenting my path to CCA-F certification.*
