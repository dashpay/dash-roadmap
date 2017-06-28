# OFFICIAL DASH ROADMAP
### Version 2.1.2 // Delivery Milestones
- Evan Duffield / evan@dash.org / Dash Labs
- Andy Freer / andy@dash.org / Dash Core CTO

  
Dash Evolution will be the first user-friendly and scalable digital currency platform suitable for mass adoption. Because this is such an ambitious goal, we’ve created a detailed roadmap to guide development. Evolution will be launched in three stages. Each release will increase the processing power, ease of use, feature set, and scalability of the network.  
 
We intend to increase the user capacity of the network by an order of magnitude with each new stage of development. Furthermore, because of increases in the amount of available budget funding, we will be able to grow the development team rapidly. We plan to double the number of developers with each release, allowing us to accelerate the implementation of each phase. 
 
We intend to schedule releases of Dash Evolution in a way that produces a high-quality product and provides a user-friendly experience. In addition to emphasizing quality and user experience, we will use each incremental release as a robust framework for future development. The Dash Core Team believes that taking the time to create a high quality product will create the most value over the long term. A quick rush to market would likely result in an inferior product that causes temporary price growth but long-term stagnation or decline. 
 
Several new technologies are required to deliver such an excellent user experience. These technologies will expand the capabilities of the backbone infrastructure supporting the network and will ensure that it is capable of handling the transaction loads and data storage requirements of a mass-market user base.
 
Masternodes will scale and be tested using a system called ”state transitions.” This system will provide a mathematically predictable way of determining the quality of service that masternodes provide. Full access to the blockchain will be required to perform proper state transitions of user objects, which will reference governance objects and blockchain transactions to perform quorum operations. Masternodes which fall under a threshold of activity will automatically be removed from the masternode list using a new system called “masternode blocks.” 
 
DashDrive will be implemented using software called IPFS, a user-friendly and popular P2P file system which will automatically handle most of the network’s sharing, redundancy and syncing operations. IPFS writes will utilize masternode quorums for security. DashDrive is an internal facing system that stores user objects within the network in a decentralized way. There is no public-facing system for storage of non-Dash related information. DashDrive is not a replacement for consumer and enterprise applications like Dropbox; it’s a mechanism to allow smooth functioning of the network.
 
Network operations will scale using a targeted model to allow for exponential growth. Hardware requirements for masternodes will gradually increase to power a larger network that services more users with greater functionality. When the first phase of Evolution is deployed, masternodes will face new hard disk requirements. They will need both a solid state drive (for faster retrieval of blockchain data) and an ordinary hard disk with higher storage capacity. Eventually the network will finance the creation of masternode-specific hardware with custom requirements. Such hardware will allow massive parallelization of transaction processing, hashing, and other system functions. More powerful hardware will increase the throughput of the network significantly. This hardware will be entirely open source and non-exploitable and will connect to commodity hardware for additional storage capacity.
 
Over the past few months we have been rapidly increasing the size of our development team in order to accelerate delivery of Evolution. In the meantime, a number of Core developers have been focused on delivering and implementing Dash 12.1. This update was absolutely vital, serving as a link between the existing Dash codebase and future Evolution releases. Now that 12.1 has been successfully rolled out, our entire development team is transitioning to work on Evolution. 
 
In order to create a quality product as quickly as possible, the team had to create a solid foundation. We had to carefully plan the project’s roadmap, create enormous amounts of documentation, and do significant research to ensure that we do not make time- and resource-wasting mistakes during the creation of Evolution. We will soon be opening a vast amount of private documentation to the community, ensuring complete transparency of our development work. This phase of the project is coming to a close, with the entire team now beginning to focus on creating the actual codebase for Evolution.
 
We would also like to announce the creation of a new team to be centered in Hong Kong, called Dash Labs. This team will be the scientific arm of the project, focusing on research and the development of custom hardware. Evan Duffield and Andy Freer are heading up this team.  Dash Labs aims to create the first open-source versions of many different types of hardware. Our goal is to help the digital currency space to remain open and transparent, while reducing the economic advantages of closed-source proprietary technology. For example, advanced open-source ASICs would eliminate most of the advantages of privately-developed ASICs. As a result, mining centralization could be significantly reduced. All economic actors will have a level playing field, at least with respect to hardware solutions.

# DashPay Wallet Alpha (September 2017)
- Dash version of CoPay, pre-Evolution functions, on test-net
- Will lead to full Evolution wallet (not merely a web wallet)
- DashCore 12.2 Release (September 2017)
- 2MB block size increase, activation in November 2017
- 2MB / 5MB block research documentation
- Launch of a read-only/view-only portal for project documentation which will be open to the entire community (to ensure transparency)
- Launch a read-only/view-only portal to view current tickets, projects the teams are working on

# DashPay Evolution Wallet Testnet Release (November 2017)
- User signup and friending process (Signup procedure for Evolution on testnet // reservation testnet)
- Basic support for purchase agreements
- Evolution Account Management (Create, Review, Update, Delete)
- DAPI testnet release

# DashCore 12.3 Release (December 2017)
- HD wallets, rehaul of networking code, etc etc (other Trac items)
- Evolution Alpha Release to Partners (testnet, December 2017)
- Integration partner testing
- Merchant and app testing
- API & SDK testing
- Multi-stage escrow transactions
- Support for user/merchant ratings via maintenance quorums
 
## DashPay Evolution Wallet Livenet Release (February 2018)
- Signup and Friending Process Evolution on Livenet
- Evolution Account Management on LiveNet
- DAPI Livenet Release
 
# 13.0 - Evolution v1 - Mainnet (June 2018)
- Public DashPay, DAPI, DashDrive, DashCore v13.0 release
- Fourth Hiring Wave - Full-time developers
- 500K daily-users supported <sup>[22](#f22)</sup>
- Ethernet networking requirement <sup>[15](#f15)</sup>
- 1TB HDD / 128GB SSD Req <sup>[8](#8)</sup> <sup>[9](#f9)</sup>
- 64TX/SEC && 5.33MB blocks <sup>[16](#16)</sup> <sup>[20](#f20)</sup> <sup>[21](#f21)</sup>
- Quorum-based DAPI implementation <sup>[4](#f4)</sup>
- Proof of service / Proof of blockchain
- Governance object support for users, groups, accounts
- Email-based invitation system <sup>[2](#f2)</sup>
- State transitions <sup>[6](#f6)</sup>
- Encryption of object data
- Offices in Arizona, Europe (CORE), and Asia (Dash SW)
- Age-based quorums <sup>[13](#f13)</sup>
- Friending system / Semaphore-based approval system <sup>[7](#f7)</sup>
- IPFS DashDrive implementation / Limited sharding ability 
- Official user-friendly Wallet
- Masternode blocks <sup>[11](#f11)</sup>
- Multi-key spork technology <sup>[30](#f30)</sup>

# 14.0 - Evolution v2 (TBD)
- Fifth Hiring Wave - Full-time developers
- 5M daily-users supported
- 2TB HDD / 256GB SSD / high-end processor <sup>[29](#f29)</sup>
- 128TX/SEC && 10.67MB blocks <sup>[17](#f17)</sup>
- GB Ethernet-handoff / Co-located level networking requirement
- Ability to move money between public and private accounts <sup>[5](#f5)</sup>
- DashDrive v2 <sup>[3](#f3)</sup>
- Governance objects for multi-user accounts (multisig)
- Masternode redundancy planning <sup>[26](#f26)</sup>
- Third-party add-ons for customer DAPI objects / wallet schema versioning
- Automatic form filling for delivery addresses using encrypted blobs
- External storage support to offload blob storage for payment request history and other information 
- Fiat / Credit card support from within wallet, seamless design <sup>[27](#f27)</sup>
- Unofficial Evolution wallets with custom features <sup>[23](#f23)</sup>
- Evolution marketplace / Add-ons / Rating system <sup>[25](#f25)</sup>
- Hardened entropy-based wallet seeding system <sup>[18](#f18)</sup>
- Collateralized mining <sup>[12](#f12)</sup>

# 15.0 - Evolution v3 (TBD)
- Sixth Hiring Wave - Full-time developers
- 50M daily-users supported
- 10 GB Ethernet-handoff / Co-located networking requirement
- 256TX/SEC && 21.34MB blocks <sup>[17](#f17)</sup>
- DashDrive sharding / 4TB HD / 512GB SSD
- GPU based block accelerator
- Masternode shares via governance objects 
- Group-based masternode shares program <sup>[1](#f1)</sup>
- Group-based voting system for picking / dropping hosting providers on group owned masternode
- Group-based voting for network proposals

# 16+ - TBD
- Custom ULBA hardware, PCI-EX or high speed USB 3.0 <sup>[14](#f14)</sup>
- Complete end-to-end open source masternode hardware / with custom silicon for processing high volumes of payments and other information. Important for maintaining exploit free hardware systems. 
- Fully open source / ahead-of-curve solutions for ASIC creation, allowing fair distribution and removing proprietary individual investment which creates imbalances in mining hardware <sup>[19](#f19)</sup>
- v16 - 42.68MB 512TX/S
- v17 - 85.36MB 1024TX/S
- v18 - 170.72MB 2048TX/S 
- v19 - 341.45MB 4096TX/S
  
Footnotes
 
<br /><a name="f1">1</a>: Group of savings accounts which correlate to single group-operated masternode
<br /><a name="f2">2</a>: Sybil-proof system, where each user created has the ability to invite three others; invitee can’t invite anyone (only proper created accounts using default registration system)
<br /><a name="f3">3</a>: Efficient propagation of sub-objects according to user-based quorum filtering
<br /><a name="f4">4</a>: DAPI has no access to user’s addresses / only object updates besides the singular pubkey address which is the user’s publicly-visible, address-based identity in the system.
<br /><a name="f5">5</a>: ADAPI (private Tor-routed DAPI implementation for PrivateSend)
<br /><a name="f6">6</a>: Burn-based credit system for allowing users to update governance objects
<br /><a name="f7">7</a>: Friending system has two objects which point to each other, inverting users into/from fields
<br /><a name="f8">8</a>: Subject to change according to ASU research 
<br /><a name="f9">9</a>: HD (disk-based) storage used for DashDrive governance object storage
<br /><a name="f10">10</a>: SSD storage used for blockchain-only storage / caches 
<br /><a name="f11">11</a>: Blockchain-based masternode quorum record / historic accounting of active masternodes at specific times
<br /><a name="f12">12</a>: System of requiring collateral + mining hardware to create blocks on network. Each collateral allowed to mine block every specific amount of time.
<br /><a name="f13">13</a>: All active masternodes will be sorted into four groups by age. The oldest 25% of the network will be in the first group, the next-oldest 25% will be in the next group, and so on. Masternode quorums will draw 25% of their quorum from each age group. 
<br /><a name="f14">14</a>: X11 hashing, quorum selection, sha/crypto transaction processing and other common functions available via custom hardware allowing for higher network security and higher transaction support
<br /><a name="f15">15</a>: System requires highly interconnected second-tier network with co-located ethernet handoff. VPS co-location should be suffient for first evo release.
<br /><a name="f16">16</a>: Upgrade to 5MB blocks doesn't require specialized hardware.
<br /><a name="f17">17</a>: Base two log-linear growth model, based on mathematically model of crypto-sphere economy and historical growth of the space.
<br /><a name="f18">18</a>: Base two growth model of block sizes beyond this
<br /><a name="f19">19</a>: Easy to remember way of seeding wallets
<br /><a name="f20">20</a>: Internal budget-based investments to create low nanometer / high quality ASIC hardware which offers bleeding edge advantage to the market, cutting out any ability for private investment to gain large advantage over other miners. 
<br /><a name="f21">21</a>: State transitions are calculated to be (200*73*10)*500000/576 bytes, per block, increasing blocksize by 807291 bytes each block, 17% of the total blocksize. 
<br /><a name="f22">22</a>: Tier-2 conceptually is able to handle much larger block propagation, due to having much higher quality network connections. We plan on having large farms of co-located servers, eventually connected using ethernet hand-off. Masternodes located in the same facility can be used for local syncing, allowing more rapid propagation of blocks to catch new servers up. Tier-1 remains permissionless, but also becomes vastly more expensive. Processing of blocks uses custom hardware, allowing for us to process transaction/transition signatures in a parallelized way. 
<br /><a name="f23">23</a>: 868 transactions per block, if assumed 1 transaction per day, per user (lots of assumptions // we need more data). (5TX/SEC + 2TS/SEC)
<br /><a name="f24">24</a>: Second-generation Evolution wallets are software based wallets which expand the object schema to allow internal wallet-to-wallet custom relationships for custom applications such as allowing businesses to have custom wallets for their application. This will allow streamlined applications with easy to use features within subsets of the whole dash economy. 
<br /><a name="f25">25</a>: DashDrive object writes require fees for each object written to the system. The system is designed to use an initial burn of coins, which create a small credit that is tracked in the system, debits are introduced for each operation that is done in relation to Evolution.
<br /><a name="f26">26</a>: Using specialized state transition for maintenance functions Each component of masternode will run redundantly under a load balancer to allow for individual component failure without causing a cascade which creates an outage 
<br /><a name="f27">27</a>: Using third party API keys, allowing user to setup keys in settings then use from wallet seamlessly without ever leaving Dash. 
<br /><a name="f28">28</a>: By leveraging dapi and third party tools, we can deploy addons and a marketplace, which allows custom third party services to integrate directly in the wallet such as debit/credit cards and fiat bank account support 
<br /><a name="f29">29</a>: High-end quality processor like the Xeon, multi-core. Recommend to at least have 8 cores. 
<br /><a name="f30">30</a>: Sporks, our software based forking mechanism will be controlled by a few members of the core-team. Three of five keys will be used as a threshold for activation of specific core-daemon features. This is to stop accidents happening, damaging the network due to neglect or misunderstanding and outright network abuse.
