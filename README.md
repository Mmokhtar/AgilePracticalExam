## Google Document: https://docs.google.com/document/d/1fZMPlZUkIPmgZ5zzB1YmlkAyab8qzlsldUYdMDP4P9o/edit?usp=sharing

# AgilePracticalExam: TACoin: Part 1
## Info
 - Name: Mohamed Mokhtar Abdelrasoul
 - ID: 18P7232
 - Group: 2
 - Section: 2
 - Project Name: TACoin (Token Acquisition Coin)
 - Project Description: TACoin (Token Acquisition Coin) is a coin aimed at standardizing the creation and deployment of blockchain tokens (both fungible and non-fungible) which represent both digital and real-life assets. The main advantage of TACoin’s system is the fact that it is both HTTP-based, and does not rely on the blockchain for the code that can be implemented off the blockchain network (unlike Ethereum).

## The Teams
### Team 1: Blockchain Developers
| Name | Role | Expertise |
| - | - | - |
| Youssef Maher | Cryptocurrency Architecture Designer | C/C++ development, P2P application design, Cloud architecture design |
| Mohamed Mokhtar | Secure Code Reviewer & Penetration Tester  | P2P application development, C/C++ development, Penetration testing, Usermode exploitation, Static code analysis, Software fuzzing |
| Mazen Mostafa | Blockchain Developer & Unit Tester | Software design patterns, Unit testing, C/C++ development, Solidity development, Python development, P2P application development |
| Kareem Ayman | API Designer & Integrator | Javascript development, Python development, Web development, Cloud API design |

### Team 2: Project Documentation and Maintenance 
| Name | Role | Expertise |
| - | - | - |
| Mostafa Lotfy | Project Code Documenter | C/C++ development, C/C++ open-source code documentation, Public code comment  |
| Ahmed Salama | Public API Documenter  | Web development, Public API documentation, Python developer |
| Ahmed Salah | Blogger & Tutorial Writer | Blogging, C/C++ development, Web Development, Android development, Electron |

### Team 3: Frontend Application Developers
| Name | Role | Expertise |
| - | - | - |
| Ahmed Bakry | Mobile Application Developer | Electron, Java mobile development, Android application development |
| Mohamed Ashraf | Web Application Developer | Electron, Javascript development, Vue framework development, HTML development |
| Omar Yehia | Desktop Application Developer | React framework development, C# WinForms/Mono development, Java desktop development |
| Mina Marcus | UI Designer | Java UI design, React template design, HTML/CSS development, Multi-platform UI design |

## Possible Stakeholders
 - Cryptocurrency Traders
 - Cryptocurrency Trading Platforms
 - Token creators and distributors 
 - Token traders and owners
 - Frontend platform developers (Web/Desktop/Mobile)
 - Cyptocurrency developers
 - Cryptocurrency miners
 - Cryptocurrency miner software creators
 - Cryptocurrency mining pool managers
 - Cryptocurrency mining ASIC creation companies

## Near Vision
### Sprint 1
At the end of sprint one, a usable form of cryptocurrency should be completed. The cryptocurrency's protocol should be HTTP based, to ease the creation of web-based applications that make use of the service. To make the cryptocurrency secure, the mining process will be based on the SHA-256 hashing algorithm (same as Bitcoin). A simple cross-platform application should be made to communicate with the P2P network.

Basic outlines of the sprint:
 - Initial version of the protocol between nodes in the network with future-proofing taken into account
 - Cross-platform Web, Desktop & Mobile application with the following features:
    - Ability to create a new wallet
    - Ability to transfer TACoins to another wallet
    - Ability to view TACoin wallet balance
 - Initial CPU-based mining software

### Sprint 2
At the end of sprint two, CCtokens (centrally controlled tokens) should be introduced into the TACoin's network. CCtokens are the first addition that sets aside TACoin's network from other cryptocurrency networks. CCtokens are tokens which are completely controlled and minted by a central entity (e.g. government, company). Both fungible and non-fungible tokens are to be implemented in this sprint.

Basic outlines of the sprint:
 - Ability to create new fungible and non-fungible CCtokens
 - Ability to mint new CCtoken instances of owned CCtokens
 - Ability to view owned CCtokens
 - Ability to transfer owned CCtoken instances to other wallets
 - Ability to transfer CCtoken ownership to other accounts

## Far Vision
TACoin aims to be the main platform for the exchange of digital and physical commodities. TACoins themselves are to be used as the form of money, in the case the user wants to buy or sell tokens (instead of exchanging). Tokens can represent physiscal commodities or digital items. Types of tokens are:

| Token Type | Explanation | Example |
| - | - | - |
| Fungible centrally controlled tokens (CCtokens) | Tokens that are minted by a central entity (e.g. company), and each token has the same value as every other token | Shares in a company |
| Non-fungible centrally controlled tokens (CCtokens) | Tokens that are minted by a central entity (e.g. government), and each token does not have the same value as every other token | Unit of real-estate (apartment, house, castle... etc) |
| Fungible single-mint tokens (SMtokens) | Tokens that are minted N times (defined tby the owner at creation), and can never be minted again | Limited stock products |
| Fungible voted-mint tokens (VMtokens) | Tokens that are minted N times (defined tby the owner at creation), and can only be minted again when more than 50% of token oners vote for it to be minted | High-risk product creation |

These 4 token types provide the users of the coin multiply ways to manage many trustless real-life environments in a quick and reliable manner.

## Product Backlog
### Product Backlog Items (User Stories)
 - Epic: As a user, I would like to own and trade TACoins and tokens to ease the exchange of money and commodities. [`114 Total Story Points`]
    - Story: As a user, I would like to create a new wallet to hold my TACoins and tokens. [`13 Story Points`] \<SprintOne\>
        - Youssef Maher
        - Mazen Mostafa
        - Ahmed Bakry
    - Story: As a user, I would like to easily and securely view my wallet balance to be able to know how much TACoins and tokens I have. [`20 Story Points`] \<SprintOne\>
        - Kareem Ayman
        - Mostafa Lotfy
        - Mohamed Ashraf
    - Story: As a user, I would like to transfer TACoins to another account to easy monetary exchange. [`20 Story Points`] \<SprintOne\>
        - Mohamed Mokhtar
        - Ahmed Salama
        - Youssef Maher
        - Mina Marcus
    - Story: As a user, I would like to manage, backup and restore multiple wallets at the same time to secure my funds. [`20 Story Points`] \<SprintOne\>
        - Mohamed Mokhtar
        - Kareem Ayman
        - Omar Yehia
    - Story: As a token creator, I would like to create a new CCtoken to mint it later on. [`8 Story Points`] \<SprintTwo\>
        - Ahmed Salah
        - Omar Yehia
    - Story: As a token owner, I would like to mint an owned CCtoken to give it to other users. [`13 Story Points`] \<SprintTwo\>
        - Mazen Mostafa
        - Mina Marcus
    - Story: As a token owner, I would like to transfer ownership of my token to another user.  [`20 Story Points`] \<SprintTwo\>
        - Mina Marcus
        - Youssef Maher
        - Ahmed Salama
 - Epic: As an application developer, I would like to incorprate TAcoins and tokens into my application to provide decentralized and secure software. [`123 Total Story Points`]
    - Story: As an application developer, I would like to have clear documentation for the protocol used for communication between nodes in the network to incorporate in my own application. [`40 Story Points`]
        - Mostafa Lotfy
        - Ahmed Salama
    - Story: As an application developer, I would like to have a ready-to-use wrapper library that enables me to view, send and receive TACoins and tokens programmatically to reduce development time. [`30 Story Points`] \<SprintTwo\>
        - Mostafa Lotfy
        - Mohamed Ashraf
        - Kareem Ayman
    - Story: As an application developer, I would like to know how TACoin's network works through online articles to decide whether I should use it in my application. [`20 Story Points`]
        - Ahmed Salah
        - Ahmed Salama
    - Story: As an application developer, I would like to understand the types of tokens in the TACoin network through online articles to know which type is best for my business-case. [`13 Story Points`] \<SprintOne\>
        - Ahmed Salah
        - Mostafa Lotfy
    - Story: As an application developer, I would like to have a public forum where I can ask questions that I cannot find an answer to it through the internet to speed up my development. [`20 Story Points`] \<SprintTwo\>
        - Mina Marcus
        - Mohamed Mokhtar
        - Ahmed Bakry
 - Epic: As a miner and/or trader, I would like to start a business and gain money via the exchange of TACoins and tokens. [`Large (L)`]
    - Story: As a trader, I would like blocks in the blockchain to be quickly added so that TACoin transfers are done quickly. [`30 Story Points`]
        - Youssef Maher
        - Mohamed Mokhtar
    - Story: As a miner and/or trader, I would like to have TACoin in a public marketplace so that I can convert my TACoins into other fiat currencies. [`60 Story Points`]
        - Mina Marcus
        - Omar Yehia
        - Mohamed Ashraf
    - Story: As a miner, I would like to have GPU-based mining software to mine more TACoins in less time and with less power-consumption. [`60 Story Points`]
        - Mazen Mostafa
        - Ahmed Salah
        - Mostafa Lotfy
    - Story: As a trader, I would like to exchange TACoins and tokens directly through the blockchain network to ensure I cannot be scammed through another website. [`80 Story Points`]
        - Ahmed Bakry
        - Omar Yehia
    - Story: As a trader, I would like to know how transfers are safe and secure so that I can buy a lot TACoins with low risk. [`30 Story Points`]
        - Mazen Mostafa
        - Kareem Ayman

### Product Backlog Rationale
The items in the product backlog are ordered according to the value given to stakeholders. This value is decided according to how much it makes the cryptocurrency usable for the real-life use cases of the coin. For example, TACoins themselves are more important than tokens because the exchange of money is more common in real life than the exchange of commodities. Moreover, exchanging commodities for money (TACoin) is prioritized because it is more common than exchanging them with other commodities, so that is also prioritized.

Things to note:
 - The sprint size is initially 2 weeks
 - The average story-points per sprint is 90 story points
 - A story must be at max 30 story points before going into a sprint
 - Epics are sized anywhere from 100 to XXL, and do not follow the fibonacci sequence (can be in any range between 100 and 200)

Story points are estimated in a modified fibonacci sequence, then in the form of T-shirt sizes as follows:
 - 1:   10-20 of them can be done in a productive work day
 - 2:   6-9 of them can be done in a productive work day
 - 3:   3-6 of them can be done in a productive work day
 - 5:   2-3 of them can be done in a productive work day
 - 8:   1-2 of them can be done in a productive work day
 - 13:  Takes about 1 productive work day
 - 20:  Takes about 1-2 productive work days
 - 30:  Takes about 2-3 productive work days
 - 40:  Takes about 2-4 productive work days
 - 60:  Takes about 4-6 productive work days
 - 80:  Takes about 6-8 productive work days
 - 100: Takes about 8-10 productive work days   [`Epic Sized`]
 - 200: Takes about 10-20 productive work days  [`Epic Sized`]
 - L:   Takes about 20-40 productive work days  [`Epic Sized`]
 - XL:  Takes about 40-60 productive work days  [`Epic Sized`]
 - XXL: Takes about 60-80 productive work days  [`Epic Sized`]

\* A productive work day is meant for the whole team

# AgilePracticalExam: TACoin: Part 2

## Documents

The average story-points per sprint (for this team) is 90 story points.

The two daily Scrum documents (one for each sprint) can be found [here](https://docs.google.com/spreadsheets/d/1PmwSIqlR63wPKU5sStW_wMGMCKIjT-waAUNeVpitzqA/edit?usp=sharing): https://docs.google.com/spreadsheets/d/1PmwSIqlR63wPKU5sStW_wMGMCKIjT-waAUNeVpitzqA/edit?usp=sharing

The sprint document for sprint 2 can be found [here](https://docs.google.com/document/d/1d1KdLVx8HhLLajzjPVwmWNQXUzcDx64URwjjUd1jNdQ/edit?usp=sharing): https://docs.google.com/document/d/1d1KdLVx8HhLLajzjPVwmWNQXUzcDx64URwjjUd1jNdQ/edit?usp=sharing

## Workflow Rationale
The rules on the transitions are:
 - Create: No rules
 - Start Design: Automatically assign to current user
 - Skip Design, No Design Required: No rules
 - Finalize Design: Automatically clear the assignee field + Only the assignee can use this transition
 - Start Implementation: Automatically assign to current user
 - Found Design Flaw, Redesign: Automatically clear the assignee field + Only the assignee can use this transition
 - Found Design Flaw, Redesign: Automatically clear the assignee field + Only the assignee can use this transition
 - Send For Security Audit: Automatically clear the assignee field + Only the assignee can use this transition
 - Start Security Audit: Automatically assign to current user
 - Found Implementation Flaw, Reimplement: Automatically clear the assignee field + Only the assignee can use this transition
 - Approve Implementation: Automatically clear the assignee field + Only the assignee can use this transition
