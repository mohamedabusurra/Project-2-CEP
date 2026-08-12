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

Paste the complete, unedited response below. Do not trim the parts that are wrong or unflattering — those are the most useful material for the reflection.

```
```

---

## What to Watch For

Two things worth noting the moment the response comes back, while it is fresh:

**Did it declare its access limits?** Claude stated up front that it could not watch the video or read the commit history and refused to score those parts. If Grok grades all four categories confidently anyway, that difference is the most interesting finding available from this exercise.

**Did it score Category 4?** `reflection.md` did not exist when either model was asked. Claude marked it ungradeable. A confident number there is a fabrication, and the exact wording is worth quoting in the reflection.

Claude's findings, for comparison: the prevalence claim is unsourced in SOURCES.md; "0.1% of people" should read "of participants"; the UK bridge example rests on a single secondary source; the slide says 0.1% while the script says one in a thousand; and the script risks running past 3:00. Claude scored 21 / 16 / 23 / not gradeable, declined to give a total out of 100, and put us at 60/75 on what it could verify.
