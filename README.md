# Blockchain-Resources

## Starter Resources

<details>
<summary>
Common Starter Resources
</summary>
   
* [Solidity](https://soliditylang.org/) - The most popular smart contract language.
* [Metamask](https://metamask.io/) - Browser extension wallet to interact with Dapps.
* [Truffle](https://trufflesuite.com/) - Most popular smart contract development, testing, and deployment framework. Install the cli via npm and start here to write your first smart contracts.
* [Hardhat](https://hardhat.org/) - Flexible, extensible and fast Ethereum development environment.
* [Cryptotux](https://cryptotux.org/) - A Linux image ready to be imported in VirtualBox that includes the development tools mentionned above
* [OpenZeppelin Starter Kits](https://openzeppelin.com/starter-kits/) - An all-in-one starter box for developers to jumpstart their smart contract backed applications. Includes Truffle, OpenZeppelin SDK, the OpenZeppelin/contracts-ethereum-package EVM package of audited smart contract, a react-app and rimble for easy styling.
* [useWeb3.xyz](https://useweb3.xyz/) — A curated overview of the best and latest resources on Ethereum, blockchain and Web3 development.

</details>   
   
<details>
<summary>
Glossaries
</summary>
   
* [A Blockchain Glossary for Beginners](https://consensys.net/knowledge-base/a-blockchain-glossary-for-beginners/)
* [Blockchain Glossary by Blockchain Hub](https://blockchainhub.net/blockchain-glossary/)
* [Crypto Glossary by Coinmarketcap](https://coinmarketcap.com/alexandria/glossary)
* [Cryptocurrency, Bitcoin terms and abbreviation](https://clacified.com/tech-science/16/cryptocurrency-bitcoin-terms-and-abbreviation-explained)
* [Solidity Cheatsheet](https://github.com/manojpramesh/solidity-cheatsheet)
   
</details> 

<details>
<summary>
Ethereum Specific Starter Resources
</summary>
   
* [EthHub.io](https://docs.ethhub.io/) - Comprehensive crowdsourced overview of Ethereum- its history, governance, future plans and development resources.
* [EthereumDev.io](https://ethereumdev.io) - The definitive guide for getting started with Ethereum smart contract programming.
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Brownie is a Python framework for deploying, testing and interacting with Ethereum smart contracts.
* [Ethereum Stack Exchange](https://ethereum.stackexchange.com/) - Post and search questions to help your development life cycle. 

</details> 


## Concepts

<details>
<summary>
Fungibility
</summary>

- The ability of a good or asset to be interchanged with other individual goods or assets of the same type
- It implies equal value between the assets
- Simplifies the exchange and trade processes
- To put it into perspective, the fungibility of money refers to the fact that all money is the same. It doesn't matter whether you have one $100 bill or one hundred $1 bills.  You can use both of them to purchase the same product
</details> 

<details>
<summary>
NFT
</summary>
   
- NFTs are unique cryptographic tokens that exist on a blockchain and cannot be replicated
- NFTs can be used to represent real-world items like artwork, real-estate, tangible items like collectibles
- "Tokenizing" these real-world tangible assets allows them to be bought, sold, and traded more efficiently while reducing the probability of fraud

</details> 


<details>
<summary>
NFT Resources
</summary>

- [Investopedia](https://www.investopedia.com/non-fungible-tokens-nft-5115211)
- [The Verge](https://www.theverge.com/22310188/nft-explainer-what-is-blockchain-crypto-art-faq)
- [Techradar](https://www.techradar.com/news/what-is-an-nft-non-fungible-tokens-explained-and-why-you-shouldnt-dismiss-this-fad)
- [Mashable](https://mashable.com/article/nft-explainer-what-are-non-fungible-tokens/)
- [Coindesk](https://www.coindesk.com/dapper-labs-coinlist-18m-token-sale-flow-blockchain)
- [First Twitter post sold by Twitter CEO Jack to @sinaEstavi for $2,915,835.47](https://v.cent.co/tweet/20)
- [NBA Topshot](https://www.nbatopshot.com)

</details> 

<details>
<summary>
DAO
</summary>

- [DAO definitions & differences between DAOs and traditional organizations](https://mirror.xyz/lisawocken.eth/DQ0N2xywJvbnog4jTD80R5orvReuOO4veZq3Muy7IqM)
- [The New Creator Economy - DAOs, Community Ownership, and Cryptoeconomics](https://dev.to/dabit3/the-new-creator-economy-daos-community-ownership-and-cryptoeconomics-lnl)
   
</details> 


## Patterns & Best Practices

<details>
<summary>
Patterns for Smart Contract Development
</summary>

* [Ethereum Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/)
* [Dappsys: Safe, simple, and flexible Ethereum contract building blocks](https://github.com/dapphub/dappsys)
    * provides building blocks for the [MakerDAO](https://github.com/makerdao/maker-otc) or [The TAO](https://github.com/ryepdx/the-tao)
    * should be consulted before creating own, untested, solutions
    * usage is described in [Dapp-a-day 1-10](https://steemit.com/@nikolai) and [Dapp-a-day 11-25](https://steemit.com/@nexusdev)
* [OpenZeppelin Contracts: An open framework of reusable and secure smart contracts in the Solidity language.](https://github.com/OpenZeppelin/openzeppelin-contracts)
    * Likely the most widely-used libraries and smart contracts
    * Similar to Dappsys, more integrated into Truffle framework
    * [Blog about Best Practices with Security Audits](https://blog.openzeppelin.com/)
* [Advanced Workshop with Assembly](https://github.com/androlo/solidity-workshop)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - especially section _Benefits_
* [CryptoFin Solidity Auditing Checklist](https://github.com/cryptofinlabs/audit-checklist) - A checklist of common findings, and issues to watch out for when auditing a contract for a mainnet launch.
* [aragonOS: A smart contract framework for building DAOs, Dapps and protocols](https://hack.aragon.org/docs/aragonos-intro.html)
    * Upgradeability: Smart contracts can be upgraded to a newer version
    * Permission control: By using the `auth` and `authP` modifiers, you can protect functionality so only other apps or entities can access it
    * Forwarders: aragonOS apps can send their intent to perform an action to other apps, so that intent is forwarded if a set of requirements are met
* [EIP-2535 Diamond Standard](https://eips.ethereum.org/EIPS/eip-2535)
    * Organize contracts so they share the same contract storage and Ethereum address.
    * Solves the 24KB max contract size limit.
    * Upgrade diamonds by adding/replacing/removing any number of functions in a single transaction.
    * Upgrades are transparent by recording them with a standard event.
    * Get information about a diamond with events and/or four standard functions.
* [Clean Contracts - A guide to writing clean code](https://www.wslyvh.com/clean-contracts/)
</details>


<details>
<summary>
Upgradability & Proxy Patterns
</summary>

In a scenario of a deployed smart contract with user funds having a vulnerability, a hot fix should be required to be deployed without delay. Traditional smart contract patterns don’t allow such hot fixes. Instead, the developers need to deploy a new contract every time they want to add a feature or fix a bug. To address this, upgradability patterns have been introduced. Upgradability means that the client always interacts with the same contract (proxy), but the underlying logic can be changed (upgraded) whenever needed without losing any previous data. There are three types of proxy patterns:

* Diamond pattern : EIP-2532
* Transparent proxy pattern : EIP-1967
* Universal upgradeable proxy standard (UUPS): EIP-1822

OpenZeppelin suggests using the UUPS pattern as it is more gas efficient. One of the main caveats is that because the upgrades are done via the implementation contract with the help of upgradeTo method, there’s a higher risk of newer implementations to exclude the upgradeTo method, which may permanently kill the ability to upgrade the smart contract.

Ref: [Using the UUPS proxy pattern to upgrade smart contracts - LogRocket](https://blog.logrocket.com/using-uups-proxy-pattern-upgrade-smart-contracts/)

</details> 

<details>
<summary>
Security Best Practices & Resources
</summary>
   
* [Smart Contract Weakness Classification and Test Cases - SWC Registry](https://github.com/SmartContractSecurity/SWC-registry) 
* [List of known attacks - Consensys](https://consensys.github.io/smart-contract-best-practices/attacks/)
* [Security Tools List - Consensys](https://consensys.github.io/smart-contract-best-practices/security-tools/)
* [Solidity Smart Contract Security Best Practices - 101 Blockchains](https://101blockchains.com/smart-contract-best-practices/)   
   
</details> 





## Developer Tools

<details>
<summary>
Smart Contract Languages
</summary>
   
* [Solidity](https://docs.soliditylang.org/en/latest/) - Ethereum smart contracting language
* [Vyper](https://vyper.readthedocs.io/en/latest/) - New experimental pythonic programming language
</details> 

<details>
<summary>
Frameworks
</summary>
   
* [Truffle](https://trufflesuite.com/) - Most popular smart contract development, testing, and deployment framework. The Truffle suite includes Truffle, [Ganache](https://github.com/trufflesuite/ganache), and [Drizzle](https://github.com/truffle-box/drizzle-box). [Deep dive on Truffle here](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [Hardhat](https://hardhat.org/) - Flexible, extensible and fast Ethereum development environment.
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Brownie is a Python framework for deploying, testing and interacting with Ethereum smart contracts.
* [Embark](https://github.com/embark-framework/embark) - Framework for DApp development
* [Waffle](https://getwaffle.io/) - Framework for advanced smart contract development and testing, small, flexible, fast (based on ethers.js)
* [Dapp](https://dapp.tools/dapp/) - Framework for DApp development, successor to DApple
* [Etherlime](https://github.com/LimeChain/etherlime) - ethers.js based framework for Dapp deployment
* [Parasol](https://github.com/Lamarkaz/parasol) - Agile smart contract development environment with testing, INFURA deployment, automatic contract documentation and more. It features a flexible and unopinionated design with unlimited customizability
* [0xcert](https://github.com/0xcert/framework/) - JavaScript framework for building decentralized applications
* [OpenZeppelin SDK](https://openzeppelin.com/sdk/) - OpenZeppelin SDK: A suite of tools to help you develop, compile, upgrade, deploy and interact with smart contracts.
* [sbt-ethereum](https://sbt-ethereum.io/) - A tab-completey, text-based console for smart-contract interaction and development, including wallet and ABI management, ENS support, and advanced Scala integration.
* [Cobra](https://github.com/cobraframework/cobra) - A fast, flexible and simple development environment framework for Ethereum smart contract, testing and deployment on Ethereum virtual machine(EVM).
* [Epirus](https://docs.epirus.io/sdk/) - Java framework for building smart contracts. 
</details> 

<details>
<summary>
IDEs
</summary>

* [Remix](https://remix.ethereum.org/) - Web IDE with built in static analysis, test blockchain VM.
* [Ethereum Studio](https://studio.ethereum.org/) - Web IDE. Built in browser blockchain VM, Metamask integration (one click deployments to Testnet/Mainnet), transaction logger and live code your WebApp among many other features.
* [Atom](https://atom.io/) - Atom editor with [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom), [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), and [language-solidity](https://atom.io/packages/language-solidity) packages
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Vim syntax file for solidity
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio Code extension that adds support for Solidity
* [Ethcode](https://marketplace.visualstudio.com/items?itemName=quantanetwork.ethcode) - Visual Studio Code extension to compile, execute & debug Solidity & Vyper programs
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - Open-source plug-in for [JetBrains IntelliJ Idea IDE](https://jetbrains.com/idea/) (free/commercial) with syntax highlighting, formatting, code completion etc.
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - Eclipse based IDE. Features context sensitive code completion and help, code navigation, syntax coloring, build in compiler, quick fixes and templates.
* [Eth Fiddle](https://ethfiddle.com/) - IDE developed by [The Loom Network](https://loomx.io/) that allows you to write, compile and debug your smart contract. Easy to share and find code snippets.
</details>

<details>
<summary>
Ethereum
</summary>
   
- [Eth Dev Tools List](https://github.com/ConsenSys/ethereum-developer-tools-list)
</details> 

<details>
<summary>
Wallet
</summary>
   
- [Metamask](https://metamask.io/)
- [Celo Extension Wallet](https://chrome.google.com/webstore/detail/celoextensionwallet/kkilomkmpmkbdnfelcpgckmpcaemjcdh?hl=en)
- [Valora](https://valoraapp.com/)
</details> 

<details>
<summary>
Faucet
</summary>
   
- [Faucet to fund testnet with Celo](https://celo.org/developers/faucet)
- [Faucet to fund 5 testnet with ETH, wETH, DAI & NFTs - Paradigm Faucet](https://faucet.paradigm.xyz/)
   - Sign in via Twitter is a must
   - Your Twitter account must have at least 1 Tweet, 15 followers, and be older than 1 month.
   - The faucet drips 1 ETH, 1 wETH, 500 DAI, and 5 NFTs (ERC721).
   - You will receive these tokens on Kovan, Görli, Optimistic Kovan, Polygon Mumbai and Avalanche Fuji.
   - You can claim from the faucet once every 24 hours.
</details> 

<details>
<summary>
Others
</summary>
   
- Steps to add Custom RPC as Alphajores Network on Metamask:
- After opening up Metamask wallet account, open the Chrome extension & click on the network dropdown
- Click on "Custom RPC"
- Put "Alfajores Network" as Network Name (you can put anything else to your own convenience)
- Put this [URL](https://alfajores-forno.celo-testnet.org/) as New RPC URL
- Put 44787 as Chain ID
- Currency Symbol & Block Explorer URL are fields optional
</details> 





## Q&As/Interview Questions 

### Fundamentals

<details>
<summary><strong>Briefly explain Consensus mechanism in Blockchain</strong></summary>

A consensus algorithm is a method through which all the peers of the blockchain network reach a standard agreement of the present state of a distributed ledger.
It achieves high reliability and establishes trust between unknown peers in the distributed computing environment.

There are different types of consensus algorithms:
   
* Proof-of-Work(PoW)
* Proof-of-Capacity (PoC)
* Proof-of-Activity (PoA)
* Delegated Proof-of-Stake(DPoS)
* Proof-of-Stake(PoS)
* Proof-of-Authority
* Proof-of-Burn 
* Unique Node Lists 
* Proof-of-Weight 
* Proof-of-Elapsed Time
* SIEVE
* Byzantine Fault Tolerance  
   
</details>

<details>
<summary><strong>What's Markel Tree</strong></summary>

Merkel Tree is a data structure that is used for verifying a block. 
   
* Each leaf node is a hash of a block of transactional data
* Each non-leaf node is a hash of its leaf node
* The Merkel root or hash root is the final hash root of all the transaction hashes. It encompasses all the transactions that are underlying all the non-leaf nodes.
   
The importance of a Merkle tree in the blockchain is that if anyone wants to verify the specific transaction in a block, they can download the chain of block headers instead of downloading every transaction and every block.
   
</details>

<details>
<summary><strong>In what order blocks are linked in blockchain?</strong></summary>
All the blocks in the blockchain are linked in the backward order or each block links with its previous block.
</details>

<details>
<summary><strong>What's a 51% attack/double-spend attack?</strong></summary>
A 51% attack or double-spend attack occurs when a group of miners on a blockchain controls >50% of the network’s mining hash rate or computing power. They
can reverse completed transactions & thus double-spend coins.
   
* In a PoW, Any malicious user would need to have 51% of computation power to solve the problem and thereby add the wrong block.
* In a PoS, any malicious user would need to have 51% of the total money on the network to add a wrong block.   
</details>

<details>
<summary><strong>What does nonce mean?</strong></summary>
   
A nonce is an abbreviation for "number only used once". A blockchain nonce is a number added to a hashed—or encrypted—block in a blockchain. 
A single-use arbitrary string or number generated for verification purposes to prevent replaying past transactions.
</details>
