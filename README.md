# [EasyNOMP](https://github.com/EasyX-Community/EasyNOMP), a fork of [BootNOMP](https://github.com/1301313Y/BootNOMP) and [NOMP](https://github.com/zone117x/node-open-mining-portal)
***Making it easy to install and configure NOMP!***<br />
***Current Version: v1.1.4***

-------

***EasyNOMP pool is live, come mine PEXA @ [https://pool.easyx.cc/](http://pool.easyx.cc/)***<br />
***Visit the Pexa Project website: https://www.pexaproject.com/***

***EasyNOMP has been abandoned due to never ending list of improvements. There may be one or two improvements but no plans to maintain the source code long term.***

-------
### Features
|   | Feature | Developer(s) |
| ------------- | ------------- | ------------- |
| **✓** | **Support for 43 Algorithms** / Such hashing, much blocks! | [foxer666](//github.com/foxer666), [zone117x](//github.com/zone117x), [1301313Y](//github.com/1301313Y) |
| **✓** | **Algorithm Auto-Switching** / To keep you making profit | [foxer666](//github.com/foxer666), [zone117x](//github.com/zone117x), [1301313Y](//github.com/1301313Y) |
| **✓** | **Patches from everywhere** / To keep EasyNOMP working, up to date, and secure | [MooLeshaCat](//github.com/mooleshacat) |
| **✓** | **SSL Enabled Dashboard** / To keep you safe &amp; secure | [MooLeshaCat](//github.com/mooleshacat) |
| **✓** | **Clear Documentation** / To help you install & configure EasyNOMP | [MooLeshaCat](//github.com/mooleshacat) |
| **✓** | **Additional Statistics Information** / To keep you informed | [1301313Y](//github.com/1301313Y) |
| **✓** | **Install Script** / No dependancy problems | [MooLeshaCat](//github.com/mooleshacat) |
| **✓** | **SEO Optimized** / So you don't have to | [1301313Y](//github.com/1301313Y), [MooLeshaCat](//github.com/mooleshacat) |
| **✓** | **Donation Addresses** / To make donation collection easier | [MooLeshaCat](//github.com/mooleshacat) |
| **✓** | **Matomo/Livezilla Support** / To make tracking and support easier | [MooLeshaCat](//github.com/mooleshacat) |
| **✓** | **Multi-coin Block Explorer** / For easier navigation | [MooLeshaCat](//github.com/mooleshacat) |
| **✓** | **Menu + Explorer Icons** / To make block explorer look cool 😎 | [MooLeshaCat](//github.com/mooleshacat) |

-------

### Helping give NOMP & BootNOMP new life, with some style!
***MooLeshaCat:*** _"[EasyX-Community/EasyNOMP](https://github.com/EasyX-Community/EasyNOMP) is built for the [EasyX Community](http://www.easyx.cc/) & [EasyX Pool](http://pool.easyx.cc/). EasyNOMP is based off of [1301313Y/BootNOMP](https://github.com/1301313Y/BootNOMP). It's focus is to add patches, bug fixes, features, and quality documentation to BootNOMP to make it easy to install. BootNOMP gives NOMP a sleek looking new design, and fully re-designed and re-coded user interface! I saw the original dev working on BootNOMP and the source code and figured I could lend a hand. I have plans to rework the documentation, Block Explorer, Docker source, and some various configuration options. I decided a soft fork would be best suited. If you would like to contribute, please consider looking at the parent project [1301313Y/BootNOMP](https://github.com/1301313Y/BootNOMP) and original project [foxer666/node-open-mining-portal](https://github.com/foxer666/node-open-mining-portal) first, as these two guys are the only ones who are helping get the NOMP rebirthing process started."_

***NOTE:*** _Want to help out? You can fork this repository by clicking "fork" in the top right._<br />

-------
### Node Open Mining Portal consists of 3 main modules:
| Project | Link |
| ------------- | ------------- |
| [EasyNOMP](https://github.com/EasyX-Community/EasyNOMP) | https://github.com/EasyX-Community/EasyNOMP |
| [Stratum Pool](https://github.com/EasyX-Community/node-stratum-pool) | https://github.com/EasyX-Community/node-stratum-pool |
| [Node Multihashing](https://github.com/EasyX-Community/node-multi-hashing) | https://github.com/EasyX-Community/node-multi-hashing |

***NOTE:*** _Stratum Pool can be replaced with [node-merged-pool](https://github.com/UNOMP/node-merged-pool) - https://github.com/UNOMP/node-merged-pool._<br />
***NOTE:*** _Node Multihashing can be replaced with [node-multi-hashing](https://github.com/EasyX-Community/node-multi-hashing) - https://github.com/EasyX-Community/node-multi-hashing._

-------
### Requirements
***NOTE:*** _These requirements will be installed in the install section!_<br />
* Coin daemon(s)
* Node Version Manager
* Node 8.1.4 or higher
* Process Manager 2 / pm2
* Redis Server
* ntp

-------
### License
Released under the GNU General Public License v2
http://www.gnu.org/licenses/gpl-2.0.html

-------
### Install Pool

Install instructions are in the directory [docs/README.md](https://github.com/EasyX-Community/EasyNOMP/blob/master/docs/INSTALL.md)

-------
### Configure Pool

Pool configuration instructions are at the EasyNOMP Wiki: https://github.com/EasyX-Community/EasyNOMP/wiki

-------
### Run in Docker

Docker instructions are in in the directory [docs/README.md](https://github.com/EasyX-Community/EasyNOMP/blob/master/docs/DOCKER.md)

-------
### Troubleshooting

Troubleshooting is in in the directory [docs/TROUBLESHOOTING.md](https://github.com/EasyX-Community/EasyNOMP/blob/master/docs/TROUBLESHOOTING.md)

-------
### Changelog

Changelog is in in the directory [docs/CHANGELOG.md](https://github.com/EasyX-Community/EasyNOMP/blob/master/docs/CHANGELOG.md)

-------
### Hashing algorithms
#### Working
|   | Algorithm | Comment|
| ------------- | ------------- | ------------- |
| ✓ | __C11__ | tested shares and payments with Dixicoin |
| ✓ | __Groestl__ | tested only shares with AuroraCoin, blocks not tested |
| ✓ | __lyra2rev2__ | shares work, needs tests with payments. currently being tested with Lunex coin |
| ✓ | __lyra2z__ | Working in testnet *mining* and *payouts* |
| ✓ | __NeoScrypt__ | working now thanks to @foxer666 pushing update to parent repo |
| ✓ | __Qubit__ | Shares works, and blocks should now too. |
| ✓ | __Scrypt__ | tested with AntiLiteCoin, 1CREDIT, ArgusCoin, WAYAWOLFCOIN and many others |
| ✓ | __SHA256__ | tested with VCOIN, don't use with BTC, no Segwit tested |
| ✓ | __X11__ | tested with BrainCoin, CannabisCoin, AdzCoin and many others |
| ✓ | __X16r__ | tested with RavenCoin, TragoCoin - Fail: BitCash |
| ✓ | __Yescrypt__ | needs tests, though should work |
| ✓ | __YescryptR16__ | needs tests, though should work |
| ✓ | __YescryptR32__ | currently being tested with WaviCoin. shares work, payments unconfirmed |

#### Need tests
|   | Algorithm | Comment|
| ------------- | ------------- | ------------- |
| ? | __Argon2__ | need tests |
| ? | __Blake__ | need tests |
| ? | __Blake2S__ | need tests |
| ? | __Cryptonight__ | need tests |
| ? | __Dcrypt__ | need tests |
| ? | __Decred__ | need tests |
| ? | __Fresh__ | need tests |
| ? | __Fugue__ | need tests |
| ? | __GroestlMyriad__ | need tests |
| ? | __Quark__ | need tests |
| ? | __Hefty1__ | need tests |
| ? | __Keccak__ | need tests |
| ? | __Lbry__ | need tests |
| ? | __lyra2re__ | need tests |
| ? | __lyra2re2__ | need tests |
| ? | __lyra2z330__ | need tests |
| ? | __NIST5__ | need tests |
| ? | __S3__ | need tests |
| ? | __Scrypt-N__ | need tests |
| ? | __Scrypt-OG__ | need tests |
| ? | __Sha1__ | need tests |
| ? | __SHAvite-3__ | need tests |
| ? | __Skein__ | need tests |
| ? | __X11Ghost__ | need tests |
| ? | __X13__ | need tests |
| ? | __X14__ | need tests |
| ? | __X15__ | need tests |
| ? | __X16Rv2__ | need tests |
| ? | __zr5__ | need tests |
| ? | __ziftr__ | need tests |

#### Don't work yet
|   | Algorithm | Comment|
| ------------- | ------------- | ------------- |
| - | __Scrypt-Jane__ | submitblock not working tested with CacheCoin, Yacoin |

-------
### Screenshots
#### Home<br />
![Home](https://raw.githubusercontent.com/EasyX-Community/EasyNOMP/master/docs/screenshots/home.png)

#### Pool Stats<br />
![Pool Stats](https://raw.githubusercontent.com/EasyX-Community/EasyNOMP/master/docs/screenshots/poolstats.png)<br /><br />

#### Miner Stats<br />
![Miner Stats](https://raw.githubusercontent.com/EasyX-Community/EasyNOMP/master/docs/screenshots/minerstats.png)<br /><br />

#### Block Explorer<br />
![Block Explorer](https://raw.githubusercontent.com/EasyX-Community/EasyNOMP/master/docs/screenshots/blockexplorer.png)<br /><br />

-------
### Credits
| User | Comment|
| ------------- | ------------- |
| [MooLeshaCat](//github.com/mooleshacat) / [EasyX-Community](//github.com/EasyX-Community/) | - Fixed lots of documentation, configuration, and block explorer<br /> - Fixed some API and Redis issues<br /> - Made block explorer multi-coin<br /> - Added cool icons to block explorer + menu |
| [foxer666](//github.com/foxer666) | How could anyone forget the original [foxer666/node-open-mining-portal](https://github.com/foxer666/node-open-mining-portal) devs? |
| [zone117x](//github.com/zone117x) | How could anyone forget the original [zone117x/node-open-mining-portal](https://github.com/zone117x/node-open-mining-portal) devs? |
| [1301313Y](//github.com/1301313Y) | How could anyone forget the original [1301313Y/BootNOMP](https://github.com/1301313Y/BootNOMP) dev? |
| &nbsp; | &nbsp; |
| [a2hill](//github.com/a2hill) | helped with X16r |
| [devnulled](//github.com/devnull-ed) | helped with lyra2z, neoscrypt algo |
| [Kris Klosterman / krisklosterman](https://github.com/krisklosterman) | Updated code for work with Node.JS >=8 |
| [Jerry Brady / mintyfresh68](https://github.com/bluecircle) | got coin-switching fully working and developed proxy-per-algo feature |
| [Tony Dobbs](http://anthonydobbs.com) | designs for front-end and created the NOMP logo |
| [LucasJones](//github.com/LucasJones) | got p2p block notify working and implemented additional hashing algos |
| [UdjinM6](//github.com/UdjinM6) | helped implement fee withdrawal in payment processing |
| [Alex Petrov / sysmanalex](https://github.com/sysmanalex) | contributed the pure C block notify script |
| [svirusxxx](//github.com/svirusxxx) | sponsored development of MPOS mode |
| [icecube45](//github.com/icecube45) | helping out with the repo wiki |
| [yoshuki43](//github.com/yoshuki43) | his K-Nomp project has really help the development! |

***Those that contributed to [node-stratum-pool](//github.com/zone117x/node-stratum-pool#credits)***

-------

### Plz Buy Me Some Coffee?

Donate if you like, but not much development is being done. I may add a few easy to do features. If you would like to take over, simply fork the repository by clicking "fork" in the top right.


BTC: `bc1qffd7j4jdspfjc8mr05g8yqfncjfdnzamec53tr`

LTC: `ltc1q8afdasd2qanphs82rqvetzu8yrk2kq6y4fqvrn`

ETC: `0x9e640ED8A6dE77D175b7c600A694426a00Cd16c2`

ETH/ERC20: `0x784207DC134B61E0bD7edA658aa830e8FD12A7c7`

ZEN: `znWtGC6b3FXn8kY5ewgfy2LfP1ppL9CF1Tc`

BSC: `0x784207DC134B61E0bD7edA658aa830e8FD12A7c7`

XMR: `84wwa7EKo8uasZAHijHKtBTuBaMPuNjCJgnfGJrsLFo4aZcfrzGvUX33sSeFNdno8fPiTDGnz4h1bCvsdFQYWRuR2619FzS`

-------

***EOF***
