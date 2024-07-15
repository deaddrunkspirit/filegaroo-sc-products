DEPRECATED

# Smart contract for Deals in Filegaroo

## Highload smartcontract for transactions

User send money to smart contract and send api request to validate transaction.

Smart contract factors:
1. User send valid amount of money with gas fees
2. API validated transaction and send external message to smart contract

After all factors met, the transaction is proccessed and money sent to user

Then SC service that listens to successful transactions notifies API that transaction is successful and sends message with product to customer.


Actors involved:
1. Smart Contract
2. Service that listens to smart contract
3. API that handles products
