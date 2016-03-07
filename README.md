# paper
区块链技术相关的论文、文档

## 索引
* [angaroa: a Byzantine Fault Tolerant Raft](docs/copeland_zhong.pdf): Hyperledger的原型Juno的共识算法Angaroa的白皮书
* [Angaroa的实现 repo](https://github.com/chrisnc/tangaroa) 
* [Juno repo](https://github.com/blockchain-university/juno) : Hyperledger的原型Juno
* [BigchainDB: A Scalable Blockchain Database(DRAFT)](docs/bigchaindb-whitepaper.pdf)
* [Rootstock white paper](docs/RootstockWhitePaperv8-Overview.pdf)
* [Lightning-newwork paper](docs/lightning-network-paper.pdf)
* [Cryptonote white paper](docs/cryptonote_whitepaper.pdf)
* [IOTA white paper(Tangle/DAG)](docs/tangle.pdf)
* [普林斯顿大学的比特币教程](docs/princeton_bitcoin_book.pdf)
* [以太坊黄皮书](docs/ethereum_yellow_paper.pdf)
* [Understanding Serenity, Part I: Abstraction](https://blog.ethereum.org/2015/12/24/understanding-serenity-part-i-abstraction/): [中文翻译](http://ethfans.org/posts/understanding-serenity-part-i-abstraction)
* [Understanding Serenity, Part 2: Casper](https://blog.ethereum.org/2015/12/28/understanding-serenity-part-2-casper/): [中文翻译](http://ethfans.org/posts/understanding-serenity-part-ii-casper)
* [隔离见证技术 - set wit: segregated witness](http://www.8btc.com/segregated-witness-is-cool)
* [IBLTs: 可逆式布鲁姆查找表(IBLT) , 如何促进比特币的去中心化](http://www.8btc.com/iblts-bitcoin-decentralization), 弱区块（weak blocks），瘦区块（thin blocks），一个“blocktorrent”协议; Invertible Bloom Lookup Table. 
* Matt Corallo的快中继网络（fast relay network）
* [Bitcoin NG](http://www.8btc.com/bitcoin-ng-2)
* [TaPOS](http://www.bts.hk/tapos-baipishu.html)
* [SkuChain](http://www.skuchain.com/): 供应链管理， [code](https://github.com/thingchain)
* [Factom](): 公正通. Factom是一个P2P的协议, 它在比特币的区块链上维护了一个数据层。 网络文件和应用被压缩成一个Merkle树上的哈希值并被存储在比特币的区块链上。Proof of existence.
* [Blockstack.io](https://blockstack.io/): 被数字资产公司收购
* [CoinSpark](https://coinspark.org/): 数字资产管理
* [MultiChain](http://www.multichain.com/): Open platform for building blockchains, It is a [DIY permissioned blockchain](http://bitcoinist.net/multichain-diy-permissioned-blockchain/). [Withe paper](http://www.multichain.com/white-paper/)
* [LightningNetwork](https://github.com/LightningNetwork/lnd): [Paper](https://github.com/LightningNetwork/paper)
* [BlackCoin](http://blackcoin.co/): POS2.0, 3.0, [CodeBase](https://github.com/rat4/blackcoin)
* [BlackHalo](http://blackhalo.info/) : Smart Contract, The first of its kind to support two-party contracts, Joint Accounts & More! 
* [Greedy Heaviest Observed Subtree(GHOST)](http://www.cs.huji.ac.il/~avivz/pubs/13/btc_scalability_full.pdf) : 以太坊使用的GHOST协议，使用tree来存储交易数据
* [IOTA](http://iotatoken.com/): [介绍](http://cointelegraph.com/news/iota-a-blockchain-less-gasp-token-for-the-internet-of-things), 面向IOT物联网，支持微支付，抗量子计算机，使用DAG（也叫Tangle）数据结构来组织区块，Tangle-blockchain[白皮书](http://188.138.57.93/tangle.pdf)
* [Emercoin](https://github.com/EvgenijM86/emercoin/): 采用STUN协议来实现P2P网络，可以与webrtc兼容 。 [代码](https://github.com/EvgenijM86/emercoin/), POW + POS , fork from [ppcoin](https://github.com/ppcoin/ppcoin)
* [openchain](https://www.openchain.org/) : client-server架构的chain，ibm贡献的代码，c#开发，适合企业内部使用
* [GitTorrent](https://github.com/conseweb/GitTorrent): 一个使用bittorrent + bitcoin构建的去中心化的github. [Blog](http://blog.printf.net/articles/2015/05/29/announcing-gittorrent-a-decentralized-github/)

## 相关文章
* [精通比特币](http://www.zhibimo.com/read/wang-miao/mastering-bitcoin/index.html)
* [how to program block chain explorers with python part 1](http://alexgorale.com/how-to-program-block-chain-explorers-with-python-part-1)
* [How to Put Custom Messages Into Bitcoin Blockchain - OP_RETURN](http://wlangiewicz.com/blog/2014/10/24/how-to-put-custom-messages-into-bitcoin-blockchain-op-return/)
* [How to write a bit torrent client](http://www.kristenwidman.com/blog/33/how-to-write-a-bittorrent-client-part-1/)
* [A simple Distributed Hash Table (DHT)](https://rezahok.wordpress.com/2009/09/21/a-simple-distributed-hash-table-dht/)
* [Tempering Kademlia with a Robust Identity Based System](http://www.lajello.com/papers/p2p08.pdf)
* [TrustedKad –Application of Trust MechanismstoaKademlia-BasedPeer-to-Peer Network](https://duepublico.uni-duisburg-essen.de/servlets/DerivateServlet/Derivate-37616/Dissertation_Kohnen.pdf)
* [S/Kademlia: A Practicable Approach Towards Secure Key-Based Routing](http://www.tm.uka.de/doc/SKademlia_2007.pdf): 基于加密学生成随机的nodeid以保证系统免受攻击
* [Kademlia](https://zh.wikipedia.org/wiki/Kademlia)
* [DemocratizingcontentpublicationwithCoral](https://www.coralcdn.org/docs/coral-nsdi04.pdf)
* [Decentralized Reddit using a DHT to store content and a blockchain to rank it](https://news.ycombinator.com/item?id=10391996) : Many other ideas about blockchains. 
* [PolderCast: Fast, Robust, and ScalableArchitecture for P2P Topic-based Pub/Sub](http://acropolis.cs.vu.nl/~spyros/www/papers/PolderCast.pdf)
* [Bitcoin-NG: A Scalable Blockchain Protocol](http://arxiv.org/pdf/1510.02037.pdf)
* [LINKABLE RING SIGNATURES OVER ELLIPTIC CURVES](https://jesper.borgstrup.dk/2014/04/linkable-ring-signatures-over-elliptic-curves/)
* [Ring signature implementation with python](http://everything.explained.today/Ring_signature/)
* [Bitcoin in Bloom: How IBLTs Allow Bitcoin to Scale: 使用IBLTs来增强比特币的可扩展性](https://www.cryptocoinsnews.com/bitcoin-in-bloom-how-iblts-allow-bitcoin-scale/)
* [使用IBLT来减少区块的传播速度](https://gist.github.com/gavinandresen/e20c3b5a1d4b97f79ac2)
* [BitGit](http://luke.dashjr.org/programs/bitcoin/) ： 相关开源项目的汇集

## 比特币、区块链相关可参考的项目
* [比特币协议说明](https://zh-cn.bitcoin.it/wiki/%E5%8D%8F%E8%AE%AE%E8%AF%B4%E6%98%8E)
* [A(nother) Bittorrent client written in the go programming language
](https://github.com/jackpal/Taipei-Torrent)
* [Full-featured BitTorrent client package and utilities](https://github.com/anacrolix/torrent)
* [A Golang port of peerflix.](https://github.com/Sioro-Neoku/go-peerflix)
* [dht: Kademlia/Mainline DHT node in Go.](https://github.com/nictuku/dht)
* [coinbits : A Python library for bitcoin peer to peer communication](https://github.com/8468/coinbits)
* [protocoin: A pure Python Bitcoin protocol implementation](https://github.com/perone/protocoin): [doc](http://protocoin.readthedocs.org/)
* [kademlia: A DHT in Python Twisted](https://github.com/bmuller/kademlia)
* [An alternative full node bitcoin implementation written in Go (golang)](https://github.com/btcsuite/btcd)
* [A secure bitcoin wallet daemon written in Go (golang)](https://github.com/btcsuite/btcwallet)
* [gocoin: Full bitcoin solution written in Go (golang)](https://github.com/piotrnar/gocoin)
* [bitcoinj: A library for working with Bitcoin with java](https://github.com/bitcoinj/bitcoinj)
* [dht_store](http://www.libtorrent.org/dht_store.html) : This is a proposal for an extension to the BitTorrent DHT to allow storing and retrieving of arbitrary data.
* [BlockStore](https://github.com/blockstack/blockstore): Name registrations on the Bitcoin blockchain with external storage
* [pydht](https://github.com/isaaczafuta/pydht): Python implementation of the Kademlia DHT data store
* [A way to experiment with Bitcoin.](https://github.com/gak/docker-bitcoin-regtest)
* [pyp2p](https://github.com/Storj/pyp2p)
* [python-OP_RETURN: Simple Python commands and library for using bitcoin OP_RETURNs](https://github.com/coinspark/python-OP_RETURN)
* [A Common Blockchain interface for the Bitcoin Core RPC.](https://github.com/blockai/rpc-common-blockchain): 一个接口规范
* [abstract-common-blockchain](https://github.com/blockai/abstract-common-blockchain): A test suite and interface you can use to implement standard Bitcoin blockchain API calls for various backends and platforms.
* [CryptoNote](https://github.com/cryptonotefoundation/cryptonote): CryptoNote protocol implementation. This is the reference repository for starting a new CryptoNote currency. See /src/cryptonote_config.h https://cryptonote.org/
* [Colored-Coins](https://github.com/Colored-Coins): The Open Source Protocol for Creating Digital Assets On The Bitcoin Blockchain. 基于比特币区块链创建、管理数字资产的开源协议。
* [CounterParty](http://counterparty.io/)
* [crypti](https://crypti.me/)
* [ipfs](https://github.com/ipfs/ipfs): IPFS - The Permanent Web
* [Open Assets Protocol](https://github.com/OpenAssets/open-assets-protocol)
* [Telehash](http://telehash.org/) : [source](https://github.com/telehash)
* [BlockName](https://github.com/telehash/blockname): A blockchain-backed DNS resolver
* [How to create genesis block](https://github.com/lhartikk/GenesisH0)
* [Factom](https://github.com/FactomProject/FactomCode): 
* [BitShares](https://bitshares.org/): BitShares is an industrial-grade financial blockchain smart contracts platform.
* [Blockstream](https://blockstream.com/): 侧链创业公司。 Blockstream’s core area of innovation is sidechains, a technology focused on improving on the blockchain, the most powerful public utility for distributed trust systems.
* [openpublish: A publishing protocol for registering media as a digital asset on the Bitcoin blockchain.](https://github.com/blockai/openpublish): 数字内容、数字资产注册、发布平台，产权可以方便转移，交换，而且可以很准确的统计阅读数
* [bitstore]()
* [bitstore-client: A content-addressable file hosting and distribution service that uses Bitcoin public key infrastructure for authentication and payment.](https://github.com/blockai/bitstore-client)
* [abstract-common-wallet](https://github.com/blockai/abstract-common-wallet): 钱包通用服务接口
* [my-two-bits](https://github.com/blockai/my-two-bits)：付费评论系统
* [Blockai](https://www.blockai.com) : 一种数字内容发布、管理平台，似乎可以用来对盗版影视剧的解决

