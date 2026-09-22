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


## New evidence check: July 2024 → July 2025 commodity prices

The 2025 Wet Season Agricultural Performance Survey provides a particularly useful cross-check because it reports the same commodity prices across all six geopolitical zones.

For July 2024 versus July 2025 it reports:

- white maize: national mean ₦961/kg → ₦456/kg (**-52.5%**);
- milled rice: ₦1,501/kg → ₦982/kg (**-34.6%**);
- brown sorghum: ₦988/kg → ₦491/kg (**-50.2%**);
- brown cowpea: ₦2,035/kg → ₦1,114/kg (**-45.2%**).

The declines occur in every geopolitical zone for these commodities. citeturn0search4

This is important because the pattern is broader than a single local market anecdote. It is consistent with a nationwide supply/market-price change.

But it still does not identify the cause.

The same survey reports that 2025 rainfall was more favorable in some regions and created opportunities for multiple planting cycles, while irregular rainfall, dry spells, erosion and water stress continued to constrain production elsewhere. citeturn1view1

Therefore even the production increase has several possible sources. We cannot equate it with a price-induced farmer response.

## New evidence check: within-year 2025 market movement

The CBN's Q2 2025 Economic Report reports that many monitored agricultural commodity prices fell in Q2 relative to Q1. It attributes the movement primarily to improved supply for some staples, while noting that seasonality pushed prices upward for nine of the twenty monitored commodities. citeturn4search6

Examples from the same table:

- brown beans: Q1 → Q2 **-34.30%**;
- white beans: **-39.34%**;
- white garri: **-5.81%**;
- white maize: **-1.63%**;
- yellow maize: **-0.85%**;
- local rice: **-2.62%**;
- tomato: **-4.25%**.

At the same time, onions rose **23.95%**, yam rose **11.00%**, and palm oil rose **13.23%**. citeturn4search6

This heterogeneity is useful.

If a single national monetary mechanism were the only relevant mechanism, we would expect much less reason to see such crop-specific divergence. But we should not infer from this observation that monetary policy had no effect. It simply establishes that food-market mechanisms are heterogeneous and must be investigated at commodity level.

## New evidence check: the high-frequency dataset is suitable for the next test

The NBS/World Bank High Frequency Crowdsourced Prices dataset contains daily observations from December 1, 2024 through June 27, 2025 for ten staple commodities, with retail, wholesale and farmgate market segments, state and LGA identifiers, and urban/rural classification. It contains roughly 1.4–2.0 lakh observations for each major commodity. citeturn1view0turn3search3

The local-rice file alone contains 198,630 records and includes date, geopolitical zone, state, LGA, rural/urban sector, market type, market segment, price per kg and daily mean price. citeturn3search1

The dataset has an important limitation: it uses crowdsourcing. The World Bank/NBS metadata acknowledge self-selection/digital-competency bias, although the final cohort was spatially stratified and the data were checked against trained-enumerator observations. The validation metrics reportedly showed strong agreement in distribution and temporal movement. citeturn1view0

So it is appropriate for **market dynamics and timing**, but should not silently be treated as a probability sample of every transaction in Nigeria.

## A stronger causal clue from the CBN evidence

The CBN Q2 report explicitly says improved supply was the primary driver of declines in many monitored agricultural commodity prices, but also identifies seasonality as important. citeturn4search6

This gives us a useful empirical split:

**Observed:** agricultural commodity prices fell for many staples.

**Institutional interpretation:** improved supply was an important driver.

**Still unresolved for our research:** what generated the improved supply?

Possibilities include:
- larger planted area;
- higher yields;
- favorable rainfall;
- multiple planting cycles;
- improved inputs/practices;
- security;
- imports;
- policy interventions;
- normal seasonal harvest dynamics;
- some combination.

That is precisely where the user's farmer-incentive hypothesis needs to be tested rather than assumed.

## Revised hypothesis tree

We should now test three nested propositions separately:

### H1 — Supply mattered

2025 physical availability increased enough to reduce prices of important food commodities.

Current evidence: **substantial support**, especially from the commodity-price and agricultural-output observations.

### H2 — Domestic production was the main source of that additional supply

Current evidence: **plausible but unresolved**.

Imports and other supply channels remain material competitors.

### H3 — High 2024 prices caused a behavioral production response that materially generated the 2025 supply increase

Current evidence: **unresolved**.

The current production tables do not establish this behavioral link.

This decomposition is better than asking prematurely whether "farmers flooded the market."

## Next test

The next step is no longer simply to collect more national price statistics.

We need to identify **the first point in the supply chain where the price reversal appears**.

For each commodity:

**farmgate → wholesale → retail**

and across producing versus consuming regions.

If farmgate prices fall first in producing regions around harvest arrival, followed by wholesale and retail prices, that would be evidence consistent with a domestic-supply mechanism.

If retail prices fall without a corresponding farmgate movement, other explanations become more important.

If imported-rice prices fall alongside local-rice prices, import/FX competition becomes more important.

If prices fall at roughly the same time across crops with very different production cycles, a common macro factor becomes more plausible.

These are empirical discriminators, not conclusions.


## New investigation pass: what the price data can and cannot establish

The newly checked World Bank/NBS HFCP metadata confirms that the market-level dataset contains separate **farmgate, wholesale and retail** observations, not merely a single consumer price series. It covers ten staple commodities from December 1, 2024 through June 27, 2025, across all 36 states and the FCT. The pre-processed files contain very large numbers of daily observations—for example, 199,828 white-maize records, 198,630 local-rice records and 202,059 white-bean records. citeturn1search0turn1search2

This is exactly the structure needed to test the proposed supply-chain sequence:

**farmgate → wholesale → retail**

The metadata also confirms that the market-segment variable explicitly distinguishes Farmgate, Wholesale and Retail. citeturn1search3

### A useful new discriminator

The hypothesis is not simply:

> “food became cheaper because farmers produced more.”

The stronger test is:

> **Did the price reversal appear first at the producer/wholesale end of markets in locations and periods where additional supply should arrive?**

If yes, that would be evidence consistent with a physical-supply mechanism.

If retail prices fall substantially without an earlier farmgate/wholesale decline, the farmer-supply explanation becomes weaker and other mechanisms become more important.

If farmgate prices fall but production does not increase, we need to investigate inventories, imports, demand and seasonal market clearing.

If local and imported commodities move differently, that gives us another way to separate domestic production from import/FX effects.

### Important caution on the HFCP data

The dataset is unusually useful, but it is not a conventional probability sample of transactions. It was collected through citizen-science crowdsourcing with 731 volunteers plus 18 trained enumerators. The World Bank/NBS documentation explicitly identifies self-selection and digital-competency bias, although the final cohort was spatially stratified and the crowdsourced series was validated against trained-enumerator observations. The producers report strong agreement in distributional and temporal measures. citeturn1search0

Therefore we should use it primarily for **timing, relative movements, market-segment relationships and spatial patterns**, while cross-checking important findings against NBS/CBN/NAERLS statistics.

## New evidence on the production-price relationship

The official 2025 NAERLS/FMAFS survey reports that major staples increased production relative to 2024, while the same report documents very large July 2024→July 2025 price declines: white maize -52.5%, milled rice -34.6%, brown sorghum -50.2% and brown cowpea -45.2%. The declines occurred across all six geopolitical zones for those commodities. citeturn0search8

This strengthens the observation that **higher measured agricultural output and substantially lower commodity prices occurred together**.

It still does not establish the direction of causality.

The remaining possibilities include:

- higher output causing lower prices;
- favorable weather increasing output and independently affecting prices;
- seasonal harvest effects;
- imports adding supply;
- demand weakening;
- inventories being released;
- lower distribution or transaction costs;
- policy/intervention effects;
- or combinations of these.

### The farmer-incentive hypothesis remains open

The 2024 NAERLS survey records exceptionally large food-price increases before the 2025 production season. For example, July 2024 white maize was ₦961/kg versus ₦452/kg in July 2023, local rice ₦1,501 versus ₦742, and brown cowpea ₦2,035 versus ₦742. citeturn0search9

Those price signals make a farmer-response mechanism economically plausible, but they do **not** demonstrate that farmers responded by expanding production.

The evidence we still need is behavioral:

**2024 price/expected return → planting decision → cultivated area/crop choice/input use → 2025 output**

The current NAERLS area figures alone cannot establish that chain.

## New distinction: “cheap selling” does not necessarily mean “bumper harvest”

The user's intuition is useful but needs one refinement.

A farmer can sell at a lower price because **the marginal value of additional output has fallen**, but that can happen for several reasons besides an exceptionally large harvest.

For example:

**A. More physical supply**
- higher yield;
- more hectares;
- more planting cycles;
- reduced losses.

**B. More competing supply**
- imports;
- neighboring-country inflows;
- release of inventories.

**C. Lower effective demand**
- consumers buy less;
- traders hold less inventory;
- purchasing power weakens.

**D. Lower selling costs / market frictions**
- transport or transaction costs fall;
- market access improves.

Therefore the research should not define “cheap food” as proof of a bumper harvest. It should identify **which market margin moved, when it moved, and what happened to physical availability**.

## Current research state

The evidence now supports a narrower proposition:

> **There was a substantial food-market price reversal during 2025, coinciding with measured increases in production for major crops.**

It does **not yet establish**:

> **High 2024 prices caused farmers to produce substantially more.**

And it does **not establish**:

> **Monetary tightening caused or did not cause the price reversal.**

Those remain competing explanations to be tested.

## Next empirical operation

The next useful operation is to obtain the HFCP commodity files themselves and calculate, by commodity and market segment:

1. daily/weekly farmgate median or mean;
2. wholesale median or mean;
3. retail median or mean;
4. farmgate→wholesale spread;
5. wholesale→retail spread;
6. first sustained downward break;
7. regional timing of that break;
8. comparison with known harvest periods;
9. comparison with imports where available.

The key output should be a **price-transmission timeline**, not another collection of annual averages.

That timeline can then be compared against crop production and area changes.



## New evidence pass: the HFCP dataset is now confirmed usable for the transmission test

The World Bank/NBS catalogue confirms that the HFCP release contains separate market-segment observations for **Farmgate, Wholesale and Retail**. The raw combined file has 220,214 records, while commodity-specific files contain roughly 140,000–203,000 records each for December 2024–June 2025. citeturn1view0turn4search4

For local rice, the dedicated file has 198,630 records and includes date, state, LGA, rural/urban context, market type, market segment, price per kg, daily mean and daily standard deviation. citeturn2view0

This matters because we can now formulate an observable test rather than merely discuss supply.

### What we should look for

For each commodity, estimate the market-segment price path:

**Farmgate(t) → Wholesale(t) → Retail(t)**

Then examine:

- first sustained decline in each segment;
- lag between segments;
- producing versus consuming locations;
- rural versus urban locations;
- price spreads between segments;
- whether the pattern coincides with harvest periods.

A domestic-supply shock should have a particularly strong prediction: **price pressure should appear near the production/marketing end of the chain before or alongside the consumer-price response**, especially in producing areas.

That is not a theorem—storage, trader behaviour and transportation can alter the timing—but it gives us a falsifiable pattern.

### Important methodological support

Earlier Nigerian crowdsourcing research explicitly separated farmgate, wholesale and retail channels and documented price declines around harvest periods. citeturn4search12

The World Bank's validation work on Nigerian maize also found strong covariance between crowdsourced and independently estimated prices across market segments, with segment-specific relationships and a typical ordering of farmgate < wholesale < retail in the validation setting. This supports using the HFCP data to study market-segment dynamics, while not eliminating its sampling limitations. citeturn4search17

### What the new evidence changes

We should **not** yet say:

> “Farmers produced more, therefore they caused food prices to fall.”

But we can now ask a much stronger question:

> **Did the 2025 food-price reversal originate at the producer/wholesale end of the market, and did that reversal occur in locations/times consistent with increased domestic supply?**

If yes, the domestic-supply hypothesis gains evidence.

If no, we investigate competing mechanisms more aggressively.

### Another warning: expensive credit does not imply no production response

FAO's April 2025 Nigeria country brief reports that elevated input prices and increased difficulty obtaining loans, partly associated with high interest rates, were expected to constrain agricultural activity. citeturn0search5

That is useful evidence for the credit branch, but it is an expectation/constraint assessment, not evidence that production actually declined.

The coexistence of:

**expensive financing / financing constraints**

and

**higher measured 2025 production**

is therefore not a contradiction yet.

It means production must have been generated through some combination of:

- productivity/yield changes;
- cultivated-area changes;
- weather;
- farmer behaviour;
- existing capital;
- alternative financing;
- intervention finance;
- labour substitution;
- technology/input changes;
- imports (for market supply, though not domestic production);
- or other mechanisms.

The next step is to identify which of these actually moved.

## Current status after this pass

**Observed:**
- major staple production increased in 2025;
- major staple prices declined substantially;
- the HFCP dataset contains the exact market-segment and geographic variables needed to examine the timing of the price reversal.

**Not established:**
- that the price decline was caused by a bumper harvest;
- that high 2024 prices caused farmers to expand production;
- that expensive credit materially reduced agricultural output;
- that monetary tightening caused the food-price decline.

**Next operation:** reconstruct the commodity-level farmgate/wholesale/retail price timeline and compare it with crop-specific harvest/production timing.
