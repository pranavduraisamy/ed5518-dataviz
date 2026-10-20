# Varuna Motion — analyst data room

**Fictional company and synthetic records.** All timestamps are India Standard Time.
Period: 2026-09-21 to 2026-10-02, 08:00–20:00 weekdays in two 6-hour shifts.
Product: small industrial pump-drive module; the line and data are described in `process/`.

## What is here
- `mes/serial_progress.csv`: station completion scans by serial (not a full time-in-state log).
- `mes/shift_kpi.csv`: management line summary.
- `plc/station_states.csv`: EdgePLC event transitions; check repeated IDs.
- `plc/buffers.csv`: minute buffer observations and sampled station states.
- `plc/press_temperature.csv`: monitoring sensor history.
- `quality/leak_tests.csv`: test attempts, including RECHECK.
- `materials/label_movements.csv`: stockroom operations ledger.
- `support/`: partial communications and requests.
- `people/`: possible interviewees (ask the instructor to role-play any one).
- `process/`: current documentation, which may be incomplete.

You may inspect datasets with spreadsheet, SQL, Python or an AI agent. Every conclusion should distinguish evidence from inference.
If you build a replay, label time resolution, any interpolation, and uncertainty rather than making event timestamps more precise than the sources.
