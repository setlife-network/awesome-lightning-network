
# ⚡ awesome-lightning-network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Lightning Network resources, apps, and libraries

## Contents

- [⚡ awesome-lightning-network ](#-awesome-lightning-network-)
  - [Contents](#contents)
  - [Lightning Network Protocol](#lightning-network-protocol)
    - [Implementations](#implementations)
    - [Specifications / White Papers](#specifications--white-papers)
  - [Applications](#applications)
    - [Desktop Interfaces](#desktop-interfaces)
    - [Web Interfaces](#web-interfaces)
    - [Command Line Interfaces](#command-line-interfaces)
    - [Mobile applications](#mobile-applications)
    - [Explorers](#explorers)
    - [Misc](#misc)
  - [Developer Resources](#developer-resources)
    - [Libraries](#libraries)
    - [Tutorials](#tutorials)
    - [Example Projects](#example-projects)
    - [Simulators](#simulators)
  - [Learning Resources](#learning-resources)
    - [Talks](#talks)
    - [Books](#books)
  - [Community](#community)
    - [IRC](#irc)
  - [Related Lists](#related-lists)
  - [Contribute](#contribute)
  - [License](#license)

---

## Lightning Network Protocol

### Implementations

| Name            | Description                                    | Link                                                       |
|-----------------|------------------------------------------------|------------------------------------------------------------|
| LND             | Lightning Network Daemon (Golang)              | [Link](https://github.com/lightningnetwork/lnd)            |
| eclair          | A Scala implementation of the Lightning Network | [Link](https://github.com/ACINQ/eclair)                    |
| lit             | Lightning Network node software (Golang)       | [Link](https://github.com/mit-dci/lit)                     |
| c-lightning     | A Lightning Network implementation in C        | [Link](https://github.com/ElementsProject/lightning)       |
| rust-lightning  | A Lightning Network implementation in Rust [Incomplete] | [Link](https://github.com/rust-bitcoin/rust-lightning) |
| lightning-onion | Onion Routed Micropayments for the Lightning Network | [Link](https://github.com/lightningnetwork/lightning-onion) |

### Specifications / White Papers

| Name                                                        | Link                                                        |
|-------------------------------------------------------------|------------------------------------------------------------|
| Lightning Network BOLTs                                     | [Link](https://github.com/lightning/bolts)                 |
| LND API Reference                                           | [Link](https://lightning.engineering/api-docs/api/lnd/)    |
| Lightning Network White Paper                               | [Link](https://lightning.network/lightning-network-paper.pdf) |
| Scalable Funding of Bitcoin Micropayment Channel Networks   | [Link](https://nakamotoinstitute.org/static/docs/scalable-funding-of-bitcoin-micropayment-channel-networks.pdf) |

---

## Applications

### Desktop Interfaces

| Name           | Description                                                               | Link                                                       |
|----------------|---------------------------------------------------------------------------|------------------------------------------------------------|
| eclair-node-gui| Cross-platform desktop GUI for Lightning                                  | [Link](https://github.com/ACINQ/eclair)                    |
| zap-desktop    | Lightning Network desktop application                                     | [Link](https://github.com/LN-Zap/zap-desktop)              |
| spark-wallet   | Minimal GUI for c-lightning; available as web, mobile and desktop application | [Link](https://github.com/shesek/spark-wallet)             |
| Node-launcher  | Quickly install BTC and launch the LN desktop app                         | [Link](https://github.com/lightning-power-users/node-launcher) |

### Web Interfaces

| Name           | Description                                                               | Link                                                       |
|----------------|---------------------------------------------------------------------------|------------------------------------------------------------|
| Joule          | A browser extension for lnd that enables payments and other interactions with lightning apps (similar to MetaMask) | [Link](http://lightningjoule.com)                         |
| lncli-web      | Light-weight web client for the lnd daemon written in NodeJS / Angular    | [Link](https://github.com/mably/lncli-web)                 |
| Ride The Lightning | Web Client for LND Daemon written in NodeJS /  Angular                   | [Link](https://github.com/Ride-The-Lightning/RTL)          |
| LND-For-WP    | WordPress plugin for managing & using your LND Node; [WordPress Plugin Directory](https://wordpress.org/plugins/lnd-for-wp/) | [Link](https://github.com/rstmsn/lnd-for-wp)               |
| ThunderHub    | Web UI for managing (multiple) LND Nodes written in TypeScript / React    | [Link](https://github.com/apotdevin/thunderhub)            |

### Command Line Interfaces

| Name           | Description                                                               | Link                                                       |
|----------------|---------------------------------------------------------------------------|------------------------------------------------------------|
| bos – Balance of satoshis | Advanced tool for LND with powerful rebalancing options and telegram bot support written in NodeJS | [Link](https://github.com/alexbosworth/balanceofsatoshis)  |
| charge-lnd     | policy based fee manager for LND                                          | [Link](https://github.com/accumulator/charge-lnd)          |
| lntop          | TUI-based interactive channels dashboard for Unix systems                 | [Link](https://github.com/edouardparis/lntop)              |
| rebalance-lnd  | A script that can be used to balance lightning channels of a lnd node     | [Link](https://github.com/C-Otto/rebalance-lnd)            |
| suez           | Tool for pretty printing and optimizing Lightning Network channels        | [Link](https://github.com/prusnak/suez)                    |

### Mobile applications

| Name                       | Description                                    | Link                                                       |
|----------------------------|------------------------------------------------|------------------------------------------------------------|
| Bitcoin Lightning Wallet   | An Android based Lightning Network compatible wallet based on Eclair ([testnet version](https://play.google.com/store/apps/details?id=com.lightning.wallet)) | [Link](https://play.google.com/store/apps/details?id=com.lightning.walletapp) |
| Muun                        | A Lightning Network wallet for Android ([Github](https://github.com/muun/apollo)) | [Link](https://muun.com/)                                  |
| Shockwallet                | A Lightning SuperApp and Decentralized Social Network | [Link](https://shockwallet.app)                           |
| Zebedee                    | Bitcoin gaming wallet                            | [Link](https://zbd.gg)                                     |

### Explorers

| Name                       | Description                                    | Link                                                       |
|----------------------------|------------------------------------------------|------------------------------------------------------------|
| 1ML                        | 1ML explorer (mainnet + testnet)               | [Link](https://1ml.com/)                                   |
| Amboss.space               | Amboss.space explorer                          | [Link](https://amboss.space/)                              |
| Bitcoin Exchange Rate      | Lightning network explorer (testnet and mainnet)| [Link](https://bitcoinexchangerate.org/lightning)          |
| List of explorers          | meta list of visualisers and metrics sites     | [Link](https://gist.github.com/bretton/798ec38165ffabc719d91e0f4f67552d) |
| Robtex Bitcoin Lightning Explorer | Robtex Bitcoin Lightning Explorer (mainnet) | [Link](https://www.robtex.com/lightning/node/)             |

### Misc

| Name                     | Description                                                                                                                         | Link                                                        |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| lightning-address-nodejs | Simple server for your personal Lightning Address                                                                                   | [Link](https://github.com/mefatbear/lightning-address-nodejs) |
| bitcoin-kit-makefile| Easy installation of full bitcoin and lightning nodes from sources                                                                  | [Link](https://github.com/Perlover/bitcoin-kit-makefile)     |
| ifpaytt                  | IFTTT (If Pay Then This) based on Lightning payments; [Blog Post](https://blockstream.com/2018/03/27/ifpaytt-brings-lightning-micropayments-to-ifttt.html) | [Link](https://github.com/ElementsProject/ifpaytt)          |
| lightning-faucet         | A faucet for the Lightning Network                                                                                                  | [Link](https://github.com/lightninglabs/lightning-faucet)    |
| lightning-jukebox        | A Lightning powered Jukebox; [Blog Post](https://blockstream.com/2018/03/28/lightning-jukebox-offers-a-fun-end-to-our-week-of-lapps.html) | [Link](https://github.com/ElementsProject/lightning-jukebox) |
| LightningBuddy           | Twitter relay for Lightning JSON-RPC interface                                                                                      | [Link](https://github.com/elaineo/LightningBuddy)            |
| LightningTip             | LND focused Lightning Tip tool, embed in webpage                                                                                    | [Link](https://github.com/michael1011/lightningtip)          |
| ln-tip-slack             | Lightning [Slack](https://slack.com/) Tipbot                                                                                        | [Link](https://github.com/CryptoFR/ln-tip-slack)             |
| nanotip                  | Lightning Tip Box (based on c-lightning); [Blog Post](https://blockstream.com/2018/03/24/tipping-on-lightning-with-nanotip-lapp.html) | [Link](https://github.com/ElementsProject/nanotip)          |
| Satoshis.Stream          | Earn Lightning sats as a podcaster, easily                                                                                          | [Link](https://satoshis.stream)                             |

---

## Developer Resources

### Libraries

| Name                          | Description                                                                                          | Link                                                        |
|-------------------------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| FileBazzar                    | Sell digital files with Lightning                                                                    | [Link](https://github.com/ElementsProject/filebazaar)       |
| Lighter                       | LN node wrapper for c-lightning, eclair and LND (Python)                                            | [Link](https://gitlab.com/inbitcoin/lighter)                |
| lightning-charge-client-js    | JavaScript client for lightning-charge                                                               | [Link](https://github.com/ElementsProject/lightning-charge-client-js) |
| lightning-charge-client-php   | PHP client for lightning-charge                                                                      | [Link](https://github.com/ElementsProject/lightning-charge-client-php) |
| lightning-charge              | A simple drop-in solution for accepting lightning payments (Javascript)                              | [Link](https://github.com/ElementsProject/lightning-charge) |
| lightning-integration         | Lightning Integration Testing Framework                                                              | [Link](https://github.com/cdecker/lightning-integration)    |
| lightning-payencode           | Minimal QR-code-ready encoding for requesting lightning payments                                     | [Link](https://github.com/rustyrussell/lightning-payencode) |
| lightning-php                 | PHP client for direct RPC-based access to the c-lightning daemon                                     | [Link](https://github.com/thorie7912/lightning-php)         |
| LightningJ                    | LND Integration API for Java                                                                         | [Link](http://www.lightningj.org/)                          |
| ln-paywall                    | Go middleware for monetizing APIs on a per-request basis with Lightning                              | [Link](https://github.com/philippgille/ln-paywall)          |
| ln-service                   | Lightning REST Service                                                                              | [Link](https://github.com/alexbosworth/ln-service)          |
| lncall                       | LND implementation of paypercall                                                                     | [Link](https://github.com/michael1011/lncall)               |
| lnrpc                        | Auto-generated LND RPC interface with Typescript type definition support                             | [Link](https://github.com/RadarTech/lnrpc)                  |
| lseed                        | A DNS seed for the Lightning Network                                                                 | [Link](https://github.com/cdecker/lseed)                    |
| paypercall                   | Charge for HTTP APIs on a per-per-call basis with Lightning                                          | [Link](https://github.com/ElementsProject/paypercall)       |
| webln                        | An app library & set of standards for communication between apps and Lightning clients in the browser (similar to Web3) | [Link](https://github.com/wbobeirne/webln) |
| woocommerce-gateway-lightning | A WooCommerce gateway for lightning payments                                                         | [Link](https://github.com/ElementsProject/woocommerce-gateway-lightning) |
| wordpress-lightning-publisher | Lightning Publisher for WordPress                                                                    | [Link](https://github.com/ElementsProject/wordpress-lightning-publisher) |
| glightning                    | Golang based plugin for c-lightning                                                                  | [Link](https://github.com/niftynei/glightning)              |
| lightningd-gjson-rpc          | [gjson](https://github.com/tidwall/gjson)-based RPC client for c-lightning                           | [Link](https://github.com/fiatjaf/lightningd-gjson-rpc)     |
| Sitzprobe                    | A c-lightning plugin that actively sends test payments through the lightning network allowing finding and/or deprecating channels for the payments | [Link](https://github.com/niftynei/sitzprobe) |
| get-lightning-paid           | A Flask REST API to generate lightning invoices and payment confirmations                            | [Link](https://github.com/conscott/get-lightning-paid)      |

### Tutorials

| Name                                                                                  | Link                                                        |
|---------------------------------------------------------------------------------------|-------------------------------------------------------------|
| Setting up a local Lightning cluster                                                  | [Link](http://dev.lightning.community/tutorial/01-lncli/index.html) |
| Using the LND gRPC Client                                                             | [Link](http://dev.lightning.community/tutorial/03-rpc-client/index.html) |
| Integrating Lightning into a server-side web application                              | [Link](http://dev.lightning.community/tutorial/04-webapp-integration/index.html) |
| How to use a Python gRPC Client with LND                                              | [Link](http://dev.lightning.community/guides/python-grpc/)  |
| How to use a Javascript gRPC Client with LND                                          | [Link](http://dev.lightning.community/guides/javascript-grpc/) |
| Chaincode Labs Lightning Application Residency Videos                                 | [Link](https://lightningresidency.com/#videos)              |
| Setting up and Testing LND with the Testnet Lightning Faucet                          | [Link](http://lightning.community/lnd/faucet/2017/01/19/lightning-network-faucet/) |
| How to Send Payments via CLI on the Lightning Network                                 | [Link](https://andrewgriffithsonline.com/blog/guide-to-make-lightning-network-pay) |

---

### Example Projects

| Name                  | Description                                                                                     | Link                                                        |
|-----------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| lightning-coindesk    | An example news app exemplifying Lightning Network micropayments integration                   | [Link](https://github.com/lightninglabs/lightning-coindesk) |

### Simulators

| Name                | Description                                                                                     | Link                                                        |
|---------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| CLoTH               | A simulator in C. See paper [CLoTH: a Simulator for HTLC Payment Networks](https://arxiv.org/abs/1812.09940) by Conoscenti et al. Code not released. |
| Blyskavka           | A simulator in Java. See paper [Split Payments in Payment Networks](https://www.researchgate.net/publication/327470777_Split_Payments_in_Payment_Networks_ESORICS_2018_International_Workshops_DPM_2018_and_CBT_2018_Barcelona_Spain_September_6-7_2018_Proceedings) by Piatkivskyi and Nowostawski. Code not released. |
| LNTrafficSimulator  | -                                                                                               | [Link](https://github.com/ferencberes/LNTrafficSimulator)   |

## Learning Resources

| Name                                                    | Description  | Link                                                        |
|---------------------------------------------------------|--------------|-------------------------------------------------------------|
| Lightning FAQ                                           | -            | [Link](https://medium.com/@AudunGulbrands1/lightning-faq-67bd2b957d70) |
| Lightning Network Bitcoin Wiki                          | -            | [Link](https://en.bitcoin.it/wiki/Lightning_Network)       |
| Radar ION - Guide to joining the Lightning Network      | -            | [Link](https://ion.radar.tech)                              |
| Hashed Timelock Contracts                               | -            | [Link](https://en.bitcoin.it/wiki/Hashed_Timelock_Contracts) |
| LN as a Directed Graph; Single-Funded Channel Topology  | (Slides)     | [Link](https://docs.google.com/presentation/d/1G4xchDGcO37DJ2lPC_XYyZIUkJc2khnLrCaZXgvDN0U/edit?pref=2&pli=1#slide=id.g85f425098_0_2) |
| How to Do "2-of-3 Multisig Contract" Equivalent on Lightning | (From LN Mailing List) | [Link](https://lists.linuxfoundation.org/pipermail/lightning-dev/2016-January/000403.html) |
| uselightning.network                                     | -            | [Link](https://uselightning.network/)                       |

### Talks

| Name                                                                    | Duration    | Link                                                        |
|-------------------------------------------------------------------------|-------------|-------------------------------------------------------------|
| Lightning Network Deep Dive with Laolu "Roasbeef" Osuntokun             | [48:10]     | [Link](https://www.youtube.com/watch?v=b_szGaaPPFk)         |
| SF Bitcoin Devs Seminar: Scaling Bitcoin to Billions of Transactions Per Day | [54:40] | [Link](https://www.youtube.com/watch?v=8zVzw912wPo)         |
| Bitcoin, Lightning, and Streaming Money                                 | [27:38]     | [Link](https://www.youtube.com/watch?v=gF_ZQ_eijPs)         |
| Lightning and the Importance of Layer Two                                | [14:15]     | [Link](https://www.youtube.com/watch?v=3PcR4HWJnkY)         |
| Bitcoin Q&A: The Lightning Network                                       | [7:55]      | [Link](https://www.youtube.com/watch?v=vPnO9ExJ50A)         |


### Books

| Title                                                      | Description  | Link                                                         |
|------------------------------------------------------------|--------------|--------------------------------------------------------------|
| Mastering the Lightning Network (LN)                       | -            | [Link](https://github.com/lnbook/lnbook)                     |
| Mastering Bitcoin, 2nd Edition                             | -            | [Link](http://shop.oreilly.com/product/0636920049524.do)     |
| Bitcoin and Lightning Network on Raspberry Pi              | -            | [Link](https://www.apress.com/gp/book/9781484255216)         |

## Community

| Resource                                          | Description  | Link                                                         |
|---------------------------------------------------|--------------|--------------------------------------------------------------|
| Lightning Network Twitter Feed                    | -            | [Link](https://twitter.com/lightning)                        |
| Lightning Network Mailing List                    | -            | [Link](https://lists.linuxfoundation.org/mailman/listinfo/lightning-dev) |
| Lightning Labs Blog                               | -            | [Link](https://blog.lightning.engineering/)                  |
| Lightning Discord                                 | -            | [Link](https://discord.gg/sm2rfS7)                           |
| Lightning Wiki                                    | -            | [Link](https://lightningwiki.net)                            |

### IRC

| Channel                                             | Description  | Link                                                         |
|-----------------------------------------------------|--------------|--------------------------------------------------------------|
| #lightning-dev (on Freenode) - Lightning protocol development | - | [Link](https://webchat.freenode.net/?channels=lightning-dev&uio=d4) |
| Channel Archive                                     | -            | [Link](https://botbot.me/freenode/lightning-dev/)            |
| #lnd (on Freenode) - Lightning only version of #bitcoin-commits | - | [Link](https://webchat.freenode.net/?channels=lnd&uio=d4)   |

## Related Lists

| Name            | Description  | Link                                                         |
|-----------------|--------------|--------------------------------------------------------------|
| awesome-bitcoin | -            | [Link](https://github.com/igorbarinov/awesome-bitcoin)       |

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.