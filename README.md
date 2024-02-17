# Introduction
Know Your Customer is a mandatory process for banks and financial institutions to verify the identity of their clients. Traditional KYC processes are centralized, creating a single point of failure that hackers can target, leading to privacy breaches and data theft. A decentralized system reduces the risk of data breaches by distributing data across a network, rather than storing it in a central database.




# Techonologies Used
frontend - ReactJS
backend - Ethereum Developement Network (Ganache), web3.js, truffle

# Steps to run the project
  1) Install the Ganache for Windows server from: 
  2) Start a new server on Ganache port 7545
  3) Install Metamask extension on Chrome
  4) Create a new network with port 7545 and chain ID 1337
  5) Use Ganache private key from one of the accounts created and import into metamask
  6) To run the project: <br />
    (i) Clone this repository <br />
    (ii) cd to client directory and run npm install <br />
    (iii) Run **truffle migrate --reset** <br />
    (iv) Run **npm start** <br />
    (v) Create account for a bank first for by switching to the Institution tab <br />
    (vi) Create customer account <br />
    (vii) If metamask doesn't pop-up automatically. connect with created account manually and approve all transactions
