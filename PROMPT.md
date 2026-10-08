Build a single-page educational website titled "After the Deal: Making Mergers Work" in this repository, then commit and push it.

TOPIC
Post-merger integration (PMI): what happens after an M&A deal is signed and closed, and why integration is where most of a merger's value is won or lost. Audience: business students and early-career professionals. Tone: clear, professional, practical — a course companion, not a sales page. All site copy in plain English, short paragraphs, active voice.

FILES TO CREATE
- index.html — the whole site, with inline CSS and vanilla JavaScript. No frameworks, no build step, no dependencies except Google Fonts.
- README.md — short description of the project and how to view it (open index.html, or GitHub Pages).
- PROMPT.md — a copy of this prompt.

TECHNICAL REQUIREMENTS
- Responsive: works at 360px phone width with no horizontal scroll.
- Light and dark mode via prefers-color-scheme; all colors as CSS custom properties on :root.
- Accessible: semantic HTML (header, nav, main, section, footer), good contrast, keyboard-usable controls, proper ARIA on tabs (role="tablist"/"tab"/"tabpanel", arrow-key navigation) and on the progress bar.
- Must work on GitHub Pages as-is (relative paths only).

VISUAL DIRECTION
Editorial and finance-flavored: a serif display font for headings (Fraunces) and a clean sans for body (Inter). Restrained palette — deep ink navy, warm off-white paper, one brass/amber accent used sparingly. Generous whitespace, thin rules between sections, numbered section labels (01 —, 02 —, …). Sticky top nav with anchor links (hidden on mobile).

SECTIONS (in this order)
1. Hero — title, thesis line "Signing the deal is the beginning, not the end", a short intro, and a strip of three stats: 4 phases, 7 pillars, 100 days.
2. Why mergers fail — the HBR finding that 70–90% of acquisitions fail to deliver expected value (Christensen, Alton, Rising & Waldeck, "The Big Idea: The New M&A Playbook", HBR, March 2011), shown as a large stat block, plus a numbered list of causes: overestimated synergies, culture clash, talent loss, slow decisions, poor communication, customer neglect.
3. Integration timeline — interactive tabs for four phases: Pre-close planning, Day 1, First 100 days, Beyond 100 days. Each panel shows an objective and 5–6 key actions (e.g. set up the IMO, cultural due diligence, avoid gun-jumping, Day 1 comms, TSAs, quick-win synergies, org design, IT migration, exiting TSAs, closing the IMO, reviewing results against the deal case).
4. The seven pillars — cards: Strategy & synergies, Leadership & governance (IMO), People & talent, Culture, Operations & IT, Customers & revenue, Communication.
5. Case studies — three factual cases, each with "What happened" and "The lesson" and a success/failure tag:
   - Daimler-Benz & Chrysler (1998): "merger of equals" undone by culture clash; Chrysler sold in 2007.
   - AOL & Time Warner (2000): synergies never materialised; huge goodwill write-down in 2002.
   - Disney & Pixar (2006): integration that deliberately protected Pixar's creative culture and leadership.
6. Integration readiness checklist — 12 checkbox items with a live score (x / 12), a progress bar that changes color, and a verdict sentence that updates with the score; plus a reset button. Keep state in memory only.
7. Common pitfalls — accordion (<details>) of 6 pitfalls, each with an "Instead:" fix: treating closing as the finish line, integrating everything by default, letting uncertainty drag on, ignoring culture, forgetting the customer, not measuring results.
8. Glossary — synergy, Integration Management Office (IMO), Day 1, Transition Service Agreement (TSA), earn-out, goodwill, cultural due diligence, retention bonus.
9. Footer — note that this is an educational project (not financial or legal advice) and a references list.

CONTENT RULES
Only use well-established, verifiable facts. Do not invent statistics, quotes or figures.

WHEN DONE
1. Open index.html and check it renders, the tabs and checklist work, and there are no console errors.
2. Commit with the message "Add After the Deal website" and push to main.
3. Tell me how to enable GitHub Pages (Settings → Pages → Deploy from branch → main / root).
