# vps价格对比：月费之外还要算续费价和流量单价，按机房挑中国大陆优化套餐

VPS 价格对比的答案，取决于一件很具体的事：你的用户在中国大陆吗。不在，2026 年通用 VPS 的入门价就在 $4–$7/月 这一档，任何走中国优化线路的机器在你这里都是溢价。在，就得进这个细分品类里比，GoMami 的入门档是 $29/月——新加坡、东京、洛杉矶三地的 Pulse.Nano，2 vCPU / 2 GB / 40 GB NVMe。

$4/月 和 $29/月 卖的是两件不同的商品：一边是通用算力，一边是中国大陆的回程路由。真正有用的对比，是把月费背后的口径拆开看——首期价还是续费价、预付几个月、流量怎么计费、退款窗口多长。

> **选购速览**
> - 只要通用算力、预算 $5–$10/月：往下翻到通用市场那节，GoMami 不属于这一档。
> - 用户在大陆、又要便宜的入门机：**LAX.Pulse.Nano 是 $29/月给 1 TB 出站**，同样 $29 的新加坡和东京 Nano 只有 500 GB，三地都走 CN2 / AS9929 / CMIN2。
> - 要香港落地又不追单核：HKG.Pulse.Mini，2 vCPU / 4 GB / 60 GB，$59/月。
> - 吃单核性能（游戏服、实时 API、编译）：HKG.Peak.X5 用 Ryzen 9 9950X，$59/月起；HKG.Turin 用 EPYC 9575F，$69/月起。
> 👉 [查看 GoMami 全部在售套餐与当前标价](https://bit.ly/Gomami)

## GoMami 全套餐价格：按机房分开看

GoMami 全线从 $29/月 到 $999/月，共 28 个在售套餐，分布在香港、东京、新加坡、洛杉矶四个机房。官网首页与文档只列香港、日本、新加坡三个 PoP，洛杉矶系列在官方商店页单独存在，第三方库存监控站在 2026 年 8 月的盘点里也把它算作第四个区域。

以下均为**月付标价**，美元。每档同样可选季付、半年付、年付，官方文档写明年付通常比月付省 15%–20%，具体折扣按产品线不同。

### 香港（HKG）

香港是三组产品线并行：Turin 用 EPYC 9575F（最高 5GHz，官方资料写明配 PCIe Gen5 U.2 SSD 与 DDR5 6400），Pulse 用 EPYC 7763，Peak X5 用 Ryzen 9 9950X（最高 5.7GHz）。

| 套餐 | 配置（vCPU · 内存 · NVMe） | 流量 · 端口 | 月价 | 订购 |
| --- | --- | --- | --- | --- |
| HKG.Turin.Mini | 2 · 4 GB · 100 GB | 1 TB · 2 Gbps | $69 | [ 订购 Mini](https://gomami.io/aff.php?aff=415&pid=14) |
| HKG.Turin.Air | 4 · 8 GB · 140 GB | 2 TB · 2 Gbps | $129 | [ 订购 Air](https://gomami.io/aff.php?aff=415&pid=15) |
| HKG.Turin.Pro | 6 · 16 GB · 180 GB | 5 TB · 5 Gbps | $299 | [ 订购 Pro](https://gomami.io/aff.php?aff=415&pid=16) |
| HKG.Turin.Ultra | 12 · 32 GB · 220 GB | 10 TB · 5 Gbps | $599 | [ 订购 Ultra](https://gomami.io/aff.php?aff=415&pid=22) |
| HKG.Pulse.Nano | 2 · 2 GB · 40 GB | 500 GB · 1 Gbps | $49 | [ 订购 Nano](https://gomami.io/aff.php?aff=415&pid=26) |
| HKG.Pulse.Mini | 2 · 4 GB · 60 GB | 1 TB · 1 Gbps | $59 | [ 订购 Mini](https://gomami.io/aff.php?aff=415&pid=4) |
| HKG.Pulse.Air | 4 · 8 GB · 80 GB | 2 TB · 1 Gbps | $119 | [ 订购 Air](https://gomami.io/aff.php?aff=415&pid=5) |
| HKG.Pulse.Pro | 8 · 16 GB · 100 GB | 5 TB · 3 Gbps | $269 | [ 订购 Pro](https://gomami.io/aff.php?aff=415&pid=6) |
| HKG.Pulse.Ultra | 16 · 32 GB · 300 GB | 10 TB · 5 Gbps | $499 | [ 订购 Ultra](https://gomami.io/aff.php?aff=415&pid=25) |
| HKG.Peak.X5.Mini | 2 · 4 GB · 40 GB | 1 TB · 2 Gbps | $59 | [ 订购 Mini](https://bit.ly/Gomami) |
| HKG.Peak.X5.Air | 4 · 8 GB · 60 GB | 2 TB · 2 Gbps | $99 | [ 订购 Air](https://bit.ly/Gomami) |
| HKG.Peak.X5.Pro | 6 · 16 GB · 80 GB | 5 TB · 5 Gbps | $199 | [ 订购 Pro](https://bit.ly/Gomami) |

### 东京（JPN）与新加坡（SIN）

两地 Pulse 系列价格完全对齐，都用 EPYC 系列处理器。东京 Mini 的端口给到 1.5 Gbps，新加坡统一 1 Gbps。

| 套餐 | 配置（vCPU · 内存 · NVMe） | 流量 · 端口 | 月价 | 订购 |
| --- | --- | --- | --- | --- |
| JPN.Pulse.Nano | 2 · 2 GB · 40 GB | 500 GB · 1 Gbps | $29 | [ 订购 Nano](https://gomami.io/aff.php?aff=415&pid=13) |
| JPN.Pulse.Mini | 2 · 4 GB · 60 GB | 1 TB · 1.5 Gbps | $49 | [ 订购 Mini](https://gomami.io/aff.php?aff=415&pid=10) |
| JPN.Pulse.Air | 4 · 8 GB · 80 GB | 2 TB · 1 Gbps | $89 | [ 订购 Air](https://gomami.io/aff.php?aff=415&pid=11) |
| JPN.Pulse.Pro | 8 · 16 GB · 100 GB | 5 TB · 3 Gbps | $169 | [ 订购 Pro](https://gomami.io/aff.php?aff=415&pid=12) |
| JPN.Pulse.Ultra | 12 · 32 GB · 300 GB | 10 TB · 3 Gbps | $338 | [ 订购 Ultra](https://gomami.io/aff.php?aff=415&pid=24) |
| SIN.Pulse.Nano | 2 · 2 GB · 40 GB | 500 GB · 1 Gbps | $29 | [ 订购 Nano](https://gomami.io/aff.php?aff=415&pid=21) |
| SIN.Pulse.Mini | 2 · 4 GB · 60 GB | 1 TB · 1 Gbps | $49 | [ 订购 Mini](https://gomami.io/aff.php?aff=415&pid=17) |
| SIN.Pulse.Air | 4 · 8 GB · 80 GB | 2 TB · 1 Gbps | $89 | [ 订购 Air](https://gomami.io/aff.php?aff=415&pid=18) |
| SIN.Pulse.Pro | 8 · 16 GB · 100 GB | 5 TB · 3 Gbps | $169 | [ 订购 Pro](https://gomami.io/aff.php?aff=415&pid=19) |
| SIN.Pulse.Ultra | 12 · 32 GB · 300 GB | 10 TB · 3 Gbps | $338 | [ 订购 Ultra](https://gomami.io/aff.php?aff=415&pid=23) |

### 洛杉矶（LAX）

LAX 系列用 EPYC 7K62，流量给得明显比亚洲三地宽：同样是 $29 的 Nano，这里有 1 TB 出站而不是 500 GB。

| 套餐 | 配置（vCPU · 内存 · NVMe） | 流量 · 端口 | 月价 | 订购 |
| --- | --- | --- | --- | --- |
| LAX.Pulse.Nano | 2 · 2 GB · 40 GB | 1 TB · 1 Gbps | $29 | [ 订购 Nano](https://gomami.io/aff.php?aff=415&pid=27) |
| LAX.Pulse.Mini | 2 · 4 GB · 60 GB | 2 TB · 1 Gbps | $59 | [ 订购 Mini](https://gomami.io/aff.php?aff=415&pid=28) |
| LAX.Pulse.Air | 4 · 8 GB · 80 GB | 4 TB · 2 Gbps | $129 | [ 订购 Air](https://gomami.io/aff.php?aff=415&pid=29) |
| LAX.Pulse.Pro | 6 · 16 GB · 100 GB | 8 TB · 3 Gbps | $259 | [ 订购 Pro](https://gomami.io/aff.php?aff=415&pid=30) |
| LAX.Pulse.Ultra | 12 · 32 GB · 300 GB | 15 TB · 5 Gbps | $599 | [ 订购 Ultra](https://gomami.io/aff.php?aff=415&pid=31) |
| LAX.Pulse.Titan | 12 · 32 GB · 600 GB | 30 TB · 10 Gbps | $999 | [ 订购 Titan](https://gomami.io/aff.php?aff=415&pid=32) |

两张表之外还有三件事要说明。

**官网首页的 EPYC 7763 套餐和商店页对不上。** 首页另列了一组：Mini 2C/4GB/40GB/1TB/1Gbps $39、Air 4C/8GB/60GB/2TB/1Gbps $79、Pro 8C/16GB/80GB/5TB/3Gbps $169。拿 Mini 那档举例，同样 2 vCPU / 4 GB，商店页的 Pulse.Mini 是 60 GB 盘、$59；首页这档是 40 GB 盘、$39。两组数字差了 $20，配置也不同。首页可能是旧版展示或不同地区组合，付款金额以结算页为准，别按首页数字做预算。

**更高规格的 HKG.Forge 系列没进表。** 第三方库存监控里能看到 56 核 / 128 GB 与 56 核 / 256 GB 两档，标价 $599 和 $899，但官网商店页面在可查资料中没有对应确认，所以本文不把它当作在售套餐推荐。官网商店另有超出本表范围的规格，选购时以商店页实际列表为准。

**DDoS 能力的两种表述要分清。** 官方文档写的是默认包含尽力而为的防护、可选 600 Gbps 高级清洗；首页直接写成最高 600 Gbps 缓解能力。按文档口径理解更稳。

## 换算成单价，GoMami 的贵和便宜分别在哪

把月价除一除，结论比参数表直白。**流量单价上，洛杉矶最划算；vCPU 单价上，GoMami 全线都没有价格优势。**

每 TB 出站流量的成本（月价 ÷ 月流量）：LAX 从 Nano 的 $29 到 Titan 的 $33.3，中间 Ultra 是 $39.9；新加坡和东京的 Pulse 从 Nano 的 $58 一路降到 Pro / Ultra 的 $33.8；香港 Pulse 最贵，Nano 到 $98、Mini 和 Air 在 $59 上下、Pro $53.8、Ultra $49.9；香港 Turin 从 Mini 的 $69 降到 Pro 与 Ultra 的 $59.8 和 $59.9，落在 $59–60 区间。

对照官方流量包 $60/TB，可以得出一个实用的判断：多数档位升级套餐拿到流量的单价，低于事后单独买流量包。流量快用完时先算一下升档差价和流量包哪个便宜。只有 HKG.Pulse.Nano（$98/TB）这类档位，买流量包才明显划算。

每 vCPU 则是另一条曲线：SIN.Pulse.Nano 折合 $14.5/vCPU，HKG.Turin.Ultra 接近 $49.9/vCPU。拿这条曲线论证 GoMami 贵没有意义，它卖的不是 vCPU 数量。

真正值得问的是这些线路值多少。有一份二手转述提到 2026 年 1 月对香港 Turin（EPYC 9575F）的测试：到新加坡持续 2.16 Gbps、延迟 40.4ms，到深圳电信 1.76 Gbps、回程 893 Mbps——原始报告未公开获取，这组数字只能当作方向参考，不能当成已复核的结论。另外 2025 年 8 月一份第三方实测记录显示 HKG.Peak.X5.Mini 的 Geekbench 5 单核 2566、多核 4520，同时指出该系列的磁盘 IO 相比 7763 系列被限制，同样命令写入差距约 3 倍。单核敏感的应用值得为此付钱，跑数据库写密集负载的则要先测 IO。

>$29 这一档最有意思的对比在这里：LAX.Pulse.Nano、SIN.Pulse.Nano、JPN.Pulse.Nano 同价，洛杉矶给 1 TB 出站，亚洲两地给 500 GB。如果只是需要一条中国优化线路做中转或小站，洛杉矶那台的流量单价是三者里最低的 $29/TB。
>
>👉 [用 LAX.Pulse.Nano 开一台 $29/月、含 1 TB 出站的入门机](https://gomami.io/aff.php?aff=415&pid=27)

## 通用 VPS 市场的价格区间在哪

如果你要的就是通用算力，这一档的公开价格大致如下。各家页面抓取时间不一，只作量级参考。

| 品牌 | 入门参考价 | 计费口径 | 关键说明 |
| --- | --- | --- | --- |
| Contabo | €4.40/月 | 24 个月订阅的等效月价，含税，最低首期 1 个月 | 无限流量 + 公平使用限速，端口 200 Mbit/s–1 Gbit/s |
| Hetzner | CX23 €5.99/月（约 $6.96） | 月付，或 €0.0096/小时 | 2 vCPU / 4 GB / 40 GB NVMe，含一个 IPv4；德国、芬兰、新加坡、美国机房，99.9% SLA |
| DigitalOcean | $4/月起 | 按秒计费，60 秒起 | 出站流量 500 GiB/月起，入站免费 |
| Hostinger | KVM 1 首价 $6.49，续费 $11.99 | 长周期预付 | 1 vCPU / 4 GB / 50 GB NVMe |

再看按 vCPU 折算的榜单。下表来自第三方在 2026 年 9 月 4 日整理的对比，vCPU 数量与月价均为该榜单列出的口径，不是各家官网自己给出的单位价格：

| 方案 | vCPU | 月价 | 每 vCPU |
| --- | --- | --- | --- |
| Contabo Cloud VPS S | 4 | 约 $6.99 | 约 $1.75 |
| Hetzner CX33 | 4 | 约 $9.71 | 约 $2.43 |
| Contabo Cloud VPS M | 6 | 约 $14.99 | 约 $2.50 |
| IONOS VPS XL+ | 8 | $44 | 约 $5.50 |
| Hostinger KVM 4 | 4 | $28.99 | 约 $7.25 |
| Hostinger KVM 2 | 2 | $14.99 | 约 $7.50 |
| DigitalOcean Basic | 4 | $48 | 约 $12.00 |

这张表解释了为什么跨品类比价没有意义：欧洲厂商把每 vCPU 压到 $2 附近，卖的是密度；美系云厂商卖的是生态和按秒弹性。中国优化线路两个都不卖，卖的是回程路由，单价必然落在另一条曲线上。

## 三个会改写账单的口径

同一台机器，换个计费周期、换个流量算法，账单能差出三成。下面三项是最容易在比价时被忽略的。

**首期价与续费价。** 大部分「$X/月起」写的是首期价。CloudsPress 2026 年 10 月更新的统计（正文口径 391 家主机商，389 家有公开首价）显示，首价中位数 $9.95/月，续费中位数 $11.46/月；在公布续费价的 52 家里，只有 19 家从不涨价。差距能有多大？Hostinger KVM 2 首价 $8.99、续费 $14.99，涨幅约 67%；KVM 4 从 $12.99 涨到 $28.99，涨幅约 123%。该统计里记录到的极端案例是 BuyVPS S-2，首价 $1/月，续费 $7.99/月。

**预付周期。** Contabo 首页那个 €4.40/月，口径本来就是 24 个月订阅的等效月价且含税。GoMami 走预付制，年付比月付省 15%–20%，$29/月 的 Pulse.Nano 年付摊下来约每月 $23.2–$24.65。省下的钱是用预付款和灵活性换的：续费订单不享受退款政策，所以年付前最好先月付跑完一个账单周期。

**流量算法。** GoMami 只统计出站，入站不计费，配额按账单周期重置，超额后可能限速而不会自动扣费，不够就买流量包（100 GB $6、1 TB $60，合 $0.06/GB）。Contabo 是无限流量加公平使用限速。Vultr 给配额，超出部分按 $0.01/GB 收。DigitalOcean 每台含出站 500 GiB/月起，入站免费。「无限流量」和「$0.06/GB」是两种风险分配方式：前者把超量风险交给厂商，代价是可能被限速；后者账单可控，但峰值难预测。

>👉 [按年付开通 SIN.Pulse.Nano，把 $29 的月价压到 $23 出头](https://gomami.io/aff.php?aff=415&pid=21)

## 价格之外的条款，才是隐性成本

比价格更值得逐条读的是计费和退款规则，它们决定一次错误下单的代价。**GoMami 的退款窗口只有 24 小时，且附了不止一条限制。**

官方文档的表述是：服务开通起 24 小时内可以申请全额退款，适用于新购买实例，原路退回，每位用户限一次；续费订单、违规被终止的服务、已使用的充值余额、因 DDoS 导致 IP 被牵引的情况都不在范围内。退款到账时间支付宝 1–3 个工作日、信用卡 5–10 个工作日、加密货币 1–3 个工作日，一旦通过，实例与数据立即永久删除。

服务条款里还有两条文档没写的边界：一是 24 小时内单台 VM 使用超过 10 GB 流量即失去退款资格；二是退款会扣除原交易产生的支付处理费。后者与文档的「全额退款」说法不完全一致，实际以工单回复为准。

到期规则更硬：账单到期日当天服务即暂停，没有宽限期；逾期 5 天终止，数据可能不可恢复；续费账单提前 7 天生成并邮件通知，绑了卡会自动扣款。另外，实例若被判定为「吵闹邻居」——持续高 CPU 负载影响同节点其他用户——可能被 CPU 限速处罚；升降配要走工单，控制面板不能自助完成。

还有一条容易和第三方文章打架的：服务条款明确写着 GoMami 不为客户做数据备份、不对数据丢失负责，建议客户自行定期备份。部分第三方文章提到「每日自动备份到 AWS S3」，官方文档里找不到对应说明。买之前按「没有平台备份」来规划更稳妥。

24 小时的窗口意味着验证时间很紧。可行做法是开通后立刻排一次中国时间 20:00–23:00 的晚高峰测试，把路由和速度跑完再决定是否申请退款——不少线路中午正常，晚上九点就崩。

>👉 [开一台 HKG.Pulse.Mini 做晚高峰实测，24 小时内可申请全额退款](https://gomami.io/aff.php?aff=415&pid=4)

## 优惠码现在还能用吗

有两个历史促销码可查，但都无法确认当前有效。`Hi,LAX` 是洛杉矶系列 2026 年 6 月上线时的 20% 循环折扣，当时把 Nano 从 $29 压到 $23.20/月；`HappyBirthday` 是 2025 年首发期的 15% 折扣，曾把 Pulse.Mini 做到 $33.15/月。两者都来自第三方文章，官方页面没有确认它们在 2026 年 10 月仍然生效。结算页有 Validate 按钮，能验再算，别把它当既定价格写进预算。

## 常见问题

**GoMami 为什么比 Contabo 贵这么多？**

卖的东西不同。Contabo 用无限流量和每 vCPU 约 $1.75 的价格卖密度，路由是通用国际线路；GoMami 全线标 CN2 / AS9929 / CMIN2 三网优化，官方称中国大陆 RTT < 50ms，溢价买的是晚高峰不塌的回程。你的用户不在大陆，这笔钱就是白花。

**流量超了会自动扣费吗？**

不会。超出月度配额后可能被限速，具体取决于套餐；可以自助加购流量包，100 GB $6 起，立刻加到当期配额里。

**部署要多久，能装什么系统？**

付款后通常 1–5 分钟自动完成，IP 和登录凭据发到邮箱。模板覆盖 Ubuntu 22.04/24.04 LTS、Debian 11/12、CentOS Stream 9、AlmaLinux 8/9、Windows Server 2019/2022，其他系统可以挂 Custom ISO。控制面板基于 VirtFusion，能实时看 CPU、内存和流量。

**支持哪些付款方式？**

信用卡（Stripe，Visa/Mastercard）、Stripe 支付宝（支持人民币支付）、加密货币（USDT 等），也可以先充值余额，用余额自动续费避免欠费停服。

## 最后怎么选

按情况对号入座，比回头翻表格快：

只要能跑通用业务的便宜机器，Contabo 和 Hetzner 的每 vCPU 成本在 $2 上下，这一档 GoMami 没有位置。

用户在大陆、预算卡在 $30，**首选 LAX.Pulse.Nano**：同样 $29/月，它给 1 TB 出站，是新加坡和东京 Nano（500 GB）的两倍，流量单价 $29/TB 也是全线最低。选亚洲两地的理由只剩一个——物理距离更近，对延迟极敏感的实时应用值得用一半流量换那点 RTT。

需要香港落地又不想为单核付溢价，HKG.Pulse.Mini 是 $59，2 vCPU / 4 GB / 60 GB。香港 Pulse.Nano 那档要 $49 却只有 500 GB 流量和 2 GB 内存，流量单价 $98/TB 是全表最贵，除非你就是要最便宜的香港入口，否则加 $10 上 Mini 更合理。

跑游戏服、实时通信、编译任务这类吃单核的负载，Peak X5（Ryzen 9 9950X，最高 5.7GHz）$59 起，Turin（EPYC 9575F，官方资料写明配 PCIe Gen5 U.2 SSD 与 DDR5 6400）$69 起。两者差 $10，差的是平台代际和存储规格，按你的负载是吃单核频率还是吃 IO 来定。

流量需求大，LAX 全线把每 TB 成本压在 $29–$40，Titan 给到 30 TB 和 10 Gbps 端口。

下单前还有两件事：结算页确认实际扣款金额，官网首页和商店页的价格并不完全一致；把第一个晚高峰留出来测线路，24 小时退款窗口不长，但足够跑一次真实测试。

>👉 [去 GoMami 商店页按机房挑选具体套餐](https://bit.ly/Gomami)
