设置变量
部署成功后，在 Pages 项目界面点击 设置 -> 变量和机密，添加以下变量：

UUID：使用 UUID 生成器 随机生成一个新的 UUID。
PROXYIP：填写代理 IP 地址，可从 随机代理 IP 站点 获取，或使用优选域名（例如 cdn-b100.xn--b6gac.eu.org）。
TR_PASS：填写一个复杂字符串，作为密码。

绑定 KV 命名空间image-20250322103724074
创建 KV:点击左侧存储和数据库，再选择 KV,然后创建一个新的 KV 命名空间
绑定 KV:回到创建的 Pages 界面。点击 设置 -> 【绑定】，点击添加，选择添加 KV 命名空间
注:变量名称只能填写“kv”(小写)


配置 BPB 面板参数
FakeDNS：设置enable

Proxy IPs / Domains：填写 IP 或者域名，PROXYIP 获取地址：点击访问

Clean IPs / Domains：优秀 IP 软件下载【点击下面 Download Scanner】 | 在线优选 IP：点击访问

TLS 端口：需要使用的端口打勾就可以，默认是 443 端口

ROUTING RULES：Bypass xxx是指 xxx 不走代理（直连访问）｜ Block xxx是指 xxx 被屏蔽访问（无法访问）

Bypass LAN：绕过本地局域网
Block Ads：屏蔽广告网址
Bypass Iran：绕过伊朗
Block Porn：屏蔽颜色网站
Bypass China：绕过中国大陆
Block QUIC：屏蔽 QUIC 协议
Bypass Russia：绕过俄罗斯
CUSTOM RULES：除了上面预设的规则外，你可以在这里自定义一些需要直连（Bypass）和屏蔽（Block）的 IP 地址/网站。
