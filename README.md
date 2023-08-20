Flow of the project:
1. User will connect their wallet with the frontend website from the browser
2. He will list out the name and description of the required art piece, which will be passed on the AI generator(using huggingface.co - provides stable diffusion api). The generator will send out the image which will be uploaded to NFT.storage(IPFS - Interplanetary File System)
3. A preview will be given to the user for the image that has to be converted to ERC721 token 
4. On approval the image will be converted to an NFT

Working: 
To compile and deploy the smart contract on hardhat localhost
`npx hardhat run ./scripts/deploy.js --network localhost`

To run the hardhat node
`npx hardhat node`

To run the react frontend file 
`npm run start`

