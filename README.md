# Digital Footprint Multiplier

by [Marian Kamenistak](https://www.marian.coach/), engineering-leadership mentor

**Paste one LinkedIn link. Get one number for how you look to a recruiter, a hiring manager or an AI screening tool, and a plan for this week, this month and this quarter.**

People come to me after sending hundreds of CVs with nothing coming back. Most of the time the skill is there. The proof is not visible. Something reads you before a person does, and it can only judge what it can see. This skill looks at you the same way, from the outside, and tells you what to fix first.

## What you get

- **A multiplier from 0.4 to 1.7.** 1.0 is a typical 2026 profile: complete, honest, forgettable. 0.4 is a profile the internet has not met yet. 1.7 brings the roles to you.
- **The evidence behind every criterion.** A quoted line or a link. No evidence, no points.
- **A plan sorted by time.** This week (under two hours each), this month, this quarter, and a checklist for the week before you apply for a promotion or a new job. Each step shows what it is worth.
- **Two profiles:** software developer and engineering manager.

The number measures how visible your proof is. It says nothing about how good you are at the job, and it is not a salary.

## Install

```
npx skills add marian-kamenistak/digital-footprint-multiplier
```

Or copy this folder into `~/.claude/skills/`.

You need Claude Code with the Claude in Chrome extension, and to be logged in to LinkedIn in your own browser. The skill reads the profile there, read-only. It does not connect, follow, message or like.

## Use

```
/digital-footprint-multiplier https://www.linkedin.com/in/your-name
```

Tell it what you are aiming at (a promotion, a new job, a target role) and the plan follows that.

## What it scores

| Software developer | Weight | Engineering manager | Weight |
|---|---|---|---|
| Outcomes in the experience section | 16 | Business and team outcomes | 18 |
| Proof of work (code, products, demos) | 16 | Headline and positioning | 12 |
| Headline and positioning | 12 | Scope and its growth | 12 |
| AI fluency you can see | 12 | People vouch for how you lead | 12 |
| Your voice (posts, talks, podcasts) | 10 | AI leadership you can see | 12 |
| Other people vouch for you | 10 | Your voice | 10 |
| Easy to screen | 10 | Network signals | 8 |
| Network signals | 8 | Easy to screen | 8 |
| Fresh and consistent | 6 | Technical credibility | 4 |
| | | Fresh and consistent | 4 |

Each criterion gets a level from "not visible yet" to "strong", judged against written anchors in `model.json`. A small script does the arithmetic, so the number does not depend on a mood.

## Rules it keeps

- **Yours, or with a yes.** Run it on your own profile, or on someone who knows and agreed. Your visit shows up in their "who viewed your profile" anyway.
- **Public and professional only.** Nothing about health, family, politics or where someone lives.
- **Kind and honest.** A gap is "not visible yet", and it comes with the next step and how long it takes. The level is not raised to be nice.

## Where it comes from

The criteria and weights are distilled from 3,662 1:1 leadership sessions with 317 engineering leaders since 2019. Version 1.0 defines "typical" by written anchors, not by a dataset of scored profiles; the anchors get recalibrated as real runs come in.

It is the outside view to pair with the [Market Value Calculator](https://www.marian.coach/market-value-calculator/): the calculator asks you twelve questions, this skill asks the internet. Where your own score is higher than your footprint, the work is real and not visible yet.

MIT license.
