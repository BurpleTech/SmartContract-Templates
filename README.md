# SmartContract-Templates
Open source Burple smart contract templates for anyone to use.

This is our contribution to our community, we will be releasing more in the future.

[Burple Website](https://burple.tech/)
---

# ERC721 NFT Token Contract :rocket:
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)

## Objective

Create a [ERC-721](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/) NFT smart contract and "Retrieve" a "Digital Asset" by its "Token ID".

The contract should cover the following functionality:

* Minting (Creation)
* Ownable
* Burnable
* Metadata Storage

## Initialize a development project in Remix IDE
1. Open [Remix IDE](https://remix.ethereum.org/) in Web Browser.
2. Create a ```Contract.sol``` file inside your Workspace.
3. Copy & Paste the code from [Burple_Contract-Templates](https://github.com/BurpleTech/SmartContract-Templates/blob/main/contract/ERC20TokenContract.sol) <img src="./images/Burple-Logo-Only-White.png" alt="Size Limit CLI" width="30"> public repo to your ```Contract.sol``` file. 

<p align="center">
  <img src="./images/ide_code_setup.jpg" alt="Size Limit CLI" width="738">
</p>

## Compile
- Solidity Compiler Plugin - Make sure, code compiles successfully without any errors.

<p align="center">
  <img src="./images/compile.jpg" alt="Size Limit CLI" width="180">
</p>

## Deploy using Ropsten Testnet
1. Deploy & Run Plugin - Select Injected Web3 Environment.
   1. Confirm, your Metamask wallet is connected. <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/MetaMask_Fox.svg/330px-MetaMask_Fox.svg.png" alt="Size Limit CLI" width="30">
2. Select ```POKEMON - Contract.sol``` from the Contract dropdown.

<p align="center">
  <img src="./images/deploy.jpg" alt="Size Limit CLI" width="180">
</p>

3. Click on the **Deploy** button.
4. Confirm the Contract Deployment Transaction. (Which will popup on your Metamask Wallet)


## Minting your NFT
1. Deployed Contract should look like below.

<p align="center">
  <img src="./images/contract_intr.jpg" alt="Size Limit CLI" width="180">
</p>

2. To Mint a NFT, ```safeMint``` function will be used.

<p align="center">
  <img src="./images/safe_mint.jpg" alt="Size Limit CLI" width="300">
</p>

3. Expand the ```safeMint``` and pass the To: Address (Wallet address), TokenId: Id, Uri: IPFS pinned metadata file link.

<p align="center">
  <img src="./images/safe_mint_input_clear.jpg" alt="Size Limit CLI" width="300">
</p>

4. Click Transact and Confirm the safeMint Transaction. (Which will popup on your Metamask Wallet)


## Verify your NFT on Ropsten Testnet
1. Open [Ropsten Etherscan](https://ropsten.etherscan.io/)
2. Search for the ```To:``` Address or https://ropsten.etherscan.io/address/[To:Address] replace TO:Address with wallet address.
3. Below Balance, Token dropdown will appear.
4. Click on the dropdown and you should see your POKEMON NFT Listed

<p align="center">
  <img src="./images/poke_tok.jpg" alt="Size Limit CLI" width="300">
</p>

Voila! You have deployed your ERC721 Smart Contract and Minted a NFT. :1st_place_medal:

# ERC20 Fungible Token Contract :rocket: :rocket:
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)

## Objective

Create a [ERC-20](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/) smart contract.

The contract should cover the following functionality:

* Minting (Creation)
* Ownable
* Burnable

## Initialize a development project in Remix IDE
1. Open [Remix IDE](https://remix.ethereum.org/) in Web Browser.
2. Create a ```Contract.sol``` file inside your Workspace.
3. Copy & Paste the code from [Burple_Contract-Templates](https://github.com/BurpleTech/SmartContract-Templates/blob/main/contract/ERC721TokenContract.sol) <img src="./images/Burple-Logo-Only-White.png" alt="Size Limit CLI" width="30"> public repo to your ```Contract.sol``` file. 

<p align="center">
  <img src="./images/ide_code_setup_20.jpg" alt="Size Limit CLI" width="738">
</p>

## Compile
- Solidity Compiler Plugin - Make sure, code compiles successfully without any errors.

<p align="center">
  <img src="./images/compile_20.jpg" alt="Size Limit CLI" width="180">
</p>

## Deploy using Ropsten Testnet
1. Deploy & Run Plugin - Select Injected Web3 Environment.
   1. Confirm, your Metamask wallet is connected. <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/MetaMask_Fox.svg/330px-MetaMask_Fox.svg.png" alt="Size Limit CLI" width="30">
2. Select ```TOKEN - Contract.sol``` from the Contract dropdown.

<p align="center">
  <img src="./images/deploy_20.jpg" alt="Size Limit CLI" width="180">
</p>

3. Click on the **Deploy** button.
4. Confirm the Contract Deployment Transaction. (Which will popup on your Metamask Wallet)


## Minting your NFT
1. Deployed Contract should look like below.

<p align="center">
  <img src="./images/contract_intr_20.jpg" alt="Size Limit CLI" width="180">
</p>

2. To Mint a Token, ```mint``` function will be used.

<p align="center">
  <img src="./images/safe_mint_20.jpg" alt="Size Limit CLI" width="300">
</p>

3. Expand the ```mint``` and pass the To: Address (Wallet address), Amount: Value (Amount in Decimals)

<p align="center">
  <img src="./images/safe_mint_input_clear_20.jpg" alt="Size Limit CLI" width="300">
</p>

4. Click Transact and Confirm the mint Transaction. (Which will popup on your Metamask Wallet)


## Verify your Fungible Token on Ropsten Testnet
1. Open [Ropsten Etherscan](https://ropsten.etherscan.io/)
2. Search for the ```To:``` Address or https://ropsten.etherscan.io/address/[To:Address] replace TO:Address with wallet address.
3. Below Balance, Token dropdown will appear.
4. Click on the dropdown and you should see your POKEMON NFT Listed

<p align="center">
  <img src="./images/token_tok.jpg" alt="Size Limit CLI" width="300">
</p>

Voila! You have deployed your ERC20 Smart Contract and Minted a Fungible Token. :1st_place_medal:
