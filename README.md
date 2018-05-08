

<p align="right">
  <a href="https://www.akaxin.com/">
    <img
      alt="Akaxin"
      src="https://avatars3.githubusercontent.com/u/32624098?s=200&v=4"
      width="128"
    />
  </a>
</p>

[Akaxin](https://www.akaxin.com)
====

[![License](https://img.shields.io/badge/license-apache2-blue.svg)](LICENSE)

Akaxin 是一款开源免费的私有聊天软件，可以部署在任意服务器上，搭建自己的聊天服务器，供自己与朋友、用户使用。

反馈与建议，请联系 hi@akaxin.xyz


一、快速体验
----

**1. 启动服务器**

* **最新版本: [openzaly-0.5.4.jar](https://github.com/akaxincom/openzaly)**
    * 支持同时启用邀请码与实名账号
    * 增加默认好友、默认群
    * 管理员首次登陆后，注册机制默认修改为：匿名（无邀请码）
    * 使用electron分发服务器集成安装包（alpha version)
* 历史版本: [old releases](https://github.com/akaxincom/openzaly/releases)

启动命令：`java -jar openzaly-server.jar`

支持的启动参数：`java -jar openzaly-server.jar -h`

**2. 下载客户端**

> * [iOS](https://itunes.apple.com/cn/app/%E9%98%BF%E5%8D%A1%E4%BF%A1/id1346971087?mt=8)
> * [Android](https://www.akaxin.com)

**3. 访问站点**

> * 生成账号（手机账号与匿名均可）
> * 输入站点服务器
> * 首次登陆为管理员，邀请码：000000
> * 别的用户登陆后可以互加好友，开始聊天。

* 匿名账号，账号保存在设备本地，用户不会填写手机信息，任何地方都获取不到。

> **站点注册方式默认为匿名，进入站点后，请根据情况第一时间修改为 实名 或者 开启邀请码，防止恶意用户进入**


二、源码编译安装
----

需要本地有mvn

```
git clone https://github.com/akaxincom/openzaly.git
sh build.sh

// Windows 环境，请直接使用 mvn 进行编译即可。
```

三、扩展开发
----

Akaxin 具有灵活、强大的扩展机制（“管理平台” 就是一个扩展）。通过嵌入WEB页面，与后端的扩展API进行交互， 可以很轻松的构建像附近交友、店铺点评、在线游戏等丰富多彩的业务功能，而你的聊天服务器，也将摇身一变，成为一个强大的社交软件平台。

> 扩展机制处于技术预览阶段，如果你希望在自己的业务中开发自己的扩展，可以联系我们（ mail: hi@akaxin.xyz ），我们将免费提供文档与技术答疑。

以下是我们开发的一个 “校园社交” 的扩展，截图如下：

> 大家可以去 demo.akaxin.com 体验。

**校园扩展截图**




四、技术贡献者
----

> 以加入时间排序

* sisishiliu
* SAM2O2O
* childeYin
* yi.chao
* lei.yu
* cuikun
* alexfanchina
* Mino0885
* 505541778
