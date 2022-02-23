<p align="center">
  <img width="200" height="200" src="https://raw.githubusercontent.com/stronghands-official/assets/main/shmn-logo-100x100.svg">

 ![In Development](http://img.shields.io/static/v1?label=STATUS&message=UNDER%20REVISION&color=RED&style=for-the-badge)
  
# StrongHands Masternode Core integration/staging repository
</p>
  
## What is SHMN?

SHMN is an open source community-driven cryptocurrency, focused on five main aspects:

* (1) User Data Protection: Through the use of SHIELD, a zk-SNARKs based privacy protocol.

* (2) Low environmental footprint and network participation equality: Through the use of a highly developed Proof of Stake protocol.

* (3) Decentralized Governance System: A DAO built on top of the tier two Masternodes network, enabling a monthly community treasury, proposals submission and decentralized voting.

* (4) Fast Transactions: Through the use of fast block times and the tier two network, SHMN is committed to continue researching new and better instant transactions mechanisms.

* (5) Ease of Use: SHMN is determined to offer the best possible graphical interface for a core node/wallet. A full featured graphical product for new and advanced users.


## About StrongHands

StrongHands is a large community of financial activists, investors and enthusiasts engaged to free the people from state control of your money.

### Join the community 

* [Discord Community](https://discord.gg/gb8QWDx)
* [Telegram Main Channel](https://t.me/stronghandsofficial)
* [Twitter](https://twitter.com/shmnofficial)


## License
SHMN Core is released under the terms of the MIT license. See [COPYING](https://github.com/stronghands-official/SHMN-source/blob/master/COPYING) for more information or see https://opensource.org/licenses/MIT.

## Development Process

The master branch is regularly built (see doc/build-*.md for instructions) and tested, but it is not guaranteed to be completely stable. [Tags](https://github.com/stronghands-official/SHMN-source/tags) are created regularly from release branches to indicate new official, stable release versions of SHMN Core.

The contribution workflow is described in [CONTRIBUTING.md](https://github.com/stronghandsblockchain/SHMN-NewSource//blob/master/CONTRIBUTING.md) and useful hints for developers can be found in [doc/developer-notes.md](https://github.com/stronghandsblockchain/SHMN-NewSource/blob/master/doc/developer-notes.md).

## Testing

Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people a lot of money.

## Automated Testing

Developers are strongly encouraged to write [unit tests](https://github.com/stronghandsblockchain/SHMN-NewSource/blob/master/src/test/README.md) for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make check. Further details on running and extending unit tests can be found in [/src/test/README.md](https://github.com/stronghandsblockchain/SHMN-NewSource/blob/master/src/test/README.md).

There are also regression and integration tests, written in Python. These tests can be run (if the test dependencies are installed) with: test/functional/test_runner.py`

The CI (Continuous Integration) systems make sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

## Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.


# StrongHands Masternode (SHMN) Specifications

<img align="left" width="18" height="18" src="https://raw.githubusercontent.com/stronghands-official/assets/main/shmn-logo-100x100.svg"> *Coin Specs* | &nbsp; 
------------ | -------------
  Name: | StrongHands Masternode
  Ticker: | SHMN
  PoW Algo: | Quark
  Required Coins for a Masternode: | 1,000 SHMN
  Reward System: | Masternode (70%) and PoS (30%)
  PoS Minimum Stake Age: | 7 days
  PoS Reward: | 5 coins/block
  Blocktime: | 180 seconds
  Total Supply: | 15,000,000 SHMN
  Port: | 50005
  RPC: | 50006
  Full Node Core Wallets | [SHMN Releases (v2400 latest)](https://github.com/stronghandsblockchain/SHMN-NewSource/releases/tag/v2400)
  Full Blockchain: speed up sync | [Bootstrap](https://bootstrap.stronghands.info/shmnboot_strap.zip)
  How to Setup a Masternode | [Guide](https://github.com/stronghandsblockchain/SHMN-masternode-setup)
  

# SHMN Masternode Stats
You can check the Network stats, ROI calculation, price and paid rewards in the last 24h at [masternodes.online](https://masternodes.online/currencies/SHMN/) page.

[MNO](https://masternodes.online/currencies/SHMN/) is a masternode coin monitoring and stats service. MNO does not research or recommend any coin. Do your own research and invest at your own risk.

ROI changes often and is not the most important factor. Please consider Dev Team - Community - PURPOSE/Platform - Liquidity - Wallet when making masternode purchases.

## PS: Always use a VPN on all your devices 
Virtual Private Network (VPN) is highly recommended to use when operating with cryptocurrencies. With so many threats and blocks emerging against a decentralized economy, VPN adds extra protection by hiding your data. It helps to overcome censorship and ISP Block rules and protects your privacy.

#### How to choose a VPN?
There are many options on the internet out there. Which VPN to choose is really up to you. Depending on your demands, you can choose a paid VPN (which usually costs around $4 per month) or search for free versions. Keep in mind, free options usually have limitations and may affect your internet speed.
We can recommend using [NordVPN](https://nordvpn.com/download/) or [Proton VPN](https://account.protonvpn.com/signup).                                         

For mobile users - [TurboVPN](https://play.google.com/store/apps/details?id=free.vpn.unblock.proxy.turbovpn&hl=en) is a good solution.
If you are eager to learn more about VPN technology - articles from this [website](https://thebestvpn.com/what-is-vpn-beginners-guide/) might be handy.


 ## Bootstrap Nodes

Choose to add any of the following bootstrap nodes, per your preferred network configuration, to speed up peer discovery. Utilize addnode=HOSTNAME in your shmn.conf file.
##### **A complete list of wallets that have connected to this node in the last 24hours you can find [here](http://shmn.explorer.stronghands.info/network#addnodes).**

### External WhiteListing IPV4
* whitelist=199.127.140.224
* whitelist=199.127.140.225
* whitelist=199.127.140.235
* whitelist=199.127.140.236

### External WhiteListing IPV6
* whitelist=[2604:6800:5e11:3611::1]
* whitelist=[2604:6800:5e11:3611::2]
* whitelist=[2604:6800:5e11:3614::3]
* whitelist=[2604:6800:5e11:3614::4]


## How to compile SHMN-source

Clone the source in a linux terminal using windows sub system or a vps and start the selection.
```
sudo git clone https://github.com/stronghands-official/SHMN-source.git && sudo chmod -R 755 SHMN-source && cd SHMN-source/compile && sudo ./compile.sh 
```


## Where to buy?

* [CATEX.io - SHMN/BTC](https://www.catex.io/trading/SHMN/BTC?load=1)
* [CATEX.io - SHMN/TRX](https://www.catex.io/trading/SHMN/TRX)


## No Sync and network problems?

* Please download the last version of our shmn.conf file [here](https://github.com/stronghandsblockchain/SHMN-NewSource/tree/master/contrib/debian/examples) and substitute the old one in SHMN folder in your Win/Mac/Linux system. For more assistance come to our Telegram group: https://t.me/SHNDsupport
