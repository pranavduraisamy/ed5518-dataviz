# PulseBoard Mapping v1.4, 2026-05-07
Data source: EdgePLC → PulseBoard shift export. Owner: reporting operations.

* `units_packed`: accepted units scanned out of ST40 during the 6-hour shift.
* `*_loss_min`: seconds where the station wasn't processing, comprising BLOCKED and HOLD (not STARVED); divided by 60. This number answers where time was not RUN, not necessarily which fault initiated the interruption.
* `*_setup_min`: operator-entered SETUP seconds, treated as planned / excluded from reported loss.
* `final_accept_pct`: packed / (packed + scrapped) in shift; *not* first-pass leak-test yield. Denominators differ when units are held between shifts.
* PLC events: `received_at` is server arrival, `time` is controller time. Replayed packets can repeat `event_id`.
Controller reason codes are not plantwide causal labels. See reporting analyst for exceptions to the mapping.
