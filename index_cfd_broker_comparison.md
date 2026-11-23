# Index CFD broker comparison --- Netherlands / EU retail account

- **Prepared:** 21 November 2026
- **Scope:** Intraday index CFDs only
- **Brokers:** IG, OANDA TMS, Pepperstone, CMC Markets, easyMarkets
- **Indices:** S&P 500, Nasdaq 100, DAX 40, FTSE 100, Dow Jones Industrial Average
- **Platform requirement:** Direct TradingView account integration, including order execution

------------------------------------------------------------------------

## 1. Executive summary

All five brokers advertise a TradingView integration that allows account holders to connect and trade from
TradingView. This satisfies the stated platform requirement in principle. The exact instrument availability and
order types should still be checked after connecting the Netherlands/EU account.

The most important findings from the public information reviewed:

- **IG:** Particularly transparent Dutch index-CFD product specifications, including session-dependent spreads,
  standard/mini contract values and 5% retail margin for the five indices.
- **OANDA TMS:** Strongest public transparency for instrument-level contract specifications and historical
  spreads. It offers both cash and futures-based index CFDs; these must not be mixed in a comparison. Its public
  product information also shows no overnight swap on some index products.
- **Pepperstone:** Publishes dated minimum/average spread data for major US index CFDs, charges no commission
  on index CFDs, and publishes its index financing formula. Some European cash-index spread data and
  minimum-size details need confirmation in the EU account.
- **CMC Markets:** Publishes instrument-specific minimum spreads, minimum sizes, holding costs and margin
  information on individual product pages. Its standard CFD account supports direct TradingView integration.
  Contract value per point is unit-based rather than a simple universal lot size.
- **easyMarkets:** Offers fixed spreads on its Web/App/TradingView route and advertises no commission. The
  public index specification is for futures-based index CFDs and gives contract values per point. The publicly
  visible page does not clearly state minimum trade sizes for these index products.

**Important qualification:** A public website's global or international terms are not necessarily the terms
that apply to a Dutch resident. For every broker, confirm the contracting legal entity and the actual
Netherlands/EU retail account schedule before depositing funds.

------------------------------------------------------------------------

## 2. How to read this comparison

### Cash CFDs versus futures-based CFDs

The products below are not always identical:

- A **cash index CFD** tracks a broker's cash-index reference price. Overnight financing and dividend
  adjustments normally apply.
- A **futures-based CFD** references an underlying index futures contract. Financing may be embedded in the
  futures basis/spread rather than charged as a daily cash-index swap. The contract may roll or expire.

This matters because a futures-based CFD can have a different price, spread, contract value and holding-cost
structure from a cash CFD on the same index.

### Spread terminology

- **Minimum spread** is the best/lowest advertised spread, not what a trader will necessarily pay most of the
  time.
- **Average spread** is more useful for cost comparison, but it must refer to the same observation period and
  trading session.
- **Fixed spread** means the broker advertises a spread that stays fixed under the stated product conditions.
  Check the precise account/platform and any exceptions.
- Spreads below are in **index points**, unless explicitly stated otherwise.

### Commission

For index CFDs, most brokers in this comparison incorporate their dealing charge into the spread and advertise
zero separate commission. This does not mean the trade is cost-free.

### Leverage

For an EU retail client, the normal maximum leverage for major stock-index CFDs is **20:1 (5% initial margin)**
under the EU product-intervention framework. This is the relevant comparison for a Netherlands-based retail
account. Higher leverage shown on international or professional-account pages is not the applicable retail
benchmark.

Reference: [ESMA --- CFD product-intervention
measures](https://www.esma.europa.eu/press-news/esma-news/esma-agrees-prohibit-binary-options-and-restrict-cfds-protect-retail-investors).

------------------------------------------------------------------------

# 3. Broker-by-broker review

## A. IG

### TradingView integration

**Supported.** IG's Dutch website explains that an IG account can be connected to TradingView and that trades
can be executed directly from TradingView charts.

Source: - [IG Netherlands ---
TradingView](https://www.ig.com/nl/handelsplatformen/tradingview) - [IG
TradingView
FAQ](https://www.ig.com/en/help-and-support/articles/692529-tradingview-faqs)

### Spreads

IG's Dutch index-CFD product page gives spreads by time of day. The figures below are from the **Dutch cash-index
CFD schedule dated 20 September 2026**.

| Index | Indicative dealing spread by session (index points) |
| --- | --- |
| S&P 500 (US 500) | 0.5 during 15:30--22:00; 1.7 during 23:00--00:00; 1.1 at other listed times |
| Nasdaq 100 (US Tech 100) | 1.1 during 15:30--22:00; 6 during 23:00--00:00; 3 at other listed times |
| DAX 40 (Germany 40) | 5.8 during 01:15--08:00; 1.4 during 08:00--09:00 and 09:00--17:30; 3.4 during 17:30--22:00; 8 during 22:00--01:15 |
| FTSE 100 | 4 during 02:00--08:00; 3 during 08:00--09:00; 1 during 09:00--17:30; 3 during 17:30--22:00; 4 during 22:00--02:00 |
| Dow Jones (Wall Street) | 3.1 during 08:00--15:30; 2.4 during 15:30--22:00; 10.8 during 23:00--00:00; 4 at other listed times |

These are the published dealing spreads, not a guarantee of the spread received on every order. The schedule
uses CET/IG's stated time conventions; check the current order ticket around daylight-saving changes.

Source: - [IG NL --- index CFD product conditions and dealing
spreads](https://www.ig.com/nl/help-en-support/articles/840934-wat-zijn-ig-s-index-cfd-productvoorwaarden) -
[IG NL --- index overview, minimum spreads and
margin](https://www.ig.com/nl/indices)

### Commission costs

IG states that its index CFDs have **no separate commission**; the spread is the principal dealing cost. Other
costs can still apply, including overnight funding for cash index CFDs, currency conversion and optional
guaranteed-stop premiums.

Source: - [IG NL --- CFD trading
costs](https://www.ig.com/nl/cfd-trading) - [IG NL --- index CFD product
conditions](https://www.ig.com/nl/help-en-support/articles/840934-wat-zijn-ig-s-index-cfd-productvoorwaarden)

### Other costs

- Overnight funding/financing and dividend adjustments can apply to cash index CFDs.
- Guaranteed stop-loss orders carry a stated premium.
- Currency conversion may apply if the account currency differs from the instrument's P/L currency.
- Futures-based index CFDs have their own expiry/rollover rules.

Source: - [IG NL --- index CFD product
conditions](https://www.ig.com/nl/help-en-support/articles/840934-wat-zijn-ig-s-index-cfd-productvoorwaarden) -
[IG NL --- costs and charges](https://www.ig.com/nl/kosten-en-tarieven)

### Minimum contract size and contract value per point

IG's Dutch product table publishes contract values per index point:

| Index | Published standard / mini value per point |
| --- | --- |
| S&P 500 | \$250 / \$50 per point in the futures table; Dutch cash schedule displays a \$1 contract denomination |
| Nasdaq 100 | \$100 / \$20 per point in the futures table; Dutch cash schedule displays a \$1 contract denomination |
| DAX 40 | €25 / €5 per point |
| FTSE 100 | £10 / £2 per point |
| Dow Jones | \$1 per point in the Dutch cash schedule |

**Important:** IG's Dutch help material contains different contract denominations across cash, futures and
micro/EUR-denominated product tables. Do not assume the standard/mini figure is the minimum order size. Confirm
the exact TradingView-connected cash CFD's minimum size and point value in the live order ticket. IG itself says
product-level minimum size is displayed in its Market Info/order ticket.

Sources: - [IG NL --- cash and futures contract
specifications](https://www.ig.com/nl/help-en-support/articles/840934-wat-zijn-ig-s-index-cfd-productvoorwaarden) -
[IG Help Centre --- where to find minimum contract size and value per
point](https://intercom-help.eu/ig-prod-help-center/en/articles/626578-product-information)

### Leverage

IG's Dutch index page lists **5% retail margin / 20:1 leverage** for all five selected indices.

Source: - [IG NL --- index margins and
leverage](https://www.ig.com/nl/indices)

### Historical data

IG provides charting and market data through its own platform and TradingView. I did not find a public promise
of downloadable, broker-native tick history or a complete 1-minute historical CFD dataset for all five products.

For systematic backtesting, ask IG:

1. How far back 1-minute bid/ask history is available for each CFD.
2. Whether historical bid/ask data can be exported.
3. Whether TradingView chart history uses IG's executable CFD prices or a separate reference feed.

Sources: - [IG TradingView
integration](https://www.ig.com/nl/handelsplatformen/tradingview) - [IG
index markets](https://www.ig.com/nl/indices)

### Reliability / execution

IG describes its index offering as having deep liquidity and fast execution, but marketing statements are not
an independent measurement of actual slippage. I did not find a current, independently comparable
index-specific fill-rate/slippage dataset for the Dutch retail account.

Test live/demo platform stability, order rejections and stop execution during the 09:00 DAX and 15:30 US opens.
Demo execution should not be assumed to match live execution.

Source: - [IG NL --- index trading](https://www.ig.com/nl/indices)

### Regulation

The relevant EU entity shown in the AFM register is **IG Europe GmbH**, based in Germany. It is authorised in
Germany and passported into the Netherlands. The AFM register explicitly notes that it does not directly
supervise this entity.

Sources: - [AFM register --- IG Europe
GmbH](https://www.afm.nl/en/sector/registers/vergunningenregisters/beleggingsondernemingen/details?id=26FC2DAB-9D03-E911-80E2-005056BB0C82) -
[IG Group --- regulatory
licences](https://www.iggroup.com/about-us/governance/regulations)

**Assessment:** Strong candidate. Particularly useful public Dutch product data. Clarify the precise cash-CFD
point value and minimum trade size before comparing it numerically with the other brokers.

------------------------------------------------------------------------

## B. OANDA TMS

### TradingView integration

**Supported for OANDA TMS clients located in the EU.** This is directly relevant to a Netherlands-based client.

Source: - [OANDA NL --- TradingView
integration](https://www.oanda.com/eu-nl/tradingview)

### Spreads

OANDA TMS publishes instrument-level specifications and historical spread charts. Its products include both
cash and futures-based index CFDs.

For example, its futures-based products include US100.pro (E-mini Nasdaq 100 futures), DE30.pro (DAX 40
futures), GB100.pro (FTSE 100 futures) and US30.pro (Dow Jones futures).

It also lists cash products, including US500.cash. The spread chart is based on its own quoted bid/ask prices
and provides session-based historical minimum, average and maximum spread information.

I have not inserted a single spread number for every index because the product variants and live spread charts
need to be matched to the exact account/product. The published minimum-spread field in a futures specification
is not necessarily the average spread you will pay.

Sources: - [OANDA TMS --- US100 instrument specification and historical
spread
chart](https://www.tmsbrokers.com/market-watch/live-quotes/US100) -
[OANDA TMS --- DE30 instrument specification and historical spread
chart](https://www.tmsbrokers.com/market-watch/live-quotes/DE30) -
[OANDA TMS --- GB100 instrument specification and historical spread
chart](https://www.tmsbrokers.com/market-watch/live-quotes/GB100) -
[OANDA TMS --- US30 instrument specification and historical spread
chart](https://www.tmsbrokers.com/market-watch/live-quotes/US30) -
[OANDA TMS --- instrument
specifications](https://www.oanda.com/eu-nl/instruments-specification)

### Commission costs

OANDA's index-CFD marketing page states that there is no commission and that the spread is the trading cost. Its
retail fee schedule also lists zero execution commission for index CFDs as "other financial instruments".

The fee schedule distinguishes retail from professional clients. Do not confuse the professional-client
commission schedule with the retail account.

Sources: - [OANDA NL --- index CFD
costs](https://www.oanda.com/eu-nl/indices-cfd) - [OANDA TMS --- fees
and commissions, valid from 30 April
2026](https://www.oanda.com/eu-nl/document/53)

### Other costs

- OANDA's EU index page advertises no daily financing cost on US and German indices. Confirm the exact
  instrument variant and current account schedule.
- Other indices may have different swap/financing treatment.
- Currency conversion may apply if the account currency differs from the product's quote currency.
- The futures-based products have futures-linked pricing and contract-specific trading hours.

Sources: - [OANDA NL --- index
CFDs](https://www.oanda.com/eu-nl/indices-cfd) - [OANDA TMS --- product
specifications](https://www.tmsbrokers.com/market-watch/live-quotes/US100)

### Minimum contract size and contract value per point

OANDA TMS publishes minimum order values and contract sizes for individual instruments. The following are the
publicly visible specifications for the futures-based contracts:

| Index | Product | Contract value per 1 lot | Minimum order | Transaction step |
| --- | --- | --- | --- | --- |
| Nasdaq 100 | US100.pro | Price × \$20; \$20 per index point per lot | 0.001 lot | 0.001 |
| DAX 40 | DE30.pro | Price × €25; €25 per index point per lot | 0.002 lot | 0.002 |
| FTSE 100 | GB100.pro | Price × £10; £10 per index point per lot | 0.01 lot | 0.01 |
| Dow Jones | US30.pro | Price × \$5; \$5 per index point per lot | 0.002 lot | 0.002 |
| S&P 500 | US500.cash | Price × \$1 per lot as listed on the cash-product page | 10 units | 10 |

The S&P row is a **cash product**, whereas the other rows above are futures-based CFDs. OANDA also publishes
futures-based US500.pro specifications; compare the exact product available in the connected account before
deciding which variant to use.

Sources: - [OANDA TMS ---
US100.pro](https://www.tmsbrokers.com/market-watch/live-quotes/US100) -
[OANDA TMS ---
DE30.pro](https://www.tmsbrokers.com/market-watch/live-quotes/DE30) -
[OANDA TMS ---
GB100.pro](https://www.tmsbrokers.com/market-watch/live-quotes/GB100) -
[OANDA TMS ---
US30.pro](https://www.tmsbrokers.com/market-watch/live-quotes/US30) -
[OANDA TMS ---
US500.cash](https://www.tmsbrokers.com/market-watch/live-quotes/US500)

### Leverage

The OANDA TMS specifications list retail margin of 5% for the selected major index futures contracts,
corresponding to **20:1 retail leverage**. Some pages also show a higher professional/experienced-client margin
tier. That higher figure is not the normal EU retail limit.

Source: - [OANDA TMS --- individual index product
specifications](https://www.tmsbrokers.com/market-watch/live-quotes/US100)

### Historical data

**A notable strength.** OANDA TMS states that it saves every price change (tick) and makes historical spread
charts available. The charts can be broken down by European, American and Asian sessions, with minimum, average
and maximum spread statistics.

This is particularly relevant to your intraday strategy because it lets you investigate the spread during your
actual trading window, rather than relying only on a headline minimum spread.

This does not automatically mean that a downloadable, long-history 1-minute bid/ask archive is included. Ask
what data can be exported and how far back it goes.

Sources: - [OANDA TMS --- US100 historical spread
chart](https://www.tmsbrokers.com/market-watch/live-quotes/US100) -
[OANDA --- instrument specifications and historical spread
charts](https://www.oanda.com/eu-nl/instruments-specification)

### Reliability / execution

OANDA TMS publishes a best-execution policy describing quote aggregation, filtering of erroneous/outlier quotes
and monitoring of execution quality, including rejected orders and requotes. This is useful policy-level
information, but it is not a substitute for instrument-specific live slippage statistics.

Sources: - [OANDA TMS --- best execution policy / legal
documents](https://www.oanda.com/eu-de/document/31) - [OANDA TMS ---
product
specifications](https://www.tmsbrokers.com/market-watch/live-quotes/US100)

### Regulation

The relevant entity is **OANDA TMS Brokers S.A.**, based in Poland and supervised by the Polish Financial
Supervision Authority (KNF). The AFM register lists it as an incoming EEA-passported investment firm and states
that the AFM does not directly supervise it.

Sources: - [AFM register --- OANDA TMS Brokers
S.A.](https://www.afm.nl/en/sector/registers/vergunningenregisters/beleggingsondernemingen/details?id=6E2C6BC5-A486-ED11-A2FF-005056BBFEB2) -
[OANDA TMS --- instrument specification/legal
details](https://www.tmsbrokers.com/market-watch/live-quotes/US100)

**Assessment:** Very interesting for your use case because of the detailed instrument specifications and
historical spread charts. Be careful to compare cash with cash or futures-based with futures-based products.

------------------------------------------------------------------------

## C. Pepperstone

### TradingView integration

**Supported.** Pepperstone lists TradingView as one of its trading platforms. The EU entity is Pepperstone EU
Limited.

Source: - [Pepperstone EU --- platforms and
TradingView](https://pepperstone.com/en-eu/) - [Pepperstone EU --- legal
documents](https://pepperstone.com/en/about-us/policies/legal)

### Spreads

Pepperstone publishes minimum and average spreads for index CFDs. Its public North American table currently
shows:

| Index | Minimum spread | Average spread shown |
| --- | ---: | ---: |
| S&P 500 (US500) | 0.4 | 0.4 |
| Nasdaq 100 (NAS100) | 1.0 | 1.0 |
| Dow Jones (US30) | 2.0 | 2.0 |

The table shows the same index spread figures for Standard and Razor accounts because Pepperstone does not
charge commission on index CFDs.

For DAX and FTSE, the website has a separate Europe tab. The public material reviewed confirms that GER40 and
UK100 cash CFDs are available, but I could not extract a current, dated EU-account average-spread figure for
both products from the public table. The forward CFD products have separate minimum spreads (GER40-F 3 points
and UK100-F 3 points); these are not the cash-CFD spreads.

Sources: - [Pepperstone --- index CFD spreads and
fees](https://pepperstone.com/en/markets/indices/index-fees) -
[Pepperstone EU --- index
CFDs](https://pepperstone.com/en-eu/markets/indices) - [Pepperstone ---
CFD forward
specifications](https://pepperstone.com/en/markets/indices/index-fees)

### Commission costs

Pepperstone states that it charges **no commission on index CFDs** on either Standard or Razor accounts. The
spread is the main dealing cost.

Source: - [Pepperstone --- index CFD
fees](https://pepperstone.com/en/markets/indices/index-fees)

### Other costs

- Overnight financing applies to cash index CFDs. Pepperstone publishes its index swap calculation and a 2.5%
    broker charge component in the formula.
- Index forward CFDs have no additional overnight funding charge; financing is incorporated into the spread.
    They are rolled to the next contract month if still held at expiry.
- Currency conversion and other account-level charges may apply.

Source: - [Pepperstone --- index CFD fees, swaps and
forwards](https://pepperstone.com/en/markets/indices/index-fees)

### Minimum contract size and contract value per point

Pepperstone's public index-spread page does not provide a complete, current EU cash-index table of minimum size
and contract value per point for all five instruments.

The forward-index table lists a minimum size of 1 contract for GER40-F, UK100-F, US30-F, NAS100-F and US500-F.
These are **forward CFDs**, not the cash contracts.

Do not infer the cash CFD minimum size or point value from the forward table. Confirm the following in the EU
TradingView-connected account or its instrument specification:

- Minimum volume and volume step for US500, NAS100, US30, GER40 and UK100.
- Value of one index point for one lot.
- Whether the account's TradingView route uses the same contract
    specification as MT5/cTrader.

Source: - [Pepperstone --- index CFD and forward
specifications](https://pepperstone.com/en/markets/indices/index-fees)

### Leverage

For a Netherlands/EU retail account, the major indices are subject to the **20:1 maximum leverage / 5% margin**
retail limit. Do not use the higher leverage figures shown on non-EU Pepperstone pages as the Dutch retail
setting.

Sources: - [ESMA --- CFD product
intervention](https://www.esma.europa.eu/press-news/esma-news/esma-agrees-prohibit-binary-options-and-restrict-cfds-protect-retail-investors) -
[Pepperstone EU --- legal and regulatory
information](https://pepperstone.com/en-eu/)

### Historical data

Pepperstone's public spread-cost page publishes dated average/minimum spread calculations. It does not establish
that a long-history downloadable tick/bid/ask archive is available for every index CFD.

TradingView chart history should not be assumed to be the same thing as an exportable archive of Pepperstone's
executable bid/ask quotes.

Ask Pepperstone for:

1. Historical 1-minute bid/ask data for each of the five CFDs.
2. Historical tick-data availability and retention period.
3. Historical spread statistics by session.
4. Whether TradingView candles are built from Pepperstone's own CFD quotes.

Source: - [Pepperstone --- index fees and spread observation
period](https://pepperstone.com/en/markets/indices/index-fees)

### Reliability / execution

Pepperstone advertises execution speeds and fill-rate statistics on its website. These are provider-reported
figures and may cover a broader product/account population rather than the five index CFDs and the EU
TradingView route specifically.

For the EU website, Pepperstone reports:

- Execution speeds from approximately 50 milliseconds.
- A reported fill rate of 99.00% on a published measurement period (check the live page for the latest period and definition).

Treat these as useful starting points, not proof of low slippage on NAS100 or GER40 during volatile openings.

Sources: - [Pepperstone EU --- index trading and execution
information](https://pepperstone.com/en-eu/markets/indices) -
[Pepperstone EU --- legal
documents](https://pepperstone.com/en/about-us/policies/legal)

### Regulation

For the EU service, the relevant entity is **Pepperstone EU Limited**, registered in Cyprus and regulated by the
Cyprus Securities and Exchange Commission (CySEC), licence 388/20. The AFM register should be checked for the
entity's current passport status for the Netherlands and the account agreement should confirm that this is the
contracting entity.

Sources: - [Pepperstone EU --- legal and regulatory
information](https://pepperstone.com/en-eu/) - [Pepperstone legal
documents](https://pepperstone.com/en/about-us/policies/legal)

**Assessment:** Strong candidate on published US index spreads and zero index commission. The main gaps to
resolve are current cash GER40/UK100 spreads, minimum cash-contract sizes and point values for the EU account.

------------------------------------------------------------------------

## D. CMC Markets

### TradingView integration

**Supported on the standard CFD account.** CMC says the standard CFD account can be linked to TradingView so
orders can be opened, managed and closed from TradingView. Its separate MT4 account does not provide access to
this integration.

Source: - [CMC Markets --- index trading and
TradingView](https://www.cmcmarkets.com/en/indices)

### Spreads

CMC publishes instrument-specific minimum spreads on its index product pages. The figures below are from the
product pages reviewed:

| Index | Published minimum spread |
| --- | ---: |
| S&P 500 (US SPX 500 Cash) | 0.50 points |
| Nasdaq 100 (US NDAQ 100 Cash) | 1.00 point |
| DAX 40 (Germany 40 Cash) | 1.20 points |
| FTSE 100 (UK 100 Cash) | 0.50 points |
| Dow Jones (US 30 Cash) | 2.20 points |

These are minimum spreads, not average spreads. Some of the public product pages are country-specific and may
show a different retail entity, margin schedule or promotion. Confirm the exact Netherlands-account figures in
the CMC order ticket before treating the table as a final quote.

Sources: - [CMC --- US SPX 500
Cash](https://www.cmcmarkets.com/en-de/instruments/us-spx-500-cash) -
[CMC --- US NDAQ 100
Cash](https://www.cmcmarkets.com/en-ie/instruments/us-ndaq-100-cash) -
[CMC --- Germany 40
Cash](https://www.cmcmarkets.com/en-gb/instruments/germany-40-cash) -
[CMC --- UK 100
Cash](https://www.cmcmarkets.com/en-de/instruments/uk-100-cash) - [CMC
--- US 30 Cash](https://www.cmcmarkets.com/en-gb/instruments/us-30-cash)

### Commission costs

CMC states that CFD commissions apply to shares and ETFs, not index CFDs. Therefore, for the five selected index
CFDs, the main transaction cost is the spread.

Source: - [CMC --- account and cost
comparison](https://www.cmcmarkets.com/en-de/compare-trading-accounts)

### Other costs

- Overnight holding costs apply to cash index CFDs. The individual product pages publish daily buy and sell
  holding-cost rates.
- Currency conversion may apply if the account currency differs from the instrument's currency.
- Guaranteed stop-loss orders may carry a premium.
- Other account-level charges should be checked in the Netherlands client agreement.

Sources: - [CMC --- index product
pages](https://www.cmcmarkets.com/en/indices) - [CMC --- trading
costs](https://www.cmcmarkets.com/en-de/compare-trading-accounts)

### Minimum contract size and contract value per point

The individual product pages reviewed show a **minimum size of 0.01** for the five products. CMC describes CFD
trade size as a number of units/notional value and supports fractional trade sizes.

| Index | Minimum size shown publicly | Value per point |
| --- | ---: | --- |
| S&P 500 | 0.01 | Unit-based; confirm point value in order ticket |
| Nasdaq 100 | 0.01 | Unit-based; confirm point value in order ticket |
| DAX 40 | 0.01 | Unit-based; confirm point value in order ticket |
| FTSE 100 | 0.01 | Unit-based; confirm point value in order ticket |
| Dow Jones | 0.01 | Unit-based; confirm point value in order ticket |

CMC does not present one universal "one lot = X currency per point" convention in the public product pages
reviewed. The actual monetary value per point depends on the instrument's unit definition and position size.
Before trading, use the order ticket to establish the cash P/L for a one-point move at the minimum size.

Sources: - [CMC --- account comparison and fractional trade
sizes](https://www.cmcmarkets.com/en-de/compare-trading-accounts) - [CMC
--- US SPX 500
Cash](https://www.cmcmarkets.com/en-de/instruments/us-spx-500-cash) -
[CMC --- US NDAQ 100
Cash](https://www.cmcmarkets.com/en-ie/instruments/us-ndaq-100-cash) -
[CMC --- Germany 40
Cash](https://www.cmcmarkets.com/en-gb/instruments/germany-40-cash) -
[CMC --- UK 100
Cash](https://www.cmcmarkets.com/en-de/instruments/uk-100-cash) - [CMC
--- US 30 Cash](https://www.cmcmarkets.com/en-gb/instruments/us-30-cash)

### Leverage

The EU retail maximum for these major index CFDs is **20:1 / 5% margin**. Some CMC global pages advertise higher
leverage, but those figures are not the correct reference for a Netherlands-based EU retail account.

Source: - [ESMA --- CFD product
intervention](https://www.esma.europa.eu/press-news/esma-news/esma-agrees-prohibit-binary-options-and-restrict-cfds-protect-retail-investors)

### Historical data

CMC product pages show charts and historical price views. I did not find a public guarantee of a downloadable
long-history 1-minute bid/ask or tick archive for all five index CFDs.

Ask CMC:

- Whether 1-minute bid/ask data is downloadable.
- How far back CFD-specific historical data extends.
- Whether historical prices are CMC's executable CFD quotes.
- Whether TradingView receives the same CFD quote feed as the CMC platform.

Sources: - [CMC --- index
trading](https://www.cmcmarkets.com/en/indices) - [CMC --- instrument
pages](https://www.cmcmarkets.com/en/instruments/us-30-cash)

### Reliability / execution

CMC describes automated execution and publishes platform/execution claims. It also reports fill-rate
information on its platform pages. These are broker-reported, not a direct comparison of live index-CFD slippage.

For this strategy, test order handling and stop execution during the DAX and US opens rather than relying on
general platform claims.

Source: - [CMC --- index trading and execution
information](https://www.cmcmarkets.com/en/indices)

### Regulation

For EU clients, the relevant entity is **CMC Markets Germany GmbH**, based in Frankfurt and regulated by BaFin. It
is passported into the Netherlands. The AFM register notes that it does not directly supervise this German
entity.

Sources: - [AFM register --- CMC Markets Germany
GmbH](https://www.afm.nl/en/sector/registers/vergunningenregisters/beleggingsondernemingen/details?id=B3045630-C2A1-EB11-A2DE-005056BB4E9F) -
[CMC Markets Germany --- imprint and BaFin
details](https://www.cmcmarkets.com/en-de/imprint)

**Assessment:** Strong candidate for the combination of TradingView, small minimum size and product-level
spread/holding-cost disclosure. The main remaining question is the exact monetary point value at 0.01 size and
whether the published product-page figures match the Dutch account.

------------------------------------------------------------------------

## E. easyMarkets

### TradingView integration

**Supported.** easyMarkets says customers can connect their account to TradingView, place trades directly from
charts and manage/close those trades through its connected easyMarkets account.

Source: - [easyMarkets --- TradingView
integration](https://www.easy-markets.com/int/platforms/tradingview) -
[easyMarkets --- integration
announcement](https://www.easy-markets.com/int/about/company/easymarkets-integrates-with-tradingview/)

### Spreads

easyMarkets publishes fixed spreads for its Web/App/TradingView route. The published index table identifies these
as **future indices**. The figures below are the regular-session fixed spread and the later-session figure where a
second value is shown:

| Index | Product symbol | Published fixed spread |
| --- | --- | --- |
| S&P 500 | SPI/USD | 1 point during 22:00--19:00; 2.4 points during 19:00--21:00 |
| Nasdaq 100 | NDQ/USD | 3 points during 22:00--19:00; 7 points during 19:00--21:00 |
| DAX 40 | DAX/EUR | 6 points during 07:00--15:30; 12 points during 00:31--07:00 and 15:30--20:00 |
| FTSE 100 | FTS/GBP | 4 points during 07:00--20:00; 8 points during 00:00--07:00 |
| Dow Jones | DOW/USD | 6 points during 22:00--19:00; 12 points during 19:00--21:00 |

These are the figures on easyMarkets' published global pricing page. The Netherlands/EU account may be routed to
a different legal entity and product schedule. Confirm the actual EU account quote and TradingView product
before relying on these numbers.

Sources: - [easyMarkets --- published index spreads and contract
specifications](https://www.easy-markets.com/int/trade/forex-spreads/) -
[easyMarkets --- S&P 500 product
page](https://www.easy-markets.com/int/trade/indices/spi-usd/)

### Commission costs

easyMarkets advertises no commission on its TradingView offering. Its pricing page describes fixed spreads and
no hidden commission. Verify the same terms in the EU client agreement.

Source: - [easyMarkets --- TradingView account benefits and
costs](https://www.easy-markets.com/int/platforms/tradingview)

### Other costs

easyMarkets advertises no funding or hidden fees on its TradingView page and offers a guaranteed stop-loss
feature with a wider spread/premium condition. Confirm the exact EU account terms, any rollover treatment on the
futures-based index CFDs, and any currency conversion charges.

Source: - [easyMarkets --- TradingView
conditions](https://www.easy-markets.com/int/platforms/tradingview)

### Minimum contract size and contract value per point

The published futures-index table gives contract values per index point:

| Index | Published value of one contract |
| --- | ---: |
| S&P 500 (SPI/USD) | \$50 per index point |
| Nasdaq 100 (NDQ/USD) | \$20 per index point |
| DAX 40 (DAX/EUR) | €13 per index point |
| FTSE 100 (FTS/GBP) | £10 per index point |
| Dow Jones (DOW/USD) | \$5 per index point |

The public table reviewed does **not** clearly state the minimum contract size or volume step for these index
products. Ask easyMarkets to confirm the minimum order and increment for the TradingView route before opening an
account.

Source: - [easyMarkets --- index spread and contract-size
table](https://www.easy-markets.com/int/trade/forex-spreads/)

### Leverage

The easyMarkets international pricing page displays leverage figures as high as 1:400/1:500. **Those are not
the appropriate leverage figures for a Dutch/EU retail client.**

The relevant EU retail maximum for these major index CFDs is **20:1 / 5% margin**, subject to the applicable EU
account classification and instrument.

Source: - [ESMA --- CFD product
intervention](https://www.esma.europa.eu/press-news/esma-news/esma-agrees-prohibit-binary-options-and-restrict-cfds-protect-retail-investors)

### Historical data

easyMarkets provides TradingView charting and market data, but I did not find a public commitment to downloadable
historical bid/ask or tick-level execution data for its index CFDs.

Ask whether it can provide:

- 1-minute historical CFD bid/ask data.
- Tick history and retention period.
- Historical spread distributions by session.
- The precise source of the TradingView chart feed.

Source: - [easyMarkets --- TradingView
platform](https://www.easy-markets.com/int/platforms/tradingview)

### Reliability / execution

easyMarkets advertises fixed spreads, negative-balance protection and a guaranteed stop-loss feature with no
slippage when the applicable feature is selected. A guaranteed stop is different from ordinary stop execution:
it may involve a wider spread or premium and should be compared on its own terms.

The legal page lists historical execution-quality reports, but the visible reports are old. I did not find a
current, independently comparable index-specific fill-rate or slippage study.

Sources: - [easyMarkets --- TradingView and guaranteed stop
conditions](https://www.easy-markets.com/int/platforms/tradingview) -
[easyMarkets --- legal documents and execution-quality
reports](https://www.easy-markets.com/int/legal/)

### Regulation

The AFM register lists **Easy Forex Trading Limited**, trading as easyMarkets, based in Cyprus, as an incoming
EEA-passported investment firm. The AFM notes that it does not directly supervise this Cyprus entity. CySEC lists
Easy Forex Trading Ltd under licence 079/07.

Do not confuse this EU entity with EF Worldwide Ltd, which appears on easyMarkets' international site and is
licensed in offshore jurisdictions. Confirm that a Dutch application is opened with Easy Forex Trading Ltd and
that the client agreement names that entity.

Sources: - [AFM register --- Easy Forex Trading Limited /
easyMarkets](https://www.afm.nl/en/sector/registers/vergunningenregisters/beleggingsondernemingen/details?id=523FF86E-68A1-E011-A203-005056BE6692) -
[CySEC --- Easy Forex Trading Ltd, licence
079/07](https://www.cysec.gov.cy/en-GB/entities/investment-firms/cypriot/37685/) -
[easyMarkets --- legal entity routing and
licences](https://www.easy-markets.com/int/legal/)

**Assessment:** Interesting if fixed spreads and TradingView are priorities. The futures-based contract values
are clearly stated, but minimum size, EU-specific pricing and the applicable entity must be confirmed.

------------------------------------------------------------------------

# 4. Cross-broker summary

## TradingView and regulation

| Broker | Direct TradingView trading | Netherlands/EU entity identified | Regulator |
| --- | --- | --- | --- |
| IG | Yes | IG Europe GmbH | BaFin (Germany); EEA passport into NL |
| OANDA | Yes, OANDA TMS EU integration | OANDA TMS Brokers S.A. | KNF (Poland); EEA passport into NL |
| Pepperstone | Yes | Pepperstone EU Limited | CySEC (Cyprus) |
| CMC Markets | Yes, standard CFD account | CMC Markets Germany GmbH | BaFin (Germany); EEA passport into NL |
| easyMarkets | Yes | Easy Forex Trading Limited | CySEC (Cyprus); EEA passport into NL |

AFM register pages: - [IG Europe
GmbH](https://www.afm.nl/en/sector/registers/vergunningenregisters/beleggingsondernemingen/details?id=26FC2DAB-9D03-E911-80E2-005056BB0C82) -
[OANDA TMS Brokers
S.A.](https://www.afm.nl/en/sector/registers/vergunningenregisters/beleggingsondernemingen/details?id=6E2C6BC5-A486-ED11-A2FF-005056BBFEB2) -
[CMC Markets Germany
GmbH](https://www.afm.nl/en/sector/registers/vergunningenregisters/beleggingsondernemingen/details?id=B3045630-C2A1-EB11-A2DE-005056BB4E9F) -
[Easy Forex Trading
Limited](https://www.afm.nl/en/sector/registers/vergunningenregisters/beleggingsondernemingen/details?id=523FF86E-68A1-E011-A203-005056BE6692) -
[Pepperstone EU legal page](https://pepperstone.com/en-eu/)

## Spreads --- selected indices

These are the best public figures located in this research, but they are **not a perfectly like-for-like
ranking**. Some are minimum spreads, some are time-dependent dealing spreads, and some relate to futures-based
CFDs rather than cash CFDs.

| Broker | S&P 500 | Nasdaq 100 | DAX 40 | FTSE 100 | Dow Jones |
| --- | --- | --- | --- | --- | --- |
| IG | 0.5 in US session | 1.1 in US session | 1.4 in main session | 1 in main session | 2.4 in US session |
| OANDA TMS | Check product spread chart | Check product spread chart | Check product spread chart | Check product spread chart | Check product spread chart |
| Pepperstone | 0.4 min / 0.4 avg published | 1.0 min / 1.0 avg published | Current cash average needs confirmation | Current cash average needs confirmation | 2.0 min / 2.0 avg published |
| CMC Markets | 0.50 min | 1.00 min | 1.20 min | 0.50 min | 2.20 min |
| easyMarkets | 1 fixed (SPI futures CFD) | 3 fixed (futures CFD) | 6 fixed in main stated session (futures CFD) | 4 fixed in main stated session (futures CFD) | 6 fixed (futures CFD) |

## Commission and leverage

| Broker | Separate commission on index CFDs | EU retail maximum leverage for selected major indices |
| --- | --- | ---: |
| IG | No | 20:1 |
| OANDA TMS | No for retail index CFDs, according to fee schedule | 20:1 |
| Pepperstone | No | 20:1 |
| CMC Markets | No on indices | 20:1 |
| easyMarkets | Advertises no commission; verify EU account agreement | 20:1 |

## Minimum size and point value --- key differences

| Broker | Minimum size publicly established? | Contract value per point publicly established? |
| --- | --- | --- |
| IG | Product ticket / Market Info; standard and mini values published, but product variants differ | Yes, but distinguish cash, futures and micro/EUR variants |
| OANDA TMS | Yes, for individual products | Yes, for individual products |
| Pepperstone | Not completely for all five cash CFDs in the public EU material reviewed | Must confirm exact cash CFD contract specification |
| CMC Markets | 0.01 shown on individual product pages reviewed | Unit-based; confirm actual point value in order ticket |
| easyMarkets | Not clearly stated for the five index CFDs in the public pricing table | Yes, for the published futures-index contracts |

------------------------------------------------------------------------

# 5. What I would prioritise for your intraday strategy

For a 1-minute intraday strategy, I would not rank brokers by minimum spread alone. I would rank them by the
following:

1. **Average spread during the exact trading window.** For you, that means the DAX open and US open, not a
   24-hour average.
2. **Slippage on market and stop orders.** This can outweigh a small difference in headline spread.
3. **Minimum cash risk per trade.** Minimum size × currency value per point × stop distance must allow
   sufficiently fine position sizing.
4. **Historical bid/ask data.** You need data suitable for testing entries, stop-losses and realistic execution
   costs.
5. **Platform execution.** Confirm that the TradingView connection supports the order types you actually use,
   and that stop-loss/take-profit orders are held by the broker.
6. **Legal entity and retail protections.** Confirm the entity in the client agreement rather than relying on the
   broker's global brand or website.

## 6. Questions to send to each broker

To complete the comparison fairly, ask every broker the same questions:

1. What is the minimum order size and volume increment for each of the five **cash index CFDs** on the
   TradingView-connected account?
2. What is the exact currency value of one index point at the minimum order size?
3. Can you provide the average bid/ask spread by 15-minute interval for the last 30 trading days?
4. Can you provide 1-minute bid/ask history or tick data for at least the last 12 months?
5. What are your measured market-order and stop-loss slippage statistics for these five indices?
6. Are stops and limits submitted through TradingView held server-side by the broker?
7. Which legal entity will be the counterparty to a Netherlands-resident retail client?

For a proper apples-to-apples comparison, request **cash CFDs for all five indices** first. If a broker offers
only a futures-based CFD for one product, record it separately rather than mixing it into the cash-CFD table.

------------------------------------------------------------------------

## 7. Source list and research limitations

The links in each broker section are the primary product, pricing, platform, legal or regulatory pages used for
the information presented. Product prices, spreads, margin schedules and legal terms can change. The research
was performed on **21 November 2026**.

Some information is not fully available from public pages:

- Current session-average spreads for every index and every broker.
- Minimum order size and point value for all five Pepperstone cash CFDs.
- CMC's monetary point value at its 0.01 minimum size.
- easyMarkets' minimum index-CFD order size for the EU TradingView route.
- Comparable long-history downloadable bid/ask data for all brokers.

These are deliberately marked as items to verify, not estimated.

This document is an information-gathering comparison, not a recommendation to trade CFDs or a personal
investment recommendation. CFDs are leveraged products and can result in rapid losses.
