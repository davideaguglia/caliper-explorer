# Caliper Share Explorer

Interactive bottom-up model of the OE brake caliper market (light vehicles): estimated unit and value shares by region and by supplier owner group (Western, Japanese/Korean, Chinese), with scenario levers.

**Live page:** https://davideaguglia.github.io/caliper-explorer/ (once GitHub Pages is enabled)

## Method
- 2025 light-vehicle production for ~20 OEM groups (≈85% of the market) plus regional residuals (rounded approximations).
- Calipers per car = 4 − 2 × rear-drum share (cars with rear drum brakes have calipers only at the front).
- Each OEM-region row is split across caliper suppliers; suppliers are grouped by controlling owner (e.g. BWI = Chinese, owned by Luxshare; CBI counted inside Astemo).
- Indicative value uses illustrative prices per caliper.

## Scenario levers
- Sourcing assumptions at the least documented Chinese OEMs (low / base / high).
- Chinese brands' share of European production and how much of it is sourced from Chinese suppliers.
- BWI classified by owner (Chinese) or origin (Western).
- Units vs indicative value; rear-drum share by region.

## Caveats
Indicative, author's estimates. Group shares are roughly ±10 percentage points; most supplier splits are analyst estimates, and the page shows how much of the volume rests on confirmed supplier links. OE light vehicles only (no trucks, no aftermarket). Not investment advice and not an official market database.

The page is a single self-contained `index.html` (fonts from Google Fonts).
