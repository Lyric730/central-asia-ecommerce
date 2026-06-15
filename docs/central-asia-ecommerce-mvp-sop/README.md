# 中亚五国出海电商 调研报告

数据冻结日期：2026-06-15  
适用目标：先跑通小宗商品出海电商 P0/P1，再为 P2/P3 留扩展口。

## 当前结论

| 项 | 结论 | 证据强度 |
|---|---|---|
| P0 首站默认 | Kazakhstan | 强：官方电商规模、支付成熟度、数字化数据同时领先 |
| P0 第二市场 | Uzbekistan | 中强：人口最大、Uzum/Payme/Click 生态强，但电商零售占比和社媒渗透低于 Kazakhstan |
| 可低成本跟进 | Kyrgyzstan | 中弱：数字化不错，但市场小、电商规模证据弱 |
| 只做小样验证 | Tajikistan | 中弱：支付改善但线上触达和履约不稳 |
| P0 排除 | Turkmenistan | 强：支付、社媒、互联网、清关透明度都不适合 P0 |
| P0 商品池 | 非通电车内用品、机械车载支架、通用手机周边 | 中强：低合规、低售后、低解释成本 |
| P0 渠道 | Classifieds + 社媒/聊天 + 本地收款 | 中强：不被 marketplace 主体/税务/仓储门槛卡住 |
| P1 渠道 | Kaspi/Uzum/Olcha/Ozon/WB/Flip 等 marketplace | 强：平台可信，但入驻前置条件重 |

## P0/P1/P2/P3 定义

| 阶段 | 定义 | 通过标准 |
|---|---|---|
| P0 | 陌生真实客户主动付款，完成首批订单交付 | 至少 1 单：客户非朋友/合作方；付款发生在发货前或平台内；完成交付；聊天、付款、物流、售后证据完整 |
| P1 | 复制闭环，形成可执行 SOP | 同一国家同一链路重复 10 单，或 2 个 SKU 各完成 3 单；记录可复盘 |
| P2 | 连续稳定出单并有稳定利润 | 连续 30 天订单、毛利、退款、客服数据达标 |
| P3 | 接触分销/批发客户 | 有批发报价、样品、账期/预付、交付和售后规则 |

## 推荐阅读顺序

1. [00-overview.md](00-overview.md)
2. [01-country-selection.md](01-country-selection.md)
3. [02-product-selection.md](02-product-selection.md)
4. [03-channel-selection.md](03-channel-selection.md)
5. [04-order-acceptance.md](04-order-acceptance.md)
6. [05-fulfillment-payment-after-sales.md](05-fulfillment-payment-after-sales.md)
7. [06-review-and-stage-gates.md](06-review-and-stage-gates.md)
8. [07-source-register.md](07-source-register.md)

## 模板

| 模板 | 用途 |
|---|---|
| [templates/country_scorecard.csv](templates/country_scorecard.csv) | 国家优先级评分 |
| [templates/local_resource_inventory.csv](templates/local_resource_inventory.csv) | 本地资源盘点 |
| [templates/sku_scorecard.csv](templates/sku_scorecard.csv) | SKU 评分和淘汰 |
| [templates/channel_test_log.csv](templates/channel_test_log.csv) | 渠道测试记录 |
| [templates/order_record.csv](templates/order_record.csv) | P0/P1 订单证据 |
| [templates/partner_due_diligence.csv](templates/partner_due_diligence.csv) | 合作方尽调 |
| [templates/payment_fulfillment_checklist.csv](templates/payment_fulfillment_checklist.csv) | 支付/履约检查 |
| [templates/stage_gate_review.csv](templates/stage_gate_review.csv) | 阶段复盘门槛 |

## 关键原则

- P0 不等于平台入驻。平台订单质量高，但 Kaspi/Uzum/WB/Ozon 常被本地主体、收款、税务、库存、认证卡住。
- P0 只验证一个问题：陌生客户是否愿意为这个商品和这条链路付款。
- COD 不算 P0 成功。全额预付款、平台内付款、本地转账或支付链接付款才算。
- 不把朋友、合作方、小卖家代买算作 P0。它们可以算渠道信号，但不是陌生客户验证。
- 选品先排雷：电池、无线、充电器、小家电、液体、化学品、功能性汽配都不进 P0。
- 数据过期处理：超过 30 天后执行前，必须重新核验支付、清关、平台入驻、广告投放国家列表。

