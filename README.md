# Full-Stack Dapp

Requires node v16 (higher is not supported atm).

This project demonstrates how you can deploy a solidity smart contract to an Ethereum (test) network 

```
git clone git@github.com:krynv/full-stack-eth-dapp.git && npm i
```

Start `hardhat` using:
```
npx hardhat node
```

Deploy the solidity smart contract:
```
npx hardhat run scripts/deploy.js --network localhost
```

Start the front end app:
```
npm start
```
