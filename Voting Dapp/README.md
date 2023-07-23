# Voting Dapp

This is an overview of Voting Dapp on Shardeum.

![Image](https://iili.io/HL7p4CQ.png)

Here's the link for Deployment --> [Video Link](https://www.loom.com/share/1cb0bab1a2454708ac935c37c1dfad62?sid=03165bd4-fe1b-4397-808b-282db36a2a38)

## Tech Stack

- Solidity
- Hardhat
- Ethers.js
- React.js
- Web3.js
- Chakra UI

## How to run

1. Clone the repo

```shell
git clone https://github.com/SamarthSaxena10/Voting-Dapp-Shardeum.git
```

2. Install dependencies

```shell
npm install
```

3. In .env and add the values

```shell
PRIVATE_KEY=
```

4. Compile and Deploy the Contract

```shell
npx hardhat compile

npx hardhat run scripts/deploy.js --network sphinx
```

5. Paste the Deployed address in src/Constant/constant.js

```shell
const contractAddress = "";
```

6. Run the React App

```shell
npm start
```
