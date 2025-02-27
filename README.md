# NWC Applications [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/getAlby/awesome-nwc)

<a href="https://nwc.dev/"><img align="center" src="https://github.com/getAlby/awesome-nwc/blob/master/nwc_logo.png" alt="awesome-nwc" title="awesome-nwc" width="600" /></a>

Curated list of awesome projects implemeting [Nostr Wallet Connect (NWC)](https://nwc.dev).

Any comments, suggestions? [Let us know](https://github.com/getAlby/awesome-nwc/issues)! We love PRs :) 

[![Discord](https://img.shields.io/badge/Join_us-d?style=social&logo=discord)](https://discord.nwc.dev/)
[![X](https://img.shields.io/badge/Follow-d?style=social&logo=X)](https://twitter.com/nwc_dev)
[![Star](https://img.shields.io/badge/Follow_this_awesome_list-f?style=social&logo=riseup&logoColor=yellow)](https://github.com/getAlby/awesome-nwc)

## What is NWC?
NWC is an open protocol to be implemented by bitcoin lightning wallets and any app to add bitcoin payment functionality.
Users connect wallets instantly – no Nostr account required. Apps orchestrate payments between these wallets without ever touching funds. 

#### Learn More
- [nwc.dev](https://nwc.dev)
- [NIP-47](https://github.com/nostr-protocol/nips/blob/master/47.md)
- [NWC interoperability tracker](https://github.com/nostrability/nostrability/issues/77)

## Content
- ⚡ [NWC Wallets](https://github.com/getAlby/awesome-nwc/blob/master/README.md#nwc-wallets)
- 📱 [Apps](https://github.com/getAlby/awesome-nwc/blob/master/README.md#apps)
- 👥 [Communities Using NWC](https://github.com/getAlby/awesome-nwc/blob/master/README.md#communities-using-nwc)
- 🛠️ [Developer Tools & Libraries for Apps](https://github.com/getAlby/awesome-nwc/blob/master/README.md#nwc-developer-tools--libraries)
- 🧩 [Protocols](https://github.com/getAlby/awesome-nwc/blob/master/README.md#protocols)


## NWC Wallets
- [Alby Hub](https://albyhub.com/) - Self-custodial lightning node with wallet and most seamless NWC service
- [Bankify](https://supertestnet.github.io/bankify/) - Turn any cashu mint into a lightning wallet with NWC support
- [Cashu.me](https://wallet.cashu.me/) - eCash-based Cashu wallet PWA
- [Coinos](https://coinos.io/) - Free custodial web wallet and payment page
- [LNbits](https://lnbits.com/) - Powerful suite of bitcoin tools that has Nostr Wallet Connect plugin
- [LN Node](https://doc.nostrassets.com/micronode-early-access) - Innovative service designed to simplify the setup and management of a lightning node
- [Minibits](https://www.minibits.cash/) - eCash wallet with a focus on performance and usability
- [Mutiny](https://www.mutinywallet.com) - Self-custodial lightning wallet that is targeting the web browser first
- [Primal](https://primal.net/) - Custodial wallet integrated with Primal's mobile Nostr client
- [Rizful](https://rizful.com/) - Instant, disposable Lightning nodes, optimized for education
- [Unraid](https://unraid.net/) - Operating system for self-hosted servers, apps and storage

#### Embedded Operating Systems
Those below support at least one of NWC wallets in their official appstores:
- [CasaOS](https://casaos.io/) - Open-source personal cloud system
- [Raspiblitz](https://raspiblitz.org/) - Bitcoin & Lightning Fullnode running on a RaspberryPi
- [Start9](https://start9.com/) - Linux-based operating system optimized for running a personal server and bitcoin node
- [Umbrel](https://umbrel.com/) - A beautiful home server OS for self-hosting apps and your bitcoin node
- [Unraid](https://unraid.net/) - Operating system for self-hosted servers and network-attached storage

#### Cloud Hosting of NWC nodes
- [Alby Cloud](https://getalby.com/pricing) - 1-click cloud deployment of Alby Hub that comes with a lightning address
- [Nodana](https://nodana.io/) - 1-click deployment of Alby Hub, LNbits (with NWC) and other services in the cloud
- [Eggstr](https://www.eggstr.com/) - Easy deployment of Nostr & Bitcoin apps with own domain

#### Lightning Backends
The following nodes or lightning backends can be used by at least one of the NWC wallets:
- [Breez SDK](https://github.com/getAlby/nostr-wallet-connect-next) - Experimental
- [Cashu](https://github.com/getAlby/hub) - Experimental
- [Greenlight](https://github.com/getAlby/glalby) - Greenlight Rust Go bindings
- [LND](https://github.com/benthecarman/nostr-wallet-connect-lnd) - Nostr Wallet Connect for LND nodes
- [LDK](https://github.com/getAlby/ldkalby) - LDK Rust Go bindings (WIP)
- [phoenixd](https://github.com/getAlby/hub) - Nostr Wallet Connect for phoenixd

#### NWC Wallet Services 
The following apps are NWC wallet services with access to the APIs of the wallets they serve and let users create connection strings:
- [Core Lightning NWC Plugin](https://github.com/gudnuf/cln_nwc) - NWC plugin for CLN
- [LNbits NWC Service](https://github.com/SamSamskies/lnbits-nwc-service) - Nostr Wallet Connect service using LNbits API (experimental)
- [Strike NWC Service](https://github.com/SamSamskies/strike-nwc-service) - NWC service using Strike API (experimental)

## Apps

#### AI
 - [Unleashed.chat](https://unleashed.chat/) - Chat interface to open-source LLM models, file support and DVMs

#### Crowdfunding
 - [Geyser](https://geyser.fund/) - Crowdfunding ideas, projects and product sales, p2p with bitcoin

#### Education
- [Kanbanstr](https://www.kanbanstr.com/) - Kanban boards over Nostr, with zaps
- [PlebDevs](https://plebdevs.com/) - Online courses on Bitcoin & Lightning code development
- [Pull that up, Jamie!](https://www.pullthatupjamie.ai/) - Search engine powered with AI

#### Finance, Accounting & Payment Tools
 - [BitcoinLink](https://www.bitcoinlink.app/) - Create URL vouchers to send sats from your wallet
 - [Bringin](https://bringin.xyz/) - Sell bitcoin from your wallet directly to IBAN accounts
 - [BTCPay Server](https://btcpayserver.org/) - Open-source payment processor
 - [BuzzPay PoS](https://github.com/getAlby/pos) - Super simple self-custodial PoS
 - [Clams](https://clams.tech/) - Dedicated accounting platform for your wallet
 - [Flash](https://paywithflash.com/) - Instant & multi-feature lightning payment gateway
 - [ZapPlanner](https://zapplanner.albylabs.com/) - Send regular payments to your favorite publisher
 - [ZapplePay](https://www.zapplepay.com/) - Smart app to zap from any nostr client & auto-zaps

#### Games
- [Satoshi Settlers](https://satoshisettlers.com/) - Settle and develop the blocks of Bitcoin on a shared world map
- [Zappy Bird](https://rolznz.github.io/zappy-bird/) - Super fun version of Flappy Bird

#### Live Streaming
- [HiveTalk](https://hivetalk.org/) - Videocalls, messaging and screensharing with Nostr login and zaps
- [Corny Chat](https://cornychat.com/) - Audio & chat rooms with zaps, over Nostr
- [Zap.Stream](https://zap.stream/) - Slick website for live streaming and chat with zaps

#### Long-form Content Publishing
- [Bitcoin Lightning Publisher](https://wordpress.org/plugins/bitcoin-lightning-publisher/) - A Wordpress plugin to accept donations and set paywalls on websites
- [Habla](https://habla.news/) - Read, write, curate and monetize long form content over Nostr
- [Highlighter](https://highlighter.com/) - Highlighter stands out by offering creators true ownership of their audience
- [YakiHonne](https://yakihonne.com/) - A well-designed decentralized long-form content media platform

#### Messengers
 - [0xChat](https://0xchat.com/) - Chat app built on the Nostr protocol with encrypted group chats

#### Music
- [Wavlake](https://www.wavlake.com/) - Music streaming app with direct contributions to creators

#### Social Media, Short-form Content 
 - [Amethyst](https://github.com/vitorpamplona/amethyst) - Feature-rich Nostr client for Android
 - [Coracle](https://coracle.social/) - Web client for the Nostr protocol
 - [Damus](https://damus.io/) -  Excellent Nostr client for iOS
 - [Freerse](https://freerse.com/) - Nostr client for Android and iOS
 - [FreeFrom](https://freefrom.space/) - Closed-source, twitter like client for Androis and iOS
 - [Lume](https://github.com/lumehq/lume/tree/v2.2.3) - Multi-purpose nostr client for Desktop
 - [More Speech](https://github.com/unclebob/more-speech) - A desktop client for the Nostr protocol
 - [Nostr Kiwi](https://nostr.kiwi/) - Place for you to share notes & curate content in communities
 - [NoStrudel](https://nostrudel.ninja/) - Platform for notes and streaming over Nostr
 - [Nostur](https://nostur.com/) - Top-notch Nostr client for iOS
 - [Nostter](https://nostter.app/) - Lightweight, elegant client with NWC
 - [Olas](https://testflight.apple.com/join/2FMVX2yM) - Instagram-like Nostr app for iOS
 - [Primal](https://primal.net/) - Fast and easy Nostr client for web, Android and iOS
 - [Snort](https://snort.social/) - Feature-packed Nostr web client
 - [Stacker News](https://stacker.news/) - Internet communities that let you upvote content and pay you bitcoin
 - [Whereostr](https://wherostr.social/) - Explore where your Nostr friends are located
 - [Yana](https://yana.do/) - Yet another Nostr app for Android and iOS
 - [Zapddit](https://zapddit.com/) - Choose topics to follow and join communities

#### Tipping Bots
 - [ThunderTip](https://github.com/d4rp4t/ThunderTip) - Telegram tipping bot via your own connected wallet
 - [Zap Bot](https://www.makeprisms.com/apps) - Discord tipping bot via your own connected wallet
 - [ZapGram](https://t.me/zap_gram_bot ) - Bitcoin Lightning wallet in Telegram

#### Wallet Interfaces
- [Alby Account](https://www.getalby.com) - Web wallet interface and lightning address to NWC wallets with ability to log in with OAuthto many apps (eg. Podcasting 2.0)
- [Alby Browser Extension](https://getalby.com/#extension) - Connect your wallet and surf the web of bitcon apps
- [Alby Go](https://albygo.com/) - Slick mobile interface with multi wallet support
- [Brick Wallet](https://github.com/supertestnet/brick-wallet) - A web frontend for NWC
- [Nostr Pay](https://github.com/aniketambore/nostr_pay) - Simple Android wallet connecting to your NWC wallet [_not maintained_]
- [Vortex](https://www.raycast.com/saunter/vortex) - [Raycast](https://www.raycast.com/) extension, the fastest way to use bitcoin on macOS
- [Zeus](https://zeusln.com/) - Mobile multi-wallet with embedded node, LNDhub and NWC connections (_from 0.10_)


#### Miscellaneous
 - [Bullish Bulletin](https://bullishbulletin.vercel.app/) - Post a message on a public board
 - [Nostrcheck Server](https://nostrcheck.me/) - Comprehensive toolbox for Nostr, with NIP-05 registration, file uploads, gallery, profile management and more
 - [Spring Browser](https://spring.site/) - Purpose-built browser to explore the universe of Nostr apps
 - [Zapper](https://zapper.fun/) - Bulk zap payments, to any Nostr event
 - [Zapstore](https://zapstore.dev) - Open, permissionless app store with zaps


## Communities Using NWC
- [**NWC.dev Discord**](https://discord.nwc.dev/) - Discord channel for developers building apps and wallets with Nostr Wallet Connect
- [Alby Discord](https://discord.getalby.com/) - Users, friends and team of Alby, with NWC as preferred app<>wallet connection protocol
- [Bitcoin Design Discord](https://discord.gg/K7aQ5PErht) - Open source community of Bitcoin designers
- [Dwadzieścia Jeden Telegram](https://t.me/dwadziesciajeden) - Community of Polish bitcoiners
- [Plebnet Discord](https://discord.gg/VJfNn2nby5) - A Bitcoin-centric group dedicated to shaping the future through open source Bitcoin and lightning infrastructure.


## NWC Developer Tools & Libraries
These tools and libraries help apps to integrate the NWC protocol and enable in-app payments
- [$prism](https://www.makeprisms.com/) - API for apps to connect to wallet services
- [Alby JS SDK](https://github.com/getAlby/js-sdk?tab=readme-ov-file#nostr-wallet-connect-documentation) - JavaScript SDK for apps to handle NWC connection strings
- [Bitcoin Connect](https://github.com/getAlby/bitcoin-connect) - Easy to integrate components for web apps that let users connect their lightning wallets with a full payment flow UX
- [Dart Package](https://pub.dev/packages/nwc) - A Dart package that simplifies the integration of Nostr Wallet Connect into client applications
- [Flutter Package](https://github.com/kumulynja/nwc_wallet) - A Flutter package that takes care of the wallet service side of the NWC
- [Lightning Address Server](https://replit.com/@ReneAaron/NWC-Lightning-Address-Server) - Request lightning invoices from your wallet via NWC
- [NDK](https://github.com/nostr-dev-kit/ndk) - Nostr Development Kit
- [NWC HTTP API](https://guides.getalby.com/developer-guide/v/nostr-wallet-connect-api/building-lightning-apps/communicating-payment-requests) - HTTP API to communicate NWC payment requests without the need of websockets
- [nwcjs](https://github.com/supertestnet/nwcjs) - Vanilla Javascript library
- [NWC Tester (Simple)](https://getalby.github.io/nwc-tester/) - Test NWC Connection Secrets
- [NWC Tester (Advanced)](https://supertestnet.github.io/nwc_tester/) - Check NWC Connection Secrets' permissions, perform events
- [Python3 library](https://github.com/supertestnet/python_nwc)
- [React Native (Expo)](https://github.com/getAlby/nwc-react-native-expo) - An example of using Alby JS SDK (Nostr Wallet Connect) in a React Native Expo project
- [Rust Nostr](https://github.com/rust-nostr/nostr) - Nostr protocol implementation, SDK and FFI
- [Dart NDK](https://pub.dev/packages/ndk) - Nostr Development Kit for Dart/Flutter

## Protocols
Protocols built on top, or interoperable with NWC
- [LN Link](https://docs.lnfi.network/lnfi-products/ln-node/ln-link) - Extenstion of NWC for Taproot assets
- [UMA Auth](https://docs.uma.me/uma-auth/introduction) - Extends NWC to simplify the UX of connecting a wallet (using OAuth 2.0), and add cross-currency payments
- [Nostr Wallet Auth](https://github.com/nostr-protocol/nips/pull/851?ref=blog.mutinywallet.com) - Protocol allowing to initiate NWC connections from the app instead of from NWC wallets

