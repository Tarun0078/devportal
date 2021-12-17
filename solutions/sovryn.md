---
title: "Sovryn - Solutions on RSK"
description: "Sovryn is a non-custodial and permissionless smart contract-based system for Bitcoin lending, borrowing and margin trading"
tags: sovryn, rsk-solutions, rsk, defi, bitcoin
render_features: 'tables-with-borders'
layout: "rsk"
---

![sovryn-banner](/assets/img/solutions/sovryn/sovryn-banner-combined.png)

[Sovryn](https://www.sovryn.app/) is a non-custodial and permissionless smart contract based system for Bitcoin lending, borrowing and margin trading.
**Users can buy SOV with RBTC, swap and trade: DOC, BPRO, rUSDT, xUSD, and MOC tokens on Sovryn**.

Sovryn does not require you to send your Bitcoin to a centralized company, 
like BitMEX or Binance, in order to trade. 
With Sovryn, you send your BTC to a smart contract that allows you to keep custody of your private keys, 
allowing you to withdraw your funds at any time.
Sovryn is permissionless in the sense that no one can censor a transaction, 
ban your account or require you to undergo KYC before trading.

## How Sovryn Works

<div class="video-container">
  <iframe width="949" height="534" src="https://youtube.com/embed/z1iKPDXKjUo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Features

- **Swaps**: Swap frictionlessly between listed tokens. 
The Sovryn Decentralized AMM ensures no one can take advantage of you creating a trade.
Learn more about [Swaps](https://wiki.sovryn.app/en/sovryn-dapp/trading#step-1-go-to-the-sovryn-dapp)
- **Margin Trading**: Margin trading allows you to use assets in your wallet as collateral for your margin, 
to borrow more assets or to increase your initial position. Learn more about [Margin Trading](https://wiki.sovryn.app/en/sovryn-dapp/trading#margin-trading-on-sovryn)
- **Liquidity Mining**: Sovryn waves goodbye to centralised services that conventionally provide market-making. 
Fees generated by trading are distributed amongst liquidity providers as a reward, 
in exchange for facilitating trades and swaps. 
Learn more about [Liquidity Mining](https://wiki.sovryn.app/en/technical-documents/amm/AMM-FAQ).
- **Market Making**: Sovryn’s layer 2 solution operating on the [Rootstock (RSK)](https://developers.rsk.co/rsk/) Bitcoin side-chain,
facilitates the frictionless usage of financial primitives for multiple assets across multiple chains to further Satoshi’s vision of monetary sovereignty beyond simple peer to peer transactions.
Learn more about [Market Making](https://wiki.sovryn.app/en/sovryn-dapp/market-making#video-how-to-earn-by-market-making) 
- **Lending**: Earn a passive income by lending your assets directly to borrowers or to margin traders and decrease your exposure to wider market performances and fluctuations. 
Sovryn’s non-custodial solution keeps you in control of your funds, 
and you are free to withdraw your assets at any time.
Learn more about [Lending on Sovryn](https://wiki.sovryn.app/en/sovryn-dapp/lending)
- **Stake and Vote**: The Sovryn protocol has hard-coded incentives for long-term growth. 
Token holders who stake their SOV receive a pro-rata share of the revenue that the platform generates from various transaction fees when they participate in the governance of the protocol by voting.
Learn more about [Staking on Sovryn](https://wiki.sovryn.app/en/governance/staking-vesting-voting#staking-sov)


## Use cases for Sovryn users

### Stacking Sats and HyperHODLing

- _Alice_, a hodler, wants to put her BTC stack to work by lending them to a margin trade.
- _Bob_, a trader, is so bullish, he isn’t satisfied just to HODL. He wants to **HyperHODL**. 
He opens a long position on BTC, borrowing the funds from Alice.

Alice and Bob do not want to move their BTC onto a centralized service and give up control of their keys. 
Using Sovryn, Alice issues a peer to peer loan straight from her wallet and Bob trades straight from his. 
Alice is now stacking sats, and Bob is **HyperHodling** without compromising their privacy, control or ideals.

### LegoLand

- _Carol_ is building a centralized exchange.
- _David_ is building a decentralized hedging dapp.

Both Carol and David can integrate permissionlessly with the trading, 
lending and liquidity of Sovryn. 
In doing so, they gain instant access to more liquidity, 
more features and can provide greater functionality for both their users and those of Sovryn.

### Sovryn Individuals

Sovryn governance will be decentralized soon. Instead of shares, 
governed by laws and enforced by courts, 
Sovryn dequity (decentralized equity) will be governed by the blockchain and enforced by Bitcoin's POW.

## Bitocracy

The SOV Bitocracy is a distributed, 
pseudonymous governing body of stakeholders in the future of the Sovryn protocol and business.

![bitocracy](/assets/img/solutions/sovryn/bitocracy.png)

SOV token holders can make executable proposals if they possess enough voting power, 
vote on proposals during a predefined voting period and in the end evaluate the outcome. 
If successful, the proposal will be scheduled on the timelock contract. 
Only after sufficient time has passed can it be executed. 
A minimum voting power of 1% of SOV (1,000,000) is required for making a proposal as well as a minimum quorum.

In addition, SOV token holders can aggregate their governing power to a specific stakeholder (without transferring their SOV tokens) through delegation

### Bitocracy Voting

- User requests to makes a code proposal
- Governance contract checks the Staking contract to determine if the user has enough voting power
- If the user has the required amount of voting power then the proposal is accepted by the Governance contract and all users with voting power are able to vote.
- Once the voting period is over and the proposal has been voted on, 
it is directly scheduled for execution and sits in the Timelock contract. 
The timelock setting decides on the waiting time.
- At the allocated time the proposal executes on the SOVRYN protocol

## Smart Contract safety and Audits

The Sovryn protocol smart contracts are periodically assessed by independent security auditors. You can see the audits here:

- [Audit by Pessimistic, October 2020](https://sovryn.app/images/pdf/SovrynAudit2020.pdf)
- [Audit by Coinspect, December 2020](https://sovryn.app/images/pdf/Sovryn_Security_Audit_Smart_Contracts_v201218.pdf)

## Try it now!

You can find the app at [https://live.sovryn.app/](https://live.sovryn.app/)

![sovryn-live-banner](/assets/img/solutions/sovryn/sovryn-live-banner.png)

## Currencies supported by Sovryn

### Cryptocurrencies

| Symbol | Name | Network |
| --- | --- | --- |
| RBTC | [Smart Bitcoin](https://developers.rsk.co/rsk/rbtc/) | RSK |
| ETH | [Ether](https://ethereum.org/en/eth/) | Ethereum |

### Fungible tokens

| Symbol | Name | Token Standard | Network |
| --- | --- | --- | --- |
| [SOV](https://explorer.rsk.co/address/0xEfC78FC7D48B64958315949279bA181C2114abbD) | [Sovryn](https://www.sovryn.app/) | ERC20 | RSK |
| [DOC](https://explorer.rsk.co/address/0xe700691da7b9851f2f35f8b8182c69c53ccad9db) | [Dollar on Chain](https://moneyonchain.com/doc-bitcoin-stablecoin/) | ERC20 | RSK |
| [MOC](https://explorer.rsk.co/address/0x9ac7fe28967b30e3a4e6e03286d715b42b453d10) | [Money on Chain](https://moneyonchain.com/moc-governance/) | ERC20 | RSK |
| [rUSDT](https://explorer.rsk.co/address/0xef213441a85df4d7acbdae0cf78004e1e486bb96) | [USDT on RSK](https://tether.to/) | ERC20 | RSK |
| [xUSD](https://explorer.rsk.co/address/0xb5999795be0ebb5bab23144aa5fd6a02d080299f) | [USD Stablecoin](https://babelfish.money/) | ERC20 | RSK |
| [BPRO](https://explorer.rsk.co/address/0x440cd83c160de5c96ddb20246815ea44c7abbca8) | [BitPro](https://moneyonchain.com/bpro-income-for-bitcoin-holders/) | ERC20 | RSK |

## Fees

See the [Sovryn Library](https://www.sovryn.app/library) for the summary of fees.

## Documentation
- [Getting Started with Sovryn](https://wiki.sovryn.app/en/getting-started/getting-started-index)
- [Sovryn Wiki](https://wiki.sovryn.app/en/home)
- [Technical Documents](https://wiki.sovryn.app/en/technical-documents/technical-documents-index)
- [Read the Blackpaper](https://docsend.com/view/mbhvi379crhagtwp)
- [Library of DYOR](https://sovryn.app/library.html)
- [Sovryn FAQs](https://wiki.sovryn.app/en/getting-started/faq-general)

## Get in touch
- [Website](https://sovryn.app/)
- [Support/Community](mailto:community@sovryn.app)
- [Forum](https://forum.sovryn.app/)
- [Github](https://github.com/DistributedCollective)

### Socials
- [Discord](https://discord.gg/J22WS6z)
- [Telegram](https://t.me/SovrynBitcoin)
- [Twitter](https://twitter.com/SovrynBTC)