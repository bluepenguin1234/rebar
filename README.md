# Rebar Bid

A quick-bid estimator for concrete reinforcing steel (rebar) on **footings and walls**.
It's a single, self-contained web page — no build step, no server, no dependencies to install.

## Use it

Open **`index.html`** in any modern browser (desktop or phone). That's it.

- **Add members** — footings and walls — and describe the bars either *by count* or *by spacing*.
- Enter your **rates & markup** (steel price, crew wage, lap factor, stock length, contingency, overhead, profit, coating).
- It calculates **installed weight, laps/splices, stock nesting, labor hours, and the bid total** live.
- **Export** a Schedule of Values + weight summary to CSV.

## Notes

This replaces the arithmetic, not the takeoff — you read the drawings and enter the members.
It is **not a stamped estimate**, and it nests stock per-member (so ordering quantities are slightly
conservative and don't share offcuts across members the way full optimization software does).
