# Iteration Plans

## March 2022

- Owner @wssgcg1213
- [Iteration Plan](https://github.com/openkraken/kraken/issues/1218)

> 以下部分还未建立 Issue，此处仅做初步计划

## April 2022

- Owner @answershuto

### Stability 

- [ ] 通过更严格的代码 Lint 规则限制可能高风险的逻辑

### Performance 

- [ ] 建立自动化的性能测试机制，输出测试报告 @answershuto
- [ ] 🚀 重构 Dart 侧的内存数据结构，根据场景选择实现 @wssgcg1213
- [ ] 🚀 通过无感的内部缓存提升首屏体验 @answershuto
- [ ] 使用 miallocate 来取代内置的内存分配器 @andycall
- [ ] 提升 Flex 布局的执行性能 @temper357

### Extensionality

- [ ] 多引擎支持 @andycall
- [ ] 提供 HTMLView 为用户提供更好的体验 @answershuto
- [ ] Stable the API of extension.


### Web Compatibility

- [ ] 新增 1000 个测试用例 @temper357

### Developer

### Website and Documentation

- [ ] Blog 文章: Kraken 渲染管线 @wssgcg1213

### Community support

- [ ] 发布 0.11.1


## May 2022

Owner @temper357

- [ ] 用统一字符串 ID 来优化整个样式设置链路 @andycall
- [ ] 通过为内存增量增加持续集成来检测可能的内存泄露 @answershuto
- [ ] Blog 文章: Kraken 布局原理 @temper357
- [ ] 🚀 通过指令分级提升渲染性能 @answershuto
- [ ] Build 2 officially maintained plugin, to guide to building a plugin community. (Waterfall) @wssgcg1213
- [ ] Provide guidance of multi page integtration. @answershuto
- [ ] Measure Kraken's web standards compliance by building a web standards compliance test report @temper357
- [ ] 支持 JS 断点调试 @andycall
- [ ] Improve the experience of debugging tools. @wssgcg1213

## June 2022

Owner @andycall

- [ ] Blog 文章: Kraken Bridge 实现 @andycall
- [ ] 通过为内存增量增加持续集成来检测可能的内存泄露 @answershuto

## July - December  2022

- [ ] 支持 JS 断点调试 @andycall
- [ ] Blog 文章: Kraken 手势&事件 @answershuto
- [ ] Blog 文章: Kraken HTTP 缓存的实现 @wssgcg1213
- [ ] Blog 文章: Kraken 开发者工具
- [ ] Blog 文章: Kraken 高性能系列 - 加载性能
- [ ] Blog 文章: Kraken 高性能系列 - 布局性能
- [ ] Blog 文章: Kraken 高性能系列 - 滚动性能

