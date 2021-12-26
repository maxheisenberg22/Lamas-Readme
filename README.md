# Lamas Finance - Jackpot Lottery

## Description

Jackpot Lottery is a chance-based game in which participants have the opportunity to win massive LMF rewards by buying lottery tickets. It is straightforward and equitable, and participants have no constraint to participate except being able to pay for the tickets.

The game happens on a daily basis. Every day, users can purchase lottery tickets at a scheduled period. Each ticket costs 5 LMF and is valid for that day only. There is no limit on the number of tickets that a user may buy. Each ticket sold adds to the size of the prize pool.

Each ticket allows the user to choose a set of 4 different numbers between 1 and 36. The more numbers matched, the larger the reward. The remainder of the prize pool of a day will be added up to the next day’s.

Jackpot Lottery uses Chainlink's VRF to ensure true and secure randomness.

## How to play

Step 1: Buy a ticket
Step 2: Choose the numbers
Step 3: Wait for the draw
Step 4: Check the result and claim the prize
Timeline
Every day, players may begin purchasing tickets at 11:00 UTC for a period of 30 minutes. Immediately after, the draw will take place.
Interface
For each ticket purchased, the player can pick a set of 4 numbers between 1 and 36. Players can select by themselves or let the system choose randomly.

Rewards
The jackpot is won when all four of the player's numbers match the jackpot number. If only two or three numbers are matched, the player will receive smaller rewards. The following ratios will be used to award the prizes:
50% of the pool will be distributed equally to players who have 4 numbers matched
20% of the pool will be distributed equally to players who have 3 numbers matched
10% of the pool will be distributed equally to players who have 2 numbers matched
As a result, the overall payoff for the owners of winning tickets (with two, three, or four matched numbers) accounts for 80% of the prize pool, with the remaining 20% reserved for the subsequent round. In the event that there are no winners on a given day, the remainder of the prize pool will also be added up to the next day’s.
Initially, there will be 30,000 LMF available in the prize pool before the first round of Jackpot Lottery. This amount of tokens is extracted from the Ecosystem pool (See Token Allocation in Section 5 for more detail).
In addition, players with at least 1 number matched will have a chance to receive an NFT piece. The rarity of the piece will depend on the number of numbers matched. More details about the NFT collection are available in Section 3.
Fee & tax
Participants must pay a negligible gas fee for the Solana network to participate in this game. For each transaction, this fee is 0.000005 SOL (approximately $0.001). 
Additionally, the winner is required to pay a small tax to the Lamas Finance system (in LMF), equal to 5% of the reward. This tax will be split into two parts: 50% goes to Lamas Treasury and the remaining 50% is burned.
In the future, the ratio of tax to be burned and tax to be given to the treasury will be modified by governance voting. Additionally, users participating in staking on Lamas Finance will receive a reduction of this tax. This will be described in further detail in Section 5.
