# Move Book 中文版

区块链技术的发展经历了两个阶段，比特币（BTC）开启了*区块链1.0时代*，以太坊（ETH）开启了*区块链2.0时代*。
以太坊的出现为区块链带来了*智能合约*这一关键技术，让区块链不只停留在记账这一单的目的，而是带来更多的应用拓展性。
遗憾的是，智能合约如同一把双刃剑，在带来众多丰富功能拓展的同时，也容易让智能合约开发者无意间引入不安全的代码，让链的资产受到威胁。

编写简单、安全、易部署的智能合约应该是*区块链3.0时代*应该关注的重点，**面向资源编程**的 [Move 语言](https://github.com/move-language/move)，无疑给这个问题提供了一个很好的解决方案。

本书是 [Move Book](https://move-language.github.io/move/) 的中文版。

## 快速开始

本书使用 [mdBook](https://rust-lang.github.io/mdBook/) 构建。

1. 使用 Cargo 安装 mdBook：

```shell
cargo install mdbook
```

2. 下载

```shell
git clone https://github.com/move-cc/move-book-zh.git
```

3. 构建并预览

```shell
cd move-book-zh
mdbook serve --open
```

## 关于本仓库

Move 语言官方团队已经批准将《Move Book 中文版》放在原仓库中的 `move/language/documentation/book/translations/move-book-zh/` 目录里。

详细工作流程见：

- [Provide Chinese Move Book #353](https://github.com/move-language/move/issues/353)
- [migrate Move Book of Chinese version from MoveCC #359](https://github.com/move-language/move/pull/359)
- [migrate Move Book of Chinese version from MoveDao #380](https://github.com/move-language/move/pull/380)

如果想要维护《Move Book 中文版》的内容，贡献你的一份力量，请直接在官方仓库提交 PR 或 issue。

现在，本仓库只为在网页里方便浏览《Move Book 中文版》，如果有建议或想法可以提 issue。

## 进度

- [ ] Introduction
- [ ] 1. Modules and Scripts
- [ ] 2. Move Tutorial
- [ ] 3. Integers
- [ ] 4. Bool
- [ ] 5. Address
- [ ] 6. Vector
- [ ] 7. Signer
- [ ] 8. References
- [ ] 9. Tuples and Unit
- [ ] 10. Local Variables and Scopes
- [ ] 11. Equality
- [ ] 12. Abort and Assert
- [ ] 13. Conditionals
- [ ] 14. While and Loop
- [ ] 15. Functions
- [ ] 16. Structs and Resources
- [ ] 17. Constants
- [ ] 18. Generics
- [ ] 19. Type Abilities
- [ ] 20. Uses and Aliases
- [ ] 21. Friends
- [ ] 22. Packages
- [ ] 23. Unit Tests
- [ ] 24. Global Storage Structure
- [ ] 25. Global Storage Operators
- [ ] 26. Standard Library
- [ ] 27. Coding Conventions
