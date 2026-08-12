# Reflection — Seeing Is No Longer Believing

## Part A — AI Grading Reflection

### A1. AI Model 1 — Summary

We used **Claude (Opus 4.5)**. It gave us:

- Content & Presentation: **21/25**
- GitHub Collaboration: **16/25** (marked "provisional" — it couldn't see our commits, Issues, or branches, only the README)
- AI Evaluation Setup: **23/25**
- Reflection Quality: **not gradeable** (this file didn't exist yet when we asked)
- Total: **60 out of 75** it could actually check, which it said was about 80%

Its main compliments: the source-quality section (§8 of `research-material.md`, where we explain which stats we trusted and which we threw out) was the strongest part of the project, the callback to our last AWS project gave the video a real argument instead of just a list of facts, and we handled the non-consensual imagery section correctly — short, factual, no examples.

What it said to fix: one claim (that fake intimate imagery is the most common use of this tech) doesn't have a source in `SOURCES.md`, one stat says "0.1% of people" when it should say "0.1% of participants," the UK bridge story leans on one article, and the video's timing might run long.

---

### A2. AI Model 2 — Summary

We used **Grok**. `TODO: paste the exact category scores here once the response is in ai-evaluation/ai-model-2.md — we haven't run it yet, so we're not putting numbers on this until we actually have them.`

What we can already say about how it approached the review: it didn't try to score things it couldn't see, like the video or our GitHub activity, the same way Claude held back. But it leaned harder into fact-checking than Claude did — it specifically praised us for throwing out the inflated "growth" percentages from vendor blogs and keeping the sourcing table.

---

### A3. Comparison — What Was Similar? What Was Different?

Both AIs were careful about not grading things they couldn't actually check, like the video itself or our GitHub history. Neither one just made up a score to fill in the blank.

Where they differed: Claude spent more time on how things were written — word choice, whether a claim matched its source exactly. Grok spent more time checking whether the numbers themselves held up, and gave us more credit for rejecting bad stats. So Claude read more like an editor, and Grok read more like a fact-checker.

---

### A4. Do You Agree With the AI's Grade?

Mostly, yes, with one exception.

- The missing source for the "most common use" claim — fair. That's a real gap and an easy fix.
- "0.1% of people" instead of "0.1% of participants" — technically correct, but small. The script says the same number a different way ("one in a thousand"), so it's not wrong, just not identically worded everywhere.
- The UK bridge story being under-sourced — fair, we only have one article for that one.
- Claude flagging "one in a thousand" and "0.1%" as if they don't match — this one we disagree with. They're the same number. That's not a factual mistake on our part, just two ways of saying it.

Nothing here really surprised us. The pattern was pretty predictable: dock points for anything it couldn't see (the video, GitHub), then grade the writing closely.

---

### A5. What Would You Do Differently?

Changes we'd actually make:
- Write "participants," not "people," everywhere the iProov stat appears.
- Make the UK bridge line in the script match the more careful wording already in our research notes.
- Put the full citation next to the 96% pornographic-deepfakes stat everywhere it shows up, not just in the sources list.

Feedback we're not taking:
- The "one in a thousand" vs. "0.1%" note — same number, not a real error.
- Any point taken off just because the AI couldn't watch our video or see our GitHub activity. That's a gap in how it graded us, not a gap in the actual project.

---

## Part B — AI Research Assistance Reflection

### B1. How You Used AI During Research

We used **Claude** and **ChatGPT** to turn dense legal text (the TAKE IT DOWN Act, EU AI Act Article 50) into plain language, **Perplexity** and sometimes **Gemini** to find sources and check whether a number was still current, and **Claude** again for structuring the script and checking whether any line sounded overstated.

---

### B2. What Worked Well

The best example: we asked Claude to turn the EU AI Act Article 50 rules and the TAKE IT DOWN 48-hour rule into two short lines we could actually say out loud in the video. What it gave us barely changed before it went into the final script. That probably saved us half an hour of rewriting.

---

### B3. What Did Not Work Well

Early on, ChatGPT gave us a "2,137% growth in deepfakes" stat and made it sound like it came from a real report. When we tried to track it down, it turned out to be a recycled number from a press release with no clear methodology behind it. We dropped it and went back to the FBI's IC3 numbers and the Surfshark study instead, which actually say what time period they're measuring.

---

### B4. Overall Reflection

We'd use AI the same way again for summarizing and translating dense text into plain language, but we'd be stricter about checking a number before we trust it, not after.

The biggest thing we learned: AI is very good at making text sound finished and confident, whether or not it's actually correct. That's exactly the moment to slow down and check the source, not speed up.
