# Extract field guide

All local timestamps are IST (UTC+05:30); timestamp precision is one second. Synthetic training extract.
TrackMES serial_progress: one row when a stage COMPLETES; no reliable start timestamp. A serial can cross shift boundaries.
EdgePLC station_states: state changes as captured by controller; repeated event_id can be network resends. RUN is actively processing. BLOCKED means completed output has nowhere to transfer. STARVED means there is no input. HOLD is an external pause. SETUP is operator-entered check. IDLE means no start yet.
EdgePLC buffers: once-per-minute physical queue count snapshots, not a complete event log. B12 is between ST10/ST20, etc.
Q-Lab leak_tests: one row per tester attempt, a second test with test_no=2 uses tester capacity and is not a second product. RECHECK means hold disposition / ambiguous reading rather than confirmed defective hardware.
TrackMES shift_kpi: a derivative management export; stage completions are different from packed counts.
SupplyDesk label_movements: transaction and posting timestamps reflect distinct business actions; blanks are not necessarily missing physical materials.
Shift boundary notes: the line does not process overnight; a few partially completed items may be left in progress.
