---
layout: page
title: "Examen Template"
permalink: /angelic-alignment/practices/examen-template/
description: "Structured logging template for daily Examen practice with metadata tracking, Rule of Fruit scoring, and SSNS planning."
---

# Examen Template

## Purpose

An Obsidian-ready template for logging your daily Evening Examen practice. Logging is **optional**—the practice itself is complete without documentation. Use this template only if tracking helps your consistency or provides useful pattern recognition over time.

---

## Template (Copy/Paste)

```markdown
---
type: examen
version: v0.1
date: {{date:YYYY-MM-DD}}
time: {{time:HH:mm}}
fruit_score: 
tripwire: 
ssns_done: 
stop_condition_met: 
tags: [AngelicAlignment, Examen]
---

# Examen — {{date:YYYY-MM-DD}}

## Gratitude (30–60s)
- 

## Aligned moment (60–90s)
- 

## Drift moment (60–90s)
- 

## Motive (name it plainly)
- (fear / pride / avoidance / fatigue / resentment / confusion / other):  
- 

## Repair / amendment (small + respectful)
- 

## Tomorrow's SSNS (2–10 minutes)
- 

## Stop condition (what "done" means)
- 

## Anti-vanity clause
If nobody praises this, it still counts.

## Notes (optional)
- 

## Rule of Fruit (optional quick score)
Rate 0–2 each (total /12): Truth __ Humility __ Compassion __ Steadiness __ Responsibility __ Harmlessness __
Total: __/12
```

---

## Field Explanations

### Metadata Fields

**type:** Always `examen` for this practice  
**version:** Current template version (v0.1)  
**date/time:** Auto-populated if using Obsidian templates  
**fruit_score:** Optional total from Rule of Fruit scoring (0-12)  
**tripwire:** Note any drift signals detected (urgency, mission inflation, etc.)  
**ssns_done:** Yes/No - did you complete the SSNS you planned?  
**stop_condition_met:** Yes/No - did you stop when you said you would?  
**tags:** For filtering and searching logs

### Core Fields

**Gratitude:** One concrete, ordinary thing from today  
**Aligned moment:** Where you acted according to your values  
**Drift moment:** Where you departed from values (behavioral, not identity)  
**Motive:** The feeling/need underneath the drift  
**Repair:** One small, respectful action to make it right  
**Tomorrow's SSNS:** The smallest safe next step (2-10 minutes)  
**Stop condition:** How you'll know you're done with the SSNS  
**Anti-vanity clause:** Reminder that completion matters, not praise

### Optional Fields

**Notes:** Any additional observations or context  
**Rule of Fruit:** Quick scoring on six virtues (0-2 each, max 12)
- Truth: Did I name reality plainly today?
- Humility: Did I resist superiority narratives?
- Compassion: Did I care for others with appropriate boundaries?
- Steadiness: Did I stay consistent and reliable?
- Responsibility: Did I do what I said I would?
- Harmlessness: Did I avoid exploitation and manipulation?

---

## When to Use This Template

**Use logging when:**
- You want to track patterns over weeks/months
- Accountability helps your consistency
- You're testing whether a practice works for you
- Your therapist requests documentation

**Skip logging when:**
- It feels like a burden rather than support
- You're in an unstable period (logging can increase rumination)
- The practice itself is more important than the record
- Perfectionism starts creeping in ("I must log perfectly")

**Remember:** The practice matters, not the log. If logging becomes an obstacle, drop it.

---

## Pattern Recognition Over Time

After 2-4 weeks of logging, review your entries for:

**Drift patterns:**
- Do certain situations trigger drift consistently?
- Are specific motives (fear, fatigue, etc.) recurring?
- Do you tend to skip certain repair actions?

**Alignment patterns:**
- Which virtues do you practice most naturally?
- Which need more attention?
- Are your SSNS realistic or too ambitious?

**Fruit scoring trends:**
- Which areas show improvement over time?
- Which remain stuck?
- Does any area consistently score 0?

**Adjustments based on patterns:**
- If fatigue drives most drift → focus on rest/boundaries
- If certain repairs never happen → make them smaller
- If SSNS consistently undone → reduce scope further
- If fruit scores flatline → check if goals are realistic

---

## Integration with Other Practices

This template works alongside:

- [Evening Examen](/angelic-alignment/practices/evening-examen/) — The practice being logged
- [SSNS Playbook](/angelic-alignment/practices/ssns-playbook/) — Reference for planning tomorrow's step
- [Attunement Test](/angelic-alignment/practices/attunement-test/) — Weekly or pre-decision assessment

**Suggested workflow:**
1. Do Evening Examen (5 minutes, no logging)
2. If helpful, copy template and fill it out (2-3 minutes)
3. File in your practice log folder
4. Weekly: Review logs briefly (5 minutes)
5. Monthly: Look for patterns (10-15 minutes)

---

## Obsidian Setup (Optional)

If using Obsidian:

1. Create template file in your templates folder
2. Set up keyboard shortcut for inserting template
3. Create a `Practices/Examen` folder for logs
4. Use Dataview plugin to track patterns (optional)

**Example Dataview query for completion rate:**
```
TABLE ssns_done, fruit_score
FROM "Practices/Examen"
WHERE type = "examen"
SORT date DESC
LIMIT 30
```

---

**Version:** 0.1  
**Created:** January 2025  
**Status:** Active template

---

[← Back to Practices](/angelic-alignment/practices/)
