# eos_dex
EOS的去中心化交易所（合约、前端、后端）
详细文档会添加到wiki

## 目的
构建去中心化交易所更方便，同时在越来越多人使用的过程中保证合约的健壮性。建设EOS生态。

## 贡献
欢迎搭建一起参与构建。（目前没有提交规范，按照git工作流提交即可，之后有时间会在wiki上完善文档）

## 前端 (WIP)
仓库地址:  [eos_dex前端](https://github.com/GiggleAll/eos_dex_front_end)

### 计划 (wiki)
1. 选一个前端交易所界面（还没找， 如果有的话）
2. 兼容scatter标准
3. 保证功能正常使用

## 服务端 (WIP)
仓库地址: [eos_dex服务端](https://github.com/GiggleAll/eos_dex_service)

### 计划 (wiki)
1. 初步计划是选用python作为开发语言，之后可能会更改，eosjs的兼容性更高（但是我python用的最熟，js一般）
2. 功能模块划分(WIP)

## 合约地址（v0.1.0）
仓库地址: [exchange](https://github.com/GiggleAll/exchange)

### 计划（wiki）
1. 完善`exchange`合约，改bug，修复逻辑漏洞
2. 添加一些交易所盈利功能（有兴趣详聊，这一块可能根据功能的不同会把相应的版本放在不同的分支）
3. 实现eos和eth跨链操作，目前参考仓库为[eos/eth](https://github.com/GiggleAll/Ethereum-EOS-cross-chain-token-exchange-example)

