datalatte
=========

datalatte enables people to anonymize, tokenize and monetize their data and provides market researchers with insights and survey tools to validate their product ideas with a web3 native community.

Community Knowledge Graph (KG)
==============================

datalatte's KG data model allows users to store and easily utilize their personal data. The graph-structured data model based on small Knowledge Graphs (KGs) offers a solution to the challenges of table-structured data sets, which are not easily comprehensible and require significant resources to gain insights. The KG data model consists of the following features:

-Decentralized storage leveraging Filecoin & IPFS

-Private KGs for different entities in the SMS stored on different nodes within the Filecoin network

-Open-ended evolution by storing parent CIDs in each KG for access to previous versions

Overall, the KG data model provides a solution for storing and utilizing personal data in a decentralized and secure manner. It allows for easy access and understanding of the data through Natural Language Processing (NLP) queries and provides computational efficiency with privacy-preserving data pipelines.

Reputation tokenomics 
======================

datalatte's Reputation tokens (XPs) incentivize user participation and provide rewards for contributions to the community. XPs are EIP1155 standard and earned through various actions within the datalatte ecosystem, such as providing data for surveys or participating in community events. They can be used for a variety of purposes within the platform, including accessing premium features and participating in governance decisions, soul-bounding reputation to datalatte's PFPs (dataBarista) and many other usecases and services only accessible by XPs. 

Note that XPs are eligible to datalatte's native utility token airdrop when public launch occurs. 

Project Layout
--------------

./solidity: the core implementation of the datalatte protocol, including the KG data model and XP token logic.

./typescript: our NPM packages, which wrap the Solidity implementation and expose a JavaScript API for interacting with datalatte.

./swift: implementation of our Swift package, also wrapping the core Solidity implementation (via a C-compatible FFI), suitable for incorporating datalatte as an XCode dependency.

./design: documents describing datalatte data structures and protocols in generalized terms.

License
-------

This project is dual licensed under MIT and Apache-2.0.

MIT:[  https://www.opensource.org/licenses/mit](https://www.opensource.org/licenses/mit)

Apache-2.0:[  https://www.apache.org/licenses/license-2.0](https://www.apache.org/licenses/license-2.0)

About
-----

datalatte is a protocol for anonymizing, tokenizing, and monetizing data. Join us in building a web3 native community and discover the potential of your data!
