![](\headerimage.png)

## 소 개

스팀(Steem) 은 공개적으로 액세스할 수 있고 한번 생성하면 변경할 수 없는 콘텐츠를 지원하기 위해 빠르고 수수료가 없는 디지털 토큰(STEEM)[^2] 기반의 확장 가능한 블록체인 프로토콜[^1]을 제공합니다. 사람들은 글쓰기나 큐레이팅 등의 창작 활동을 통해 화폐를 벌 수 있으며, 이를 "지능 증명" (Proof-of-Brain) 이라고 부릅니다. 이 프로토콜의 구성요소인 블록체인과 토큰(token)은 보안, 불변성, 장기 존속성(longevity)을 위해 상호 의존하고 있기 때문에 서로 꼭 필요한 존재입니다. 스팀은 수 년간 성공적으로 운영되어 왔으며 현재는 트랜잭션 처리 수에서 비트코인과 이더리움을 넘어섰습니다.[^3]

다른 블록체인과 비교했을때, 스팀은 자체적인 보상 체계를 가지고 있고, 평문 형태로 변경 불가능하게 저장된 콘텐츠에 공개적으로 접근할 수 있는 최초의 데이터베이스라는 점에서 특별합니다. 이같은 특징 덕분에 스팀은 수많은 인터넷 애플리케이션이 참여하고 데이터를 공유하는 공개 출판 플랫폼이 되었으며, 스팀은 가장 가치있는 콘텐츠에 공헌하는 사람들에게 보상을 제공합니다.

가상 화폐 영역에서 STEEM은 비트코인과 이더리움과 비교했을 때 "스마트", "소셜"이라는 고유의 특성을 갖고 있습니다. 이러한 특성은 두 가지 새로운 토큰 기능에서 비롯된 것입니다. 첫 번째 기능은 콘텐츠 창작과 큐레이션을 장려하는 토큰 풀(보상 풀이라고 부른다) 이고, 두 번째 기능은 콘텐츠의 가치를 평가하고 콘텐츠에 토큰을 분배하기 위해 집단 지성을 활용하는 투표(voting) 시스템입니다. 이 두 가지 고유한 특성들이 결합된 것을 지능 증명(Proof-of-Brain) 이라고 부르며, 이것은 커뮤니티 참여자에게 토큰을 분배하기 위해 사람들의 작업이 필요하다는 것을 강조하는 작업 증명(Proof-of-Work)[^4]을 기반으로 합니다. 지능 증명은 끊임없이 성장하는 커뮤니티를 구축하기 위한 도구로서 STEEM을 사용하며, STEEM에 내재된 보상 체계는 커뮤니티 가치를 상승시키는 방향으로 커뮤니티 멤버들이 활동할 수 있게 유도합니다.

발전된 블록체인, 토큰 기술과 더불어, 스팀은 사용자 경험을 향상시키기 위해 도난 계정 복구[^5], 에스크로 서비스, 사용자 홍보 콘텐츠(promoted content), 평판 시스템, 예금 계정 등의 고급 기능들을 추가로 제공합니다. 이 기능들을 이용할때 사용자에게는 모든 트랜잭션에 대해 3 초의 확인 시간과 수수료 무료 혜택이 제공됩니다. 이 모든 것들은 인터넷 상의 콘텐츠 제작자, 커뮤니티 참여자들에게 스마트하고 사회적인(social) 화페를 도입하기 위한 임무를 지원하는데 사용됩니다.

## 지능 증명: 스마트, 소셜 토큰

사용자가 토큰 기반 커뮤니티 시스템에 공헌한 만큼 그들에게 보상하는 토큰 시스템은 콘텐츠의 사회적인 가치를 설정하고 평가하기 위한 방법(mechanisms)이 필요합니다: 우리는 이것을 "지능 증명"이라고 부릅니다.

### 보상 풀("토큰은 어디에서 만들어지는가?")

스팀 블록체인의 가장 혁신적인(동시에 가장 오해받는) 특징 중의 하나는 "보상 풀"입니다. 보상 풀로부터 토큰은 가치있는 콘텐츠 제작자들에게 분배됩니다. 보상 풀이 무엇인지 이해하기 위해서는 우선, DPoS(위임된 지분 증명) 블록체인에서의 토큰 생산 방식이 PoW(작업 증명) 블록체인의 생산 방식과 다르다는 것을 이해해야 합니다. 전통적인 PoW 블록체인에서 토큰은 정기적으로 생산되지만 분배는 작업을 수행하는 머신을 이용해 토큰을 채굴하는 사람들("miner") 을 대상으로 무작위로 이루어집니다.

PoW 전용 가상 화폐와는 다르게 스팀에서 토큰은 고정 비율로 3초마다 1개의 블록씩 생성됩니다. 블록체인의 정의된 규칙에 기반한 시스템에서 이들 토큰은 다양한 액터(actors) 들에게 분배됩니다. 콘텐츠 제작자, 증인(witnesses), 큐레이터 등의 액터들은 토큰을 두고 전문화된 방법으로 경쟁합니다. 채굴자들이 원시 컴퓨팅 능력으로 경쟁하는 전통적인 PoW의 분배 수단과는 다르게, 스팀 네트워크의 액터들은 네트워크의 가치를 높이기 위해 경쟁합니다.

2016년 12월을 기점으로 새롭게 생성된 토큰의 인플레이션율은 연 9.5% 였고, 이후 인플레이션율은 25만개의 블록당 0.01%(연 0.5%) 로 감소합니다. 인플레이션이 이 비율로 지속적으로 감소하면 약 20.5년 후에는 0.95%가 될 것입니다.

매년 스팀 블록체인에 의해 생성된 새로운 토큰 공급량 중 75%는 "보상 풀"을 구성하는데 사용되며, 이들은 콘텐츠 제작자와 큐레이터에게 분배됩니다. 15%는 토큰 소유자(vested token holders) 에게 분배되며, 10%는 스팀의 DPoS 합의(consensus) 프로토콜에 협력하는 블록 생산자들("증인"이라고 부른다) 에게 분배됩니다.

#### 콘텐츠 제작자와 큐레이터에 대한 보상

콘텐츠를 제작하는 사용자는 콘텐츠 제공을 통해 네트워크의 가치를 상승시키고 있습니다. 이렇게 만들어진 콘텐츠들은 기존 사용자들에게 즐거움을 선사하고, 이들이 지속적으로 플랫폼을 이용하게 만들며, 새로운 사용자를 플랫폼으로 유입시키는 역할을 합니다. 이로 인해 화폐는 보다 폭넓은 사용자들에게 분배되고, 네트워크 효과는 상승합니다. 콘텐츠를 충분히 평가한 후 투표하는 사용자들은 가장 가치있는 콘텐츠를 작성한 사용자에게 화폐가 분배될 수 있는 환경을 구축하는데 중요한 역할을 담당하고 있습니다. 콘텐츠 제작과 투표 활동에 대해 블록체인은 지분 가중치(stake-weighted) 투표 시스템을 통해 모아진 집단 지성(collective wisdom of the crowd) 에 기반한 가치에 따라 보상합니다.

#### Voting with Staked-Tokens to Determine Allocation of Rewards

스팀은 STEEM 1개당 투표 1개 기준으로 동작한다. Under this model, individuals who have contributed the most to the platform, as measured by their account balance, have the most influence over how contributions are scored. Stake can be bought or earned. Users can not gain additional influence by owning multiple accounts, since one single account with an amount of stake will have the same influence as two different accounts sharing the same amount of stake. The only way for users to increase their influence in the platform is to increase their stake.

Furthermore, Steem only allows members to vote with STEEM when it is committed to a 13 week vesting schedule called Steem Power. Under this model, members have a financial incentive to vote in a way that maximises the long term value of their STEEM.

## Speed and Scale on the Steem Blockchain

The Steem blockchain is designed to be one of the fastest and most efficient blockchains in existence, which is necessary to be able to support the amount of traffic expected on a social media platform larger than the size of Reddit. Steem has already surpassed Bitcoin in number of transactions, and is able to scale to support 10,000 or more transactions per second.

### Delegated Proof of Stake (DPoS)

Often bottlenecked by Proof-of-Work (PoW)[^6], many blockchains can’t scale beyond three transactions per second, which is a fraction of the world’s financial traffic. Steem needed far more scale and speed than that offered by PoW, and so a lesser known algorithm called Delegated Proof of Stake (DPoS)[^7] was leveraged to lay the foundation for a blockchain suited for billions of users.

Because of DPoS, the Steem blockchain is able to generate a new block every 3 seconds with minimal computational load. This means that the blockchain can process more transactions and hold more information, including content.

By defining the rules for when a Hardfork occurs, the witnesses elected within the DPoS framework can quickly and efficiently decide on whether or not to move forward with a proposed hardfork, allowing the Steem blockchain protocol to evolve more rapidly than most others. The Steem blockchain has already successfully forked 18 times[^8], and each time a Hardfork has occurred, only a single chain has persisted after the fork.

### ChainBase

ChainBase[^9] is the database portion of the blockchain stack and replaced Graphene[^10] in 2016. ChainBase has faster load and exit times, supports parallel access to the database and is more robust against crashes than its predecessor. It also has less frequent database corruption, allows instant “snapshotting” of entire database state, and can serve more RPC requests from the same memory.

### AppBase

AppBase is the first step in creating a multi-chain FABRIC. AppBase enables many components of the Steem blockchain to become modular by creating additional non-consensus blockchains as dedicated plugins. These plugins can be updated much more rapidly because they do not require replaying the entire blockchain. This makes steemd[^11] far more efficient and easier to maintain and scale.

Practically speaking, AppBase enables different cores, or even different computers, to maintain different parts of the Steem blockchain. This is significantly more efficient than requiring every core, and every computer in the network maintain the entire blockchain. Modularizing the blockchain enables it to take full advantage of the modular nature of computers. This is one necessary step in the long process of creating a fully parallel, fully optimized blockchain.

## Steem’s Platform Features

The Steem blockchain serves a dual purpose of being a digital token processing system, as well as a mainstream social media platform. The features offered by the blockchain need to support both purposes, and provide users with a world class experience when using both aspects of the platform.

### Primitives Designed for Content Applications

Steem offers users the unique ability to publish and store different types of content directly and permanently into the immutable ledger of the blockchain as plain text. Once stored in the blockchain, data becomes available publically for developers to build from. Developers are able to interact with the content directly in the blockchain using the available APIs. Several of the blockchain primitives developers can build from include Account Names, Posts, Comments, Votes and Account Balance.

### Native Name System

Wallet addresses used by many blockchain technologies, such as Bitcoin and Ethereum, have historically consisted of long strings of random letters and numbers, however, these wallet addresses can make it difficult to transact with other users in a typical online-social-media context because users are unable to recall the long-string addresses from memory. The Steem blockchain uses each participant's user name as their wallet address, which bolsters the user experience for participants who attempt to send tokens because they can verify the addresses from their own memory.

### Steem Blockchain Dollars (SBD)

Many users who are introduced to cryptocurrency struggle to comprehend how “magic internet tokens” awarded by the platform can actually have real world value. In order to help bridge the gap between more traditional fiat money systems which mainstream users are used to, and the cryptocurrency tokens which they are awarded through the platform, a new currency called Steem Blockchain Dollars (SBD) was created.

SBD tokens are designed to be pegged closely to one USD, so that users who receive them can know approximately how much they are worth in “real dollar” terms. SBD tokens also offer a relatively stable currency for users to hold if they are looking to preserve their account value relative to USD. A more detailed technical explanation can be found in the Steem technical whitepaper.[^12]

### Decentralized Exchange

The Steem blockchain offers a decentralized token exchange, similar to the Bitshares exchange.[^13] The exchange allows users to trade their STEEM and SBD tokens through a public decentralized peer-to-peer market. Users are able to place buy and sell orders, and order matching is performed automatically by the blockchain. There is also a publicly accessible order book and order history which users can use to analyze the market. Users can interact with the exchange directly using the blockchain API, or use a GUI such as the one on Steemit.com.[^14]

### Payments Through Escrow

The irreversible nature of blockchain transactions is an important security feature, although there are many cases where users may not be comfortable sending their tokens to another individual without a way to get them back if the other user does not hold up their end of the agreement. The Steem blockchain provides a way for users to send coins to each other with a third party designated as an escrow service. The user acting as the escrow service is able to determine if the terms of the agreement have been met, and either allow the funds to be released to the receiver or returned to the sender.

### Hierarchical Private Key Structure

Steem employs a first of its kind hierarchical private key system to facilitate low-security and high-security transactions. Low-security transactions tend to be social, such as posting or commenting. High-security transactions tend to be transfers and key changes. This allows users to implement different levels of security for their keys, depending on the access that the keys allow.

These private keys are the Posting, Active and Owner. The posting key allows accounts to post, comment, edit, vote, resteem[^15], and follow/mute other accounts. The active key is meant for more sensitive tasks such as transferring funds, power up/down transactions, converting Steem Dollars, voting for witnesses, placing market orders, and resetting the posting key. The owner key is only meant for use when necessary. It is the most powerful key because it can change any key of an account, including the owner key, and to prove ownership during an Account Recovery. Ideally it is meant to be stored offline, and only used when the account’s keys need to be changed or to recover a compromised account.

Steem also facilitates the use of a Master Password that encrypts all three keys. Webservices can use a Master Password that decrypts and signs with the necessary private key. Master Passwords may allow users to trust certain services to keep improper keys from being transferred across any servers, thus increasing user experience while maintaining a secure client-side signing environment.

### Multi Sig Authorities

The Steem blockchain allows an authority to be split across multiple entities, so that multiple users may share the same authority, or multiple entities are required to authorize a transaction in order for it to be valid. This is done in the same way as Bitshares[^16] where each public/private key pair is assigned a weight, and a threshold is defined for the authority. In order for a transaction to be valid, enough entities must sign so that the sum of their weights meets or exceeds the threshold.

### Multiple Reward Beneficiaries

For any given post there may be a number of different people who have a financial interest in the reward. This includes the author, possible co-authors, referrers, hosting providers, blogs that embedded blockchain comments, and tool developers. Whatever website or tool that is used to construct a post or comment will have the ability to set how rewards from that comment are divided among various parties. This allows for various forms of collaboration, as well as a way for platforms that are built on top of the Steem blockchain to collect a portion of the rewards from their users.

### Smart Media Tokens (SMT)

Smart Media Tokens are native tokens that can be built on the Steem blockchain. STEEM is the first SMT to ever exist, and the Smart Media Token protocol aims to monetize content websites and applications across the web by allowing people to create tokens that possess properties similar to STEEM, but customizable to suit the vision of any online community through incentivized behavior, essentially replicating STEEMs success to any website or application. More technical details can be found in the Smart Media Tokens whitepaper[^17].

### Stolen Account Recovery

If a user’s account is compromised, they may change their keys using their private owner key. In the event that the attacker is able to compromise the private owner key and change the password on the account, the user has 30 days to submit a previously functional private key through Steem’s industry-first stolen account recovery process, and regain control over their account. This may be offered by a person or company who provides registration services to Steem. It is not mandatory for the registrar to provide this service to its users, but it is available to increase the value of a registrar's users’ experience.

### Security Through Time-Locks

If a user’s active or owner key is compromised, the attacker would have full access to all of the funds in their account. Because blockchain transactions are irreversible, users have no way to get their funds back after they have been stolen.

The Steem blockchain allows users to store their STEEM and SBD tokens in a savings account, so that the funds may not be withdrawn until after a three day waiting period. In addition, STEEM that is held in the 13 week vesting schedule may only be withdrawn at a rate of 1/13 per week, after an initial waiting period of seven days. These time-locks prevent an attacker from being able to access the full portion of the user’s funds immediately, so that the rightful owner has time to regain control over their account before all of their funds can be withdrawn.

### Bandwidth Rate Limiting for Fee-less Operations

Because the witnesses are paid entirely through the generation of new tokens, there is no need to charge users a fee for powering the blockchain. The only reason to charge a fee would be as a deterrent to prevent users from completing an unreasonable amount of transactions, which could potentially impact the performance of the blockchain.

In order to place reasonable limits on the system use, each user is given a limited bandwidth. Whenever users perform blockchain operations such as token transfers, posting content, and voting, it uses up a portion of their bandwidth. If a user exceeds their bandwidth allowance, they must wait to perform additional actions until their bandwidth recharges.

Bandwidth limits adjust based on network use, so users have a higher bandwidth allowance when the network usage is low. The amount of bandwidth that an account is allowed is directly proportional to the amount of Steem Power a user has, so users can always increase their bandwidth allowance by getting additional Steem Power.

## Conclusion

The unique rewards and incentive program offered by the Steem blockchain and token are designed to make Steem the ultimate on-ramp into cryptocurrency for mainstream users. The performance of the blockchain is designed with widespread mass adoption of the currency and platform in mind. When combined with the lightning fast processing times and fee-less transactions, Steem is positioned to become one of the leading blockchain technologies used by people around the world.

[^1]: Delegated Proof of Stake Position Paper. Grigg, 2017. https://steemit.com/eos/@iang/seeking-consensus-on-consensus-dpos-or-delegated-proof-of-stake-and-the-two-generals-problem

[^2]: To differentiate it from the term for its blockchain, the correct spelling of Steem’s native digital token is STEEM.

[^3]: Transaction Volumes: Transactions Per Second Report. Steem Witness and user “@roadscape”. https://steemit.com/blockchain/@roadscape/tps-report-2-the-flippening

[^4]: Proof-of-Work. Wikipedia. https://en.wikipedia.org/wiki/Proof-of-work\_system

[^5]: Stolen Account Recovery initiation for Steemit.com users: 07-13-2017 https://steemit.com/recover\_account\_step\_1

[^6]: Bitcoin Scalability Problem https://en.wikipedia.org/wiki/Bitcoin\_scalability\_problem

[^7]: DPoS Whitepaper https://steemit.com/dpos/@dantheman/dpos-consensus-algorithm-this-missing-white-paper

[^8]: https://steemit.com/steemit/@steemitblog/proposing-hardfork-0-20-0-velocity

[^9]: ChainBase Release https://steemit.com/steem/@steemitblog/announcing-steem-0-14-4-shared-db-preview-release

[^10]: Graphene Documentation http://docs.bitshares.org/

[^11]: The component of the Steem blockchain framework responsible for processing transactions and the distribution of rewards.

[^12]: Steem Whitepaper https://steem.io/SteemWhitePaper.pdf

[^13]: Bitshares Decentralized Exchange http://docs.bitshares.org/\_downloads/bitshares-general.pdf

[^14]: Steemit.com Currency Market https://steemit.com/market

[^15]: “Resteem” is the term used in the Steem blockchain for when a user shares the content with their followers.

[^16]: Bitshares Flexible Identity Management http://docs.bitshares.org/\_downloads/bitshares-general.pdf

[^17]: Smart Media Tokens Whitepaper https://smt.steem.io/smt-whitepaper.pdf