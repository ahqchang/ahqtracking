# Studying to do list

App 與 DApp
 - 傳統 App 不論是 native 或是 web-based application，都是與特定組織（國家）的後端系統互動。
 - 去中心化 App（DecentralizedApplications，DApp）是透過智能合約對接區塊鏈，藉著區塊鏈去中心化的特性可以有若干好處：
   - 解耦特定組織（國家）對系統的影響
   - 利益的分配是对全部参与者都公平的

 https://geth.ethereum.org/docs/dapp/mobile

2020 年開始，區塊鏈 web3.0 顯露趨勢，以 Ethereum 與 Polkadot 為主的 web3.0 生態體系正在快速建構。
以太坊的主流功能是智能合約，但構成 web3.0 的 "去中心化數據存儲 swarm" 和 "信息通訊協議 whisper" 也同樣重要。

摸索：[指引开发 imToken DApp](https://imtoken.gitbook.io/developers/v/zh/products/webview/development-guide-for-imtoken-dapp)
 - 直接體驗 imToken [官方 DApp 範例專案](https://github.com/consenlabs/token-getting-started)
   
   安裝 imToken App，註冊登入後透過右上角的 QR Code 掃碼功能掃描 [QR Code](https://imtoken.gitbook.io/developers/v/zh/products/webview/development-guide-for-imtoken-dapp#zhi-jie-yu-lan-xiang-mu)
 - Clone 官方 DApp 範例專案，參考上一部的體驗內容追蹤程式碼
   > git clone git@github.com:consenlabs/token-getting-started.git
 - 如何部署 DApp？

   觀察上方的體驗功能，目前看來是開發者自行部署，然後必須使用 imToken 特製的 webview 來載入執行程式碼中的特別 API



虛擬貨幣轉帳，要留意代幣標準（例如：ERC 20、ERC 777、BEP 20 ...），在不兼容的標準之間交易
比方說：幣安智能鏈（BEP-20）與以太坊（ERC-20）
這部分當下筆者已知的有[幣安橋](https://academy.binance.com/zt/articles/an-introduction-to-binance-bridge)可提升不同區塊鏈之間的互操作性，讓任何人將其加密資產，兌換成幣安鏈和幣安智能鏈的打包代幣 (或從代幣換回加密資產)。



————————————————

[快乐区块维基](https://happypeter.github.io/binfo/)
快乐区块维基（ Binfo – Blockchain Info ）。学习比特币 ，区块链和 Web3.0 需要掌握很多基础概念，但是如果去看维基百科或者其他材料，会发现内容都太细太深。有没有一个 wiki 网站专注提供区块链内容，且每一篇瞄准一个概念或者一项技术，短小通俗，定位清晰呢？快乐区块维基就是这样一个网站，读者打开每个词条都可以轻松的理解里面每一句话，同时又可以找到跟多拓展阅读内容的链接，技术阅读也能快乐。目前大部分词条都由 happypeter 完成，大家可以 clone 项目来添加新词条，或者点击每个页面末尾的“到 Github 上编辑本页”来修改当前词条。

————————————————

[Web3j: Web3 Java Ethereum Ðapp API](https://github.com/web3j/web3j)
Web3j is a lightweight, highly modular, reactive, type safe Java and Android library for working with Smart Contracts and integrating with clients (nodes) on the Ethereum network:

[Web3.swift: Web3 swift Ethereum Ðapp API](https://github.com/Boilertalk/Web3.swift)
Web3.swift is a Swift library for signing transactions and interacting with Smart Contracts in the Ethereum Network.

————————————————

[去中心化金融 (DeFi, Decentralized finance)](https://zh.wikipedia.org/zh-tw/%E5%8E%BB%E4%B8%AD%E5%BF%83%E5%8C%96%E9%87%91%E8%9E%8D)
DeFi平台利用區塊鏈上的智慧型合約進行金融活動，允許人們向他人借出或借入資金，交易加密貨幣，並在類似儲蓄的帳戶中獲得利息。

————————————————

[imtoken dapp 开发帮助](https://blog.csdn.net/zdyah/article/details/108347580)

有种 app,可以加载 其他dapp网站,网页或者小程序,这种app就是dapp
有的人说 dapp就是智能合约+App,这是不正确的.只能说 智能合约+App是dapp的一种.
例如: 微信,支付宝等都是dapp
IMtoken 钱包就是这种特殊的 dapp,它集成了一个浏览器,可以加载其他的网站, 我们可以开发基于imtoken钱包的网站,
为什么要开发dapp?为什么需要dapp?因为这些dapp 会提供了 一些 js 特殊对象, 和底层函数库.
但在pc 浏览器和app 普通浏览器中则没有 专门的函数库.
也就是你的网站只能在这类app中打开,才能使用他们的函数库

————————————————

## ☗ [GitBook](https://www.gitbook.com/?utm_source=legacy&utm_medium=redirect&utm_campaign=close_legacy)
[Author: Gasolin](https://gasolin.idv.tw/)

 - [Ethereum區塊鏈！智能合約(Smart Contract)與分散式網頁應用(dApp)入門](https://gasolin.gitbooks.io/learn-ethereum-dapp/content/)

[Author: Happypeter](https://happypeter.github.io/)

 - [以太坊世界观下的 DApp](https://happypeter.github.io/binfo/dapp)
 - [快乐区块维基](https://happypeter.github.io/binfo/)

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


