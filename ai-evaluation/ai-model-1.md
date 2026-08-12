# AI Evaluation — Model 1: Claude (Anthropic)

**Model:** Claude Opus 4.5, claude.ai web interface
**Method:** We uploaded our project files directly (slide deck, video script, README, SOURCES.md, research notes) rather than pasting links, because we wanted the model grading the actual contents rather than guessing from a URL it may not be able to open.

---

## Our Prompt

> Written by us, not adapted from the sample. Three deliberate choices: we gave it the course level and audience, we ordered it to declare what it could not inspect instead of guessing, and we asked it to **falsify** our facts rather than assess our slides. The third instruction is why the response below is criticism instead of compliments.

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

## Claude's Full Response

### What I could and could not inspect

**Read directly:** README, SOURCES.md, research notes, video script, slide deck.

**Could not inspect:** the video itself — I cannot watch video, so I cannot confirm runtime, audio quality, whether all three of you appear and speak, or whether delivery matches the script. Nor could I see commits, Issues, branches, pull requests, or Discussion activity.

That shapes the scores below. Category 1 is graded on your script and deck as a proxy for a video I have not seen. Category 2 is graded on structure and README only — maybe a third of what that category asks about. Category 4 I cannot score at all.

### Trying to prove your facts wrong

**What holds up:** the Arup figure, the IC3 2025 numbers, the Surfshark totals, the Entrust 1-in-5, the Article 50 date and penalty ceiling, and the TAKE IT DOWN 48-hour window are all correctly scoped and attributed. I specifically checked whether any forecast was presented as a measurement — the most common error on this topic — and none was. Naming Deloitte's $40B-by-2027 as a projection rather than a headline is the right call.

**1. Your most-quoted claim is your least-sourced.** The script says fake intimate imagery "has always been" the most common use. Probably true and widely repeated, but it traces to a 2019 Deeptrace study that is seven years old and appears nowhere in SOURCES.md. Your entire methodological argument is *only figures with a named source and a stated window* — and the one claim you assert with "always" has neither. Cite the study with its date, or soften the wording to something your existing sources support.

**2. The 0.1% figure overreaches.** The slide reads "0.1% of people could reliably tell real from fake." iProov measured *participants* on specific stimuli. "Of people" generalises a sample to a population — the exact move §8 criticises other sources for. Two words fixes it.

**3. Thin sourcing on the UK bridge example.** The December 2025 image and train cancellations rest on one trade-press article. Good illustration, keep it, but the causal claim ("spread fast enough to cancel trains") is stronger than one secondary source supports.

**4. Internal mismatch.** Script says "one in a thousand," slide says "0.1%." Same number, but the viewer converts mid-sentence. Pick one form.

**Timing risk (not factual):** ~410 words plus instructed pauses likely lands 2:50–3:05 against a hard 3:00 ceiling. Rehearse timed, and know in advance which two sentences you would cut.

### Scores

**1. Content & Presentation — 21/25.** Recency is unambiguous: Article 50 applied 2 August 2026, FTC enforcement began 19 May 2026, both inside your window rather than retrofitted. Societal impact is covered across consumers, markets, journalism and individual victims rather than staying inside the technology. The discussion question is genuinely open, follows from your evidence, and is answerable by a first-year — harder than it looks. Opening on the Arup call instead of a definition is the right instinct: you buy attention before spending it on explanation, and "a copy machine for people" does the technical work in one retainable sentence. Deductions: the sourcing gap and scope overreach are accuracy faults in a project whose thesis is accuracy discipline (−2); timing risk (−1); participation and delivery unverifiable, so I am scoring the script's *design* for three speakers, not its execution (−1, provisional).

**2. GitHub Collaboration — 16/25, provisional and mostly unverifiable.** Structure matches the assignment's recommended layout exactly. README carries team names, roles, topic summary, key findings, discussion question, and links. Splitting research notes from presentation materials makes the repo navigable. But commits, Issues, branches, pull requests and Discussion activity are the bulk of this category and I have no evidence either way, so I am scoring only the structural third I can see. One thing I *can* flag: `reflection.md` does not exist yet, and it is on the deliverables checklist.

**3. AI Evaluation Setup — 23/25.** The prompt is well above the sample and clearly your own. Giving the model the course level, ordering it to declare its access limits, and asking to be falsified rather than assessed is why this response contains four specific criticisms instead of four compliments — you engineered the feedback you got, which is the skill the assignment is teaching. Rubric included in full. Deduction only for the second model's response not being saved at time of writing.

**4. Reflection Quality — not gradeable.** `reflection.md` does not exist. I will not guess a score for a document I have not read, and you should be suspicious of any model that does. You already have unusually good raw material for it: §8 of your research notes is essentially a finished B3, and the four criticisms above give you something concrete to agree or disagree with in A4.

**Total: 60/75 on what I could verify — 80%, a solid B.** I am not reporting a /100, because inventing the missing pieces would make the number less honest, not more useful. If Category 2's hidden portion matches its visible portion and Category 4 is finished to the standard of the rest, this lands in the high 80s.

### Three strengths

1. **The source-quality audit is the best thing here, and it is not close.** §8 identifies that the headline statistics on this topic (900%, 1,210%, 2,137%, 3,892%) are mutually inconsistent, explains why — different windows, different denominators, forecasts recycled as measurements — and documents what you kept and why. First-year projects almost never do this, and here the methodology is genuinely interesting content: "the statistics about this problem are themselves unreliable" is a finding.

2. **The callback to your previous project earns its place.** "The cloud removed the barrier between an idea and the world — it removed the same barrier for a lie" is a real causal argument, not decoration: commodity rented compute is substantially why synthetic media scaled, and you are the group best positioned to make it because you established the first half last time. It also gives the video a thesis rather than a list.

3. **The non-consensual imagery section is handled correctly.** One slide, four spoken lines, factual, no examples or names, and it names the legal remedy. Groups usually either skip this — leaving the project incomplete — or handle it badly. You did neither.

### Three areas to improve

1. Close the sourcing gap on the prevalence claim. It is the one place your own standard is not met, and a grader who reads §8 then hears "has always been" will notice.
2. Fix both scope overreaches: "of people" → "of participants," and one consistent form of the 0.1% figure across slide and script.
3. Finish the repository before polishing the deck. The missing `reflection.md` is worth more rubric points than any remaining design work, and it is the cheapest point in the project to secure.

### Other comments

You asked me to falsify your claims and I found four. A prompt asking me to "evaluate this project" would have found roughly zero, because I would have defaulted to describing what you did rather than testing it. That gap — between the feedback you get and the feedback you ask for — belongs in B4.

Second: I could not watch your video or read your commits, and I said so. A model asked less carefully could have produced a fluent, confident, entirely fabricated paragraph about your editing and your branch hygiene, and nothing in the writing quality would have told you it was invented. Given your topic, that is not a coincidence to pass over. Whatever you conclude in A4 about fairness, the sharper observation is that the failure mode of the tool grading you is the failure mode of the technology you are presenting on: fluent, confident, unverifiable.
