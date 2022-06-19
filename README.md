# _DeFi-Hradhat-Token-Cliaim

# setting .env
After creat .env file, please copy the content of .env.sample.
And you can set params.


# deploy
 npx hardhat run  --network rinkeby scripts/deploy.js

# verify
- first contract
 npx hardhat verify --network rinkeby 0x6----first contract address----5

 https://rinkeby.etherscan.io/address/0xDBC99496c826540419d08753695A885039FC6776#code

# test
npx hardhat test