# Patagonian's Nft & Web3 Hackaton :rocket:

Welcome to the “ultilities & general info repository” for Patagonian’s dApps Hackaton. Here you can find a basic guide and resources to start with our challenge. Any architecture, design or technologies set are valid.

## Resources:

### Basic guide (here you can find how to interact with contract).

[Truffle-Suite-Guide](https://trufflesuite.com/guides/nft-marketplace/)

[Video-tutorial-sample](https://www.youtube.com/watch?v=ToA62ZpR0Ys&ab_channel=thirdweb)

## Requirements && recomendations

- lts node version (ethers library only supports lts. 18 is recommended).

- Any Javascript based front-end framework (we recommend Nextjs for the easy server/api integration).

- Ganache client installed locally.

- Truffle Console installed locally.

- Open ganache and load ```config/truffle-config.js``` folder in a new project.

- #### When your run: ``` $ truffle --version``` you should see something like this:

  - ```Truffle v5.7.3 (core: 5.7.3)```
  - ```Ganache v7.7.3```
  - ```Solidity - 0.8.17 (solc-js)```
  - ```Node v18.13.0```
  - ```Web3.js v1.8.1```

- Web Browser Metamask extension.

- ethers library installed in project (this is an adapter library used to interact with metamask and will make your development experiencie easier).

- @openzeppelin/contracts library installed in project (set of tools used for developing smart contracts).

- @metamask/providers library also installed in the project (optional).

- a metadata & image hosting for dApps (we recommend "pinata").

- Lastly, with truffle suite installed and ready for development, migrate the contract with: ``` $ truffle migrate```

### Optional:

- ethereum-abi-types-generator library. Tool to get types and interfaces for your contract. [Here](https://www.npmjs.com/package/ethereum-abi-types-generator/)

## Summary ###

### Contract:

- A base NFT contract with all features, ready to use.

### Config

- Configuration file needed for Ganache.

### Migrations

- ```$ truffle migrate``` will search for any migration under ```/migrations```. Next, the migration will load contract under ```/contracts```

### env.example

- Default Ganache's chain ID number and network ID number.

### General architecture guide (optional)

![Semantic description of image](/asset/basic-arch.drawio.png "Example")
