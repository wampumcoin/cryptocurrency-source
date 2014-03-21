WampumCoin

Scrypt Proof of Work

60 Second Block Targets

10 Block Difficulty Retargets

25 Billion Max Coins

Coin Distribution Breakdown:

	int64 nSubsidy = 3500 * COIN;
    if(nHeight < 11){nSubsidy = 50000000 * COIN;}
	else if(nHeight < 100000){nSubsidy = 150000 * COIN;}
	else if(nHeight < 200000){nSubsidy = 100000 * COIN;}
	else if(nHeight < 250000){nSubsidy = 75000 * COIN;}
	else if(nHeight < 300000){nSubsidy = 50000 * COIN;}
	else if(nHeight < 350000){nSubsidy = 30000 * COIN;}
	else if(nHeight < 375000){nSubsidy = 20000 * COIN;}
	else if(nHeight < 384400){nSubsidy = 10000 * COIN;}

Default RPC PORT 35885

Default P2P PORT 35883

%AppData%\WampumCoin\wampumcoin.conf

