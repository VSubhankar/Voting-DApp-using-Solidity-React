# Decentralized Voting Application
This is a small application to implement voting in solidity smart contract using ReactJS.

## Preview
Before voting --->
![image](https://github.com/VSubhankar/Voting-DApp-using-Solidity-React/assets/95838403/1d4f5348-6517-4169-8374-5677cd9840a3)

After Voting  --->

![image](https://github.com/VSubhankar/Voting-DApp-using-Solidity-React/assets/95838403/f7bb105f-0f14-4f5b-8544-716f1cd73a43)



## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Once you have pasted your private key and contract address in the .env file, simply run command

```shell
npm start
```
