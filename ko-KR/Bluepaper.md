![](\headerimage.png)

## 소 개

스팀(Steem) 은 공개적으로 액세스할 수 있고 한번 생성하면 변경할 수 없는 콘텐츠를 지원하기 위해 빠르고 수수료가 없는 디지털 토큰(STEEM)[^2] 기반의 확장 가능한 블록체인 프로토콜[^1]을 제공합니다. 사람들은 글쓰기나 큐레이팅 등의 창작 활동을 통해 화폐를 벌 수 있으며, 이를 "지능 증명" (Proof-of-Brain) 이라고 부릅니다. 이 프로토콜의 구성요소인 블록체인과 토큰(token) 은 보안, 불변성, 장기 존속성(longevity) 을 위해 상호 의존하고 있기 때문에 서로 꼭 필요한 존재입니다. 스팀은 수 년간 성공적으로 운영되어 왔으며 현재는 트랜잭션 처리 수에서 비트코인과 이더리움을 넘어섰습니다.[^3]

다른 블록체인과 비교했을때, 스팀은 자체적인 보상 체계를 가지고 있고, 평문 형태로 변경 불가능하게 저장된 콘텐츠에 공개적으로 접근할 수 있는 최초의 데이터베이스라는 점에서 특별합니다. 이같은 특징 덕분에 스팀은 수많은 인터넷 애플리케이션이 참여하고 데이터를 공유하는 공개 출판 플랫폼이 되었으며, 스팀은 가장 가치있는 콘텐츠에 공헌하는 사람들에게 보상을 제공합니다.

가상 화폐 영역에서 STEEM은 비트코인과 이더리움과 비교했을 때 "스마트", "소셜"이라는 고유의 특성을 갖고 있습니다. 이러한 특성은 두 가지 새로운 토큰 기능에서 비롯된 것입니다. 첫 번째 기능은 콘텐츠 창작과 큐레이션을 장려하는 토큰 풀(보상 풀이라고 부른다) 이고, 두 번째 기능은 콘텐츠의 가치를 평가하고 콘텐츠에 토큰을 분배하기 위해 집단 지성을 활용하는 투표(voting) 시스템입니다. 이 두 가지 고유한 특성들이 결합된 것을 지능 증명(Proof-of-Brain) 이라고 부르며, 이것은 커뮤니티 참여자에게 토큰을 분배하기 위해 사람들의 작업이 필요하다는 것을 강조하는 작업 증명(Proof-of-Work)[^4]을 기반으로 합니다. 지능 증명은 끊임없이 성장하는 커뮤니티를 구축하기 위한 도구로서 STEEM을 사용하며, STEEM에 내재된 보상 체계는 커뮤니티 가치를 상승시키는 방향으로 커뮤니티 멤버들이 활동할 수 있게 유도합니다.

발전된 블록체인, 토큰 기술과 더불어, 스팀은 사용자 경험을 향상시키기 위해 도난 계정 복구[^5], 에스크로 서비스, 사용자 홍보 콘텐츠(promoted content), 평판 시스템, 예금 계정 등의 고급 기능들을 추가로 제공합니다. 이 기능들을 이용할때 사용자에게는 모든 트랜잭션에 대해 3 초의 확인 시간과 수수료 무료 혜택이 제공됩니다. 이 모든 것들은 인터넷 상의 콘텐츠 제작자, 커뮤니티 참여자들에게 스마트하고 사회적인(social) 화페를 도입하기 위한 임무를 지원하는데 사용됩니다.

## 지능 증명: 스마트, 소셜 토큰

사용자가 토큰 기반 커뮤니티 시스템에 공헌한 만큼 그들에게 보상하는 토큰 시스템은 콘텐츠의 사회적인 가치를 설정하고 평가하기 위한 방법(mechanisms)이 필요합니다: 우리는 이것을 "지능 증명"이라고 부릅니다.

### 보상 풀("토큰은 어디에서 만들어지는가?")

스팀 블록체인의 가장 혁신적인(동시에 가장 오해받는) 특징 중의 하나는 "보상 풀"입니다. 보상 풀에서 나온 토큰은 가치있는 콘텐츠를 제작한 사람들에게 분배됩니다. 보상 풀이 무엇인지 이해하기 위해서는 우선, DPoS(위임된 지분 증명) 블록체인에서의 토큰 생산 방식이 PoW(작업 증명) 블록체인의 생산 방식과 다르다는 것을 이해해야 합니다. 전통적인 PoW 블록체인에서 토큰은 정기적으로 생산되지만 분배는 작업을 수행하는 머신을 이용해 토큰을 채굴하는 사람들("miner") 을 대상으로 무작위로 이루어집니다.

PoW 전용 가상 화폐와는 다르게 스팀은 토큰이 고정 비율로 3초마다 1개 블록씩 생성됩니다. 블록체인의 정의된 규칙에 기반한 시스템에서 이들 토큰은 다양한 액터(actors) 들에게 분배됩니다. 콘텐츠 제작자, 증인(witnesses), 큐레이터 등의 액터들은 토큰을 두고 전문화된 방법으로 경쟁합니다. 채굴자들이 원시 컴퓨팅 능력으로 경쟁하는 전통적인 PoW의 분배 수단과는 다르게, 스팀 네트워크의 액터들은 네트워크의 가치를 높이기 위해 경쟁합니다.

2016년 12월을 기점으로 새로운 토큰은 연 9.5% 인플레이션율로 생성되었고, 이후 인플레이션율은 25만개의 블록당 0.01%(연 0.5%) 씩 감소합니다. 인플레이션이 이 비율로 지속적으로 감소하면 약 20.5년 후에는 0.95%가 될 것입니다.

매년 스팀 블록체인에 의해 생성된 새로운 토큰 공급량 중 75%는 "보상 풀"을 구성하는데 사용되며, 이들은 콘텐츠 제작자와 큐레이터에게 분배됩니다. 15%는 스팀 파워 소유자(vested token holders) 에게 분배되며, 10%는 스팀의 DPoS 합의(consensus) 프로토콜에 협력하는 블록 생산자들("증인"이라고 부른다) 에게 분배됩니다.

#### 콘텐츠 제작자와 큐레이터에 대한 보상

콘텐츠를 제작하는 사용자는 콘텐츠 제공을 통해 네트워크의 가치를 높입니다. 이렇게 만들어진 콘텐츠들은 기존 사용자들에게 즐거움을 선사하고, 이들이 지속적으로 플랫폼을 이용하게 만들며, 새로운 사용자를 플랫폼으로 유입시키는 역할을 합니다. 이로 인해 화폐는 보다 폭넓은 사용자들에게 분배되고, 네트워크 효과는 상승합니다. 콘텐츠를 충분히 평가한 후 투표하는 사용자들은 가장 가치있는 콘텐츠를 작성한 사용자에게 화폐가 분배될 수 있는 환경을 구축하는데 중요한 역할을 담당하고 있습니다. 콘텐츠 제작과 투표 활동에 대해 블록체인은 지분 가중치(stake-weighted) 투표 시스템을 통해 모아진 집단 지성(collective wisdom of the crowd) 에 기반한 가치에 따라 보상합니다.

#### 스팀 파워 기반의 투표가 보상의 양을 결정한다.

스팀은 STEEM 1 개당 1 번의 투표를 기준으로 동작합니다. 이 모델에서는 플랫폼에 가장 공헌을 많이한 개인이 누구인지를 그들의 계정 잔고로 측정하며, 공헌실적이 높을수록 큰 영향력을 갖습니다. 지분(Stake) 은 살 수도 있고 벌 수도 있습니다. 사용자는 여러 개의 계정을 소유하는 방법을 이용해 추가적인 영향력을 발휘할 수 없습니다. 일정한 지분이 있는 하나의 계정과 이 계정과 같은 양의 지분을 공유한 두 개의 다른 계정들의 영향력은 같을 것입니다. 사용자가 플랫폼 안에서 영향력을 높일 수 있는 유일한 방법은 그들의 지분을 늘리는 것 뿐입니다.

뿐만 아니라, 스팀에서 커뮤니티 멤버들은 스팀 파워를 통한 투표만 가능합니다. STEEM에 대해 13 주간의 귀속 일정(vesting schedule) 을 마치면 스팀 파워를 얻을 수 있습니다. 이러한 모델 구조에서 커뮤니티 멤버들에게는 장기적으로 STEEM의 가치를 최대화 할 수 있는 방향으로 투표하게끔 하는 금전적인 인센티브가 존재합니다.

## 스팀 블록체인의 속도와 확장

스팀 블록체인은 현존하는 블록체인 중 가장 빠르고 효율적인 형태로 설계되었고, Reddit 의 트래픽 양보다 훨씬 더 많은 소셜 미디어 플랫폼 트래픽을 감당하기 위해서는 이러한 설계가 필수적입니다. 스팀은 트랜잭션 수에서 이미 비트코인을 능가했으며, 초당 1만개 이상의 트랜잭션을 지원하도록 확장할 수 있습니다.

### 위임된 지분 증명(DPoS)

작업 증명(PoW)[^6]에서 발생하는 잦은 병목현상으로 인해 대부분의 블록체인은 초당 트랜잭션을 3회 이상으로 확장할 수 없습니다. 전세계 금융 트래픽에서는 3회 이상의 트랜잭션 처리가 가능합니다. 스팀은 PoW가 제공했던 것보다 훨씬 확장성이 좋고 빠르길 원했고 수십 억 사용자에게 적합한 기반을 구축하기 위해 비교적 덜 알려진 위임된 지분 증명(DPoS)[^7] 이라는 알고리즘을 사용했습니다.

스팀 블록체인은 DPoS 덕분에 최소한의 계산 부하 환경(minimal computation load) 에서 3초당 새로운 블록 1개를 만들 수 있습니다. 이는 블록체인이 좀 더 많은 트랜잭션을 처리할 수 있고 콘텐츠를 포함해 보다 많은 정보를 가질 수 있다는 것을 의미합니다.

하드포코가 발생했을 때 정의된 규칙에 따르면, DPoS 프레임워크 내에서 증인(선출된) 은 제안된 하드포크에 대한 진행여부를 신속하고 효율적으로 결정할 수 있습니다. 이러한 방식은 스팀 블록체인 프로토콜이 다른 블록체인보다 빠르게 발전하게 된 이유이기도 합니다. 스팀 블록체인은 이미 18번의 포크[^8]를 성공적으로 마쳤으며, 하드포크가 발생할 때마다 포크 이후에 오직 1개의 체인만 유지하고 있습니다.

### ChainBase

ChainBase[^9] 는 블록체인 스택에서 데이터베이스에 해당하는 부분이며 Graphene[^10]은 2016년에 ChainBase 로 대체되었습니다. ChainBase 는 로드 및 종료 시간이 빠르고, 데이터베이스에 대한 병렬 접근을 지원하며 이전 버전인 Graphene에 비해 크래시 대응이 강화되었습니다. 또한 데이터베이스 손상 빈도가 적고, 전체 데이터베이스 상태에 대한 인스턴트 "스냅샷"이 가능하며, 같은 메모리 환경에서 보다 많은 RPC 요청을 제공합니다.

### AppBase

AppBase 는 멀티 체인 FABRIC 을 만드는 첫 번째 단계입니다. AppBase 은 전용 플러그인 역할을 하는 비합의(non-consensus) 블록체인을 추가 생성하여 스팀 블록체인의 많은 구성요소들을 모듈화할 수 있습니다. 이들 플러그인은 전체 블록체인을 리플레이(replaying) 하지 않기 때문에 좀 더 빠르게 업데이트할 수 있습니다. AppBase 덕분에 steemd[^11] 는 관리와 확장이 훨씬 쉬워졌고 효율성도 향상되었습니다.

사실 AppBase 는 서로 다른 코어(core), 심지어 다른 컴퓨터에서 스팀 블록체인의 다른 부분들을 관리하는 것이 가능합니다. 이같은 방식은 네트워크 안의 모든 코어와 모든 컴퓨터에서 전체 블록체인을 유지하는 것보다 훨씬 효율적입니다. 블록체인을 모듈화하면 컴퓨터 모듈화와 관련된 특성을 모두 활용할 수 있습니다. 이것은 블록체인의 완전한 병렬화, 충분한 최적화를 달성하기 위한 긴 여정에서 반드시 필요한 단계입니다.

## 스팀의 플랫폼 기능

스팀 블록체인은 주류(mainstream) 소셜 미디어 플랫폼뿐만 아니라 디지털 토큰 처리 시스템 용도로도 사용합니다. 블록체인에 의해 제공되는 기능들은 플랫폼, 디지털 토큰 시스템 역할을 지원하고, 플랫폼 및 디지털 토큰 시스템을 이용할 때 사용자에게 세계 최고의 경험을 제공하기 위해 필요합니다.

### 콘텐츠 애플리케이션을 위해 고안된 기본 기능들(primitive)

스팀은 직접적이면서도 영구적으로 다양한 종류의 콘텐츠를 블록체인의 변경 불가능한 원장(ledger) 으로 평문처럼 저장하고 출판할 수 있는 고유한 기능을 사용자에게 제공합니다. 블록체인에 일단 저장되면 개발자들이 이 데이터를 공개적으로 이용할 수 있게 됩니다. 개발자는 제공된 API를 통해 블록체인 안에 있는 콘텐츠를 이용할 수 있습니다. 블록체인 기본 기능(blockchain primitives) 개발자들은 계정 이름, 포스트, 코멘트, 투표, 계정 잔고 등의 기능을 만들었습니다.

### Native Name System

비트코인이나 이더리움 같은 많은 블록체인 기술에서 사용하고 있는 지갑 주소는 임의의 문자와 숫자를 조합한 긴 문자열로 구성됩니다. 하지만, 사용자들이 이렇게 긴 지갑 주소를 기억하기 어렵기 때문에 일반적인 온라인 소셜 미디어 환경에서 다른 사람과 거래할 때 매우 불편합니다. 스팀 블록체인은 각 참가자의 사용자 이름을 지갑 주소로 사용하며 이러한 방식을 이용하면 거래 참가자들이 자신의 기억 속에서 해당 지갑 주소를 확인할 수 있기 때문에 토큰을 거래하는 참가자들의 사용자 경험을 강화시킵니다.

### 스팀 블록체인 달러 (SBD)

플랫폼에서 “마법의 인터넷 토큰” 이 지급되는 방법에 대해 이해하기 위해 가상화폐 세계에 들어온 사람들은 가상화폐 세계에서 뿐만 아니라 실제 우리가 살고 있는 세상에서도 가치가 있는 토큰을 보유할 수 있습니다. 대부분의 사용자가 익숙한 좀 더 전통적인 실물 화폐 시스템과 플랫폼을 통해 지급되는 가상화폐 토큰 사이의 격차를 줄이기 위해 스팀 블록체인 달러 (SBD) 라고 불리는 새로운 화폐를 만들었습니다.

SBD 토큰은 1 USD와 가깝게 페그되도록 고안되었기 때문에 SBD 를 받은 사용자들은 이들이 “실제 달러” 기준으로 얼마만큼의 가치가 있는지 대략적으로 알 수 있습니다. 또한, 그들의 계좌 가치를 USD와 연계해서 보존하고 싶어하는 사용자들에게 SBD 토큰은 상대적으로 안정적인 화폐입니다. 좀 더 상세한 기술적인 설명은 스팀 기술 백서[^12]를 확인하시길 바랍니다.

### 분권화된 거래소

스팀 블록체인은 비트쉐어 거래소[^13]와 유사한 분권화된 토큰 거래소를 제공합니다. 거래소에서 사용자들은 공개적으로 분권화된 개인 대 개인(peer-to-peer) 시장을 통해 STEEM과 SBD 토큰을 거래할 수 있습니다. Users are able to place buy and sell orders, and order matching is performed automatically by the blockchain. There is also a publicly accessible order book and order history which users can use to analyze the market. Users can interact with the exchange directly using the blockchain API, or use a GUI such as the one on Steemit.com.[^14]

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