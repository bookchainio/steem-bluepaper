![](\headerimage.png)

## 简介

Steem为可公开访问和不可变的内容提供了可扩展的区块链 协议 [^1], 以及一个快速且免手续费的代币 (称为STEEM) [^2], 让人能够用他们的智慧来赚取货币 (可以称为 "Proof-of-Brain ")。 这一协议的两个组成部分, 区块链和代币, 都依赖于彼此的安全性、不变性和持久性, 因此是相互依存的。 Steem已经成功地经营了一年多, 现在已经超过了比特币和以太币的交易数量。[^3]

与其他区块链相比, Steem是第一个用于存储不可变文字内容，有内置的奖励机制的公开数据库。 这使得Steem成为一个公共发布平台。 任何互联网应用程序都可以从中抽取和共享数据, 同时为那些贡献最有价值的内容的人提供奖励。

在加密货币中, Steem的独特性使其比起其他代币， 例如比特币和以太币， 更加 "智能化" 和 "社交化"。 这源于代币的两个新特征。 第一个是用于激励内容创建和鉴定 的代币库(称为 "奖励库")。 第二个是一个投票系统，它利用人群的智慧来评估内容价值，并向该内容分发代币。 这两个独特特征的组合可以称为 Proof-of-Brain, 它是基于 Proof-of-Work [^4] 的双关, 旨在强调以人工分发形式把代币分发给社区参与者。 Proof-of-Brain 把STEEM定位成一个用于建立不断增长的社区的工具, 通过奖励架构鼓励社区的成员去增加社区的价值。

除了在 区块链 和代币技术方面的这些进步, Steem系统还提供了额外的高级功能来增强用户体验, 如被盗帐户的恢复 [^5]、国际支付宝(escrow) 服务、用户内容推广、信誉系统和储蓄账户。 与此同时, 为用户提供三秒交易确认和零交易费用。 所有这些都使它能够支持将智能化和社交化货币带到互联网出版商和社区建设者的使命。

## 用脑量证明：智能和社交代币

一个基于对社区贡献而奖励用户的代币系统需要一个决定和评估内容价值的机制: 我们称之为 "用脑量证明"。

### 奖励库(代币从哪里来？)

Steem区块链中最创新的 (也是最被误解的) 特点之一是"奖励库"，一个用于给有价值内容的创作者分发代币的代币库。 要了解奖励库, 首先需要理解的是DPoS(委派式权益证明 Delegated Proof-of-Stake) 区块链和 PoW(工作量证明 Proof-of-Work) 区块链代币产生方式中的不同之处。 在传统的PoW 区块链中, 代币是定期产生的, 但随机分发给那些在用计算机执行工作的人 ("矿工")。

不同于其他只用PoW的加密货币, Steem中的代币以每三秒一个区块的固定速率生成。 这些代币根据区块链的定义规则分发给系统中的各个参与者。 这些参与者, 如内容创作者、见证者和鉴定者, 会以不同的方式为代币而竞争。 与传统的PoW分配中矿工们在用计算实力争夺代币的方式不同, Steem网络激励参与者以增加网络价值的方式竞争。

从2016年12月开始, 新代币的生产年率将设置为9.5%, 之后以每25万个区块0.01%的比率减少, 大概每年下降约0.5%。 这个通货膨胀率将持续下降直至到达0.95%，需时大约20.5 年。

在Steem区块链 每年生产的新代币中的75% 将会成为 "奖励库", 分发给内容创作者和内容鉴定者。 15% 会分配给被既定的代币持有人, 10% 会被分配给见证者, Steem DPoS 共识协议里的区块生产者。

#### 内容创作者和鉴定者的奖励

The users who produce content are adding value to the network by creating material that will drive new users to the platform, as well as keep the existing users engaged and entertained. This aids in distributing the currency to a wider set of users and increases the network effect. The users that take time to evaluate and vote on content are playing an important role in distributing the currency to the users who are adding the most value. The blockchain rewards both of these activities relative to their value based on the collective wisdom of the crowd collected through the stake-weighted voting system.

#### Voting with Staked-Tokens to Determine Allocation of Rewards

Steem operates on the basis of one-STEEM, one-vote. Under this model, individuals who have contributed the most to the platform, as measured by their account balance, have the most influence over how contributions are scored. Stake can be bought or earned. Users can not gain additional influence by owning multiple accounts, since one single account with an amount of stake will have the same influence as two different accounts sharing the same amount of stake. The only way for users to increase their influence in the platform is to increase their stake.

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

This protocol layer is under development. Its whitepaper will be posted here.

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