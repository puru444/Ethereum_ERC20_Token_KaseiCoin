# ETHEREUM ERC-20 CRYPTO TOKEN (KASEICOIN)
![Kaseicoin](https://user-images.githubusercontent.com/86034323/142831784-c98e2661-61b2-457e-a6c2-f51d3dbf347f.png)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**DISCLAIMER:** This is just a college project based on hypothetical situation instructed to students to test their Blockchain Skills, hereby this Token doesn't contain any monetary value in any form. The content/code mentioned below is just for education purpose only & it's not a financial advice to consider this token to invest in any form or even to promote by any means.

Ether/Wei used in this project are FAKE Ether/Wei, in order to test the capabilities of this project I have used the replica of Ether in test instance. Therefore, please do not consider any of these ether as real ones.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**BACKGROUND:** After waiting for years and passing several tests, I have been selected by the Martian Aerospace Agency to be part of the first human colony on Mars. As a prominent Fintech Professional, I am chosen to lead a project to develop a Monetary System for the new Mars colony. I have decided to base this new monetary system on Blockchain Technology, and to define a new cryptocurrency called KaseiCoin. (“Kasei” means “Mars” in Japanese.)

KaseiCoin will be a fungible token that is ERC-20 compliant. I will launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

![mars image](https://user-images.githubusercontent.com/86034323/142826306-3374034e-a275-4538-97d6-94d67c8f71dd.png)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**CONTENT:**
- Project Description
- Technologies
- Ethereum Smart Contracts - Features & Transactions
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

**I. Following Smart Contracts are Defined, Compiled & Deployed:**

**1. Define & Compile Contracts:** 

A. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoin" with few variables:

![Compiled KaseiCoin Contract](https://user-images.githubusercontent.com/86034323/142838401-15a9bdc9-a05a-47b2-909a-a68ec74f88ec.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

B. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoinCrowdSale" with few variables:

![Compiled KaseiCoinCrowdsale Contract](https://user-images.githubusercontent.com/86034323/142838636-4dc79422-f967-4e1a-8849-7bb3c9745f3b.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

C. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoinCrowdSaleDeployer" with few variables:

![Compiled KaseiCoinCrowdsaleDeployer Contract](https://user-images.githubusercontent.com/86034323/142838782-2e504053-b420-4217-b4e2-b94a639e83a1.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**2. Deploy Contracts:**

A. In order to deploy the Contracts, 90 Ether were sent from Ganache (Personal Blockchain) to MetaMask (Wallet) to cover expenses:

![ganache_sent_eth](https://user-images.githubusercontent.com/86034323/142841440-4240fe1d-7190-4555-a70d-4637d31de583.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

B. KaseiCoin Contract Deployment under environment "Injected Web3":

![KaseiCoin Deployed_1](https://user-images.githubusercontent.com/86034323/142843183-c09f0bd9-5c03-4f62-ab07-29a4d06670bb.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

C. Transact The deployed contract "KaseiCoin" with: Name of the Coin: "KaseiCoin", Symbol: "KAS", Initial Supply: "100 Quintillion" (Conversion: 1 KAS = 1 ETHER). Metamask Wallet displays the Gas Fees and Total Amount spent in order to deploy this contract:

![KaseiCoin_Deployed_Confirmation_Step1](https://user-images.githubusercontent.com/86034323/142843604-6e21c741-24e4-449e-8486-b20d35a7f65c.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

D. Check the Metamask Wallet Balance i.e. reduced by the Gas Fees spent on Contract Deployment with details:

![KaseiCoin_Deployed_Confirmation_Step2](https://user-images.githubusercontent.com/86034323/142844764-6206c3bb-1df4-4902-af5a-1b75d2328579.png)

![KaseiCoin_Deployed_Confirmation_Step3](https://user-images.githubusercontent.com/86034323/142844794-35648698-9fbb-49e1-a272-747dd2d8b9d0.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

E. Verify the Transaction on Personal Blockchain (GANACHE) with details:

![KaseiCoin_Deployed_Confirmation_Step4](https://user-images.githubusercontent.com/86034323/142845349-bec288fd-6003-47ba-831a-ca10fb03eefb.png)

![KaseiCoin_Deployed_Confirmation_Step5](https://user-images.githubusercontent.com/86034323/142845393-f5b85ff1-2212-4f58-9940-071640c18628.png)

![KaseiCoin_Deployed_Confirmation_Step6](https://user-images.githubusercontent.com/86034323/142845426-732fc0d5-bbff-4a6a-a81e-beb9241de97a.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

F. 

