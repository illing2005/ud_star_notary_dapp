# Decentralized Star Notary Service

This project was developed as part of the 
[Udacity Blockchain Developer Nanodegree Program](https://www.udacity.com/course/blockchain-developer-nanodegree--nd1309)

The DApp implements the ERC-721 non-fungible token interface and let's you create, sell, and transfer star tokens.

It is deployed to the public Rinkeby testnet.

- Token Name: *Udacity Star Token*
- Token Symbol: *UST*
- Versions: Truffle v5.4.29, OpenZeppelin v2.3.0
- Contract address: [0x713252c71517800ccfb41282972a0c9a25e69a49](https://rinkeby.etherscan.io/address/0x713252c71517800ccfb41282972a0c9a25e69a49)

## Project and Task description:

### Task 1

#### Your Project is to Modify the StarNotary version 2 contract code to achieve the following:

- Add a name and a symbol for your starNotary tokens. Resource
- Add a function lookUptokenIdToStarInfo, that looks up the stars using the Token ID, and then returns the name of the star.
- Add a function called exchangeStars, so 2 users can exchange their star tokens...Do not worry about the price, just write code to exchange stars between users.
- Write a function to Transfer a Star. The function should transfer a star from the address of the caller. The function should accept 2 arguments, the address to transfer the star to, and the token ID of the star.

### Task 2

#### Add supporting unit tests, to test the following:

- The token name and token symbol are added properly.
- 2 users can exchange their stars.
- Stars Tokens can be transferred from one address to another.

### Task 3

#### Deploy your Contract to Rinkeby

- Edit the truffle.config file to add settings to deploy your contract to the Rinkeby Public Network.

### Task 4

#### Modify the front end of the DAPP to achieve the following:

- Lookup a star by ID using tokenIdToStarInfo() (you will have to add code for this in your index.html and index.js files)

