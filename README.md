# ETHEREUM ERC-20 CRYPTO TOKEN (KASEICOIN)
![Kaseicoin](https://user-images.githubusercontent.com/86034323/142831784-c98e2661-61b2-457e-a6c2-f51d3dbf347f.png)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**DISCLAIMER:** This is just a college project based on hypothetical situation instructed to students to test their Blockchain Skills, hereby this Token doesn't contain any monetary value in any form. The content/code mentioned below is just for education purpose only & it's not a financial advice to consider this token to invest in any form or even to promote by any means.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**BACKGROUND:** After waiting for years and passing several tests, I have been selected by the Martian Aerospace Agency to be part of the first human colony on Mars. As a prominent Fintech Professional, I am chosen to lead a project to develop a Monetary System for the new Mars colony. I have decided to base this new monetary system on Blockchain Technology, and to define a new cryptocurrency called KaseiCoin. (“Kasei” means “Mars” in Japanese.)

KaseiCoin will be a fungible token that is ERC-20 compliant. I will launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

![mars image](https://user-images.githubusercontent.com/86034323/142826306-3374034e-a275-4538-97d6-94d67c8f71dd.png)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**CONTENT:**
- Project Description
- Technologies
- Ethereum Smart Contract - Features & Transactions
- Contributor
- License
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**PROJECT DESCRIPTION:**

KaseiCoin is an Ethereum based ERC-20 Token (Fungible Token) that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library. The crowdsale contract that I create will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KAS, or KaseiCoin tokens. 

Following are the high-level details of this project:

Version Used: Pragma Solidity 0.5.0
Smart Contracts compiled in Version: Pragma Solidity 0.5.5

1. Define a new Contract named **'KaseiCoin'** i.e. ERC20, ERC20Detailed & ERC20Mintable.
2. Define a new Contract named **'KaseiCoinCrowdSale'** i.e. CrowdSale & MintedCrowdSale.
3. Define a new Contract named **'KaseiCoinCrowdSaleDeployer'** with public addresses details.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**TECHNOLOGIES:**

- Remix IDE - (https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.7+commit.e28d00a7.js)
- Code Compiler Version: 0.5.5 (OpenZeppelin Solidity Library)
- OpenZeppeling Solidity Library - (https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/Crowdsale.sol, https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/emission/MintedCrowdsale.sol)
- Contract Deployment Environment: Injected Web3
- Language: Solidity
- Crypto Currency: Ether/Wei
- Local Blockchain: Ganache
- Wallet: Metamask

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**ETHEREUM SMART CONTRACTS (Environment: Remix IDE)**
----------------------------------------------------

**A. Following Smart Contracts are Defined, Compiled & Deployed:**

**1. Defined & Compile Contracts:** 

I. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoin" with few variables:

![Compiled KaseiCoin Contract](https://user-images.githubusercontent.com/86034323/142838401-15a9bdc9-a05a-47b2-909a-a68ec74f88ec.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

II. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoinCrowdSale" with few variables:

![Compiled KaseiCoinCrowdsale Contract](https://user-images.githubusercontent.com/86034323/142838636-4dc79422-f967-4e1a-8849-7bb3c9745f3b.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

III. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoinCrowdSaleDeployer" with few variables:

![Compiled KaseiCoinCrowdsaleDeployer Contract](https://user-images.githubusercontent.com/86034323/142838782-2e504053-b420-4217-b4e2-b94a639e83a1.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**2. Deploy Contracts:**

