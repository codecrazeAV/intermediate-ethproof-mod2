# Front end integration of deployed smart contract

This project is a simple integration of smart contract deployed on local host blockchain network with it's front end. 
Here, front end is the web page on which users can interact with the smart contract built and deployed on a blockchain network.

## Description

In this project I have built a smat contract with basic transaction functions like withdraw, deposit and send functions. 
And integrated it with the front end. User need to deploy the smart contract on their local blockchain network. 
After launching the front end users can intereact with the deployed smart contract from the web page and make all the transactions.
Users also need metamask wallet to make transaction.

## Getting Started
download the zip file from the git repo and extract it to your machine.

### Installing
You can install all the dependencies you would need for implementing this project with the command 
```
npm i
```
Let the terminal where you have ran this command be terminal 1st

### Executing program
open 2 more terminals. In 2nd terminal run the command 
```
npx hardhat node
```
In the 1st terminal run 
```
npx hardhat run --network localhost scripts/deploy.js
```
on the third terminal run
```
npm run dev
```
## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)


## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
