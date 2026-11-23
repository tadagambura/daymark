# Daymark: Spec

**Countdown to anything, and never miss a birthday** · #11 of 17 · Wave 2: Recurring keepers · Used: Daily glance · Very easy · Revenue potential: Medium · Plans, Trips & Occasions · Source: ChatGPT + Perplexity (absorbs GiftNudge, PackRight and MoveDay)

## One-liner

Beautiful countdowns (and 'days since' counters) for the things you're looking forward to: holidays, payday, exams, moving day, concerts. Plus a people & birthdays mode: the people you buy for, their birthdays and anniversaries, a running note of gift ideas for each, and a nudge two weeks before with your ideas and budget ready. Lives on your home screen as a widget.

## Problem / audience

- **Who it's for:** Anyone looking forward to something, and whoever in the household 'does the presents'.
- **The problem it solves:** People want to see the days ticking down to things they care about, and birthdays sneak up with gift ideas long forgotten.
- **Example:** A worker counts down to payday and a holiday on one widget; in March they note that their sister mentioned a pottery class, and in October Daymark nudges them two weeks before her birthday with the idea and budget ready.

## MVP features (ship with only these)

1. Countdowns and count-ups ('days since') with themed cards
2. Recurring events: payday, bin day, term dates
3. People & birthdays: birthdays, anniversaries and a gift-idea note per person, captured year-round
4. Reminders 2 weeks and 2 days before birthdays; budget per person and a 'bought' tick
5. Share a countdown card; three free countdowns
6. Templates with a checklist attached: trip (packing list) and UK house move (council tax, TV licence, DVLA, meter readings)

## Not in MVP

- Home-screen and lock-screen widgets
- Christmas list mode and shared family gift lists
- Gift suggestions by age and interest (affiliate, clearly labelled)
- Shared countdowns for group trips
- Photo backgrounds and premium themes

## Monetisation

| Model | Detail |
|---|---|
| Free | 3 countdowns and up to 5 people, with ads |
| Premium | £24.99/year (shown first) or £3.49/month, or a lifetime unlock: unlimited countdowns and people, widgets, themes, shared lists |
| Affiliate | Gift ideas linking to retailers, clearly labelled |
| Ads | Banner only, never on the countdown card |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | The countdown on the widget daily; birthday reminders |
| Tiny win | Glance at the widget, or tick 'bought' / add a gift idea |
| Progress | Days remaining and % complete; who's sorted this year |
| Share | Countdown cards and family wishlists |
| Next step | When an event arrives, prompt for the next one; after a birthday, jot ideas for next year |
| Cadence | Daily glance, event-driven, Christmas peak |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Countdown hits zero: confetti cannon and the flip clock spins
- Each new day: a flip-clock digit flips with a satisfying clack
- Birthday approaching: the gift box shakes a little more each day
- Marked as bought: the ribbon unties itself into confetti
- Birthday: the cake's candles blow themselves out


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app; widgets need the native build. A web version is a quick start.
- **Data:** On the device only.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Seasonal countdowns; Life milestones; Gift ideas by person; Christmas planning; Remembering dates
- **Shareable output:** Countdown cards and family wishlists

## Risks

Crowded category; widgets and design quality are the difference. Contact import (later) needs careful privacy wording. The store name may already be taken.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
