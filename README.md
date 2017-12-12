# **AltCoinWrapper**

AltCoinWrapper provides a simple to use GUI for diffrent Cryptocoin Miners out there..

# **What it does: In Detail**

*All requests are made using the API of the provided Miners*

**Startup:**
* On Startup it launches ccMiner to query for CUDA devices
* If it finds cuda Devices, it will set to correct values into the GUI, this is needed to query WhattoMine.com
	
**Start Button pressed:**
* Query Whattomine.com with the Data from your GUI ( Hardware Specific Request ! )
* The Data returned is a JSON. The JSON is used to get the most profitable coin to Mine
* If an Algo is found, which a Pool set for in the Config + a Wallet Adress is set in the config
* The Miner will start Mining

# **Supported Miners**
* ccminer Version: tpruvot @https://github.com/tpruvot/ccminer
 *excavator Version: Nicehash @https://github.com/nicehash/excavator

# Planned Miners
* ccMiner Version: KlausT
* ccMiner Version: Nanashi-Meiyo-Meijin
* I'm open for requests

# Supported Coins:
* ZEC
* VTC
* ZEN
* MONA
* ETH
* ETC
* VIVO;
* TZC
* ALTCOM
* BWK
* BTG
* I'm open for requests
		
# Default Pools. ( Can be Changed using the GUI )
**Some of them work really bad for me, so i'm also looking for more stable pools, if someone can suggest some, i'd be happy :)**
	
	ZEC 		eu1-zcash.flypool.net
	VTC 		vtc.poolmining.org
	ZEN 		zen.pool.sexy
	MONA 		lyra2v2.n-engine.com
	ETH 		eu1.ethermine.org
	ETC 		eu1-etc.ethermine.org
	VIVO 		altminer.net
	TZC 		altminer.net
	ALTCOM 		s.umine.org
	BWK 		s.umine.org
	BTG 		eu.pool.gold
	

# F.A.Q.	
**Does it contain Fees / Virus / Keyloggers or anything which is not stated above.**

*No.*

**Why is it written in Java.**

*Straight forward development, to finish the project fast, there is no need for the Wrapper to be fast, the work is done by the Miner executables itself*

*Easy to decompile, for those who want to have a look into the source / don't believe that there are no fees, or hidden actions performed ....*

**Supported OS**

*Windows 7,8,8.1,10 - Yes*

*Unix - Not Testst, for Sure the Executables in MinerBinarys/ needs to get exchange, then it might work.*

**Why don't you release the Source Code**

*I don't want to have "Fake" Wrappers released that contain harmful software, thats not what this project is about.*


# If you find this Tool useful, feel Free to contribute / donate !

	ALTCOM: AYQPHhecCSKwZRnnfGKgC1EQzBYitCP9bR
	BTG: 	GRUGUR8qMSVACXRWhLhi9VRkPfVN37yzFm
	BWK:	bby8Uo4nikEvD4ECe1bAGS9P1ZwFUz1DAG
	MONA:	MQEmYAtHbEsJASWAYSwb1r1RxzMVG1V7ox
	TZC:	TeUi6Qg4G2t9iHQB43kGp9DwwUpCSwsihy
	VIVO:	VY6MZbKEhYVnXfea9zxh45edUJaFWk4GxW
	VTC:	VuvmZYCqiEr3orxQyvmRjftii4wnuUex8W
	ZEC:	t1N8xF7ySepizF6MXLm7je3wZSBDB1rAzRQ
	ZEN:	zngjgwAeYbJFFeKBh9JNVR6qH3QB4CUrttC
	BTC:	1Mj9wvPE75J8qcVU3WXDBjpftpcejWRYMk
	ETC:	
	ETH:	