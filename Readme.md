# Shardeum

Shardeum is an EVM-based L1 that uses dynamic state sharding to achieve linear scalability while retaining atomic composability across shards.

Shardeum can increase its TPS capacity with each validator added to the network to retain low fees forever.

You can watch this video below for more details about what Shardeumn is! :point_down:

[![What is Shardeum? A shirt Intro ](data:image/jpeg;base64,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)](https://youtu.be/97yFJYDF9x8 "What is Shardeum? - A Short Intro")  
What is Shardeum? - A Short Intro

## Documentation :open_book:
https://docs.shardeum.org/

## Deploying Dapps on Shardeum 👨🏻‍💻

Since Shardeum is EVM-compatible, all existing EVM tools will be compatible out of the box. You can also deploy smart contracts written in Solidity or Vyper and migrate existing contracts from other EVM-compatible chains without any code change.

[Adding Shardeum Network](https://docs.shardeum.org/network/endpoints)

> Note: Use Shardeum dappnet as it is specifically meant for the developers to test their dapps.

## Resources :books:

[Solidity Documentation](https://docs.soliditylang.org/en/v0.8.19/)   
[Truffle](https://docs.shardeum.org/smart-contracts/deploy/truffle)  
[Hardhat](https://docs.shardeum.org/smart-contracts/deploy/hardhat)  
[Foundry](https://docs.shardeum.org/smart-contracts/deploy/foundry)  
[Remix IDE](https://docs.shardeum.org/smart-contracts/deploy/remix)  
[Intro to Shardeum](https://www.youtube.com/watch?v=f7XzU7LiEOU)  
[How to Build a dapp on Shardeum](https://www.youtube.com/watch?v=eAHgMQtuC6g)  
[How to create dynamic NFTs](https://www.youtube.com/watch?v=XI6vn2RpSUA)  
[How to create a DAO](https://www.youtube.com/watch?v=u53tmckbtXk)

## Technical Blogs :scroll:
[Build an NFT Minter Dapp on Shardeum](https://shardeum.org/blog/build-an-nft-minter-dapp-on-shardeum/)  
[Build and Deploy an ERC20 Vault on Shardeum](https://shardeum.org/blog/build-and-deploy-an-erc20-vault-on-shardeum/)  
[SupraOracles Integration with Shardeum](https://shardeum.org/blog/supraoracles-integration-shardeum/)  
You can also check out more such technical tutorials on the [Shardeum Blog](https://shardeum.org/blog/category/shardeum-tutorials/).

## Tutorials :man_teacher:

### Storage :open_file_folder:
[EVM Storage](https://docs.shardeum.org/storage/storage-evm)  
[IPFS and Filecoin](https://docs.shardeum.org/storage/ipfs-and-filecoin)  
[Crust Network](https://docs.shardeum.org/storage/crust)  
[Lighthouse](https://docs.shardeum.org/storage/lighthouse)  
[Pinata](https://docs.shardeum.org/storage/pinata)
[Spheron](https://docs.shardeum.org/storage/spheron)