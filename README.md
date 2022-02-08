# ETH-Tech-Marketplace

### Prerequisites
+ Node.js(npm) installed on your local machine
+ MetaMask Chrome extension installed in your browser
+ Ganache, you can download from [here](https://trufflesuite.com/ganache/)

### To run the project:
1. `git clone https://github.com/meetakbari/ETH-Tech-Marketplace.git`
2. `cd ETH-Tech-Marketplace`
3. `npm install`
4. `npm install -g yarn` 
5. `[sudo] yarn global add truffle@5.0.5` (due to some npm versioning issue with truffle, I have used truffle with yarn)
6. `npm start run`

### To compile the smart contracts 
+ `[sudo] yarn truffle compile`

### To test the smart contracts
+ `[sudo] yarn truffle test` 

### To deploy the smart contracts 
+ `[sudo] yarn truffle migrate`

### To open the truffle console
+ `[sudo] yarn truffle console`
