# Spatialytics Groundwater

Drop a pin in Minnesota and get a screening read from live public layers:

- Nearby **County Well Index** wells (depth, aquifer code, static water level, official MWI log)
- **Water-table aquifer vulnerability** (High / Medium / Low)
- A plain-language score for excavation, a new domestic well, and shallow contamination risk

This replaces the broken `Farm-Groundwater` Next app (missing map components, three hardcoded Martin County cards, 2007 water levels). The old Dunnell / Sherburn / Fairmont sites are saved pins on top of live data.

## Use it

Open `index.html` or deploy the folder to Vercel as a static site.

Not a substitute for a licensed well contractor, county septic review, or a DNR appropriation review.

## Sources

- MGS / MDH County Well Index locations
- Minnesota Well Index logs
- Water-table aquifer vulnerability
- DNR Cooperative Groundwater Monitoring (linked)
- Minnesota Hydrogeology Atlas HG-03 (linked)
