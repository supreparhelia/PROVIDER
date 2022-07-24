# 公告：

本仓库是为了方便学术交流为目的，不提供任何代理上网的服务，也不会记录任何有关的信息，不提供任何承诺也不承担任何因使用本仓库中的文件与文档而产生法律责任，请遵守当地的法律法规！

# 简介

本仓库自动化功能全部基于 GitHub Actions 实现，如果有需要可以自行 Fork 实现个性化需求。
对网络上公开分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择Clash, Shadowrocket之类能自动切换低延迟节点的客户端。

本项目生成适用于 [**Clash Premium 内核**](https://github.com/Dreamacro/clash/releases/tag/premium)的规则集（RULE-SET），同时适用于所有使用 Clash Premium 内核的 Clash 图形用户界面（GUI）客户端。使用 GitHub Actions 北京时间每天早上 6:30 自动构建，保证规则最新。

## 说明

本项目规则集（RULE-SET）的数据主要来源于项目 [@Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) 和 [@v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)；[`Apple`](https://github.com/Loyalsoldier/clash-rules/blob/release/apple.txt) 和 [`Google`](https://github.com/Loyalsoldier/clash-rules/blob/release/google.txt) 列表里的域名来源于项目 [@felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)；中国大陆 IPv4 地址数据使用 [@17mon/china_ip_list](https://github.com/17mon/china_ip_list)。

本项目的规则集（RULE-SET）只适用于 Clash **Premium** 版本。Clash Premium 相对于普通版，增加了 **TUN 增强模式**，能接管设备所有 TCP 和 UDP 流量，类似 [Surge for Mac](https://nssurge.com) 的增强模式。更多高级特性请看[官方 wiki](https://github.com/Dreamacro/clash/wiki/premium-core-features)。

👉[Telegram群组](http://t.me/PapaLaozi) 
👉[Telegram频道](http://t.me/PoorTaoist) 

私人频道，谢绝打扰！
