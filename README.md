#### Problems in Exixting System
---
- Shipment visibility
- Expiration
- Slow Process and Error prone paper work
- Mutable and Invalid source
- Lack of coordination

#### Advantages of blockchain supply chain:
---
- Accurate information across the entire chain at any point and at any location
- Instant access to real-time updates and alerts if issues are detected
- Visibility of all handovers in the supply chain
- Traceability back to source of all materials
- Seamless collaboration between all parties
- Reduce paper work and Speedup process


# Medical-Blockchain
This blockchain dapp shows the contribution it can add to the medical field, by tracking medicine from the moment it is manufactured till it reaches the patient.


- HD Wallet: <br>
    Connecting to ropsten network using infura

#### Tools and Technologies
---
- Solidity (Ethereum Smart Contract Language)
- Metamask (Ethereum wallet)
- Ropsten test network ( use ropsten faucet to get ethers on ropsten network )
- Truffle
- Infura
- Web3JS
- Javascript
- HTML

#### Prerequisites
---
- Nodejs v8.12 or above
- Truffle v5.0.0 (core: 5.0.0) (http://truffleframework.com/docs/getting_started/installation)
- Solidity v0.5.0
- Metamask (https://metamask.io)
- Ganache (https://truffleframework.com/docs/ganache/quickstart)


**Setting up Ethereum Smart Contract:**

```
git clone https://github.com/kamalkishorm/Blockchain_SupplyChain.git
cd Blockchain_SupplyChain/
```
**Update truffle.js **

Change the mnemonic to your metamask wallet seedphrase and the also ropsten infura key. 

```
Go to your project folder in terminal then execute :

```
rm -rf build/

truffle compile

truffle migrate --reset
```

The output would look like this:

1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x7dd085c13645afb916318e03a7755b05b5f5a9e5dbe5cde5a512f58251c4257f
   > Blocks: 0            Seconds: 0
   > contract address:    0x09e45726261f220b9a9947a354fC40Af8856d6D1
   > block number:        13
   > block timestamp:     1620728966
   > account:             0x9702b4C4d3259152acb9559E68aCF1Ad90E84683
   > balance:             99.96338326
   > gas used:            225237 (0x36fd5)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.000277462 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:         0.000277462 ETH


2_deploy_contracts.js
=====================

   Deploying 'ManufacturerRole'
   ----------------------------
   > transaction hash:    0x9a23082eaeb6ced0a6339cd233bc946957789371c465e22d30a80c6db1b60384
   > Blocks: 0            Seconds: 9
   > contract address:    0x95cc2F672C78c90Eef6F52015b74e0de49F85D35
   > account:             0x2d5faBF0533647E18dc4e96CdD447EF0045Db32B
   > balance:             2.099289105222213392
   > gas used:            380330
   > gas price:           1 gwei
   > value sent:          0 ETH
   > total cost:          0.00038033 ETH


   Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0x0fafa79db7bf45bc37f0e5383ecc9def8ed2dd467abdde7a78a50e290f42883b
   > Blocks: 0            Seconds: 9
   > contract address:    0x3A863d01F5c23B0c5fDA62f8E3878e37C7946832
   > account:             0x2d5faBF0533647E18dc4e96CdD447EF0045Db32B
   > balance:             2.098908903222213392
   > gas used:            380202
   > gas price:           1 gwei
   > value sent:          0 ETH
   > total cost:          0.000380202 ETH


   Deploying 'PharmacistRole'
   --------------------------
   > transaction hash:    0x836b7e4190379ee2f6eb94b3118d2c5d0854c776a657ed6cfe01aab3f455c92f
   > Blocks: 0            Seconds: 9
   > contract address:    0x8B3fe04804552B929058a879662856Dd3D107883
   > account:             0x2d5faBF0533647E18dc4e96CdD447EF0045Db32B
   > balance:             2.098528701222213392
   > gas used:            380202
   > gas price:           1 gwei
   > value sent:          0 ETH
   > total cost:          0.000380202 ETH


   Deploying 'PatientRole'
   -----------------------
   > transaction hash:    0xdd299cba520a28f55225edf845a7725b05de920324aad706d17d4830e8b0c315
   > Blocks: 0            Seconds: 9
   > contract address:    0x75163E16d6eA79462835D48f5C5Ae793FF35B874
   > account:             0x2d5faBF0533647E18dc4e96CdD447EF0045Db32B
   > balance:             2.098148499222213392
   > gas used:            380202
   > gas price:           1 gwei
   > value sent:          0 ETH
   > total cost:          0.000380202 ETH


   Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0xe1b88cc1d8bc9c669cb9969e1f42086decac73be539709cd8c2d2fac1690c445
   > Blocks: 0            Seconds: 9
   > contract address:    0x33d839692456381d4D741095B89f523E805a00FB
   > account:             0x2d5faBF0533647E18dc4e96CdD447EF0045Db32B
   > balance:             2.095517993222213392
   > gas used:            2630506
   > gas price:           1 gwei
   > value sent:          0 ETH
   > total cost:          0.002630506 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:         0.004151442 ETH


Summary
=======
> Total deployments:   6
> Final cost:          0.004428904 ETH


#### Run the application:

```
Use the command:

npm start 

to run the application.

```
