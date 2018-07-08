# Etherium

## What is it?
Etherium is a way to do smart contracts.  A contract consists of the following:

* none - how many times the sender has sent a transaction
* to - address of the account the money is going to, if to is black, this is a new contract
* data - compiled bytocode for th contract [only present during contract creation]
* value - amount of wei to send to the to address [initial amount of ether can be assigned at creation]
* gasPrice - amount of wei sender is willing to pay per unit gas to get transaction processed. Wei / unit of gas
  * Each operation like add or divide costs some amount of gas, which gets * by gasPrice to get cost of computation
* gasLimit - units of gas that this transaction can consume, total amount we are willing to spend.
* v, r, s - cryptographic pieces of data that can be used to generate senders account address

## What is block chain?

Great intro site: https://anders.com/blockchain/block.html

## How does it work?

Etherium Rules:
* Any time we want to change anything on the blockchain we need to submit a transaction.

Two ways to execute a function in the blockchain:
* Function that changes data - sending a transaction, can modify contract data, takes time, returns a transaction hash, costs money!
* Function that does not change data - calling the function, can return data, runs instantly, free to do!

Units of measurement:
* 1 Ether = 1,000,000,000,000,000,000 Wei
* There is no fractional Wei

## Contract Hash 
0x36204b6Aa7506b08EB0E4F50881126e44aa63c24


