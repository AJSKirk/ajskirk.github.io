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

\\\[P(n=k) = p^k\\\]

This gives the simple decision rule, to accept the bet if and only if

\\\[P(n=4) = p^4 <= .4\\\]

\\\[\\Rightarrow p <= \\sqrt\[4\]{.4}=.795\\\]

I didn't think that AlphaGo was good enough to win with an 80% probability in any given match, so I accepted the bet.

***

### Retrospective

I think my central idea (there are 32 possible ways this series plays out, and only one of them results in me losing the bet) was a good one, though I do think I was overconfident in taking the 2:3 odds. I initially thought Lee had a good chance of winning because he was simply so much better than any human that AlphaGo had played before, but the first game should have seriously tempered my assessment there. Lee seemed to lead for much of the first game, but ultimately did lose.

Ironically the main reason I seem to have won was that I was wrong to treat \\(p\\) as constant across all games. Lee won Game 4 by taking an uncharacteristically risky strategy, deliberately as a response to AlphaGo proving that it could eke out small advantages time and time again in cautious games. Lee learned how to counter AlphaGo quicker than I had anticipated.