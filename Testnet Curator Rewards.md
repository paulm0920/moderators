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
In the real mainnet, there won’t have a concept called epoch. Because there is no "reset" button in the real blockchain. however, during preview and test net, we probably will need to update the whole blockchain so that the old data have to be removed. Every time we remove the old data and start everything from the very beginning, we call it an Epoch Start.

Do not worry about all the token you mined during last epoch. Those money are not real money, you can just do it again from very beginning. All the real rewards, including USDT and CML will not be stored in the preview or test net. They are not lost.

So you can consider the epoch start is just a genesis block, just it may happen again and again.

## T token faucet
Because every transaction needs a certain amount of T token as gas fee. In the beginning of the preview net, there is no T token. In order to cold start, we will need to use faucet to generate some "free" test T token to start.

There must be some kind of constrain. if anyone can get unlimited free T test token, there won’t be any scarcity of T token. No one would like to mine T token using simulation mining. We will need to test the token economy, the scarcity is a must have. So we have to have some kind of constrain to the faucet.

### Faucet constrain
For any address, if there is no free faucet token were issued during last 10 blocks, one T token can be issued when user click the faucet button.

During preview net, new blocks are generated every 3 seconds. So every half minute, anyone can generate one T token. Since gas is very cheap, it would be enough for anyone to do a lot of transactions using one T token. In order to get more T token, user still need to mine using mining machine, or stake to other CML to gain dividends. For example, a regular minner can get one T token every 3 seconds. 

## No CML coupon faucet but investor waiting list
In the real Tea Project main-net, only early stage investors and core team members own CML coupon before the genesis block. So that when the main net starts, those coupons can be convert to CML seeds via a "lucky draw". 

In the preview net, we allow everyone to become an investor without any real cost. It is no CML coupon faucet but we provide a investor waiting list.

Before next epoch starts, anyone can go to our website fill in a [[preview investor form]]. Fill in your email address, TEA address, number of tokens (A/B/C no more than 5 in each category). When the new epoch starts, teaproject.org website will send email to everyone in the waiting list an notification. At the same time, the coupons are already in the genesis block under everyone’s TEA addresses.

Therefore, everyone who fill in the form can become a TEA investor, and own the genesis CML token. What they need to do is to go to the TEA portal and click "lucky draw" to convert their coupon to the CML seeds (frozen seeds sometimes) and start mining.

## Start mining

After the lucky draw, those investors own CML seeds. If any seed is defrost already, they can start mining by [[planting to a mining machine simulator]].

After mining started, the user can see the mining reward every few minutes. In preview net, we set the [[fast mode]] so that you can see the mining reward every 5 minutes. In the real main net it should be every day.

## Earn T token by staking

Besides running a mining machine yourself, you can stake seeds or T token to other CML’s staking slots to earn dividends. This is called staking.

Currently each staking slot costs $T 1000, or any defrost CML seed.

## Become a candidate
Let’s assume the competition is a blog post. Whoever write a blog post that meets the competition requirement can become a candidate.

Go to preview.teaproject.org/competition/candidate. fill in the form with the following fields:
- Url to your work. Anyone can click to evaluate your work
- Name it . An easy to remember name for your work
- Your token address to receive reward
- Memo, show to your supporters.

Once commit, you will receive an URL points to your proposal. This URL will be used by your supporters to vote for you.

## Become a supporter to vote
If you have T token, you like one of the candidate and believe he will win in this epoch’s competition, you can vote for him. If he wins, you will get reward too.

To vote, go to preview.teaproject.org/competition/vote
Select the one you like best from the list, click vote. input the amount of T token you would like to stake.

You can find the current voting situation on this page too. Including:
- How many T token has vote for each candidate
- How many reward-token has been mint for each candidate
- What’s the price of the next buy/sell reward-token based on the bonding curve
- Based on the current reward-token number, how many T token reward you are supposed to get if this candidate wins

## Get reward
When the result released, the candidate win the candidate reward (likely to be a real CML coupon for the main net), the supporters also share the supporter reward. Every reward token get one share. This reward is likely to be in USDT

## Epoch ends
Once the reward issued, the epoch is get to the end. The winner candidates and supporter win the reward in CML coupon and USDT. 

The epoch ends, and all TEA token or seeds in this epoch are expired when new epoch starts. 

Everything will restart from the every beginning. The different is the new epoch will be a new preview version. For example from preview11 to preview12 with software upgrade.

We will keep upgrade the preview epoch until we reach a stable version. Then we can start the main net.

# Additional rules explained
## Can I sell my reward token if I changed my mind?
Yes, you can. You buy the reward token from the bonding curve, you can also sell it back to the bonding curve. The result is that you will get T token from the bonding curve reservior at the **current sell** price. Note, it might be higher or lower than your **original purchase price**.  The reward token you returned back to the bonding curve is burn.

You can use the refund to buy reward token for other candidate if you want.

## When epoch ends, will I lost all my mined T token and CML?
Yes, but no worries, you can get them again as you did in this epoch once the next epoch starts.

## Will I lost my reward USDT or CML coupon?
No, you won’t lose them because they will be stored outside of the preview net. USDT will be in your ERC20 address as you provide when 

# Technical design