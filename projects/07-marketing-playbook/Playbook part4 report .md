# AI-Assisted Marketing Playbook
## Part 4: Monthly Report Production Workflow

> **Company:** Luxury Glamping Tent Solutions Provider  
> **Author:** Ken Tam | Marketing Officer, Sydney  
> **Last updated:** April 2026

---

## Overview

This workflow covers how to use AI to produce our monthly marketing report efficiently. The report covers social media performance, website traffic, and sales leads — and is presented to the direct manager.

**Time saved:** Previously took several days. With this workflow: approximately 3–4 hours.

**Tools we use:**
- Instagram Insights
- Google Analytics
- Semrush
- Meta Business Manager
- Google Tag Manager
- Manual export where needed

---

## What the Report Covers

| Section | Data Source | What manager wants to see |
|---------|------------|--------------------------|
| Social media reach | Instagram Insights / Meta Business Manager | Numbers + trend vs last month |
| Engagement rate | Instagram Insights | Numbers + what drove high/low engagement |
| Follower growth | Instagram Insights | Net growth + quality of new followers |
| Website traffic | Google Analytics / Google Tag Manager | Volume + top sources + behaviour |
| Leads generated | Semrush / CRM / manual | Number of leads + quality assessment |
| Sales connection | CRM / sales team input | Did marketing activity drive sales conversations? |

---

## Step-by-Step Workflow

---

### STEP 1: Data Collection (You — 45–60 mins)

AI cannot access your platforms directly. This step is yours.

**Checklist:**
- [ ] Export Instagram Insights — reach, impressions, engagement rate, follower growth
- [ ] Export Meta Business Manager — paid reach, ad performance (if running ads)
- [ ] Pull Google Analytics — sessions, users, top pages, traffic sources, avg session duration
- [ ] Pull Google Tag Manager — conversion events, form submissions, key goal completions
- [ ] Pull Semrush — organic traffic, keyword rankings, any notable changes
- [ ] Note leads from CRM or manually — number of enquiries, source, quality
- [ ] Ask Sales team — did any leads from marketing convert or progress this month?

**Time-saving tip:** Create a simple spreadsheet template with all these fields. Each month, just fill in the numbers. This becomes your "data paste" for AI in Step 2.

---

### STEP 2: Paste Data into AI + Generate Analysis (AI — 20–30 mins)

Once you have all your numbers, paste them into Claude using this prompt:

**AI Prompt — Monthly Analysis:**
> I need to produce a monthly marketing report for my manager. Here is this month's data:
>
> **Social Media:**
> - Instagram Reach: [number] (vs last month: [number])
> - Engagement Rate: [%] (vs last month: [%])
> - Follower Growth: +[number] (total now: [number])
>
> **Website:**
> - Sessions: [number] (vs last month: [number])
> - Top traffic source: [source]
> - Leads/form submissions: [number]
>
> **Sales:**
> - New leads generated: [number]
> - Leads that progressed to sales conversation: [number]
>
> **Context:**
> - This month we ran: [any campaigns, posts, events, promotions]
> - Industry/seasonal context: [anything relevant — e.g. "slow season", "just after a trade show"]
>
> Please:
> 1. Identify the 3 most significant trends or patterns in this data
> 2. Explain likely reasons for any notable increases or decreases
> 3. Flag anything that needs attention or further investigation
> 4. Keep analysis concise — my manager wants insight, not just a summary of the numbers

---

### STEP 3: Generate Recommendations (AI + You — 15–20 mins)

After reviewing the analysis, use this prompt to generate next month's recommendations:

**AI Prompt — Recommendations:**
> Based on the analysis above, suggest 3–5 specific, actionable recommendations for next month's marketing activity.
>
> Context about our business:
> - We sell luxury glamping tent solutions to B2B clients (resort owners, farm owners, developers)
> - Our main channels are Instagram, LinkedIn, and direct outreach
> - Our sales cycle is [length — e.g. several weeks to months]
> - We are a small marketing team (2 people)
>
> Format: Each recommendation should include:
> - What to do (specific action)
> - Why (based on this month's data)
> - How to measure success next month
>
> Be realistic — we have limited time and budget. Prioritise highest impact actions.

---

### STEP 4: Draft the Report (AI — 15 mins)

Once analysis and recommendations are ready, generate the full report:

**AI Prompt — Full Report Draft:**
> Using the data, analysis, and recommendations above, write a monthly marketing report for my manager.
>
> Format:
> - Executive Summary (3–4 sentences — the most important things to know)
> - Performance Snapshot (key numbers in a simple table)
> - Analysis (what the numbers mean — 3 key insights)
> - Sales Connection (did marketing contribute to leads or sales this month?)
> - Recommendations (3–5 actions for next month)
>
> Tone: Professional, direct, concise. My manager wants to understand performance quickly — no fluff.
> Length: No more than 1–2 pages when formatted.

---

### STEP 5: Your Review + Final Edits (You — 30–45 mins)

This step cannot be delegated. You must:

**Check for accuracy:**
- [ ] Are all numbers correct? (AI sometimes misreads or miscalculates — verify against raw data)
- [ ] Are the trends actually meaningful, or is AI over-interpreting small changes?
- [ ] Are the recommendations realistic for our team size and budget?

**Add what AI doesn't know:**
- [ ] Any internal context — team changes, budget shifts, product launches
- [ ] Sales team input — any leads that closed or fell through
- [ ] Your own judgment — is the tone right for how your manager prefers to receive information?

**Final check:**
- [ ] Would you be comfortable presenting this in a meeting right now?
- [ ] Is there anything your manager will ask that isn't answered in the report?

---

## Monthly Report Template (Copy-Paste Ready)

Use this as your starting structure each month:

```
MONTHLY MARKETING REPORT
[Month] [Year]
Prepared by: Ken Tam

─────────────────────────────
EXECUTIVE SUMMARY
[3–4 sentences: overall performance, biggest win, biggest concern, 
and most important action for next month]

─────────────────────────────
PERFORMANCE SNAPSHOT

| Metric | This Month | Last Month | Change |
|--------|-----------|------------|--------|
| Instagram Reach | | | |
| Engagement Rate | | | |
| Follower Growth | | | |
| Website Sessions | | | |
| Leads Generated | | | |
| Sales Conversations | | | |

─────────────────────────────
KEY INSIGHTS
1. [Most important trend or finding]
2. [Second most important]
3. [Third — often an area needing attention]

─────────────────────────────
SALES CONNECTION
[Did marketing activity contribute to leads or sales this month? 
Be specific — which channels or content drove enquiries?]

─────────────────────────────
RECOMMENDATIONS FOR NEXT MONTH
1. [Action] — [Why] — [How to measure]
2. [Action] — [Why] — [How to measure]
3. [Action] — [Why] — [How to measure]
```

---

## Discernment Checklist for Reports

Before sending to your manager:

- [ ] Are all numbers verified against raw source data?
- [ ] Does the analysis explain *why*, not just *what*?
- [ ] Are recommendations specific and actionable — not vague?
- [ ] Is the sales connection section filled in with real input from the sales team?
- [ ] Is the tone and length right for how your manager prefers to receive information?
- [ ] Would you be confident presenting this verbally if asked?

---

## Future Upgrade: API Integration

Currently, data collection (Step 1) is manual. Future option:

| Tool | API Available | What it would automate |
|------|-------------|----------------------|
| Instagram Graph API | ✅ Yes | Auto-pull reach, engagement, follower data |
| Google Analytics API | ✅ Yes | Auto-pull sessions, traffic sources, conversions |
| Meta Marketing API | ✅ Yes | Auto-pull ad performance data |

With API integration, Steps 1 and 2 could be fully automated — reducing report time from 3–4 hours to under 1 hour.

---

*Part of the AI-Assisted Marketing Playbook — [Claude Learning Journey](https://github.com/KenTammm/claude-learning-journey)*
