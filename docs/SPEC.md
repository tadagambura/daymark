# Daymark: Spec

**Countdown to anything** · #12 of 33 · Wave 2: Recurring keepers · Used: Daily glance · Very easy · Revenue potential: Medium · Plans, Trips & Occasions · Source: ChatGPT + Perplexity

## One-liner

Beautiful countdowns, and 'days since' counters, for the things you're looking forward to: holidays, birthdays, payday, exams, moving day, concerts, due dates. Lives on your home screen as a widget.

## Problem / audience

- **Who it's for:** Broad: students, planners, parents, event-goers, anyone looking forward to something.
- **The problem it solves:** People want to see the days ticking down to the things they care about, somewhere they'll see it every day.
- **Example:** A worker counts down to payday, a student to exams and a family to their holiday, all on one home-screen widget.

## MVP features (ship with only these)

1. Countdowns and count-ups ('days since') with themed cards
2. Days, weeks and hours, plus a progress bar
3. Recurring events: payday, bin day, birthdays, term dates
4. Three free countdowns
5. Share a countdown card; reminder the day before

## Not in MVP

- Home-screen and lock-screen widgets
- Shared countdowns for group trips
- Photo backgrounds and premium themes

## Monetisation

| Model | Detail |
|---|---|
| Free | 3 countdowns, with ads |
| Premium | £4.99–£9.99 lifetime (or £1.99/month): unlimited countdowns, widgets, themes, shared countdowns |
| Ads | Banner only, never on the countdown card |

Prices are starting points; test before committing.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | The countdown itself, seen daily on the widget |
| Tiny win | Glance at the widget |
| Progress | Days remaining and % complete |
| Share | Countdown cards |
| Next step | When an event arrives, prompt for the next one ('Next holiday?') |
| Cadence | Daily glance, event-driven |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Flip-clock countdown
- Confetti explosion when a countdown hits zero


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app; widgets need the native build. A web version is a quick start.
- **Data:** On the device only.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Seasonal countdowns; Life milestones; Anticipation and planning
- **Shareable output:** Countdown cards

## Risks

Crowded category; widgets and design quality are the difference. The store name may already be taken.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
