
Decentralised Voting application using Ethereum Network

### Dir Structure 

```bash

    |
    +---build/contracts
    |                  Election.json
    |                  Migrations.json
    |
    +---contracts
    |            Election.sol
    |            Migrations.sol
    |
    +---migrations
    |             1_initial_migration.js
    |             2_deploy_contracts.js
    |
    +---src
    |      +---css
    |      |      bootstrap.min.css
    |      |      bootstrap.min.css.map
    |      |
    |      +---images
    |      |
    |      +---js
    |      |     app.jss
    |      |     bootstrap.min.jss
    |      |     truffle_contract.jss
    |      |     web3.min.jss
    |      |
    |      +---index.html
    |
    +---test
    |       .gitkeep
    |       election.js
    |
    +---.gitattributes
    |
    +---.gitignore
    |
    +---bs-config.json
    |
    +---LICENCE
    |
    +---package-lock.json
    |
    +---package.json
    |
    +---README.md
    |
    +---truffle-config.json
    

```
## Setup
### Dependencies
<ul>
  <li>NPM: https://nodejs.org</li>
  <li>Truffle: https://github.com/trufflesuite/truffle</li>
  <li>Ganache: http://truffleframework.com/ganache/</li>
  <li>Metamask: https://metamask.io/</li>
</ul>  

Follow the steps below to download, install, and run this project.

### Step 1. Clone the project
`git clone 

### Step 2. Install dependencies
```

$ npm install
```
### Step 3. Start Ganache
Open the Ganache GUI client. This will start your local blockchain instance.


### Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

### Step 5. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

### Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

If you get stuck, want to collaborate or found a bug, please raise an issue.
