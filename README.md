# todoDAppp
A simple todo list dApp using ethereum blockchain smart contracts.

# commands
1. Init: truffle init
2. Compile: truffle compile
3. Migrate: truffle migrate

# truffle console commands
1. truffle console
2. get smart contract deployed instance: todoList = await TodoList.deployed()
3. get smart contract address: todoList.address
4. access public variable from smart contract: todoList.taskCount() // will return and store as BigNumber
5. access public variable and store in a local variable:
   1. taskCounts = await todoList.taskCount()
   2. taskCounts.toNumber()
6.
