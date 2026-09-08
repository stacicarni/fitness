# Postpartum Fitness Coach — Staci

A self-contained coaching system: intake, phased plan, exercise library, nutrition
guardrails, and a weekly log. Built for a 2026 restart that turns into a routine
you keep for years.

## Where you are right now

| | |
|---|---|
| **Baby born** | Mon, Aug 17, 2026 |
| **Today** | Tue, Sep 8, 2026 |
| **Postpartum age** | 3 weeks + 1 day (start of PP week 4) |
| **Birth** | Vaginal / unmedicated ("natural") |
| **Your age** | 39 → **40 on Sep 26, 2026** |
| **6-week mark** | **Mon, Sep 28, 2026** |
| **12-week mark** | Mon, Nov 9, 2026 |
| **Current phase** | **Phase 0 — Reconnect** |

## How to use this repo

1. **Fill out [`intake/INTAKE-SURVEY.md`](intake/INTAKE-SURVEY.md).** It is long on
   purpose. Every question changes something in the plan. Answer inline, commit it,
   and the plan gets rebuilt around your answers.
2. **Train from [`plan/`](plan/).** Start with
   [`phase-0-reconnect.md`](plan/phase-0-reconnect.md) — that is this week.
3. **Log in [`logs/`](logs/).** Copy `logs/TEMPLATE.md` each Monday. The log is how
   progression decisions get made; without it we are guessing.
4. **Check [`reference/RED-FLAGS.md`](reference/RED-FLAGS.md) once, now.** Know what
   stops a session and what sends you to a doctor.

## The arc through the rest of 2026

```
Sep 7 ───────── Sep 28 ───────── Oct 26 ───────── Nov 23 ───── Dec 21 ── Jan 4
   PHASE 0        PHASE 1          PHASE 2          PHASE 3      PHASE 4    │
  Reconnect    Rebuild Base    Load + Impact Prep    Build     Consolidate  │
   PP wk 4-6     PP wk 7-10       PP wk 11-14      PP wk 15-18  PP wk 19-20 │
                                                                            ▼
                                                            The forever template
                                                                  (2027+)
```

## The non-negotiables

- **Nothing in Phase 0 requires clearance. Nothing after Phase 0 happens without it.**
  Your 6-week visit on/around Sep 28 is the gate.
- **Symptoms outrank the schedule.** Leaking, heaviness/bulging, doming, pain, or a
  jump in bleeding means you regress a level that day. Every time. See
  [`plan/PROGRESSION-RULES.md`](plan/PROGRESSION-RULES.md).
- **Ask for a pelvic floor PT referral at your 6-week visit** even if you feel fine.
  In much of Europe it is standard postpartum care; in the US you usually have to
  ask. It is the single highest-value thing you can do for the next 12 months of
  training. Kaiser and Sutter both have pelvic health PT in the East Bay.
- **Running is not the first thing back. It is one of the last.** See
  [`reference/RETURN-TO-RUNNING.md`](reference/RETURN-TO-RUNNING.md). Target window
  is 12-16 weeks postpartum (Nov-Dec), gated by a test, not a date.

## Your equipment

**Home:** Peloton Bike + full app (yoga, strength, stretching, meditation, postnatal),
Bowflex SelectTech adjustable dumbbells (5-52.5 lb each, 2.5 lb increments to 25),
2 × 3 lb dumbbells, resistance bands, yoga mat, 2 blocks, meditation cushion.
**Building (Metro510, El Cerrito):** elliptical, treadmill, weights.
**Outside:** running path. Ohlone Greenway runs right past you — flat, paved, stroller-friendly.

## A note on scope

This is a structured training and nutrition plan, not medical advice. It is built
from mainstream postpartum rehab practice (Goom/Donnelly/Brockwell return-to-running
guidelines, ACOG activity guidance, standard pelvic health progressions). Your OB,
midwife, or pelvic floor PT overrules anything in here.

## The interactive version

`web/dashboard.html` is published as a private Artifact:
**https://claude.ai/code/artifact/2933df1e-3b03-4719-83b3-952619d20001**

Today's session with checkboxes, the intake survey (saves as you type), the roadmap,
nutrition, and the safety reference. It's the same content as this repo, in the form
you'd actually use at 6am with a baby on one arm.

The file is an Artifact fragment — no `<!doctype>`/`<html>` wrapper, since the platform
adds one at publish time. To change it, edit the file and republish to the same URL.
