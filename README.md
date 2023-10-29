# ethers.js
A complete, compact and simple library for Ethereum and ilk, written in TypeScript.
Features

Keep your private keys in your client, safe and sound
Import and export JSON wallets (Geth, Parity and crowdsale)
Import and export BIP 39 mnemonic phrases (12 word backup phrases) and HD Wallets (English as well as Czech, French, Italian, Japanese, Korean, Simplified Chinese, Spanish, Traditional Chinese)
Meta-classes create JavaScript objects from any contract ABI, including ABIv2 and Human-Readable ABI
Connect to Ethereum nodes over JSON-RPC, INFURA, Etherscan, Alchemy, Ankr or MetaMask
ENS names are first-class citizens; they can be used anywhere an Ethereum addresses can be used
Small (~144kb compressed; 460kb uncompressed)
Tree-shaking focused; include only what you need during bundling
Complete functionality for all your Ethereum desires
Extensive documentation
Large collection of test cases which are maintained and added to
Fully written in TypeScript, with strict types for security and safety
MIT License (including ALL dependencies); completely open source to do with as you please
Keep Updated
For advisories and important notices, follow @ethersproject on Twitter (low-traffic, non-marketing, important information only) as well as watch this GitHub project.

For more general news, discussions, and feedback, follow or DM me, @ricmoo on Twitter or on the Ethers Discord.

For the latest changes, see the CHANGELOG.

Summaries

September 2022
June 2022
March 2022
December 2021
September 2021
May 2021
March 2021
December 2020
Installing
NodeJS

/home/ricmoo/some_project> npm install ethers
Browser (ESM)

The bundled library is available in the ./dist/ folder in this repo.

<script type="module">
    import { ethers } from "./dist/ethers.min.js";
</script>
Documentation
Browse the documentation online:

Getting Started
Full API Documentation
Various Ethereum Articles
Providers
Ethers works closely with an ever-growing list of third-party providers to ensure getting started is quick and easy, by providing default keys to each service.

These built-in keys mean you can use ethers.getDefaultProvider() and start developing right away.

However, the API keys provided to ethers are also shared and are intentionally throttled to encourage developers to eventually get their own keys, which unlock many other features, such as faster responses, more capacity, analytics and other features like archival data.

When you are ready to sign up and start using for your own keys, please check out the Provider API Keys in the documentation.

A special thanks to these services for providing community resources:

Ankr
QuickNode
Etherscan
INFURA
Alchemy
Pocket
Extension Packages
The ethers package only includes the most common and most core functionality to interact with Ethereum. There are many other packages designed to further enhance the functionality and experience.

Hardware Wallets (coming soon)
Account Abstraction (coming soon)
License
MIT License (including all dependencies).
