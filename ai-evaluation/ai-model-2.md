# AI Evaluation — Model 2: Grok (xAI)

**Model:** Grok, grok.com web interface
**Method:** Same project files uploaded, and the same prompt used for Claude — deliberately unchanged. If we varied the wording between models, any difference in the grades could be caused by our prompt rather than by the models, and the comparison in our reflection would be worthless. One prompt, two models, one variable.

---

## Our Prompt

```
You are grading a group project for CEP146 — Essential Tooling for Programmers,
a first-year course. The audience for the video is other first-year students,
not specialists. There are three of us in the group.

Our topic is deepfakes and synthetic media — impersonation fraud, AI-generated
misinformation, and non-consensual imagery — including the EU AI Act Article 50
transparency rules and the US TAKE IT DOWN Act. Our project files are attached:
the slide deck, the video script, our README, our source list, and our research
notes.

Before you grade, do two things:

1. Tell us honestly which parts you were actually able to inspect and which you
   are inferring. If you cannot watch the video or see our commit history, say so
   plainly and do not invent a score for those parts — mark them unverifiable.
   We would rather have a partial grade we can trust than a complete one we cannot.

2. Try to prove our facts wrong. Every statistic came from a source listed in
   SOURCES.md. Check whether each number is stated with the right scope, date
   range, and level of confidence, and tell us where we have overstated something
   or where a claim in the script is not backed by anything in our source list.
   We care about this more than comments on slide design.

Then grade us using the rubric below.

Grading Rubric (each category worth 25 points, total out of 100):

1. Content & Presentation — recent topic (last 6–12 months); accurate and clearly
   explained; organized and within 2:30–3:00; explains why it matters to society;
   ends with a thoughtful discussion question; all members participate.

2. GitHub Collaboration — organized repo; commits from all members; Issues,
   branches and pull requests used; complete README (team names, topic summary,
   video link, discussion question, sources); Discussion board used.

3. AI Evaluation Setup — 2 different models used; full prompts saved and visible;
   rubric included in the prompt; full responses saved; prompts specific and
   thoughtful rather than vague.

4. Reflection Quality — compares the two AI results; clear opinion on whether we
   agree with the suggested grade; reflects on how AI helped or did not help our
   research; honest and specific with real examples.

Please provide a score out of 25 per category, a total out of 100, 2–3 specific
strengths, 2–3 specific areas to improve, and any other useful comments.
```

---

## Grok's Full Response

**Honest scope of what I can and cannot inspect**

I was given:
- The full video script
- The research notes
- The slide deck
- The README
- Strong excerpts and descriptions of the source list and data-quality notes

I **cannot** inspect:
- The actual YouTube video (delivery, pacing, whether all three members appear and speak, whether the final question is held in silence, visual quality, audio)
- The GitHub repository itself (commit history by member, Issues, branches/PRs, Discussion board activity)
- The final `reflection.md`
- The `/ai-evaluation/` folder (exact prompts sent to the two models and their full responses)

Therefore:

- **Content & Presentation** — I can grade the substance of the script, research accuracy, slide design, and discussion question with high confidence. Video *delivery* and "all members on camera" remain **unverifiable**.
- **GitHub Collaboration** — **Unverifiable**. I will not invent a score.
- **AI Evaluation Setup** — **Unverifiable**. I will not invent a score.
- **Reflection Quality** — **Unverifiable**. I will not invent a score.

I am only scoring what I can actually see.

---

**Fact-checking (trying to break your numbers)**

I checked the core claims against primary or high-quality secondary sources.

| Claim | Verdict | Notes |
|-------|---------|-------|
| Arup Hong Kong deepfake call, $25.6M, 15 transfers, Feb 2024 | **Holds** | Confirmed by Hong Kong Police statements, Arup acknowledgment, FT, CNN, etc. Exact figure and structure match. |
| FBI IC3 2025: 22,364 AI-related complaints, ~$893M losses | **Holds** | Official 2025 IC3 report (released ~April 2026). First year the category was broken out separately. Numbers match precisely. |
| iProov: only 0.1% / 1 in 1,000 could reliably distinguish real vs AI media | **Holds with minor language note** | iProov study of ~2,000 UK/US participants. The 0.1% figure is accurate. Script's "one in a thousand people" is a reasonable public translation of the same number. Claude's distinction between "participants" and "people" is pedantic rather than material. |
| EU AI Act Article 50 transparency / deepfake labelling applicable 2 August 2026 | **Holds** | Confirmed across European Commission materials and multiple legal analyses. Fines up to €15M / 3% also correct. |
| TAKE IT DOWN Act: 48-hour platform removal duty enforceable from May 2026 | **Holds** | Signed 19 May 2025; platform obligations became enforceable 19 May 2026. FTC began enforcement and issued warning letters around that date. |
| Bombay Stock Exchange deepfake of CEO Sundararaman Ramamurthy (Jan 2026, later resurfaced) | **Holds** | BSE issued formal advisory in January 2026; the video reappeared and required further action. |
| Europol IOCTA projection ~8M deepfakes in 2025 vs ~500k in 2023 | Plausible / consistent with secondary reporting | I did not re-verify the exact Europol PDF in this pass; the research notes treat it as a projection, which is the correct framing. |
| "96% of deepfake videos online are pornographic" | Needs the exact citation attached every time | Commonly cited figure from International AI Safety Report / related sources. Your research notes correctly flag data-quality issues around prevalence claims in general. Keep the source glued to the number. |

**Where you were careful and strong**
- You explicitly rejected the circulating four-digit "surge" percentages and documented why.
- You treated loss totals as undercounts.
- You distinguished measurement windows and methodology.
- NCII is handled with appropriate restraint (no examples, no names, no images).

**Minor overstatements / tightening opportunities**
1. Script sometimes says "people" where the iProov study said "participants." Fixable in one pass.
2. The UK earthquake / collapsed-bridge claim is thinner than the Arup or BSE claims. The research notes are more cautious than some spoken lines; align the spoken version to the notes.
3. Make sure every appearance of the 96% figure carries its source.

Overall: the factual core is unusually solid for a first-year project. Most of the numbers survive adversarial checking.

---

**Partial grade (only what is verifiable)**

**Content & Presentation (script + research + slides + discussion question) — 22/25**

Strengths:
- Topic is recent, clearly relevant, and explained at the right level for first-year students.
- Strong through-line from the previous cloud project (same economics, different payload).
- Script is tight, speakable, and well-paced for 2:30–3:00 with three distinct voices.
- Research notes show real intellectual honesty about data quality.
- Discussion question is excellent and open-ended.
- Slides follow a clean, professional, high-trust visual system (white space, restrained teal, sparse content).

Deductions:
- A couple of language-precision issues on the iProov figure and the UK example.
- Video delivery, on-camera participation of all three members, and final timing remain unverifiable, so I cannot award the full 25.

**GitHub Collaboration — Unverifiable, no score**

**AI Evaluation Setup — Unverifiable, no score**

**Reflection Quality — Unverifiable, no score**

---

**Summary for you**

On the parts I can actually examine, this is a strong first-year project. The research discipline and the decision to treat prevalence and loss figures carefully stand out. The main remaining risks are (1) the video itself and (2) whether the GitHub and reflection artifacts match the quality of the script and notes.

I am deliberately not inventing scores for the parts I cannot see. That is the honest version of the grade you asked for.

---

## What to Watch For — how this actually compared to Claude

**Did it declare its access limits?** Yes, and more strictly than Claude did. Claude gave *provisional* numeric scores for GitHub Collaboration (16/25) and AI Evaluation Setup (23/25) even though it couldn't see commits, Issues, or the AI-evaluation folder. Grok refused to put a number on any of those three categories at all — "unverifiable, no score" rather than a hedged guess.

**Did it score Category 4?** No — same as Claude, it marked Reflection Quality unverifiable rather than inventing a number for a file that didn't exist yet when it was asked.

**Where the two models actually disagreed:** Claude flagged "0.1% of people" vs. "0.1% of participants" as an overstatement worth fixing. Grok independently called that same distinction "pedantic rather than material" — a direct disagreement between the two graders on how serious that wording issue is.

Claude's findings, for comparison: the prevalence claim is unsourced in SOURCES.md; "0.1% of people" should read "of participants"; the UK bridge example rests on a single secondary source; the slide says 0.1% while the script says one in a thousand; and the script risks running past 3:00. Claude scored 21 / 16 / 23 / not gradeable, declined to give a total out of 100, and put us at 60/75 on what it could verify.
