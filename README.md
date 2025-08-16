# Debug_Starklotto

## 📌 Description
Sandbox repository for **Debugging and testing Starklotto**.  
Includes:

- Starknet contracts (Cairo 2.11.4)
- Test setup with **Starknet Foundry 0.46.0**
- Ready-to-use structure for development and debugging
- Potential frontend integration for contract interaction

> This repository was created as an isolated environment for experimenting without affecting the production logic.

---

## ⚙️ Requirements

- [Scarb 2.11.4](https://docs.swmansion.com/scarb/)
- [Starknet Foundry 0.46.0](https://github.com/Shard-Labs/starknet-foundry)
- Cairo 2.11.4
- Node.js >= 18 (for frontend)
- Yarn or npm (for frontend)

---

## 🛠️ Installation

1. Clone the repository:

```
git clone git@github.com:FutureMindsTeam/Debug_Starklotto.git
cd Debug_Starklotto
```

2. Install frontend dependencies
3. 
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
