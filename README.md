# Welcome to Bloxchange

### What is our main idea?

---

### Which features does Bloxchange offer?

---

### How did we manage the project?

---

## Technologies used in Bloxchange

We have used several technologies to build this decentralized autonomous organization:

### IPFS/Web3.storage

All Data storage and querying is done via IPFS with help of Web3.storage SDKs and docs on the website.
**Web3.Storage** is used for storing all sort of Data including user profile, grants request and researches on **IPFS**, done with the help of the SDK provided and stored in JSON format.
The querying of the data is done with CID Gateway links and then rendered in Frontend. The CIDs are stored in contract to avoid data tampering. We take the input of the data from the user , pack it in JSON file and then upload the files IPFS via web3.storage. IPFS is also used to store our NFTs metadata compatible for ERC721 .

Website is currently up and working on the provided links of vercel and Spheron , can be tested according to the docs provided on the website. Also Backend Flow is added in the presentation.


---

## Smart Contracts

All of our smart contracts are written in Solidity. You can find them under [/backend/contracts](https://github.com/adiig7/Polygon-BUIDL-IT/tree/main/backend/contracts).

They have currently been published on Polygon Mumbai Testnet due to testing and presentational reasons.

In the smart contracts themselves you can find dev comments and explanations.
<br /><br /><br />


---

## Frontend

For the UI and design we have used the s to setup our project easily and build/design it with the help of JavaScript, React and HTML/CSS.

<br /><br /><br />

### Frontend folders in our project:

**constants** - important file with different constants to call in other programs

**pages** - all of our different frontend webpages

**public** - public files like images etc.

**src** - assets like images and single components of the different webpages

**styles** - CSS styling files
<br /><br /><br />

### Other important files:

**.env** - important API-keys for deployment

**.gitignore** - lets GitHub ignore several files like sensible data

**next.config.js** - configuration of Next.js

---

## Backend

In our backend folder you can find everything that’s working behind the scenes of Bloxchange!
<br /><br /><br />

### Backend folders in our project:

**contracts** - Solidity Smart Contracts

**scripts** - deployment scripts for the Smart Contracts
<br /><br /><br />

### Other important files:

**.gitignore** - lets GitHub ignore several files like sensible data

**README.md** - Smart Contract Addresses

**hardhat.config.js** - HardHat configuration file

---

## Wallet Connection

You can connect your wallet with the help of **RainbowKit**. The `create-web` package uses **RainbowKit** internally.

Look at the docs of RainbowKit on how to use it: [https://www.rainbowkit.com/docs/introduction](https://www.rainbowkit.com/docs/introduction)

---

### Developers

### Dhrumi Shah

![dhrumi](https://user-images.githubusercontent.com/54351909/200527848-325c8b67-3312-4e3a-88e4-fe7ea09db121.jpg)

**Frontend Developer**

Loves and hates CSS Simulatenously. Worked on making the frontend for the Bloxchange.

---

### Aditya Gupta

![aditya_gupta](https://user-images.githubusercontent.com/11206675/184015293-d9fc4e74-9a6a-49e7-be93-f0c7d1ebac32.jpg)

**Full Stack Web3 Developer**

Worked on making the frontend pages as well as integrating the smart contracts withe the frontend

---
