# ERC20 Token + DEX + FrontEnd Dapp (Web3.js)
==============================================

2 contracts:

One to implement a Token. The RIPP Token. ERC20 standard.

RIPPToken ContractId = 0x2A7A5d59a99D713E3813D70041db2c33714fa760  (live on BSC) 




One to implement an exchange (to buy or sell the RIPP token). This contract also creates and initilizes the RIPP Token. 

A simple exchange to swap 1 wei BNB/Ether for 1 RIPP token. 1 BNB / 1 Ether = 1,000,000,000,000,000,000 wei.

RIPPDEX ContractId = 0x2A7A5d59a99D713E3813D70041db2c33714fa760   (live on BSC)


Both contracts are written in Solidity, and included in Ripp.sol

So you just need to deploy only the RIPPDEX contract, since this will deploy the Ripp token contract. 

Initial token supply goes to DEX contract. 

I compiled and then deployed using Remix IDE. 

I have fully tested and deployed on BSC to take advantage of cheaper gas fees. The exact same code should also work on Ethereum chain. 


The web app is a simple HTML/CSS/Javascript. Its aim is to demonstarte the basics of a DAPP. No server side node.js required. No react or any other tools, just simple html/JS. All integrations with local metamask are done via front end web3 javascript. Just need a basic web server to host the html and javscript app is required. You need to only change the 2 contract addresses defined in the index.html, to reflect your own 2 contract addresses.


