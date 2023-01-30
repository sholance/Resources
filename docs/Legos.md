---
title : "Legos List"
description: "List of Legos Useful to ODC"
lead: ""
date: 2023-1-30T22:26:54+01:00
lastmod: 2023-1-30T22:26:54+01:00
draft: false
images: []
---

### Legos 

Below is a list curated to highlight some of the Legos that useful to the ODC Landscape. 

legos are literally "pieces that can be joined together to make models of many different objects" and more importantly Legos in this context are said to be **components of the data mesh which have consistent input and outputs which can easily duplicate analysis and other repeated functions used to better empower communities collective decision making. [more](https://gov.gitcoin.co/t/public-goods-legos-roadmap/12546#what-do-these-legos-actually-look-like-3) and [more](https://gov.gitcoin.co/t/anti-sybil-legos/12265#what-does-a-lego-look-like-1) on Legos** 


### List of Useful Legos

**⛓️ On-Chain History:**
- [Link](https://gov.gitcoin.co/t/using-fdd-fraud-defense-tools-in-a-protocol-future/12526#wallet-legos-10)
- How It Works: This Lego should return a Yes or No value if a user engaged in certain web3 activities in a specific timeframe.
- As a Grant Lego: *Specific Web3 activites and timeframe could be customized by round operator and used as an individual lego or combined with other legos in detecting Sybils, when this lego is combined with several other Legos, a more robust and comprehensive result can be gotten.*
- As a Donation Lego: *With better understanding a donor's wallet behaviour, sybil behaviours can be easily detected and attackers foound out. It is proposed that this lego be also customizable for any specific time span.*

**🧮 High Frequency Trading:**
- [Link](https://gov.gitcoin.co/t/using-fdd-fraud-defense-tools-in-a-protocol-future/12526#wallet-legos-10)
- How It Works: *Returns the Range of wallet activity timestamps over number of transactions*
- Grant Lego: *The range of wallet activity timestamps over the number of transactions; often an indicator of bot-control or other automatic wallet-vetting scripts; The threshold for this metric is yet to be determined and may be set dynamically based on community averages. This dynamic approach allows for a more accurate representation of the range of wallet activity timestamps and a more effective way of detecting potential bot activity.*

**🍥 Money-Mixer:**
- [Link](https://gov.gitcoin.co/t/using-fdd-fraud-defense-tools-in-a-protocol-future/12526#wallet-legos-10)
- How It Works: *Returns Boolean if a user has iteracted with known money-mixers.*
- As a Grant Lego: *Checks for grant recipient addresses interaction with known money-mixer services. Could be a bad signal if grant recipient addresses have interacted with money-mixers.*
- As a Donation Lego: *Checks for the donation wallet’s address interaction with known money-mixers. Might not be a particularly significant signal for donors.*

**💬 Social Presence:** 
- [Link](https://gov.gitcoin.co/t/using-fdd-fraud-defense-tools-in-a-protocol-future/12526#wallet-legos-10)
- How It Works: *Returns Boolean.*
- Grant Lego: *Evaluates the relationship between the amount of unique donations received and the number of twitter followers. Returns a boolean if a particular project is within 1 standard deviation from the ratio of the number of Twitter followers for a specific grant to the number of unique donations received for that grant.*

**👯‍♂️ Funding Wallet Is Unique:** 
- [Link](https://gov.gitcoin.co/t/using-fdd-fraud-defense-tools-in-a-protocol-future/12526#wallet-legos-10)
- How It Works: *Returns Boolean for uniqueness of funding wallet*
- Grant Lego: *This can be utilized with other indicators that could determine duplicate grant creation more. Could be used as a proof to indicate high risk money-mixing activity.*

Resources
[Legos for Prioritization](https://docs.google.com/spreadsheets/d/1sMgm3cg3pfMvRbmrteknpu44qsyuQlvn3vizgwnOgOU/edit#gid=2020378185)
[Gitcoin Discord](https://discord.gg/gitcoin)
[Open Data COmmunity Discord](https://discord.gg/Ye3QrWf6fG)

More resources on Legos 
[Public Goods Lego Roadmap](https://gov.gitcoin.co/t/public-goods-legos-roadmap)
[Anti Sybil Legos: What does a lego look like](https://gov.gitcoin.co/t/anti-sybil-legos/12265#what-does-a-lego-look-like-1)
[Lego Docs](https://github.com/Fraud-Detection-and-Defense/lego-docs)
[Using FDD in a protocol](https://gov.gitcoin.co/t/using-fdd-fraud-defense-tools-in-a-protocol-future/12526)
