# Actions-4B-OpenWrt

旁路由的情况下，可以科学上网，但是国内不能上网，需要在防火墙中添加自定义规则

```
iptables -t nat -I POSTROUTING -j MASQUERADE
```

已加入的

|原名|中文|
|:----|:----|
|luci-app-accesscontrol  	| 访问时间控制
|luci-app-arpbind  	      | IP/MAC绑定
|luci-app-autoreboot  	  | 支持计划重启
|luci-app-ddns   	        | 动态域名 DNS（集成阿里DDNS客户端）
|luci-app-filetransfer  	| 文件传输（可web安装ipk包）
|luci-app-firewall   	    | 添加防火墙
|luci-app-frpc            | 内网穿透客户端
|luci-app-frps            | 内网穿透服务端
|luci-app-nft-qos  	      | QOS流控 Nftables版
|luci-app-netdata         | Netdata 实时监控（图表）
|luci-app-nlbwmon   	    | 网络带宽监视器
|luci-app-ramfree  	      | 释放内存
|luci-app-sfe  	          | Turbo ACC网络加速（集成FLOW,BBR,NAT,DNS...
|luci-app-uhttpd  	      | uHTTPd Web服务器
|luci-app-unblockmusic  	| 解锁网易云灰色歌曲3合1新版本
|luci-app-upnp            | 通用即插即用UPnP（端口自动转发）
|luci-app-watchcat  	    | 断网检测功能与定时重启
|luci-app-wol   	        | WOL网络唤醒
|luci-app-adguardhome     | AdGuard Home
|luci-app-openclash       | Open Clash
|luci-app-openvpn         | Open VPN
|luci-app-openvpnserver   | Open VPN Server
|luci-app-aria2           | aria2
|luci-app-samba           | samba
|luci-app-ssr-plus        | 科学上网
|luci-app-transmission    | transmission
|                         |
|Utilities --> Shells --> zsh | zsh
|Utilities --> Editors --> vim-full | vim-full
|Utilities --> Comperssion --> unzip | unzip
|Utilities --> Terminal --> screen | screen
|Network --> iperf3       | iperf3 局域网测速


- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [P3TERX Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © P3TERX
