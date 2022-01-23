# Deploying an NFT project on rinkeby testnet


Deploy ypur own NFT project with Alchemy and pinata

Run the following commands to deploy:


```shell
npm install @openzeppelin/contracts@3.1.0-solc-0.7
npm install --save-dev @nomiclabs/hardhat-ethers "ethers@^5.0.0"
npm install @alch/alchemy-web3                                  
npm install dotenv --save                         

npx hardhat
npx hardhat compile
npx hardhat run scripts/run.js --network rinkeby
node scripts/mint-nft.js
```
