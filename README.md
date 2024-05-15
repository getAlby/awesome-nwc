# NWC Applications [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/getAlby/awesome-nwc)

<a href="https://nwc.dev/"><img align="center" src="https://github.com/MoritzKa/assets/blob/main/nwc_logo.png" alt="awesome-nwc" title="awesome-nwc" width="600" /></a>

Curated list of awesome projects implemeting [Nostr Wallet Connect (NWC)](https://nwc.dev).

Any comments, suggestions? [Let us know](https://github.com/getAlby/awesome-nwc/issues)! We love PRs :) 

[![Discord](https://img.shields.io/badge/Join_us-d?style=social&logo=discord)](https://discord.nwc.dev/)
[![X](https://img.shields.io/badge/Follow-d?style=social&logo=X)](https://twitter.com/nwc_dev)
[![Star](https://img.shields.io/badge/Follow_this_awesome_list-f?style=social&logo=riseup&logoColor=yellow)](https://github.com/getAlby/awesome-nwc)

## Content
- [Apps](https://github.com/getAlby/awesome-nwc/blob/master/README.md#apps)
- [Developer Tools & Libraries for Apps](https://github.com/getAlby/awesome-nwc/blob/master/README.md#nwc-developer-tools--libraries-for-apps)
- [Wallets](https://github.com/getAlby/awesome-nwc/blob/master/README.md#nwc-wallets)
- [Wallet Services](https://github.com/getAlby/awesome-nwc/blob/master/README.md#nwc-wallet-services) 

## Apps

### Browsers
 - [Spring Browser](https://spring.site/) - Purpose-built browser to explore the universe of Nostr apps

### Chat
 - [0xChat](https://0xchat.com/) - Chat app built on the Nostr protocol with encrypted group chats

### Community Apps
- [Nostr Kiwi](https://nostr.kiwi/) - Place for you to share notes & curate content in communities
- [Stacker News](https://stacker.news/) - Internet communities that let you upvote content and pay you bitcoin
- [Zapddit](https://zapddit.com/) - Choose topics to follow and join communities

### Games
- [Satoshi Settlers](https://satoshisettlers.com/) - Settle and develop the blocks of Bitcoin on a shared world map
- [Zappy Bird](https://rolznz.github.io/zappy-bird/) - Super fun version of Flappy Bird

### Long-form Content Publishing
- [Habla](https://habla.news/) - Read, write, curate and monetize long form content over Nostr
- [YakiHonne](https://yakihonne.com/) - A well-designed decentralized long-form content media platform

### Music Publishing
- [Wavlake](https://www.wavlake.com/) - Music streaming app with direct contributions to creators
   
### Payment Planners
 - [ZapPlanner](https://zapplanner.albylabs.com/) - Send regular payments to your favorite publisher
 - [ZapplePay](https://www.zapplepay.com/) - Smart app to zap from any nostr client & auto-zaps

### Point of Sale 
 - [BuzzPay PoS](https://github.com/getAlby/pos) - Super simple self-custodial PoS
 - [Flash](https://paywithflash.com/) - Instant & multi-feature lightning payment gateway

### Short-form Content Publishing 
 - [Amethyst](https://github.com/vitorpamplona/amethyst) - Feature-rich Nostr client for Android
 - [Coracle](https://coracle.social/) - Web client for the Nostr protocol
 - [Damus](https://damus.io/) -  Excellent Nostr client for iOS
 - [Freerse](https://freerse.com/) - Nostr client for Android and iOS
 - [Lume](https://github.com/lumehq/lume/tree/v2.2.3) - Multi-purpose nostr client for Desktop
 - [More Speech](https://github.com/unclebob/more-speech) - A desktop client for the Nostr protocol
 - [noStrudel](https://nostrudel.ninja/) - Platform for notes and streaming over Nostr
 - [Nostter](https://nostter.app/) - Lightweight, elegant client with NWC
 - [Nostur](https://nostur.com/) - Top-notch Nostr client for iOS
 - [Primal](https://primal.net/) - Super fast Nostr client for web, Android and iOS
 - [Snort](https://snort.social/) - Feature-packed Nostr web client
 - [Whereostr](https://wherostr.social/) - Explore where your Nostr friends are located
 - [Yana](https://yana.do/) - Yet another Nostr app for web, Android and iOS but with very responsive UI

### Video Publishing
 - [Zap.Stream](https://zap.stream/) - Slick website for live streaming and chat with zaps

### Wallet Interfaces
- [Alby Browser Extension](https://getalby.com/#extension) - Connect your wallet and surf the web of bitcon apps
- [Vortex](https://www.raycast.com/saunter/vortex) - The fastest way to use bitcoin on macOS

## NWC Developer Tools & Libraries for Apps
These tools and libraries help apps to integrate the NWC protocol to support in-app bitcoin payments
- [Alby JS SDK](https://github.com/getAlby/js-sdk) - JavaScript SDK for NWC
- [Bitcoin Connect](https://github.com/getAlby/bitcoin-connect) - Easy to integrate components for web apps to for connecting to Lightning wallets and enabling [WebLN](https://www.webln.guide/)
- [rust-nostr](https://github.com/rust-nostr/nostr) - Nostr protocol implementation, SDK and FFI
- [NDK](https://github.com/nostr-dev-kit/ndk) - Nostr Development Kit
- [NWC HTTP API](https://guides.getalby.com/developer-guide/v/nostr-wallet-connect-api/building-lightning-apps/communicating-payment-requests) - HTTP API to communicate NWC payment requests without the need of websockets
- [$prism](https://www.makeprisms.com/) - API for apps to connect to wallet services

## NWC Wallets
- [Alby](https://www.getalby.com) - Bitcoin lightning wallet ready to be connected to any bitcoin app on the web and mobile
- [Cashu.me](https://wallet.cashu.me/) - eCash-based Cashu wallet PWA
- [Mutiny](https://www.mutinywallet.com) - self-custodial lightning wallet that is targeting the web browser first
- [Umbrel](https://umbrel.com/) - A beautiful home server OS for self-hosting apps and your bitcoin node
- [Start9](https://start9.com/) - Linux-based operating system optimized for running a personal server and bitcoin node

### NWC Wallet Services 
These apps have access to the APIs of the wallets they serve and let users create connection strings
- [Core Lightning](https://github.com/gudnuf/cln_nwc) - Nostr Wallet Connect plugin for CLN
- [Breez SDK](https://github.com/getAlby/nostr-wallet-connect-next) - NWC service for the Breez SDK (experimental)
- [LND](https://github.com/benthecarman/nostr-wallet-connect-lnd) - Nostr Wallet Connect for LND nodes
- [NWC](https://github.com/getAlby/nostr-wallet-connect) Wallet service to allow 3rd-party apps to connect to your wallet or node
- [Umbrel](https://github.com/getAlby/nostr-wallet-connect) Wallet service for Umbrel nodes
- [Start9](https://marketplace.start9.com/nostr-wallet-connect) Wallet service for StartOS users

## Communities Using NWC
- [Plebnet.dev](https://discord.gg/VJfNn2nby5) -A Bitcoin-centric group dedicated to shaping the future through open source Bitcoin and lightning infrastructure.

## Misc
- [Lightning Address Server](https://replit.com/@ReneAaron/NWC-Lightning-Address-Server) - Request lightning invoices from your wallet via NWC
