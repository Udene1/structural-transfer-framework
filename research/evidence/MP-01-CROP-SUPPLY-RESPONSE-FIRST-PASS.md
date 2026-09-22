# MP-01 — Crop-Level Supply Response: First Empirical Pass

## Status

Preliminary empirical evidence. This artifact narrows the supply-side investigation; it does not establish a causal explanation for Nigeria's 2025 disinflation.

## What the official 2025 agricultural data actually show

The 2025 Wet Season Agricultural Performance Survey from NAERLS/FMAFS provides a useful first check because it reports both cultivated land and production estimates for 2024 and 2025.

| Crop | Land area 2024 (ha) | Land area 2025 (ha) | Area change | Production 2024 (MT) | Production 2025 (MT) | Production change |
|---|---:|---:|---:|---:|---:|---:|
| Rice | 4,572,945 | 4,636,940 | +1.4% | 9,129,908 | 9,372,329 | +2.7% |
| Maize | 5,063,032 | 5,073,573 | +0.21% | 11,216,837 | 11,441,215 | +2.0% |
| Cowpea | 4,834,377 | 4,856,200 | +0.45% | 4,093,945 | 4,284,264 | +4.6% |
| Yam | 6,335,595 | 6,448,455 | +1.78% | 54,577,973 | 55,784,099 | +2.21% |
| Cassava | 9,281,807 | 9,415,728 | +1.44% | 64,361,225 | 65,385,978 | +1.59% |
| Sorghum | 5,246,412 | 5,321,964 | +1.44% | 6,416,975 | 6,501,048 | +1.3% |
| Millet | 1,547,776 | 1,562,660 | +0.96% | 1,546,293 | 1,548,409 | +0.14% |

Source: 2025 Wet Season Agricultural Performance Survey, NAERLS/FMAFS. citeturn2search2

### First interpretation

The data are interesting but already modify the original hypothesis.

There was **expanded cultivated area**, but for the major staples the increase in area was generally modest. Production increases were also modest for several crops. Cowpea shows a larger production increase (+4.6%) than its area increase (+0.45%), implying that yield or other production factors account for much of its change.

Therefore, the evidence currently supports:

> agricultural supply increased in 2025

more strongly than it supports:

> a large wave of additional farmers entered production because 2024 prices were unusually attractive.

The second proposition still requires direct evidence.

## Important distinction: area response versus farmer-entry response

The official survey reports land area, but the current evidence does not yet establish that the number of farmers increased because of high 2024 prices.

A farmer can increase total cultivated area without:
- entering agriculture for the first time;
- hiring additional farmers;
- changing crops;
- increasing the number of farming households.

Conversely, more farmers could participate without producing much additional output if average farm size fell.

So the causal link we need is:

**2024 crop price / expected return → farmer or acreage decision → 2025 production**

not merely:

**2024 price → 2025 production.**

The 2024 APS provides a useful baseline: it describes Nigerian production as dominated by smallholders and reports average cultivated areas for major crops, while 60% of surveyed farmers expected 2024 output to be at least 25% above 2023. citeturn1search5

That expectation is not evidence of a 2025 incentive response. It is a baseline observation that helps us avoid confusing expected output, realized output, and later price movements.

## The market data opportunity is unusually strong

The World Bank/NBS High Frequency Crowdsourced Prices dataset covers 2024–2025 and contains **farmgate, wholesale and retail prices** for yellow and white maize, garri, yam, imported and local rice, sorghum, white and brown beans, and soybeans across all 36 states and the FCT, with geographic information down to states and LGAs. The data were collected at high frequency and are specifically suited to examining short-term shocks, seasonality and spatial price variation. citeturn1search0

This is much closer to the "underground" layer we were looking for than national CPI alone.

It gives us a possible empirical chain:

**farmgate price → wholesale price → retail price**

and allows us to ask whether price changes began at the farm/wholesale level when new supply arrived, rather than simply observing the final CPI.

## A competing explanation is already visible: imports

USDA's March 2025 Nigeria Grain and Feed Annual projected rice production at 7.9 million tonnes for MY2025/26 while expecting rice imports to rise 16% to 2.8 million tonnes. It also expected lower-priced informal rice imports to put downward pressure on domestic rice prices. citeturn0search2

This matters because a fall in rice prices cannot automatically be attributed to domestic Nigerian farmers producing more.

For rice at least, we need to separate:

**domestic production effect**
from
**import-supply effect**
from
**exchange-rate effect**
from
**seasonality.**

## Another important identification issue: the CPI itself changed

NBS rebased the CPI with a 2023 weight reference period and 2024 price base, and the rebased system contains separate food, imported-food and farm-produce indices. citeturn1search3

Therefore the research should not use the raw headline inflation series as the sole dependent variable for a 2024→2025 causal comparison.

For this branch, item-level and market-level price series are preferable.

## Current evidence matrix

| Proposition | Current evidence | Status |
|---|---|---|
| 2025 agricultural production increased | NAERLS 2025 APS reports increases across major staples | Supported as an observation |
| Cultivated area increased | NAERLS reports modest area increases for major staples | Supported as an observation |
| More farmers entered because 2024 prices were high | No direct evidence established yet | Open |
| Higher 2024 prices caused the area increase | Not established | Open |
| 2025 harvest caused local price declines | Crop/market reports and APS point toward improved supply, but timing/causal isolation incomplete | Plausible, not established |
| Imports contributed to lower food prices | Evidence exists, including rice import expectations and FAO/NBS evidence | Supported as a competing mechanism |
| Supply-side changes materially contributed to national food disinflation | Not yet quantified | Open |
| Monetary tightening caused the food-price decline | Not established by this branch | Open |

## Research implication

The first-pass evidence does **not** justify replacing the monetary explanation with a farmer-incentive explanation.

Instead it gives us a better empirical question:

> **When Nigerian food prices declined during 2025, did the decline originate in increased domestic physical supply, increased imports, seasonal harvests, lower distribution costs, weaker demand, or some combination—and how large was each contribution?**

Only after answering that can the monetary-policy evidence be interpreted against the competing food-supply mechanism.

## Next operation

Use the HFCP 2024–2025 dataset to reconstruct, for maize, rice, garri/cassava, beans and selected other staples:

1. 2024 farmgate price path.
2. 2025 farmgate price path.
3. Wholesale price path.
4. Retail price path.
5. Geographic dispersion.
6. Timing of major harvest periods.
7. Timing of price reversals.
8. Where possible, production/area changes.
9. Import timing and volumes.
10. Whether farmgate prices moved before retail prices.

The strongest test is temporal and spatial:

> **If new domestic supply is driving the price decline, where and when should the price reversal appear first?**

That prediction can be checked rather than assumed.
