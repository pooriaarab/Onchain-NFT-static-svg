### Onchain NFT: Static SVG
Mint and on-chain NFT on Rinkeby testnet.

### Install dependencies
Run the following command to install the dependencies:
```
npm install
```
### Edit .env.example with your API
Create new app on Alchemy, view HTTP URL, then paste in API_URL
Visit https://docs.alchemy.com/alchemy/introduction/getting-started

### Edit .env.example with your private key from MetaMask
Visit https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key and paste key into PRIVATE_KEY

### Switch MetaMask to Rinkeby and get rEth
Visit https://gist.github.com/tschubotz/8047d13a2d2ac8b2a9faa3a74970c7ef

### Rename .env.example
```
Rename to ".env" (remove ".example" from the filename)
```

### Compile contract
Run the following command to compile your contracts:
```
npx hardhat compile
```

### Deploy contract
Run the following command to compile your contracts:
```
npx hardhat --network rinkeby run scripts/deploy.js
```

## When editing any files like .env, save your file
Press CTRL+S or File > Save to apply changes
