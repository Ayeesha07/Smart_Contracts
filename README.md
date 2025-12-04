# Smart_Contracts
Deploy smart contracts using MetaMask and demonstrate interactions.

📌 Smart Contracts Included
Contract File	Purpose
SimpleStorage.sol	Demonstrates Set & Get operations on blockchain
Ownable.sol	Implements Ownership & Access Control using modifiers
SimpleToken.sol	A Simple ERC-20 like Token with transfers

All contracts were compiled & deployed using Remix IDE and executed via MetaMask.
📁 Location:
/contracts/

🔧 Tools & Technologies Used
Tool	Purpose
Solidity	Smart contract programming language
Remix IDE	Smart contract development & deployment
MetaMask	Wallet and blockchain transaction signing
Ganache / Sepolia	Ethereum network for deployment & testing
GitHub	Version control and documentation

🚀 Deployment Steps (Demonstration)
1️⃣ Open Remix IDE → Create Solidity Files
2️⃣ Compile using Solidity Compiler 0.8.x
3️⃣ Deployment via MetaMask

Environment: Injected Provider – MetaMask

Connect to Sepolia or Ganache
4️⃣ Confirm deployment transaction in MetaMask
5️⃣ Contract deployed successfully
6️⃣ Execute contract functions:

Read operations (free)

Write operations (require gas)

🧪 Execution Results
Contract	Demo
SimpleStorage	setNumber(10) → getNumber() returns 10
Ownable	onlyOwnerCanAccess() works only for deployer
SimpleToken	Token transferred from Account 1 → Account 2 successfully

All transaction logs confirmed in:
✔ MetaMask Activity
✔ Ganache UI / Sepolia Etherscan


Screenshots showing compilation and deployment:
📂 /screenshots/

File	Description
simple_storage_contract.jpeg
ownable_contract.jpeg	
simple_token_contract.jpeg	
