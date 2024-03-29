
### Why is Tether Important?

In the instance that for every dollar received a Tether has been printed, Tether is not particularly important other than for its status as the first and largest stablecoin.

If however that relationship was, or is, decoupled and some significant percentage of Tethers were printed with less than 1 USD backing then Tether is very important.

Let us explore.

Let us define a simple model with three trading pairs.

1. USD - USDT
2. USDT - BTC
3. BTC - USD

Furthermore suppose the peg holds and 1 USDT = 1 USD on the market. Also 4 USD purchase 1 BTC, therefore 4 USDT can purchase 1 BTC. Again let us assume there is a single exchange designated as the market.

Let us assume there is a Tether tresury where USDT can be purchased off market. Let X define the cost in USD to buy 1 USDT from the Tether Tresury.

Suppose X = 1 for Person A.  Person A purchases 1 USDT from the Tresury for 1 USD. Person A then enters the market with 1 USDT. As specified above the peg holds and they are able to exchange 1 USDT back for 1 USD. They are also able to exchange their USDT for 0.25 BTC or if they traded their 1 USDT for 1 USD they could also trade that 1 USD for 0.25 BTC.

Table 1 - Possible outputs when X = 1

| Inputs | Possible Outputs |
|--------|------------------|
| 1 USD  | 1. 1 USDT        |
|        | 2. 1 USD         |
|        | 3. 0.25 BTC      |

Let us now suppose X = 0.1. In this instance person B is able to purchase 10 Tethers for 1 USD from the Tether Tresury. They can then go the market and purchase 10 USD for their 10 USDT. Or they can exchange their 10 USDT for 0.25 * 10 = 2.5 BTC.

Where X = 0.1 the possible inputs for a 1 USD input are.

Table 2 - Possible outputs when X = 0.1

| Inputs | Possible Outputs |
|--------|------------------|
| 1 USD  | 1. 10 USDT       |
|        | 2. 10 USD        |
|        | 3. 2.5 BTC       |

Let us complicate our model slightly and introduce pricing depth for market 2. USDT - BTC.

Table 3 - BTC to USDT - Example Market Depth

| BID            | OFFER          |
|----------------|----------------|
| Volume / Price | Price / Volume |
| 1 / 3          | 4 / 1          |
| 1 / 2          | 5 / 1          |
| 1 / 4          | 6 / 1          |

Now let us go back back to person A who is able to purchase 1 USDT from the Tether Tresury where X = 1. Let us talk through the possible outcomes again. Person A purchases their 1 USDT for 1 USD and then enters the market and can again buy 1 USD, or they can purchase 0.25 BTC.

Table 4 - Possible outputs when X = 1 with market depth

| Inputs | Possible Outputs |
|--------|------------------|
| 1 USD  | 1. 1 USDT        |
|        | 2. 1 USD         |
|        | 3. 0.25 BTC      |

Assume X is still equal to 0.1 for Person B and let us review their possible outcomes with the newly added pricing depth to market 2. Person B buys 10 Tethers for 1 USD. They go to the market and they are able to purchase 10 USD, or 1 BTC @ 4 USDT, 1 BTC @ 5 USDT and 0.17 BTC @ 6 USDT.

Table 5 - Possible outputs when X = 0.1 with market depth

| Inputs | Possible Outputs |
|--------|------------------|
| 1 USD  | 1. 10 USDT       |
|        | 2. 10 USD        |
|        | 3. 2.17 BTC      |

Person B in Scenario 2 cannot purchase as many BTC, as they could in Scenario 1 when they could purchase infinity BTC at 0.25 BTC/USDT 

Scenario 2 displays the implications in pricing of BTC when there is an ability to acquire USDT for less than 1 USD.

### Possible ways Tether has maintained its Peg
1/08/21

Over the past couple of months post the NYAG's investigation, there has been increasing public scrutiny of the stablecoin Tether. Tether is one of the most actively traded cryptocurrencies in existence, often in the top 3 daily active traded cryptocurrencies alongside BTC and ETH. Tether is privately owned and managed. Stablecoins are intended to maintain a fixed or at least "stable" pricing relationship with another currency or asset. 

There are currently questions about the legitamacy of the executives that run Tether. This post does not seek to investigate these accusations but instead present theoretically how Tether has managed to maintain its goal peg to the US dollar. The following is based purely on assumption and should not be considered fact.

In general if a pegged currency and for the purposes of this post, a cryptocurrency, trades above the underlying asset, there is an incentive for the general public to purchase the cryptocurrency directly from the managers of the cryptocurrency at the pegged rate and sell it on market to make the "risk-free" arbirtrage profit. For example if there are buy orders on Binance, or some other Tether supporting exchange, for let us say $1.10 USD, then there is an incentive to buy new Tethers from Tether directly and sell them into that buy order, there by reducing the price of Tethers on the market and making yourself a $1.10 - $1 = $0.1 USD per Tether profit. For a regular currency, its central bank could issue more of its currency to achieve the same function.

That is relatively simple but what about if there are sell orders for Tethers for less than $1 USD, we could say that Tethers are trading below the pegged price. In this instance the expected arbitrage mechanism is for a buyer to buy the Tether which is being sold let's say for $0.9c and then "sell" or "redeem" them to Tether for the pegged rate of $1 USD to make a "risk-free" arbitrage profit of again $0.1 USD minus any fees relating to the redemption. A regular currency for comparison could sell its reserves of other currencies, or assets for its own currencies there by increasing demand.

This is relatively simple, there are more complicated examples due to Tether being traded against other cryptocurrencies, who are then also traded against USD. These can provide other arbitrage opportunities.

Now the conjecture is that it is relatively difficult to redeem Tethers, you have to be a trusted partner and the market capitalisation has only really grown over the past 5 years suggesting that redemptions are rare and relatively small compared to new issuance. This is not really surprising as you can transfer tethers into dollars on a Tether supporting exchange, instead of having to create a new relationship with Tether.

Lets assume for this blog that it is effectively impossible to redeem Tethers from Tether itself. This means the simplest mechanism for arbitraging Tethers that are trading below the peg does not exist. Then how would Tether manage to maintain the Peg?

This is where we have to make some assumptions that are difficult to really confirm. Tether has received some amount of dollars for the Tethers it has printed. According to its report of assets provided to the NYAG these are not held as dollars entirely but as other assets, predominately commercial paper, but also including other cryptocurrencies. If Tether wanted to use its reserves to support its peg, and reduce the demand for redemptions than we could assume that a portion of that commercial paper is used to buy reserve cryptocurrencies that can be sold on market to prop up the market price of Tether.

Lets explore this last assumption, these entities could purchase Tethers on market using their reserve cryptocurrency assets, funded by loans from Tether, to stablise the price of tethers when their is limited organic demand for them. These entities could then sell these Tethers purchased during periods of limited demand and sell them during times of increased demand for Tether.

As of today (1/8/2021) there are 61.81 billions Tethers in circulation. Tether themselves have confirmed that these assets are not backed one for one by USD but it is unkown how much reserves it and its affiliate entities have to maintain the peg in the event of an extended sell off.

### Why Callide C's Failure is an important signal for Australia's National Energy Market

Today, energy grids across the world are trying to de-carbonise. This isn't purely out of the goodness of energy generators, politicians and public servants hearts. But due the levelised cost of energy from renewable sources now matching or under pricing the cost of even legacy carbon intensive generation. This shift has in combination with strong consumer and business demand for renewable energy meant that the vast majority of new generation projects built by both number and capacity are renewable projects.

In line with this reduction in cost of renewable energy generation price but more recently biased the price of energy storage, namely batteries has also decreased. Batteries have not seen the levels of consumer and market penetration as renewable deployments. The delta between these two can be explained to some extent by the respective maturities of these technologies however that does not explain the entire difference.

Currently the National Energy Market (NEM) is in a unique place. The majority of Electricity generation comes from coal fired power stations with an average age of >20 years and with an average expected life span of an additional 15 years going forward. A large amount of largely price inelastic residential and large scale solar has been deployed in the past 15-20 years leading to some of the cheapest relative average electricity prices the country has ever seen. But also a relatively severe duck curve.

During daylight hours in high radiation days the marginal price of electricity can sometimes fall below zero, leading to large scale curbing of generation assets across the country, this means that large amounts of energy are effectively wasted, before the sun sets and their are substantial price increases in the evening.

Although the difference between these two prices provides a battery some opportunity to arbitrage, this opportunity is curbed by legacy coal fired power stations increasing generation during the two sides of the duck curve, to maximize their revenue. Prospective battery developers have to fund projects with some forecasted view of how power prices will look in the near future when coal fired power stations close. These forecasts are not generally sufficient in order to secure the required financing, as currently batteries in the NEM make the majority of their revenue via ancillary services, like frequency modulation, rather than true arbitrage revenue, and these services are not seen as being scalable.

The failure of Callide C in Queensland provides a window in to a near future of the NEM. Prospective battery, and renewable developers, will be pleased to see the general price levels increase in the wake of its issues, and the value of their prospective arbitrage opportunities have increased. This is after the closure of just one-third of a single Coal Fired Power Station. There are lots more that will need to close down in the not too distant future.

### The Curious Case of NBIM Investing and Divesting in an Australian Microcap.

One of, in my opinion, the most amazing online documents is held on Norways soverign wealth funds website. It has over 20 years of the funds investments available to be searched easily, denominated in both Kroner and USD. Norways sovereign wealth fund is the largest in the world and the bredth and depth of their investments is well worth a browse.

The Norweigan Soverign wealth fund invests in Equities all around the world. In Australia it uses Citicorp and J.P Morgan as nominees, this is why you don't often see Norges Bank Investment Management (NBIM), the investment manager of the soveriegn wealth fund, appear on many of the ASX listed companies top 20 holdings in their annual reports. They do have massive stakes though, from a 1.4 billion USD interest in CSL Ltd representing a 1.4% ownership stake, a larger stake than even the Australian government owns of the once public asset, to a 26 million USD interest in department store chain Myer Holdings LTD, a 1.68% ownership stake.

An Australian equity that I have followed for many years now, Genex Power LTD (GNX), appears on the database for year ends 2017, 2018, 2019 but not for 2016 and 2020. They built a stake in the business and then sold it. This isn't particularly interesting, except for the the fact that GNX at the time had a market cap ranging from  35-75 million USD, very much a microcap. During this time GNX owned a single 50MW solar farm in Outback North Queensland, and was trying to establish funding for its cornerstone project a pumped hydro power station. This speaks to how far NBIM is willing to travel to find investment opportunities and the diversity of investment holdings.

NBIM also records and makes public their voting instructions for shareholder meetings that it participates in. In its ownership history, NBIM voted in the 3 general meetings for GNX, 2 Annual General Meetings, and one special meeting before liquiditating its holding. Across those meetings NBIM voted for 17 of 21 of GNX's managments proposals and against 4. In its last general meeting it voted against 3/4 management proposals, including voting against the relection of two directors.

Some Norweigan investment analyst has researched and vouched for this company to be approved for a 1 million USD, 1.6% stake, the investment was approved by the investment board, and after a couple of year of underperformance, the fund made clear its grievence in its final AGM and liquidated its holdings. I find the idea that the fund is actively managing assets which are 1/1,400,000 of the funds AUM and the idea that it is doing this for over 9,000 equities really quite awesome. It supports the idea that NBIM is working in the best interests of the Norweigian people. GNX has made some impressive steps recently to become a more diversifed renewable energy generator and I will ensure to keep following whether NBIM reinvests in GNX and will take that as a strong vote confidence in the companies future.
