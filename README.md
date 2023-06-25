# Front end integration of deployed smart contract

This project is a simple integration of smart contract deployed on local host blockchain network with it's front end. 
Here, front end is the web page on which users can interact with the smart contract built and deployed on a blockchain network.

## Description

In this project I have built a smat contract with basic transaction functions like withdraw, deposit and send functions. 
And integrated it with the front end. User need to deploy the smart contract on their local blockchain network. 
After launching the front end users can intereact with the deployed smart contract from the web page and make all the transactions.
Users also need metamask wallet to make transaction.

## Getting Started
download the zip file from the git repo and extract it to your machine and open it on VS code.

### Installing
You can install all the dependencies you would need for implementing this project with the command 
```
npm i
```
Let the terminal where you have ran this command be terminal 1st

### Executing program
open 2 more terminals. On 2nd terminal run the command 
```
npx hardhat node
```
This will start a local Ethereum network on your machine.
On the 1st terminal run 
```
npx hardhat run --network localhost scripts/deploy.js
```
this will execute a script called deploy.js using the Hardhat development environment and the specified network configuration.
on the third terminal run
```
npm run dev
```
This wil launch the front end where you can interact with the smart contract.
## Help
For the project you would need to have metamask wallet extension on your web browsesr.
<br>
To interact with the deployed smart contract and make transactions on your local etheruem network, you would need to 
configer it into metamask wallet. Choose to add network, there click add network manually, then add the network 
to your configeration of your local etheruem network. Make sure your network has the same RPC url which appeared on the terminal 
when you executed the command "npx hardhat network"
<br>
if you encoounter any error during interacting with the smart contract, just clear transaction history on your metamask wallet 
for the same wallet address in the same network and try again. 

## Authors
Anjan Gorai
