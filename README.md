# Smart Contracts Deployment Activity

Deploy smart contracts using MetaMask and demonstrate interactions.

---

## 📌 Smart Contracts Included

| Contract File | Purpose |
|--------------|---------|
| `SimpleStorage.sol` | Demonstrates Set & Get operations on blockchain |
| `Ownable.sol` | Implements Ownership & Access Control using modifiers |
| `SimpleToken.sol` | A Simple ERC-20 like Token with transfer support |

📁 Location: `contracts/`

---

## 🔧 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Solidity | Smart contract programming language |
| Remix IDE | Contract development & deployment |
| MetaMask | Wallet & transaction confirmation |
| Ganache / Sepolia | Blockchain network for testing |
| GitHub | Version control & documentation |

---

## 🚀 Deployment Steps (Demonstration)

1️⃣ Open **Remix IDE** → Create Solidity contract files  
2️⃣ **Compile** using Solidity Compiler `0.8.x`  
3️⃣ Deployment using **MetaMask**  
   - Environment: *Injected Provider – MetaMask*  
4️⃣ Connect to **Sepolia** or **Ganache**  
5️⃣ Confirm deployment in MetaMask  
6️⃣ Execute smart contract functions

✔ Read operations are free  
✔ Write operations require gas (MetaMask confirmation)

---

## 🧪 Execution Results

| Contract | Demo Output |
|---------|-------------|
| SimpleStorage | `setNumber(10)` → `getNumber()` returns **10** |
| Ownable | `onlyOwnerCanAccess()` works only for deployer |
| SimpleToken | Tokens successfully transferred from Account 1 → Account 2 |

⛓ All transactions confirmed using:
- MetaMask Activity
- Ganache UI / Sepolia Etherscan

---

## 📸 Screenshots

Screenshots showing compilation and deployment:

📂 Folder: `screenshots/`

| File Name | Description |
|----------|-------------|
| `simple_storage_contract.jpg` | Smart contract code |
| `ownable_contract.jpg` | Smart contract code |
| `simple_token_contract.jpg` | Smart contract code |

