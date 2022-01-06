---
cssclass: ad-column
---

> 本文介绍的是除官方的 obsidian sync 以外的同步方案，本文只提供思路，不会提供具体的操作步骤。

市面上的设备分为 PC 端（win、Mac、Linux）与移动端（iPhone或iPad、安卓）。

同步方案大体分为：

```ad-light-blue
- 复制粘贴，只适用与 PC（Win、Mac、Linux）之间进行同步。
- 设备厂商提供的云盘，如：apple 的 iCloud，华为的 huawei cloud，且都提供了 PC 客户端。
- 通过同步软件实现同步，如：syncthing ，相似的有 resillio sync、Dropsync、foldersync
- 通过 Git 同步
- 局域网共享
```

**建议移动设备(手机、iPad)上仅做预览，尽量不要使用双向同步和在手机上编辑，不然很容易导致文件冲突或数据丢失（混乱）。**
## 📒  同步前的准备工作
-   将 `.ovsidian` 文件夹复制两份，一份改名为 `.obsidian_ipad` ，另一份改为 `.obsidian_phone`。
-   然后在 obsidian app 的 `设置--->关于--->切换配置文件夹` 输入: `.obsidian_ipad`，这样就可以为 iPad 设备选择适配它的配置，</br> 如：修改 coloumn.css 才会在 iPad 上实现分栏效果。
-   这样做得好处就是可对不同的设备进行定制从而达到适配 PC、Android、iPad 的目的。
## 📲  如何选择同步方案
> 下面列举出不同设备之间的同步方案，请根据需要进行选择。

```ad-col2
title: PC To PC（Windows、Mac、Linux）
icon: list-ol
color: 0,162,110
- 最简单的方法就是复制粘贴。
- Mac to Windows 可在 Windows 上安装 iCloud 进行同步，Linux 上的 iCloud 只能查看不能进行同步。
- 在 PC 上都可安装 Git 客户端，用 Git 同步最安全，因为它带有版本控制。(推荐)
- Syncthing 提供 Linux、Windows、Mac 客户端，也可通过它进行同步。
- 在 Windows 上开启文件共享，然后在 Mac、Linux 安装对应的支持 samba 协议的软件也可进行同步，配置麻烦，对权限控制比较严格。
```

```ad-col2
title: PC（Windows、Mac、Linux） To Android
icon: list
color: 255,130,203
- 在 PC 和 Android 上都安装 Syncthing，通过它进行同步。
- 在 PC 和 Android 上都安装 Git 客户端，通过它进行同步，Android 设备上的 Git 客户端推荐使用：MGit
- 利用手机厂商的软件。如：huawei cloud、huawei share 等，未测试。
- Windows 上开启局域网共享，Android 设备上通过自带的文件管理器利用webDAV 进行连接，未测试。
```

<p></p>

```ad-col2
title: PC（Windows、Mac、Linux） To ios
icon: list-ol
color: 255,193,81
- windows/Mac 与 ios之间同步，可在 Windows/Mac 上安装 iCloud 进行同步，Linux 上的 iCloud 只能查看不能进行同步。
- Linux 与 ios 之间同步，只能通过 Git 同步，ios 上的 Git 客户端推荐使用：working copy。
- ios 上只能安装第三方的 Syncthing 软件 (Möbius Sync)，但它和 Obsidian 是不同的应用文件夹。
- Windows 上开启局域网共享，ios 设备上安装 Docements 软件，并使用 webDAV 进行连接
```

```ad-col2
title: ios To Android
icon: list
color: 0,158,164
- 移动端设备之间进行文件同步需要借助 PC 作为中转。
- 在 windows/Mac 上安装 iCloud 与 Syncthing，ios 设备通过 iCloud 同步文件到 PC，PC 通过 Syncthing 同步到安卓。
- 需自建 Git 仓库或者使用 Gitee 等提供的私有仓库，Android 设备安装 MGit，ios 设备安装 working copy,然后通过 git pull 进行拉取更新，git push 推送更新。
```

## 📎  参考
- [官方提供的同步方案](https://help.obsidian.md/Obsidian/iOS+app)
- [Obsidian Git 插件](https://github.com/denolehov/obsidian-git/issues/57)
- [Android 与 Win 同步](https://www.bilibili.com/read/mobile?id=13339751)
- [ios 与 PC 通过 Git 进行同步笔记](https://blog.csdn.net/weixin_37786060/article/details/119951142)