# 03: Cheap bulk electronics that win at auction (Whatnot first, eBay as a reference)

*Research report, not a product change. Prepared 2026-10-09. Unless a source says otherwise, every web source below was observed on **2026-10-09**. Numbers in **bold italics** or marked "(est.)" are modelled estimates. Every input is either cited `[S#]` or labelled as an assumption `[A#]`.*

Scope: **which** low-unit-cost electronics draw bids and clear above cost on Whatnot live auctions, and **where** to buy them in bulk. Liquidation pallet suppliers and Whatnot fees/margins are covered in separate reports. This one only re-states the fee inputs the per-unit math needs.

---

## TL;DR

1. **2026 import costs change the usual answer.** China-origin consumer electronics now carry about **37.5%** in stacked Section 301 duties (25% product list plus 12.5% forced-labor action) [S7], and air freight costs about **$6.90/kg** [S9]. Add Whatnot's fees and many classic generic "Whatnot electronics" items at their typical prices **break even or lose money per unit**: TWS earbuds, power banks, LED strips, ring lights, karaoke mics and HY300 projectors (rows 14–20 below).
2. **The best per-unit profit comes from domestic secondary-market goods:**
   - used video games bought in bulk lots
   - genuine branded audio pulled from returns lots
   - tested/cleaned used controllers
   - light, cheap generics whose freight and duty stay small (RGB mice, Y68-class watches, USB-C cables)
3. **Genuine AirPods are a trap to buy on purpose.** Used-like-new costs ~$64.80 [S67], above the ~$50–55 they fetch on Whatnot [S25]. Counterfeit risk is also the highest of any item here. Sell them only when they come inside a lot, and authenticate first.
4. **Avoid entirely:**
   - "1:1", "AAA+++" or "Top1-level" AirPods-style earbuds and "Original charger for iPhone" listings. Suppliers openly sell these [S95–S99], and Whatnot treats branded lookalikes as counterfeit [S10].
   - "Jailbroken / fully loaded" Fire TV Sticks [S51].
   - R36S handhelds sold with ROM-loaded cards (IP risk; see §5).

---

## 1. Ranking table (sorted by estimated net profit per unit on Whatnot)

How to read it:
- **Landed** = what one *sellable* unit costs you. It includes duty, freight and a defect/unusable allowance.
- **Auction price** = the expected hammer price at a $1 start (est.), anchored on the Whatnot listing and price-tracker comps in §2.
- **Fees** use Whatnot's electronics rate: 5% commission [S1][S2] plus 2.9% + $0.30 processing on item + tax + shipping [S1]. The formula is in §3.
- **Net** = auction price − fees − landed − $0.50 packaging [A6].
- **Break-even** = the lowest hammer price at which you don't lose money. It is the most useful number for $1-start decisions.

All money values are **estimates** derived from the cited inputs and labelled assumptions.

| # | Item | Genuine / generic | Bulk source (MOQ) | Landed unit cost (est.) | Typical auction price (est.) | Whatnot fees (est.) | **Est. net / unit** | Net if commission is 8% | Break-even hammer | Demand | Risk notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | JBL Go 4 (and similar branded mini speakers) from returns lots | Genuine, returns | Mixed electronics returns lot. Cost allocated at 18.9% of $49.95 retail [S79][S65], +20% buyer fee/freight [A8], 75% working [A7] | $15.10 | $25 [A9] | $2.41 | **$6.98** | $6.23 | $17.40 | Med–High | You can't buy only JBLs. The mix is random. Test on camera. |
| 2 | Used PS5 DualSense, tested/cleaned | Genuine, used | As-is controller lots, ~$22/unit [A10] (informed by [S78]), 70% usable [A11] | $31.43 | $40 (Whatnot $28–$52 [S46][S47][S48]; PriceCharting loose $38.85 [S60]) | $3.63 | **$4.44** | $3.24 | $35.16 | High | Stick drift. Repair time. Lot pricing data is from 2025. |
| 3 | RGB wired gaming mouse (K1013 class) | Generic | Made-in-China $2.57–2.83, MOQ not listed [S93] | $5.38 | $10 (Whatnot listing $10 [S41]) | $1.20 | **$2.92** | $2.62 | $6.82 | Med | Low ticket. Bundle with a keyboard combo (Whatnot $17, seller shows 341 sold [S42]). |
| 4 | Budget smartwatch, Y68/D20 class | Generic | Made-in-China Y68 $2.71–3.21, **MOQ 800** [S88] | $5.39 | $10 [A9] (Whatnot generic watches $15–$21 [S30][S31][S32]) | $1.20 | **$2.91** | $2.61 | $6.83 | Med | MOQ 800 is about $4.3k landed, too big for these budgets. Make no medical claims. Use no Apple/Samsung marks. |
| 5 | Mixed returns "pull" (average working unit) | Mixed brands | Walmart/B-Stock consumer-electronics lot: $2,913 final bid / 461 units = $6.32/unit [S79], +20% [A8], 75% working [A7] | $10.11 | $15 [A9] | $1.60 | **$2.79** | $2.34 | $11.97 | Med | Must follow Whatnot Surprise Sets rules if sold blind [S12][S13]. |
| 6 | Used PS4 / Xbox One games (common titles) | Genuine, used | eBay bulk lot: 80 Xbox One games $119.99 [S76] + $14.99 shipping [A12], 90% sellable [A13] | $1.87 | $6 [A9] (PriceCharting common PS4 loose $4–$15 [S63]) | $0.87 | **$2.75** | $2.57 | $3.01 | High | Scratched discs. Check which Whatnot category (and rate) games fall under. |
| 7 | Apple AirTag 4-pack, sealed, bought on sale | Genuine, new | Retail sale $63 ($15.75 each) [S66] | $63.00 | $72 (Whatnot asks $70 and $75 [S49][S50]) | $6.22 | **$2.28** | $0.12 | $69.52 | Med | Works only at sale prices. A Gen 2 exists, per a Slickdeals commenter [S66]. A good traffic driver, a poor profit item. |
| 8 | R36S retro handheld (blank / no-ROM card) | Generic | AliExpress US-warehouse ~$23–$27 delivered [S69] (used $25 [A14]), 5% DOA [A5] | $26.32 | $32 (Whatnot $24–$59 [S20][S21][S22]; eBay ask $32.99 [S74]) | $2.98 | **$2.20** | $1.24 | $29.60 | High | The default "20,000+ games" card is pirated ROMs. See §5. |
| 9 | Mini camera drone (toy class) | Generic | Made-in-China mini RC drone $14, MOQ 48 [S92]. Lithium freight [A4] | $25.53 | $30 (Whatnot $29.99 [S43]; $35 [S45]; $5 low [S44]) | $2.82 | **$1.16** | $0.26 | $28.74 | Med | Li-po batteries. FCC radio rules. Wide price spread. |
| 10 | Galaxy/astronaut star projector | Generic | Made-in-China $5.00–6.35, MOQ 50 [S89] | $11.90 | $15 [A9] (Whatnot $4–$38 [S27][S28][S29]; Walmart $9.88–$49.99 [S75]) | $1.60 | **$1.00** | $0.55 | $13.91 | Med | Bulky for its price. Sea freight makes it work (§4). |
| 11 | USB-C cable (bid-driver) | Generic | Made-in-China $0.30–0.60, MOQ 1,000 [S94] | $1.02 | $3 [A9] | $0.63 | **$0.85** | $0.76 | $2.07 | High as a $1 start (cables appear in $1-start show titles [S53]) | Price is an assumption. Use a branded OEM line (e.g., LDNIO [S94b]) if you need MOQ 10. |
| 12 | Budget smartwatch, 1.52" IPS | Generic | Made-in-China $7.66–7.82, MOQ 100 [S87] | $12.31 | $15 (Whatnot $15–$21 [S30][S31][S32]) | $1.60 | **$0.59** | $0.14 | $14.36 | Med | Thin margin. |
| 13 | Kids digital camera | Generic | Made-in-China $5.99, MOQ 100 [S90] | $10.14 | $12 (Whatnot $12, seller shows 71 sold [S36]) | $1.36 | **$0.00** | −$0.36 | $12.00 | Med | Children's product: CPSIA testing/CPC needed [A15]. |
| 14 | USB 5 m LED strip, sound-reactive | Generic | Made-in-China $3.65–4.05, MOQ 100 [S91] | $7.78 | $8 (Whatnot $5–$26 [S39][S40]) | $1.04 | **−$1.32** | −$1.56 | $9.43 | Med | Low ticket. |
| 15 | Generic TWS earbuds | Generic | Made-in-China "Xy-16" $4.00–8.50, MOQ 30 [S85] | $10.15 | $10 (Whatnot $5–$14 [S23][S24]) | $1.20 | **−$1.85** | −$2.15 | $12.01 | High | The category is full of AirPods lookalikes. Sell only plain, unbranded designs [S10]. |
| 16 | 10,000 mAh 20 W power bank | Generic | Made-in-China $6.80–7.80, MOQ 20 [S86]. Lithium freight [A4] | $13.72 | $12 (Whatnot $5–$20 [S33][S34][S35]) | $1.36 | **−$3.58** | −$3.94 | $15.90 | High | Dangerous-goods freight. Fire/recall liability. |
| 17 | HY300 mini projector | Generic | Made-in-China $21.90–26.90, MOQ 20 [S84] | $44.16 | $45 (Whatnot mini projector $67 ask [S26]) | $4.03 | **−$3.69** | −$5.04 | $49.02 | Med | Heavy. Positive only on sea freight or a DDP deal (§4, [S72]). |
| 18 | 10" ring light with stand | Generic | Made-in-China $5.75, MOQ 500 [S83] | $14.22 | $10 (Whatnot $10 [S38]) | $1.20 | **−$5.91** | −$6.21 | $16.44 | Low | Freight weight kills it. |
| 19 | Bluetooth karaoke mic | Generic | Made-in-China $6.11–8.56, MOQ 50 [S91b] | $14.30 | $9 (Whatnot $8, seller shows 507 sold [S37]) | $1.12 | **−$6.92** | −$7.19 | $16.53 | Med | Good demand, wrong cost base. |
| 20 | Apple AirPods 4, open-box/used | Genuine | Amazon used-like-new $64.80 [S67] | $64.80 | $55 [A9] (Whatnot open-box $50 [S25]) | $4.84 | **−$15.14** | −$16.79 | $71.48 | High | Highest counterfeit risk. Never buy to flip. Authenticate any you get inside a lot. |

**eBay as a reference:** eBay's standard final value fee is **13.6% + $0.40 per order over $10 ($0.30 at $10 or less)** [S4]. At the same hammer prices, eBay fees run about 13% higher than Whatnot's at a $3 ticket and about 60–65% higher at $25–$72 (e.g., $0.71 vs $0.63 at $3; $3.80 vs $2.41 at $25; $10.19 vs $6.22 at $72; model output, excluding the final value fee on shipping). eBay therefore makes sense as the overflow channel for higher-ticket genuine items (controllers, AirTags, speakers), not for $3–$10 generics.

---

## 2. Demand evidence by item type (part 1 of the brief)

Whatnot's own 2026 report lists **Electronics +444%** among the fastest-growing categories of 2025 [S5]. A secondary source puts electronics at ~8% of live sellers [S3]. Another says electronics is not a gated category and names cables, chargers, headphones and small accessories as suitable live-sale products; that part is the author's opinion [S6]. Typical Whatnot "Everyday Electronics" shows advertise **$1 starts** with earbuds, power banks, cables, smartwatch gear, Apple items, gaming and "pallet pulls" [S53][S54][S55].

Two caveats apply to every comp below:
- **Whatnot listing pages show the listing/BIN price, not the auction hammer.**
- **The "sold" counts on those pages are the seller's lifetime total, not sales of that item.**

Treat both as demand signals, not sell-through rates. eBay sold/completed search, Reddit and Whatnot's live pages all returned HTTP 403 to automated fetches during this research (see §8), so no true auction sell-through percentage could be measured.

| # | Item type | Genuine / generic | Price evidence (date observed 2026-10-09 unless noted) | Demand signal |
|---|---|---|---|---|
| 1 | Generic TWS earbuds | Generic | Whatnot $5 (seller 2K sold, 4.9★) [S23]; $14 sealed [S24] | Staple of $1-start shows [S53] |
| 2 | AirPods 4 | Genuine | Whatnot open-box $50 [S25]; Amazon used-like-new $64.80 [S67] | High interest, high fraud |
| 3 | Power banks 10k mAh | Both | Whatnot $5 (Heyday, 150 available) [S33], $9 [S34], $20 [S35] | Named in show titles [S53][S54] |
| 4 | USB-C cables/chargers | Generic | No hammer comp found; $3 is assumption [A9] | Named in show titles [S53] |
| 5 | Generic smartwatches | Generic | Whatnot $15 [S30], $19.99 [S31], $21 [S32] | "Smartwatch gear" in $1-start shows [S53] |
| 6 | Bluetooth speakers (JBL) | Genuine | Walmart JBL Go 4 $39.95 (was $49.95) [S65] | Branded audio is a common lot-pull hook [S55] |
| 7 | Galaxy/star projectors | Generic | Whatnot $4 [S28], $29.99 [S27], $38 [S29]; Walmart $9.88–$49.99 [S75] | Moderate |
| 8 | LED strips | Generic | Whatnot $5 [S39], $17 (30 m) [S40] | Moderate |
| 9 | Ring lights | Generic | Whatnot 10" $10 [S38] | Low |
| 10 | Retro handhelds (R36S) | Generic | Whatnot $24 (seller 503 sold) [S20], $50 [S22], $59 sealed (seller 3.2K sold) [S21]; eBay ask $32.99 [S74] | Strong; "retro handhelds" named as a Whatnot winner [S3] |
| 11 | Anbernic RG35XX family | Genuine brand | AliExpress RG35XX Plus $35.61 delivered from a US warehouse (Mar 2026) [S73] | Strong in retro shows [S3] |
| 12 | PS5 DualSense | Genuine | Whatnot $28 [S47], $50 [S46], $52 open-box [S48]; PriceCharting loose $38.85 / new $62.49 [S60] | High |
| 13 | Xbox Series controller | Genuine | PriceCharting loose $24.45 / new $44.99 [S62] | High (no bulk cost found, not ranked) |
| 14 | Joy-Con pair | Genuine | PriceCharting loose $36.95 / new $57.49 [S61] | High (no bulk cost found, not ranked) |
| 15 | Switch Lite | Genuine | PriceCharting loose $100 / CIB $117.50 [S64] | High ticket. Outside the "cheap bulk" brief. |
| 16 | Used games (PS4/Xbox One) | Genuine | PriceCharting common PS4 loose $4–$15 (GTA V $8.05) [S63] | High; "retro/JRPG/Pokémon" are the strongest [S3] |
| 17 | Mini projectors | Generic | Whatnot $67 [S26] | Moderate |
| 18 | Mini drones | Generic | Whatnot $29.99 (33 sold) [S43], $5 [S44], $35 [S45] | Moderate, wide spread |
| 19 | Kids cameras | Generic | Whatnot $12 (seller 71 sold) [S36] | Moderate (gift season) |
| 20 | Karaoke mics | Generic | Whatnot $8 (seller 507 sold) [S37] | Moderate |
| 21 | RGB mouse / keyboard combos | Generic | Whatnot mouse $10 [S41]; KB+mouse $17 (seller 341 sold) [S42] | Moderate |
| 22 | AirTags | Genuine | Whatnot 4-pack $70 [S49] / $75 [S50]; retail sale $63 [S66], $57 seen [S66b] | Moderate |
| 23 | Fire TV Stick (stock) | Genuine | Whatnot 1st-gen open-box $20 [S52] | **Avoid "jailbroken" listings** [S51] |
| 24 | Amazon/Walmart returns "pulls" | Mixed | Walmart/B-Stock lot $6.32/unit avg [S79] | Common show format [S55] |
| 25 | Phone cases | Generic | Made-in-China $0.42–$2.10 [S97b] | No Whatnot hammer comp found; not ranked |

---

## 3. Fee and cost model (assumptions)

| ID | Assumption | Value | Basis |
|---|---|---|---|
| A1 | Whatnot commission, electronics | **5%** of item price (8% sensitivity column) | Crosslist, updated 2026-09-30 [S1]; Feescal, Mar 2026 [S2]. **Conflict:** Underpriced (2026-10-01) says 8% for every category except coins [S3]. Whatnot's help page returned 403, so the 8% case is shown too. |
| A1b | Whatnot processing | 2.9% + $0.30 on item + shipping + tax | [S1][S2] |
| A2 | China import duty stack | **37.5%** of FOB (25% Sec. 301 + 12.5% forced-labor Sec. 301, eff. 2026-07-24) | TariffsTool [S7]. CustomsBrokerUSA (2026-07-13) lists the 12.5% as proposed and some items at 7.5% [S8]. Confirm by HTS code. |
| A3 | Air freight | $7.00/kg (rounded up from $6.90) × assumed packed weight per unit | Freightos via Bloomberg, Mar 2026 [S9]. Unit weights are assumptions (0.05–1.2 kg). |
| A4 | Lithium-battery (DG) air freight | $10/kg | Assumption. A higher DG rate is plausible, but no current quote was found [S9]. |
| A5 | Defect/DOA allowance, new generics | 5% | Assumption |
| A6 | Packaging per unit | $0.50 | Assumption |
| A7 | Working rate in returns lots | 75% | Assumption |
| A8 | Liquidation buyer fee + LTL freight | +20% on winning bid | Assumption. B-Stock adds a buyer fee not shown in final bids [S79]. |
| A9 | Hammer prices where no direct comp exists | As stated in table | Assumption, anchored on nearest comps |
| A10 | As-is DualSense cost | ~$22/unit | Assumption, informed by 2025 eBay as-is lot sales of roughly C$20–30/controller [S78] |
| A11 | Usable rate after cleaning/repair | 70% | Assumption |
| A12 | Shipping on 80-game lot | $14.99 | Assumption, from a similar 80-game lot listing (search snippet) |
| A13 | Sellable share of a game lot | 90% | Assumption |
| A14 | R36S delivered price | $25 | Midpoint of $23–$27 AliExpress US-warehouse deals [S69][S70] |
| A15 | Kids' products need CPSIA third-party testing and a Children's Product Certificate | n/a | Regulatory note, not costed. Verify with CPSC. |
| A16 | Buyer sales tax 7%; per-unit share of buyer-paid shipping $3 | Used only for the processing-fee base | Assumption |

**Formulas used (P = hammer price):**
- Landed cost (China import) = (FOB × 1.375 + kg × freight rate) ÷ 0.95. FOB = midpoint of the listed range [A2–A5].
- Whatnot fees = 0.05·P + 0.029·(1.07·P + $3) + $0.30 = **0.081·P + $0.39** [A1, A1b, A16].
- Net per unit = P − Whatnot fees − Landed cost − $0.50.
- Break-even P = (Landed cost + $0.50 + $0.39) ÷ 0.919.
- eBay fees = 0.136·P + $0.40 (or $0.30 if P ≤ $10) [S4]. This excludes the final value fee on shipping.

**Worked check (row 1):**
- Landed: 0.189 × 1.20 × $49.95 ÷ 0.75 = $15.10.
- Fees: 0.05 × 25 + 0.029 × (26.75 + 3) + 0.30 = 1.25 + 0.863 + 0.30 = $2.41.
- Net: 25 − 2.41 − 15.10 − 0.50 = **$6.98**.

**Worked check (row 15):**
- Landed: (6.25 × 1.375 + 0.15 × 7) ÷ 0.95 = (8.594 + 1.05) ÷ 0.95 = $10.15.
- Fees: 0.05 × 10 + 0.029 × (10.70 + 3) + 0.30 = 0.50 + 0.397 + 0.30 = $1.20.
- Net: 10 − 1.20 − 10.15 − 0.50 = **−$1.85**.

---

## 4. Bulk sources, unit cost, MOQ, lead time (part 2 of the brief)

### 4a. Domestic secondary market (best margins found)
| Channel | Unit cost evidence | MOQ / lot size | Lead time | Notes |
|---|---|---|---|---|
| Walmart Liquidation (B-Stock) consumer-electronics lots | Lot #134309: 461 units, ext. retail $15,446, final bid $2,913 → **$6.32/unit, ~18.9% of retail** (2025 lot) [S79] | Pallets (hundreds of units) | Ground LTL (days) | Buyer fee + freight not included [A8]. Mixed TVs/appliances dilute the unit value. |
| Amazon return pallets (various liquidators) | Typically $300–$400 per pallet; electronics pallets cost more [S80] | Pallet | Days | Condition varies widely [S80]. Pallet suppliers are covered in the separate report. |
| eBay bulk game lots | 80 Xbox One games $119.99 (~$1.50/game) [S76] | 80–100 games | Days | Untested lots. Some discs need resurfacing. |
| eBay as-is controller lots | 2025 sales of roughly C$20–30/controller for as-is/for-parts DualSense lots [S78] | 4–5 per lot | Days | Parts/repair skill needed. |
| AliExpress **US-warehouse** listings | R36S ~$23–$27 delivered [S69]; RG35XX Plus $35.61 delivered (Mar 2026) [S73] | 1 unit | Ships from the US; one deal noted "no tariff charges" [S73] | Promo-code-dependent pricing. Cheaper than importing R36S yourself (Made-in-China $21.99–23.99 FOB [S82] → ~$35.85 landed with A2/A3/A5). |

**US wholesalers named in the brief:** DollarDays, Wholesale Central, 888 Lots and BULQ were searched. **No per-unit electronics pricing could be retrieved for them** (search results returned no listings, and site fetches were blocked). They are **unverified** and should be priced manually before use. The nearest US bulk comps found were wired earbuds at ~$0.49–$0.57 each in 100–300 packs (Walmart 300-pack $170.99) [S81]. Those suit kids/classroom giveaways, not auction lots.

### 4b. Overseas factories (Made-in-China.com search pages. Alibaba and DHgate blocked automated access. 1688 and AliExpress bulk tiers were not checked)
Representative FOB prices (USD, before duty and freight) are cited per row in §1 [S82–S94]. Search-page medians observed across ~30 listings each:

| Search | Listings | Median low price | Median MOQ |
|---|---|---|---|
| TWS earbuds | 31 | $7.49 | 30 |
| Power bank | 31 | $9.50 | 50 |
| Smart watch | 30 | $17.89 | 100 |
| Galaxy projector | 31 | $8.00 | 10 |
| LED strip | 30 | $3.00 | 60 |
| Kids camera | 30 | $11.96 | 100 |
| USB-C cable | 31 | $0.65 | 100 |
| Phone case | 31 | $2.01 | 100 |

These are **search-page medians** that mix very different products, so use the specific listing in §1 for costing.

**Alibaba "welcome deal" prices** are one-off new-buyer promotions, not wholesale tiers. Examples: R36S $14.70 ($17.08 with tax, Dec 2025) [S71]; HY300 projector $18.99 delivered (Apr 2026) [S72]. If an HY300 could repeatably be landed for about $20, net per unit would be about +$20 at a $45 hammer. That is the single biggest upside in this list, but no repeatable source was verified.

**Lead time:** China→US e-commerce shipping was quoted at 15–20 days in 2024 R36S deals [S70]. Air-freight lead time for factory orders is an assumption: ~7–15 days door-to-door plus production.

**Landed-cost sensitivity for generic imports** (model output: low end of the FOB range; "sea" = assumed $1.50/kg consolidated):

| Item (hammer) | Low FOB + air | Low FOB + sea | Low FOB + sea + only 25% duty |
|---|---|---|---|
| TWS earbuds ($10) | net $1.41 | $2.28 | $2.80 |
| Power bank ($12) | −$2.86 | −$0.18 | $0.72 |
| HY300 projector ($45) | −$0.07 | $6.87 | $9.76 |
| Galaxy projector ($15) | $1.98 | $4.87 | $5.53 |
| LED strip ($8) | −$1.03 | $0.71 | $1.19 |
| Kids camera ($12) | $0.00 | $1.16 | $1.94 |

**Takeaway:** generic imports only work at volume-tier prices on sea freight, which needs larger orders and longer lead times than a $500–$2,000 starter budget allows.

---

## 5. Brand / IP / safety risk (read before buying)

- **Whatnot bans counterfeits outright,** including items using a brand's name or logo that the brand didn't make, "even if the seller says it's fake." Unbranded lookalikes are allowed only if they are not marketed as "inspired by" or as a replica [S10][S11]. Counterfeit refunds are charged back to the seller, and accounts can be suspended [S10].
- **Supplier listings that are counterfeit or IP-infringing by their own titles** (all observed on Made-in-China.com):
  - "2025 Premium AAA+++ Tws Anc PRO 2 3 Air Max 4 - 1:1" [S95]
  - "1:1 Replica Anc PRO 3 Tws Earbuds" [S96]
  - "Mobile Phone Charger Pd 20W **Original Charger for iPhone**" at $1.69–2.55 [S97]
  - "(Top1-level version) Airbuds … Air Max Buds PRO 2 3 4" [S98]
  - "Hot Sale **Airepods** Custom Logo" [S99]
- **R36S / retro handhelds:** listings advertise "15,000–20,000+ games" [S20][S82]. Those are preloaded ROMs of copyrighted games. Sell the hardware with a blank or open-source-OS-only card, describe it that way, or skip it. The R36S is ranked above with that assumption.
- **Jailbroken / "fully loaded" Fire TV Sticks** are piracy devices [S51]. Never list them. Stock units are fine [S52].
- **Power banks and drones** contain lithium cells. Expect dangerous-goods freight [A4], and buy only units with recognised safety certification. The fire/recall exposure is yours as the seller.
- **Kids' cameras, toy drones and karaoke toys** are children's products, so CPSIA rules apply [A15].
- **Mystery boxes / "pulls":** Whatnot's Surprise Sets policy (updated June 2026) requires the possible contents to be disclosed. Sealed surprise products used in breaks, sets or giveaways must be on Whatnot's Identified Product List [S12][S13].

---

## 6. Recommendation: starter baskets (part 4 of the brief)

Totals include $0.50/unit packaging [A6]. "Expected net" assumes every sellable unit sells at the §1 estimated price. **It is an estimate, not a forecast.**

### $500 basket: "domestic-first, low MOQ"
| Line | Cash | Units sold | Net/unit (est.) | Net (est.) |
|---|---|---|---|---|
| 1 × 80-game lot ($119.99 + $14.99 ship) [S76][A12], 72 sellable | $134.98 + $36.00 packaging | 72 | $2.75 | $198.15 |
| 30 × RGB wired mouse (landed $5.38) [S93] | $161.45 + $15.00 | 30 | $2.92 | $87.63 |
| 50 × LDNIO USB-C cable, MOQ 10 (FOB $0.75–0.78 → landed $1.48) [S94b], **bid-drivers** sold at $3 [A9] | $73.78 + $25.00 | 50 | $0.39 | $19.71 |
| **Total** | **$446.21** (≈$54 left for supplies/test gear) | **152** | | **≈ $305.50** |

### $2,000 basket: "add branded volume + a returns lot for variety"
| Line | Cash | Units sold | Net/unit (est.) | Net (est.) |
|---|---|---|---|---|
| 3 × 80-game lots, 216 sellable | $404.94 + $108.00 | 216 | $2.75 | $594.45 |
| 20 × as-is DualSense @ ~$22 [A10], 14 usable [A11] | $440.00 + $7.00 | 14 | $4.44 | $62.21 |
| Mixed electronics returns lot, ~$400 (~53 units at $7.58 all-in, 39 working) [S79][A7][A8] | $400.00 + $19.50 | 39 | $2.79 | $108.64 |
| 60 × RGB wired mouse | $322.89 + $30.00 | 60 | $2.92 | $175.27 |
| 80 × LDNIO USB-C cable (bid-drivers) | $118.05 + $40.00 | 80 | $0.39 | $31.54 |
| **Total** | **$1,890.39** (≈$110 reserve) | **409** | | **≈ $972.10** |

Why these baskets, and what to add later:
- **Bid-drivers** (cables, $3–$6 games) keep a $1-start stream moving. **Margin items** (controllers, branded audio from the returns lot, mice) earn the money.
- I left out the R36S, AirTags and the Y68 watch. The R36S has thin margin plus ROM/IP exposure. AirTags make about $2/unit and go negative at 8% commission. The Y68 watch needs MOQ 800.
- Add AirTags only when you find them at ≤$63/4-pack [S66]. Add Y68 watches once you can absorb the MOQ.

### Tips for running $1-start auctions profitably
1. **Know each item's break-even before it goes live** (the §1 column). Run $1 starts only on items whose break-even is under ~$4 (games $3.01, cables $2.07). Start everything else at or near its break-even, e.g., DualSense ~$35, JBL ~$17.
2. **Test on camera.** Whatnot-focused guidance ranks returns as the main electronics risk and says to show items working and state any missing accessories [S3]. That matters most for returns-lot and used items.
3. **Alternate bid-drivers and margin items.** Use a cheap $1 item to build the room, then run a controller or speaker while viewers are engaged. Shows that pair "$1 starts" with Apple or gaming headliners are the norm in the category [S53][S54][S55].
4. **Bundle low-ticket items** (mouse + cable, two games) so the $0.30 fixed processing fee and the packaging are spread over a higher ticket.
5. **Put sealed, genuine, high-ticket items on eBay as well.** eBay fees are higher [S4], but its buyer pool is wider for controllers and speakers.
6. **Never** list replica/"1:1" goods, ROM-loaded handhelds or jailbroken streaming sticks (§5).

---

## 7. What would change this ranking
- **The electronics commission is the 8% case rather than 5%** [S3]: every net drops by 3% of the hammer price (see the 8% column). AirTags go to ~$0.
- **The 12.5% forced-labor layer is not in force, or an HTS exclusion applies** [S8]: generic import rows improve by ~9% of FOB.
- **Repeatable DDP/US-warehouse pricing near the Alibaba welcome deals** [S71][S72]: projectors and handhelds jump to the top.
- **Real hammer data:** manually pull eBay *sold auction* comps and a few Whatnot show recaps per item to replace the [A9] estimates.

## 8. Method and limitations
- Done with web search plus page fetches on 2026-10-09.
- **These sources returned HTTP 403 / bot checks and could not be read directly:** eBay sold/completed search, Reddit (r/whatnotapp, r/Flipping, r/sidehustle), Whatnot help/live pages, Alibaba, DHgate and Walmart lot pages. Whatnot listing pages and Walmart lot data were read through search-index snippets. Made-in-China.com search pages were read through a text-extraction reader.
- **No Reddit or YouTube seller breakdowns could be cited.** No item has a measured auction sell-through rate. "Demand" is a qualitative rating from listing prices, seller sale counts and show titles.
- Prices on Whatnot listing pages are asks/BIN, not hammer prices. Listing ages vary up to ~2 years [S49][S32].

---

## Sources (all observed 2026-10-09; source's own date noted where known)

**Fees, platform, policy**
- [S1] Crosslist, "Whatnot Fees for Sellers" (updated 2026-09-30): https://crosslist.com/blog/whatnot-fees-for-sellers
- [S2] Feescal, "Whatnot Seller Fees 2026" (Mar 2026): https://feescal.com/blog/whatnot-seller-fees-2026
- [S3] Underpriced, "Best Items to Sell on Whatnot in 2026: Category Scorecard" (updated 2026-10-01): https://www.underpriced.app/blog/best-items-to-sell-on-whatnot-2026
- [S4] eBay Help, "Selling fees": https://www.ebay.com/help/selling/fees-credits-invoices/selling-fees?id=4822
- [S5] Whatnot, "2026 State of Live Selling Report" (2026-01-28): https://blog.teamwhatnot.com/unitedstates/2026livesellingreport
- [S6] Online Marketing Classroom, fastest-growing Whatnot categories (2026-07-31): https://onlinemarketingclassroom.com/blog/2026/07/31/fastest-growing-whatnot-categories/
- [S10] Whatnot, Counterfeit Policy and Restricted Branded Items Policy: https://help.whatnot.com/hc/en-us/articles/360061604031-Counterfeit-Policy-and-Restricted-Branded-Items-Policy
- [S11] Whatnot, Prohibited or Restricted Items: https://help.whatnot.com/hc/en-us/articles/360061224972-Prohibited-or-Restricted-Items-on-Whatnot
- [S12] Whatnot, Surprise Sets Policy (updated June 2026): https://help.whatnot.com/hc/en-us/articles/34107510260237-Surprise-Sets-Policy
- [S13] Whatnot, Professionally Sealed Surprise Products: https://help.whatnot.com/hc/en-us/articles/39618879679757-Professionally-Sealed-Surprise-Products

**Tariffs, freight**
- [S7] TariffsTool, "China Electronics Tariff 2026" (updated 2026-08-17 / 2026-09-14): https://www.tariffstool.com/guides/tariff-on-electronics-from-china-2026
- [S8] Customs Broker USA, Section 301 2026 rate guide (2026-07-13): https://customsbrokerusa.com/section-301-tariffs-china-2026-rate-guide/
- [S9] Bloomberg Supply Lines (2026-03-05), Freightos Air Index China–US $6.90/kg: https://www.bloomberg.com/news/newsletters/2026-03-05/air-cargo-disruptions-and-the-iran-war

**Whatnot listings and shows**
- [S20] R36S $24 (thedealstation): https://whatnot.com/listing/TGlzdGluZ05vZGU6MTk4MDA1NDg5Ng==
- [S21] R36S $59 sealed: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6OTQwNTg4OTk2
- [S22] R36S white $50: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6NTk4MDk1ODYw
- [S23] Bluetooth earbuds $5: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6OTA5NzQ4MzM2
- [S24] Sentry TWS earbuds $14: https://whatnot.com/listing/TGlzdGluZ05vZGU6MjE5OTU0NjU0MQ==
- [S25] AirPods 4 open-box $50: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6ODU5NTkwNTUw
- [S26] Mini portable projector $67: https://www.whatnot.com/en-GB/listing/TGlzdGluZ05vZGU6NDk4ODA5NjM1
- [S27] AURA galaxy projector $29.99: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6Mzc1OTM5NDY1
- [S28] Gizmos star projector $4: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6NTkzNTYwMjQ3
- [S29] LitEnergy star projector clock $38: https://whatnot.com/listing/TGlzdGluZ05vZGU6MTA3ODY3Njg3MA==
- [S30] Coucur smartwatch $15: https://whatnot.com/listing/TGlzdGluZ05vZGU6MTAyOTM1OTc2Mw==
- [S31] Smartwatch $19.99: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6NDY1NTAwNDYx
- [S32] Vivitar smartwatch $21: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MzQ0NzgxNzgx
- [S33] Heyday 10k mAh power bank $5: https://whatnot.com/listing/TGlzdGluZ05vZGU6MTIxNTk0MDA0MQ==
- [S34] HOSGUBO power bank $9: https://whatnot.com/listing/TGlzdGluZ05vZGU6MTc1Mjg4OTc4Nw==
- [S35] Pongo power bank $20: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6NjIwMTA2OTg0
- [S36] Children's digital camera $12: https://whatnot.com/listing/TGlzdGluZ05vZGU6MTUwNDM4MjIzNw==
- [S37] Bluetooth karaoke mic $8: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MTIyMzYyNDc0Ng==
- [S38] Fine Life 10" ring light $10: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MTg2NTkzMDk5
- [S39] LED strip 16 ft $5: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MTg3MDkxMjgwMQ==
- [S40] RGB LED strip 30 m $17: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MTk3MDE2Nzg0MQ==
- [S41] RGB wired gaming mouse $10: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6NTI3MjUwMjky
- [S42] RGB keyboard + mouse combo $17: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MTc0OTIyMDQyMA==
- [S43] Mini drone for kids $29.99: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MzE5NDczMDQ1
- [S44] Attop X-Pack 2 mini drone $5: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MzU3MTA4OTgy
- [S45] L23 drone $35: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MTAzMTA5MzI3
- [S46] DualSense Cobalt Blue, tested, $50: https://whatnot.com/listing/TGlzdGluZ05vZGU6MTk3NjA1NDA0OQ==
- [S47] PS5 controller, tested, $28: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6OTg5ODk5MjI5
- [S48] DualSense Sterling Silver open-box $52: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MjU1MjgxMTIw
- [S49] AirTag 4-pack sealed $70: https://whatnot.com/listing/TGlzdGluZ05vZGU6MTIyNzExMzI3Nw==
- [S50] AirTag 4-pack $75: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6OTYyODA3MDQ0
- [S51] "Jailbroken Fire TV Stick 4K" (example of what to avoid): https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MzUyNzcyNDk1
- [S52] Fire TV Stick 1st gen open-box $20: https://www.whatnot.com/listing/TGlzdGluZ05vZGU6MzM5MDEzMTAw
- [S53] iceflextech show, "Everything Starts at $1: Earbuds, Power Banks, Cables, Smartwatch Gear": https://www.whatnot.com/live/e36ba93f-4fcd-42d5-b134-754bd6a83f5a
- [S54] voltage_electronics show ($1 starts, power banks, headphones): https://www.whatnot.com/live/112f7809-592f-48b2-9439-5d27528c40ca
- [S55] randomelectronix show ($1 starts, pallet pulls): https://www.whatnot.com/live/c331293b-31f6-496f-86ec-69937009c1a5

**Price trackers, retail, deals**
- [S60] PriceCharting, DualSense: https://www.pricecharting.com/game/playstation-5/dualsense-controller
- [S61] PriceCharting, Joy-Con Neon: https://www.pricecharting.com/game/nintendo-switch/joy-con-neon-red-blue
- [S62] PriceCharting, Xbox Series controller (Carbon Black): https://www.pricecharting.com/game/xbox-series-x/xbox-wireless-controller-carbon-black
- [S63] PriceCharting, PS4 console list: https://www.pricecharting.com/console/playstation-4
- [S64] PriceCharting, Switch Lite Gray: https://www.pricecharting.com/game/nintendo-switch/nintendo-switch-lite-gray
- [S65] Walmart, JBL Go 4 ($39.95, was $49.95): https://www.walmart.com/ip/5632072909
- [S66] Slickdeals, AirTag 4-pack $63 ($15.75 each) (early 2026): https://slickdeals.net/f/19315824-4-count-apple-airtag-1st-generation-63-15-75-each-free-shipping
- [S66b] Slickdeals, AirTag 4-pack $57 at Walmart: https://slickdeals.net/f/19385859-57-4-pk-apple-airtag-bluetooth-tracking-devices-1st-gen-free-s-h-at-walmart-com
- [S67] Slickdeals, Amazon used-like-new AirPods 4 $64.80: https://slickdeals.net/f/18442558-prime-used-like-new-apple-airpods-4-wireless-earbud-headphones-w-charging-case-64-80-more-free-shipping
- [S69] Slickdeals, BOYHOM R36S ~$23 US warehouse (AliExpress): https://slickdeals.net/f/18768313-3-5-boyhom-r36s-retro-handheld-game-console-linux-system-256g-128g-23-xx-free-s-h
- [S70] Slickdeals, R36S from $26.80, 15–20 day shipping (Jun 2024): https://slickdeals.net/f/17563059-r36s-retro-game-emulation-handheld-various-colors-from-26-80-free-15-20-day-shipping-aliexpress
- [S71] Slickdeals, R36S $14.70 Alibaba welcome deal (Dec 2025): https://slickdeals.net/f/18932332-r36s-linux-based-portable-retro-game-handheld-14-70-17-08-total-with-tax-alibaba-welcome-deal
- [S72] Slickdeals, HY300 projector $18.99 on Alibaba (2026-04-01): https://slickdeals.net/f/19372275-hy300-projector-720p-streaming-media-player-android-11-support-1080p-4k-projecteur-hy320-game-video-player-home-theater-tv-box-fs-alibaba-18-99
- [S73] Slickdeals, Anbernic RG35XX Plus $35.61 US shipping (2026-03-05): https://slickdeals.net/f/19273488-anbernic-rg35xx-plus-retro-gaming-handheld-35-61-free-u-s-shipping-aliexpres
- [S74] eBay listing, R36S $32.99 ask, 35 sold (search snippet): https://www.ebay.de/itm/136437826763
- [S75] Walmart galaxy/planetarium projectors $9.88–$49.99: https://www.walmart.com/c/kp/planetarium-light
- [S76] eBay, lot of 80 Xbox One games $119.99: https://www.ebay.de/itm/146779034175
- [S78] eBay as-is DualSense lots (2025 sales, e.g., "Restposten 5x Sony DualSense"): https://www.ebay.de/itm/277554127250
- [S79] Walmart Liquidation (B-Stock) lot #134309, "6 Pallet Spaces of Supplies, TVs & Consumer Electronics", 461 units, ext. retail $15,446, final bid $2,913 (2025): https://liquidations.walmart.com/auction/auction/view/id/134309
- [S80] AOL, "What Are Amazon Return Pallets…": https://www.aol.com/amazon-return-pallets-exactly-plus-100600785.html
- [S81] Walmart, 300-pack wired earbuds $170.99: https://www.walmart.com/ip/Bulk-Disposable-Earbud-Headphones-in-Ear-Earphones-with-3-5mm-Headphone-Plug-Wholesale-Lot-300-Pack-Black/160798321

**Made-in-China.com supplier listings (FOB, observed 2026-10-09)**
- [S82] Esaker R36S $21.99–23.99, MOQ 10: https://esaker.en.made-in-china.com/product/rZoAsNcHyvtd/China-Original-R36s-Handheld-Game-Console-Genuine-Retro-Gaming-Device-Factory-Direct-From-China-OEM-ODM-Manufacturer-for-USA-and-Europe-Market.html
- [S83] 10" LED ring light with stand $5.75, MOQ 500: https://chinapack-nb.en.made-in-china.com/product/htEYAnwoIHWa/China-10-Inch-LED-Ring-Light-with-Stand-Set.html
- [S84] HY300 projector $21.90–26.90, MOQ 20: https://d5512300b957a3f6.en.made-in-china.com/product/KQqRkczDsiYJ/China-Hy300-Factory-Price-Smart-Projector-Android-11-4K-Decoding-720p-Resolution-Projector-Screen-Android-Mini-Projector.html
- [S85] Xy-16 TWS earbuds $4.00–8.50, MOQ 30: https://cnrunton.en.made-in-china.com/product/rxmUeVaKFYRp/China-Xy-16-Most-Popular-Tws-Headphones-Sports-Headset-Wireless-Earphones-Earbuds.html
- [S86] 10,000 mAh 20 W power bank $6.80–7.80, MOQ 20: https://gzronc.en.made-in-china.com/product/xgwRehCMfaWy/China-Fast-Charging-High-Output-20W-22-5W-External-Battery-Mobile-Charger-10000-mAh-Power-Bank-with-Cables.html
- [S87] 1.52" IPS smartwatch $7.66–7.82, MOQ 100: https://gdsimba.en.made-in-china.com/product/odlakUcVXfAy/China-Wholesale-New-1-52inch-IPS-Smart-Watches-Waterproof-Sports-Smartwatch.html
- [S88] Y68 smartwatch $2.71–3.21, MOQ 800: https://newlove521.en.made-in-china.com/product/GPrpxODEImhy/China-Y68-Smart-Watch-Screen-Sport-Hot-Selling-Intelligent-Smart-Watch-Y68-Health-Fitness-Tracker-Wristband-D20-Smartwatch.html
- [S89] Astronaut galaxy star projector $5.00–6.35, MOQ 50: https://tinanis.en.made-in-china.com/product/KOgtUmYvCXAw/China-Galaxy-Star-Projector-Starry-Sky-Night-Light-Astronaut-Lamp-Home-Room-Decor-Decoration-Bedroom-Decorative-Luminaires-Gift.html
- [S90] Kids digital camera $5.99, MOQ 100: https://glorytechnology.en.made-in-china.com/product/QFDtpenrRbTa/China-2-0-Inch-HD-Display-Fun-Cartoon-Shell-Digital-Kids-Camera.html
- [S91] USB 5 m sound-activated LED strip $3.65–4.05, MOQ 100: https://world-dawn.en.made-in-china.com/product/FEiUpYgPOWkH/China-DC5V-USB-Flexible-5m-Long-with-Sound-Activated-Function-LED-Strip-Light.html
- [S91b] Bluetooth karaoke mic $6.11–8.56, MOQ 50: https://oudiobop16889.en.made-in-china.com/product/nzgpQUmZqLVO/China-2-4G-Wireless-Bluetooth-Karaoke-Microphone-Dynamic-Rechargeable-Microphone-for-Singing.html
- [S92] Mini RC drone for beginners $14, MOQ 48: https://kaizhengtoy.en.made-in-china.com/product/dRFpurQobVkg/China-Easy-to-Use-Mini-RC-Drone-for-Beginners-with-Stability.html
- [S93] K1013 RGB wired gaming mouse $2.57–2.83: https://sztvcmall.en.made-in-china.com/product/eFjfNsCvtyTO/China-K1013-6-Key-USB-Wired-Gaming-Mouse-3200dpi-RGB-LED-CE-FCC-RoHS.html
- [S94] Type-C charging cable $0.30–0.60, MOQ 1,000: https://tat-shing.en.made-in-china.com/product/SZyTOodWSapR/China-Android-Phone-and-USB-Device-Type-C-Charging-Cable-Tatshing.html
- [S94b] LDNIO LC901c USB-C to C cable $0.75–0.78, MOQ 10: https://gdldnio.en.made-in-china.com/product/otCUNvJukZks/China-Ldnio-LC901c-Top-Quality-65W-Pd-Quick-Charge-QC3-0-USB-C-to-Type-C-Cable-Super-Fast-Charging-Cable-for-iPhone-18-17-Series.html
- [S95] *(avoid, counterfeit)* "AAA+++ … 1:1" earbuds: https://yueting3c.en.made-in-china.com/product/bfwRFMGobUYp/China-2025-Premium-AAA-Tws-Anc-PRO-2-3-Air-Max-4-1-1-Us-EU-UK-Stock-Bluetooth-Earbuds.html
- [S96] *(avoid, counterfeit)* "1:1 Replica Anc PRO 3": https://huanxitech.en.made-in-china.com/product/MfwrcqhAbRYS/China-1-1-Replica-Anc-PRO-3-Tws-Earbuds-Active-Noise-Cancelling-HiFi-Sound.html
- [S97] *(avoid, counterfeit)* "Original Charger for iPhone" $1.69–2.55: https://apf888.en.made-in-china.com/product/UmPrxKfysShz/China-Mobile-Phone-Charger-Pd-20W-Original-Charger-for-iPhone-Wholesale-Mobile-Phone-Accessories.html
- [S97b] Phone case price range example (card-holder TPU case $0.42–0.45, MOQ 100): https://szdazec.en.made-in-china.com/product/PQCReJAvJUcq/China-Card-Holder-Cell-Phone-Case-for-iPhone-14-13-12-11-PRO-Max-7-8-Plus-TPU-Wallet-Soft-Back-Cover-Shockproof.html
- [S98] *(avoid, counterfeit)* "(Top1-level version) Airbuds": https://szgz01.en.made-in-china.com/product/dLlpaRYEFfhJ/China-Top1-level-version-Airbuds-Noise-Cancelling-in-Ear-Pods-Air-Max-Buds-PRO-2-3-4-Stereo-Headphone-Earphone-Wireless-Bluetooth-Earbuds-Gaming-Headset.html
- [S99] *(avoid, trademark lookalike)* "Airepods Custom Logo": https://gdsimba.en.made-in-china.com/product/aFYfLkrxoTGt/China-Hot-Sale-Airepods-Custom-Logo-Stereo-Tws-True-Earbuds-Headphone.html
