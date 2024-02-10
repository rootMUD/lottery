# 🏗 Lottery dApp 

> Smart Contract Addr:
>
> https://optimistic.etherscan.io/address/0x130251dEEA9f9fD16809086369AC3494D0509B33#code

🧪 Lottery dApp 是一个用于对 RMUD 用户等用户群体进行抽奖的 dApp。

🧪 Lottery dApp is a dApp used to draw lottery for user groups such as RMUD users.

## Quickstart
## Backend 
## Frontend
### Requirements

Before you begin, you need to install the following tools:

- [Node (v18 LTS)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)

To get started with Bodhi AI Explorer, follow the steps below:

1. Clone this repo & install dependencies

```
git clone https://github.com/NonceGeek/ai-based-smart-contract-explorer.git
cd ai-based-smart-contract-explorer
yarn install
```

2. Run a local network in the first terminal:

```
yarn chain
```

This command starts a local Ethereum network using Hardhat. The network runs on your local machine and can be used for testing and development. You can customize the network configuration in `hardhat.config.ts`.

3. On a second terminal, deploy the test contract:

```
yarn deploy
```

This command deploys a test smart contract to the local network. The contract is located in `packages/hardhat/contracts` and can be modified to suit your needs. The `yarn deploy` command uses the deploy script located in `packages/hardhat/deploy` to deploy the contract to the network. You can also customize the deploy script.

4. On a third terminal, start your NextJS app:

```
yarn start
```

Visit your app on: `http://localhost:3000`. You can interact with your smart contract using the contract component or the example ui in the frontend. You can tweak the app config in `packages/nextjs/explorer.config.ts`.

Run smart contract test with `yarn hardhat:test`

- Edit your smart contract `VectorDBProposalGovernancer.sol` in `packages/hardhat/contracts`
- Edit your frontend in `packages/nextjs/pages`
- Edit your deployment scripts in `packages/hardhat/deploy`



## Architecture

`TODO`

