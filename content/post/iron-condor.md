---
author: maddy
date: 2022-10-31T20:31:00+05:30
lastmod: 2023-04-15T10:10:53+05:30
title: Iron Condor 🦅
description: 
tags:
- Youtube📺
- Iron-Condor🦅 
- Option-Strategies🛠️ 
categories: 
- 🤹Options-Trading
draft: false
disableComments: false
---
# Iron Condor 🦅

- "Cheap", "Risk Capped", "Safe Neutral Strategy" for either Range bound market or Volatile market.

## Features 🌈
- Cheap
- Risk Capped on both sides.
- Awkward to adjust.
- Aka "Credit Spread".
- Combination of "Credit Put Spread" + "Credit Call Spread"
	- Short Iron Condor - Profit if Range Bound.
	- Long Iron Condor - Profit if Volatile.
- Delta Neutral
- Only One side is tested, Other side is not tested. Hence we can do adjustment on only one side.
- 

## Conditions ☝🏼

Do Iron Condor IF

1. IV > HV
2. 30+ IV Rank
3. Bearish Volatility
4. For any IV or Falling IV
5. For Weekly or Monthly Expiry. ( 60 Days )
6. Checkout [[9 Rules of Options - Sourabh Gandhi]]

## Remember 🤔

1. Medium Margin/Capital Requirement
2. Medium Risk
3. High Leverage
4. Capped Risk
5. Non Directional
6. Probability of Profit around 60%.
7. Check for liquidity.

## Step by Step Placement of Order 🪜

1. Select Strike Price as per Spot Nifty. ( 100 Pts Rule)
	1. Note Down Current Strike Price.
	2. Note Down X & Y
		- X = Price/Lot of Current Strike Price - 100 PE 
		- Y =  Price/Lot of Current Strike Price + 100 CE
    3. X + Y = Z, Round Off Z.
    4. Consider Z as Pts. 
	    - Subtract Z from PE
	    - Add Z to CE
    5. Note down 4 Orders & Price.
	    - ![](https://i.imgur.com/D4F4b2Q.png)
2. Make Scenario to know Risk Reward.
	- ![](https://i.imgur.com/DA48rEb.png)
3. Create Basket in Zerodha Kite
	- Note Down Margin.
	- Make sure Atlest 5% more than margin money available.
	- Note Down ( Expected Profit to exit) 4% * Margin to 5% * Margin.
	- Execute later.
4. Trade Execution
5. Book Profit ( Conservative Basis )
	- Important & Difficult
	- Don't Wait for Maximum profit.
	- 4% to 5% weekly profit wrt Margin Deployed.
	- Square off 4 trades simultaneously.

## Suggestions 🧙🏼‍♂️ 

- Monthly Iron condor is better than weekly Iron Condor position as the T+0 line is less steeper.
- T+0 less steeper, better position.
- T+0 line, dotted line, How position will behave today.
- Other line, how it will perform expiry.
- Monthly Iron Condor < Weekly Iron Condor
- Weekly have lot more negative gamma than monthly IC.

## How to take Monthly IC position using delta

![](https://i.imgur.com/SVLewUo.png)

1. Check Greeks on each Strike Price.
2. Positive delta value for call option.
3. Now determined Call Option, take other 3 positions.

![](https://i.imgur.com/tpFQ2T8.png)

#### eg: Calculations
[![](https://i.imgur.com/QGgfmpFm.png)](https://i.imgur.com/QGgfmpF.png)

#### eg: Chart
[![](https://i.imgur.com/SJlB0dGm.png)](https://i.imgur.com/SJlB0dG.png)

## Diagram 📈

 ![](https://i.imgur.com/eTsyDM1.png)


![](https://i.imgur.com/uHBsEFP.png)


![](https://i.imgur.com/k2HqgxN.png)


## Adjustment
### Adjustment 01
![](https://i.imgur.com/thdjbfw.png)
### Adjustment 02
- Convert Iron Condor to Iron Butterfly.
	- Leave one Loss making sell order. Square off the rest for profit.
	- Then make an Iron Butterfly. Remember you are already in profit.

### Iron Condor Backtest

![](https://i.imgur.com/G5rcLDI.png)

![](https://i.imgur.com/n6qXwCc.png)

- Gave around 38% for jun to sep 2022.
- Gave around 35% for jan to mar 2022.

---
🏷️Tags : #Investments💷/Options-Trading🎛️ 
📚Reference :
<iframe width="250" height="150" src="https://www.youtube.com/embed/mkSuGYcd7is" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>