# PlayBook
Execution Criteria For Various setups. I will include the .py files for each  setup.
1: Codename: "Ol' Faithful"


Codename: O’l Faithful… this one does not effectively capture v-shaped recoveries in event that  the highs of large down candles eclipse close of price for the first 5 bullish candles despite price closing above highs of prior 3 candles. Additionally let’s acknowledge that three minute time frame intervals leave out quicker paced micro trends. Which may develop faster, yet have less probability of follow-through which are where the bulk of the outsized gains will likely come from.
Bullish Scenario Setup

***figure out how to code this:
FOLLOWING [if true statement] a “sell-off” occurs.
Def selloff  = if price decreases  x%   within __x___time frame, AND x% of the prior Xmany candles close at a price lower than they opened.
or
Def accumulation zone = if price ATR is under x percentage of its price or some variation measuring volatility contraction} AND x% of the prior Xmany candles close lower than they opened.
#Both of these are conditions which may trigger a series of following checks prior to triggering a buy signal.
#note the second smaller leg down of the selloff seems to be a good spot to hop in. identifiable in the volume signature with one higher volume candle with large downward price action followed by a second large volume signature of the final push downward to trigger sell side stops to be triggered. It is here one should look at price direction, it is most often here that an inflection from sell-side to buy-side pressure may occur, with the result being higher quoted price.
#Idea: Identification of consolidation/ tightening bid-ask spread at key zone to be identified as Variable: {inflection point} Volume Parameter?
Current candle = (n1) = {close price of most recent candle.} defined by 3m TF
Entry: If closing Price(n1) exceeds ALL the closing prices of the prior three candles (n-2),(n-3),(n-4) AND the HIGHS of the prior five candles,(n2),(n3),(n4)(n5) (n6) then Enter.
Exit/close: If the  close price of ALL the prior three candle’s(n1),(n2) & (n3) exceed,(>) LIVE current price(n0),  AND current price(n0) is below lows of the prior 5 candles(n2)(n3)(n4)(n5)(n6). 
**identification of Confirmation*?*?
***ict bullish breaker where there is a liquidity grab” ** identified as price going below prior lows in the last X many bars following a selloff as defined prior. This is the final leg down” so to speak. The final grab on liquidity ( large amount of volume on a down candle post the larger prior down candle with larger volume.) {less volume yet price goes lower and then snaps back to prices above the larger volume candle’s close.
##test the difference between 4 and 5 period aggregation.
##test for different times of day/ week/month.
See which hours, days, weeks, perform best based on this criteria. :for underlying and options too. Can iterate for multiple strike lines.
#ATR & VWAP too bollinger bands, MACD divergence… idek we’re getting excessive kere
**I think TTM includes many of these in it’s display of bar coloring and zero line.
Stats to compute prior to any capital allocation:
 Run monte carlo sim:
“Ol’ Faithful” Testing:
Need to define averages: ( Avg win %), (Avg loss%)
In even of win,  average %return.
In even of loss average %drawdown.
Win: X% return is generated
Loss: x% loss or greater is generated
A “win” or “hit” will be identified by unrealized gains reaching/coming within 1% of a certain %return threshold measured in R-Multiples: (Returns generated in relation to max potential drawdown before position auto terminates with market order to close.)
Hence a loss should theoretically always be about the same size, however a win is measured in multiples of that max drawdown(MD) thus MD = 1.  Ex: 1.6R :Meaning the return generated was 1.6x that of whatever amount could have potentially been lost.
Variables defined:
Capital allocated = CA         ### %of portfolio dedicated to specific entry thesis: oc
Max draw;down = MD           ## expressed as an integer( 0 to 1)
Risk: (CA(MD)) = R              ## relevant in case of losing scenarios

Kelly Criterion & optimal bet sizing: Kelly inputs
https://quantpedia.com/beware-of-excessive-leverage-introduction-to-kelly-and-optimal-f/
https://www.youtube.com/watch?v=DZdZ9pIvlTE&ab_channel=Quantpedia
Probability of success, hit rate:
Odds: RR assessment 

#note: Current Price: Defined as the midpoint between the bid-ask spread. quote


Add size:
If  position is above x% profit maybe say 5-15% then add x% upon cross of zero line into positive territory on ttm upon the close of a candle above previous highs: essentially if candle closes into  Lblue above zero then add x% to pos otherwise no action.
#test for this number


Remove size:
 If  position is down x% maybe say 5-15 then reduce by x% upon cross of zero line into negative territory on ttm upon the close of a candle below previous lows: essentially if candle closes red below zero then reduce pos by x% otherwise no action.



Bearish Scenario Setup






















 
Thought: Now how would the data change if the closing values of prior 3  candles was aggregated, (ex: average price, Volume weighted Average Price, .
Now weight this based on…

1: need source of income 2: need lender 3:thought out gameplan, backtests an stats Pitchdeck.
Need1: high probability for parked $ in MSTR Shares outright.. Longterm dated MSTR Calls. This means we have high exposure to BOTH Delta & Theta.
Strategy to offset this while still not locking up working capital…

Identification of Consolidation: ATR, imp vol measurement current state ranked asa percentile of prior  avg 30 trading days.
Measure of range expansion velocity?

