# Acorn

## How to run this project locally:

### Prerequisites

- Node.js >= v16
- Truffle
- `git checkout master`

### Contracts

- Run `npm ci` in project root to install Truffle build and smart contract dependencies
- Run `truffle compile`
- Run `truffle develop`, in the Truffle console run `migrate`
- To run tests, in Truffle console: `test`

### Frontend

- `cd client`
- `npm ci`
- Import accounts from local Truffle network with private keys shown in Truffle console to MetaMask
- `npm run start`
- Open `http://localhost:3000`
