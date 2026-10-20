# Synapses Services

Public services homepage for Synapses, featuring Still Home, a home-cleaning service in Metro Vancouver.

The services homepage is served from `/`, and Still Home is served from `/stillhome/`. Both pages use relative local assets and respect reduced-motion preferences. Still Home includes service information, scroll animations, and an estimate calculator that runs locally in the visitor's browser. The calculator creates a shareable summary; it does not submit a booking.

The Halloween offer runs October 19–25, 2026, in Vancouver time. For the example 3-bed, 2.5-bath home around 1,300 sq ft, the first deep clean is CA$319 instead of CA$369, with supplies included and a free redo of missed areas on the agreed checklist. Biweekly upkeep is CA$199. The calculator applies the quoted offer only to the matching home-size band, and restores standard first-clean pricing after the deadline. `stillhome/pricing.js` holds that policy.

Deploy the repository root with GitHub Pages. `CNAME` sets the custom domain to `services.synapses.cloud`, and `.nojekyll` keeps the static files unchanged.
