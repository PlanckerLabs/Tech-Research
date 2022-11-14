## ZK 概述
+ ZK是什么？大家自己google
+ 这里从产品建设视角，分析下，zk能给产品场景中提供什么建设能力，目前有哪些可能的思考，从而考虑是否引入zk技术来帮助产品更安全、精简、高效
+ 当然，先介绍下zk领域的主要角色，技术原理

### Resource
+ 基础知识：
+ https://mp.weixin.qq.com/s/STKCytryJSBixoC8jn53Hw, 这个有系列，感觉不错
+ https://vitalik.ca/general/2017/11/09/starks_part_1.html, basic 3
+ https://learnblockchain.cn/article/269 ,STARK概述+对比
+ http://blog.hubwiz.com/2020/02/16/compare-gp-zksnarks/, snark
+ https://www.jianshu.com/p/889b7e09ae9a   ,https://eprint.iacr.org/2019/953 ,Plonk：通用性和可更新setup
+ https://www.8btc.com/media/6714670 plonk
+ ----
+ 一些对比
+ https://www.bcskill.com/index.php/archives/1195.html
+ https://consensys.net/blog/blockchain-explained/zero-knowledge-proofs-starks-vs-snarks/
+ 讨论STARK和SNARK，首字母缩写词：zk-STARK代表零知识可扩展的透明知识论证，zk-SNARK代表零知识简洁非交互式知识论证。
+ ----
+ https://learnblockchain.cn/article/672
+ ----
+ 以太坊社区讨论：https://ethereum.stackexchange.com/questions/59145/zk-snarks-vs-zk-starks-vs-bulletproofs-updated
+ 从技术的几个角度：proof size(gas)、trsted setup，complexity(proover,verifier)，Post-quantum secure(crypto assumptions)
+ ![image](https://user-images.githubusercontent.com/2945287/201565490-fa91f535-6895-4aed-9cf1-1b5f18356e91.png)

+ -----
+ https://docs.google.com/presentation/d/1gfB6WZMvM9mmDKofFibIgsyYShdf0RV_Y8TLz3k1Ls0
+ https://www.youtube.com/watch?v=VUN35BC11Qw
+ https://eprint.iacr.org/2019/099.pdf，Sonic: Zero-Knowledge SNARKs from Linear-Size Universal and
Updatable Structured Reference Strings
+ https://eprint.iacr.org/2018/046.pdf
+ https://research.metastate.dev/plonk-by-hand-part-1/ ，手推plonk

### 技术原理

### 技术价值
+ https://foresightnews.pro/article/detail/18285 ,讨论了zk的可能应用场景，感觉要加点钱包安全、抗量子等的讨论
+ 
### 应用现状

### 开发SDK
+ https://github.com/3for/libsnark/tree/master/libsnark/zk_proof_systems/ppzksnark
+ https://github.com/gluk64/awesome-zero-knowledge-proofs
+ https://slideslive.com/38911617/privacy-for-everyone

### 小结
