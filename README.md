# BT1a2
Assignment 2
First of all i install web3.js library
![image](https://github.com/yyerensiz/BT1a2/assets/147133096/4fa34abb-6649-4c75-acf2-567a35a447de)
Then we creating variables and connecting our Ganache testing environment with this commands
  var Web3 = require('web3')
  var url = 'OUR URL OF GANACHE SERVER'
  var web3 = new Web3(url)
  var address = 'ADDRESS OF GANACHE ACCOUNT'
and with command below we can see account balance
  To see in WEI:
  web3.eth.getBalance(address, (err, bal) => {balance = bal})
  balance
  Then to see in ETH:
  web3.utils.fromWei(balance, 'ether')
In remix
![image](https://github.com/yyerensiz/BT1a2/assets/147133096/5d445071-9cb8-4335-b43f-aa82f778373a)
![image](https://github.com/yyerensiz/BT1a2/assets/147133096/168f5c43-0fa3-46bb-8777-c01f23fafebb)
![image](https://github.com/yyerensiz/BT1a2/assets/147133096/cf9dc123-5fe5-4ccc-ab99-9e9138a57f5e)

![image](https://github.com/yyerensiz/BT1a2/assets/147133096/f4685fa1-a970-4747-9241-bb67c2efae12)
![image](https://github.com/yyerensiz/BT1a2/assets/147133096/3a33dc00-e8da-4834-a838-2f8b37d65f0d)
