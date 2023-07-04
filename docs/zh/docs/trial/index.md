---
hide:
  - nav
---

# 体验社区版

<div style="text-align: center;">
  <p style="font-size: 18px;"><img src="./images/hu01.gif" alt="Image" width="80"> 欢迎安装体验！</p>
  <p style="font-size: 28px; color: green;">DaoCloud Enterprise 社区版! <img src="./images/hu02.gif" alt="Image" width="80"></p>
</div>

DCE 5.0 以云原生底座为核心，自研开源组件加持，提供云原生计算、网络、存储等能力，支持多云、多集群全生命周期统一纳管，
屏蔽底层基础设施复杂性，降低企业使用云原生应用门槛，提高应用开发效率。

<p style="font-size: 20px;">解锁社区版三部曲</p>

## <p><span style="font-family: 'Arial', sans-serif; font-size: 24px; color: #00FF00;">1st</span> 安装教程传送</p>

!!! tip

    1. 根据自身情况，选择安装教程
    2. 安装成功后，即可生成登录链接
    3. 通过默认账户和密码，即可登录获取密钥

### 在线安装

=== "kind 集群"

    **适用范围：**云原生小白和爱好者，在机器资源不充裕，并且对 Kubernetes 集群的了解还不够深入的情况下使用

    **预计时间：**10-30 分钟

    **前情描述：**Kind 是一个用来快速创建和测试 Kubernetes 的工具，它把环境的依赖降低到最小，
    仅需要机器安装了 Docker 即可使用。需要注意的是，该方式安装的特点仅支持通过节点端口的方式暴露
    DaoCloud Enterprise 社区版来访问服务。

    点击[进入安装](../install/community/kind/online.md)

=== "标准 Kubernetes 集群"

    **适用范围：**适合已经成功搭建过标准的 Kubernetes 集群的技术人员，在机器资源充足并且能够搭建 Kubernetes 集群的情况下使用。

    **预计时间：**10-30 分钟

    **前情描述：**需要对 Kubernetes 有一定了解，搭建一个标准 Kubernetes 集群即可开始安装。
    该方式安装的特点是支持通过节点端口、VIP 的方式暴露 DaoCloud Enterprise 社区版来访问服务。

    点击[进入安装](../install/community/k8s/online.md)

=== "公有云 Kubernetes 集群"

    **适用范围：**适合已经在多种云上部署业务，面临多云管理问题的用户使用。

    **预计时间：**10-30 分钟

    **前情描述：**直接在公有云平台创建一个 Kubernetes 集群，其余安装操作与标准 Kubernetes 集群在线安装一致。
    该方式安装的特点是支持通过公有云厂商提供的 CLB 方式暴露 DaoCloud Enterprise 社区版来访问服务，
    且支持接入和管理市面上主流的 Kubernetes 发行版。

    点击[进入安装](../install/community/k8s/online.md)

### 离线安装

如果您的网络受限，可以选择使用 Kubernetes 集群离线安装。

**适用范围：**适合安装环境为企业内网或其他网络需求

**预计时间：**10-30 分钟

**前情描述：**离线安装对网络没有要求，不过需要提前下载安装包

点击[进入安装](../install/community/k8s/offline.md)

## <p><span style="font-family: 'Arial', sans-serif; font-size: 24px; color: #00FF00;">2nd</span> 申请登录密钥</p>

1. 点击此处 免费申请「DCE 5.0 社区版」许可证密钥，许可证密钥将发送至您的邮箱
  （很多邮箱可能会拦截许可证密钥的邮件，如长时间未收到，可查看是否归为垃圾邮件）。

    ![check mail](./images/license01.png)

2. 在等待邮件的过程中，按屏幕提示，可先进入社区版登录页面（通过安装成功后获取的链接进入），点击`申请授权码`。

    ![get code](./images/license02.png)

3. 根据上图，您需要再获取 ESN（即集群系统独有的设备编码），具体获取方式为：

    1. 登录 DCE 社区版
    2. 点击左侧导航栏`全局管理` -> `平台设置` -> `正版授权`
    3. 点击`管理许可证`按钮，打开`管理许可证`页面，复制 ESN 编码。

    ![esn](./images/license03.png)

4. 收到许可证邮件后，回到`获取离线授权码`页面，输入设备独有的 ESN，输入许可证密钥后，即可获得离线授权码。

    ![get offline](./images/license04.png)

5. 复制并粘贴上一步换取的离线授权码，再次回到 ESN 编码的获取页面，
   在下方代码块输入离线授权码，点击`立即激活`。恭喜您！现在可以探索全新的 DCE 5.0 啦！

!!! note

    由于在申请许可证时，选择的有效期过短，有些小伙伴会出现许可证过期的情况，
    这时，可点击[查看更多续期操作](../dce/license0.md#_1)。

## <p><span style="font-family: 'Arial', sans-serif; font-size: 24px; color: #00FF00;">3rd</span> 开启云原生之旅</p>

**[云原生技术实践公开课](https://appu8cplrlw7661.h5.xiaoeknow.com)**：适合零基础或初级云原生开发者学习，涵盖云原生发展背景、基础知识、操作实践等内容。

**[视频教程](../videos/index.md)**：涵盖容器管理、全局管理、可观测性这三大模块功能的使用演示，更有商业版功能演示教程，欢迎大家参阅。

<p style="font-size: 20px;">了解更多 DaoCloud Enterprise 社区版</p>

[什么是容器管理](../kpanda/intro/what.md){ .md-button .md-button--primary }
[什么是全局管理](../ghippo/intro/what.md){ .md-button .md-button--primary }
[什么是可观测性](../insight/intro/what.md){ .md-button .md-button--primary }