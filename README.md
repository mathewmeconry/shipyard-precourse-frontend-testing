# Shipyard Precourse

This repo is for the Shipyard precourse.
It follows the tutorial [https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13).


# Prepare the repo for usage
Run `yarn` in the root folder to install the dependencies.

# Compile and deploy the contracts
Go into the folder `hardhat` and run `npx hardhat compile`.
Deploy locally: `npx hardhat run scripts/deploy.js`  
Deploy rinkeby: `ETH_KEY=YOUR-PRIVATE-KEY npx hardhat run scripts/deploy.js --network rinkeby`

# Run the frontend
Go into the folder `frontend` and run `yarn run start`

