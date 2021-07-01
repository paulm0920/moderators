# Gist
This proposal is a dApp that can run when TEA testnet ready. 

Some highlights:
- TEA core team offers reward in USDT and CML to both content creators and curators.
- Rewards issued for every epoch.(one or two weeks)
- TEA Core Team propose a topic or requirement guideline. Content creator create the content and post to his own social media. 
- Content creators commit the link to the dApp as a "candidate"
- Curators review the content. If he believe this content is the best he can stake their $T to this candidate and receive this candidate's tokens.
-  The conversion rate between the candidate's token and $T is based on a bonding curve
-  When an epoch ends, the top three candidates who receive highest candidate token win the three rewards. For example, 100 USDT. 
-  The reward is used to buy back all this candidate's token. For example, if there are 1000 token for this winner, every token worth 0.1 USDT. 
-  The staked $T and candidate token is burnt while the holder receives USDT reward based on how many candidate token he owns.
-  Beside the three rewards, there is another best content reward to one of the three candidates. TEA core team decide who is the winner based on their content. The winner will receive one CML team seed coupon. Worth $1000 in May 2021. 
-  Once the epoch ends, the Testnet may upgrade and possible reset. A new epoch restarts


## No air drops

Many blockchain projects use air drop to get initial community activity. I do not think that is a good idea because:
- The crowd doesn't care the project at all. Al they care is the free token.
- Since they do not care about the project. The only thing they can do once receive the token is going dump in the market
- Free air drop token hard to keep value

To fix this while get community activity when cold start, we can use this dApp. 

## Our Benefits:
- We reward content creators who did contribution to the community and for the project
- They can create content because they know the project
- Curators cannot make the content but they can still join the game by voting using their own $T.
- Curators share the reward too. This is the motivation to the curators.
- In order to join the game, you have to min $T first. So that they will need to learn how to use the TEA miner portal. Thus we can train a group of potential miners from this game.
- We can test the social feedback from the test bonding curve used in curator's market.

## Rewards to both content creators and curators
Content creators create content. They have chance to win the top reward **One CML seed**. He can also stake to the bonding curve at the lowest possible price since he is creator himself. 

Curators may not be able to create content, but they can stake their $T to "signal" which content is the best and most likely to win the top reward. They will win portion of the 100 USDT reward if their vote is correct.

If they did not win, nothing to lose. They can try again in the next epoch.

## Get potential users to try TEA

We will need to get people to try using our TEA miner's portal. The best way to invite people and motivate them to try is paying them. Due to the problem of air drops, we decide to use this game to motivate them. 

When they know how to mine the TEA in the testnet, they will likely join the real mining in the future when mainnet is ready.

Although the $T in the game is faked, but the USDT and CML are real.

## Improve UX during Testnet
We can get test data to improve our UX. We hope to know if the mining work flow and curator market with bonding curve actually works.

# User workflow
## Epoch starts
In the real mainnet, there won’t have a concept called epoch. Because there is no “reset” button in the real blockchain. however, during preview and test net, we probably will need to update the whole blockchain so that the old data have to be removed. Every time we remove the old data and start everything from the very beginning, we call it an Epoch Start.

Do not worry about all the token you mined during last epoch. Those money are not real money, you can just do it again from very beginning. All the real rewards, including USDT and CML will not be stored in the preview or test net. They are not lost.

So you can consider the epoch start is just a genesis block, just it may happen again and again.

# Technical design