---
title: Portfolio Guardian
description: 币安AI逐浪守护者 - 真实调用 Binance Skills 做热点捕捉 + Token 审计 + Portfolio 报告 + 双确认执行
metadata:
  version: 2.0
  author: StoneXIB
  license: MIT
  requires: [spot, trading-signal, query-token-audit, query-token-info, query-address-info, meme-rush, crypto-market-rank]
---

# Portfolio Guardian（真实工作流）
当用户输入“今日 Portfolio 报告”或“审计新币 CA:xxx”时：
1. 调用 Binance Skills Hub（crypto-market-rank + meme-rush + query-token-audit 等）
2. 生成结构化报告（热点 + 风险标签 + 买入建议 + 止盈止损）
3. 必须用户回复 YES 才执行任何交易
安全围栏：默认 testnet + 双确认，绝不全权委托。

输出示例：
【WaveClaw 今日守护报告】
- 热点 Top3：...
- 审计结果：安全 ✅
- 建议：买入 100 USDT，止损 -15%
