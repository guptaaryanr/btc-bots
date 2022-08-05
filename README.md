# btc-bots

reason for using colab is that talib was not working properly on vs code
backtesting pending but working on a way to do it as it is very important to compare all models against the same historical trends over a longer period than just waiting for my computer to eventually crash from the overworking
comparison of all models is with live data currently against a buy and hold strategy
returns were better in all cases than this strategy and risk was reduced

buy and sell functions have been largely copied from another coder who had more success than my buggy mess

v1 uses aroon indicator as a trial with a decent reduction in risk but no large jump in return in most cases

v2 is a crazy idea from a friend who saw someone combine all indicators in talib for a different project so v2 is an average of every indicator in talib. saw a moderate increase in return from v1 and same reduction of risk as v1 in most cases

v3 uses a function from talib to analyze the engulfing pattern which helped reduce risk slightly more as it is by nature a more passive and less aggressive approach. return fell from v1 and v2 by a slight bit but i am guessing this is because of testing during a bad time for btc

v4 will be focused on a more intelligent approach on my part rather than flinging mud on the wall to see what sticks. i have learnt that combining moderately aggressive indicators intelligently works better in reducing risk. increasing return might be a different matter though

i eventually wish to have this actually start trading on the market rather than paper trading
