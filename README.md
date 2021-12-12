# buildspace-nft-contract

This repo contains the contract developed during [Buildspace's NFT course](https://app.buildspace.so/projects/CO961ddb5f-f428-4608-9949-a9a2f461eb3f).

Frontend [here](https://github.com/umluizlima/buildspace-nft-frontend).

## Development

1. Install dependencies;
    ```shell
    npm install
    ```

2. Create a `.env` file and add secrets to it;

3. Run
    ```shell
    npx hardhat run scripts/run.js --network hardhat
    ```

## Deployment

1. Deploy to `rinkeby` testnet;
    ```shell
    npx hardhat run scripts/deploy.js --network rinkeby
    ```

2. Copy the contract address that is printed to console at the end of previous step;

3. Verify the contract on `etherscan`;
    ```shell
    npx hardhat verify CONTRACT_ADDRESS --network rinkeby
    ```

4. Check the link that is printed to console at the end of previous step;
