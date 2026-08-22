---
name: ascension-quest-master
description: Transform overwhelming personal, academic, or spiritual goals into a structured, gamified 90-day questline with daily actionable missions, RPG-style XP and stat tracking, and built-in rest days and reflection prompts. Use when users say "new goal", "build a habit", "questline", "90-day plan", or express a large intimidating life goal they want to tackle without burnout.
---

# Ascension Quest Master

Turns a massive, intimidating life goal into a 90-day RPG-style "questline" you can actually win. Instead of staring at an overwhelming mountain, you get a structured campaign: daily actionable missions, stat boosts (Intellect, Spirit, Discipline, etc.), XP toward level-ups, and scheduled rest days with reflection prompts to prevent burnout.

## When To Use

Activate when the user:

- Says **"new goal"**, **"build a habit"**, **"questline"**, **"90-day plan"**, or similar
- Describes a large goal (final-year uni project, coding skill-up, spiritual growth / "the Word", fitness, career push) that feels overwhelming
- Wants structure, momentum, and accountability over a defined period

## Philosophy (The "Win Without Burning Out" Rules)

1. **Small daily missions beat one giant goal.** Each day is a concrete, completable action.
2. **Rest is part of the game.** Scheduled rest days are mandatory — they're how you avoid burnout and keep momentum.
3. **Stats make progress visible.** Every mission feeds a stat; watching stats grow is the motivation loop.
4. **Reflection is a mission, not a break.** Periodic reflection prompts deepen the work (spiritual, mental, emotional).
5. **The quest adapts.** If the user misses days, recalibrate the timeline rather than guilt-trip.

## Workflow

Follow this order when a user opens a quest.

### Step 1 — Capture the Goal

Ask or extract:

| Field | Example |
|-------|---------|
| **Goal (macro)** | "Ship my final-year project" |
| **Domain(s)** | Academic, Spiritual, Coding, Fitness, Career |
| **End state** | "Working prototype + written report by deadline" |
| **Stakes / why** | "Graduation, portfolio, honoring my time" |
| **Deadline (fixed or flexible)** | "90 days", "before finals", "no deadline" |
| **Current level** | "0 XP" — where they are now |
| **Constraints** | Hours per day, available days, recurring conflicts |

### Step 2 — Build the 90-Day Questline

Structure the campaign in **three phases of ~30 days**:

| Phase | Days | Theme | Focus |
|-------|------|-------|-------|
| **Act I — Foundation** | 1–30 | Build the base | Setup, learning core concepts, first wins |
| **Act II — Momentum** | 31–60 | Deep work | Hardest core work, volume, skill compounding |
| **Act III — Mastery & Delivery** | 61–90 | Finish strong | Polish, integration, final output, reflect |

Within each phase, lay out a **weekly rhythm**:

| Day | Weight | Typical Mission |
|-----|--------|-----------------|
| Mon–Thu | Work | 2–4 targeted missions across stats |
| Fri | Work | Bigger "boss" milestone task |
| Sat | **Rest** | No missions — active recovery, light reflection |
| Sun | Reflection | Journaling prompt, review the week, plan next |

### Step 3 — Assign Stats & XP

Define the user's **stat categories** (pick relevant ones, 2–4 is enough):

- **Intellect** — learning, problem-solving, studying, coding
- **Discipline** — consistency, habits, showing up
- **Spirit** — scripture, prayer, meditation, inner growth
- **Body** — fitness, energy, health
- **Craft** — the actual skill/output of their goal

**XP rules:**

- Small daily task: `+5 XP`
- Medium task: `+10 XP`
- Weekly "boss" milestone: `+25 XP`
- Rest day completed mindfully: `+2 XP` (still counts, for showing up to rest)
- Reflection entry: `+5 XP`
- **XP curve:** levels every 100 XP. `100 XP → Level 1 ... 400 XP → Level 4`

Assign every mission to at least one stat and record expected XP.

### Step 4 — Generate Daily Missions

For each day produce:

```text
Day N — <Phase> / <Theme>
Mission:  <one concrete, completable action>
Stat:     <Intellect | Discipline | Spirit | Body | Craft>
XP:       +N
Reward:   <small tangible treat or note>
```

Missions must be **small enough to finish in 20–45 minutes** on a workday. If a mission can't fit, split it.

### Step 5 — Build In Rest & Reflection

- **Rest days** (weekly Saturday, or after heavy boss days): explicitly no grind — walk, nap, social time, light scripture/meditation only.
- **Reflection prompts** (Sunday weekly, plus Days 30 & 60 "phase review", plus Day 90 "final journal"):

  - *What stat grew this week, and what specifically caused it?*
  - *Where did I almost stall, and what got me through?*
  - *What is one thing I need to change for next week to keep this sustainable?*
  - *(Spiritual)* *Where did I see the Word or prayer shape my work this week?*

### Step 6 — Track & Recalibrate

- Maintain a running **XP ledger** and **stat totals** from the previous day's input.
- **Level-ups**: at each new level, grant a simple achievement line (e.g., "Level 2 — Momentum Citizen").
- **Missed days**: never shame. Adjust the remaining timeline, fold the missed mission into a lighter slot, and keep the streak-alternative (total cumulative XP) moving.
- After each 30-day phase, present a **phase review** before drafting the next act.

## Output Format

When delivering a plan, structure it as:

```markdown
## ⚔️ <Goal> — 90-Day Questline

**Character:** <current level + relevant stats>

### Act I — Foundation (Days 1–30)
| Day | Type | Mission | Stat | XP |
|-----|------|---------|------|----|
| 1   | Work | ...     | Intellect | +5 |
...
### Act II — Momentum (Days 31–60)
...
### Act III — Mastery & Delivery (Days 61–90)
...

### Weekly Rhythm
- Mon–Thu: work missions
- Fri: boss milestone
- Sat: **rest**
- Sun: reflection

### Weekly Reflection Prompts
...
```

Offer to start with **Day 1's mission** immediately so the user wins their first XP today.

## Example (Spiritual + Academic)

User: *"I want to dedicate more time to God and actually finish my coding project."*

- **Stats:** Spirit, Intellect, Discipline
- **Act I (1–30):** daily 15-min scripture + prayer (Spirit, +5); daily 1 short coding lesson (Intellect, +5); nightly 5-min plan (Discipline, +2)
- **Boss (Fri):** "Finish the week's module and add it to the project" (+25)
- **Rest (Sat & chosen):** no coding; church/community, walk
- **Reflection (Sun):** journal on where God and discipline met this week

## Anti-Burnout Guarantees

- Never schedule 7 consecutive work days.
- After a 3-day grind streak, force a light/recovery day.
- All missions are time-boxed; if an act grows too heavy, cut scope, not the person.
- The goal is momentum + completion, not perfection.