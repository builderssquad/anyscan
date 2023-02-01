# Anyscan

![Anyscan](https://anyscan.org/img/logo.svg)

Website: https://anyscan.org

Anyscan Explorer for any EVM chain

## Motivation 

Building an alternative and cheaper version of Etherscan for EVM (Ethereum Virtual Machine) chains has several motivations:

* Cost Savings: The cost of using Etherscan can be high for some users, particularly those conducting many transactions. An alternative that is less expensive can appeal to these users.
* User Experience: Some users may find the user experience of Etherscan lacking in certain areas, and building an alternative with improved UX can attract these users.
* Customization: Some users may require customized features that Etherscan doesn't provide. An alternative that offers these customization options can attract these users.

## Implementation 

Anyscan uses ReactJS, NodeJS and MongoDB. 

![Tech](https://miro.medium.com/proxy/0*hU4zJiyVwWcM0L-w.png)

List of benefits: 

* React: React is a popular and widely-used JavaScript library for building user interfaces. It provides a fast and efficient way to build complex, dynamic, and interactive interfaces with a high level of user engagement.
* MongoDB: MongoDB is a NoSQL database that is well-suited for storing large amounts of semi-structured data, such as blockchain transactions. It provides fast and flexible querying capabilities, allowing for quick and efficient retrieval of data.
* Scalability: Both React and MongoDB are highly scalable, which is important for an application like an Etherscan alternative that may be handling a large volume of data.
* Community Support: Both React and MongoDB have large and active communities, which can provide resources, tools, and support for building and maintaining the application.
* Integration: React and MongoDB can easily be integrated with other technologies, such as blockchain networks and payment systems, to provide a comprehensive solution for managing and tracking blockchain transactions.
* Overall, building an Etherscan alternative on React and MongoDB provides advantages such as scalability, community support, fast and efficient querying capabilities, and easy integration with other technologies.

In comparison Blockscout explorer uses Elixir Language (https://github.com/blockscout/blockscout) - Elixir has some advantages but there are few weaknesses. The most essential weakness is that it is hard to find, keep and extend the team of Elixir developers when Javascript does not have such problem. 

Javascript stack allows to scale a team and make features time to market. 

## Available Functionaly

In general: 

* Block explorer: Anyscan allows users to search, view, and verify transactions, blocks, and other EVM-related data on the blockchain.
* Token Tracker: Anyscan tracks and displays information about ERC-20 tokens, including their total supply, price, and market cap.
* Contract Verification: Etherscan verifies the source code of smart contracts deployed on the Ethereum blockchain, making it easier for users to inspect and understand their behavior.
* Analytics: Etherscan provides various charts and statistics related to the Ethereum network, such as network hash rate, gas price, and miner distribution.
* API: Etherscan provides an API for developers to retrieve blockchain data, including historical data and real-time updates, for use in their own applications.


In details: 

* Search: Ellasic search by text for tokens
* Operations: Read and Write actions for verified smart contracts 
* Bytecode to Opcode disassembler
* Show latest blocks and transactions, Total txns, latest blocknumber, Market capitalization, History transactions within 24h, 1 week, 1 month
* Support Api endpoints to get txn, block and tokens
* Get Transaction history
* Get Block history
* Display log events
* Display internal transactions
* ERC-20 and ERC-721 Token Transfers
* Charts and Statistics
* Detail pages (Block, Transaction, Address, Token)
* Add Comments using Disqus
* Search functionality with Block hash and number, Txn hash, Token name etc.
* Show Top accounts by coin balance
* Single smart contract verification and read/write contract.
* Add rpc on metamask
* Show holding tokens
* NFT page (NFT transactions, NFT image)


## Commin Soon Functionaly (on test stage)

* Profile easy API to obtian all tokens holded by specific address 

## Roadmap

Basically, the default plan is to make everything what is available in Etherscan.
As far we supported by projects they could apply chain specific functiality and define priorities of default tasks


* Improving user experience: Etherscan could continue to improve its user interface and user experience, making it more accessible and intuitive for users of all levels of technical expertise.
* Adding new features: Decentralized exchange (DEX) explorer, an oracle explorer, or a staking explorer, to provide a one-stop solution for blockchain users.
* Integrating with other platforms: Anyscan integration with other blockchain platforms, wallets, and decentralized applications (dApps), enabling users to interact with the Ethereum network through a unified platform.
* Tools: Anyscan offers various tools and services, such as a gas price calculator and a tool for calculating EVM address balances.
* Project Info: Ability to add token specific informaiton (website, social links)
* Debug: Integration with Remix (debug of transaction)
* Data Tools: Advanced filtering and sorting of all data
* Search: Ellasic search improvement, support of all entities 
* Facts: Token holder rich list
* State: Integration with ganache to recompute blockchain state locally and provide full web3-rpc. This will remove need to provide expensive gateway nodes and allow users to use optimized high load endpoint for Metamask, Dapps.



## Launched on chains

* Velas Mainnet (https://velascan.org) - The fastest EVM chain with 5 blocks per 2 second. Here we provide the proof that we can handle such speed
* Mantlescan Testnet (https://testnet.mantlescan.org/) - Layer 2 for ethereum with trustless L1-L2 bridge . 


## Support 

Feel free to create an Issue in this repository. Development team consider this approach as main the communication channel. 

