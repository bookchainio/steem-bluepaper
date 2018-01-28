![](\headerimage.png)

## Introduction

Steem dey provide a scalable blockchain protocol[^1] for publicly accessible and immutable content, along with a fast and fee-less digital token (them dey cal am STEEM)[^2] wey fit make people earn the currency by using dia brain (waiting dem fit call "proof-of-brain"). De two building blocks wey this protocol, both blockchain and token, depend on each other for security, immutability and longevity, and are therefore integral for each others' existence. Steem don dey successfully operate for more than a year now, and don dey pass both Bitcoin and Ethereum in number of transactions processed.[^3]

Compared to other blockchains, Steem don stand out as the first publicly accessible database wey immutably stored content in the form of plain text along with an in-built incentivization mechanism. This don make Steem a public publishing platform from which any internet application fit pull and share data while rewarding those wey contribute the most valuable content.

In the field of crypto-currencies, the unique properties of STEEM make am both "smart" and "social" compared to others, like bitcoin and ether. This stems from two new token features. The first na pool of tokens dedicated to incentivizing content creation and curation (called the "rewards pool"). The second na voting system wey leverages the wisdom wey the crowd fit assess the value of content and distribute token for am. These two unique properties if them combined fit referred am as Proof-of-Brain, wey be entendre based on Proof-of-Work[^4], fit to emphasize the human work wey them need to distribute tokens to community participants. Proof-of-Brain positions STEEM as tool way them take dey build perpetually growing communities, wey encourage them members to add value for the community through the built for rewards structure.

In addition to these advancements for blockchain and token technology, Steem like system dey provides another advanced features wey enhance the person experience, like Stolen Account Recovery[^5], escrow services, user promoted content, a reputation system, and savings accounts. Them do all this wan while providing users with three second confirmation times and zero fees on all transactions. All this wan allow am to support the mission of bringing smart and social currency to publishers and community builders across the internet.

## Proof of Brain: Smart and Social Tokens

Token systems wey reward users as them dey contribute to wan token-based community system need mechanisms for establishing and evaluating content's social value: we dey call am this "Proof-of-Brain."

### The Rewards Pool ("Where the tokens dey come from?")

Wan of the most innovative (and most misunderstood) area of the steem blockchain na the "Rewards Pool" from were token dey distribute to valuable content creators. In order to understand waiting the Rewards Pool be, person first needs to understand say tokens dey produced differently for DPoS blockchains pass if them dey PoW blockchains. For traditional PoW blockchains, tokens dey produced regularly but randomly distributed to the people wey machines dey perform work ("miners"). 

Different from PoW-only cryptocurrencies, tokens for Steem dey generate for fixed rate of one block for every three seconds. These tokens go distribute to various actors for the system based on the defined rules of the blockchain. These actors, such as content creators, witnesses, and curators, compete in specialized ways for the tokens. Unlike the traditional Pow means of distribution, where miners them competing over raw computing power, the actors for the Steem network them incentivized to compete in ways wey add value to the network.

The rate wey new tokens dey generate them set am to 9.5% per year starting in December 2016, and reduce to the rate of 0.01% every 250,000 blocks, or about 0.5% per year. The inflation go continue to dey reduce for this rate until e reach 0.95% after some period of about 20.5 years.

Of the supply of new tokens wey create by the Steem blockchain every year, 75% of those tokens compose the "rewards pool" come dey distribute to content creators and content curators. 15% wey distribute to vested holders, and 10% wey distribute to Witnesses, the block producers cooperating inside Steem's DPoS concensus protocol.

#### Rewards for Content Creators and Curators

De users wey produce content wey add value to de network by creating materials wey go drive new users to the platform, as well as keep the existing users occupy and entertained. Dis go help to distributing de currency to plenty set of users and increases de network effect. De users wey take time take evaluate and vote on content dey play important role to dey distribute de currency to de users wey dey add de value wey big pass. De blockchain rewards together wit dis activities relative to dia value ontop de collective wisdom of de crowd wey dem collect tru de stake-weighted voting system.

#### Voting wit Staked-Token to Determine Allocation of Rewards

Steem operates on de basis of one-STEEM, one-vote. Unda dis model, person wey contribute pass for de platform, as dem measure am by dia account balance, get de most influence over how contributions dem scored. Dem go it buy stake or earn am. Users no go gain anoda influence if dem get plenty accounts, since wan single account wit an amount of stake go get de same influence as two different accounts sharing de same amount of stake. De only way for users go fit increase dia influence in de platform na to increase dia stake.

As e come be, Steem go only allow members to vote wit STEEM wen e go committed to a 13 week vesting schedule dem call am Steem Power. Unda dis model, members get wan financial incentive to vote for wan way wey increase the long term value of dia STEEM.

## Speed and Scale for de Steem Blockchain

De Steem blockchain get design we be wan of de fastest and plenty efficient blockchains for existence, wey dey necessary for dem to support de amount wey traffic expect or wan social media platform wey big pass the size of Reddit. Steem don already pass Bitcoin for plenty transactions, and e fit scale to support 10,000 or plenty transaction for one second.

### Delegated Proof of Stake (DPoS)

Meny times bottlenecked wey Proof-of-Work (PoW)[^6], plenty blockchains no fit scale pass three transaction for wan second, wey be fraction of de world's financial traffic. Steem need plenty more scale and speen pass de offered wey PoW, and less known algorithm wey dem call Delegated Proof of State (DPoS)[^7] dem leverage am to lay de foundation wey blockchain complete for billions of users.

Because of DPoS, de Steem blockchain don dey generate wan new block every 3 seconds wit small computational load. Dis mean sey de blockchain fit process plenty transactions and hold plenty information, including content.

By finding the rules for wen wan Hardfork happen, the witnesses elected inside de DPoS framework fit quickly and efficiently decide if or not dem go move forward wit wan proposed hardfork, allowing de Steem blockchain protocol to evolved plenty rapidly dan plenty odas. De Steem blockchain don already successfully forked 18 times[^8], and each time wan hardfork don happen, only wan single chain don continue after de fork.

### ChainBase

ChainBase[^9] na de database portion wey de blockchain stack and replaced Graphene[^10] for 2016. ChainBase get faster load and exist times, supports parallel access to de database and get plenty robust against crashes dan him predecessor. E also get less frequent database corruption, allows instant "snapshotting" for entire database state, and fit serve plenty RPC requests from de same memory.

### AppBase

AppBase na de first step for creating plenty-chain FABRIC. AppBase dey make plenty components of de Steem blockchain to become modular if dem create anoda non-consensus blockchains as dedicated plugins. These plugins fit dey updated many more rapidly becus dem no dey ask replaying de whole blockchain. Dis na him make steemd[^11] get plenty efficient and dey easy to mentain and scale.

For practical, AppBase go fit make different cores, or even different computers, to mentain different parts of de Steem blockchain. Dis wan dey important pass plenty efficient dem dey ask every core, and every computer wey dey de network mentain de whole blockchain. Modularizing de blockchain go make am to take full advantage of de modular nature of computers. Dis wan na one neccessary step for de long process to take create wan full parallel, full optimized blockchain.

## Steems's Platform Features

De Steem blockchain dey serve as dual purpose were wan digital token processing system, and as maistreem social medial platform. De features wey blockchain offer need to support both purpose, and give users wan world class experience wen dem use both aspects of de platform.

### Primitives Designed for Content Applications

Steem dey offer useres de unique power to publish and keep different types of content directly and permanently inside de immutable ledger of de blockchain as plain text. Once stored in the blockchain, data becomes available publically for developers to build from. Developers are able to interact with the content directly in the blockchain using the available APIs. Several of the blockchain primitives developers can build from include Account Names, Posts, Comments, Votes and Account Balance.

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