# martingale

The Martingale betting strategy is based on two fundamental rules. The first, is you must be betting in a game that has a win/loss rate that is close to 50/50. The second, is that whenever you win you put your savings somewhere where you can't touch them and when you lose you double your previous bet. That's all there is to it!

The way it "works" (the expected value is still negative but it can still provide positive returns) is that the probability that you lose a lot of money is very very low, however if you do hit that .0001% you will lose A LOT of money. The probability that you win small amounts is very high. This is why the expected value is negative even if the probability of winning is very high. 

The way this code works is you input the amount of money you are hoping to win (goal). Then you input the amount of money you are willing to lose (risk). The higher the "goal" the higher probability of losing the "risk" amount. The higher the "risk" amount, the more likely you are to hit your "goal" amount.

This Martingale model takes on two assumptions. The first is that the odds of winning are 18/38 or 47% (modeled after playing colors or even/odd in roulette). The second is that each bet is $10, which is common in casinos. 
