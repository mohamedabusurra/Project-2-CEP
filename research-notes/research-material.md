# Deepfakes: Synthetic Media, Scams, and the Collapse of Proof

## 1. What a Deepfake Actually Is

A deepfake is synthetic media — video, image, or audio — where a real person's face or voice has been generated or manipulated by an AI model so that they appear to say or do something they never did.

The pipeline is simple enough to describe in three steps. First, collect reference material: a podcast appearance, a conference talk, a clip from social media. Second, a model learns the mapping — how that specific face moves, how that specific voice sounds. Third, it re-renders. What used to require a studio now requires a public video and a rented GPU.

Two numbers set the scale of how low the barrier has fallen. Voice cloning needs roughly three seconds of source audio. Impersonating an executive convincingly can take as little as twenty seconds of footage (CSO Online, 2026).

## 2. Why It Broke Out Now: The Same Economics as Our Last Project

Our previous project argued that IaaS turned computing from a capital expense into an operating expense, and that this removed the barrier between an idea and a global product.

The uncomfortable follow-on is that the barrier came down for everyone. The compute needed to train or run a face-swap or voice-clone model is rented by the minute, from the same infrastructure market, at consumer prices. There is no hardware to buy and no specialist skill required — the tooling is packaged.

That is the honest bridge between the two projects: it isn't that AI got smarter, it's that forgery got cheap and distribution got free.

Volume reflects it. Europol's IOCTA 2025 cites a projection of roughly 8 million deepfakes shared online in 2025, against about 500,000 in 2023.

## 3. Harm One: Scam Calls and Impersonation Fraud

The single largest documented loss remains the Arup case — a finance employee in Hong Kong joined a video conference in February 2024 where every other participant was synthetic, and authorised 15 transfers totalling roughly US$25.6 million (confirmed by Hong Kong Police; acknowledged publicly by Arup in May 2024).

At consumer scale the same technology becomes the "family emergency" call. The FBI's IC3 report published in April 2026 added an AI-related descriptor for the first time in the report's history, logging 22,364 complaints and US$893.35 million in adjusted losses for 2025.

Surfshark's April 2026 study, built from the AI Incident Database, Resemble.AI and OECD records, puts documented global deepfake fraud losses at about US$2.19 billion between January 2019 and March 2026 — with roughly US$1.65 billion of that in 2025 alone. Social media is the single largest origin of reported losses.

## 4. Harm Two: Fake News and Manufactured Credibility

The financial number understates the problem, because the most damaging deepfakes don't take money — they take belief.

Two examples we used. In December 2025, following a UK earthquake, a synthetic image of a collapsed bridge circulated widely enough to contribute to train cancellations. And in January 2026, the Bombay Stock Exchange issued a formal advisory about a fabricated video of its Managing Director and CEO, Sundararaman Ramamurthy, offering stock recommendations and promising "supernormal profits" through a WhatsApp channel. The exchange worked with platforms to remove it and had to issue a second advisory on 8 March 2026 when the same video resurfaced.

This is the mechanism that matters for markets and public opinion: the credibility of a fake claim is borrowed from a real, trusted face. FINRA's 2026 Regulatory Oversight Report flags AI-generated voices and deepfake threats explicitly and requires member firms to run risk-based compliance programmes addressing them.

## 5. Harm Three: Non-Consensual Intimate Imagery

Financial fraud is the most reported category, not the most common one. The dominant real-world use of face-swapping technology since it appeared has been fabricated intimate imagery of real people without their consent — overwhelmingly of women, and including minors.

The US response is the TAKE IT DOWN Act (Pub. L. No. 119–12). Its criminal provisions took effect on signing; the platform obligations became enforceable on 19 May 2026. Covered platforms — any service primarily hosting user-generated content, not just large social networks — must provide an accessible removal-request mechanism and remove the material and known identical copies within 48 hours. The FTC enforces it; Chairman Ferguson sent warning letters on 11 May 2026 to Alphabet, Amazon, Apple, Automattic, Bumble, Discord, Match Group, Meta, Microsoft, Pinterest, Reddit, SmugMug, Snapchat, TikTok and X. Civil penalties run to $53,088 per violation.

**Handling note for the video:** we cover this factually and briefly. No examples, no names, no imagery.

## 6. Why "Just Look Closer" Fails

The instinctive defence is detection. The evidence says detection is the weakest link.

- iProov's Threat Intelligence Report 2025 found that only 0.1% of participants could reliably distinguish real from AI-generated content.
- Peer-reviewed work puts human accuracy on high-quality fakes at close to chance, while about 60% of people are confident they would do better than that.
- Automated detectors that reach up to ~96% accuracy in lab conditions lose roughly 45–50% of that accuracy in real-world deployment.
- Entrust's 2026 Identity Fraud Report (published 18 November 2025, drawing on more than a billion identity verifications across 195 countries) found deepfakes now drive 1 in 5 biometric fraud attempts.

The conclusion we build the video around: if perception fails and detection degrades, the defence has to move to process — provenance on the content, and verification on the human side.

## 7. The Policy Response, as of August 2026

**EU.** Article 50 of the AI Act (Regulation (EU) 2024/1689) became applicable on **2 August 2026** — eight days before this project was submitted. It requires four disclosures: that a person is interacting with an AI system; that synthetic content is machine-readably marked; that emotion-recognition or biometric-categorisation systems are in use; and that deepfakes and AI-generated text published on matters of public interest are labelled. The Commission adopted final guidelines on 20 July 2026 and confirmed the Code of Practice on Transparency of AI-Generated Content as adequate. Penalties reach €15 million or 3% of worldwide annual turnover. Content generated before 2 August is not retroactively covered.

**US.** No general federal deepfake statute. TAKE IT DOWN covers NCII specifically; the FTC and SEC address fraud and market manipulation through existing authority; 47 states have enacted deepfake legislation, roughly 169 laws since 2022 (MultiState).

**Practical layer.** Provenance and watermarking standards work in the opposite direction to detection: instead of proving something is fake, they attach a signed trail proving something is genuine. Plus the free control that stops the Arup attack — out-of-band verification. Hang up, call back on a number you already had, agree a family code word.

## 8. A Note on the Numbers (Read This Before Quoting Anything)

This topic has a serious data-quality problem, and it is worth flagging in the reflection.

Vendor and marketing blogs quote growth figures of 900%, 1,210%, 2,137%, and 3,892% — measured over different windows, on different denominators, and mutually inconsistent. Several trace back to the same unsourced press release. Others present forecasts as measurements (e.g. Deloitte's $40 billion by 2027 is a projection, not a recorded loss).

**What we used, and why:**

| Figure | Source | Why we trusted it |
|---|---|---|
| $893.35M, 22,364 complaints (2025) | FBI IC3, published April 2026 | Government reporting, defined category, stated window |
| $2.19B total / $1.65B in 2025 | Surfshark, April 2026 | Built on public incident records; methodology disclosed |
| 1 in 5 biometric fraud attempts | Entrust 2026 Identity Fraud Report | Named dataset, >1B verifications, stated date |
| $25.6M Arup loss | Hong Kong Police / Arup statement | Confirmed by the victim organisation |
| 48-hour removal / 2 Aug 2026 | FTC and European Commission | Primary legal sources |

**What we rejected:** every four-digit "surge" percentage, and any total presented without a measurement window. We also treat all loss totals as undercounts — congressional analysis suggests fewer than 5% of voice-clone victims ever report.

This mirrors the call we made in our last project, where we used the 33% AWS market-share figure over the 98% figure circulating online, because the latter measured website tracking rather than cloud spending.
