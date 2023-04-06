[Datalatte](https://www.datalatte.com)
=========

<p align="center">
    <img src="https://www.datalatte.com/imgs/datalatte.svg">
</p>
<p align="center">
    <a href="https://discord.com/invite/saUmuZ3Rrw">
        <img src="https://img.shields.io/discord/308323056592486420?logo=discord"
            alt="chat on Discord"></a>
    <a href="https://twitter.com/intent/follow?screen_name=datalatteAi">
        <img src="https://img.shields.io/twitter/follow/datalatteAi?style=social&logo=twitter"
            alt="follow on Twitter"></a>
</p>

Datalatte is a two-sided dApp that enables people to anonymize, tokenize, and monetize their data, while providing researchers and organizations with survey-based insights to develop and improve their products.

The components building our MVD (Minimum Viable Decentralization) are:

[dataNFT as a survey](https://github.com/datalatte-ai/ocean-wrapper-dataNFT-as-a-survey)
==============================

A python library wrapper repository of ocean protocol to publish a survey a dataNFT. 

This repository includes documenation on different components for:

- Data NFT publishing on ocean market
- DataToken minting 
- fixed-price listing 

Additional micro-services: 
- IPFS storage for surveyquestion.json and surveyresponse.json
- surveyresponse.json auditor
- survey response binder


[ Public Survey Smart Contract 📝🔗](https://github.com/datalatte-ai/ocean-wrapper-dataNFT-as-a-survey)
==============================

- Ocean smart contracts interaction: Ocean DataNFT Factory, Ocean DataToken Factory, On-chain Metadata Store
- Stakeholders: Survey publisher, data owner, Datalatte
- Functions: Initialization, User Responses

Additional services: Surveyresponse.json binder, survey response audit, Chainlink function oracle

[ Public Survey SC + Bounty Pool 💰🏆 📝🔗](https://github.com/datalatte-ai/ocean-wrapper-dataNFT-as-a-survey)
==============================

- Functions: Initialization, Bounty Distribution

[ Private Survey SC 🔒📈 💰🏆 📝🔗](https://github.com/datalatte-ai/ocean-wrapper-dataNFT-as-a-survey)
==============================

- Stakeholders: Survey publisher, data owner, Datalatte
- Added functions to Survey SC Functions: Initialization, Encryption & Timelock, Decryption & Publication
Additional services: Chainlink oracle


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
