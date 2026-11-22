# MoneyMinute: Spec

**Learn money in a minute a day** · #8 of 33 · Wave 1: Daily keepers · Used: Daily · Easy, content-heavy · Revenue potential: Medium–high · Habits, Health & Learning · Source: New (Claude)

## One-liner

Duolingo for money. One 60-second lesson or quiz a day on budgeting, saving, credit scores, pensions, tax and scams (UK-focused), with streaks, XP and levels. Each lesson ends with a practical action you can take in StackUp, PocketLeft or SubSpot. The approach draws on the principles in Morgan Housel's The Psychology of Money (credited, and explained in our own words), and every lesson cites a trusted source.

## Problem / audience

- **Who it's for:** Young adults who feel behind on money basics.
- **The problem it solves:** Money advice is long and overwhelming; people want small, practical, trustworthy steps.
- **Example:** A user does a two-minute lesson on credit scores each morning, keeps a 50-day streak, and starts a StackUp emergency-fund challenge from a lesson prompt.

## MVP features (ship with only these)

1. One 60-second lesson or quiz a day
2. Units: money mindset (inspired by The Psychology of Money), budgeting, saving, credit, pensions, tax, scams
3. Streaks with freezes, XP, levels and gems
4. A practical 'do it now' action after each lesson
5. Every lesson shows its source (MoneyHelper, GOV.UK, HMRC, FCA) and when it was last checked

## Not in MVP

- Optional leagues (needs a backend)
- Premium deep-dive units
- Life-event packs: first job, moving out

## Monetisation

| Model | Detail |
|---|---|
| Free | The daily lesson, with ads |
| Premium | £2.99/month: all units, unlimited practice, no ads |
| Cross-promotion | Funnels into StackUp, PocketLeft and SubSpot |

Prices are starting points; test before committing.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Daily lesson reminder |
| Tiny win | Finish a 60-second lesson |
| Progress | Streak, XP, levels, units completed |
| Share | Level-up and streak cards |
| Next step | The next unit unlocks |
| Cadence | Daily |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## AI

**None for facts.** Lessons are written and checked by people from trusted sources. AI may help draft, but never publishes a fact unreviewed. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app.
- **Data:** On the device only; lessons ship as content files.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Money basics; Myth vs fact; UK money rules explained
- **Shareable output:** Level-up and streak cards

## Risks

Accuracy is everything: every fact comes from a trusted source, is checked by a person before it's published, and is re-checked on a schedule (tax rules change every April). AI can help draft, but never publishes unreviewed. The Psychology of Money is used for its ideas, credited, never copied (copyright). Education, not personal advice: FCA financial-promotion rules mean no product recommendations.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
