# Studying to do list

App 與 DApp
 - APP <-> 後端 <-> DB數據庫
   
   傳統 App 不論是 native 或是 web-based application，都是與特定組織（國家）的後端系統互動。

 - DAPP <-> 以太坊虛擬機上的[智能合約](https://blockcast.it/2018/03/11/what-is-a-smart-contract/) <-> 區塊鏈網路
   
   去中心化 App（DecentralizedApplications，DApp）是透過智能合約對接區塊鏈，藉著區塊鏈去中心化的特性可以有若干好處：
   - 解耦特定組織（國家）對系統的影響
   - 利益的分配是对全部参与者都公平的

   ![App 與 DApp 差別示意圖](https://www.researchgate.net/publication/342343000/figure/fig2/AS:904663155109888@1592699912831/Traditional-web-application-architecture-vs-DApp-architecture.jpg)

   [[figure 1]](https://www.researchgate.net/figure/Traditional-web-application-architecture-vs-DApp-architecture_fig2_342343000)

<hr>

DApp 概念資訊：

2020 年開始，區塊鏈 web3.0 顯露趨勢，以 Ethereum 與 Polkadot 為主的 web3.0 生態體系正在快速建構。
以太坊的主流功能是智能合約，但構成 web3.0 的 "去中心化數據存儲 swarm" 和 "信息通訊協議 whisper" 也同樣重要。

<hr>

DApp 開發：

[DApp Mobile API (native)](https://geth.ethereum.org/docs/dapp/mobile)

[Build your first Android Dapp using Web3j and Infura](https://medium.com/@madhurakunjir2611/build-your-first-android-dapp-using-web3j-and-infura-36d2596c1e2a)

[Bitfinex API 使用](https://easonwang.gitbook.io/blockchain/bitfinex-api-shi-yong)




摸索：[指引开发 imToken DApp](https://imtoken.gitbook.io/developers/v/zh/products/webview/development-guide-for-imtoken-dapp)
 - 直接體驗 imToken [官方 DApp 範例專案](https://github.com/consenlabs/token-getting-started)
   
   安裝 imToken App，註冊登入後透過右上角的 QR Code 掃碼功能掃描 [QR Code](https://imtoken.gitbook.io/developers/v/zh/products/webview/development-guide-for-imtoken-dapp#zhi-jie-yu-lan-xiang-mu)
 - Clone 官方 DApp 範例專案，參考上一部的體驗內容追蹤程式碼
   > git clone git@github.com:consenlabs/token-getting-started.git

   [TransactionEncoder.signMessage方法代码示例](https://vimsky.com/examples/detail/java-method-org.web3j.crypto.TransactionEncoder.signMessage.html)
 - 如何部署 DApp？
   > yun install && yun run dev

   部署就老樣子
   觀察上方的體驗功能，目前看來是開發者自行部署，然後必須使用 imToken 特製的 webview 來載入執行程式碼中的特別 API

 - 現今有許多Dapp Librarys可以用來跟Ethereum網路溝通，像是由Java撰寫web3J，python的Web3.py和.Net的nethereum。今天要介紹的Web3.js則是由Javascript撰寫的Ethereum JavaScript API。Web3.js提供了一些基本操作，譬如getBalane()、sendTransaction()…等，也可以利用 Web3.js來幫我們佈署smart contract到Ethereum網路上。使用者可以利用Web3.js提供的界面來跟Metamask或Geth Node，甚至是Ganache Testrpc互動。

 - [詳細教程：用Ethers.js构建一个简单的DApp](https://learnblockchain.cn/article/339)

 - [以太坊手把手空氣幣發幣教學 - 割韭菜起手式](https://blog.toright.com/posts/6347/%e4%bb%a5%e5%a4%aa%e5%9d%8a%e6%89%8b%e6%8a%8a%e6%89%8b%e7%99%bc%e5%b9%a3%e6%95%99%e5%ad%b8-%e5%89%b2%e9%9f%ad%e8%8f%9c%e8%b5%b7%e6%89%8b%e5%bc%8f.html)

 - [使用Node.js在AMM交易所上自动交易代币简单示例](https://blog.csdn.net/weixin_39430411/article/details/117605046)

 - [以太坊開發者工具列表](https://www.gushiciku.cn/pl/p9Ut/zh-tw)
以太坊的2個主要的客戶端軟體是Geth和Parity。

 - [Web3j: Web3 Java Ethereum Ðapp API](https://github.com/web3j/web3j)
Web3j is a lightweight, highly modular, reactive, type safe Java and Android library for working with Smart Contracts and integrating with clients (nodes) on the Ethereum network:

 - [Web3.swift: Web3 swift Ethereum Ðapp API](https://github.com/Boilertalk/Web3.swift)
Web3.swift is a Swift library for signing transactions and interacting with Smart Contracts in the Ethereum Network.

 - [imtoken dapp 开发帮助](https://blog.csdn.net/zdyah/article/details/108347580)

[去中心化加密货币钱包系统设计](https://zhuanlan.zhihu.com/p/43906328?utm_source=ZHShareTargetIDMore&utm_medium=social&utm_oi=900034278698680320)


PS: Ganache Testrpc是專門用來模擬私人Ethereum網路環境的工具，只在本地端的電腦上運行，資料只存放在Memory中。重開後等同於建立另一個全新的私人Ethereum網路。適合前期拿來開發Dapp功能。
[(ref: Ethereum Dapp初心者之路(5): 簡介Web3 Javascript API及常用操作)](https://ksin751119.medium.com/ethereum-dapp%E5%88%9D%E5%BF%83%E8%80%85%E4%B9%8B%E8%B7%AF-5-%E7%B0%A1%E4%BB%8Bweb3-javascript-api%E5%8F%8A%E5%B8%B8%E7%94%A8%E6%93%8D%E4%BD%9C-253c468450c0)


<hr>

備註：名詞資訊、注意事項 ....：

AMM（Automated Market Maker，自動做市商）
任何市場都可能存在沒有足夠的有機流動性以支持活躍的交易的狀況，做市商本質上就是通過促進這些市場中不會發生的交易來緩解這一問題的代理商。在傳統的 CEX 裡許多做市商都是專業的團隊或是機構。而 AMM ( Automated Market Maker )，相當於把他們這個角色給真正的去中心化了。
每個用戶都可以把自己的代幣扔到流動池里，成為一個小的做市商，然後享受交易對手續費分紅。且流動池資金是去中心化開源合約控制，AMM 交易數據全部上鏈，不像傳統 CEX 的平台幣銷毀或是分紅，畢竟沒有人知道他們手續費真的掙了多少，平台幣流通了多少等等……而在 AMM 這裡，一切透明。
更重要的是，你的資產依舊在你個人控制的錢包里，而不是進了交易平台，所以資產依舊 100% 安全，這是傳統 CEX 無論如何不可能實現的。
AMM 技術雖然得到了飛速的發展，近期被很多人所追捧，但並不是完全沒有風險的，其中一個風險就是其中的[無常損失](https://academy.binance.com/zt/articles/impermanent-loss-explained)。

DEX（Decentralized Exchanges，去中心化交易所）

CEX（Centralized Exchange，中心化交易所）

Nonce(number once) 代表只能被使用一次的亂數，或者叫做不重覆性的亂數：
 - [什麼是挖礦中的 Nonce?](https://0xzx.com/zh-tw/2021100422051781164.html)
 - [挖礦 = 求解一個合適的nonce整數，區塊鏈與加密數字貨幣知識](https://www.gushiciku.cn/pl/pLml/zh-tw)

虛擬貨幣轉帳，要留意代幣標準（例如：ERC 20、ERC 777、BEP 20 ...），在不兼容的標準之間交易
比方說：幣安智能鏈（BEP-20）與以太坊（ERC-20）
這部分當下筆者已知的有[幣安橋](https://academy.binance.com/zt/articles/an-introduction-to-binance-bridge)可提升不同區塊鏈之間的互操作性，讓任何人將其加密資產，兌換成幣安鏈和幣安智能鏈的打包代幣 (或從代幣換回加密資產)。

Popular exchanges that fall into this category are Coinbase, Binance, Kraken, and Gemini. These exchanges are private companies that offer platforms to trade cryptocurrency. These exchanges require registration and identification, known as the Know Your Customer (or Know Your Client) rule.

[去中心化金融 (DeFi, Decentralized finance)](https://zh.wikipedia.org/zh-tw/%E5%8E%BB%E4%B8%AD%E5%BF%83%E5%8C%96%E9%87%91%E8%9E%8D)
DeFi平台利用區塊鏈上的智慧型合約進行金融活動，允許人們向他人借出或借入資金，交易加密貨幣，並在類似儲蓄的帳戶中獲得利息。





————————————————

[快乐区块维基](https://happypeter.github.io/binfo/)
快乐区块维基（ Binfo – Blockchain Info ）。学习比特币 ，区块链和 Web3.0 需要掌握很多基础概念，但是如果去看维基百科或者其他材料，会发现内容都太细太深。有没有一个 wiki 网站专注提供区块链内容，且每一篇瞄准一个概念或者一项技术，短小通俗，定位清晰呢？快乐区块维基就是这样一个网站，读者打开每个词条都可以轻松的理解里面每一句话，同时又可以找到跟多拓展阅读内容的链接，技术阅读也能快乐。目前大部分词条都由 happypeter 完成，大家可以 clone 项目来添加新词条，或者点击每个页面末尾的“到 Github 上编辑本页”来修改当前词条。

————————————————

## ☗ [GitBook](https://www.gitbook.com/?utm_source=legacy&utm_medium=redirect&utm_campaign=close_legacy)
[Author: Gasolin](https://gasolin.idv.tw/)

 - [Ethereum區塊鏈！智能合約(Smart Contract)與分散式網頁應用(dApp)入門](https://gasolin.gitbooks.io/learn-ethereum-dapp/content/)

[Author: Happypeter](https://happypeter.github.io/)

 - [以太坊世界观下的 DApp](https://happypeter.github.io/binfo/dapp)
 - [快乐区块维基](https://happypeter.github.io/binfo/)
 - [以太坊的 Gas 机制](https://happypeter.github.io/binfo/eth-gas)

## ☗ [video-index](https://www.video-index.com/en)
[Author: POCKET NETWORK](https://www.video-index.com/en/video-owner/pocket%20network)

- [CONNECT ANDROID DAPP TO ETHEREUM - SETUP/INSTALL/CONFIG](https://www.video-index.com/en/android-dapp-ethereum/english/connect-android-dapp-to-ethereum-setupinstallconfig)
- [CONNECT ANDROID DAPP TO ETHEREUM - SETUP / INSTALL / CONFIG [PART 1]](https://www.video-index.com/en/ethereum/english/connect-android-dapp-to-ethereum-setup-install-config-part-1)
- [CONNECT ANDROID DAPP TO ETHEREUM - CREATE / IMPORT WALLET [PART 2]](https://www.video-index.com/en/android-dapp-ethereum/english/connect-android-dapp-to-ethereum-create-import-wallet-part-2)
- [CONNECT ANDROID DAPP TO ETHEREUM - READ DATA FROM SMART CONTRACTS [PART 3]](https://www.video-index.com/en/android-dapp-ethereum/english/connect-android-dapp-to-ethereum-read-data-from-smart-contracts-part-3)

## ☗ [it邦幫忙](https://ithelp.ithome.com.tw/)
[Author: HAO](https://ithelp.ithome.com.tw/users/20119338/ironman)

 - [區塊練起來-智能合約與DApp開發](https://ithelp.ithome.com.tw/users/20119338/ironman/2150)

## ☗ [medium.com](https://medium.com/)
[Author: MaRi Eagar](https://econova.medium.com/)

 - [What is the difference between decentralized and distributed systems?](https://medium.com/distributed-economy/what-is-the-difference-between-decentralized-and-distributed-systems-f4190a5c6462)

[Author: Albert Lin](https://ksin751119.medium.com/)

 - [Ethereum Dapp初心者之路(1): 簡介Dapp(Decentralized Application)](https://ksin751119.medium.com/ethereum-dapp%E5%88%9D%E5%BF%83%E8%80%85%E4%B9%8B%E8%B7%AF-1-%E7%B0%A1%E4%BB%8Bdapp-decentralized-application-cf12ce581f90)

## ☗ [devblogs.microsoft.com](https://devblogs.microsoft.com/)
[Author: Derrick Stolee](https://devblogs.microsoft.com/devops/author/stolee/)

 - [Exploring new frontiers for Git push performance](https://devblogs.microsoft.com/devops/exploring-new-frontiers-for-git-push-performance/)

## ☗ [Ethereum](https://blog.ethereum.org/)
[Author: Taylor Gerring](https://blockchain-documentary.com/taylor-gerring-ethereum/)

 - [building the decentralized web 3.0](https://blog.ethereum.org/2014/08/18/building-decentralized-web/)

## ☖ [非權威參考文章]
 - [imtoken dapp 开发帮助](https://blog.csdn.net/zdyah/article/details/108347580)

## ☖ [未整理]
 - [指引开发 imToken DApp ](https://imtoken.gitbook.io/developers/v/zh/products/webview/development-guide-for-imtoken-dapp)
 - [介紹整理論文 references 的工具](https://www.lxws.net/ask.php?id=1593)
 - [漫谈容器发展史](liupzmin.com/2019/11/06/docker/container-chat/)
 - [免费的编程中文书籍索引](https://github.com/justjavac/free-programming-books-zh_CN)
 - [2020年仍然有效的一些XSS Payload](https://www.freebuf.com/articles/web/226719.html)
 - [好的開始 Shell Script](http://billie66.github.io/TLCL/book/index.html)


