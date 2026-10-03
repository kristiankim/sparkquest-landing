# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

- **Parents** are the buyers and administrators. They set up each child, define daily tasks and point values, and design the reward menu. They evaluate Sparkquest on this marketing site and sign up at `/auth/signup`.
- **Kids aged roughly 4–12** are the daily users. Families with several children of different ages are the core case, so routines can differ per child and some tasks are shared between siblings.

## Product Purpose

Sparkquest is a habit-tracking app for families. Parents set the routine. Kids check off daily tasks, earn points and build streaks, then trade points for rewards the parent has chosen. It succeeds when good daily habits stick through consistent repetition that kids are motivated to keep up.

## Positioning

A gamified system that reinforces habits, with streaks and points, inside a reward economy that each family designs for itself. Parents choose the rewards and set their prices; the app doesn't supply them. The motivation is game mechanics, but the tone stays calm and warm, and missing a day never brings punishment or shame.

## Operating Context

- Kids check in on a phone or tablet, once a day or at set times (morning, after school). The check-in is meant to take about 30 seconds and fit on one screen.
- Parents manage everything from a PIN-gated dashboard with a weekly view of what stuck and what didn't.
- The product app is a separate Next.js 14 codebase ([kristiankim/Kiddoscore](https://github.com/kristiankim/Kiddoscore)), live at sparkquest.netlify.app. This repo is the static marketing site only, deployed by Netlify from `main`.

## Capabilities and Constraints

Confirmed features:
- Multiple children per family, with per-child tasks and tasks shared between siblings
- Daily task checklists with point values set by the parent
- Streaks: a missed day resets the streak to zero. No points are lost and the kid sees no shaming message.
- A reward menu the parent designs, with their own prices, which kids redeem with points
- A weekly view for parents
- A PIN-gated parent dashboard, so kids can't change their own point values

Open decisions:
- **Sparkquest is free during the beta.** The landing page shows a single free beta offer; the earlier plans section is kept in `index.html` but hidden.
- **Pricing and plans are not decided.** The current page's $0 tier for one child, $4/month Family plan, 6-kid limit and 14-day trial are placeholders, not product facts.
- **Calendar sync** is listed as "coming soon". Its status is not confirmed.
- **The marketing copy contradicts the positioning.** The current page says "No streaks", "No streak shaming" and "never gamified". These lines predate the decision to gamify with streaks and need rewriting.

## Brand Commitments

- Name: **Sparkquest**. The mark is a white star on a rounded indigo square (`assets/mark.svg`).
- Voice: calm, warm, encouraging, unhurried. Sentence case everywhere. Gamified, but never loud, hype-driven, punishing or anxious. No urgency tactics, and no shaming when a streak breaks.
- Apercu is the marketing-only typeface (`fonts/`) and is never used in the product UI. Visual foundations are owned by the Kiddoscore repo.

## Evidence on Hand

- Product UI is shown only as hand-built HTML/CSS mockups (phone checklist, parent dashboard) in `index.html`, using placeholder kids (Maya, Arlo, Juno).
- There are no real testimonials, user counts, press, case studies or screenshots of the live app in this repo. Future work must not fabricate any of them.
- Privacy, Terms and Contact pages don't exist yet; the footer links point to `#`.

## Product Principles

1. **Motivate, never punish.** Streaks and points reward consistency. A missed day resets quietly and tomorrow is a fresh start.
2. **Parents own the economy.** The family decides the rewards, the prices and the routines. The app provides the structure, not the values.
3. **Fast for kids.** The daily check-in should take about 30 seconds and be usable by a 4-year-old.
4. **Calm by default.** Game mechanics are delivered warmly. No noise, nagging or manipulative urgency for kids or parents.

## Accessibility & Inclusion

- The kid-facing UI must work for pre-readers and early readers aged around 4. Kids of that age need large tap targets and can't rely on text alone.
- The audience is children, so privacy and trust materials (privacy policy, children's data handling) are expected before launch. COPPA-style obligations are likely relevant but haven't been assessed.
