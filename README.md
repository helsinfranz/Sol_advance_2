# Sol_Advance_2

The following is a Anchor Framework program designed to perform Create, increment and decrement operations.

## Description

This is a smart contract implemented in Devnet using the Anchor framework. A client program is provided for testing and interacting with the smart contract.

## Getting Started

### Executing program

To run the program, please follow these steps:

`npm i`

and install yarn if getting error

**Build**

`anchor build`

**Deploy**

`anchor deploy`

Once you have completed the above steps,

you can interact with the contract using the following command:

`anchor test`

It will run the testing.ts file and then all the three functions will be called 
which will create the Counter account using program and then call the increment and decrement functions  which will also display the number in program logs.
