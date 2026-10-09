# 04: Whole-business returns (ROI, ROE) and time required

*Research report, not a product change. Prepared 2026-10-09. Every web source was observed on **2026-10-09** unless a different date is given; where a source shows its own publication or update date, that date is listed too. Sources are cited as `[W#]` (Section 7). Anything not from a source is labelled **(A)** for assumption or **(model)** for an output of the model in Section 2. Companion reports: `01-pallet-sourcing.md` (open PR mdb1230/Agent-Reach#1) and `03-cheap-bulk-auction-winners.md` (in progress on another branch). They are cited as `[R01]` and `[R03]`. Report 02 (Whatnot fees and per-item margins) was not found in any open PR or worktree on 2026-10-09, so this report re-derives the fee inputs it needs.*

---

## Executive summary

The business: buy branded electronics returns and liquidation pallets, test them, and sell them item by item in Whatnot auctions, with eBay for leftovers. The three scenarios below differ mainly in **what you pay for a pallet, how much of it works, and what it fetches**. Those three inputs decide the result. Capital size and audience growth matter much less.

| Metric | Conservative | Base | Optimistic |
|---|---|---|---|
| Return per inventory cycle, after fees and variable costs | **+5.6%** (a bad pallet is **−32.7%**) | **+38%** | **+99%** |
| Annual return on inventory, after fixed costs (pre-tax) | **−23% to −31%** | **+177% to +185%** | **+750% to +758%** |
| ROE, owner-funded, after a 25% tax set-aside | **−15% to −21%** | **+87% to +94%** | **+354% to +387%** |
| ROE with 50% extra credit-card debt at 22.36% APR | −14% to −21% | +165% to +173% | +647% to +680% |
| Hours/week (part-time $2k–$5k tiers / full-time $15k tier) | 12–17 / 36 | 13–18 / 41 | 14–21 / 48 |
| Owner's effective hourly pay (pre-tax) | **below $0** | **$3.56–$8.85** | **$14–$31** |
| First month with operating profit | never | month 1 | month 1 |
| Month the startup equipment is paid back | not within 24 months | month 4–5 | month 2 |
| Months to replace a median full-time paycheck ($5,421/month pre-tax [W23]) by reinvesting profits | never | **not reached in 36 months.** Profit levels off at about $2.6k–$3.2k/month once you pay for help | 2–4 months |

**Verdict.** This is worth a **small, gated test with $2k–$5k**. It is **not** a safe plan to replace a full-time income.

- **The return percentages flatter the business.** ROE looks high because the capital is small. In the base case the owner earns **$4–$9 an hour** (model). That is below the $20–$25/hour one Whatnot seller reported after costs [W4]. Once the owner's time is costed at $20/hour, **every base-case tier loses money** (Table 2.7).
- **The upside is real but needs everything to go right at once:** landed cost at or below 20% of retail, at least 85% of units working, and auction prices at or above 55% of retail. Seller-reported electronics pallet results sit nearer the conservative case. Examples: a $2,500 Liquidation.com electronics pallet was valued at only ~$3,700 "assuming most of that stuff works" [W17], and only 13% of electronics pallets are New or Like New [R01].
- **Go/no-go:** scale past $5k only if, by day 90, measured results on 2–3 lots match the optimistic inputs and trailing-30-day profit is at least $15/hour (Section 4.3).

---

## 1. Benchmarks

### 1.1 Live-commerce (Whatnot) platform benchmarks

| Benchmark | Value | Source and caveat |
|---|---|---|
| Hours per week, Whatnot sellers | **~19 h/week**; 69% go live daily | Whatnot/Wakefield 2024 report. Sample: 1,613 Whatnot sellers with ≥6 months on the platform and ≥2 shows/week; plus 500 cross-platform sellers (±4.4%), fielded Aug 2024 [W1] |
| Hours per week, 2026 | **~23 h/week**, "live streaming and running the business" | Value Added Resource summary of Whatnot's 2026 report (2026-01-30, updated 2026-03-07) [W3]. Whatnot's own page doesn't show the hours figure [W2] |
| Revenue at 3–4 shows/week | **>$13,000/month average sales** | Whatnot 2026 report (2026-01-28) [W2]. Sales, not profit; all categories |
| Frequency effect | Daily sellers earn **100–250×** what sellers going live once or twice a month earn; monthly→weekly is **10–20×** | [W2] |
| Share who are full time | **1 in 8** Whatnot sellers | [W2] |
| Income distribution | 66% of live sellers earn >$10k/month **revenue**; the average seller had been live selling for only **8 months** | 2024 report, cross-platform survey [W1] |
| Electronics share and growth | 8% of live sellers sell electronics (2024) [W1]; electronics GMV **+444%** in 2025 [W2] | Survivor bias: all surveyed sellers were still active |
| Vendor estimate of seller tiers | Part-time (1–2 shows/week): $1.5k–$5k revenue, **$600–$2,500 profit/month**; 3–4 shows/week: $13k+ revenue, $4k–$8k profit | BundleLive (2026-02-15). Vendor estimate, no method given [W7] |
| Vendor estimate of margins | "35–50%" profit margin after COGS, fees and shipping | [W7]. Community claim, mostly collectibles and apparel, not returns electronics |

### 1.2 Seller-reported results (YouTube transcripts; dates are upload dates)

Reddit (r/Flipping, r/whatnotapp, r/Entrepreneur) blocked automated access during this research. Both direct fetches and domain-restricted search returned errors (Section 6). Seller voices therefore come from YouTube transcripts and from secondary sources that quote Reddit.

| Seller (category) | What they reported | Implied metric | Source |
|---|---|---|---|
| Philly Phlipper (collectibles, full-time, ~40k followers) | $125,688 sales in Jan–Apr 2025. He *assumed* ~15% fees (his estimate; his actual Whatnot rate was "about 11% plus 30 cents"). Sourcing ~$1,200/week, plus part-time help, supplies and promotion → "about $80,000 profit in four months". 8 months full-time on Whatnot after years on eBay | ~62% net margin, but cost of goods is only ~15% of sales. Not comparable to pallets | [W10] |
| Trash Pandas Thrift (thrift apparel, couple) | First month: 12 shows, $9,153 sales, 1,078 items, ~$1/unit cost; first show $459, then about $790/show | ~77% margin before shipping supplies and labour (model arithmetic from their figures) | [W11] |
| Kevin Toomey (thrift, first timer) | 3-hour show: $210 sales; $182.92 received after fees, including tips; cost of goods $215.17 → **lost ~$32** before his time | Negative ROI on show 1 | [W12] |
| Kate's Fashion Flipz (apparel) | Quit after a handful of shows: 2 buyers on show 2, ~$50 on her best show. Grew to ~850 followers via follow-for-follow, but "it hasn't made a difference for my sales" | Audience didn't convert | [W13] |
| Cayley Elaine (coach/seller) | Sellers with "tens of thousands of followers" sometimes have ~15 viewers | Followers ≠ buyers | [W14] |
| TY Wilson (sports-card singles) | Over one year: 20,000+ orders, 200+ hours streamed, nearly $600k sales | Up to ~100 orders per live hour in a fast low-ticket category | [W15] |
| Stephanie Canada (sewing patterns, new seller) | 60 items in 2.5 h; 112 items in 5 h 10 min, "two hours longer than I thought" | **~22–24 items per live hour**, the model's pace input | [W16] |
| Reddit seller quoted by Underpriced | 4 nights/week × 3–4 h live; **30–35 h/week** in total; "$20–25 per hour" after costs on $8k–12k/month sales | Effective wage benchmark | [W4] (secondary) |
| SarahGrace (Liquidation.com electronics returns pallet) | Paid $2,500. Many broken units. Estimated total value $3,700 "assuming most of that stuff works" | **≤1.48× gross before fees**, unrealised | [W17] |

### 1.3 Liquidation and returns economics

| Benchmark | Value | Source |
|---|---|---|
| What electronics pallets close at | Median **12.6% of stated retail**; B-Stock 22.8%, Liquidation.com 8.6% | [R01] (90 days to 2026-09-13) |
| Add-ons to the bid | Buyer's premium 10% (B-Stock), 5–10% (Liquidation.com); median freight **63.8% of the winning bid** | [R01] |
| Condition mix | Only **13%** of electronics pallets were New, Like New, open-box or shelf pulls | [R01] |
| Unsellable share | "Nearly 15–30% of items… may be damaged or unsellable" | AmzScout (dated 03.02.2026) [W19] |
| Resale by condition | New 70–90% of retail, Like New 50–70%, damaged 30–40%; recommended max bid 20–40% of manifest retail | Threecolts (2025-05-15) [W18] |
| Pessimistic bound | A veteran reseller says Amazon pallets rarely net more than ~5% of retail once unsellables are stripped | AOL, via search snippet only; the article returned 404 on fetch [W29] |
| Return/refund rate | Whatnot 2–5% vs eBay 6–8% (vendor figure); claims within 3 days of delivery (vendor figure) | BundleLive (2026-02-15) [W8] |
| Illustrative pallet log | 6 pallets: ROI 27%→105% per period, $4–$36/hour, 45–60 day sell-through. **The page itself labels it illustrative** | Underpriced [W6] |

### 1.4 Inventory turnover and cash-conversion cycle (CCC)

| Business | Inventory turns/yr | Days inventory (DIO) | Days receivable (DSO) | Days payable (DPO) | CCC (days) | Net margin |
|---|---|---|---|---|---|---|
| Best Buy, FY2025 (ended 2025-02-01) | 6.40 | 57.0 | 8.7 | 54.6 | **11.1** | 2.2% |
| This model: Conservative | 4.06 | 84 | 6 | 0 | **90** | −4% to −5% |
| This model: Base | 6.08 | 55 | 5 | 0 | **60** | 17% |
| This model: Optimistic | 8.11 | 40 | 5 | 0 | **45** | 39% |
| eBay one-off seller (single forum post) | ~1.8 (inventory "about every 200 days") | ~200 | — | — | — | — |

- **Best Buy** figures come from its FY2025 10-K XBRL data [W20]. Cost of sales was $32,143M on average inventory of $5,021.5M. Receivables averaged $991.5M on revenue of $41,528M. Payables averaged $4,808.5M. Net earnings were $927M. Turns = COGS ÷ average inventory; DIO = 365 ÷ turns; DSO = receivables ÷ revenue × 365; DPO = payables ÷ COGS × 365; CCC = DIO + DSO − DPO.
- **The eBay figure** is one seller's calculation, with no date beyond "2 years ago" [W28].
- **Model CCC (A).** Each cycle runs from wiring money for a pallet to the cash landing in your account:
  - Conservative: 14 days freight + 10 days processing + 60 days selling + 6 days ship/payout.
  - Base: 10 + 7 + 38 + 5.
  - Optimistic: 7 + 5 + 28 + 5.
- **Payables:** DPO is 0 because B-Stock wants a wire within 2 business days [R01]. Paying by credit card can add a ~25–55-day float. That is the leverage case in 2.8.
- **Receivables:** DSO is short because Whatnot pays US sellers within 4 hours of carrier-confirmed delivery [W9].
- **What this means:** a reseller cannot get Best Buy's supplier credit, so the whole cycle is funded by the owner. That is why capital, not audience, limits revenue at $2k–$15k (Table 2.6).

---

## 2. Financial model

### 2.1 How it works (formulas)

All inputs are in the tables below and in the Python appendix (Section 8). Change a number and re-run to get every table back.

```
Inventory capital  I  = K − equipment − 10% × K          (K = starting capital)
Revenue multiple   m  = [sell × hammer + (1 − sell) × salvage] ÷ cost
    cost    = landed cost (bid + buyer premium + freight) as a share of retail
    sell    = working share; hammer = auction price as a share of retail; salvage = share of retail recovered on dead units
Whatnot fee/sale      = c × P + 2.9% × (1.07 × P + $8) + $0.30   (c = commission, P = avg sale price; processing is charged on item + tax + shipping)
eBay fee/sale         = 13.6% × P + $0.40
Variable cost ratio v = [85% × Whatnot fee + 15% × eBay fee + packaging] ÷ P + giveaways% + refunds%
ROI per cycle         = m × (1 − v) − 1
Turns per year        = 365 ÷ cycle days
Monthly revenue       = min( I × m × (365/12) ÷ cycle ,  shows/week × 52/12 × $/show ÷ 0.85 )
                         └ capital-limited ┘          └ audience-limited (Whatnot is 85% of sales) ┘
                         (month 1 capital-limited revenue is halved while the first lot arrives)
Pre-tax profit        = revenue − revenue ÷ m − v × revenue − fixed costs − interest
Net income            = pre-tax × (1 − 25%) if positive (tax set-aside), else pre-tax
Annual ROI on inventory = 12 × pre-tax ÷ I
ROE                   = 12 × net income ÷ K   (owner-funded; with debt D, equity is still K)
Effective hourly      = monthly pre-tax (or net) ÷ monthly hours
Payback month         = first month where cumulative net income ≥ equipment cost
```

"Steady state" means month 13 (after the audience ramp). Annualised ROI is the simple version (profit withdrawn each month). Compounding is not shown as a headline because the audience and labour limits stop it from compounding (2.9).

### 2.2 Scenario inputs (editable)

| Input | Conservative | Base | Optimistic | Basis |
|---|---|---|---|---|
| Landed cost, % of retail (`cost`) | 24% | 22% | 20% | Base = median close 12.6% × (1 + 10% premium + 63.8% freight) = 21.9% [R01]. Graded Sony headphone lots closed ~20–21% before fees [R01]. Threecolts' max bid is 20–40% [W18]. (A) within those bounds |
| Working share (`sell`) | 70% | 75% | 85% | 15–30% unsellable [W19]; [R03] uses 75%. (A) |
| Auction price for working units, % of retail (`hammer`) | 48% | 50% | 55% | Like New resells for 50–70% of retail [W18]. Whatnot $1-start auctions often clear below eBay comps [W4][W10]. (A), low end |
| Salvage on dead units, % retail | 3% | 5% | 5% | (A): parts lots on eBay |
| Average sale price `P` | $30 | $40 | $50 | [R03] hammer estimates for branded audio/controllers $25–$40, up to $72. (A) |
| Whatnot commission `c` | 8% | 8% | 5% | 8% standard tier (Underpriced, updated 2026-10-01) [W4]; 5% electronics (Crosslist, updated 2026-09-30) [W9]. Unresolved: Whatnot's help page returns 403, and a tiered structure began 2026-09-21 [R01] |
| Payment processing | 2.9% + $0.30 | same | same | [W4][W9] |
| Buyer sales tax / buyer-paid shipping in the processing base | 7% / $8 | same | same | (A) |
| eBay share of revenue; eBay fee | 15%; 13.6% + $0.40 | same | same | eBay fee per [R03] (eBay Help). Share (A) |
| Packaging per order | $1.00 | $0.75 | $0.60 | (A); [R03] uses $0.50 |
| Giveaways and show promotion, % of revenue | 5% | 4% | 3% | Sellers report $10–15 paid promotion per show [W11] and $10 gift-card giveaways [W13]. (A) |
| Refunds, returns, chargebacks, % of revenue | 5% | 3% | 2% | Whatnot return rate 2–5% (vendor) [W8]. Electronics risk is higher (A) |
| Cash cycle (days) | 90 | 60 | 45 | See 1.4; illustrative 45–60 days [W6]. (A) |
| Revenue per show, month 1 / months 2–3 / 4–6 / 7+ | $50 / $200 / $350 / $500 | $125 / $350 / $600 / $900 | $200 / $500 / $1,200 / $1,500 | Guide: M1 $50–200, M2–3 $200–500, M4–6 $500–2,000 per show [W4]. Whatnot: 3–4 shows/week average >$13k/month [W2] ≈ $750–$1,000/show. (A) |
| Tax set-aside on positive profit | 25% | 25% | 25% | Self-employment tax is 15.3% [W22] on 92.35% of profit (≈14.1%), plus federal and state income tax. (A); not tax advice |
| Card APR for the leverage case | 22.36% | same | same | Fed G.19 rate on accounts assessed interest, Aug 2026 (FRED, updated 2026-10-07) [W21] |

### 2.3 Startup capital: equipment, supplies, inventory and reserve

| Starting capital (K) | Equipment & supplies | Cash reserve (10% of K) | Inventory capital = K − equipment − reserve | Monthly fixed costs | Show cadence |
|---|---|---|---|---|---|
| $2,000 | $470 | $200 | **$1,330** | $60 | 2/week |
| $5,000 | $1,385 | $500 | **$3,115** | $120 | 2/week |
| $15,000 | $3,270 | $1,500 | **$10,230** | $400 | 4/week |

**$2k tier: phone you already own + basics**

| Item | Cost |
|---|---|
| Ring light + tripod/phone mount kit | $50 |
| Clip-on mic | $25 |
| Thermal label printer (used 4x6) | $110 |
| 4x6 labels, 500 | $20 |
| Shipping scale | $25 |
| Test kit: USB-C/USB power meter, chargers, cables, batteries | $60 |
| 1 steel shelving unit | $80 |
| Starter boxes, mailers, bubble wrap, tape | $100 |
| **Total equipment & supplies** | **$470** |

**$5k tier: two-camera phone setup + test bench**

| Item | Cost |
|---|---|
| Ring light + 2 softbox lights | $140 |
| Lavalier/USB mic | $60 |
| Second (used) phone for overhead/product cam | $250 |
| Tripods/overhead arm | $60 |
| Thermal label printer (new 4x6) | $170 |
| 4x6 labels, 1,000 | $40 |
| Shipping scale | $25 |
| Test bench: power meter, multimeter, HDMI monitor, chargers, cables | $200 |
| 3 steel shelving units | $240 |
| Boxes, mailers, bubble wrap, tape | $200 |
| **Total equipment & supplies** | **$1,385** |

**$15k tier: PC-based multi-camera stream + bigger test station**

| Item | Cost |
|---|---|
| Laptop/PC for multi-camera streaming software | $800 |
| 2 cameras/webcams | $300 |
| Lighting kit (key, fill, backdrop) | $200 |
| USB/XLR mic | $120 |
| Stream deck/capture misc. | $100 |
| Wireless thermal label printer | $285 |
| 4x6 labels, 2,000 | $80 |
| Shipping scale | $25 |
| Test bench: power meter, multimeter, monitor, console/TV test station, chargers | $400 |
| 6 steel shelving units + bins | $560 |
| Boxes, mailers, bubble wrap, tape | $400 |
| **Total equipment & supplies** | **$3,270** |

Price anchors:
- Ring-light/tripod kits run $24.97–$54.62 [W24].
- A Rollo X1038 thermal printer is $169.99 new or ~$110 used; the wireless model is $284.98; 500 4×6 labels cost $19.99 [W25].
- All other line items are assumptions (A). The plan assumes you already own a smartphone.

### 2.4 Monthly fixed costs (A)

| Item | $2k | $5k | $15k |
|---|---|---|---|
| Software (bookkeeping/inventory app, cloud storage) | $20 | $40 | $60 |
| Extra phone/internet share, test consumables | $40 | $50 | $90 |
| Storage (home → garage/storage unit) | $0 | $30 | $150 |
| Insurance, misc. | $0 | $0 | $100 |
| **Total (`fixed`)** | **$60** | **$120** | **$400** |

Whatnot itself charges no listing or subscription fees [W4].

### 2.5 Unit economics per inventory cycle

| Scenario | Revenue per $1 of inventory (m) | Fees as % of revenue | All variable costs (v) | ROI per cycle = m×(1−v)−1 | Cash cycle (days) | Turns/yr = 365÷cycle | Annualized, simple = ROI×turns |
|---|---|---|---|---|---|---|---|
| Conservative | 1.438 | 13.2% | 26.5% | **5.6%** | 90 | 4.06 | 23% |
| Base | 1.761 | 12.8% | 21.6% | **38.0%** | 60 | 6.08 | 231% |
| Optimistic | 2.375 | 10.0% | 16.2% | **99.1%** | 45 | 8.11 | 804% |
| *Stress: bad pallet* | 0.916 | 13.2% | 26.5% | **−32.7%** | — | — | — |

The **bad pallet** stress case uses the conservative fees and costs, but 25% landed cost, 55% working and a 40% hammer price.

### 2.6 Results by capital tier and scenario (steady state, month 13)

| Capital | Scenario | Monthly revenue | Monthly pre-tax profit | Monthly net (after 25% tax set-aside) | Net margin (pre-tax) | Annual ROI on inventory (pre-tax, after fixed costs) | ROE (owner-funded) | First profitable month | Equipment payback month | Hours/week | $/hour pre-tax | $/hour after tax |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| $2k | Conservative | $646 | −$35 | −$35 | −5% | −31% | **−21%** | never | not within 24 | 12.1 | −$0.66 | −$0.66 |
| $2k | Base | $1,188 | $196 | $147 | 17% | 177% | **88%** | 1 | 4 | 12.7 | $3.56 | $2.67 |
| $2k | Optimistic | $2,135 | $831 | $623 | 39% | 750% | **374%** | 1 | 2 | 13.6 | $14.06 | $10.54 |
| $5k | Conservative | $1,513 | −$61 | −$61 | −4% | −23% | **−15%** | never | not within 24 | 16.8 | −$0.83 | −$0.83 |
| $5k | Base | $2,781 | $481 | $360 | 17% | 185% | **87%** | 1 | 5 | 18.4 | $6.03 | $4.52 |
| $5k | Optimistic | $5,001 | $1,967 | $1,476 | 39% | 758% | **354%** | 1 | 2 | 20.5 | $22.11 | $16.58 |
| $15k | Conservative | $4,970 | −$205 | −$205 | −4% | −24% | **−16%** | never | not within 24 | 35.9 | −$1.32 | −$1.32 |
| $15k | Base | $9,135 | $1,572 | $1,179 | 17% | 184% | **94%** | 1 | 5 | 41.0 | $8.85 | $6.64 |
| $15k | Optimistic | $16,422 | $6,455 | $4,841 | 39% | 757% | **387%** | 1 | 2 | 48.0 | $31.01 | $23.26 |

How to read Table 2.6:
- **Capital, not audience, limits sales.** In every tier and scenario, steady-state revenue is capital-limited. The model's audience ceiling after month 7 is $5.1k–$30.6k a month depending on tier and scenario, well above what $1.3k–$10.2k of inventory can turn over.
- **Thin shows at the low tiers.** At $2k–$5k the inventory only supports ~2–10 Whatnot items per show (model: units sold × 85% ÷ 8.7 shows/month). Filling a 2-show/week cadence takes cheap bid-drivers [R03], paid for from the giveaway budget. At $2k, one show a week is more realistic.
- **"First profitable month = 1"** assumes the first lot arrives within ~2 weeks. It counts operating profit only; recovering the equipment cost is the payback column.

### 2.7 Year 1, and profit after paying the owner a wage

| Capital | Scenario | Year-1 pre-tax profit | Year-1 hours | Steady-state annual profit after paying the owner $20/h |
|---|---|---|---|---|
| $2k | Conservative | −$429 | 623 | −$12,967 |
| $2k | Base | $2,229 | 656 | −$10,883 |
| $2k | Optimistic | $9,529 | 702 | −$4,215 |
| $5k | Conservative | −$768 | 862 | −$18,246 |
| $5k | Base | $5,442 | 942 | −$13,365 |
| $5k | Optimistic | $22,372 | 1,046 | $2,251 |
| $15k | Conservative | −$2,689 | 1,788 | −$39,807 |
| $15k | Base | $16,584 | 2,027 | −$23,778 |
| $15k | Optimistic | $67,111 | 2,314 | $27,508 |

The **last column** answers the real question: does the business earn more than a $20/hour job? (A: $20/hour is the low end of the $20–25/hour seller report [W4].)
- **Base case:** no tier does.
- **Optimistic case:** only the $5k and $15k tiers do.

### 2.8 Leverage: credit card or inventory financing

| Capital | Scenario | ROE, owner-funded | ROE with +50% card debt at 22.36% APR | ROE with +50% debt at 0% promo APR | Monthly interest at 22.36% | Hours/week with debt | $/hour pre-tax with debt (22.36%) |
|---|---|---|---|---|---|---|---|
| $2k | Conservative | −21% | −21% | −9% | $19 | 13.6 | −$0.58 |
| $2k | Base | 88% | 167% | 175% | $19 | 14.8 | $5.78 |
| $2k | Optimistic | 374% | 667% | 676% | $19 | 16.4 | $20.88 |
| $5k | Conservative | −15% | −14% | −3% | $47 | 20.7 | −$0.67 |
| $5k | Base | 87% | 165% | 173% | $47 | 23.5 | $8.98 |
| $5k | Optimistic | 354% | 647% | 656% | $47 | 27.4 | $30.30 |
| $15k | Conservative | −16% | −16% | −5% | $140 | 47.6 | −$0.98 |
| $15k | Base | 94% | 173% | 181% | $140 | 56.4 | $11.78 |
| $15k | Optimistic | 387% | 680% | 689% | $140 | 68.6 | $38.16 |

Leverage roughly **doubles ROE** in the base and optimistic cases, because each $1 of inventory earns 38%–99% per cycle and turns 6–8× a year, far above a 22% APR.

It **does not help in the conservative case**: 5.6% × 4.06 turns ≈ 23%/year, about the same as the card APR. It **makes a bad pallet worse**: borrowed money loses 33% per cycle plus interest.

Leverage also **adds ~1.5–21 hours a week** of testing and packing. The higher ROE is mostly paid for in owner hours.

0% promotional APR cards give the best result, but only for 12–21 months (A, typical offer terms). Leverage only helps while sales are capital-limited. Once sales hit the audience limit, extra inventory just sits on the shelf.

### 2.9 Sensitivity (Base, $15k tier; one input changed at a time)

| Change | ROI per cycle | Monthly pre-tax | $/hour pre-tax |
|---|---|---|---|
| **Base as modelled** | 38.0% | $1,572 | $8.85 |
| Landed cost 18% of retail | 68.7% | $3,163 | $15.98 |
| Landed cost 26% of retail | 16.8% | $471 | $2.88 |
| Working share 65% | 22.0% | $741 | $4.24 |
| Working share 85% | 54.1% | $2,404 | $13.28 |
| Hammer 40% of retail | 11.3% | $187 | $1.17 |
| Hammer 60% of retail | 64.7% | $2,958 | $15.14 |
| Commission 5% instead of 8% | 42.5% | $1,805 | $10.16 |
| Average sale price $30 / $50 | 36.2% / 39.1% | $1,476 / $1,630 | $7.10 / $10.22 |
| Cash cycle 45 / 90 days | 38.0% / 38.0% | $2,230 / $915 | $10.72 / $6.21 |
| Refunds 6% of revenue | 32.7% | $1,298 | $7.31 |

**The three pallet inputs (cost, working share, hammer) swing monthly profit from $187 to $3,163** (base $1,572). The fee rate and the average sale price move it by $233 or less.

**What to optimise, in order:**
1. Buying discipline.
2. The quality of the grading.
3. How hard the auction is run.

Only then the fees.

### 2.10 Reinvesting profits to replace a full-time income

Setup for this run:
- **Target:** BLS median full-time weekly earnings, $1,251 (Q2 2026) [W23], = **$5,421/month pre-tax** (model: $1,251 × 52 ÷ 12).
- **Reinvestment:** the owner takes nothing out; after-tax profit goes back into inventory.
- **Show cadence:** may grow to daily, using the same per-show audience ramp.
- **Paid help:** owner hours above 45/week are paid at $18/hour (A).

| Scenario | Start | Month target reached | Inventory then | Monthly revenue | Monthly pre-tax (after paid help) | Paid help/month | Total hours/week |
|---|---|---|---|---|---|---|---|
| Conservative | $5k | not reached in 36 months (best: month 2) | $3,025 | $1,469 | −$62 | $0 | 17 |
| Conservative | $15k | not reached in 36 months (best: month 2) | $9,900 | $4,810 | −$212 | $0 | 35 |
| Base | $5k | not reached in 36 months (best: month 24) | $36,751 | $32,118 | $3,230 | $3,585 | 91 |
| Base | $15k | not reached in 36 months (best: month 18) | $37,684 | $32,118 | $2,634 | $3,902 | 95 |
| Optimistic | $5k | month 4 | $8,372 | $13,439 | $5,490 | $0 | 35 |
| Optimistic | $15k | month 2 | $12,164 | $17,843 | $6,622 | $426 | 50 |

**Base case:** profit levels off at **~$2.6k–$3.2k a month**. That happens once revenue reaches the daily-show audience ceiling (~$32k/month) and about half of the ~90–95 weekly hours have to be paid for.

**Bottom line:** in the base case, one person cannot replace a median paycheck with this model. Only the optimistic inputs get there, in **2–4 months**, at 35–50 h/week.

---

## 3. Time required

### 3.1 Time drivers (inputs)

| Driver | Value | Basis |
|---|---|---|
| Items sold per live hour | 22 | 22–24/h from a new seller's show [W16]. Fast card sellers reach ~100 [W15]. Electronics need on-camera demos [R01], so (A) uses the low figure |
| Minimum show length; prep + post-show admin | 1.5 h; 1.5 h/show | Guides: 2–4 h shows, 1–2 h prep, 1–3 h post-show bundling and shipping [W4]. (A) at the low end, because packing is counted separately |
| Receiving/unpacking per unit processed | 3 min | (A) |
| Testing, cleaning, grading per unit processed | 8 min | (A). No published per-unit triage time was found. Whatnot requires defects to be disclosed in writing and on stream, and untested items go in "For Parts" [R01] |
| eBay photos + listing per item | 15 min | (A), informed by eBay forum anecdotes of 2–10 min to list plus several minutes for photos (search snippets, not verified per post) |
| Packing & shipping per order; customer service per order | 5 min; 2 min | (A). Whatnot gives a 48-hour shipping timer after a show [W16] |
| Sourcing, bookkeeping, promotion | 2–4, 1–2, 1–2 h/week by tier | (A) |

### 3.2 Hours per week by activity (Base, steady state)

| Activity | Part-time ($5k, Base) h/week | Full-time ($15k, Base) h/week |
|---|---|---|
| Sourcing: browsing manifests, bidding, freight quotes | 3.0 | 4.0 |
| Receiving & unpacking (3 min/unit processed) | 1.1 | 3.5 |
| Testing, cleaning, grading (8 min/unit processed) | 2.9 | 9.4 |
| Photographing & listing eBay items (15 min each) | 0.6 | 2.0 |
| Show prep & post-show admin (1.5 h/show) | 3.0 | 6.0 |
| Live streaming | 3.0 | 6.0 |
| Packing & shipping (5 min/order) | 1.3 | 4.4 |
| Customer service, returns, disputes (2 min/order) | 0.5 | 1.8 |
| Bookkeeping, taxes, inventory sheet | 1.5 | 2.0 |
| Promotion: social posts, scheduling, clips | 1.5 | 2.0 |
| **Total** | **18.4** | **41.0** |
| *Units sold per week* | 16 | 53 |
| *Shows per week* | 2.0 | 4.0 |

**Cross-check against benchmarks:**
- Whatnot sellers average 19 h/week (2024) [W1] and 23 h/week (2026 summary) [W3].
- A Reddit seller reported 30–35 h/week for 4 shows a week [W4].
- The guide's own arithmetic is 20–36 h/week at 3–4 shows [W4].
- The model's 18 h (part-time) and 41 h (full-time) are consistent with these. Testing returns is the biggest extra cost compared with collectibles sellers.

### 3.3 Weekly schedules

**Part-time (~18 h/week; $5k Base; 2 shows/week)**

| Day | Block | Hours |
|---|---|---|
| Mon (evening) | Sourcing: scan B-Stock/Liquidation.com/TechLiquidators, set max bids from the formula | 1.5 |
| Tue (evening) | Receive/unpack, test and grade ~20 units; photograph eBay items | 2.5 |
| Wed (evening) | Show prep 0.75 h + **live show 1.5 h** + labels 0.5 h | 2.75 |
| Thu (evening) | Pack & ship Wednesday's orders, customer messages; test more units | 2.5 |
| Fri | eBay listings, social posts/clips for the weekend show | 1.5 |
| Sat (morning) | Sourcing follow-up, freight quotes, bookkeeping | 2.5 |
| Sun (afternoon) | Show prep 0.75 h + **live show 1.5 h**; pack and ship Sunday night/Monday (~1.5 h) | 3.75 |
| Floating | Returns/disputes, promotion | 1.4 |
| **Total** | | **18.4** |

**Full-time (~41 h/week; $15k Base; 4 shows/week)**

| Day | Morning (≈3–4 h) | Afternoon (≈3–4 h) | Evening |
|---|---|---|---|
| Mon | Pack & ship weekend orders; customer service | Sourcing and bidding (2 h); bookkeeping (1 h) | — |
| Tue | Receive pallet; unpack and sort | Test/clean/grade (3 h) | Prep + **live show 1.5 h** |
| Wed | Pack & ship; eBay photos/listings | Test/clean/grade (3 h) | — |
| Thu | Pack & ship | Test/grade (2.5 h); promo clips | Prep + **live show 1.5 h** |
| Fri | Sourcing (2 h); freight follow-up | eBay listings; returns/disputes | — |
| Sat | Test/grade, build show lineups | Prep | **Live show 1.5 h** |
| Sun | Off | Prep | **Live show 1.5 h** |

### 3.4 Ramp-up timeline

| Milestone | Estimate | Evidence |
|---|---|---|
| Audience | Month 1: 0–100 followers, 3–15 viewers/show; months 4–6: 500–1,000 followers, 35–80 viewers; months 6–12: 1,000+ followers, 60–150+ viewers | Underpriced follower guide (updated 2026-07-14), "targets, not guarantees" [W5]. Zero-viewer shows are common early; one seller quit with ~850 followers and almost no sales [W13] |
| Revenue per show | M1 $50–200 → M2–3 $200–500 → M4–6 $500–2,000 → "sustainable" after month 6 | [W4]. Real first shows: $210 at a loss [W12]; $459 rising to ~$790 for a thrift couple [W11] |
| Steady sales | **Months 4–7** for the audience. In the model, capital rather than audience limits revenue from month 2 ($2k–$5k tiers) or month 4 ($15k tier) | Model; [W4] says to judge after 3–6 months |
| Operating break-even | Month 1 (base/optimistic); never (conservative) | Model, Table 2.6 |
| Equipment payback | Months 4–5 (base); month 2 (optimistic) | Model, Table 2.6 and the ramp below |
| Replace a full-time income | Base: not reached solo. Optimistic: months 2–4 with reinvestment. Seller-reported: Philly Phlipper was full-time ~8 months in, with years of eBay inventory sense behind him [W10]; the average live seller in 2024 had been selling only 8 months [W1] | Model 2.10; [W1][W10] |

Base-case ramp, $5k tier (model):

| Month | Capital-limited revenue | Audience-limited revenue | Revenue (lower of the two) | Binding limit | Pre-tax profit | Cumulative after-tax cash vs. $1,385 equipment |
|---|---|---|---|---|---|---|
| 1 | $1,391 | $1,275 | $1,275 | audience | $155 | −$1,269 |
| 2 | $2,781 | $3,569 | $2,781 | capital | $481 | −$908 |
| 3 | $2,781 | $3,569 | $2,781 | capital | $481 | −$548 |
| 4 | $2,781 | $6,118 | $2,781 | capital | $481 | −$187 |
| 5 | $2,781 | $6,118 | $2,781 | capital | $481 | $173 |
| 6 | $2,781 | $6,118 | $2,781 | capital | $481 | $534 |
| 7 | $2,781 | $9,176 | $2,781 | capital | $481 | $894 |

---

## 4. Verdict

### 4.1 Is it worth pursuing, and at what scale?

- **Yes, as a capped experiment of $2k–$5k, part-time (~13–18 h/week), for 90 days.** Downside: the conservative case loses about $35–$61/month on top of the $470–$1,385 equipment, much of which resells. The test's job is to measure the three numbers that decide everything: landed % of retail, working %, and hammer % of retail.
- **Scale to $15k and full time only if the measured inputs reach the optimistic column.** At base inputs, $15k of capital and 41 h/week pay **$8.85/hour pre-tax**. Even reinvesting everything, profit levels off around **$3k/month** before tax once help is paid.
- **Don't use expensive credit unless the measured per-cycle ROI is above ~25%.** A 0% promotional card is fine for funding a second lot once lot 1 meets its numbers.

### 4.2 Key risks

| Risk | Why it matters here | Evidence | Mitigation |
|---|---|---|---|
| Bad pallets | One bad lot (−33% per cycle) wipes out ~1 base-case cycle of profit on the same money | Only 13% of electronics pallets are New/Like New; Best Buy returns have "the worst failure rates" [R01]; a $2,500 pallet was full of broken units [W17]; Amazon pallets "rarely" net more than 5% [W29] | Buy graded or manifested lots; cap any one lot at 40% of capital [R01]; bid from the formula, not from the "MSRP" headline |
| Slow audience growth | Revenue below capital capacity in months 1–3 is pure overhead | ~850 followers, no sales [W13]; big followings with ~15 viewers [W14]; frequency drives earnings 10–250× [W2] | Fixed schedule; $1 starts; bid-drivers [R03]; giveaways budgeted at 3–5% |
| Burnout | The labour is the real cost: about 620–2,300 h/year in year 1 (Table 2.7). Shows run longer than planned | 5 h 10 m show "two hours longer than I thought" [W16]; 69% of sellers go live daily [W1]; "below minimum wage" anecdotes [W3] | Use $/hour as the KPI; batch testing; cap show length; hire packing help before adding shows |
| Platform policy and fee changes | 5% vs 8% commission is worth ~$230/month at $15k Base (2.9) | New tiered fees from 2026-09-21 [R01]; conflicting electronics rate [W4][W9]; Whatnot may refund buyers "for reasons outside the seller's control" [W26] | Re-check fees in Seller Hub monthly; keep eBay as a fallback channel |
| Chargebacks, "not as described" claims, returns | Electronics fail after the sale; refunds hit revenue directly | Buyer protection covers items not as described; returns must ship within 5 business days of approval; sellers can dispute returns [W26][W27] | Test on camera; disclose defects verbally and in writing [R01]; keep test logs and serial numbers |
| Tariffs and imports | Generic China-made filler items can go negative | ~37.5% stacked duties on China-origin electronics [R03] | Stick to domestic returns; buy imports only at volume pricing |
| Compliance | Some lots need e-waste agreements; lithium batteries have shipping rules; you need resale certificates and sales-tax handling | Walmart electronics lots need R2/e-Stewards [R01]; hazmat rules [R01] | Read lot terms before bidding |

### 4.3 Go/no-go milestones

| Checkpoint | Go if ALL of these hold | Stop or pivot if |
|---|---|---|
| **Day 30** | ≥1 lot fully processed. Measured landed cost ≤25% of retail; working share ≥70%; ≥8 shows held; average ≥$150/show; refunds ≤5% | Working share <60%, or landed cost >30% of retail on the first lot |
| **Day 60** | Lot ROI after fees ≥+25% (= m × (1 − v) − 1 using measured inputs); ≥50% of lot 1 sold within 45 days of arrival; average ≥$350/show and 10–30 viewers; pre-tax ≥$10/hour on tracked hours | Lot ROI <+10%, or <$200/show after 16 shows |
| **Day 90** | Trailing-30-day pre-tax profit ≥$1,000 (part-time) **and** ≥$15/hour; equipment paid back; cash cycle ≤60 days; 250–500 followers [W5]. To scale to $15k/full time: measured inputs at or near the optimistic column (landed ≤20%, working ≥85%, hammer ≥55%) | Two or more Day-90 checks fail: stop, sell the equipment, or switch to eBay-only graded single-SKU lots |

---

## 5. How to update the model

1. Track three numbers per lot:
   - landed cost ÷ manifest retail
   - working units' retail ÷ total retail
   - hammer ÷ retail on working units
2. Put them into `cost`, `sell` and `hammer` in Section 8 and re-run `python3 model.py`.
3. Replace `comm` with the electronics commission shown in your Seller Hub.
4. Replace `cycle` with the days from wire transfer to the last payout for each lot.

---

## 6. Method and limitations

- **Reddit was not reachable.** `old.reddit.com` and `reddit.com` JSON returned blocked/HTML pages to automated requests, and the search tool refused the reddit.com domain. Reddit seller voices appear only second-hand [W4].
- **YouTube data are auto-caption transcripts.** They were downloaded with `yt-dlp` and searched for figures. Spoken numbers can be mis-transcribed. Each claim above was read in context.
- **The Whatnot Help Center returned HTTP 403.** Fee and protection terms come from search snippets and third-party summaries. The 5% vs 8% electronics commission conflict is unresolved.
- **No independent survey of reseller net margins or hours** was found. Whatnot's reports are vendor-published, survey only active sellers (survivor bias), and report revenue, not profit.
- **Model simplifications:**
  - inventory capital is constant (profits withdrawn) except in 2.10;
  - no seasonality (Q4 likely stronger);
  - the 25% tax set-aside is a rule of thumb, and losses get no tax credit;
  - equipment is not depreciated;
  - the owner's time is unpaid except in 2.7 and 2.10.

---

## 7. Sources

| ID | Source | Date |
|---|---|---|
| W1 | Whatnot, "2024 State of Livestream Selling Report" (PDF, with Wakefield Research) — https://blog.teamwhatnot.com/s/Whatnot_State_of_Livestream_Selling_Report.pdf | Published Oct 2024; observed 2026-10-09 |
| W2 | Whatnot, "2026 State of Live Selling Report" — https://blog.teamwhatnot.com/unitedstates/2026livesellingreport | Published 2026-01-28; observed 2026-10-09 |
| W3 | Value Added Resource, "Whatnot 2026 Live Selling Report: Growth, Friction…" — https://www.valueaddedresource.net/whatnot-2026-live-selling-report/ | 2026-01-30, updated 2026-03-07; observed 2026-10-09 |
| W4 | Underpriced, "Whatnot Selling Guide 2026: Is Livestream Flipping Worth It" — https://www.underpriced.app/blog/whatnot-selling-guide-2026 | Updated 2026-10-01; observed 2026-10-09 |
| W5 | Underpriced, "Grow Your Whatnot Audience to 1K Followers" — https://www.underpriced.app/blog/grow-whatnot-audience-followers-guide | Updated 2026-07-14; observed 2026-10-09 |
| W6 | Underpriced, "Liquidation Pallets: 3 Sources for 30–80% ROI in 2026" (case labelled illustrative) — https://www.underpriced.app/blog/liquidation-pallet-flipping-guide-2026 | Observed 2026-10-09 |
| W7 | BundleLive, "The 2026 Whatnot Seller Income Report" (vendor estimates) — https://bundlelive.com/blog/whatnot-seller-income-report-2026 | 2026-02-15; observed 2026-10-09 |
| W8 | BundleLive, "How to Handle Returns and Refunds on Whatnot" — https://bundlelive.com/blog/whatnot-returns-refunds-guide | 2026-02-15; observed 2026-10-09 |
| W9 | Crosslist, "Whatnot Fees for Sellers" — https://crosslist.com/blog/whatnot-fees-for-sellers | Updated 2026-09-30; observed 2026-10-09 |
| W10 | Philly Phlipper, "I sold $125,000 in 4 months on whatnot…" — https://www.youtube.com/watch?v=1SL7X-W4q2c | Uploaded 2025-05-21; transcript observed 2026-10-09 |
| W11 | Trash Pandas Thrift, "$9,153 Our First Month As A New Whatnot Seller" — https://www.youtube.com/watch?v=33NC6gXo6mg | Uploaded 2024-05-12 |
| W12 | Kevin Toomey, "Is Selling on Whatnot Worth it in 2026? (Tips From A First Timer)" — https://www.youtube.com/watch?v=gR4rEyiRNd4 | Uploaded 2025-12-19 |
| W13 | Kate's Fashion Flipz, "WhatNot Is NOT Worth It - Here's Why" — https://www.youtube.com/watch?v=3LNLMHrTbW0 | Uploaded 2025-08-19 |
| W14 | Cayley Elaine, "Harsh Truths About Selling on Whatnot" — https://www.youtube.com/watch?v=7s5n67c44wQ | Uploaded 2025-09-12 |
| W15 | TY WILSON, "The BRUTAL TRUTHS from SELLING on WHATNOT!" — https://www.youtube.com/watch?v=bkRZQC6dfIE | Uploaded 2026-01-23 |
| W16 | Stephanie Canada, "I tried selling on WhatNot and here is my HONEST review" — https://www.youtube.com/watch?v=_xZvxWwvK5U | Uploaded 2026-06-29 |
| W17 | SarahGrace, "I Bought a CHEAP Best Buy Return Pallet" — https://www.youtube.com/watch?v=xW79xkCFe0k | Uploaded 2024-11-30 |
| W18 | Threecolts, "How to buy and sell Amazon return pallets" — https://www.threecolts.com/blog/amazon-return-pallets/ | 2025-05-15; observed 2026-10-09 |
| W19 | AmzScout, "Amazon Return Pallets" — https://amzscout.net/blog/amazon-return-pallets/ | Dated "03.02.2026"; observed 2026-10-09 |
| W20 | Best Buy Co., Form 10-K FY2025 — https://www.sec.gov/Archives/edgar/data/764478/000076447825000007/bby-20250201x10k.htm ; XBRL figures from https://data.sec.gov/api/xbrl/companyfacts/CIK0000764478.json | FY ended 2025-02-01; observed 2026-10-09 |
| W21 | FRED, TERMCBCCINTNS, commercial bank credit-card rate, accounts assessed interest (22.36%, Aug 2026) — https://fred.stlouisfed.org/data/TERMCBCCINTNS | Updated 2026-10-07; observed 2026-10-09 |
| W22 | IRS, "Self-employment tax (Social Security and Medicare taxes)" — https://www.irs.gov/businesses/small-businesses-self-employed/self-employment-tax-social-security-and-medicare-taxes | Observed 2026-10-09 |
| W23 | BLS, "Usual Weekly Earnings of Wage and Salary Workers, Second Quarter 2026" ($1,251) — https://www.bls.gov/news.release/wkyeng.nr0.htm | Released 2026-07-21; observed 2026-10-09 |
| W24 | Walmart ring-light/tripod kit listings ($24.97, $47.54, $54.62) — https://www.walmart.com/c/kp/influencer-kit | Via search results, 2026-10-09 |
| W25 | Rollo printer and label prices: eBay X1038 new $169.99 — https://www.ebay.com/itm/116043673472 ; Walmart Rollo wireless $284.98 and labels — https://www.walmart.com/c/kp/rollo-printer-etsy | Via search results, 2026-10-09; used ~$110 from the same results |
| W26 | Whatnot Help Center, "Whatnot Buyer Protection" — https://help.whatnot.com/hc/en-us/articles/360061194552-Whatnot-Buyer-Protection | Via search results, 2026-10-09 (direct fetch 403) |
| W27 | Whatnot Help Center, "Seller Provided Support for Sellers" — https://help.whatnot.com/hc/en-us/articles/26528358542349-Seller-Provided-Support-for-Sellers | Via search results, 2026-10-09 (direct fetch 403) |
| W28 | eBay Community, "Sell-Through Rates – Practical Applications" — https://community.ebay.com/t5/Selling/Sell-Through-Rates-Practical-Applications/m-p/34395818 | Posts "2 years ago"; observed 2026-10-09 |
| W29 | AOL Lifestyle, "Who keeps buying return boxes—and when it usually goes wrong" — https://www.aol.com/lifestyle/keeps-buying-return-boxes-usually-151000848.html | Via search snippet 2026-10-09; page returned 404 on fetch, so treat as unverified |
| R01 | Companion report `research/whatnot/01-pallet-sourcing.md` (PR mdb1230/Agent-Reach#1), citing BStalker, B-Stock, Liquidation.com and Direct Liquidation data | Observed 2026-10-09 |
| R03 | Companion report `research/whatnot/03-cheap-bulk-auction-winners.md` (work in progress, branch `office/nibble-65a9`) | Observed 2026-10-09 |

---

## 8. Appendix: the model (Python 3, no dependencies)

Save as `model.py`. `run(SCEN["Base"], 15000)` returns inventory, 24 monthly rows, first profitable month and payback month. Month index 12 is the steady state used in the tables. Re-running it reproduces every table in Section 2.

```python
"""Whole-business model for the Whatnot electronics resale report (04).
Every input is in the dicts below; the report prints the same tables."""

TIERS = {  # capital tier -> setup
    2000:  dict(capex=None, shows_wk=2, fixed=60,  src_h=2.0, books_h=1.0, promo_h=1.0),
    5000:  dict(capex=None, shows_wk=2, fixed=120, src_h=3.0, books_h=1.5, promo_h=1.5),
    15000: dict(capex=None, shows_wk=4, fixed=400, src_h=4.0, books_h=2.0, promo_h=2.0),
}
CAPEX = {  # itemised startup equipment per tier
    2000: [("Ring light + tripod/phone mount kit", 50), ("Clip-on mic", 25),
           ("Thermal label printer (used 4x6)", 110), ("4x6 labels, 500", 20),
           ("Shipping scale", 25), ("Test kit: USB-C/USB power meter, chargers, cables, batteries", 60),
           ("1 steel shelving unit", 80), ("Starter boxes, mailers, bubble wrap, tape", 100)],
    5000: [("Ring light + 2 softbox lights", 140), ("Lavalier/USB mic", 60),
           ("Second (used) phone for overhead/product cam", 250), ("Tripods/overhead arm", 60),
           ("Thermal label printer (new 4x6)", 170), ("4x6 labels, 1,000", 40),
           ("Shipping scale", 25), ("Test bench: power meter, multimeter, HDMI monitor, chargers, cables", 200),
           ("3 steel shelving units", 240), ("Boxes, mailers, bubble wrap, tape", 200)],
    15000: [("Laptop/PC for multi-camera streaming software", 800), ("2 cameras/webcams", 300),
            ("Lighting kit (key, fill, backdrop)", 200), ("USB/XLR mic", 120), ("Stream deck/capture misc.", 100),
            ("Wireless thermal label printer", 285), ("4x6 labels, 2,000", 80), ("Shipping scale", 25),
            ("Test bench: power meter, multimeter, monitor, console/TV test station, chargers", 400),
            ("6 steel shelving units + bins", 560), ("Boxes, mailers, bubble wrap, tape", 400)],
}
for k in TIERS:
    TIERS[k]["capex"] = sum(v for _, v in CAPEX[k])
RESERVE = 0.10  # share of capital kept as cash buffer

SCEN = {
    "Conservative": dict(cost=0.24, sell=0.70, hammer=0.48, salvage=0.03, asp=30, comm=0.08,
                         pack=1.00, promo=0.05, refunds=0.05, cycle=90,
                         show=[50, 200, 200, 350, 350, 350, 500]),
    "Base":         dict(cost=0.22, sell=0.75, hammer=0.50, salvage=0.05, asp=40, comm=0.08,
                         pack=0.75, promo=0.04, refunds=0.03, cycle=60,
                         show=[125, 350, 350, 600, 600, 600, 900]),
    "Optimistic":   dict(cost=0.20, sell=0.85, hammer=0.55, salvage=0.05, asp=50, comm=0.05,
                         pack=0.60, promo=0.03, refunds=0.02, cycle=45,
                         show=[200, 500, 500, 1200, 1200, 1200, 1500]),
}
EBAY_SHARE, EBAY_PCT, EBAY_FIX = 0.15, 0.136, 0.40
PROC_PCT, PROC_FIX, BUYER_TAX, BUYER_SHIP = 0.029, 0.30, 0.07, 8.00
TAX = 0.25
WK = 52 / 12  # weeks per month
DPM = 365 / 12  # days per month
# hours
H_PREP = 1.5           # prep + post-show admin per show (lineup, lights, labels batch)
ITEMS_PER_LIVE_H = 22  # auction items sold per live hour
MIN_LIVE_H = 1.5       # shortest worthwhile show
ITEMS_PER_SHOW = 60    # target lineup; fewer shows if inventory is thin
MIN_RECV, MIN_TEST, MIN_PACK, MIN_CS, MIN_EBAY_LIST = 3, 8, 5, 2, 15
CC_APR = 0.2236
DEBT_RATIO = 0.5


def multiple(s):  # revenue per $1 of landed inventory cost
    return (s["sell"] * s["hammer"] + (1 - s["sell"]) * s["salvage"]) / s["cost"]


def var_ratio(s):  # variable costs per $1 of revenue
    p = s["asp"]
    wn = s["comm"] * p + PROC_PCT * ((1 + BUYER_TAX) * p + BUYER_SHIP) + PROC_FIX
    eb = EBAY_PCT * p + EBAY_FIX
    fee = ((1 - EBAY_SHARE) * wn + EBAY_SHARE * eb) / p
    return fee + s["pack"] / p + s["promo"] + s["refunds"], fee


def month(s, t, K, inv, debt=0.0, demand_shows_wk=None):
    tier = TIERS[K]
    m = multiple(s)
    v, _ = var_ratio(s)
    cap_rev = (inv + debt) * m * DPM / s["cycle"] * (0.5 if t == 1 else 1.0)
    per_show = s["show"][min(t, 7) - 1]
    demand = (demand_shows_wk or tier["shows_wk"]) * WK * per_show / (1 - EBAY_SHARE)
    rev = min(cap_rev, demand)
    uw = rev * (1 - EBAY_SHARE) / s["asp"]  # Whatnot units
    shows = max(tier["shows_wk"] * WK, uw / ITEMS_PER_SHOW)  # fixed cadence; more shows only if inventory overflows
    cogs = rev / m
    var = rev * v
    interest = debt * CC_APR / 12
    pretax = rev - cogs - var - tier["fixed"] - interest
    units = rev / s["asp"]
    hours = (shows * H_PREP + max(shows * MIN_LIVE_H, uw / ITEMS_PER_LIVE_H)
             + units / s["sell"] * (MIN_RECV + MIN_TEST) / 60
             + units * (MIN_PACK + MIN_CS) / 60
             + units * EBAY_SHARE * MIN_EBAY_LIST / 60
             + (tier["src_h"] + tier["books_h"] + tier["promo_h"]) * WK)
    return dict(rev=rev, cap=cap_rev, demand=demand, cogs=cogs, var=var, pretax=pretax,
                net=pretax * (1 - TAX) if pretax > 0 else pretax, hours=hours, units=units,
                bound="capital" if cap_rev <= demand else "demand", interest=interest, shows=shows,
                live=max(shows * MIN_LIVE_H, uw / ITEMS_PER_LIVE_H))


def run(s, K, debt=0.0, months=24):
    inv = K - TIERS[K]["capex"] - RESERVE * K
    rows = [month(s, t, K, inv, debt) for t in range(1, months + 1)]
    cum, payback, be = -TIERS[K]["capex"], None, None
    for t, r in enumerate(rows, 1):
        cum += r["net"]
        if be is None and r["pretax"] > 0:
            be = t
        if payback is None and cum >= 0:
            payback = t
    return inv, rows, be, payback


HIRE_WAGE, OWNER_MAX_H_WK = 18.0, 45.0


def run_reinvest(s, K, months=36, max_shows_wk=7):
    """Owner draws nothing; after-tax profit goes back into inventory. Shows can grow to daily;
    owner hours above OWNER_MAX_H_WK are paid help at HIRE_WAGE."""
    inv = K - TIERS[K]["capex"] - RESERVE * K
    out = []
    for t in range(1, months + 1):
        r = month(s, t, K, inv, demand_shows_wk=max_shows_wk)
        hire = max(0.0, r["hours"] - OWNER_MAX_H_WK * WK) * HIRE_WAGE
        r["pretax"] -= hire; r["hire"] = hire
        r["net"] = r["pretax"] * (1 - TAX) if r["pretax"] > 0 else r["pretax"]
        out.append((t, inv, r))
        inv += r["net"]
        if inv <= 0:
            break
    return out
```
