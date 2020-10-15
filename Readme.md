
# BSC Developer Tools List

A guide to available tools, components, and platforms for developing applications on BSC.

## Developer Tools
### Developing Smart Contracts
#### Smart Contract Languages

| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|  [Solidity](https://solidity.readthedocs.io/en/latest/)|Ethereum smart contracting language|10 |
| [Vyper](https://vyper.readthedocs.io/en/latest/) | New experimental pythonic programming language| 10|

#### Frameworks

| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Truffle](https://trufflesuite.com/)| Most popular smart contract development, testing, and deployment framework.|9, can not verify contract on truffle directly(we use BscScan, Truffle do not integrated with it)|
|[Embark](https://github.com/embark-framework/embark)| Framework for DApp development | 10 |
|[Waffle](https://getwaffle.io/)| Framework for advanced smart contract development and testing, small, flexible, fast (based on ethers.js)| 10 |
|[Dapp](https://dapp.tools/dapp/)| - Framework for DApp development, successor to DApple| 10 |
|[OpenZeppelin SDK](https://openzeppelin.com/sdk/)| OpenZeppelin SDK: A suite of tools to help you develop, compile, upgrade, deploy and interact with smart contracts.| 10|
|[0xcert](https://github.com/0xcert/framework/)| JavaScript framework for building decentralized applications| 10 |

#### IDEs
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Remix](https://remix.ethereum.org/)| Web IDE with built in static analysis, test blockchain VM|10 |
|[Intellij Solidity Plugin]| Open-source plug-in for [JetBrains IntelliJ Idea IDE](https://jetbrains.com/idea/)|10|

### Other tools
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Buidler](https://buidler.dev/)| Extensible developer tool that helps smart contract developers increase productivity by reliably bringing together the tools they want.| 10 |
|[Azure Blockchain Dev Kit for BSC for VSCode](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain)| VSCode extension that allows for creating smart contracts and deploying them inside of Visual Studio Code|10|


### Test blockchain networks
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[bscnode](https://docs.binance.org/smart-chain/developer/fullnode.html) | Run an BSC node for development |10|
|[Ganache](https://github.com/trufflesuite/ganache)| App for test BSC blockchain with visual UI and logs, except for some precompile contract, the rest is same|9|
|[Local BSC Network](https://github.com/ConsenSys/local_ethereum_network)| User can simply set up a bsc network using clique consensus|10|

#### Test Ether faucets

| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[BSC faucet](https://testnet.binance.org/faucet-smart)| |10|


### Communicating with BSC
#### Frontend BSC APIs
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Web3.js](https://github.com/ethereum/web3.js/)| Javascript Web3 | 10| 
|[Eth.js](https://github.com/ethjs)| Javascript Web3 alternative | 10 |
|[Ethers.js](https://github.com/ethers-io/ethers.js/)| Javascript Web3 alternative, useful utilities and wallet features | 10|
|[light.js](https://github.com/paritytech/js-libs/tree/master/packages/light.js)| A high-level reactive JS library optimized for light clients| 10|
|[Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper)| Typescript Web3 alternative|10|
|[Ethereumjs](https://github.com/ethereumjs/) - A collection of utility functions for Ethereum like [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) and [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)|10|
|[flex-contract](https://github.com/merklejerk/flex-contract) and [flex-ether](https://github.com/merklejerk/flex-ether)|  Modern, zero-configuration, high-level libraries for interacting with smart contracts and making transactions.|10|
|[web3x](https://github.com/xf00f/web3x)|  A TypeScript port of web3.js. Benefits includes tiny builds and full type safety, including when interacting with contracts.
|[Nethereum](https://github.com/Nethereum/)| Cross-platform Ethereum development framework | 10 |
|[Drizzle](https://github.com/truffle-box/drizzle-box)| Redux library to connect a frontend to a blockchain| 10| 
|[Tasit SDK](https://github.com/tasitlabs/tasitsdk)| A JavaScript SDK for making native mobile Ethereum dapps using React Native| 10|
|[Subproviders](https://0x.org/docs/tools/subproviders)| Several useful subproviders to use in conjunction with [Web3-provider-engine](https://github.com/MetaMask/web3-provider-engine) (including a LedgerSubprovider for adding Ledger hardware wallet support to your dApp)| 10 |
|[web3-react](https://github.com/NoahZinsmeister/web3-react)| React framework for building single-page Ethereum dApps | 10 |
|[ethvtx](https://github.com/ticket721/ethvtx)| ethereum-ready & framework-agnostic redux store configuration. [docs](https://ticket721.github.io/ethvtx/)| 10|
|[ChainAbstractionLayer](https://github.com/liquality/chainabstractionlayer)| Communicate with different blockchains (including Ethereum) using a single interface.| 10|
|[Delphereum](https://github.com/svanas/delphereum)|a Delphi interface to the Ethereum blockchain that allows for development of native dApps for Windows, macOS, iOS, and Android.|10|

#### Backend BSC APIs
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Web3.py](https://github.com/ethereum/web3.py)| Python Web3| 10|
|[Web3.php](https://github.com/sc0Vu/web3.php) |PHP Web3| 10 |
|[Ethereum-php](https://github.com/digitaldonkey/ethereum-php)| PHP Web3| 10 |
|[Web3j](https://github.com/web3j/web3j) | Java Web3| 10|
|[Nethereum](https://nethereum.com/)|.Net Web3 | 10 |
|[Ethereum.rb](https://github.com/EthWorks/ethereum.rb)| Ruby Web3 | 10|
|[Web3.hs](https://hackage.haskell.org/package/web3) |Haskell Web3 | 10 |
|[KEthereum](https://github.com/komputing/KEthereum) | Kotlin Web3 | 10 |
|[Eventeum](https://github.com/ConsenSys/eventeum)| A bridge between Ethereum smart contract events and backend microservices, written in Java by Kauri| 10 |
|[Ethereumex](https://github.com/mana-ethereum/ethereumex)| Elixir JSON-RPC client for the Ethereum blockchain | 10 |
|[Ethereum-jsonrpc-gateway](https://github.com/HydroProtocol/ethereum-jsonrpc-gateway)| A gateway that allows you to run multiple Ethereum nodes for redundancy and load-balancing purposes. Can be ran as an alternative to (or on top of) Infura. Written in Golang.| 10 | 
|[EthContract](https://github.com/AgileAlpha/eth_contract) | A set of helper methods to help query ETH smart contracts in Elixir|10|
|[Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) |A MESG Service to interact with any Ethereum contract based on its address and ABI.| 10| 
|[Ethereum Service](https://github.com/mesg-foundation/service-ethereum)| A MESG Service to interact with events from Ethereum and interact with it.|10|
|[Marmo](https://marmo.io/)| Python, JS, and Java SDK for simplifying interactions with Ethereum. Uses relayers to offload transaction costs to relayers.|10|

#### Bootstrap/out of box tools
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Truffle boxes](https://trufflesuite.com/boxes)| Packaged components for the Ethereum ecosystem| 10 |
|[Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts)| Out-of-the-box deployment scripts for private PoA networks| 10 |
|[Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network)| Out-of-the-box deployment scripts for private PoW networks| 10 |
|[Cheshire](https://github.com/endless-nameless-inc/cheshire) | A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box| 10 |
|[aragonCLI](https://github.com/aragon/aragon-cli) | aragonCLI is used to create and develop Aragon apps and organizations.| 10 |
|[ArcJS](https://github.com/daostack/arc.js) | Library that facilitates javascript application access to the DAOstack Arc ethereum smart contracts.| 10 |
|[Blocknative](https://blocknative.com) |Assist.js is an embeddable widget that improves Dapp usability. The tool programmatically identifies and outlines clear actions for end-users to follow when interacting with MetaMask to overcome — and even prevent — common pitfalls and obstacles.|10|

#### Ethereum ABI (Application Binary Interface) tools

| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[ABI decoder](https://github.com/ConsenSys/abi-decoder) | library for decoding data params and events from Ethereum transactions| 10|
|[ABI-gen](https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen)| Generate Typescript contract wrappers from contract ABI's.|10|
|[Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) | Auto-generate UI form field definitions and associated validators from an Ethereum contract ABI|10|
|[headlong](https://github.com/esaulpaugh/headlong/) | type-safe Contract ABI and Recursive Length Prefix library in Java| 10 |
|[Truffle Pig](https://npmjs.com/package/trufflepig) | a development tool that provides a simple HTTP API to find and read from Truffle-generated contract files, for use during local development. Serves fresh contract ABIs over http.| 10|
|[Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) | A MESG Service to interact with any Ethereum contract based on its address and ABI.| 10 |
|[Nethereum-CodeGenerator](https://github.com/StefH/Nethereum-CodeGenerator) - A web based generator which creates a Nethereum based C# Interface and Service based on Solidity Smart Contracts.| 10| 


### Infrastructure
#### Ethereum Clients
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Seth](https://github.com/dapphub/dapptools/tree/master/src/seth)| Seth is an Ethereum client tool—like a "MetaMask for the command line"|10 |


#### Messaging
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Whisper](https://github.com/ethereum/wiki/wiki/Whisper)| Communication protocol for DApps to communicate with each other, a native base layer service of the Ethereum web3 stack|10|
|[DEVp2p Wire Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md)| Peer-to-peer communications between nodes running Ethereum/Whisper| 10|
|[Pydevp2p](https://github.com/ethereum/pydevp2p) | Python implementation of the RLPx network layer| 10|
|[3Box Threads](https://docs.3box.io/api/messaging)| API to allow developers to implement IPFS persisted, or in memory peer to peer messaging.|10|

### Testing Tools
| Name  | Description  | Support on BSC(rate 1 to 10) |
|  ---  |---|---|
|[Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage)| Solidity code coverage tool | 10| 
|[Solidity coverage](https://github.com/sc-forks/solidity-coverage) | Alternative code coverage for Solidity smart-contracts| 10|
|[Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler| 10 |
|[Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) | Alternative and updated Solidity smart contract profiler|  10 |
|[Espresso](https://github.com/hillstreetlabs/espresso) | Speedy, parallelised, hot-reloading solidity test framework| 10|
|[Eth tester](https://github.com/ethereum/eth-tester) | Tool suite for testing Ethereum applications| 10|
|[Cliquebait](https://github.com/f-o-a-m/cliquebait) | Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network| 10|
|[Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) | The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts| 10 |
|[Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) | Solidity graphical debugger | 10|
|[Tenderly CLI](https://github.com/Tenderly/tenderly-cli)|Speed up your development with human readable stack traces| 10|
|[Solhint](https://github.com/protofire/solhint) | Solidity linter that provides security, style guide and best practice rules for smart contract validation| 10|
|[Ethlint](https://github.com/duaraghav8/Ethlint) | Linter to identify and fix style & security issues in Solidity, formerly Solium| 10|
|[Decode](https://github.com/hacker-DOM/decode) | npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand| 10|
|[truffle-assertions](https://github.com/rkalis/truffle-assertions) | An npm package with additional assertions and utilities used in testing Solidity smart contracts with truffle. Most importantly, it adds the ability to assert whether specific events have (not) been emitted.| 10 |
|[Psol](https://github.com/Lamarkaz/psol) | Solidity lexical preprocessor with mustache.js-style syntax, macros, conditional compilation and automatic remote dependency inclusion.|10|
|[solpp](https://github.com/merklejerk/solpp) | Solidity preprocessor and flattener with a comprehensive directive and expression language, high precision math, and many useful helper functions.|10|
|[Decode and Publish](https://flightwallet.github.io/decode-eth-tx/) | Decode and publish raw ethereum tx. Similar to https://live.blockcypher.com/btc-testnet/decodetx/|10|
|[Doppelgänger](https://getdoppelganger.io/) | a library for mocking smart contract dependencies during unit testing. |10|
|[rocketh](https://github.com/wighawag/rocketh) | A simple lib to test ethereum smart contract that allow to use whatever web3 lib and test runner you choose.|10|
|[pytest-cobra](https://github.com/cobraframework/pytest-cobra) | PyTest plugin for testing smart contracts for Ethereum blockchain.| 10 |

### Security Tools
[MythX](https://mythx.io/) - Security verification platform and tools ecosystem for Ethereum developers
[Mythril](https://github.com/ConsenSys/mythril) - Open-source EVM bytecode security analysis tool
[Oyente](https://github.com/melonproject/oyente) - Alternative static smart contract security analysis
[Securify](https://securify.chainsecurity.com/) - Security scanner for Ethereum smart contracts
[SmartCheck](https://tool.smartdec.net/) - Static smart contract security analyzer
[Ethersplay](https://github.com/crytic/ethersplay) - EVM disassembler
[Evmdis](https://github.com/Arachnid/evmdis) - Alternative EVM disassembler
[Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
[Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
[Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool on Smart Contracts and Binaries
[Slither](https://github.com/crytic/slither) - A Solidity static analysis framework
[Adelaide](https://github.com/sec-bit/adelaide) - The SECBIT static analysis extension to Solidity compiler
[solc-verify](https://github.com/SRI-CSL/solidity/) - A modular verifier for Solidity smart contracts
[Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns
[Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected
[Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Free smart contract security audits from Callisto Network
[Piet](https://piet.slock.it) - A visual Solidity architecture analyzer

### Monitoring
* [Alethio](https://aleth.io/) - An advanced Ethereum analytics platform that provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search. Real-time market information and trading activities across Ethereum's decentralized exchanges can also be explored.
* [amberdata.io](https://amberdata.io) - Provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search.
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - A tool to monitor a number of smart contracts and transactions
* [Scout](https://scout.cool/) - A live data feed of the activities and event logs of your smart contracts on Ethereum
* [Tenderly](https://tenderly.co/) - A platform that gives users reliable smart contract monitoring and alerting in the form of a web dashboard without requiring users to host or maintain infrastructure
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - Explore smart contracts with decoded transaction data, see how the contract is used and search transactions with specific function calls
* [BlockScout](https://github.com/poanetwork/blockscout) - A tool for inspecting and analyzing EVM based blockchains. The only full featured blockchain explorer for Ethereum networks.
* [Terminal](https://terminal.co/) - A control panel for monitoring dapps. Terminal can be used to monitor your users, dapp, blockchain infrastructure, transactions and more.
* [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) - An extensible framework written in Golang for listening to on-chain events and doing something in response.

### Other Miscellaneous Tools
* [aragonPM](https://hack.aragon.org/docs/apm-intro.html) - a decentralized package manager powered by aragonOS and Ethereum. aragonPM enables decentralized governance over package upgrades, removing centralized points of failure.
* [Truffle boxes](https://www.trufflesuite.com/boxes) - Packaged components for building DApps fast.
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html) - Solidity compiler
* [Sol-compiler](https://sol-compiler.com/) - Project-level Solidity compiler
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile solidity-code faster, easier and more reliable
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Combine solidity project to flat file utility. Useful for visualizing imported contracts or for verifying your contract on Etherscan
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - Alternative, merges all imports into single file for solidity contracts
* [RLP](https://github.com/ethereumjs/rlp) - Recursive Length Prefix Encoding in JavaScript
* [eth-cli](https://github.com/protofire/eth-cli) - A collection of CLI tools to help with ethereum learning and development
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal is a command line tool for managing common tasks in Ethereum
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity
* [Parity Signer](https://github.com/paritytech/parity-signer) - mobile app allows signing transactions
* [py-eth](http://py-eth.com) - Collection of Python tools for the Ethereum ecosystem
* [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) - Concats solidity files developed under Truffle with all of their dependencies
* [Decode](https://github.com/hacker-DOM/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [TypeChain](https://github.com/ethereum-ts/TypeChain) - Typescript bindings for Ethereum smartcontracts
* [EthSum](https://ethsum.netlify.com) - A Simple Ethereum Address Checksum Tool
* [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) - allows indexing blocks or listening to Events in PHP
* [Purser](https://github.com/JoinColony/purser) - JavaScript universal wallet tool for Ethereum-based wallets. Supports software, hardware, and Metamask -- brings all wallets into a consistent and predictable interface for dApp development.
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - Connect to MetaMask from node.js
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Documentation generator for Solidity projects
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - Export Ethereum blockchain data to CSV or JSON files
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Prettier plugin for formatting Solidity code
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - Ethereum and Unity integration demo
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - Ethereum and Unity integration demo/sample
* [Wonka](https://github.com/Nethereum/Wonka) - Nethereum business rules engine demo/sample
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - A set of tools to standarize Solidity import and artifact resolution in frameworks.
* [eth-reveal](https://github.com/justinjmoses/eth-reveal) - A node and browser tool to inspect transactions - decoding where possible the method, event logs and any revert reasons using ABIs found online. 
* [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) - A useful library written in Golang to reliably send a transaction — abstracting away some of the tricky low level details such as gas optimization, nonce calculations, synchronization, and retries.


#### Popular Smart Contract Libraries
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - Contains tested reusable smart contracts like SafeMath and OpenZeppelin SDK [library](https://github.com/OpenZeppelin/openzeppelin-sdk) for smart contract upgradeability
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - A collection of Solidity libraries for building secure and gas-efficient smart contracts on Ethereum.
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) - A group of packages built for use on blockchains utilising the Ethereum Virtual Machine
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library
* [Aragon](https://github.com/aragon/aragon) - DAO protocol. Contains [aragonOS smart contract framework](https://github.com/aragon/aragonOS) with focus on upgradeability and governance
* [ARC](https://github.com/daostack/arc) - an operating system for DAOs and the base layer of the DAO stack.
* [0x](https://github.com/0xProject) - DEX protocol
* [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - Contains correctness proofs of token contracts wrt. given specifications and high-level properties
* [Provable API](https://github.com/provable-things/ethereum-api) - Provides contracts for using the Provable service, allowing for off-chain actions, data-fetching, and computation



#### Prebuilt UI Components
* [aragonUI](https://ui.aragon.org) - A React library including Dapp components
* [components.bounties.network](https://components.bounties.network) - A React library including Dapp components
* [ui.decentraland.org](https://github.com/decentraland/ui) - A React library including Dapp components
* [dapparatus](https://github.com/austintgriffith/dapparatus) - Reusable React Dapp components
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Metamask React Components
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - A cross-platform hybrid hosting mechanism for web based decentralised applications
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - Cross-platform desktop wallet sample
* [eth-button](https://eth-button.github.io/eth-button/) - Minimalist donation button
* [Rimble Design System](https://rimble.consensys.design/) - Adaptable components and design standards for decentralized applications.
* [3Box Plugins](https://docs.3box.io/build/plugins) - Drop in react components for social functionality. Including comments, profiles and messaging.


### 
* [Atra Blockchain Services](https://console.atra.io) - Atra provides web services to help you build, deploy, and maintain decentralized applications on the Ethereum blockchain.


### Requirement from Community

* The graph
* Multi sender/ Airdrop
* gnosis-safe.io
* [Infura](https://infura.io/) - Ethereum API access to Ethereum networks (Mainnet, Ropsten, Rinkeby, Goerli, Kovan)
[BSC on Google Cloud](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/ethereum?filter=category:developer-tools) - Build Ethereum network based on Proof of Work
* [CloudFlare Distributed Web Gateway](https://cloudflare.com/distributed-web-gateway/) - Provides access to the Ethereum network through the Cloudflare instead of running your own node
* [Chainstack](https://chainstack.com/) - Shared and dedicated Ethereum nodes as a service (Mainnet, Ropsten)
|[ez-ens](https://github.com/merklejerk/ez-ens)|  Simple, zero-configuration Ethereum Name Service address resolver. | 10 |
https://app.dfuse.io/home

* [Infura](https://infura.io/) - A managed service providing Ethereum client standards-compliant APIs
* [Truffle Teams](https://trufflesuite.com/teams) - Zero-Config continuous integration for truffle projects

