# Pi 固件自动编译

## 固件介绍

- 本固件用于个人租房旁路使用，不适合所有人

## 基本信息

- 默认地址：192.168.0.10  
- 默认用户名：root  
- 默认密码：password

## 插件
<img src="https://github.com/Gabrielxzx/Actions-ImmortalWrt-SideRoute/blob/master/assets/luci/System.png" width="180" /><img src="https://github.com/Gabrielxzx/Actions-ImmortalWrt-SideRoute/blob/master/assets/luci/Service.png" width="180" /><img src="https://github.com/Gabrielxzx/Actions-ImmortalWrt-SideRoute/blob/master/assets/luci/Nas&VPN.png" width="180" /><img src="https://github.com/Gabrielxzx/Actions-ImmortalWrt-SideRoute/blob/master/assets/luci/Network.png" width="180" />

## 下载链接

- [Releases](https://github.com/Gabrielxzx/Actions-ImmortalWrt-SideRoute/releases)

## 备注

- 随缘更新，随缘增加型号
- 使用香橙派zero过程中若出现国内网络访问异常现象，需在防火墙自定义规则中加入以下规则  
	`iptables -t nat -I POSTROUTING -j MASQUERADE`

## 鸣谢

特别感谢以下项目：

- 感谢 ImmortalWrt 团队的 [ImmortalWrt 仓库](https://github.com/immortalwrt/immortalwrt)
- 感谢 kenzok8 大的 [Openwrt 整合包](https://github.com/kenzok8/openwrt-packages)
- 感谢 P3TERX 大的[云编译仓库](https://github.com/P3TERX/Actions-OpenWrt)和[中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)  

