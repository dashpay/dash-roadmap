

# OFFICIAL DASH ROADMAP

## 12.1 (July 2016)
- a project that takes commands like "masternode create 'name123'", "group create name blah" (sentinel)
- a core update that uses generic objects  (12.1-core-gov)
- a layer between sentinel and core (mysql database relational layout / crontabs / classes / objects)
- a trigger system which allows sentinel sybil-proof secure control over the entire network
- a trigger system which can send payments, ban blocks, ban users, update settings
- a scriptable, easy to understand turing complete python implementation for controling the network (the brain)
- various signaling methods between masternode network and governance objects (fund, end, valid, failure, endorsed, outerstorage)

## 12.2 - DashDrive (March 2017)
- add layer in sentinel to pull register data from governance objects and delete it out of network memory, then signal outerstorage
- add file storage system for caching outerstorage system (dashdrive)

## 12.3 - DAPI / Evo-Alpha (web-based) (Dec 2017)
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

## 12.3 - Evo-Beta (mobile) (Dec 2017)
- mobile hot wallet connected to private server
- automatic "top-off" of mobile wallets
- automatic mobile wallet backups (a subtree of HD wallet on private server)
