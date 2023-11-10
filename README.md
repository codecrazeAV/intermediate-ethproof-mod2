# Front-end integration of deployed smart contract

This project is a simple integration of a smart contract deployed on a local host blockchain network with its front end. The front end is the web page on which users can interact with the smart contract built and deployed on a blockchain network.
## Description

In this project, I have built a smart contract with basic transaction functions like withdraw, deposit, and send functions.
And I integrated it with the front end. The user needs to deploy the smart contract on their local blockchain network.
After launching the front end, users can interact with the deployed smart contract from the web page and make all the transactions.
Users also need a metamask wallet to make transactions.

## Video Representation
https://drive.google.com/file/d/15XaIIE1rb_4QLJDFVfQdLSIxs8yNpXC0/view?usp=sharing

## Getting Started
download the zip file from the git repo, and extract it to your machine and open it on VS code.

### Installing
You can install all the dependencies you would need for implementing this project with the command 
```
npm i
```
Let the terminal where you have run this command be the terminal 1st

### Executing program
Now, open 2 more terminals. On 2nd terminal run the command 
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
This will launch the front end where you can interact with the smart contract.
## Help
For the project, you would need to have a metamask wallet extension on your web browser.
<br>
To interact with the deployed smart contract and make transactions on your local Ethereum network, you would need to
Configure it in the metamask wallet. Choose to add network, then click to add the network manually, then add the network.
to the configuration of your local Ethereum network. Make sure your network has the same RPC URL that appeared on the terminal.
when you executed the command "npx hardhat network"
<br>
if you encounter any error while interacting with the smart contract, just clear the transaction history on your Metamask wallet 
for the same wallet address in the same network and try again. 

## Authors
Anjan Gorai
