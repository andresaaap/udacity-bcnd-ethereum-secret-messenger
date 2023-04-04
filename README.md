# Ethereum Secret Messenger
## Udacity Blockchain Nanodegree

## Description

This software is a Dapp that creates messages in the ethereum rinkeby network

## Prerequisites
- Have a program like [webserver for chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb) to host the website locally
- Chrome
- Metamask

## Ganache environment

### How to install?

1. Download the project from this github repository

2. Start ganache

2. Deploy the contract to ganache using remix IDE

2. Set the contract address

![contract address](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/contract-address.png)

3. Set the account address that you are going to use

![account address](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/account-address.png)

### How to run?

1. Host the dapp locally with http-server. First, run `npm i`. Then, open the terminal and change directory to the project. Then, run this command to host the dapp `./node_modules/http-server/bin/http-server PATH_TO_YOUR_PROJECT`. Then, open in the browser http://127.0.0.1:8080

2. Log in metamask
3. Open the website in Chrome
4. Connect metamask to website:
![connect to metamask](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/metamask-connection-1.png)

![connect to metamask step 2](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/metamask-connection-2.png)

![connect to metamask step 3](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/metamask-connection-3.png)


5. Write the message

![dapp](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/UI.png)


6. Click on "set secret message"

![confirm transaction](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/confirm-transaction.png)

## Rinkeby environment

### How to install?

1. Download the project from this github repository

2. Connect to metamask (rinkeby) and make sure that it has funds for rinkeby

3. Compile the contract using remix IDE

4. Deploy the contract to rinkeby using remix IDE. Make sure that **Environment** is set to **Injected Web3**

![deploy](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/deploy.png)

![deploy confirm](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/deploy-confirm-metamask.png)

5. Set the contract address

![contract address](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/contract-address.png)

6. Set the account address that you are going to use

![account address](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/account-address.png)

### How to run?

1. Host the dapp locally with http-server. First, run `npm i`. Then, open the terminal and change directory to the project. Then, run this command to host the dapp `./node_modules/http-server/bin/http-server PATH_TO_YOUR_PROJECT`. Then, open in the browser http://127.0.0.1:8080

2. Log in metamask
3. Open the website in Chrome
4. Write the message

![dapp](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/UI.png)


5. Click on "set secret message"

![confirm transaction](https://github.com/andresaaap/udacity-bcnd-ethereum-secret-messenger/blob/master/img/confirm-transaction.png)
