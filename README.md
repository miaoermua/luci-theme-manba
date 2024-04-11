## Luci-theme-manba

黑金 OpenWrt Luci 主题冰红茶

主题纯娱乐主题配置和 Argon 主题相同，不太兼容原版 luci-theme-argon 如主题颜色 #542580 未生效请 (SSH) 删除 `rm /etc/config/argon-config` 后重新安装生成即是曼巴主题

Forked from [luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)

## 编译

适用于 LEDE 18.06 Lua 版本

```bash
git clone https://github.com/miaoermua/luci-theme-manba -b lede
make package/luci-theme-manba/compile V=s
```