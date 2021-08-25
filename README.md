# ERC20 Token + DEX
==========================

2 contracts:

One to implement a Token. The RIPP Token. ERC20 standard.

RIPPToken ContractId = 0x2A7A5d59a99D713E3813D70041db2c33714fa760  (live on BSC) 







One to implement an exchange (to buy or sell the RIPP token). This contract also creates and initilizes the RIPP Token. 

A simple exchange to swap 1 wei BNB/Ether for 1 RIPP token. 1 BNB / 1 Ether = 1,000,000,000,000,000,000 wei.

RIPPDEX ContractId = 0x2A7A5d59a99D713E3813D70041db2c33714fa760   (live on BSC)






So you just need to deploy only the RIPPDEX contract, since this will deploy the Ripp token contract. 

Initial token supply goes to DEX contract. 

I have fully tested and deployed on BSC to take advantage of cheaper gas fees. The exact same code should also work on Ethereum chain. 

It was deployed using remix and fully tested in remix. 

The web app is a simple HTML/CSS/Javascript only way to show the basics of a DAPP. No server side node.js / ganache or test tools required. Just any web server to host the html and javscript. 


