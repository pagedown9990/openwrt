# openwrt

[***P3TERX***大佬写的中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## 说明
- 基于***flippy大***的固件打包脚本，适配的机型有：***贝壳云***、***我家云***、***N1***、***S905x3（包括常见的hk1、h96、x96等盒子）***、***s922x（目前支持GT-King、GT-King Pro两款盒子）***、***微加云*** 等！
- releases中的直刷固件分为[***精简版***](https://github.com/hibuddies/openwrt/releases/tag/Z-ARMv8-mini) 和[***高大全版***](https://github.com/hibuddies/openwrt/releases/tag/Z-ARMv8-gdq)，精简版主要适合科学上网为主要需求的用户，高大全版用的是f大的配置文件，+o版是flowoffload加速,+版是sfe加速！
- Docker固件：`docker pull hibuddies/openwrt-aarch64:latest`，精简版：`docker pull hibuddies/openwrt-aarch64-mini:latest`，极致精简版无任何服务：`docker pull hibuddies/openwrt-aarch64-micro:latest`
- 固件默认IP：`192.168.1.1` 默认密码：`password`
- 刷机和升级方法请参考f大这两个帖子：[➦旧帖](https://www.right.com.cn/forum/thread-981406-1-1.html) 和 [➦新帖](https://www.right.com.cn/forum/thread-4055451-1-1.html)
- 精简版固件包含的插件预览：

  ![image](https://github.com/hibuddies/openwrt/blob/main/image/%E7%B2%BE%E7%AE%80%E7%89%88%E5%9B%BA%E4%BB%B6.jpg)

## 感谢

- flippy大
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [c-hive/gha-remove-artifacts](https://github.com/c-hive/gha-remove-artifacts)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
