# Voting Dapp

This is a Voting Dapp on Shardeum using Solidity and ReactJS.

[Video tutorial for code setup instructions](https://www.loom.com/share/1cb0bab1a2454708ac935c37c1dfad62?sid=03165bd4-fe1b-4397-808b-282db36a2a38)

## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract :

```shell
npx hardhat compile
```

and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat run scripts/deploy.js --network sphinx
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Once you have pasted your private key and contract address in the .env file, simply run command

```shell
npm start
```
