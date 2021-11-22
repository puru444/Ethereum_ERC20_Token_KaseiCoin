# ETHEREUM ERC-20 CRYPTO TOKEN (KASEICOIN)
![Kaseicoin](https://user-images.githubusercontent.com/86034323/142831784-c98e2661-61b2-457e-a6c2-f51d3dbf347f.png)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**DISCLAIMER:** This is just a college project based on hypothetical situation instructed to students to test their Blockchain Skills, hereby this Token doesn't contain any monetary value in any form. The content/code mentioned below is just for education purpose only & it's not a financial advice to consider this token to invest in any form or even to promote by any means.

Ether/Wei used in this project are FAKE, in order to test the capabilities of this project I have used the replica of Ether in test instance (Localhost). It is NOT a Mainnet network (production) therefore, please do not consider any of these ether as real ones.

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

**I. FOLLOWING SMART CONTRACTS ARE DEFINED, COMPILED & DEPLOYED:**

**1. DEFINE & COMPILE CONTRACTS:** 

A. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoin" with few variables:

![Compiled KaseiCoin Contract](https://user-images.githubusercontent.com/86034323/142838401-15a9bdc9-a05a-47b2-909a-a68ec74f88ec.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

B. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoinCrowdSale" with few variables:

![Compiled KaseiCoinCrowdsale Contract](https://user-images.githubusercontent.com/86034323/142838636-4dc79422-f967-4e1a-8849-7bb3c9745f3b.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

C. Under Version Pragma Solidity 0.5.5, the Contract defined as "KaseiCoinCrowdSaleDeployer" with few variables:

![Compiled KaseiCoinCrowdsaleDeployer Contract](https://user-images.githubusercontent.com/86034323/142838782-2e504053-b420-4217-b4e2-b94a639e83a1.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**2. CONNECT GANACHE-METAMASK WITH REMIX IDE:**

In order to deploy the Contracts, 90 Ether were sent from Ganache (Personal Blockchain) to MetaMask (Wallet) to cover expenses:

![ganache_sent_eth](https://user-images.githubusercontent.com/86034323/142841440-4240fe1d-7190-4555-a70d-4637d31de583.png)

![Metamask_Remix_Connection](https://user-images.githubusercontent.com/86034323/142849402-632b7da1-657b-424f-8b1f-1c5eecd10919.png)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3. DEPLOY CONTRACT "KaseiCoin":**

A. KaseiCoin Contract Deployment under environment "Injected Web3":

![KaseiCoin Deployed_1](https://user-images.githubusercontent.com/86034323/142843183-c09f0bd9-5c03-4f62-ab07-29a4d06670bb.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

B. Transact the deployed contract "KaseiCoin" with: Name of the Coin: "KaseiCoin", Symbol: "KAS", Initial Supply: "100 Quintillion" (Conversion: 1 KAS = 1 ETHER). Metamask Wallet displays the Gas Fees and Total Amount spent in order to deploy this contract:

![KaseiCoin_Deployed_Confirmation_Step1](https://user-images.githubusercontent.com/86034323/142843604-6e21c741-24e4-449e-8486-b20d35a7f65c.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

C. Check the Metamask Wallet Balance i.e. reduced by the Gas Fees spent on Contract Deployment with details:

![KaseiCoin_Deployed_Confirmation_Step2](https://user-images.githubusercontent.com/86034323/142844764-6206c3bb-1df4-4902-af5a-1b75d2328579.png)
![KaseiCoin_Deployed_Confirmation_Step3](https://user-images.githubusercontent.com/86034323/142844794-35648698-9fbb-49e1-a272-747dd2d8b9d0.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

D. Verify the Transaction on Personal Blockchain (GANACHE) with details:

![KaseiCoin_Deployed_Confirmation_Step4](https://user-images.githubusercontent.com/86034323/142845349-bec288fd-6003-47ba-831a-ca10fb03eefb.png)

![KaseiCoin_Deployed_Confirmation_Step5](https://user-images.githubusercontent.com/86034323/142845393-f5b85ff1-2212-4f58-9940-071640c18628.png)

![KaseiCoin_Deployed_Confirmation_Step6](https://user-images.githubusercontent.com/86034323/142845426-732fc0d5-bbff-4a6a-a81e-beb9241de97a.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**4. DEPLOY CONTRACT "KaseiCoinCrowdSaleDeployer":**

A. Quick check on the balance on-hand in Metamask Wallet and copy the Wallet Address in order to deploy the contract "KaseiCoinCrowdSaleDeployer":

![KaseiCoinCrowdSale_Deployed_Confirmation_Step1meta](https://user-images.githubusercontent.com/86034323/142847023-8a2e4f3e-ada6-47a0-89ad-5bc87fcd08f0.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

B. Deploy the CrowdSale Deployer contract: "KaseiCoinCrowdSaleDeployer" with: Name of the Coin: "KaseiCoin", Symbol: "KAS", Wallet Address: "0x27583414d38e0E595901369a7147611010F3F58c". Metamask Wallet displays the Estimated Gas Fees and Total Amount spent in order to deploy this contract:

![KaseiCoinCrowdSaleDeployed_confirmation_step1](https://user-images.githubusercontent.com/86034323/142847369-e0afdd16-16cc-4628-b199-2d214bab6954.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

C. Check the Metamask Wallet Balance i.e. reduced by the Gas Fees spent on Contract Deployment with details:

![KaseiCoinCrowdSaleDeployed_confirmation_step2](https://user-images.githubusercontent.com/86034323/142848418-2d6e6982-fcfd-4012-be9c-b854efd9f726.png)
![KaseiCoinCrowdSaleDeployed_confirmation_step3](https://user-images.githubusercontent.com/86034323/142848451-4076be65-cd60-4b29-b37e-ed579d9a9971.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

D. Verify the Transaction on Personal Blockchain (GANACHE) with details:

![KaseiCoinCrowdSaleDeployed_confirmation_step4](https://user-images.githubusercontent.com/86034323/142848582-e470a552-cd77-4d86-94b5-2779b5cb571f.png)

![KaseiCoinCrowdSaleDeployed_confirmation_step5](https://user-images.githubusercontent.com/86034323/142848603-b4e63733-d17f-4caf-bef4-b91de081d80f.png)

![KaseiCoinCrowdSaleDeployed_confirmation_step6](https://user-images.githubusercontent.com/86034323/142848627-873138f4-720b-47eb-a637-c547955709bd.png)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**5. DEPLOY CONTRACT "KaseiCoinCrowdSale":**

A. Deploy the CrowdSale contract: "KaseiCoinCrowdSale" with: Rate: "100", Wallet: "0x27583414d38e0E595901369a7147611010F3F58c", Token: "0x27583414d38e0E595901369a7147611010F3F58c". Metamask Wallet displays the Estimated Gas Fees and Total Amount spent in order to deploy this contract:

![KaseiCoin_CrowdSale_Confirmation_Step1](https://user-images.githubusercontent.com/86034323/142850645-d937c758-0b8f-4c05-8a4e-3234ac693551.png)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

B. Check the Metamask Wallet Balance i.e. reduced by the Gas Fees spent on Contract Deployment with details:

![KaseiCoin_CrowdSale_Confirmation_Step2](https://user-images.githubusercontent.com/86034323/142851202-2b14bf34-e954-46ed-b1c4-aeeb48f1ac45.png)
![KaseiCoin_CrowdSale_Confirmation_Step3](https://user-images.githubusercontent.com/86034323/142851220-349a96ea-7965-4d7a-8c15-a41824665c81.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

C. Verify the Transaction on Personal Blockchain (GANACHE) with details:

![KaseiCoin_CrowdSale_Confirmation_Step4](https://user-images.githubusercontent.com/86034323/142851351-df761181-67b9-4b2e-b7b3-6b64b6af7672.png)

![KaseiCoin_CrowdSale_Confirmation_Step5](https://user-images.githubusercontent.com/86034323/142851377-cac8a57f-9b6d-429f-a262-5604b9012fe1.png)

![KaseiCoin_CrowdSale_Confirmation_Step6](https://user-images.githubusercontent.com/86034323/142851397-dfd483a1-eaff-4d36-84b8-4bfddb71a5dd.png)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**6. MINT THE COINS "KAS":**

A. Mint the KaseiCoins "KAS" under wallet: "0x27583414d38e0E595901369a7147611010F3F58c" with the total amount: 10 Quintilllion Wei or 10 KAS. Metamask Wallet displays: The new account notification where these 10 KAS will be deposited with the Estimated Gas Fees and Total Amount spent in order to MINT these 10 KAS Coins:

![TRX_2_Step1](https://user-images.githubusercontent.com/86034323/142852495-e5a0104e-d2af-4392-a9a0-50cf1f0dc37f.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

B. Metamask Wallet has been updated with New Account Name to carry 10 KAS with remaining ETHER Balance & Transaction Details:

![TRX_2_Step2](https://user-images.githubusercontent.com/86034323/142853486-365d29ab-a7bb-4660-b020-8329466bb837.png)
![TRX_2_Step3](https://user-images.githubusercontent.com/86034323/142853502-5a04ecd4-b5a1-4c9e-8b0d-04e4246dd7ea.png)
![TRX_2_Step4](https://user-images.githubusercontent.com/86034323/142853515-eff897d0-9f1b-4ec8-8182-53ded65d9837.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

C. Verify the Transaction on Personal Blockchain (GANACHE) with details:

![TRX_2_Step5](https://user-images.githubusercontent.com/86034323/142853927-badbedba-8d4a-4373-b682-a2fff2c416bb.png)
![TRX_2_Step6](https://user-images.githubusercontent.com/86034323/142853945-43911123-6301-4ff0-b9ed-971fe8bfc4e2.png)
![TRX_2_Step7](https://user-images.githubusercontent.com/86034323/142853970-9f5eada6-8084-4e49-a2f1-ffc4e70da7a2.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

D. Total Supply of KAS: 10 (10 Quintillion)

![Mintecoins](https://user-images.githubusercontent.com/86034323/142855480-c868dc63-e609-4e4c-96b3-e135e404fe1f.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**7. VERIFY THE BALANCE OF 10 KAS:**

![TRX_3_step4](https://user-images.githubusercontent.com/86034323/142855671-d5176d9e-9acc-4763-b8d7-128b55b94510.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

A. Sent 1 KAS out of Account with remaining balance of 9 KAS in-hand:

![TRX_3_step6](https://user-images.githubusercontent.com/86034323/142855769-87d92e92-5c40-444b-bbd9-1f426787228a.png)
![TRX_3_step7](https://user-images.githubusercontent.com/86034323/142855841-6755f093-8a1b-48d5-9601-3f572a44dd1f.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**CONTRIBUTOR**

- PRATEEK SHARMA

www.linkedin.com/in/prateek-sharma-21a081180

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**LICENSE**

GNU General Public License v3.0

