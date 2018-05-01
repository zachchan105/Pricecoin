Pricecoin integration/staging tree
================================

Copyright (c) 2009-2014 Bitcoin Developers

Copyright (c) 2011-2014 Litecoin Developers

Copyright (c) 2018 Pricecoin Developers

What is Pricecoin?
----------------

Pricecoin is an altcoin based off of the source code of Litecoin.

- Algo: Scrypt (POW 100%), no premine
- Symbol: PCN
- Block Time: 1 minute block targets
- Max Coin Supply: 1 million total coins
- Mining Reward: 10 (4/17/2018)
- Mature Block Confirmation: 5
- Reward Halving: 18,000 Blocks
- RPC Port: 2332

BitcoinTalk ANN:  https://bitcointalk.org/index.php?topic=3433872.new#new

Installing Pricecoin Wallet
-------------------

Windows
 - Navigate to Releases
 - Download the most recent Pricecoin EXE
 - Follow instruction

Mac
 - Navigate to Releases
 - Download the most recent Pricecoin EXE
 - Download Wine and Winebottler - http://winebottler.kronenberg.org/
 - Use Wine + Pricecoin Portable Binary to run on OSX
 
 *Development is in progress for both dedicated mobile and OSX Wallets*
 
 
Mining Pricecoin
-------------------

Pricecoin is built on the Scrypt algorithm. This means it can be mined with both
ASICs and GPUs. We are currently supported by a variety of pools. 




https://jgpool.jgalodesrvbox.ovh/ 


-a scrypt -o stratum+tcp://jgpool.jgalodesrvbox.ovh:3433 -u YOUR_WALLET_ADDRESS -p c=PCN



http://busypool.com/


-a scrypt -o stratum+tcp://busypool.com:3433 -u WALLET -p c=PCN



https://pool.cirserv.com/


-a scrypt -o stratum+tcp://pool.cirserv.com:3433 -u <WALLET_ADDRESS> -p c=PCN



We have a pre-configured CCMiner you can find here: 

https://github.com/zachchan105/Pricecoin/files/1952852/ccminer-x64-Pricecoin.zip

*Make sure to input your PCN address in the PricecoinMiner.cmd file*

Block Explorers
-------------------

Block Explorers allow the user to view data about Pricecoin's blockchain without having to download
the wallet program.
 
 https://pricecoin.jgalodesrvbox.ovh/
 
Exchanges
-------------------
 
 -https://biten.trade/
 
 
Development Process
-------------------

I love to program and plan to actively develop Pricecoin. This originally 
started as a challenge from my cousin after multiple discussions on cryptocurrency. Lots of late nights
and dedication is what makes this coin what it is today. 

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. 

Social Media
------------------

Discord: https://discord.gg/FZhvJAW

Twitter: https://twitter.com/PricecoinCrypto

Website: https://www.pricecoincrypto.com/

Instagram: https://www.instagram.com/pricecoincrypto/

About Me
-------------------

Zach Price:
https://docs.google.com/document/d/1zboqKraqDfI4GqIEllLYDlW83g78A93ZTUB7q4W2Euc/edit?usp=sharing

Pricecoin Contributors 
-------------------

Jason Metko / Chris Gunn / Jézékael Galodé / Jack Donat
