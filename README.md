# NFT Contracts

[Solidity](https://soliditylang.org/) smart contracts for [NFTs](https://en.wikipedia.org/wiki/Non-fungible_token) used in [Mutant Kingdom](https://mutantkingdom.io/).

## Project setup

The project is build using [**brownie**](https://github.com/eth-brownie/brownie), you need to have [**python 3.6 or greater**](https://www.python.org/) installed to run the project, you also need [**Nodejs 6.11.5 or greater**](https://nodejs.org/en/) since brownie relies on [ganache-cli](https://www.npmjs.com/package/ganache-cli) to run a local blockchain. 

+ Make sure you have installed [python3.6+](https://www.python.org/) and Install [nodejs](https://nodejs.org/en/)
+ Install ganache cli-running `npm install -g ganache-cli`, check if the installation worked with `ganache-cli --version`
+ Go to the project folder and create a python virtual environment running `python3 -m venv .venv` 
+ Activate the virtual environment running `source .venv/bin/activate`
+ Install the project dependencies defined inside the `requirements.txt` running `python3 -m pip install -r requirements.txt`

_Done!! now you have a isolated python environment that can run the project_


Want to know why brownie for smart contract development ? _[**check this stackexchange answer**](https://ethereum.stackexchange.com/a/103176/63616)_
