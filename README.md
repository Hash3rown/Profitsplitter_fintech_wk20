SOLIDITY HOMEWORK - Profit Splitter:

This repository contains a .sol smart contract which can be used to evenly distribute deposits (ETH) to three different addresses simultaneously.

Simply deploy the contract (specifying the three addresses)

![deploy scrn](screenshots/Deploy.png)
****
Check your wallet balances:

![before](screenshots/Before.png)
****
Send a transaction (in this example we're sending 13 ETH):

![tx](screenshots/Deposit.png)
This will call the Deposit function (specifying an amount).

****

Approve the transaction with your browser wallet:

![approve](screenshots/ApproveMM.png)

****


The funds will be automatically divided and split evenly between the 3 addresses.

Check your balances again!

![after](screenshots/After.png)
****
You can view the transaction details by pasting the transaction hash into a block explorer:

![txGanache](screenshots/txGanache.png)

****
