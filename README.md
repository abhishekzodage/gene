# gene
open terminal-1 change directory to your folder(cd)
	1)geth

open another terminal-2 change directory to your folder(cd)
	1)geth --datadir=./chaindata init genesis.json
	2)geth --datadir=./chaindata
	3)geth attach
	4)eth.accounts
	5)personal.newAccount()
	6)eth.accounts
ITS enough uptil 6) point but if they ask for mining use below steps
	7)miner.setEtherbase(eth.accounts[0])
	8)miner.start(1)
	9)miner.stop(1)
