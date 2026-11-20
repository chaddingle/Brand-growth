# Brand Growth: short-form video system

Every agent in this repo reads this file first. It holds the niche, audience, voice, goals and rules for the TikTok account. If something here conflicts with a request, the hard rules win.

## Niche
Self-improvement, documented in real time. A JD/MBA student who doesn't want to practice law shows how he thinks and what he's changing as he goes. He was against college (his mom thought he was crazy), ended up in grad school, used to skip class and cram, and now organizes and iterates. The long game: show the grind now, so that a year or two from now the "this was me then, look at me now" payoff is earned. Until then, every post has to be worth watching by itself.

This account is **not** for real estate or builder networking. That's a separate account.

## Audience
Broad. Students, early-career people and anyone trying to get their act together: people who procrastinate, cram, overthink, avoid hard conversations, or chase things that look like progress but aren't. They want something relatable and specific, not generic advice.

## Goals
- **Primary metric: new followers per 1,000 views.** Not views, not saves. Baseline is about 0.66-0.8 per 1,000.
- Follower targets: 10K first, then 50-100K.
- Supporting signals: share of viewers still watching after the first seconds, saves, and shares.
- Daily slots: (1) a timelapse of real logged hours (the "10,000 hours" series, with the craft named plainly, e.g. "Business"), (2) one talking video on a broad, relatable theme, (3) one flex post built for growth. The 10,000 hours never comes up in a talking video.

## Voice
- Confident, direct, conversational. Short sentences. Sounds spoken, not like an essay.
- One vivid image per script. Occasional tag questions ("right?").
- Edge is fine. Insulting people is not.
- Profanity is optional: once or twice at most, on the pivot line, spoken only (never in on-screen text).
- Anchors are **time and process numbers** (10 minutes, 25 questions, a 90, 6.5 hours of cramming, 1,000 flashcards, logged hours, day count), never money. Every number has to be real.
- Personal and specific beats generic. Keep his own wording nearly word for word when he gives you a rough paragraph.
- **Endings:** finish on a real line or a real moment. No recaps, no "this is your sign", nothing motivational or bro-y.
- One idea per video. If a draft has two ideas, split it into two videos.

## Hard rules (never break)
1. Never name or hint at his school, employer, firm, city, or any real estate plans or deals. Check clothing and backgrounds for school lettering. Saying "law degree" and "MBA" is fine; a school name is not.
2. No exam content. No client or confidential information. No private health details unless he brings them up for a video.
3. Never invent numbers, results, income, purchases or experiences. If a real detail is missing, ask one question or leave a `[bracket]`. Two brackets per script at most.
4. "10x extreme" applies to attitude, framing and stakes, never to facts.
5. Verify every stat, quote, attribution and science claim before it goes in a script. If you can't verify it, say "a quote I read" or cut it. Don't repeat unchecked claims from reference videos.
6. Aim contrarian takes at ideas and behaviors, not at groups or named people. No sweeping group claims.
7. Borrow structure from other creators, never their wording, titles, format names or catchphrases.
8. No fake flexing and no implied partnerships. Paid or gifted deals get disclosed. Legal and financial points are personal experience, not advice.
9. Don't reuse stories that were already posted or cut (see `research/story-bank.md`) unless he asks for a re-record.

## Repo layout
```
CLAUDE.md                     ← this file (all agents read it)
.claude/agents/researcher.md  ← analyzes a week's folder and writes a report
.claude/agents/writer.md      ← turns the report into scripts
research/
  README.md                   ← what to drop in each week, and how
  story-bank.md               ← real stories, plus the posted and cut lists
  results-log.md              ← how each post performed (the agents learn from this)
  YYYY-Www/                   ← one folder per week (e.g. 2026-W47)
    transcripts/              ← 10-20 viral video transcripts (.txt/.md)
    analytics/                ← your TikTok analytics export (csv/screenshots/notes)
reports/                      ← researcher output: YYYY-Www-research.md
drafts/                       ← writer output: YYYY-Www-scripts.md
```

## Weekly run
> Have the researcher analyze `research/2026-W47`, then have the writer draft 5 scripts from the findings.

After posting, add each post's numbers to `research/results-log.md` so next week's research accounts for what actually worked.
