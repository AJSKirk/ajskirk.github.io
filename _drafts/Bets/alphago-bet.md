---
layout: post
title: AlphaGo Bet

---
### Summary

On the 9th of March 2016 I bet against [Daniel Filan](http://danielfilan.com/) that AlphaGo would lose at least one game of its five-game series against Lee Sedol. I bet 100 AUD at 2:3 odds, which corresponds to me thinking I had at least a \\(0.6\\) probability of winning.

Status: **Won**

***

### Reasoning

I made the bet shortly after the first game, which AlphaGo lost. This means that in order for me to lose the bet, AlphaGo needed to win all remaining four games. In order for it to have been a good bet, the probability of this happening needed to be less than \\(0.4\\).

Let \\(p\\) be the probability of AlphaGo winning any given game, and let \\(n\\) be the number of games won by AlphaGo. For simplicity's sake, assume that this \\(p\\) is constant across all games in the series (that is to say, Lee Sedol does not learn any weaknesses of AlphaGo after a few games, nor does he become rattled and play worse). The probability of a probability \\(p\\) event occurring in \\(k\\) out of \\(k\\) trials is given by a particularly simple case of the [binomial distribution](http://mathworld.wolfram.com/BinomialDistribution.html)

$$P(n=k) = p^k$$