# CoffeeSupplyChain
This is a dapp to track a supply chain for coffee from farm to consumer
# Run Instructions
Installing
A step by step series of examples that tell you have to get a development env running

Clone this repository:

git clone https://github.com/udacity/nd1309/tree/master/course-5/project-6
Change directory to project-6 folder and install all requisite npm packages (as listed in package.json):

cd project-6
npm install
Launch Ganache:

ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
Your terminal should look something like this:

truffle test

In a separate terminal window, Compile smart contracts:

truffle compile
Your terminal should look something like this:

truffle test

This will create the smart contract artifacts in folder build\contracts.

Migrate smart contracts to the locally running blockchain, ganache-cli:

truffle migrate
Your terminal should look something like this:

truffle test

Test smart contracts:

truffle test
All 10 tests should pass.

truffle test

In a separate terminal window, launch the DApp:

npm run dev
