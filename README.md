# Solidity-Final-Proof
This Project is "Create a Token" which signifies its use that it can be used to create a token in solidity language using state variables and then we can perform various operations on these token like minting and burning the token.
# Description
This Solidity Project having Smart Contract perform the operations:
Contract has Name,Abbreviation and total supply of the token.
Each Sender given his account address is mapped to his balance in account.
The Functionality of minting token which increases the total value as well as the balance of sender account by given value.
The Functionality of burning token which decreases total value and balance of sender by given value only when enough balance is present in senders account.
If you want to make a similar project you need to perform these operations:
Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
Your contract will have a mapping of addresses to balances (address => uint)
You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
Lastly, your burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.


# Getting Started
## Installing
To download the program simply click on the <> code button and then you will see the option to download it in zip file.if you want to use it for your project you can click on fork repository and it will be saved on your github for further modifications.
## Executing Program
To run the Program paste your downloaded file in RemixIDE.Then Compile the code and deploy it .after deployment add your account in the address section and value by which you want to increase the value in mint function and after clicking mint you will see your total supply will be increased by clicking on total supply.
Similarly you can perform the burn function for your token you can change the name of token ,abbrevation and total supply like
```
string public tokenname="YOUR TOKENNAME";
string public tokenabbrv="YOUR TOKENABV.";
string public totalsupply=Your total supply;
```
