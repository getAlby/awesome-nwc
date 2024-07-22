# NWC Applications [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/getAlby/awesome-nwc)

<a href="https://nwc.dev/"><img align="center" src="https://github.com/getAlby/awesome-nwc/blob/master/nwc_logo.png" alt="awesome-nwc" title="awesome-nwc" width="600" /></a>

Curated list of awesome projects implemeting [Nostr Wallet Connect (NWC)](https://nwc.dev).

Any comments, suggestions? [Let us know](https://github.com/getAlby/awesome-nwc/issues)! We love PRs :) 

[![Discord](https://img.shields.io/badge/Join_us-d?style=social&logo=discord)](https://discord.nwc.dev/)
[![X](https://img.shields.io/badge/Follow-d?style=social&logo=X)](https://twitter.com/nwc_dev)
[![Star](https://img.shields.io/badge/Follow_this_awesome_list-f?style=social&logo=riseup&logoColor=yellow)](https://github.com/getAlby/awesome-nwc)

## What is NWC
NWC is an open protocol to be implemented by bitcoin lightning wallets and any app to add bitcoin payment functionality.
Users connect wallets instantly – no Nostr account required. Apps orchestrate payments between these wallets without ever touching funds. 

## Content
- [Apps](https://github.com/getAlby/awesome-nwc/blob/master/README.md#apps)
- [Developer Tools & Libraries for Apps](https://github.com/getAlby/awesome-nwc/blob/master/README.md#nwc-developer-tools--libraries-for-apps)
- [Wallets](https://github.com/getAlby/awesome-nwc/blob/master/README.md#nwc-wallets)
- [Wallet Services](https://github.com/getAlby/awesome-nwc/blob/master/README.md#nwc-wallet-services) 

## Apps

#### Accounting
 - [Clams](https://clams.tech/) - Dedicated accounting platform for your wallet

#### Browsers
 - [Spring Browser](https://spring.site/) - Purpose-built browser to explore the universe of Nostr apps

#### Chat
 - [0xChat](https://0xchat.com/) - Chat app built on the Nostr protocol with encrypted group chats
 - [Corny Chat](https://cornychat.com/) - Audio & chat rooms with zaps, over Nostr
 - [ThunderTip](https://github.com/d4rp4t/ThunderTip) - Telegram tip bot with your own wallet 

#### Community Apps
- [Nostr Kiwi](https://nostr.kiwi/) - Place for you to share notes & curate content in communities
- [Stacker News](https://stacker.news/) - Internet communities that let you upvote content and pay you bitcoin
- [Zapddit](https://zapddit.com/) - Choose topics to follow and join communities

#### Games
- [Satoshi Settlers](https://satoshisettlers.com/) - Settle and develop the blocks of Bitcoin on a shared world map
- [Zappy Bird](https://rolznz.github.io/zappy-bird/) - Super fun version of Flappy Bird

#### Long-form Content Publishing
- [Habla](https://habla.news/) - Read, write, curate and monetize long form content over Nostr
- [YakiHonne](https://yakihonne.com/) - A well-designed decentralized long-form content media platform
- [Highlighter](https://highlighter.com/) - Highlighter stands out by offering creators true ownership of their audience

#### Music Publishing
- [Wavlake](https://www.wavlake.com/) - Music streaming app with direct contributions to creators
   
#### Finance & Payment Planners
 - [BitcoinLink](https://www.bitcoinlink.app/) - Create URL vouchers to send sats from your wallet
 - [ZapPlanner](https://zapplanner.albylabs.com/) - Send regular payments to your favorite publisher
 - [ZapplePay](https://www.zapplepay.com/) - Smart app to zap from any nostr client & auto-zaps
 - [Bringin](https://bringin.xyz/) - Sell bitcoin from your wallet directly to IBAN accounts

#### Point of Sale 
 - [BTCPay Server](https://btcpayserver.org/) - Open-source payment processor
 - [BuzzPay PoS](https://github.com/getAlby/pos) - Super simple self-custodial PoS
 - [Flash](https://paywithflash.com/) - Instant & multi-feature lightning payment gateway

#### Short-form Content Publishing 
 - [Amethyst](https://github.com/vitorpamplona/amethyst) - Feature-rich Nostr client for Android
 - [Coracle](https://coracle.social/) - Web client for the Nostr protocol
 - [Damus](https://damus.io/) -  Excellent Nostr client for iOS
 - [Freerse](https://freerse.com/) - Nostr client for Android and iOS
 - [Freefrom](https://freefrom.space/) - Closed-source, twitter like client for Androis and iOS
 - [Lume](https://github.com/lumehq/lume/tree/v2.2.3) - Multi-purpose nostr client for Desktop
 - [More Speech](https://github.com/unclebob/more-speech) - A desktop client for the Nostr protocol
 - [noStrudel](https://nostrudel.ninja/) - Platform for notes and streaming over Nostr
 - [Nostter](https://nostter.app/) - Lightweight, elegant client with NWC
 - [Nostur](https://nostur.com/) - Top-notch Nostr client for iOS
 - [Primal](https://primal.net/) - Super fast Nostr client for web, Android and iOS
 - [Snort](https://snort.social/) - Feature-packed Nostr web client
 - [Whereostr](https://wherostr.social/) - Explore where your Nostr friends are located
 - [Yana](https://yana.do/) - Yet another Nostr app for web, Android and iOS but with very responsive UI

#### Video Publishing
 - [Zap.Stream](https://zap.stream/) - Slick website for live streaming and chat with zaps

#### Wallet Interfaces
- [Alby Browser Extension](https://getalby.com/#extension) - Connect your wallet and surf the web of bitcon apps
- [Nostr Pay](https://github.com/aniketambore/nostr_pay) - Simple Android app to connect for your NWC wallet
- [Vortex](https://www.raycast.com/saunter/vortex) - The fastest way to use bitcoin on macOS

## NWC Developer Tools & Libraries for Apps
These tools and libraries help apps to integrate the NWC protocol and enable in-app payments
- [Alby JS SDK](https://github.com/getAlby/js-sdk?tab=readme-ov-file#nostr-wallet-connect-documentation) - JavaScript SDK for apps to handle NWC connection strings
- [Bitcoin Connect](https://github.com/getAlby/bitcoin-connect) - Easy to integrate components for web apps that let users connect their lightning wallets with a full payment flow UX
- [rust-nostr](https://github.com/rust-nostr/nostr) - Nostr protocol implementation, SDK and FFI
- [NDK](https://github.com/nostr-dev-kit/ndk) - Nostr Development Kit
- [NWC HTTP API](https://guides.getalby.com/developer-guide/v/nostr-wallet-connect-api/building-lightning-apps/communicating-payment-requests) - HTTP API to communicate NWC payment requests without the need of websockets
- [$prism](https://www.makeprisms.com/) - API for apps to connect to wallet services
- [React Native (Expo)](https://github.com/getAlby/nwc-react-native-expo) - An example of using Alby JS SDK (Nostr Wallet Connect) in a React Native Expo project
- [Dart Package](https://pub.dev/packages/nwc) - A Dart package that simplifies the integration of Nostr Wallet Connect into client applications.
- [Flutter Package](https://github.com/kumulynja/nwc_wallet) - A Flutter package that takes care of the wallet service side of the NWC.

## NWC Wallets
- [Alby](https://www.getalby.com) - Bitcoin lightning wallet ready to be connected to any bitcoin app on the web and mobile
- [Boardwalk Cash](https://boardwalkcash.com/) - Dollar-denominated Ecash and lightning wallet
- [Cashu.me](https://wallet.cashu.me/) - eCash-based Cashu wallet PWA
- [LN Node](https://doc.nostrassets.com/micronode-early-access) - Innovative service designed to simplify the setup and management of a lightning node
- [Mutiny](https://www.mutinywallet.com) - self-custodial lightning wallet that is targeting the web browser first
- [Start9](https://start9.com/) - Linux-based operating system optimized for running a personal server and bitcoin node
- [Umbrel](https://umbrel.com/) - A beautiful home server OS for self-hosting apps and your bitcoin node

The following apps are NWC wallet services with access to the APIs of the wallets they serve and let users create connection strings:
- [Core Lightning](https://github.com/gudnuf/cln_nwc) - NWC plugin for CLN
- [Breez SDK](https://github.com/getAlby/nostr-wallet-connect-next) - NWC service for the Breez SDK (experimental)
- [LNbits](https://github.com/SamSamskies/lnbits-nwc-service) - Nostr Wallet Connect service using LNbits API (experimental)
- [LND](https://github.com/benthecarman/nostr-wallet-connect-lnd) - Nostr Wallet Connect for LND nodes
- [NWC](https://github.com/getAlby/nostr-wallet-connect) - Open-source wallet service to allow 3rd-party apps to connect to your wallet or node
- [Start9](https://marketplace.start9.com/nostr-wallet-connect) - Wallet service for StartOS users
- [Strike](https://github.com/SamSamskies/strike-nwc-service) - NWC service using Strike API (experimental)
- [Umbrel](https://github.com/getAlby/nostr-wallet-connect) - Wallet service for Umbrel nodes

## Communities Using NWC
- [NWC.dev](https://discord.nwc.dev/) - Discord channel for developers building apps and wallets with Nostr Wallet Connect 
- [Plebnet.dev](https://discord.gg/VJfNn2nby5) - A Bitcoin-centric group dedicated to shaping the future through open source Bitcoin and lightning infrastructure.

## Misc
- [Lightning Address Server](https://replit.com/@ReneAaron/NWC-Lightning-Address-Server) - Request lightning invoices from your wallet via NWC
