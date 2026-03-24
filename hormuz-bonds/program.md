# Hormuz Disruption — Investment Grade Bond Research

## Thesis

The Strait of Hormuz is the world's most critical energy chokepoint — ~20-21M barrels/day of oil (~20% of global supply) and ~20% of global LNG transits through a 21-mile-wide channel. A partial or full closure due to Iran-related conflict would be the most significant supply shock since the 1973 oil embargo.

**The investment question is NOT "what goes up if oil spikes."** It's: **"Which investment-grade issuers have cash flows that mechanically increase under a Hormuz disruption AND can physically deliver on that cash flow?"**

This means: NO Middle East producers (can't ship), NO companies dependent on Hormuz transit, NO speculative credits. Only investment-grade bonds from companies that **benefit from the disruption while operating outside the blast radius.**

## First Principles: What Actually Happens If Hormuz Closes

Think through the physical reality, not the headline:

### Layer 1: Direct Energy Impact
- **~20M bbl/day of oil trapped** (Saudi, Iraq, Kuwait, UAE, Qatar exports)
- **Qatar LNG offline** — world's largest LNG exporter, ALL shipments through Hormuz
- Oil spikes to $120-200+ depending on duration
- LNG spot prices spike 3-5x in Asia/Europe
- SPR releases buy weeks, not months

### Layer 2: Who Fills the Gap? (THE OPPORTUNITY)
- **US shale producers**: can ramp within months, pipelines to Gulf Coast terminals functional
- **Brazil (Petrobras)**: deepwater pre-salt production, Atlantic shipping routes completely unaffected
- **Guyana (Exxon Stabroek)**: new production, Atlantic route
- **Norway (Equinor)**: North Sea production to Europe, zero Hormuz exposure
- **Canada oil sands**: pipelines to Pacific (TMX) and US refineries
- **Australia LNG**: NW Shelf, Gorgon, Wheatstone — Pacific LNG supply for Asia, zero Hormuz
- **US LNG exporters**: Cheniere, Venture Global — Gulf Coast to Europe/Asia
- **Alternative pipelines**: East-West Pipeline (Saudi, 5M bbl/day bypass capacity), IPSA pipeline, Abu Dhabi's Fujairah pipeline (1.5M bbl/day)

### Layer 3: Second-Order Winners
- **Tanker companies**: longer shipping routes = more ton-miles = higher day rates. But most are high-yield, not IG
- **Defense primes**: Lockheed, RTX, Northrop — defense spending accelerates. Already IG-rated
- **Uranium/Nuclear**: Hormuz disruption accelerates energy security → nuclear restart narrative. Cameco is IG
- **Fertilizer with non-ME feedstock**: Nutrien (Canadian potash + US nat gas feedstock). Food security panic
- **Refining with domestic crude access**: Valero, Phillips 66 — US Gulf Coast refiners with access to discounted WTI while global crude spikes. Crack spreads explode
- **Pipeline/midstream**: Enterprise Products, MPLX, Energy Transfer — toll-road economics, higher throughput
- **War risk insurance**: reinsurance companies (Swiss Re, Munich Re) — premiums spike

### Layer 4: What Most People Miss
- **Petrochemical disruption**: Saudi/Qatar are massive ethylene, methanol, fertilizer exporters. Disruption = shortage in plastics, chemicals
- **Shipping insurance costs**: war risk premiums on ALL Gulf shipping surge 10-50x. Benefits non-Gulf routes
- **Food prices**: fertilizer + oil spike → food inflation → benefits agricultural commodity producers
- **Industrial gas**: Air Liquide, Linde — critical to refining/chemical processes, pricing power increases
- **Copper/aluminum**: energy-intensive smelting gets expensive globally, BUT non-Gulf producers with cheap hydro power (Norsk Hydro, Alcoa Iceland) gain relative advantage

## Bond Selection Criteria

We want **investment-grade corporate bonds** (BBB- or above by S&P / Baa3 or above by Moody's) from issuers that:

1. **Cash flow mechanically increases** under Hormuz disruption (not just "might benefit")
2. **Can physically deliver** — production and shipping routes bypass Hormuz entirely
3. **Already investment-grade** — we want the credit improvement story (IG bonds that become STRONGER credits under stress, not junk bonds gambling on a scenario)
4. **Liquid bonds** — institutional-size issuances, not obscure private placements
5. **Reasonable spread** — buying at tight spreads means no upside. Want bonds trading at normal-to-wide spreads that would tighten under disruption

### Bond Metrics to Evaluate

| Metric | What to Look For |
|--------|-----------------|
| Credit Rating | BBB- to A+ (sweet spot: BBB/BBB+ with upgrade potential under scenario) |
| Spread to Treasury | Current OAS vs 5yr range. Wider = more upside |
| Duration | 3-7 year preferred (enough time for scenario to play out, not too much interest rate risk) |
| Debt/EBITDA | <3x preferred. Under disruption scenario, EBITDA rises → leverage drops → credit improves |
| Interest Coverage | >4x. Under scenario, should improve dramatically |
| FCF/Debt | >15%. Should improve under scenario |
| Hormuz Exposure | ZERO. No revenue, supply chain, or shipping route dependency on Hormuz |
| Revenue Uplift | Estimate % revenue/EBITDA increase under $150 oil / $30 LNG scenario |

## Research Loop

For each issuer:

### 1. Chokepoint Benefit Analysis
- **How exactly does this issuer benefit from Hormuz closure?**
- Map the physical flow: where is production? Where does it ship? Who buys it?
- Quantify: if oil goes to $150 and LNG to $30/mmbtu, what happens to EBITDA?
- Verify: does the company have ZERO Hormuz transit dependency?

### 2. Credit Analysis
- Current rating and outlook
- Key credit metrics: leverage, coverage, FCF
- Stress test: what do metrics look like under disruption scenario?
- Bond specifics: maturity, coupon, current spread, covenants

### 3. Risk Assessment
- What if disruption doesn't happen? Is this still a decent bond? (don't need the thesis to hold for the bond to not lose money)
- What second-order risks exist? (e.g., global recession from oil shock could hurt demand)
- Sanctions/regulatory risk to the issuer?
- ESG/reputational risk of "profiting from conflict"?

### 4. Write Research Note

Save to `reports/<ISSUER>.md`:

```
# <ISSUER> — <Bond Description>
## Date: <date>
## Conviction: HIGH / MEDIUM / LOW

### Disruption Benefit Thesis (2-3 sentences)

### Physical Flow Map
- Production location: ...
- Shipping route: ...
- Key customers: ...
- Hormuz exposure: NONE / describe any indirect exposure

### Scenario Impact
| Metric | Current | Under $150 Oil / $30 LNG |
|--------|---------|--------------------------|
| Revenue | $XB | $XB (+XX%) |
| EBITDA | $XB | $XB (+XX%) |
| Debt/EBITDA | X.Xx | X.Xx |
| Interest Coverage | X.Xx | X.Xx |
| FCF | $XB | $XB |
| Implied Rating Move | ... | ... |

### Bond Specifics
| Field | Value |
|-------|-------|
| Ticker/CUSIP | ... |
| Coupon | X.XX% |
| Maturity | YYYY-MM-DD |
| Rating (S&P/Moody's) | XX/Xx |
| Current Price | $XX |
| Current Spread (OAS) | XXbps |
| 5yr Spread Range | XX-XXbps |

### Base Case (no disruption)
Is this bond still acceptable without the Hormuz thesis?

### Risks
### Verdict: BUY / MONITOR / PASS
```

### 5. Log Results

Append to `results.tsv`:
```
issuer	bond_desc	rating	spread_bps	conviction	hormuz_ebitda_uplift	leverage_current	leverage_stress	verdict	one_liner
```

### 6. Commit and Continue

## Target Universe

### Tier 1: Direct Energy Beneficiaries (non-Hormuz producers)
- **Exxon Mobil (XOM)** — Guyana Stabroek + Permian, zero Hormuz. AA- rated
- **Chevron (CVX)** — Permian + Australia LNG (Gorgon/Wheatstone), zero Hormuz. AA- rated
- **ConocoPhillips (COP)** — US shale + Alaska + Australia. A rated
- **Petrobras (PBR)** — Brazilian pre-salt, Atlantic route. BB+/Ba1 (below IG but worth monitoring)
- **Equinor (EQNR)** — North Sea to Europe. AA- rated
- **Canadian Natural Resources (CNQ)** — Oil sands, TMX pipeline to Pacific. BBB+ rated
- **Cheniere Energy (LNG)** — US Gulf Coast LNG, massive Europe/Asia demand under disruption. BBB rated
- **Woodside Energy (WDS)** — Australia NW Shelf LNG, Pacific supply. BBB+ rated

### Tier 2: Midstream / Pipeline (toll-road models)
- **Enterprise Products (EPD)** — US Gulf Coast NGL/crude pipelines. BBB+ rated
- **MPLX LP (MPLX)** — Marcellus/Permian gathering + processing. BBB rated
- **Energy Transfer (ET)** — Largest US pipeline network. BBB rated
- **Enbridge (ENB)** — Canadian crude to US + offshore Gulf. BBB+ rated
- **TC Energy (TRP)** — NGTL, Keystone. BBB+ rated

### Tier 3: US Refiners (crack spread explosion)
- **Valero (VLO)** — Largest independent US refiner, Gulf Coast complex. BBB rated
- **Phillips 66 (PSX)** — Refining + midstream + chemicals. BBB+ rated
- **Marathon Petroleum (MPC)** — Largest US refiner by capacity. BBB rated

### Tier 4: Defense Primes
- **Lockheed Martin (LMT)** — F-35, missiles, naval systems. A- rated
- **RTX Corp (RTX)** — Patriot, NASAMS, jet engines. BBB+ rated
- **Northrop Grumman (NOC)** — B-21, space, cyber. BBB+ rated
- **General Dynamics (GD)** — Submarines, Gulfstream. A rated

### Tier 5: Second-Order / Non-Obvious
- **Cameco (CCJ)** — Uranium. Nuclear energy security narrative. BBB- rated
- **Nutrien (NTR)** — Potash + nitrogen fertilizer. Non-ME feedstock. BBB rated
- **Linde (LIN)** — Industrial gas monopoly. Pricing power in energy-stressed environment. A rated
- **Mosaic (MOS)** — US phosphate + Canadian potash. BBB rated
- **Targa Resources (TRGP)** — NGL export terminal, benefits from US energy demand. BBB rated

### Tier 6: Reinsurance (war risk premium)
- **Berkshire Hathaway (BRK)** — Reinsurance + energy holdings. AA rated
- **Swiss Re** — War risk premium spike. AA- rated

## Rules

- **Physical reality first.** Trace the barrels, the molecules, the ships. If you can't map the physical flow, you don't understand the trade
- **IG only.** No high-yield lottery tickets. We want credits that get STRONGER under stress
- **Zero Hormuz exposure.** If any part of the supply chain touches Hormuz, it's disqualified
- **Base case must not lose money.** Every bond should be acceptable even if Hormuz never closes. The disruption is upside optionality, not the base case
- **Quantify the uplift.** "Oil goes up so they benefit" is not analysis. Model the EBITDA impact
- **Duration matters.** 3-7 year bonds preferred. Too short = no time for thesis. Too long = too much rate risk
- **NEVER STOP** unless the human interrupts
