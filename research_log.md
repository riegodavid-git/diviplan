# Research Log

Dated SCOUT findings, appended each cycle. Each entry: date, topic, finding, source, materiality (Low/Med/High).

---

## 2026-06-09 — Strategy Proposal research (SCOUT)

### Platforms (how to reach the market from PH)
- **DragonFi** — Local PSE broker. Commission **0.25% + 12% VAT** on buys, **no minimum commission** (dropped the ₱20 floor in 2024), **₱1,000 to start (Lite = ₱0)**, no subscription/hidden fees. Offers PSE stocks, locally-distributed mutual funds (incl. funds with US exposure), **PERA accounts** (admin fee waived for 2025; standard 0.45%/yr or ₱300, whichever lower), and curated model portfolios "Dividend Harvest" & "Strategic Growth." Dividend-investing focus. **Med** — strong local + tax-advantaged (PERA) option; does NOT give direct US-listed ETF access. [Source: dragonfi.ph/pricing, TradingBrokers review, Philstar]
- **COL Financial** — Local PSE broker. **0.25%** online commission, **₱5,000** min initial (First class). Deep research/education. **Low/Med** — established but higher entry than DragonFi. [Source: TradingBrokers, smartpinoyinvestor]
- **BPI Trade** — Local PSE broker. **0.25%**, **₱20 min/trade**, **₱120/yr custodial** (prorated). Bank-integrated, beginner-friendly. **Low**. [Source: TradingBrokers]
- **GoTrade** — Access to **US-listed** stocks/ETFs, **fractional from $1**, low/zero stated commission (stocks 0.15–0.3% per fee schedule), **₱45 per deposit**, FX spread on PHP→USD (watch this). **Med** — cheapest, simplest path to US ETFs while balances are small; US-domiciled holdings carry US tax drag (see Tax). [Source: heygotrade.com fee PDF, tipidnation, investingengineer]
- **Interactive Brokers (IBKR)** — Global access, **no account minimum**, very low tiered fees (US stocks from $0.0035/sh, $0.35 min). Can buy **Irish-domiciled UCITS ETFs** (CSPX, VWRA) — the tax-efficient route. **High** — best long-term/tax-efficient platform; steeper learning curve for a beginner. [Source: interactivebrokers.com pricing, brokerchooser]

### Funds / instruments
- **FMETF** (First Metro Philippine Equity ETF, PSE) — tracks PSEi, **expense ratio 0.50%**, **accumulating (pays no dividends)**, ~-6.6% trailing 1-yr total return at time of search. **Med** — simplest single-ticker local-market exposure. [Source: stockanalysis.com, firstmetroetf.com.ph, dividends.ph]
- **VOO** (US-domiciled S&P 500 ETF) — ultra-low cost (~0.03%), but US-domiciled → 30% US dividend withholding for PH residents + US estate-tax situs exposure. Buy via GoTrade/IBKR. **Med**.
- **CSPX / VWRA** (Irish-domiciled UCITS, S&P 500 / FTSE All-World, **accumulating**) — Irish domicile → **15% withholding at fund level** (vs 30% for US-domiciled), **no US estate tax**, accumulating = no investor-level dividend to declare. Buy via IBKR. **High** — most tax-efficient core for a long horizon. [Source: Bogleheads NRA wiki, Endowus, Syfe, Davy]

### Tax mechanics (PH resident individual) — LEDGER inputs
- **Local PH dividends:** 10% final withholding tax (CMEPA, RA 12214). [Source: Grant Thornton, Cruz Marcelo]
- **Selling PSE-listed shares:** Stock transaction tax **reduced 0.6% → 0.1%**, effective **July 1, 2025** (CMEPA). [Source: PwC PH, BusinessWorld, Inquirer, FirstMetroSec]
- **US-domiciled ETF dividends (e.g. VOO):** US withholds **30%** for PH residents (PH–US treaty gives no better portfolio-dividend relief in practice). **High** for income-focused holdings.
- **Irish-domiciled ETF (CSPX/VWRA):** **15%** US withholding at fund level, no second PH layer if accumulating; **not** US-situs → avoids US estate tax. **High** advantage as balances grow.
- **US estate tax:** US-situs assets above ~**$60,000** exposed to up to **40%** for nonresident aliens; Irish-domiciled funds sidestep this. **Med now, High later.** [Source: Bogleheads, DeadSimpleSaving]
- **PERA** (Personal Equity & Retirement Account, available via DragonFi): tax-advantaged (5% tax credit, tax-exempt income) **but locked until age 55** — conflicts with the age-35 cushion goal; note for later. **Low for now.**

---

## 2026-06-09 — DragonFi baskets & feeder funds, PSEi vs US (SCOUT, follow-up)

User flagged FMETF/PSEi as going sideways. Confirmed and researched DragonFi's offerings.

- **PSEi reality check:** PSEi is **down ~20% over the past 10 years — the worst-performing major benchmark tracked by Bloomberg.** Regional peers rose (Asia-Pacific +72%, Indonesia +82%). FMETF just tracks this. **High** — user's instinct to avoid it is correct. [Source: SCMP, Bloomberg]
- **S&P 500 for contrast:** ~**14.8% annualized** over the 10 years to Dec 2025 (USD); higher in PHP terms due to peso depreciation. [Source: Fidelity, dqydj]
- **DragonFi is a broker, not a fund issuer — it has no ETFs of its own.** What it actually offers: PSE stocks/REITs; PHP-denominated *feeder funds*; curated research model portfolios; and PERA. [Source: dragonfi.ph]
- **PHP feeder funds on DragonFi (the interesting part):**
  - **BPI US Equity Index Feeder Fund (Peso)** — tracks **S&P 500 Net Total Return** by holding **SPDR SPY**; inception **Nov 11, 2019**; aggressive equity. Fee figures conflict across sources: KIIDS cites ~**0.55% TER**, uitf.com.ph lists a **1.50% trust fee** — likely different share classes; **VERIFY the exact class fee before buying.** **High** — clean PHP route to the S&P 500. [Source: dragonfi.ph/market/funds/BPIEF5, uitf.com.ph fund_id 377, BPI KIIDS Jan 2026]
  - **Manulife American Growth Equity Feeder Fund** — US growth-equity feeder, PHP. **Med**. [Source: dragonfi.ph/market/funds/AG4]
- **DragonFi model portfolios (research-team "real-money" baskets you replicate by buying the stocks):**
  - **Dividend Growth Portfolio: +49.31% total return since inception Nov 29, 2023; +19.29% YTD**, vs PSEi +1.22% (2024) and -5.84% YTD. **Med** — strong, BUT ~2.5-yr track record only, active stock selection, self-reported by the broker; do not treat as the proven core. [Source: Inquirer, dragonfi.ph]
  - Also "Dividend Harvest" and "Strategic Growth" tracked in the in-app Investing Club (detailed holdings/returns gated behind the app).
- **Tax note on PHP feeder funds (UITFs):** individual investor's redemption gains are generally **not separately income-taxed** (the trust is tax-exempt), a quiet advantage vs directly holding a US-domiciled ETF (30% dividend withholding + estate-tax situs). The 30% US withholding still applies *inside* SPY and is reflected in the feeder's return/fee drag. **Med** — verify current BIR treatment.

**Takeaway:** Avoiding FMETF is right. Best long-term growth = US/global equity, not PH. Three routes to it, cheapest-to-most-convenient: Irish-domiciled ETF via IBKR (lowest tax/fee, 15% withholding, no estate tax) → US-domiciled ETF via GoTrade (0.03% fee but 30% withholding) → **PHP feeder fund via DragonFi (most convenient, PHP, no FX/IBKR learning curve, but ~0.55–1.5% fee).** Model baskets = idea source, not core.

---

## 2026-06-09 — Philippine REITs (SCOUT, follow-up)

User asked about PH REITs for dividend income; comfortable with risk.

- **Why REITs yield so much:** By law (RA 9856) PH-listed REITs must **distribute ≥90% of distributable income** as dividends → structurally high yields, paid quarterly. **High.** [Source: ALBURO Law, lawphil RA 9856, BIR RR 13-2011]
- **Yields & names (2025–26):** Sector yields ~**6–8%**.
  - **AREIT** (Ayala Land) — first & largest PH REIT, AUM ₱117B, most diversified, prime Greenbelt/CBD assets; yield ~**6.4%**; **TSR +74% since Aug-2020 IPO**. Most stable/blue-chip. **High.**
  - **RCR** (Robinsons Land) — mature retail + office; strong **+27% YTD (mid-2025)**, mid-to-high yield. **Med.**
  - **MREIT** (Megaworld) — BGC offices, steady asset infusions; stable. **Med.**
  - **FILRT** (Filinvest) — higher yield ~6–7% but more risk (lower occupancy/profitability). **Med.**
  [Source: investingengineer.com, stockanalysis.com, Metrobank Wealth Insights, Statista]
- **Tax:** REIT cash dividends to a resident individual = **10% final withholding tax** (REIT withholds it; nothing more to file). OFWs are exempt through ~the law's incentive window. **Med.** [Source: Taxify.ph, ALBURO, PwC PH]
- **Key risk:** REITs are **interest-rate sensitive** — they fell hard in 2022–23 as rates rose, recovering as rates ease. High yield ≠ low risk; treat as a satellite, not the whole portfolio. **High.**
- **Mechanics:** Buy REIT shares directly on **DragonFi** (PSE-listed) → quarterly cash dividends land in the account (−10%) → reinvest. This is the hands-on "dividend journey" the user wants; also **PERA-eligible** (DivY/PSEi/REIT lists) for tax-advantaged long-term holding. [Source: dragonfi.ph PERA+ guide]

**Synthesis for game plans:** Pair a **global/US equity growth engine** (the compounding core — PH equity has lagged badly) with a **PH REIT + dividend satellite** (real, growing PHP income now; motivating + diversifying). Weighting between them is the main lever, set by how much current income vs. max compounding the user wants.

---

## 2026-06-09 — REIT picks for the 10% sleeve (SCOUT + TRANSLATOR)

All 8 PSE-listed REITs are buyable on DragonFi. Profiles:

| REIT | Sponsor | Sector | ~Yield | Read |
|---|---|---|---|---|
| **AREIT** | Ayala Land | Office + premium retail (Greenbelt) | 6.1–6.4% | Largest, most diversified, best track record (+74% TSR since 2020). **Blue-chip anchor.** |
| **CREIT** | Citicore | **Renewable energy / solar** | ~6.3% | Only non-property REIT; paid >100% of distributable income 4 yrs running; growing dividend. **Best diversifier.** |
| **MREIT** | Megaworld | Office (townships) | 6–7% | Solid, tenant stickiness via township model. |
| **RCR** | Robinsons Land | Office/BPO, nationwide | ~5.7% | Largest by asset count, geographic spread. |
| **DDMPR** | DoubleDragon | Office | 8–9% | Highest yield but quality/occupancy concerns. Higher risk. |
| **FILRT** | Filinvest | Office (PEZA/BPO) | 6–7% | Higher yield, occupancy/profitability risk. |
| **VREIT** | Vista (Villar) | Malls + office | ~ | Smaller, less liquid. |
| **PREIT** | — | Power (Visayas) | ~ | Niche, smaller. |
[Source: investingengineer.com, dailypik.com, fitzvillafuerte.com, bilyonaryo (CREIT 2025), Simply Wall St, stockanalysis.com]

- **Current headwind:** Rising PH bond yields are a near-term drag on REIT prices (higher "risk-free" rate competes with REIT yields). REITs are rate-sensitive — expect price volatility. **Med/High.** [Source: Metrobank Wealth Insights, Apr 2026]
- **Recommendation for a small (10%) sleeve:** Don't over-diversify a tiny allocation (commission/complexity drag). **Start 100% AREIT** (safest, most diversified single name); once the sleeve grows past ~₱20–30k, add **CREIT** (~60/40 AREIT/CREIT) for genuine sector diversification (energy vs. office/retail). Avoid DDMPR/FILRT (yield traps risk), VREIT/PREIT (liquidity). **Med confidence.**

---

## 2026-06-11 — Feeder fund fee CONFIRMED, Signature Portfolios, 40-year trends, platform funding (SCOUT)

### Feeder fund fee — RESOLVED (was "VERIFY" from 2026-06-09)
- **BPI US Equity Index Feeder Fund: 1.5% trust fee per annum, confirmed by user from BPI's own fund page** (bpi.com.ph → US Equity Index Feeder Fund). The 0.55% KIIDS figure was a different share class. On top of the fee, the fund tracks the S&P 500 **Net** Total Return index (≈0.4%/yr embedded 30% US dividend withholding inside SPY) → **total ongoing drag ≈ 1.9%/yr vs the gross index. HIGH materiality** — largest cost leak in the current plan; triggers re-route recommendation for the 88% global sleeve. [Source: bpi.com.ph fund page, user-verified 2026-06-11]

### DragonFi Signature Portfolios (dragonfi.ph/signature-portfolio, read 2026-06-11)
- **What they are:** follow/copy baskets of PSE-listed stocks, bought through the app. 13 live portfolios in two groups — **DragonFi research-team baskets** (Dividend Harvest; Strategic Growth; **D15 Dividend Benchmark** "best dividend payers/growers"; REIT Basket; Power Portfolio; Banking Portfolio; Diversified Category Leaders) and **creator/influencer portfolios** (MoneyWise Engineer ~3.8k buyers — value+dividend; InvestingPH ~2.3k — dividend value; Trina's Snowball Picks — high-yield snowball; Kuya Jon — simple-business income; Stocksilog — growth+dividends; eTrader — active, claims to beat PSEi since 2017). Holdings/returns detail is gated behind app login. **Med.**
- **Reported performance (self-reported/secondary):** Dividend Harvest **+39.36% in 2024, +81.88% since launch** [DragonFi FB]; research team's Dividend Growth Portfolio **+49.31% since Nov 29, 2023 inception** [Inquirer, Mar 2025].
- **Assessment:** all are **PH-only, active, short track records (≤2.5 yrs), broker-self-reported**, in a market that lost ~20% over 10 years. Fine as **idea source / dividend-stock watchlist (esp. D15)**; REIT Basket overlaps our REIT sleeve; **not a substitute for the global core**. Possible small PH-dividend satellite *post-graduation* if income goals grow. **Med.**

### 40-year trends (for HORIZON/TRANSLATOR context)
- **Megatrend consensus** (Vanguard, Morgan Stanley, BNP, PwC, Barclays): (1) AI/technology acceleration + digital economy; (2) energy transition/electrification (AI power demand feeds clean-energy buildout); (3) demographics — aging rich world, young South/SE Asia + Africa; longevity/healthcare demand; (4) geopolitics/multipolarity. **Med** (directional, not investable precision).
- **Economic weight shifts East:** China projected largest economy ~2035; India top-2–3 by ~2050–2075; Indonesia top-5 by 2050 (PwC World in 2050, Goldman, OECD long view). US share of global GDP/market cap likely declines from today's ~60% of world equity. **High for allocation design** — argues for all-world market-cap exposure that self-adjusts, vs a permanent 100% US bet.
- **Philippines specifically:** HSBC projects PH = **16th largest economy by 2050** (PwC: ~20th); working-age population growing to **~2045** (demographic dividend); ~150M people by 2050. Long-run tailwind for PH assets (REIT sleeve, future PH-dividend satellite), though PSE execution has badly lagged the macro story for a decade. **Med.**
- [Sources: pwc.com World in 2050, HSBC via Inquirer, OECD long-view 2060, vanguard.co.uk/megatrends, morganstanley.com megatrends]

### Platform funding mechanics (PH-specific, 2026)
- **GoTrade:** still operating for PH; fractional US ETFs from $1 (VOO 0.03% ER, VTI, VT all available); fund in PHP (₱45/deposit + FX spread ~0.2–0.5%); commission ~0.15–0.3%. Regulated via Labuan (LFSA); US custody SIPC-insured to $500k. Mixed app-store reviews on withdrawal speed/support — platform risk is the tradeoff. **High** (it's the cheap student-phase pipe to US ETFs). [heygotrade.com, App Store PH]
- **IBKR from PH:** bank wire costs **~₱2,000–3,000 per USD wire** (BPI/Metrobank/UnionBank + intermediary fees) — kills small monthly deposits. **Wise→IBKR integration** cuts transfer to ~$1.27 but funding Wise from PHP has its own ~1.5–2% conversion cost at small size. Practical read: **IBKR economics only work with batched, larger transfers (post-graduation salary), exactly as planned.** **High.** [bearyotrades.substack.com, ibkrguides.com Wise transfer, nomoneylah.com IBKR deposit guide 2026]

**Takeaway:** Plan's architecture (global core + REIT satellite, batching, reinvest-everything) survives audit. The single material leak is the **1.5%/yr feeder fee** on the 88% sleeve — re-route global contributions through GoTrade (VT or VOO, drag ~0.4–0.7%/yr) during the student phase, IBKR/VWRA at graduation unchanged. REIT sleeve on DragonFi unchanged. Signature Portfolios = watchlist, not core.

---

## 2026-06-11 — Security audit: institutional playbook, custody mechanics, GoTrade due diligence (SCOUT, 2nd pass)

User asked: optimize for consistency + long-term growth + security ("what if the company goes bankrupt in 20 years?"), and to systematically track what professionals/big funds do.

### Institutional Watch #1 — what the giant long-horizon money does
- **Norway GPFG (world's largest SWF, >$2T):** ~70% equities / 30% bonds, **passively mirrors FTSE Global All Cap — ~9,000 companies in 70 countries** (~1.5% of every listed company on earth). The world's most security-obsessed fund is a boring all-world indexer. **High** — direct template for our global sleeve shape. [Source: nbim.no, Duke Finance profile, Wikipedia GPFN]
- **NBIM's 2026 warning:** CEO Tangen told lawmakers of "concentration risk around a few companies that we have never seen before in the fund's history"; 54% of the whole fund now sits in the US; their stress test says an **AI correction could wipe ~35% of the entire fund**. Finance ministry ordered concentration/geopolitical scenario analysis. **High** — validates all-world over pure S&P 500, and tempers AI-trend chasing. [Source: IPE, Jan-May 2026]
- **Japan GPIF (world's largest pension, ~$1.9T):** locked 25/25/25/25 domestic/foreign stocks/bonds **for five more years from FY2025**; foreign equity ~82% passive. Their entire edge = consistency + rebalancing, not selection. **Med/High** — the "strict monthly buys" decision mirrors this. [Source: gpif.go.jp, top1000funds]
- **Berkshire/Buffett:** record **~$348B cash**, rotated away from concentrated mega-cap positions; still zero gold ("nonproductive"). Buffett's standing estate instruction remains 90% S&P 500 index / 10% T-bills. **Med** — a valuation caution flag, not a sell signal; cash pile = his version of dry powder, our version = weekly contributions. [Source: ainvest, money.ca, hedgefollow 13F]
- **Gold:** ATH ~$5,589/oz Jan 2026, 8 straight monthly gains, central banks buying. We skip it (nonproductive, Buffett's logic; growth phase of life). **Low/Med.**
- **How we use Institutional Watch:** slow signals only — allocation shape, concentration warnings, valuation temperature. Never trade triggers. Added to SCOUT role in CLAUDE.md: brief every cycle + quarterly 13F-season deep-dive.

### Custody mechanics — what can and cannot vaporize in 20 years
- **Fund provider bankruptcy (Vanguard/BPI/BlackRock):** fund assets are **segregated at third-party custodians, not on the provider's balance sheet**; worst case = orderly wind-down at NAV. A market-cap index fund "goes to zero" only if ~9,000 companies do. **High (reassurance).**
- **US broker failure:** SEC Rule 15c3-3 segregation + **SIPC $500k/customer (incl. $250k cash)**; accounts typically bulk-transferred to another broker within days. SIPC covers non-US customers. Does NOT cover market losses. [Source: sipc.org, finra.org, investor.gov]
- **PH broker failure (DragonFi):** shares recorded at **PDTC** (central depository), segregated from broker assets; PH **SIPF compensation is tiny (~₱10k-100k per claimant depending on source)** — real protection is the segregation, not the fund. **Med** — fine for the 12% REIT sleeve. [Source: respicio.ph, pseacademy.com.ph]
- **BPI UITF:** trust assets segregated from the bank's balance sheet under BSP regulation; a BPI failure ≠ loss of fund assets. **Med.**
- **What actually destroys 20-year outcomes:** single-company positions (the REIT sleeve carries this — capped at 12% by design), leverage, fraud/unregulated platforms, panic selling, and compounding fees (the 1.5% feeder = ~₱3M scenario drag). NOT a Vanguard bankruptcy. **High.**

### GoTrade due diligence (user-requested before committing)
- **Structure verified from primary documents:** GoTrade users sign the **Alpaca Customer Agreement directly** — the brokerage account is opened **in the user's own name at Alpaca Securities LLC** (FINRA member; clearing via Velox Clearing LLC and Vision Financial Markets LLC; all three SIPC members). W-8BEN provisions confirm non-US individuals are direct beneficial owners. [Source: heygotrade.com/legal/alpaca-customer-agreement.pdf v18.2021.12, heygotrade.com/legal/gotrade-sipc.pdf — both read 2026-06-11]
- **Implication:** if GoTrade (Labuan-regulated app layer) fails, shares remain in the user's named, segregated account at Alpaca — recovery = paperwork/transfer, not loss. SIPC $500k applies against Alpaca failure with missing assets. Residual risks: operational friction (withdrawal/support complaints in app reviews), FX spread on PHP→USD, crypto accounts NOT SIPC-covered (we don't use them). **High — passed; user approved GoTrade as global-sleeve pipe 2026-06-11.**

### DECISION (user, 2026-06-11) — Plan 2.1 "Trusted Optimizer"
- Global sleeve 88%: **VT (all-world, ~0.06-0.07% ER) monthly on GoTrade**; BPI feeder = fallback parking only. Migrate to **VWRA via IBKR at graduation, hard rule before US-situs nears $60k**.
- REIT sleeve 12%: unchanged (AREIT/CREIT 60/40, DragonFi).
- **100% invested** (no ballast sleeve) — contributions are the dry powder. **Strict monthly buys** (consistency ritual > per-trade cost shaving).
- Files updated: profile.json, college_game_plan.md (v1.1), CLAUDE.md (SCOUT + Status), dashboard.

---
