# Scoring Criteria

Total score out of 100, weighted across 5 dimensions + signal adjustments.

## 1. Business Quality (25 points)

| Score | Criteria |
|-------|----------|
| 21-25 | Wide moat, dominant market position, secular tailwind, best-in-class management |
| 16-20 | Clear competitive advantage, growing market share, strong management |
| 11-15 | Decent business, some differentiation, competent management |
| 6-10  | Commodity business, limited moat, average management |
| 1-5   | Declining moat, losing share, governance concerns |

## 2. Financial Strength (25 points)

| Score | Criteria | Data Check |
|-------|----------|------------|
| 21-25 | High margins, strong FCF, low debt, high ROIC (>20%), consistent growth | Net margin >15%, D/E <0.5, FCF yield >5% |
| 16-20 | Above-average margins, positive FCF, manageable debt, good ROIC (15-20%) | Net margin 10-15%, D/E <1.0 |
| 11-15 | Average margins, breakeven FCF, moderate leverage, decent ROIC (10-15%) | Net margin 5-10%, D/E <2.0 |
| 6-10  | Thin margins, negative FCF, high leverage, low ROIC (<10%) | Net margin <5%, D/E >2.0 |
| 1-5   | Burning cash, overleveraged, deteriorating fundamentals | Negative FCF, D/E >3.0 |

## 3. Growth (20 points)

| Score | Criteria | Data Check |
|-------|----------|------------|
| 17-20 | Revenue CAGR >20%, accelerating growth, large TAM runway | YoY rev growth >20%, sequential acceleration |
| 13-16 | Revenue CAGR 10-20%, steady growth, good TAM | YoY rev growth 10-20% |
| 9-12  | Revenue CAGR 5-10%, mature but stable | YoY rev growth 5-10% |
| 5-8   | Revenue CAGR 0-5%, slow growth, limited upside | YoY rev growth 0-5% |
| 1-4   | Declining revenue, shrinking TAM | Negative YoY rev growth |

## 4. Valuation (20 points)

| Score | Criteria | Data Check |
|-------|----------|------------|
| 17-20 | Significantly undervalued vs intrinsic value and peers, PEG <1 | P/E < sector median, PEG <1.0 |
| 13-16 | Moderately undervalued, reasonable multiples for growth | P/E near sector median, PEG 1.0-1.5 |
| 9-12  | Fairly valued, priced for current expectations | P/E at sector median, PEG 1.5-2.0 |
| 5-8   | Somewhat overvalued, priced for perfection | P/E > 1.5x sector median, PEG 2.0-3.0 |
| 1-4   | Extremely overvalued, bubble territory | P/E > 2x sector median, PEG >3.0 |

## 5. Catalyst & Timing (10 points)

| Score | Criteria | Data Check |
|-------|----------|------------|
| 9-10  | Strong near-term catalyst, positive momentum, sentiment inflection | RSI recovering from <30, news sentiment positive, insider buying |
| 7-8   | Identifiable catalyst within 6 months | Upcoming earnings, product launch, analyst upgrades |
| 5-6   | No clear catalyst, neutral sentiment | RSI 40-60, mixed news, no insider activity |
| 3-4   | Headwinds present, negative sentiment | RSI >65, negative news flow, insider selling |
| 1-2   | Major overhang, regulatory/legal risk, earnings deterioration | RSI >80, investigation, guidance cuts |

## Signal Adjustments (applied after base score)

### Bullish Signals
| Signal | Adjustment | How to Verify |
|--------|------------|---------------|
| Insider cluster buying (3+ buys, 90 days) | +3 | SEC EDGAR Form 4 search |
| Earnings beat + raised guidance | +2 | Recent news / earnings report |
| RSI < 30 (oversold) | +2 | Yahoo Finance OHLCV or Twelve Data |
| StockTwits sentiment > 70% bullish | +1 | StockTwits API |
| Reddit mentions surging (momentum, not meme) | +1 | ApeWisdom API |

### Bearish Signals
| Signal | Adjustment | How to Verify |
|--------|------------|---------------|
| RSI > 70 (overbought) | -2 | Yahoo Finance OHLCV or Twelve Data |
| StockTwits sentiment < 30% bullish | -1 | StockTwits API |
| Reddit meme surge (no fundamentals) | -1 | ApeWisdom + context check |
| Accounting red flags / restatements | -3 | SEC EDGAR / news search |
| Under SEC/regulatory investigation | -5 | SEC EDGAR / news search |

### Flags (no auto-adjustment, note in report)
| Signal | What It Means |
|--------|---------------|
| Unusual volume (>2x 20-day avg) | Something is happening — could be good or bad |
| Price >15% off 52-week high | Potential value or falling knife |
| Price within 5% of 52-week high | Momentum or toppy |
| Put/call ratio >1.2 (market-wide) | Fearful market — contrarian bullish context |
| Put/call ratio <0.6 (market-wide) | Greedy market — contrarian bearish context |

## Verdict Thresholds

| Score | Verdict |
|-------|---------|
| 75+   | BUY — strong conviction, set a price target |
| 55-74 | HOLD — decent business, not compelling at current price |
| <55   | AVOID — fundamental or valuation concerns |

## Self-Correction

After every 10 stocks, review accuracy:
- If BUY picks are consistently losing value: tighten valuation scoring
- If AVOID picks are rallying: check if momentum/sentiment signals were ignored
- If all scores cluster in 55-70 range: recalibrate — the rubric may be too conservative or generous
- Update this file with learnings
