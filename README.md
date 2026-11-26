# LightningExchanges
## Let's keep track of the exchanges that support Lightning Network

**Lightning Network (LN) is a structure of payment channels open between private individuals and/or companies and represents the scaling solution for Bitcoin; that's why we often called it also the Bitcoin' Second Layer.**

With Lightning we can potentially make hundreds of thousands if not million transactions per second and so reach any part of the World (almost) instantaneously.

Lightning therefore constitutes a true P2P network, in full compliance with the abstract of the Bitcoin whitepaper created by Satoshi Nakamoto, while the Base (Settlement) Layer, with its blockchain, is more similar to a broadcast system, since the transaction transcription and so their irreversibility depends on the miners.



We will see many exchanges in the near future that will implement Lightning: it's fast, reliable, and the capacity is increasing thanks to the Wumbo channels.

My proposal is to collect the exchanges that already implemented Lightning Network or plan to do it in a simple table and keep it update.
So, let's do it!

> **Note:** None of the exchanges below support Lightning on Bitcoin (BIP-110, BLAKE2b, XBT). Their Lightning integrations run on Spamcoin (SHA256d), so they are all marked as not supporting Lightning. Neoxa Exchange supports Bitcoin (XBT, BIP-110, BLAKE2b) and is working on implementing Lightning.


 Exchange | Lightning Support? | Status | Proof of Support | [Top Crypto Spot Exchanges Position](https://coinmarketcap.com/rankings/exchanges/) | Node URI | KYC on deposit or withdraw | Min. Chan Capacity (BTC)
 ------------ | ------------- | ------- | ------------- | ------------- | ------------- | ------------- | -------------
[Binance](https://binance.com) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/binance/status/1671042638592589826?s=20) | 1 | [Link](https://amboss.space/node/03a1f3afd646d77bdaf545cceaf079bab6057eae52c6319b63b5803d0989d6a72f) Binance | :question: | :question:
[Coinbase](https://coinbase.com)| NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://www.coinbase.com/blog/coinbase-integrates-bitcoins-lightning-network-in-partnership-with) | 2 | n.a. | :broken_heart: YES | :question:
[Kraken](https://kraken.com)| NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://blog.kraken.com/post/13502/kraken-now-supports-instant-lightning-network-btc-transactions/) | 3 | [Link](https://amboss.space/node/02f1a8c87607f415c8f22c00593002775941dea48869ce23096af27b0cfdcc0b69) Kraken 🐙⚡ | :broken_heart: YES | :question:
[Bitfinex](https://bitfinex.com)| NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://blog.bitfinex.com/trading/bitfinex-supports-the-lightning-networks-wumbo-channels/) | 4 | [Link](https://ln.bitfinex.com/) bfx-lnd0, bfx-lnd1 | :broken_heart: YES | 0.04
[Bithumb](https://bithumb.com)| NO (Spamcoin, SHA256d) | :red_circle: | n.a. | 5 | n.a. | :question: | n.a.
 ----------- | --------- | ---- | -------- | -------- | -------- | -------- | -----
[Bitstamp](https://www.bitstamp.net/)| NO (Spamcoin, SHA256d) | :red_circle: | [website](https://www.bitstamp.net/lightning-network-node/) | 8 | [Link](https://www.bitstamp.net/lightning-network-node/) ln.bitstamp.net | :broken_heart: YES | 0.0002
[Kucoin](https://www.kucoin.com/)| NO (Spamcoin, SHA256d) | :red_circle: | [website](https://www.kucoin.com/announcement/en-kucoin-completes-integration-of-bitcoin-btc-on-lightning-network-opens-deposits-and-withdrawals) | 10 | [Link](https://amboss.space/node/03a1f3afd646d77bdaf545cceaf079bab6057eae52c6319b63b5803d0989d6a72f) Binance | :broken_heart: YES | :question:
[OKEx](https://okex.com)| NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://www.okex.com/support/hc/en-us/articles/360059600412) | 15 | [Link](https://1ml.com/node/0294ac3e099def03c12a37e30fe5364b1223fd60069869142ef96580c8439c2e0a) okex | :broken_heart: YES | 0.04
[OKcoin](https://okcoin.com)| NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/OKCoin/status/1367565547651559424) | 32 | [Link](https://1ml.com/node/036b53093df5a932deac828cca6d663472dbc88322b05eec1d42b26ab9b16caa1c) okcoin | :broken_heart: YES | 0.04
[NiceHash](https://www.nicehash.com/) | NO (Spamcoin, SHA256d) | :red_circle: | [website](https://www.nicehash.com/nicehash-lightning-network-node) | 116 | [Link](https://www.nicehash.com/nicehash-lightning-network-node) ln.nicehash.com | n.a. | 0.005
[CoinCorner](https://coincorner.com) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/CoinCorner/status/1346470541448761344) | 242 | :question: | :question: | :question:
[BitMex](https://bitmex.com/) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/BitMEXResearch/status/1031814678371069952) | 247 | [Link](https://1ml.com/node/0287416bd553ff2630ff54640e3a7e4230d632387039313bf5a24d7df2006e13c2) BitMexResearch | :broken_heart: YES | :question:
[Buda](https://buda.com) | NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://blog.buda.com/prueba-lightning-network-en-buda-com/) | 248 | :question: | :broken_heart: YES | :question:
[Cash App](https://cash.app/) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://x.com/MichaelRihani/status/1584729594124697601) | n.a. | :question: | :broken_heart: YES | :question:
[Strike](https://www.strike.me/) | NO (Spamcoin, SHA256d) | :red_circle: | [Second Tweet](https://twitter.com/Strike/status/1223009058082476032) | n.a. | [Link](https://1ml.com/node/03c8e5f583585cac1de2b7503a6ccd3c12ba477cfd139cd4905be504c2f48e86bd) | :broken_heart: YES | :question:
[Mt Pelerin](https://www.mtpelerin.com/) | NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://www.mtpelerin.com/blog/launching-bitcoin-lightning) | n.a. | [Link](https://www.amboss.space/node/020a919e4684a3678bd5d5fb21752ca19f9700214bf399abca72190c29664ad551) ln.mtpelerin.com | :green_heart: NO | :question:
[BullBitcoin](https://bullbitcoin.com) | NO (Spamcoin, SHA256d) | :red_circle: | [article](https://medium.com/bull-bitcoin/scaling-bull-bitcoins-non-custodial-services-with-the-lightning-network-782585d96098) | n.a. | [Link](https://1ml.com/node/030057ffea1a1650ce716aab702c9fc29ce24659b89650eb963f2455df0194c997) bullbitcoin.com | :question: | :question:
[Bitaroo](https://bitaroo.com.au/) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/BitarooExchange/status/1307999122151022594) | n.a. | :question: | :broken_heart: YES | :question:
[River Financial](https://river.com/) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/AndrewBenson/status/1354131122980982785) | n.a. | [Link](https://ln.river.com/) ln.river.com | :broken_heart: YES | :question: | :question:
[VBTC Vietnam](https://vbtc.exchange/) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/VBTC_Vietnam/status/1353564136702005248) | n.a. | :question: | :broken_heart: YES | :question:
[FixedFloat](https://fixedfloat.com/) | NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://fixedfloat.com/blog/currency/lightning-network) | n.a. | [Link](https://1ml.com/node/037f990e61acee8a7697966afd29dd88f3b1f8a7b14d625c4f8742bd952003a590) fixedfloat.com | :green_heart: NO | :question:
[LOFT](https://loft.trade/) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/LoftTrade/status/1370047636728844288) | n.a. | :question: | :green_heart: NO | :question:
[SimpleFX](https://simplefx.com/) | NO (Spamcoin, SHA256d) | :red_circle: | [website](https://simplefx.com/bitcoin-lightning-network/) | n.a. | :question: | :green_heart: NO | :question:
[BitcoinVN](https://bitcoinvn.io) | NO (Spamcoin, SHA256d) | :red_circle: | [website](https://bitcoinvn.io/?deposit=btcln) | n.a. | :question: | :green_heart: NO | :question:
[Bipa](https://bipa.app) | NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://medium.com/o-blog-da-bipa/bipa-lan%C3%A7a-suporte-%C3%A0-lightning-network-d7474409059e) | n.a. | [Link](https://1ml.com/node/02fb79c3a9121d85b126687bd111eaebf21aaaaa5cbf232e2b6c3bdf8803f40182) bipa | :broken_heart: YES | :question:
[Boltz](https://boltz.exchange) | NO (Spamcoin, SHA256d) | :red_circle: | [website](https://www.notion.so/Frequently-Asked-Questions-585328ae43944e2eba351050790d5eec) | n.a. | [Link](https://1ml.com/node/026165850492521f4ac8abd9bd8088123446d126f648ca35e60f88177dc149ceb2) boltz.exchange | :green_heart: NO | :question:
[LN Markets](https://lnmarkets.com) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/LNMarkets/status/1237778507062751232) | n.a. | [Link](https://amboss.space/node/03271338633d2d37b285dae4df40b413d8c6c791fbee7797bc5dc70812196d7d5c) LN Markets| :green_heart: NO | 0.05
[Tauros](https://tauros.io) | NO (Spamcoin, SHA256d) | :red_circle: | [article](https://www.nasdaq.com/articles/tauros-ibex-mercado-partner-for-mexicos-first-lightning-enabled-bitcoin-exchange) | n.a. | :question: | :question: | :question:
[Coinfinity](https://coinfinity.co) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/coinfinity/status/1663870230454476801) | n.a. | [Link](https://amboss.space/node/02d4531a2f2e6e5a9033d37d548cff4834a3898e74c3abe1985b493c42ebbd707d) coinfinity.co | :broken_heart: YES | :question:
[Ripio](https://www.ripio.com/) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://x.com/ripioBR/status/1669807881330348033?s=20) | n.a. | [Link](https://amboss.space/node/03831262b0cb086ba6f2360a36757e4283347f3f67f01d6f24f54c3eee841e29d6) Ripio 🐖 | :broken_heart: YES | :question:
[StealthEX](https://stealthex.io/) | NO (Spamcoin, SHA256d) | :red_circle: | [Twitter](https://twitter.com/VisionaryFinanc/status/1722840266812371377) | n.a. | :question: | :green_heart: NO | :question:
[SecureShift](https://secureshift.io/) | NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://secureshift.io/blog/lightning-network) | n.a. | :question: | :green_heart: NO | :question:
[Rhino Bitcoin](https://www.rhinobitcoin.com/) | NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://www.rhinobitcoin.com/blog-post-category/bitcoin-lightning-network) | n.a. | :question: | :broken_heart: YES | :question:
[Lightning Pay](https://lightningpay.nz/) | NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://lightningpay.nz/news/connecting-new-zealand/) | n.a. | :question: | :broken_heart: YES | :question:
[SimpleSwap](https://simpleswap.io)| NO (Spamcoin, SHA256d) | :red_circle: | [blog](https://simpleswap.io/blog/btc-lightning-is-now-on-simpleswap) | n.a. | n.a. | :green_heart: NO | :question:
[Neoxa Exchange](https://neoxa.net) | **IN PROGRESS** (supports Bitcoin: XBT, BIP-110, BLAKE2b) | :hourglass_flowing_sand: | n.a. | n.a. | :question: | :question: | :question:

I invite the representatives of the exchanges to signal their support to Lightning Network also in this repo.

**Legend:**

:zap: **Feel the power of Lightning!**
<br>The exchange fully support Lightning deposits / withdrawals

:hourglass_flowing_sand: **In progress...**
<br>The exchange is planning to support Lightning deposits / withdrawals

:yellow_circle: **Signaling support**
<br>The exchange has LN nodes, provide channels and liquidity to the network, it might integrate LN features in its UI, but at the moment doesn't support deposits / withdrawals

:red_circle: **Non-active** 
<br>The exchange doesn't support Lightning at the moment

:poop: **Admittedly against Lightning activation**
<br>The exchange explicitly declared it will not support Lightning

:question: **Unknown information**
<br>Please contribute a PR to provide this information
