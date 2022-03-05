# Blockchain ERC samples
## ERC20-Crypto-Template
It is always based on EIP20 Token Standard.
This sample is clone from this github [Bitatlas] (https://github.com/Bitatlas/ERC20/blob/main/ERC20.sol).

### Compiling and deploying steps (Custom)
* Pull the ERC20 Token sample (Zimba.sol) and add it on Remix. 
* Make appropriate changes (Contract Name, Crypto Name, Symbol, Decimal, Total Supply)
* Compile and deploy this Smart Contract to(Mainnet | Polygon | Binance Smart Chain | Test Network)
* Make note of Smart Contract address after successfully deployed.
* Go to MetaMask --> Assets --> Import Tokens --> paste the Smart Contract address to add the Token in your wallet.
* We can see new coin and with intial supply value for that particular account.
* Send it to anyone you want, if target account don't see the new coin follow step 5 for targeted account.
* Done voila !!!

### Compiling and deploying steps (Already existed coin Ether, Shibu etc)
* Pull the Smart Contract from Etherscan.io (https://etherscan.io/address/0x95ad61b0a150d79219dcf64e1e6cc01f0b64c4ce#code)
* Add new solidity file in Remix and paste the Smart Contract and compile it (Sample file Zyaba attached in github).
* Before deploying change the contract to this (TokenMintERC20-nameContract.sol).
* In the deploy option fill the relevant the information (Crypto Name, Symbol, Decimal, for FreeReciver and TokenOwnerAddress add your address)
* And deploy the contract to target platform
* Done voila !!!

### Compiling and deploying steps (Using OpenZepplin)
* Go to OpenZepplin wizard (https://docs.openzeppelin.com/contracts/4.x/wizard) and make changes as required.
* Copy the Smart Contract and create new file and paste it on Remix.
* Deploy the Smart Contract by selecting the Contract file.
