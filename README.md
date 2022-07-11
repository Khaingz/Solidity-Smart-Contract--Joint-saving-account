# Solidity-Smart-Contract-Joint-saving-account

Challenge20

# Description 

A fintech startup company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, I’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. My smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

# Instructions

The steps for this Challenge are divided into the following sections:

Step 1 - Create a Joint Savings Account Contract in Solidity

Step 2 - Compile and Deploy Your Contract in the JavaScript VM

Step 3 - Interact with Your Deployed Smart Contract (Adding interact screenshot in ReadMe "Execution_Results " File.)

# Compile and Deploy Your Contract in the JavaScript VM

- Compile smart contract, Deploy the smart contract in the JavaScript VM

### Successfully deployed joint saving contract screenshot

![alt text](https://github.com/Khaingz/Solidity-Smart-Contract--Joint-saving-account/blob/main/Execution_Results/Successfully%20deployed%20joint%20saving%20contract%20Screenshot.png)










# Interact with your Deployed Smart Contract

The folowing screenshots demonstrates the Joint Savings contract being deployed and the corresponding functions being successfully exectued.

1. Use the "setAccounts" function to defined the authorized Etherreum address that will able to withdraw funds from your contract.

### "setAccounts" function screenshot

![alt text](https://github.com/Khaingz/Solidity-Smart-Contract--Joint-saving-account/blob/main/Execution_Results/Set%20Account%20Screenshot.png)










2. Test the "deposit" function of smart contract by sending the following amounts of ether. After each transaction, use the "contractBalance" function to verify that the funds were added to the contract: 

### ContractBalance Transaction 1 - send 1 ether as wei screenshot

![alt text](https://github.com/Khaingz/Solidity-Smart-Contract--Joint-saving-account/blob/main/Execution_Results/ContractBalance%20Transaction%201-%20send%201%20ether%20as%20wei%20Screenshot.png)










### ContractBalance Transaction 2 - send 10 ether as wei screenshot

![alt text](https://github.com/Khaingz/Solidity-Smart-Contract--Joint-saving-account/blob/main/Execution_Results/contractBalance%20withdraw%202%20-%20Withdraw%2010%20ether%20into%20accountTwo%20screenshot%20with%20lastToWithdraw%20%26%20lastWithdrawAmount%20function.png)











### ContractBalance Transaction 3 - send 5 ether screenshot

![alt text](https://github.com/Khaingz/Solidity-Smart-Contract--Joint-saving-account/blob/main/Execution_Results/ContractBalance%20Transaction%203-%20send%205%20ether%20Screenshot.png)










3. Once you’ve successfully deposited funds into the smart contract, test the contract’s withdrawal functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo. After each transaction, use the "contractBalance" function to verify that the funds were withdrawn from thecontract. Also, use the "lastToWithdraw" and "lastWithdrawAmount" functions to verify that the address and amount were correct.


### ContractBalance withdraw transaction 1 - Withdraw 5 ether into accountOne screenshot, with "lastToWithdraw" & "lastWithdrawAmount" function

![alt text](https://github.com/Khaingz/Solidity-Smart-Contract--Joint-saving-account/blob/main/Execution_Results/contractBalance%20withdraw%201%20-%20Withdraw%205%20ether%20into%20accountOne%20screenshot%20with%20lastToWithdraw%20%26%20lastWithdrawAmount%20function.png)










### ContractBalance withdraw transaction 2 - Withdraw 10 ether into accountTwo screenshot, with "lastToWithdraw" & "lastWithdrawAmount" function

![alt text](https://github.com/Khaingz/Solidity-Smart-Contract--Joint-saving-account/blob/main/Execution_Results/contractBalance%20withdraw%202%20-%20Withdraw%2010%20ether%20into%20accountTwo%20screenshot%20with%20lastToWithdraw%20%26%20lastWithdrawAmount%20function.png)










# Technologies 

This project leverages Remix IDE to build and test smart contracts that are created in Solidity. Using the web version of Remix IDE, there is no need to install any software.

- Remix IDE - Open source application for developing, deploying, and administering smart contracts that run in Ethereum-based blockchains.

# Contributor

Khaing Thwe