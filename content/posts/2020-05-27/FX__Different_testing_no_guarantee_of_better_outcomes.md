+++
categories = ["Cryptocurrency", "Blockchain", "SmartContract"]
date = "2020-05-27"
description = "FX: Different testing no guarantee of better outcomes"
tags = ["Cryptocurrency", "Blockchain", "SmartContract"]
title = "FX: Different testing no guarantee of better outcomes"
type = "post"
+++

{{<iframe id="large-banner" src="https://www.bounty.group/#slide=26.0" width="100%" height="600" scrolling="no" style="border: 0px solid rgb(216, 221, 230); border-radius: 3px;">}}

#  FX: Different testing no guarantee of better outcomes

COPYING AND DISTRIBUTING ARE PROHIBITED WITHOUT PERMISSION OF THE
PUBLISHER: [ SContreras@Euromoney.com][1]

By:  Paul Golden  Published on:  Friday, July 26, 2019

While the ability to run [simulation](https://www.fintechee.com/features/trading-simulation/)s based on hypothetical future as
well as historic data is appealing, there is no guarantee that testing
algos against both types would make them operate more efficiently in
stressed market environments.

Advanced [simulation](https://www.fintechee.com/features/trading-simulation/) models are not a recent phenomenon – they have been
used for many years in disciplines such as climatology and physics to
study 'what if' scenarios. But increased availability and affordability
of computing power have brought these techniques within the reach of
banks and other FX market participants.

![Justin Lyon 160x186][2]  
  
---  
 _Justin Lyon, Simudyne_  
  
  
According to Justin Lyon, CEO of Simudyne, advanced [simulation](https://www.fintechee.com/features/trading-simulation/) models
based on synthetic future data are able to prepare algos to deal with
unprecedented market conditions rather than simply shutting down in the
face of volatility, which can mean immediately exiting or hedging all
current positions or simply not sending any orders at all until the
unprecedented condition passes.

"Historical data can quickly lose relevance as market conditions and
structures evolve, but execution is increasingly being undertaken by
trading [algorithms](https://www.fintechee.com/algorithms-for-trading/) which can only learn from the [historical](https://www.fintechee.com/services/historical-data-for-forex/) data they
have been fed," he says. "Agent-based modelling and [simulation](https://www.fintechee.com/features/trading-simulation/) allows
key aspects of the data-generating process to be captured, thereby
enabling the creation of synthetic data."

Lyon reckons that testing algos against this data would improve market
participants' understanding of how their strategies could impact the
broader market.

 **

### The right data

**

Using [simulation](https://www.fintechee.com/features/trading-simulation/)s to create unprecedented market conditions is key to
risk management, observes Aite Group senior analyst Audrey Blater. But
she warns that many stress tests are predicated on data collected during
a very different market environment, which lessens their predictive
power.

Another potential issue with [historical](https://www.fintechee.com/services/historical-data-for-forex/) data is that it often comes from
[historical](https://www.fintechee.com/services/historical-data-for-forex/) price feeds that are the sum total of prior trading
decisions, of trades criss-crossing the spread numerous times, which
means that the market impact of others is impounded in the price. Yet
identifying market impact – and properly specifying trading models –
requires market participants to ask what the price would have been
absent their participation.

Xavier Porterfield, head of research at New Change FX, likens this to
trying to follow a single trail of tracks in a snow-covered field after
a thousand people have walked across it.

![Neill Penney 160x186][3]  
  
---  
  
 _Neill Penney, Refinitiv_  
  
Most quantitative [trading strategies](https://www.fintechee.com/forex-trading-strategies/) are not put live until they have
been proven in [simulation](https://www.fintechee.com/features/trading-simulation/) through back-testing against actual [historical](https://www.fintechee.com/services/historical-data-for-forex/)
data. While in the past such [simulation](https://www.fintechee.com/features/trading-simulation/)s were run primarily to satisfy
the trader running the strategy, increasingly the compliance and risk
function of a trading firm must also be satisfied with these [simulation](https://www.fintechee.com/features/trading-simulation/)s
before a strategy can go live.

Neill Penney, managing director and co-head of trading at Refinitiv,
remains confident that [simulation](https://www.fintechee.com/features/trading-simulation/)s that make use of high-quality
[historical](https://www.fintechee.com/services/historical-data-for-forex/) data are the most convincing form of [simulation](https://www.fintechee.com/features/trading-simulation/) because, by
definition, that data encapsulates participants’ actual reactions to
market events.

"Where [historical](https://www.fintechee.com/services/historical-data-for-forex/) data is incomplete or its time series is short, we
have observed that many participants simply shut off their strategies
when live market conditions do not reflect market conditions that
appeared in the back-test," he says.

The way in which back-test [simulation](https://www.fintechee.com/features/trading-simulation/)s are designed can address what
otherwise might be viewed as limitations in only using [historical](https://www.fintechee.com/services/historical-data-for-forex/) data.
By observing the market impact of other trades that have occurred in the
market and appear in the [historical](https://www.fintechee.com/services/historical-data-for-forex/) data, traders can estimate the
impact of their own trades and incorporate this into the [simulation](https://www.fintechee.com/features/trading-simulation/).

 **

### Modelling rules

**

Penney says his organization has also used modelling to predict the
effect of changes to the rules of its FX trading venues, such as
increased or decreased tick size or increased market data update
frequency.

"Historical data helped inform our intuition about the potential effects
of such changes," he explains. "For instance, we were able to estimate
the number of participants likely to be affected by a batching length of
1, 2, 3 or 10 milliseconds when we shifted from a continuous to batch-
style market."

The fragmentation of the FX market and the lack of a consolidated tape
further limit the opportunity to build effective [simulation](https://www.fintechee.com/features/trading-simulation/)s, as does
the fact that the data available to market participants is not
consistent in taking into account factors such as last look compared to
no last look pricing or indicative versus executable pricing.

Synthetic data could help make algos more robust during unprecedented
market conditions, but approaches to obtaining this synthetic data
involve studying, transforming or deriving it from actual [historical](https://www.fintechee.com/services/historical-data-for-forex/)
data, says Penney.

“It may be useful to modify [historical](https://www.fintechee.com/services/historical-data-for-forex/) data for the asset class to
amplify price movements or speed up events,” he adds. “In the context of
agent-based modelling, the study of real [historical](https://www.fintechee.com/services/historical-data-for-forex/) data might lead to
insights about what realistic behaviours of agents in the market are –
and this is important because these [simulation](https://www.fintechee.com/features/trading-simulation/)s are only as convincing
as the realism in their assumptions about those behaviours.”

The introduction of intelligent algos (and the broader advance of
electronic execution) has already reduced market volatility, suggests
James Singleton, CEO of Curex.

"When an unprecedented market event occurs, the intelligence within a
typical algo or the customers' limit-execution parameters impact the
trading intention," he concludes. "Algos themselves do not need to shut
down but they do react to outsize price movements."

  

   1. mailto:SContreras@Euromoney.com
   2. /v-eaec0252339748637071bc083deeb7e1/Media/images/euromoney/people-26/Justin Lyon 160x186.jpg
   3. /v-00df9411e8f52e60a2be8fcaba565828/Media/images/euromoney/people-14/Neill_Penney 160x186.jpg