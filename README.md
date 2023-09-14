# bootcamp-planning
Versioned architectural planning for the Bank bootcamp project at NTT Data

# New Lima Bank Project
### Glossary
#### Account
A personalized registry for the clients of the bank, that contains information about itself regarding to monetary amounts, balances, and transactions.
#### Account Holder
A client that is linked to an account and has the authorization to request the bank to make changes to the account.
#### Bank User
A human person that works for the bank and has a user account in the internal electronic systems.
#### Client
Every person (legal or natural) that uses one or more of the bank services.
#### Regular client
A human person that uses one or more of the bank services and is identified with an id card and has an address in the country and has an account with the bank.
#### Corporate client
A legal person that uses one or more of the bank services, and is identified with a government issued identification number, has an address or representative office in the country, and has one or more human person representative and has an account with the bank.
#### Non-Account client
A regular or corporate client that uses only the loan services of the bank and does not have a passive account opened. Can be converted to regular or corporate client if later decides to open an account.
#### Savings Account
A passive account for the bank, that holds the savings of a regular client and pays interests but limits the amounts or frequency of withdrawals.
#### Checking Account
A passive account for the bank that holds money for a client. It’s a more liquid passive, with very little limitations for the holder of the account, but also pays very little interest rates.
#### Fixed-Term Savings account
A passive account for the bank, that is very little liquid. Transactions are limited but pays more interest rates for the holder.
#### Credit Card
A physical representation of an assets account that gives the client the ability to generate expenses paid for the bank, that will later be returned with an interest rate. It has a credit limit that depends on the sum of the balances of every account of the client. Issuing a credit card creates an asset account for the bank that increases its balance with every expense by the client, up to the credit limit. 
#### Loan Account
An asset account that is the counterparty of a loan. The client receives money (the amount is based on different criteria), and a loan account is created with the same amount, that will be reduced gradually with every monthly payment by the client.

### Account creation by type of client

|                           | Regular Client | Corporate Client | Non-Account Client   |
|---------------------------|:--------------:|:----------------:|:--------------------:|
|Savings Account            | **Yes** (one max.) | No               | No                   |
|Checking Account           | **Yes** (one max.) | **Yes** (Multiple)| No                   |
|Fixed-Term Savings Account	|**Yes** (Multiple)  | No               | No                   |
|Credit Card                | **Yes**            | **Yes**          | No                   |
|Loan                       | **Yes**            | **Yes**          | **Yes**              |

Every client (of any kind) can access the balance of his accounts, as well as the registry of transactions.


