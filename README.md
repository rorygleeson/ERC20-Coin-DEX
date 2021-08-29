# ERC20 Token + DEX + FrontEnd Dapp (Web3.js) + MetaMask


# 2 contracts


One to implement a Token. The YODA Token. ERC20 standard.
YODAToken ContractId = 0x809F244aFcbFB1435FF9e4b4EC00A758f4C4b8Ab  (live on BSC) 




One to implement an exchange (to buy or sell the YODA token). This contract also creates and initilizes the YODA Token. 
A simple exchange to swap 1 wei BNB/Ether for 1 YODA token. 1 BNB / 1 Ether = 1,000,000,000,000,000,000 wei.
YODADEX ContractId = 0x201f130dF701c6693CF7c47B784ef1A06c696f99   (live on BSC)


Both contracts are written in Solidity, and included in YODA.sol

So you just need to deploy only the YODADEX contract, since this will deploy the YODA token contract. 

Initial token supply goes to YODADEX contract. 

I compiled and then deployed using Remix IDE. 

I have fully tested and deployed on BSC to take advantage of cheaper gas fees. The exact same code should also work on Ethereum chain. 

# HTML/JS DAPP 
The web app is a simple HTML/CSS/Javascript. Its aim is to demonstarte the basics of a DAPP. No server side node.js required. No react or any other tools, just simple HTML/JS. 
All integrations with local metamask are done via front end web3 javascript. Just need a basic web server to host the index.html page. You need to only change the 2 contract addresses defined in the index.html, to reflect your own 2 contract addresses.


