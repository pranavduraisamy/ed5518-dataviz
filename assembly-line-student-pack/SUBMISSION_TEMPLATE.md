# Review-friendly `replay.html` outline

Your deliverable is **one self-contained HTML file**, not a PDF, slide deck, notebook, or hosted dashboard alone. It must run when opened with `file:///…/replay.html` with Wi-Fi disconnected. An online URL is optional.

Recommended layout (you may design a better one):

1. **Top/summary:** Your strongest finding in one sentence; what the engineering supervisor should do next; explicit confidence.
2. **Replay stage (essential, interactive):** Four station blocks, three finite buffers, timestamped state and queue occupancy; working **Play/Pause** and **seek** controls, with a display of the selected time window. Let a reviewer jump between at least three consequential episodes. An animated chart without meaningful linkage to the factory events does not count.
3. **Evidence inspector:** On selecting a moment, expose its date/time, observed values and relevant source/fields. Be clear about `time` vs `received_at`, event duplicates, minute-granularity buffers and interpolated assumptions.
4. **Investigation and alternatives:** `claim | source (path + record/time/query) | confidence + why` table, two rejected hypotheses, what evidence might revive them.
5. **Decision:** One practical next-shift intervention, risk/guardrails, success metric, and what observation would reverse your recommendation.

**Technical requirements:** Inline CSS and JavaScript only. Embed all data required to render and operate the submission in the document, e.g. `<script type="application/json" id="dataset">...</script>` or a JavaScript constant (with safely encoded content). No fetches, local CSV reads, CDNs, web fonts, external images, package installs, or web server. You may preprocess with Python or an agent; the final HTML must not rely on those tools. Opening the HTML should immediately show a useful default view. Offline test it in a new browser profile with network disabled.

**Minimum acceptance check:** The reviewer can save your single file to any directory, open it without the source datasets or internet, press Play, Pause, move the time slider, see meaningful changes, navigate three different intervals, and inspect your evidence. If one of these fails, the replay deliverable is incomplete.
