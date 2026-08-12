# Research Notes — AI Safety & Ethics: Deepfakes and Non-Consensual Media

**Course:** CEP146 — Essential Tooling for Programmers
**Topic:** Sexual deepfakes / non-consensual intimate imagery (NCII)
**Why it's a "current event":** The legal and policy response peaked in the last 12 months — the U.S. platform-removal deadline hit May 2026, Denmark's world-first likeness law is coming into force in 2026, the first U.S. conviction landed in April 2026, and UNICEF released its first global-scale child data in 2026.

---

## 1. What it is
A **deepfake** is an image, video, or voice generated or altered by AI to look real. The category with the fastest-growing, most serious harm is **non-consensual intimate imagery (NCII)** — sexual or nude images of real people created without their consent. The key distinction from older "revenge porn": **no real photo ever has to exist.** The image is entirely synthetic, yet the harm to the victim is real.

## 2. Scale (the "why it matters")
- The **International AI Safety Report 2026** estimates roughly **96% of deepfake videos online are pornographic**, and NCII **overwhelmingly targets women and girls**. In a survey across 10 countries, **2.2% of respondents** said someone had generated NCII of them, and the vast majority of "nudify" apps explicitly target women.
- **UNICEF / ECPAT / INTERPOL (2026):** across 11 countries, at least **1.2 million children** disclosed having their images manipulated into sexually explicit deepfakes in the past year — in some countries **1 in 25 children** (roughly one child per classroom).
- **Schools:** A 2026 WIRED investigation documented **~600 students across ~90 U.S. schools**, described as shifting from isolated incidents to an "endemic" problem. Earlier CDT research (2024) found only ~36% of teachers said their school had an adequate process to support victims.

## 3. The legal / policy response (the AI-ethics core)
- **United States — TAKE IT DOWN Act:** Signed into law **May 19, 2025**. Criminalizes knowingly *publishing* NCII, including AI deepfakes. Gave platforms until **May 19, 2026** to build a **48-hour notice-and-removal** process, enforced by the **FTC** (which has already sent warning letters to major platforms). **First conviction: April 2026** (an Ohio man). Important nuance: it targets **publication**, not private creation.
- **DEFIANCE Act:** Passed the U.S. Senate **Jan 13, 2026** — would add a federal **civil** right to sue for victims. **Not yet law.**
- **Denmark:** First country in Europe to propose giving people a **copyright-style right over their own face, body, and voice** — enabling takedowns and compensation. Expected to enter into force around **mid-2026** (delayed by a snap election).
- **UK:** The **Online Safety Act 2023** criminalized *sharing/threatening* to share intimate deepfakes; the **Data (Use and Access) Act (June 2025)** added criminalizing the *non-consensual creation* of sexual deepfakes.

## 4. The ethical tension (great for critical thinking / the discussion question)
- **Free speech vs. protection:** A U.S. state deepfake law (Hawaii's election-deepfake statute) was **struck down Jan 30, 2026** on First Amendment grounds — courts are wary of over-broad rules that could hit satire or political speech.
- **The creation-vs-publication gap:** Most laws punish *sharing*, not *making*. Should generating the image at all be the crime?
- **Is copyright even the right tool?** Legal scholars question whether stretching copyright (Denmark's approach) fits a problem that's really about dignity and consent.
- **Shared responsibility:** Harm runs across a chain — the person who typed the prompt, the AI tool that made it possible, and the platform that let it spread. Laws written for real photos "break down" when the image was synthesized entirely by an algorithm.

## 5. The programmer angle (why it matters to *this* class)
The tools are now on any phone, and targets are increasingly ordinary students, not celebrities. As future developers, the people in this room are the ones who will build — or refuse to build — and add safeguards to these systems. Technology outran both ethics and law; closing that gap is an engineering responsibility, not just a legal one.
