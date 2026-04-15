# AI Delegation Plan — Monthly Social Media Report

> **Author:** Ken Tam | Marketing Officer, Sydney  
> **Context:** Documented as part of my Claude Certified Architect – Foundations (CCA-F) learning journey  
> **Framework:** Based on the AI Fluency 4D Framework — Delegation Competency  
> **Last updated:** April 2026

---

## Overview

This document applies the Delegation competency from the AI Fluency Framework to a real, recurring work task: producing a monthly social media performance report for my manager.

**The problem I was solving:** This report previously took several days to complete. The most time-consuming parts were the analysis and improvement recommendations — ironically, the parts AI is best at.

---

## Step 1 — Problem Awareness

**Task:** Monthly social media report  
**Audience:** Direct manager  
**Required components:**
- Numerical performance data (reach, engagement, CTR, follower growth)
- Analysis of trends and patterns
- Recommendations for improvement
- Plan for the following month

**Pain points before AI:**
- Data gathering and formatting: tedious but straightforward
- Analysis: time-consuming, required multiple passes
- Recommendations: hardest part — easy to default to generic advice
- Total time: several days per report

---

## Step 2 — Platform Awareness

Understanding what AI can and cannot do for this task:

| Component | AI Capability | Reason |
|-----------|-------------|--------|
| Export data from platforms | ❌ Cannot | No direct access to IG/FB dashboards without API |
| Format and structure data | ✅ Strong | Given raw numbers, AI organises and presents clearly |
| Identify patterns and trends | ✅ Strong | AI excels at spotting anomalies and comparing periods |
| Write analysis narrative | ✅ Strong | Clear, structured analysis from provided data |
| Generate recommendations | ✅ Strong | Multiple improvement angles for human review |
| Draft next month's plan | ⚠️ Partial | AI provides framework; human adds company-specific context |
| Final review and sign-off | ❌ Human only | Manager expectations and brand direction require human judgment |

### With API Integration (Advanced)

If connected to the Instagram Graph API or Google Analytics API, AI can move from **Augmentation** to **Agency** mode — retrieving data autonomously without manual export. This removes the last major manual step.

---

## Step 3 — Task Delegation Plan

### Without API (Current Setup)

| Task | Owner | How |
|------|-------|-----|
| Export data from platforms | 👤 Me | Manual export from IG/FB/GA dashboards |
| Paste data into AI | 👤 Me | Copy raw numbers into Claude |
| Format into tables | 🤖 AI | Claude structures and formats |
| Identify trends and patterns | 🤝 Together | I provide context; AI analyses |
| Write improvement recommendations | 🤝 Together | AI drafts; I refine based on brand knowledge |
| Draft next month's plan | 🤝 Together | AI provides structure; I add specifics |
| Final review | 👤 Me | Ensure accuracy and alignment with manager expectations |

### With API (Future Setup)

| Task | Owner | How |
|------|-------|-----|
| Data retrieval | 🤖 AI (Agency) | Auto-pull via Instagram Graph API / GA API |
| All analysis and drafting | 🤖 AI | Automated with human review checkpoint |
| Final review and approval | 👤 Me | Human sign-off before submission |

---

## Results

### Time Comparison

| Stage | Before AI | After AI (No API) | After AI (With API) |
|-------|-----------|-------------------|---------------------|
| Data gathering | ~2 hours | ~2 hours | ~0 mins (automated) |
| Formatting | ~1 hour | ~10 mins | ~0 mins |
| Analysis | ~1 day | ~30 mins | ~30 mins |
| Recommendations | ~1 day | ~30 mins | ~30 mins |
| Draft write-up | ~1 day | ~1 hour | ~1 hour |
| Review | ~2 hours | ~1 hour | ~1 hour |
| **Total** | **~3 days** | **~4 hours** | **~2 hours** |

*Note: Time estimates based on personal experience. API integration not yet implemented — marked as future goal.*

---

## Key Learnings

**1. The hardest parts are the best to delegate**  
Analysis and recommendations felt hardest because they required sustained focus. These are exactly what AI handles well — pattern recognition and option generation at speed.

**2. Human value shifts upstream**  
With AI handling drafting and analysis, my value moved to: knowing what questions to ask, providing business context AI doesn't have, and making the final judgment call.

**3. API integration = the next level**  
Moving from Augmentation to Agency mode via API would eliminate the last major manual task (data export). This is the next practical upgrade to explore.

**4. Delegation ≠ abdication**  
I still review every output. AI doesn't know my manager's communication preferences, our brand's current priorities, or what happened this month that might explain a data anomaly. That context is mine to provide.

---

## The Delegation Framework Applied

```
Problem Awareness:   Clear goal → monthly report for manager
                     Clear pain point → analysis takes too long

Platform Awareness:  AI strong at: formatting, analysis, recommendations
                     AI weak at: accessing live data, brand judgment

Task Delegation:     Human owns: data export, context, final review
                     AI owns: formatting, pattern analysis, draft writing
                     Together: recommendations, next month planning
```

---

## Next Steps

- [ ] Test full report workflow with AI assistance
- [ ] Document actual time saved (update estimates above with real data)
- [ ] Explore Instagram Graph API integration for Agency-mode automation
- [ ] Share delegation template with marketing team

---

## Related Portfolio Projects

- [Project 1: Instagram Campaign Performance Analysis](../use-case-1-campaign-analysis.md)
- [Project 2: AI Tools Stack for Marketing](../ai-tools-stack-for-marketing.md)
- [Project 3: AI Capabilities & Limitations — Reality Check](../03-ai-reality-check/README.md)

---

*Part of my [Claude Learning Journey](https://github.com/KenTammm/claude-learning-journey) — documenting my path to CCA-F certification.*
