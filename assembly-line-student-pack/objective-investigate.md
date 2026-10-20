# Exercise 1 — Find the Failure Nobody Asked About
**For:** Production manager / engineering design leader · **Suggested time:** 3 hours · **AI tools:** unrestricted.

You are reviewing a short extract from Varuna Motion Components Pvt Ltd, which builds small industrial pump-drive module at Sriperumbudur, Tamil Nadu. Production planning wants to know which single machine merits an improvement budget after a throughput dip. The most circulated dashboard points toward the press.

The question may be framed correctly or not. You have access to `data/` from several systems and may request a 10-minute interview with a person in `data/people/`. Do not assume that every anomaly is causal or that every KPI measures what its name suggests.

**Your task:** Discover the most consequential **question that wasn't asked**. Show something meaningful about the physical process, not just statistical surprise. Make a defensible decision: what would you change first, or what would you measure before approving action? A novel result that survives a serious attempt at refutation beats three attractive charts.

Suggested starting point: the production request in `data/support/`. Use at least two genuinely independent evidence channels for material conclusions.

## Evidence obligation
Include a compact table with `claim | source (path + fields, row/time or reproducible query) | confidence (high/medium/low + why)`. Add at least **two rejected hypotheses**, with what evidence would make you reconsider them. Separate observation from inference. Cite useful counterevidence; do not overstate certainty. You may use AI agents, code, spreadsheets, interviews (request instructor role-play), and collaborate, but are accountable for verification.

**Required submission: a single self-contained `replay.html` file.** It must open locally from disk in a browser **without internet access**, without a server, and without fetching `data/` files, external scripts, fonts, images, or stylesheets. Embed the necessary data and all CSS/JavaScript/images in the HTML. A functional, time-based replay is mandatory: show station activity and buffer occupancy over time with at least play/pause and a seekable timeline or equivalent working temporal navigation (not merely a slideshow of static charts). Make relevant source timestamps and data limitations visible. Do not infer sub-minute precision from minute-sampled buffers. Include your investigation, conclusions, evidence table, rejected hypotheses and recommendations in the same HTML; make it easy for a reviewer to skim before exploring.

**Optional hosting:** You may additionally share a public URL to the exact same HTML, but a hosted link **does not replace** the `replay.html` file. The file must still work fully offline. If both exercises are assigned, **one HTML may satisfy both** so long as it addresses both objectives. If only one exercise is assigned, submit one HTML addressing that exercise with a meaningful replay.

Your tools and AI prompts need not be reported; your claims and checks do. No PDF is required for this case-study submission.

The materials are synthetic. You're not required to discover any particular hidden explanation. An evidence-backed disagreement with management, or a defensible request for a missing measurement, is a legitimate result.
