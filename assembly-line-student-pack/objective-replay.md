# Exercise 2 — Replay a Factory That Changes Its Mind
**For:** Shift supervisor / industrial engineer · **Suggested time:** 4 hours · **AI tools:** unrestricted.

The shift supervisor wants a replay that explains **where work waits, where stations are starved or blocked, and when the constraint changes**. The plant has 4 stations and three finite buffers; the available files come from independent systems and do not all define time or production identically.

**Your task:** Construct a time-ordered visual explanation from `data/`. Show buffer occupancy and station activity, a timeline of at least **three contrasting windows** (including an apparently dramatic but benign or unresolved event), and the causal sequence implied by each window. Build a working in-browser time replay, with play/pause and a seekable timeline, that visibly changes with time. An attractive static storyboard or screenshots alone are **not** a replay. Do not smooth over missing scans or invent second-level precision from minute snapshots.

Choose at least one episode where a naive station-downtime ranking gives the wrong next action. What does the visualization add over an email that simply says which station to inspect? Recommend what the supervisor should do during the next shift, with thresholds and an alternative explanation.

## Evidence obligation
Include a compact table with `claim | source (path + fields, row/time or reproducible query) | confidence (high/medium/low + why)`. Add at least **two rejected hypotheses**, with what evidence would make you reconsider them. Separate observation from inference. Cite useful counterevidence; do not overstate certainty. You may use AI agents, code, spreadsheets, interviews (request instructor role-play), and collaborate, but are accountable for verification.

**Required submission: a single self-contained `replay.html` file.** It must open locally from disk in a browser **without internet access**, without a server, and without fetching `data/` files, external scripts, fonts, images, or stylesheets. Embed the necessary data and all CSS/JavaScript/images in the HTML. A functional, time-based replay is mandatory: show station activity and buffer occupancy over time with at least play/pause and a seekable timeline or equivalent working temporal navigation (not merely a slideshow of static charts). Make relevant source timestamps and data limitations visible. Do not infer sub-minute precision from minute-sampled buffers. Include your investigation, conclusions, evidence table, rejected hypotheses and recommendations in the same HTML; make it easy for a reviewer to skim before exploring.

**Optional hosting:** You may additionally share a public URL to the exact same HTML, but a hosted link **does not replace** the `replay.html` file. The file must still work fully offline. If both exercises are assigned, **one HTML may satisfy both** so long as it addresses both objectives. If only one exercise is assigned, submit one HTML addressing that exercise with a meaningful replay.

Your tools and AI prompts need not be reported; your claims and checks do. No PDF is required for this case-study submission.

The materials are synthetic. You're not required to discover any particular hidden explanation. An evidence-backed disagreement with management, or a defensible request for a missing measurement, is a legitimate result.
