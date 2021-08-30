
# ![StrongHands Masternode](https://raw.githubusercontent.com/stronghands-official/assets/main/shmn-logo-100x100.svg)
# StrongHands Masternode Core integration/staging repository

## What is SHMN?

SHMN is an open source community-driven cryptocurrency, focused on five main aspects:

* (1) User Data Protection: Through the use of SHIELD, a zk-SNARKs based privacy protocol.

* (2) Low environmental footprint and network participation equality: Through the use of a highly developed Proof of Stake protocol.

* (3) Decentralized Governance System: A DAO built on top of the tier two Masternodes network, enabling a monthly community treasury, proposals submission and decentralized voting.

* (4) Fast Transactions: Through the use of fast block times and the tier two network, SHMN is committed to continue researching new and better instant transactions mechanisms.

* (5) Ease of Use: SHMN is determined to offer the best possible graphical interface for a core node/wallet. A full featured graphical product for new and advanced users.

More information and specs at [StrongHands Academy](https://docs.stronghands.info). Join the community at [StrongHands Blockchain Discord](https://discord.gg/gb8QWDx).

## License
SHMN Core is released under the terms of the MIT license. See [COPYING](https://github.com/stronghands-official/SHMN-source/blob/master/COPYING) for more information or see https://opensource.org/licenses/MIT.

## Development Process

The master branch is regularly built (see doc/build-*.md for instructions) and tested, but it is not guaranteed to be completely stable. [Tags](https://github.com/stronghands-official/SHMN-source/tags) are created regularly from release branches to indicate new official, stable release versions of SHMN Core.

The contribution workflow is described in [CONTRIBUTING.md](https://github.com/stronghands-official/SHMN-source/blob/master/CONTRIBUTING.md) and useful hints for developers can be found in [doc/developer-notes.md](https://github.com/stronghands-official/SHMN-source/blob/master/doc/developer-notes.md).

## Testing

Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people a lot of money.

## Automated Testing

Developers are strongly encouraged to write [unit tests](https://github.com/stronghands-official/SHMN-source/blob/master/src/test/README.md) for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make check. Further details on running and extending unit tests can be found in [/src/test/README.md](https://github.com/stronghands-official/SHMN-source/blob/master/src/test/README.md).

There are also regression and integration tests, written in Python. These tests can be run (if the test dependencies are installed) with: test/functional/test_runner.py`

The CI (Continuous Integration) systems make sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

## Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.


# StrongHands Masternode (SHMN) Specifications

![SHMN](https://raw.githubusercontent.com/stronghands-official/assets/695773fea72e8dc15a90acd7eecf3ce18c7ff840/shmn-logo-20x20.svg) *Coin Specs* | &nbsp;
------------ | -------------
  Name: | StrongHands Masternode
  Ticker: | SHMN
  PoW Algo: | Quark
  Required Coins for a Masternode: | 1,000 SHMN
  Reward System: | Masternode and PoS
  PoS Minimum Stake Age: | 7 days
  PoS Reward: | 5 coins/block
  Blocktime: | 180 seconds
  Total Supply: | 15,000,000 SHMN
  Port: | 50005
  RPC: | 50006
  FullNode Core Wallets | [SHMN Releases (v.2.4 stable)](https://github.com/stronghands-official/SHMN-source/releases/tag/v2400)
  

 ## Bootstrap Nodes
---
Choose to add any of the following bootstrap nodes, per your preferred network configuration, to speed up peer discovery. Utilize addnode=HOSTNAME in your shmn.conf file.

#### IPV4

* dnsseed.shmn.stronghands.info
* shmn.explorer.stronghands.info
* node1.shmn.stronghands.info
* node2.shmn.stronghands.info
* 143.244.208.76
* 143.198.155.198

#### IPV6

* [2604:a880:4:1d0::297:e000]
* [2607:4f00:0:509::3]
* [2a01:4f8:10a:232d::48]
* [2a02:c207:2041:5161::5]
