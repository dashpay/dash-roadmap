

# OFFICIAL DASH ROADMAP

## 12.1 (July 2016)
- a project that takes commands like "masternode create 'name123'", "group create name blah" ([sentinel](https://github.com/evan82/sentinel/))
- a core update that uses generic governance objects ([12.1-core-gov](https://github.com/evan82/dash/blob/v0.12.1.x-gov/src/governance.h#L209))
- a decoupling layer between sentinel and dash-core ([mysql database relational layout / crontabs / classes / objects](https://github.com/evan82/sentinel/blob/master/database/001.sql))
- a trigger system which allows sentinel sybil-proof secure control over the entire network ([governance-misc.h](https://github.com/evan82/dash/blob/v0.12.1.x-gov/src/governance-misc.h#L27))
- a trigger system which can send payments, ban blocks, ban users, update settings
- a scriptable, easy to understand turing complete python implementation for controling the network ([brain.py](https://github.com/evan82/sentinel/blob/master/lib/brain.py))
- various signaling methods between masternode network and governance objects ([fund, end, valid, failure, endorsed, outerstorage](https://github.com/evan82/dash/blob/v0.12.1.x-gov/src/governance-vote.h#L28))
- support for users, groups, companies, contracts, proposals, projects, project-milestones and project-reports ([classes.py](https://github.com/evan82/sentinel/blob/master/lib/classes.py))

## 12.2 - DashDrive (March 2017)
- add layer in sentinel to pull register data from governance objects and delete it out of network memory, then signal outerstorage
- add file storage system for caching outerstorage system (dashdrive)

## 12.3 - DAPI / Evo-Alpha (web-based) (Jan 2018)
- login to personal server from dash.org using username and password
- keep private balance
- local accounts
- 2 factor security
- full node per user
- supports autopay
- supports masternodes
- supports proposal/contract/user/group creation / management
- flat fees set by sentinel
- autonomous attack deflection
- USD balance support (cryptocapital)
- Automatic movement of funds between USD and Dash (bots on your private server, apis for polo, etc) 

## 12.4 - Evo-Beta (mobile) (Aug 2018)
- mobile hot wallet connected to private server
- automatic "top-off" of mobile wallets
- automatic mobile wallet backups (a subtree of HD wallet on private server)

## 13.0 - Evo v1 - Proof-Of-Work 2.0
- collateralized mining implementation which supports energy efficiency mode
- use mining network simply for hashes, masternode network will determine validity of data
