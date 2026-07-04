# Rebar Bid

A quick-bid estimator for concrete reinforcing steel (rebar).
It's a single, self-contained web page — no build step, no server, no dependencies to install.

## Use it

Open **`index.html`** in any modern browser (desktop or phone). That's it.

- **Add members** — footings, walls, piers/columns, slabs-on-grade, grade beams — and describe the bars either *by count* or *by spacing*.
- Pick a **bar shape** — straight, L-bend/dowel, hook, U-bar/stirrup, or closed tie — and enter leg lengths; cut length and weight are computed for you.
- Enter your **rates & markup** (steel price, crew wage, lap factor, stock length, contingency, overhead, profit, sales tax, coating).
- It calculates **installed weight, laps/splices, stock nesting, labor hours, sales tax, and the bid total** live.
- **Export** a Schedule of Values + weight summary to CSV, or **Print / Save as PDF** a customer-facing quote (your company header, itemized scope, subtotal/tax/total). Overhead and profit stay hidden on the printed quote.

## Notes

This replaces the arithmetic, not the takeoff — you read the drawings and enter the members.
It is **not a stamped estimate**, and it nests stock per-member (so ordering quantities are slightly
conservative and don't share offcuts across members the way full optimization software does).
