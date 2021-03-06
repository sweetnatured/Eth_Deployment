# Ethereum Rinkeby Test Network Deployment

This repository shows the deployment of a contract on ethereum rinkeby test network. Before deployment, simple test script tests smart contract's functions.


Dependicies
------
To install dependicy modules :

``` mark
npm install
```

Web3
---
The web3.js library is a collection of modules that contain functionality for the ethereum ecosystem. [link](https://web3js.readthedocs.io/en/v1.2.11/getting-started.html)

Infura
------

Infura provides the tools and infrastructure that allow developers to easily take their blockchain application from testing to scaled deployment - with simple, reliable access to Ethereum and IPFS. [link](https://infura.io/faq)

Ganache
-------
Ganache is a personal blockchain for rapid Ethereum and Corda distributed application development. You can use Ganache across the entire development cycle; enabling you to develop, deploy, and test your dApps in a safe and deterministic environment. [link](https://trufflesuite.com/docs/ganache/overview#:~:text=Ganache%20is%20a%20personal%20blockchain,flavors%3A%20a%20UI%20and%20CLI.)



Test
----
To test smart contract's message and setMessage functions :
``` mark
npm run test
```

Deployment
---------
To deploy the contract on rinkeby test network : 
``` mark
node deploy.js
```
#### Notice

To deploy the contract, you have to give your account's mnemonic's as parameter in _**`HDWalletProvider()`**_  function at deploy.js.
To see how open metamask account and add money please watch the [link](https://www.youtube.com/watch?v=Wk9W01KI4RU)


Validation
---------

To validate the deployment on the rinkeby network , let's visit the [rinkeby.etherscan](https://rinkeby.etherscan.io/) website and search by pasting the 
hash value of deployment adress.






