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

- Compile your smart contract

- Deploy the smart contract in the JavaScript VM

![alt text](https://github.com/


# Interact with your Deployed Smart Contract

The folowing screenshots demonstrates the Joint Savings contract being deployed and the corresponding functions being successfully exectued.

1. Use the "setAccounts" function to defined the authorized Etherreum address that will able to withdraw funds from your contract.

![alt text](https://github.com/










2. Test the "deposit" function of smart contract by sending the following amounts of ether. After each transaction, use the "contractBalance" function to verify that the funds were added to the contract: 

- Transaction 1: send 1 ether as wei:

![alt text](https://github.com/










- Transaction 1: send 10 ether as wei:

![alt text](https://github.com/











- Transaction 1: send 10 ether as wei:

![alt text](https://github.com/










3. Once you’ve successfully deposited funds into the smart contract, test the contract’s withdrawal functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo. After each transaction, use the "contractBalance" function to verify that the funds were withdrawn from thecontract. Also, use the "lastToWithdraw" and "lastWithdrawAmount" functions to verify that the address and amount were correct.


-Withdrawal 1: Withdraw 5 ether into accountOne:

![alt text](https://github.com/










- Withdrawal 2: Withdraw 10 ether into accountTwo:

![alt text](https://github.com/










# Technologies 

This project leverages Remix IDE to build and test smart contracts that are created in Solidity. Using the web version of Remix IDE, there is no need to install any software.

-Remix IDE - Open source application for developing, deploying, and administering smart contracts that run in Ethereum-based blockchains.

# Contributors

Khaing Thwe