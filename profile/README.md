[Datalatte](https://www.datalatte.com)
=========

<p align="center">
    <img src="https://www.datalatte.com/imgs/datalatte.svg">
</p>
<p align="center">
    <a href="https://discord.com/invite/saUmuZ3Rrw">
        <img src="https://img.shields.io/discord/308323056592486420?logo=discord"
            alt="chat on Discord"></a>
    <a href="https://twitter.com/intent/follow?screen_name=DATALATTE_">
        <img src="https://img.shields.io/twitter/follow/DATALATTE_?style=social&logo=twitter"
            alt="follow on Twitter"></a>
</p>

Datalatte offers market researchers insights and survey tools to help them verify their product ideas with a web3 native community while enabling users to anonymize, tokenize, and monetize their data.

[Community Knowledge Graph (KG)](https://github.com/datalatte-ai/Knowledge-graph-storage-on-filecoin)
==============================

Datalatte's KG data model allows users to store and easily utilize their personal data. The graph-structured data model based on small Knowledge Graphs (KGs) offers a solution to the challenges of table-structured data sets, which are not easily comprehensible and require significant resources to gain insights. The KG data model consists of the following features:

-Decentralized storage leveraging Filecoin & IPFS

-Private KGs for different entities in the SMS stored on different nodes within the Filecoin network

-Open-ended evolution by storing parent CIDs in each KG for access to previous versions

Overall, the KG data model provides a solution for storing and utilizing personal data in a decentralized and secure manner. It allows for easy access and understanding of the data through Natural Language Processing (NLP) queries and provides computational efficiency with privacy-preserving data pipelines.

[Reputation tokenomics](https://github.com/datalatte-ai/EIP-1155-XP-Contract)
======================

Datalatte's Reputation tokens (XPs) incentivize user participation and provide rewards for contributions to the community. XPs are EIP1155 standard and earned through various actions within the Datalatte ecosystem, such as providing data for surveys or participating in community events. They can be used for a variety of purposes within the platform, including accessing premium features and participating in governance decisions, soul-bounding reputation to Datalatte's PFPs (dataBarista) and many other usecases and services only accessible by XPs. 

Note that XPs are eligible to Datalatte's native utility token airdrop when public launch occurs. 

Project Layout
--------------

> ./Solidity: the core implementation of the Datalatte protocol, including the XP token logic.

> ./JavaScript: our NPM packages, which wrap the Solidity implementation and expose a JavaScript API for interacting with Datalatte.

> ./Vue: our client side framework that handles most of the work as our goal is to do everything on the client side. 

> ./design: documents describing Datalatte data structures and protocols in generalized terms.

License
-------

This project is dual licensed under MIT and Apache-2.0.

MIT:[  https://www.opensource.org/licenses/mit](https://www.opensource.org/licenses/mit)

Apache-2.0:[  https://www.apache.org/licenses/license-2.0](https://www.apache.org/licenses/license-2.0)

About
-----

Datalatte is a protocol for anonymizing, tokenizing, and monetizing data. Join us in building a web3 native community and discover the potential of your data!
