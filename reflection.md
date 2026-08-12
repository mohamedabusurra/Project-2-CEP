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

We used **Grok**. It gave us:

- Content & Presentation: **22/25**
- GitHub Collaboration: **unverifiable, no score**
- AI Evaluation Setup: **unverifiable, no score**
- Reflection Quality: **unverifiable, no score**

Its main compliments: the research notes show real honesty about data quality, the script is tight and well-paced for three voices, the discussion question is strong, and the slides are clean and easy to trust. It also went through our numbers one by one — Arup, the FBI IC3 figures, the EU AI Act date, the TAKE IT DOWN 48-hour rule, the BSE deepfake — and said all of them hold up.

What it said to fix: the same "people" vs. "participants" wording Claude flagged, tighten the UK bridge/earthquake line to match our more careful research notes, and put the source next to the 96%-pornographic stat every time it appears, not just in the source list.

---

### A3. Comparison — What Was Similar? What Was Different?

Where they agreed: both models refused to invent a score for things they couldn't see — the video itself, our GitHub activity — and both landed on almost the same Content & Presentation score (21 vs. 22). Both also independently checked our numbers against outside sources and said the core facts hold up.

Where they differed:
- Claude still gave us provisional numbers for GitHub Collaboration (16/25) and AI Evaluation Setup (23/25) even though it admitted it couldn't really see those things. Grok wouldn't put a number on any of the three unseeable categories at all — stricter than Claude on its own rule.
- They disagreed on how serious the "0.1% of people" vs. "0.1% of participants" issue is. Claude listed it as something to fix. Grok called the same thing "pedantic rather than material" — basically told us not to worry about it.

Grok gave more useful feedback here, mainly because it was more consistent: it applied its own "don't invent a score" rule across the board instead of bending it for two categories like Claude did.

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
