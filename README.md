# ContractExecutor
A smart contract user interface which allows you to run live smart contracts

This version is a simplified MVP that takes the smart contract ABI in the url params and is then able to manipulate
it using web3.js

Website url: https://xcontract.herokuapp.com/

Example url call for OpenRep contract: 

https://xcontract.herokuapp.com/api/[%7B"constant":false,"inputs":[%7B"name":"vendor","type":"address"%7D],"name":"trade","outputs":[],"payable":false,"type":"function"%7D,%7B"constant":false,"inputs":[%7B"name":"username","type":"string"%7D,%7B"name":"location","type":"string"%7D],"name":"addUser","outputs":[%7B"name":"","type":"string"%7D],"payable":false,"type":"function"%7D,%7B"constant":false,"inputs":[%7B"name":"vendor","type":"address"%7D,%7B"name":"isPositive","type":"bool"%7D,%7B"name":"message","type":"string"%7D],"name":"giveReputation","outputs":[],"payable":false,"type":"function"%7D,%7B"constant":false,"inputs":[%7B"name":"user","type":"address"%7D],"name":"viewReputation","outputs":[%7B"name":"","type":"uint256"%7D,%7B"name":"","type":"uint256"%7D,%7B"name":"","type":"uint256"%7D,%7B"name":"","type":"uint256"%7D,%7B"name":"","type":"uint256"%7D],"payable":false,"type":"function"%7D,%7B"payable":false,"type":"fallback"%7D,%7B"anonymous":false,"inputs":[%7B"indexed":true,"name":"user","type":"address"%7D,%7B"indexed":true,"name":"message","type":"string"%7D],"name":"_positiveReputation","type":"event"%7D,%7B"anonymous":false,"inputs":[%7B"indexed":true,"name":"user","type":"address"%7D,%7B"indexed":true,"name":"message","type":"string"%7D],"name":"_negativeReputation","type":"event"%7D,%7B"anonymous":false,"inputs":[%7B"indexed":true,"name":"username","type":"string"%7D,%7B"indexed":true,"name":"location","type":"string"%7D,%7B"indexed":true,"name":"user","type":"address"%7D],"name":"_addUser","type":"event"%7D,%7B"anonymous":false,"inputs":[%7B"indexed":true,"name":"vendor","type":"address"%7D,%7B"indexed":true,"name":"buyer","type":"address"%7D],"name":"_newTrade","type":"event"%7D,%7B"anonymous":false,"inputs":[%7B"indexed":true,"name":"user","type":"address"%7D,%7B"indexed":true,"name":"positive","type":"uint256"%7D,%7B"indexed":true,"name":"negative","type":"uint256"%7D,%7B"indexed":false,"name":"total","type":"uint256"%7D,%7B"indexed":false,"name":"burnedEth","type":"uint256"%7D,%7B"indexed":false,"name":"burnedCoins","type":"uint256"%7D],"name":"_viewedReputation","type":"event"%7D]/0x706af303364dc89a6b8dba265947442b05e84776


