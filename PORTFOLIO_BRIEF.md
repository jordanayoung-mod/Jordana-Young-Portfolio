# PORTFOLIO_BRIEF.md

Shared brief for every assistant working on Jordana Young's UX research portfolio (Grok Bot "Portfolio Collaborator", Claude, and others).

## How to use this file
- This file is the source of truth. Use the hero, metrics, and case study text below exactly as written unless Jordana approves a change.
- Suggest changes to Jordana; she relays them to the Portfolio Collaborator, which merges approved changes here.
- Follow the voice profile for anything written in Jordana's name.

Site: https://jordanayoung-mod.github.io/Jordana-Young-Portfolio/

## Voice profile
- Synthesizer who joins dots between what people say and what they do.
- Ends in clear action/imperative.
- Specific, experience-recreating language over vague labels.
- Avoid em dashes, "it's not about X it's about Y", platitudes, slang, performative reflection.
- Reports lead with recommendation/outcome; short and scannable while preserving the "so what" and the how.
- Explicit connectors, assertive tone.

## Hero
- Eyebrow: SENIOR UX RESEARCHER · AI & ENTERPRISE
- Name: Jordana Young
- Bio: I study how people build, test, and trust AI agents, and I build the AI tools that speed up research. 20 years of mixed-methods research at Microsoft, Meta, SodaStream (PepsiCo), and Ipsos.
- CTAs: 6 case studies | Research ops | Outreach and training | Download PDF
- Canonical PDF only: the eyebrow and every page footer say "Senior Design Researcher, User Science". The site hero stays as written above.

## Metrics strip (never generic labels like "People studied" or "Faster insights")
- n=9,000 — choice study behind Instagram Shops personalized product page
- +36% — weekly Express Wi-Fi registrations in Delhi
- 2 — factories built after a SodaStream ethnography
- ILLUMI — UserTesting Award 2026
- 21 — published studies on AI agents at Microsoft

On screen the first, second, third, and fifth stay in the strip, and ILLUMI stays in the hero badge. The printed page 1 shows all five in the strip, and the badge is an image.

## Source of truth for case studies (Option A, approved)
The bullet cards on the site are the long-form case studies. The prose paragraphs below are the short form for the PDF summary line and for cover letters. Each card title carries a one-line summary taken from the outcome of that prose, then the approved role line. The role line is separate from the case study text.

Order on the site and in both PDFs: agent readiness first, then the other Microsoft studies, then Meta, then SodaStream.

## Case studies (use these exact versions)

### 1. Microsoft · Copilot Studio — Agent readiness (2025–2026)
How do teams decide an AI agent is ready to ship?
Agents entered critical work faster than teams could check them. Thirty-five builder interviews and more than 170 jobs to be done showed the split: debugging and evaluation are different jobs owned by different people. Release decisions were made by consensus, not metrics. Many failures could not be reproduced after model drift. The work defined the evaluation controls. Debugging support was prioritized. Quality and safety criteria were adopted by product, security, and governance. Teams now have a shared way to decide readiness.
Card summary: Teams now have a shared way to decide readiness.
Role line: I led the research that set the quality and safety criteria product, security and governance adopted, giving teams one shared way to decide an agent is ready to ship.

### 2. Microsoft · Copilot Studio — Understanding evaluation results (2025–2026)
Can builders understand an AI evaluation result?
Features shipped faster than traditional studies could run. Tests with builders in four countries showed the stall. Everyone could start an evaluation. Most stopped at the results. They saw pass or fail but not why or what to do next. Switching views repeated work and added cost. The fixes made pass/fail visible with explanation, added severity, re-ran only failed prompts, and placed results beside configuration. Builders can now act on a result instead of guessing.
Card summary: Builders can now act on a result instead of guessing.
Role line: I led the research that made builders able to act on an evaluation result: pass/fail with explanation, severity, and re-runs of failed prompts only.

### 3. Microsoft · Copilot Studio — Security ownership (2025)
What do builders need to own security for AI agents?
Developers without security training were asked to catch risks early. Ten hours of interviews showed the mismatch. Builders think in threat levels, not protection levels. They confused real-time and historical status. They learned of threats by email, often days late. The product shifted to threat-based severity, a clear real-time versus historical split, a shared workspace, and all permissions editable in the UI. Builders can now catch risks in the flow of their work.
Card summary: Builders can now catch risks in the flow of their work.
Role line: I led the research that shifted the product to threat-based severity and in-flow alerts, so builders catch risks while they work instead of days later by email.
Site method line, long form: "Synthesis of internal studies and 13 external papers." Interview and participant sample sizes stay. The count of internal studies is not published.

### 4. Meta · Instagram Shops (2020–2023)
Which product details make someone buy?
One page layout served every category. Engineering planned an ML dynamic display but did not know which variables to model. Twelve interviews showed what people said they wanted. A discrete choice survey (n=9,000, 17 variables) showed what they actually chose. Three fashion-specific variables and six cross-category value variables drove conversion. A price guarantee did not. Those nine variables were prioritized in model training. The page became a personalized dynamic display. The price guarantee was deprioritized.
Card summary: The page became a personalized dynamic display. The price guarantee was deprioritized.
Role line: I led the research that picked the nine variables the ML team trained on, which turned one fixed page layout into a personalized dynamic display and killed the price guarantee.

### 5. Meta · Express Wi-Fi, Delhi (2020–2023)
Why weren't people in Delhi using free Wi-Fi?
Usage sat far below forecast. Eighty-five percent of users were men 18–36, and data could not explain the gap. Interviews and mapping showed the barriers: registration demanded private ID documents many people lacked, the form was too literacy-heavy on feature phones, and the network served the street rather than the home. Registration was simplified, Sign in with Facebook was added, the form was redesigned around icons, and access points moved toward residential areas. Weekly registrations rose 36 percent.
Card summary: Weekly registrations rose 36 percent.
Role line: I led the research that removed the ID barrier, redesigned registration around icons and moved access points toward homes, lifting weekly registrations 36 percent.

### 6. SodaStream · PepsiCo (2017–2020)
Why do people stop refilling?
Earlier work had not found drivers the business could act on. In-home ethnography showed the mismatch. People need two or three bottles already chilling and two or three refills to form the habit. Machines shipped with one of each. Empties were forgotten in car trunks. Gas felt like a commodity. A quick-connect cylinder and new valve were patented. A new machine was built around them. Two factories opened. Multi-bottle sets and expanded subscriptions followed.
Card summary: A new machine was built around them. Two factories opened.
Role line: I led the ethnography behind a patented quick-connect cylinder, a new machine and two new factories.

## Approved decisions (Nov 19, 2026)
Jordana approved these for the Canonical Senior Design Researcher application. The build is PR #1. Do not merge until she says so.

Shipped on the site and in both PDFs:
- IIEX "From Hype to Human" placeholder row is hidden. The talk card stays. Takeaways are not invented.
- Layout: the mobile study-automation steps are fully visible, the choice-study table shows Option C, the mobile nav has a section menu, and stat text does not break mid-word.
- Link preview: og:title, og:description (the approved bio), og:image (the hero photo at an absolute URL), Twitter card tags, and a favicon.
- The tools section is renamed Research ops. Order: shared skills library, rapid-test template, peer review process, study automation, then the individual tools. No adoption numbers. Impact Bot is a log that ties research to the product decisions it changed.
- Microsoft stat boxes show outcomes. Agent readiness: adopted by product, security and governance. Evaluation results: rapid-test template adopted by the team. Security: threat-based severity recommended, because the impact text says recommended, not adopted.
- Agent readiness is case study 1. The others are renumbered. Long-form bullets stay, except the confidentiality edits below.
- Each card has the summary line and the role line above, under the title.
- Futures is renamed Outreach and training. Order: IIEX talk, UXR Days talk, 4-day leadership workshop, 3-day design sprint, then essays and trend work.
- Two schematics: an illustrative JTBD theme map (170+ jobs, 11 themes, counts labeled illustrative) and an evaluation results before and after. No product screenshots.
- Closing line: Building research into how your product teams decide? Email me.
- Education narrative is approved and sits with the BSc Biological Sciences entry. Wording below.
- Hero statement, sub copy, and the on-screen metrics strip are unchanged. Hero CTAs now say Research ops and Outreach and training, because those sections were renamed.
- Print: landscape A4. General file `Jordana-Young-UX-Research-Portfolio.pdf`. Canonical file `Jordana-Young-Canonical-Design-Research-Portfolio.pdf`, identical except the eyebrow and footer title. Page 1 is the hero, all five metrics, and the "How each case study reads" explainer. The hero button row is hidden in print only. One case study per page. Research ops is condensed and ordered by adoption. Outreach and training is one page with no placeholders. Experience, the Methods tag cloud, education, and the closing CTA, with email and LinkedIn linked, share the last page. Footer: Jordana Young · [title] · jordanayoung@gmail.com · n/N. The ILLUMI badge is an image with alt text.
- The case-study question subtitle under each title is removed on the site and in print. The one-line summary from the prose replaces it.
- In Understanding evaluation results, the impact line ends at "results beside configuration." The stray word "handoff." is removed on the site and in both PDFs.
- SodaStream keeps "Pink cylinder for brand recognition."
- Shared skills library description no longer lists skill file names. Human Value Add Assessor no longer lists the three-model pipeline or the "98-attribute rubric in 8 categories." The separate UserTesting MCP server card is removed. These cuts are on the site and in print.
- In print, the study-automation demo player is replaced by one clickable line: Watch the demo: jordanayoung-mod.github.io/Jordana-Young-Portfolio. The player stays on the site.
- Outreach and training no longer shows the Assumption / With AI / What if table, the Volume to Human value list, or the trailing STEEP sentence. Image captions and the Express Wi-Fi screenshots stay.
- The Methods tag cloud on Experience stays, on the site and in both PDFs.

Education narrative (approved):
"I trained as a biologist, with a minor in business studies, so I learned to design experiments and trust evidence over assumption. The business side showed me where that evidence changes decisions, so I took the scientific method into consumer research at Kantar and have applied it to products ever since."

Confidentiality, approved. Old wording, then new:
- "Workflow trace views prioritized on the roadmap for debugging." / "Trace views were prioritized for debugging." → "Debugging support prioritized." / "Debugging support was prioritized." No roadmap.
- "Switching views re-ran the model, adding compute cost." / "Switching views re-ran the model and raised compute cost." → "Switching views repeated work and added cost." No model.
- "Framing friction as compute cost brought engineering on board." → "Framing the friction as repeated work and added cost brought engineering on board." No compute architecture.
- "Synthesis of 6 internal studies and 13 external papers." → "Synthesis of internal studies and 13 external papers." Interview and participant sample sizes stay.

## Pending
- Item 1. IIEX takeaways. Jordana will send three. The placeholder row stays hidden until then.
- Item 5. Open-source the Human Grade Benchmark Kit as its own public repo. Jordana confirmed the IP is clear. The kit's files still need to come from her. It is not linked from the site yet.

## Known site issues (as of Nov 19, 2026)
- The Meta timeline gap and the missing case study labels were already fixed on the live site before this change. Both are removed from this list.
- IIEX placeholders are not visible. They are pending content, listed above.

## Current target: Canonical, Senior Design Researcher (User Science team, remote EMEA)
What the role weighs: research ops and scalability, integrating research into product and engineering decision flows, organizational change, learning culture and training, open-source and technical curiosity, visual and information design, turning chaos into clarity (knowledge systems), storytelling, strong academic record or a compelling alternative-path narrative.

Tailoring plan:
1. Lead with research ops: done on the site, without adoption numbers. Study automation, the shared skills library, the rapid-test template, peer review, and Impact Bot as a decision log.
2. Make organizational change explicit in the stat boxes: done. Agent readiness criteria adopted by product, security, and governance.
3. Frame synthesis work as a knowledge system: the illustrative JTBD theme map is on the agent readiness card. Say "internal studies and 13 papers", not a count of internal studies.
4. Address open source: pending. Publish the Human Grade Benchmark Kit when Jordana supplies the files.
5. Add information-design visuals: both schematics are done. No product screenshots.
6. Education narrative: approved and on the site. Exact wording above.
7. Use "Senior Design Researcher, User Science" on the Canonical PDF eyebrow and footer, and in the cover letter. Keep the AI-focused hero on the site and on the general PDF.
