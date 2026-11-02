# Caliper Share Explorer

Interactive bottom-up model of the OE brake caliper market (light vehicles): estimated unit shares by region and by supplier owner group (Western, Japanese/Korean, Chinese), with scenario levers.

**Live page:** https://davideaguglia.github.io/caliper-explorer/ (once GitHub Pages is enabled)

## Method
- 2025 light-vehicle production for ~20 OEM groups (≈85% of the market) plus regional residuals (rounded approximations).
- Calipers per car = 4 − 2 × rear-drum share (cars with rear drum brakes have calipers only at the front).
- Each OEM-region row is split across caliper suppliers; suppliers are grouped by controlling owner (e.g. BWI = Chinese, owned by Luxshare; CBI counted inside Astemo).
- All shares are by units (calipers), not value.
- Market-size cross-check only: total calipers × one illustrative blended price (≈€34) ≈ €11bn, inside published $10–16bn estimates (not used as inputs).

## Scenario levers
- Sourcing assumptions at the least documented Chinese OEMs (low / base / high).
- Chinese brands' share of European production and how much of it is sourced from Chinese suppliers.

## Outlook (2026 → 2030 → 2036)
Scenario explorer, not a forecast. EMB cars in China = new vehicles × EMB share of new cars (the unit of the published anchor, capped at the EV share); outside China = new vehicles × EV share × EMB take-rate among EVs. EMB calipers are split between incumbent (Western, Japanese, Korean) and Chinese suppliers.
- Sourced anchors: EV share (IEA Global EV Outlook 2026, BNEF EVO 2026, EV Volumes); EMB in China <1% of new cars in 2026 and ≈15% by 2030 (Donghai Securities forecast).
- Assumptions (marked on the page): EMB take-rate outside China, Chinese suppliers' share of EMB, 2036 EMB take-rates, EV shares for Japan, Korea and Rest of World.
- Vehicle volumes held at 2025 levels; hydraulic supplier shares from today's model.
- Output: world caliper units by year split into hydraulic / EMB and incumbent / Chinese suppliers, plus a summary table.

## Caveats
Indicative, author's estimates. Group shares are roughly ±10 percentage points; most supplier splits are analyst estimates, and the page shows how much of the volume rests on confirmed supplier links. OE light vehicles only (no trucks, no aftermarket). Not investment advice and not an official market database.

The page is a single self-contained `index.html` (fonts from Google Fonts).
