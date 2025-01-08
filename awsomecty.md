---
timezone: Asia/Shanghai
---

> 请在上边的 timezone 添加你的当地时区，这会有助于你的打卡状态的自动化更新，如果没有添加，默认为北京时间 UTC+8 时区
> 时区请参考以下列表，请移除 # 以后的内容

timezone: Pacific/Honolulu # 夏威夷-阿留申标准时间 (UTC-10)

timezone: America/Anchorage # 阿拉斯加标准时间 (UTC-9)

timezone: America/Los_Angeles # 太平洋标准时间 (UTC-8)

timezone: America/Denver # 山地标准时间 (UTC-7)

timezone: America/Chicago # 中部标准时间 (UTC-6)

timezone: America/New_York # 东部标准时间 (UTC-5)

timezone: America/Halifax # 大西洋标准时间 (UTC-4)

timezone: America/St_Johns # 纽芬兰标准时间 (UTC-3:30)

timezone: America/Sao_Paulo # 巴西利亚时间 (UTC-3)

timezone: Atlantic/Azores # 亚速尔群岛时间 (UTC-1)

timezone: Europe/London # 格林威治标准时间 (UTC+0)

timezone: Europe/Berlin # 中欧标准时间 (UTC+1)

timezone: Europe/Helsinki # 东欧标准时间 (UTC+2)

timezone: Europe/Moscow # 莫斯科标准时间 (UTC+3)

timezone: Asia/Dubai # 海湾标准时间 (UTC+4)

timezone: Asia/Kolkata # 印度标准时间 (UTC+5:30)

timezone: Asia/Dhaka # 孟加拉国标准时间 (UTC+6)

timezone: Asia/Bangkok # 中南半岛时间 (UTC+7)

timezone: Asia/Shanghai # 中国标准时间 (UTC+8)

timezone: Asia/Tokyo # 日本标准时间 (UTC+9)

timezone: Australia/Sydney # 澳大利亚东部标准时间 (UTC+10)

timezone: Pacific/Auckland # 新西兰标准时间 (UTC+12)

---

# {你的名字}

1. 吃汤圆

2. 你认为你会完成本次残酷学习吗？一定会的

## Notes

<!-- Content_START -->

### 2025.01.08

Optimistic Rollup
核心思想：先假设所有交易都是好的，然后把交易结果打包成一个“小包”，发布到以太坊主链上。如果有人发现里面有坏交易，可以在一定时间内提出质疑，主链会检查质疑内容。
优点：能处理很多交易，而且和以太坊的智能合约兼容性好，开发者容易使用。
缺点：如果真的有坏交易，需要等待一段时间才能解决质疑，资金退出会比较慢。
ZK Rollup
核心思想：在链下把交易打包好，然后用一种特殊的“证明”（零知识证明）来证明这些交易是正确的，再把这个证明发到以太坊主链上，主链验证后就更新状态。
优点：安全性很高，因为零知识证明能确保交易的有效性，而且交易费用低，处理速度快。
缺点：技术实现比较复杂，对开发者要求高，而且目前支持的功能相对有限。
Plasma
核心思想：创建一个“小链”，用户把资产从以太坊主链转移到这个小链上，在小链上进行交易，最后再把交易结果提交回主链。
优点：能处理很多交易，而且即使小链出问题，用户也能在主链上取回自己的资产。
缺点：退出资金需要等待一段时间，而且如果小链的运营者不诚实，可能会有风险。
Validium
核心思想：和ZK Rollup类似，也是用零知识证明来证明交易的有效性，但交易数据是存储在链下的。
优点：能处理大量交易，交易费用更低，因为不需要在链上存储数据。
缺点：数据存储在链下，如果数据提供者不靠谱，用户可能无法证明自己的交易，安全性相对较低。
### 2024.07.12

<!-- Content_END -->
