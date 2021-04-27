# Neo Stack
This page provides an overview of the open-source Neo Stack. This is a living document with continuous updates. 

## Table of Contents
- [About](#about)
- [Funding](#funding)
- [Layers of Neo Stack](#layers-of-neo-stack)
  - [Protocol Layer](#protocol-layer)
  - [Infrastructure for dApp Development](#infrastructure-for-dapp-development)
  - [Digital Asset Protocol & Infrastructure](#digital-asset-protocol--infrastructure)
---


## About
The Neo stack is a set of software (sub)systems, components and tools that collectively empower and enable developers to build decentralized applications (dApps) on the Neo Blockchain. The Neo Blockchain is currently being upgraded to Neo|N3, and all listed projects should support Neo|N3 at the launch.

The Neo mission is to build the premier Digital Asset platform to realize our vision of the Smart Economy. Hence, the Neo Stack architecture aims to enable broad developer tooling and productivity for digital asset issuance and circulation at scale.

## Funding
In order to promote the growth and evolution of the Neo ecosystem, the Neo Foundation offers comprehensive [Neo Grants](https://github.com/gracegui43/Neo-Grants) to support software development and research efforts related to Neo. 

[Neo General Grants Program](https://github.com/gracegui43/Neo-Grants/blob/master/Neo%20General%20Grants%20Program.md) is focused on funding projects to build out the layers of the Neo Stack.  **According Neo's periodical roadmap and focus, we will update Neo Stack with potential interested projects and corresponding priority.** The Neo Foundation tends to support teams for excellent blockchain software development. **Projects that fill gaps in the current ecosystem, or projects that demonstrate extraordinary value over existing projects, will be given priority.**  Such value could be in many forms including but not limited to differentiated functionality, superior user experience, attracting new developers and users to the ecosystem or leading to a higher likelihood of the long-term sustainability of the ecosystem.



## Layers of Neo Stack
We look for innovative, pioneering approaches to enhance the Neo Stack. If you are looking for direction, please see below for an illustrative view of the layers that comprise the Neo stack.

If you believe that we should sponsor the development of certain tools/projects related to Neo that aren't currently in the [Neo Stack](https://github.com/gracegui43/Neo-Grants/blob/master/Neo%20Stack.md), then please feel free to submit a new pull request addressing the proposal. We will review your proposal and if the team deems it to be a priority then it will be added to the Neo Stack.

### Protocol Layer
Component|Existing Projects|Potentially idea or projects|Priority
--|--|--|--
Consensus Mechanism|[dBFT2.0](https://docs.neo.org/docs/en-us/basic/technology/dbft.html), [dBFT3.0](https://github.com/NeoResearch/dbft-report/tree/master/docs)||
Virtual Machine|[NeoVM](https://github.com/neo-project/neo-vm)||
Oracle|[Built-in Oracle](https://docs.neo.org/docs/en-us/advanced/oracle.html)||
Distributed Storage|[NeoFS](https://fs.neo.org/)||
DID|[Seraph ID](https://github.com/neo-ngd/seraph-id-smart-contracts), [vivID](https://moonlight.io/features/identity-management)||
Name Service|[NNS](https://neo.org/technology#neo-name-service)||
Cross Chain Protocol|[Poly Network](https://www.poly.network/)||

### Infrastructure & Modules 
Component|Existing Projects|Potentially idea or project|Priority
--|--|--|--
Nodes|C# - [neo-node](https://github.com/neo-project/neo-node)<br />Golang - [neo-go](https://github.com/nspcc-dev/neo-go)<br />Python - [neo-mamba](https://github.com/CityOfZion/neo-mamba)|SPV or any light nodes implementation|
**Dev Env**||Local development environment to speed up development and testing for smart contracts and other Neo applications.|**2021Q2**
Wallets and Extensions|[NeoLine](https://neoline.io), [O3](https://o3.network), [NEON](https://neonwallet.com)||
Explorer|[NeoTube](https://neotube.io), [Neo Tracker](https://neotracker.io), [NEL Scan](https://scan.nel.group), [Dora](https://dora.coz.io/), [NeoTube\|N3](https://neo3.neotube.io/)||
Monitors|[Neo Monitor](http://monitor.cityofzion.io)|Tools to monitor the status of the blockchain network, including node stability, block generation, transaction processing and traffic, etc.|2021Q3
**Node API Service**||Tools to provide highly scalable and stable API services for all Neo applications.|**2021Q2**
Analytics Services||Provide structured and verifiable on-chain data for contracts and other Neo applications.|2021Q3
Privacy|| Add-on plugins and related infrastructure capabilities to enhance the set of privacy features for Neo|
Layer2||Layer2 protocols for scalability, privacy, data storage, etc|

### Application Development Support 

| Component               | Existing Projects                                            | Potentially idea or project                                  | Priority   |
| ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------- |
| Smart Contract compiler | C# compiler & library - [neo-devpack-dotnet](https://github.com/neo-project/neo-devpack-dotnet)<br />Go compiler - [neo-go](https://github.com/nspcc-dev/neo-go)<br />Python compiler - [neo-boa](https://github.com/CityOfZion/neo3-boa)<br />Java compiler -  [neow3j](https://neow3j.io/#/smart_contract_development/tutorial?id=tutorial) |                                                              |            |
| Smart Contract Library  |                                                              | Provide reusable smart contract modules, more secure smart contract templates based on recurring design patterns to simplify and to enhance the productivity of smart contract development. | **2021Q2** |
| Smart Contract Security |                                                              | Neo smart contract security libraries to identify vulnerabilities during compilation, and related smart contract auditing tools. | 2021Q3     |
| SDK                     | JavaScript - [neon-js](https://github.com/CityOfZion/neon-js)<br />Java/Android/Kotlin - [neow3j](https://neow3j.io/#/) <br />Golang - [neo-gogogo](https://github.com/neo-ngd/neo-gogogo)<br />Python - [neo-mamba](https://github.com/CityOfZion/neo-mamba) | **iOS SDK**                                                  | **2021Q2** |
| IDE Plugins             | [Neo Blockchain Toolkit](https://github.com/neo-project/neo-blockchain-toolkit/blob/master/quickstart.md) | popular IDE integration, such as Intejj, Visual Studio, GoLand, etc. | 2021Q3     |
| **Web IDE**             | [NeoCompiler Eco](https://neocompiler.io), [NeoRay](https://neoray.nel.group/#/debug), [Neo IDE](https://github.com/everstake/neo-ide) | Provide a ready to use online sandbox to write, test, deploy and manage smart contracts. | **2021Q2** |
| dev Framework           | [Neo Blockchain Toolkit](https://github.com/neo-project/neo-blockchain-toolkit), <br/>[NEO•ONE](https://neo-one.io) | Frameworks to simplify and enable highly productive development environment for smart contracts and dApp, potentially integrated with current dev infrastructures. | 2021Q3     |
| NeoFS Dev Tools         |                                                              | Tools, API or SDK to enable easy access to NeoFS features through Neo and NeoFS network, to strengthen distributed storage usage for Neo applications. | 2021Q3     |
| Tutorial                |                                                              | Interactive and on-interactive tutorials to on-board developers to the Neo stack: learn how to code on Neo, ranging from smart contract to broad dApp development. | **2021Q2** |
| Templates               |                                                              | Templates to help accelerate the development process for smart contracts and dApps. | **2021Q2** |

### Digital Asset Protocol & Infrastructure
Component|Existing Projects|Potential idea & projects|Priority
--|--|--|--
Oracle Solution||Oracle projects built using the Neo built-in oracle to provide specific functionality or features, such as price feed, randomness, bridge, etc.|**2021Q2**
DAO||DAO-as-a-Service infrastructure to support on-chain governance, voting, etc.|2021Q3
Stable Coin Protocol|                                                      ||2021Q3
Token Swap Protocol|[Flamingo swap](https://flamingo.finance/swap/tabs)</br>[O3 swap](https://o3swap.com/)||
Lending Protocol||Decentralized lending protocol to enable users to earn interest by supplying digital assets, as well as obtaining loans, etc.|**2021Q2**
 NFT marketplace，issuing platform |                               |NFT marketplace to issue, display and exchange NFT asset on Neo.|**2021Q2**

