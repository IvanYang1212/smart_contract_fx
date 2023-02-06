# smart_contract_fx

POC porject to publish stable coin based on currency

## Setup

Clone this repo

```
git clone https://github.com/IvanYang1212/smart_contract_fx.git
cd smart_contract_fx
```

Then install dependencies

```
yarn
```

2. Create .env file copying .env.example, and update the config for PRIVATE_KEY and PRC_URL

`.env` Example for goerli test net:

```
RPC_URL=https://eth-goerli.g.alchemy.com/v2/TPsr2nrhRHJZ7DJkEZl3PVu-qTCwPJAM
```

4. Compile your code

Run

```
yarn compile
```

You'll see files `SimpleStorage_sol_SimpleStorage.abi` and `SimpleStorage_sol_SimpleStorage.bin` be created.

5. Run your application

```
node deploy.js
```

It will take a while when deploy the smart contract to test net.
