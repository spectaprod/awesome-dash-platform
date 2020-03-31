# Awesome Dash Platform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Useful resources for using [Dash Platform](https://dashdevs.org) and building things on top of it

_This list is for projects, tools, or pretty much any things related to Dash Platform that are totally_ **awesome**_. This is for products which are already awesome - if you have plans for cool stuff to do with Dash, you should build it, and then link it here. If you have an idea for an awesome thing to do with Dash, a good place to ask about it might be in [ipfs/apps](https://github.com/ipfs/apps) or [ipfs/notes](https://github.com/ipfs/notes)._

## Table of Contents

- [Contribute](#contribute-to-this-list)
- [Articles](#articles)
- [DAPI](#dapi)
- [Dapps](#dapps)
- [Docs](#docs)
- [Tools](#tools)
- [Videos](#videos)
- [Bounties](#bounties)
- [Discussions](#discussions)
- [License](#license)

## Contribute to this list!

Everyone is welcome to submit their new Dash Platform item, but it will be accepted only if it meets our [content policy](https://github.com/andyfreer/awesome-dash-platform/blob/master/POLICY.md).

Readme and the website are automatically generated. In order to add an element to this list, you need to modify the files in `/data` and then run  `make build` before publishing your pull request. Read [contributing guidelines](https://github.com/andyfreer/awesome-dash-platform/blob/master/CONTRIBUTING.md) to learn how to do so.


## Articles

- 2020-03-18: [Announcing the Release of Dash Platform v0.11](https://blog.dash.org/announcing-the-release-of-dash-platform-v0-11-d1b7238ed0e6) - Dash Blog
- 2019-12-30: [Announcing the Release of Dash Platform on Evonet](https://blog.dash.org/announcing-the-release-of-dash-platform-on-evonet-c5a94dee0e59) - Dash Blog
- 2019-12-30: [Long-Awaited Dash Evolution Platform Released on Testnet](https://dashnews.org/long-awaited-dash-evolution-platform-released-on-testnet-with-developer-documentation-hub/) - Dash News
- 2019-12-18: [Edge Wallet Highlights Dash Evolution Update](https://dashnews.org/edge-wallet-highlights-dash-evolution-update-skeptical-on-store-of-value-analysis/) - Dash News
- 2019-12-09: [Ryan Taylor Explains Unique Pain Point Dash Platform Solves for Consumers and Merchants](https://dashnews.org/ryan-taylor-explains-unique-pain-point-dash-platform-solves-for-consumers-and-merchants/) - Dash News
- 2019-11-16: [Dash developers announced the timeline of  Evolution platform release](https://www.fxstreet.com/cryptocurrencies/news/dash-developers-announced-the-timeline-of-evolution-platform-release-201911161943) - FX Street
- 2019-10-17: [Introducing the Platform Chain](https://blog.dash.org/introducing-the-platform-chain-982fe6aea67f) - Dash Blog
- 2019-05-20: [An Introduction to Dash Platform, DAPI, and Drive](https://blog.dash.org/an-introduction-to-dash-platform-dapi-and-drive-9d080d6e89c9) - Dash Blog

## DAPI

- [Connecting to Evonet](https://dashplatform.readme.io/docs/tutorial-connecting-to-evonet) - The purpose of this tutorial is to walk through the steps necessary to access Dash's Decentralized API (DAPI)
- [Create and Fund a Wallet](https://dashplatform.readme.io/docs/tutorial-create-and-fund-a-wallet) - This tutorial explains how to generate a new wallet, retrieve an address from it, and transfer test funds to the address from a faucet.
- [DashJS](https://dashevo.github.io/DashJS/#/) - Connect to Dash from a Browser / NodeJS Server using Dash's Decentralized-API
- [Register a Name for an Identity](https://dashplatform.readme.io/docs/tutorial-register-a-name-for-an-identity) - The purpose of this tutorial is to walk through the steps necessary to register a Dash Platform Name Service (DPNS) name.
- [Register an Identity](https://dashplatform.readme.io/docs/tutorial-register-an-identity) - Identities serve as the basis for interactions with Dash Platform. The purpose of this tutorial is to walk through the steps necessary to register a user identity.
- [Retrieve Documents](https://dashplatform.readme.io/docs/tutorial-retrieve-documents) - In this tutorial we will retrieve some of the current data from a data contract.
- [Send Funds](https://dashplatform.readme.io/docs/tutorial-send-funds) - Once you have a wallet and some funds, another common task is sending Dash to an address.
- [Submit Documents](https://dashplatform.readme.io/docs/tutorial-submit-documents) - Data is stored in the form of Documents which are entities encapsulated in a state transition before being submitted to DAPI.

## Dapps

- [Dash Chrome-Wallet](https://github.com/readme55/Dash-Chrome-Wallet) - Chrome-Extension Cryptocurrency Wallet for the Dash EvoNet-Testnet environment (WIP)
- [DashPay](https://github.com/dashevo) - Mobile Dapp enabling Username based payments and Platform authentication (WIP)
- [DPNS](https://dashplatform.readme.io/docs/explanation-dpns) - Name Service Dapp providing Usernames for Dash Blockchain Identities (LIVE) [Source](https://github.com/dashevo/js-dpp/tree/v0.11-dev/schema/identity)
- [Masternode Polling Tool](https://chat.dashdevs.org) - Polling Masternodes for Decisions (IDEA)
- [MemoDash](https://github.com/dashevo/memo-dash-prototype) - Decentralized Twitter Alternative Dapp in REACT (BOUNTY)
- [Merchant Directory](https://app.dashnexus.org/proposals/dash-platform-merchant-directory/overview) - Merchant Directory Dapp (PROPOSAL)

## Docs

- [Core Developer Guide](https://dashcore.readme.io/docs/core-guide-introduction) - Detailed docs for working with Dash's internal Core Network
- [Dash User Docs](https://docs.dash.org/en/stable/) - User documentation for understanding general Dash concepts & usage
- [DashJS](https://dashevo.github.io/DashJS) - JavaScript library for Dapp developers on Dash Platform
- [Platform Developer Guide](https://dashplatform.readme.io/) - Guides and documentation to help you start working with Dash Platform as quickly as possible, as well as support if you get stuck.
- [Tendermint Core Docs](https://docs.tendermint.com/master/) - Docs for Tendermint, the BFT protocol used on Layer 2 in conjunction with Masternode quorums

## Tools

- [Block Explorer (Core)](http://devnet-evonet-28309188.us-west-2.elb.amazonaws.com:3001/insight/) - Core Network Blocks (Layer 1), for Currency, Identity and Credit Transactions [Source](https://github.com/dashevo/insight-ui)
- [Block Explorer (Platform)](https://github.com/dappforce/dappforce-tendermint-explorer) - Masternode Network blocks (Layer 2), for State Transitions
- [DAPI Client Python](https://github.com/thephez/dapi-client-py) - A very basic, read-only DAPI client.
- [Dash Masternode Deployment Tool](https://github.com/strophy/dash-masternode-docker) - This tool deploys a Dash masternode to the current host.
- [Dash Network Deploy](https://github.com/dashevo/dash-network-deploy) - This tool assists in deploying and managing Dash networks.
- [EvoNet Faucet](http://devnet-evonet-28309188.us-west-2.elb.amazonaws.com/) - Get EvoNet coins to test with
- [Platform Console](https://dash-platform-console.now.sh/identities) - Explore & Update Platform State (WIP) [Source](https://github.com/denlb/dash-platform-console)

## Videos

- 2020-01-06: [DASH EvoNet Review](https://www.youtube.com/watch?v=Vs3cjw51o4w) - Today we are taking a look at the Dash Evonet which is a development network provided for experimentation and evaluation of Dash Platform features.
- 2019-12-11: [DashPay Wallet - Brian Foster](https://www.youtube.com/watch?v=wkBFcWbsXtQ) - Brian Foster describes the development and features of the "Evolution" DashPay Wallet
- 2019-12-11: [Dash Evolution Open House Analysis | Tao & Amanda LIVE!](https://www.youtube.com/watch?v=PFIOm9KO5sA) - Join the team from Dash Core Group for an open discussion of the upcoming Dash Platform and Dashpay-enabled wallets release, commonly known as Evolution.
- 2019-12-11: [Introduction To Dash Platform - Dana Alibrandi](https://www.youtube.com/watch?v=WNoMSP0nPDQ) - Dana Alibrandi introduces Dash Platform and its functionality
- 2019-12-09: [Dash Evolution Open House 2019](https://www.youtube.com/watch?v=ie7fJMw5WIo) - Join the team from Dash Core Group for an open discussion of the upcoming Dash Platform and Dashpay-enabled wallets release, commonly known as Evolution.
- 2019-11-22: [What is Dash Platform?](https://www.youtube.com/watch?v=8jI7Nt3lILs) - The Cryptoviser analysis of Dash Platform
- 2019-10-31: [Understanding Dash Platform and Chain - Expert Followup](https://www.youtube.com/watch?v=Vb3KwVxPE84) - Christopher sits down with Dash Product Manager Dana Alibrandi and Dash Core Developer Ivan Shumkov to get into more technical details about the Dash Platform's concepts
- 2019-10-12: [Dash Platform - Dana Alibrandi and Ivan Shumkov](https://www.youtube.com/watch?v=5Q1cCt9v1U0) - Dana Alibrandi, Dash Platform Product Owner, Dash Core Group Ivan Shumkov, Dash Platform Engineer, Dash Core Group
- 2019-07-12: [Dash Podcast 112 - Intro To Dash Platform feat. Dana Alibrandi](https://www.youtube.com/watch?v=VcLdDmt9TSM) - Intro To Dash Platform feat. Dana Alibrandi Product Owner from Dash Core Group
- 2019-04-19: [Dash Podcast 100 - Feat. Ivan Shumkov](https://www.youtube.com/watch?v=gUDN62ePWms) - Intro To Dash Platform feat. Dana Alibrandi Product Owner from Dash Core Group
- 2018-05-15: [Platform Prototype Demo 3](https://www.youtube.com/watch?v=ZJVW9iUHqLg) - Chuck, Suba, and Chris from Dash Core demonstrate three exploratory designs for the Dashpay DAP demo home screen
- 2018-04-25: [Platform Prototype Demo 2](https://www.youtube.com/watch?v=EtYax7iz4hU) - Dash Core developers Joshua, Chuck, and Suba demonstrate the 2nd prototype of the first Dash decentralized application, show off some mobile app designs, and demonstrate the VMN block explorer.
- 2018-03-16: [Platform Prototype Demo 1](https://www.youtube.com/watch?v=gbjYhZT2Ulc) - Dash Core developers Joshua and Chuck demonstrate a prototype of the first Dash decentralized application and show some technical details of the Dash Evolution platform

## Bounties

- [C# DAPI Bindings](https://trello.com/c/6qVaLYmo/16-c-dapi-bindings) 
- [Community EvoNet MN Hosting](https://trello.com/c/rzjc7eY1/26-community-evonet-mn-hosting) 
- [Create Hello World Tutorial](https://trello.com/c/wEawlJb2/23-create-hello-world-tutorial) 
- [DashDevs.org Work](https://trello.com/c/iN58zxs0/19-dashdevsorg-work) 
- [Golang DAPI Bindings](https://trello.com/c/ErETMzMX/21-golang-dapi-bindings) 
- [Memo Dash Dapp](https://trello.com/c/Kzn8JX12/12-memo-dash-dapp) 
- [Platform Console](https://trello.com/c/Xezls3IC/9-platform-console-fork-to-dashjs-and-finish-sandbox-prototype) 
- [Python DAPI Bindings](https://trello.com/c/o7Rf2ETW/15-python-dapi-bindings) 
- [Python DAPI Bindings](https://trello.com/c/o7Rf2ETW/15-python-dapi-bindings) 
- [RUST DAPI Bindings](https://trello.com/c/7EwpLxKZ/13-rust-bindings) 
- [Tendermint Block Explorer](https://trello.com/c/ezAfj6lG/18-tendermint-block-explorer) 

## Discussions

* [Join us on Discord!](https://chat.dashdevs.org)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
