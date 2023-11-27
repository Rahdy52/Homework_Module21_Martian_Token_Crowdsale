# Unit 21: Martian Token Crowdsale

![alt=""](Images/application-image.png)

## Background

After waiting for years and passing several tests, the Martian Aerospace Agency selected you to become part of the first human colony on Mars. As a prominent fintech professional, they chose you to lead a project developing a monetary system for the new Mars colony. You decided to base this new system on blockchain technology and to define a new cryptocurrency named **KaseiCoin**. (Kasei means Mars in Japanese.)

KaseiCoin will be a fungible token that’s ERC-20 compliant. You’ll launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin. So let's roll.

## Evaluation Evidence

### Create the KaseiCoin Token Contract

This section is as explained in the class.

<img width="1218" alt="Create the KaseiCoin Token Contract" src="https://github.com/Rahdy52/Homework_Module21_Martian_Token_Crowdsale/assets/66510693/c24b8bc4-3d88-441e-accf-c795461e8645">


### Create the KaseiCoin Crowdsale Contract

Same as above.

<img width="1218" alt="Create the KaseiCoin Crowdsale Contract" src="https://github.com/Rahdy52/Homework_Module21_Martian_Token_Crowdsale/assets/66510693/8dd5a256-a881-4f99-ad74-84a34a7506bd">


### Create the KaseiCoin Deployer Contract

Same as above.

<img width="1218" alt="Create the KaseiCoin Deployer Contract" src="https://github.com/Rahdy52/Homework_Module21_Martian_Token_Crowdsale/assets/66510693/e4e2608b-2c90-4c12-a94a-0a18d761c2bd">


### Deploy and Test the Crowdsale on a Local Blockchain

To deploy the contracts, complete the following steps:
1. In the Remix IDE, navigate to the Deploy & Run Transactions pane, and then complete the following steps:
    ◦ Select an address from MetaMask to use to deploy the contracts.
    ◦ Copy the address to the clipboard.
    ◦ Select the KaseiCoinCrowdsaleDeployer contract, and then fill in the values for Name and Symbol. Paste the address from the clipboard into the Wallet box.
    ◦ Click transact, and when the MetaMask dialog box opens, confirm the transaction.
2. Navigate to the Deployed Contracts section, and then open the box that’s associated with the KaseiCoinCrowdsaleDeployer contract. Notice that buttons for KaseiCoin_crowdsale_address and KaseiCoin_token_address now appear.
3. Link the contract that’s associated with KaseiCoin_crowdsale_address to the KaseiCoinCrowdsale  contract previously created by completing the following steps:
    ◦ Copy the address that’s associated with KaseiCoin_crowdsale_address .
    ◦ Scroll up to the Contract box, and then select the compiled KaseiCoinCrowdsale.
    ◦ Copy the address into the At Address box.
    ◦ Click the At Address button.
4. Notice the deployed KaseiCoinCrowdsale contract in the Deployed Contracts section.

<img width="1218" alt="Test and Deploy in Local Blockchain" src="https://github.com/Rahdy52/Homework_Module21_Martian_Token_Crowdsale/assets/66510693/1218e7be-b6ce-4d68-87a9-8ba1ad58a0f6">

### Test the KaseiCoin_Token Crowdsale

Transact to buy KaseiCoin_Tokens

1. Buy KaseiCoin_Tokens from the crowdsale by completing the following steps:
    ◦ Select a new account from MetaMask. Notice the new account address in the Account box in the Remix IDE. Copy this account address to the clipboard.
    ◦ In the Value box, enter a value of wei to determine the number of tokens for this account to buy.
    ◦ Navigate to the deployed KaseiCoinCrowdsale contract, paste the address into the buyTokens box, and then click the buyTokens button.
    ◦ When the MetaMask dialog box opens, click Confirm.
    ◦ Confirm that the number of bought tokens is correctly reflected in Remix by clicking the totalSupply button.
2. Repeat the purchase process by using a third MetaMask address. Confirm that the total supply of tokens is correctly reflected in Remix by clicking the totalSupply button.

<img width="1218" alt="Screenshot 2023-11-26 at 1 19 30 pm" src="https://github.com/Rahdy52/Homework_Module21_Martian_Token_Crowdsale/assets/66510693/1f2d4b72-8cdc-45e7-bd13-d6de5847d3a2">


<img width="1218" alt="Screenshot 2023-11-26 at 1 22 28 pm" src="https://github.com/Rahdy52/Homework_Module21_Martian_Token_Crowdsale/assets/66510693/83a0aad6-148e-4da0-a08f-af2c150ce231">


<img width="1229" alt="Screenshot 2023-11-26 at 11 51 08 pm" src="https://github.com/Rahdy52/Homework_Module21_Martian_Token_Crowdsale/assets/66510693/8e029276-4ec5-4b3c-afc2-d016e1df4c92">

<img width="1199" alt="Screenshot 2023-11-26 at 11 49 35 pm" src="https://github.com/Rahdy52/Homework_Module21_Martian_Token_Crowdsale/assets/66510693/c9ca4c71-3a6f-41ad-b18a-87f2c972f39a">


