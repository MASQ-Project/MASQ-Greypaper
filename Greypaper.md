# MASQ

## Project Greypaper

# TABLE OF CONTENTS

| Topic | Page # |
| ------ | ------ |
| Preamble – The Greypaper | [Navigate](#preamble) |
| Introduction | [Navigate](#introduction) |
| Solution – Rule of Three | [Navigate](#solution) |
| Founding Principles | [Navigate](#founding-principles) |
| Project Milestones | [Navigate](#key-goals) |
| Docker Style CLI | [Completed](#docker-cli) |
| Graphic User Interface (GUI) | [Completed](#gui) |
| Electron Desktop App | [In Progress](#electron) |
| Auto Port-Forwarding | [In Progress](#port-forward) |
| Tokenomics | [Navigate](#tokenomics)  |
| Don the MASQ & Get Involved | [Support Us](#support-us) |
| SUPPORT OUR CAUSE | [Donate](#donate) |
| References | [References](#references) |

<a id="preamble"></a>
## PREAMBLE - THE GREYPAPER

Readers may be thinking “Why is this document called a ‘Greypaper’, and not a Whitepaper?"

Through discussion over the team's combined years of experience in business, technology, cryptocurrency and project management, an interesting idea was proposed - one of the MASQ team decided that there had to be an alternative to the mainstream idea of releasing a Whitepaper.

Whitepapers are exactly what they sound like – written in black and white and often outlining definitive goals and deadlines.

This Greypaper will be a living and evolving document that can be updated on a needs-basis with accurate information. All the while providing enough starting information for readers to appreciate the overall vision and purpose of the project.

Through this, MASQ aspires to not only be transparent in their goals and intentions, but also to avoid hype, disappointment and misinformation.
 
 <a id="introduction"></a>
# INTRODUCTION

MASQ is a community-driven project aimed at solving the problem of internet censorship by repressive regimes. The project Committee is addressing this by building a decentralized mesh network which happens to also be censorship resistant.

By doing so, it will allow content available on the World Wide Web to be accessible to anyone and everyone with an internet connection, all while allowing users to both share internet freedom and have an incentive to dedicate their excess bandwidth to the network.

**MASQ intends to deliver an Open Source solution to a growing Real World set of issues through a unique approach combining:**
- Programming
- Blockchain application
- Network encryption
- Software design
- Self-healing autonomous network structures

**The Use-cases of MASQ Node and the MASQ Network are central to the whole purpose - these include:**
- providing censorship resistance from oppresive regimes
- encouraging freedom of information across the clear net, regardless of geographical location
- increasing user accessibility to 'freedom based' applications, such as cryptocurrency, open source development platforms etc
- promoting privacy of personal information

**MASQ Network’s vision is that its software attracts over 1 million users across millions of devices and creates an ecosystem of applications that leverages the decentralized mesh network.**


> “A whole world behind the MASQ”

<a id="solution"></a> 
# SOLUTION – POWER OF THREE

The software solution is made up of three design components: 

 - Encrypted - **Completed** - Node allows--and encourages--encrypted connections, but it mainly addresses operations on a lower level. It operates on standard protocols such as TLS, SSL and HTTP/S 

 - Untraceable - **Completed** - Data is sent through a multi-hop network route that changes too quickly to trace
 
 - Clandestine – **In progress** - Will hide not only the data, not only the route, but also the very fact that the user is using MASQ at all
 
Read more about these methods in detail on the [Encryption Wiki Page]

<a id="founding-principles"></a>
# FOUNDING PRINCIPLES
 
## Decentralized Governance
The MASQ team has a core group of founders and external advisors. A future governance model will be explored, which allows MASQ Network project to be fully decentralized.

There will be no CEO, and practical methods are applied to ensure no one person controls the entire project.

## Community Spirit
The MASQ team have all been born of other projects and communities - they understand that without the true spirit of ‘By the Community, for the Community” the network and thus the project will cease to exist. From these humble roots, the team want to actively grow the Community and realize the full potential that the project can bring to the modern world of internet communication.

## Privacy
MASQ intends to keep user privacy as an utmost priority, as without true privacy of the network participants, the network cannot grow to its full potential across the world to restricted countries, where access to such a solution could come with severe penalty from Government and watchdog agencies.

Similarly, members of the Committee will remain pseudo-anonymous until such time that the network will be completely immutable, and there is little to no external threat to them. Some of the Committee are willing to be openly identified.
 
<a id="key-goals"></a>
# PROJECT MILESTONES

<a id="docker-cli"></a>
### Docker-Style CLI Interface - completed, v2 undergoing further development
MASQ has developed on the skeleton behind any G/UI, and is now based on an interactive Command Line Interface, which will be adapted to be used in all further iterations of the software. This UI-Gateway interface has been implemented and allows UIs to communicate directly with the running Node instance (masqd). The interfacing itself is handled across WebSockets broadcasts, handled by UIs and node across the UI-Gateway.

A configuration file can be set up and referenced by the software Daemon, and then MASQ Node can be initialized by the user with a few simple commands on a Command Prompt in Windows, Linux or Mac

After more of the UI-Gateway infrastructure (MASQNode-UIv2) design is developed and implemented, further UI components and GUIs can be designed and built on top of the MASQ Node software for more user-friendly adoption and fully-fledged visual features.

<a id="gui"></a>
### Graphic User Interface (GUI) - completed, v2 undergoing further development
Through the power of the amazing MASQ Community, a team developed a streamlined GUI that operates by communicating through the new MASQNode-UIv2-Gateway over Websocket broadcasts and messaging.

The GUI is first a browser-based solution for Alpha and Beta type testing with community, and is being developed into further iterations of GUIs. These may be based on other platforms or languages for greater user experience and streamlined features. 

<a id="electron"></a>
### Electron Desktop App - in progress
In parallel to the browser version, an Electron-based desktop app is being developed, which can be run on the 3 main platforms - windows, MacOS and Linux.

This will be complete with new visual UX/UI and integrate new features for a better user onboarding experience

<a id="port-forward"></a>
### Auto Port-Forwarding - in progress
A major stumbling block with the software is communicating the traffic in and our of Node through user’s routers. The development team are automating this process so users will not have to configure their routers manually

### Additional Key Milestones

* Clandestine Routing

* Neighborhood Modes

* Terminal Intelligence

## MASQ Project GitHub is Open Source
MASQ developers [GitHub] start with Open Source code from Substratum (the code base was created and developed by Substratum LLC, a registered US company based in Tennessee) – under the GPLv3 license. All source code derived from Substratum is cited as such and credit given properly.

<a id="tokenomics"></a>
# Tokenomics

The MASQ ERC20 token will be a pure utility token. Its primary purpose is to provide a monetization component within the Node software to allow micro-transactions between nodes providing services to each-other within the network. These services are measured and values are individually set by the user of each Node, creating a 'free and open market' within the network itself for users to provide their bandwidth and Node routing services.

This monetization component is inherent to the security of the network, as it ensures:
- that users can both exchange a token to prove they are a reliable consumer or server of services
- reduce the likelihood of large scale network attacks such as botnets and DDoS
- 'Bad actor' Nodes or Nodes not clearing their consuming token debt will be banned or marked in a delinquent list, thus rendering them inactive Nodes

## Smart Contract
MASQ is using a clone of an OpenZeppelin ERC20 token smart contract adapted by Substratum, which was audited by Quantstamp in 2018-2019. It was modified with a single constructor to provide protection from double-spending attacks.

Our smart contract in Solidity can be view publicly on our [verified contract address](https://etherscan.io/address/0x02ba9B528425f9de08F961B88A10b03Be8B8B998) on etherscan.io

## Token Supply and Development

*The MASQ v2 utility token was announced on 17th October, 2020.
Detailed information can be immediately referenced on this [Medium](https://medium.com/masq-project/)*

**Total Token Supply: 37,500,000**

Airdrop Swapped: 1,304,570

Circulating Initial Advisor Pool: 5,000,000

Committee: 9,000,000

Development & Marketing: 22,195,430

*No further tokens will be minted or mined

## Development & Marketing Allocations:

From the 22,195,430 tokens being released, they will be allocated towards key areas of project activity:

- Marketing & Liquidity 11,500,000

- Developer Community 9,000,000

- Initial Staking Reward Pools 1,695,430

## Token Releases:

Upon minting, non-circulating tokens will be distributed from the deployer wallet (unissued supply) into the 3 relevant wallets, according to a time-release schedule

**Development and Marketing**

- Upon minting — 5,500,000*

- 1,500,000 released monthly thereafter, for 12 months

**Founders**

- Upon minting — 1,400,000**

- Released monthly thereafter, for total of 8 months

\* *(note these tokens are made available to provide v2 token liquidity to Linkswap, and staking reward programs)*

\** *(divided by founding members)*



<a id="support-us"></a>
# GET INVOLVED

>Do you have a passion for Internet Freedom?
>Freedom of Information for the world?
>Do you have knowledge of Rust, or similar programming and would like to volunteer some of your time?
>Have you simply wanted and try to test a superior alternative to VPN or Tor?

**Join our Community and Contact us!**

Get in Touch
 - [Telegram]
 - [Twitter]
 - [GitHub]
 - [Website]

<a id="donate"></a>
# SUPPORT OUR CAUSE

As all of our team members are volunteers donating our time and efforts, we will rely on donations from our community to help fund hosting, development, website services and other project expenses

ETH address for any donations from our wonderful community:

[masq.eth](https://masq.eth) - ENS

[Donate ETH directly](https://etherdonation.com/d?to=0x27d9A2AC83b493f88ce9B4532EDcf74e95B9788d&amount=0.02)

BTC - ```bc1qnsm0eqt9z9228n7hqc6a0g9dns84vsg3whnmsh```
 
<a id="references"></a>
## REFERENCES

**OpenZeppelin Token Contracts:**
- [MIT License](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/LICENSE)
- [Contract Library](https://github.com/OpenZeppelin/openzeppelin-contracts)
- [ERC20 Tokens](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/master/contracts/token/ERC20)


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job)

   [Telegram]: <https://t.me/MASQ_ai>
   [Twitter]: <https://twitter.com/MASQ_ai>
   [GitHub]: <https://github.com/MASQ-Project>
   [Website]: <https://MASQ.ai>
   [Encryption Wiki Page]: https://github.com/MASQ-Project/Node/wiki/Encryption-Methods-Explained
