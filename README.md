# Debug Starklotto

## 📌 Description
Sandbox repository for **Debugging and testing Starklotto**.  
Includes:

- Starknet contracts based on **Scaffold Starknet v1.0.12**
- Test setup compatible with **Starknet Foundry 0.46.0**
- Cairo 2.11.4
- Ready-to-use structure for development and debugging
- Potential frontend integration for contract interaction

> This repository is an isolated environment for experimenting without affecting the main production code.

---

## ⚙️ Requirements

- [Scarb 2.11.4](https://docs.swmansion.com/scarb/)
- [Starknet Foundry 0.46.0](https://github.com/Shard-Labs/starknet-foundry)
- Cairo 2.11.4
- Node.js >= 18 (for frontend)
- Yarn or npm (for frontend)
- Scaffold Starknet version 1.0.12

---

## 🛠️ Installation

1. Clone the repository:

```
git clone git@github.com:FutureMindsTeam/Debug_Starklotto.git
cd Debug_Starklotto
```

2. Install frontend dependencies
   
```
cd frontend
npm install
```
# or
```
yarn install
```

3. Install contract dependencies:
   
```
cd ../contracts
scarb build
```
