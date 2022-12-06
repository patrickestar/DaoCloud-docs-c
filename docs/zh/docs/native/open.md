# 开源项目

本页按字母顺序列出云原生开源项目的动态。

### A, B

- [Acorn：Acorn Labs 开源的 K8s 应用打包和部署框架](https://acorn.io/introducing-acorn/)  

    [Acorn](https://github.com/acorn-io/acorn) 能够将所有应用程序的 Docker 镜像、配置和部署规范打包成一个 Acorn 镜像工件，这个工件可以推送到任何 OCI 镜像仓库。
    因此，开发人员无需切换工具或技术栈就能够将在本地开发应用转移到生产中。
    Acorn 镜像通过在 Acornfile 中描述应用程序的配置来创建，无需 Kubernetes YAML 的样板文件。

- [Antrea CNI 插件 v1.9.0 发布（CNCF 项目）](https://github.com/antrea-io/antrea/releases/tag/v1.9.0)

    新增多个多集群功能，包括跨集群 Pod 间连接、节点控制器支持 Gateway 高可用、允许 Pod IP 作为多集群 service 的端点；
    增加类似于 kube-proxy 的 service 健康检查；审计日志添加规则名称；一个 service 支持 800+ 端点。

- [Antrea CNI 插件 v1.8.0 发布（CNCF 项目）](https://github.com/antrea-io/antrea/releases/tag/v1.8.0)  

    该版本主要新特性：增加 ExternalNode 功能、K8s 网络策略增加审计日志支持、支持利用 Antrea ClusterNetworkPolicy 控制 NodePort 服务的外部访问、允许对不同的网络端点进行逻辑分组、每次 Antrea release 都生成新的 Helm Chart 版本、支持拓扑感知 TopologyAwareHints、在 IPPool CRD 中添加状态字段。

- [APISIX 云原生 API 网关 v3.0 发布](https://github.com/apache/apisix/blob/release/3.0/CHANGELOG.md#300)

    v3.0 新增 Consumer Group 用于管理多个消费者、支持配置 DNS 解析域名类型的顺序、新增 AI 平面用于智能分析和可视化配置与流量、全面支持 ARM64、新增 gRPC 客户端、实现数据面与控制面的完全分离、提供控制面的服务发现支持、新增 xRPC 框架、支持更多四层可观测性、集成 OpenAPI 规范、全面支持 Gateway API。

- [APISIX 云原生 API 网关 v2.15.0 发布](https://github.com/apache/apisix/blob/release/2.15/CHANGELOG.md#2150)  

    该版本主要新特性：支持用户自定义插件的优先级、支持通过表达式决定插件是否需要执行、自定义错误响应、允许采集 Stream Route 上的指标。

- [Arbiter：时速云开源基于 K8s 构建的可扩展调度和弹性工具](https://mp.weixin.qq.com/s/xF6Zij2FB2dq3QsZO6ch1g)

    [Arbiter](https://github.com/kube-arbiter/arbiter) 聚合各种类型的数据，用户可以基于这些数据管理、调度或扩展集群中的应用程序。它可以帮助 Kubernetes 用户了解和管理集群中部署的资源，进而提高企业应用程序的资源利用率和运行效率。

- [Argo CD GitOps 工具 v2.5.0 发布（CNCF 项目）](https://github.com/argoproj/argo-cd/releases/tag/v2.5.0)

    该版本主要新特性：支持基于集群过滤应用程序、添加 Prometheus 健康检查、添加通知 API、支持 CLI 的自定义应用程序操作、增加对默认容器注释的支持、限制 redis 的出口规则、添加 Gitlab PR 生成器 webhook、新增 ApplicationSet Go 模板、新增 ArgoCD CLI 本地模板。

- [Argo 2022 年项目安全审计结果发布](https://mp.weixin.qq.com/s/m1-bnWKU54SYMfKW_xEkIA)  

    Argo 团队、CNCF 与软件安全公司 Ada Logics 合作，对 Argo 的四个项目进行安全审计。
    共发现 26 个问题：Argo CD 7 个，Argo Workflows 6 个，Argo Events 13 个。为 Argo CD 发布了七个 CVE，Argo Events 两个 CVE。
    截止报告发布时，所有可利用的问题都已修复，并作为安全建议发布在 [GitHub](https://github.com/orgs/argoproj/projects/19) 上。  
    审计报告全文: <https://github.com/argoproj/argoproj/blob/master/docs/argo_security_audit_2022.pdf>

- [Backstage 开发者门户构建平台的安全审计报告和威胁模型发布（CNCF 项目）](https://backstage.io/blog/2022/08/23/backstage-security-audit)  

    [审计](https://backstage.io/blog/assets/22-08-23/X41-Backstage-Audit-2022.pdf)共发现 10 个漏洞。
    在 Backstage [v1.5](https://backstage.io/docs/releases/v1.5.0) 中，其中的 8 个漏洞都已完全修复。
    尚待解决的 4 个问题中，3 个与速率限制和内部 DoS 问题相关。
    [威胁模型](https://backstage.io/docs/overview/threat-model)总结了操作员、开发人员和安全研究人员的主要安全考虑事项，涵盖 Backstage 典型设置中涉及的信任模型和角色、集成者的职责以及常见配置问题等。

- [Backstage 开发者门户构建平台 v1.4.0 发布（CNCF 项目）](https://github.com/backstage/backstage/releases/tag/v1.4.0)  

    该版本主要新特性：Search API 升级到 v1、新增后端系统（实验性）、大量命令行及授权后端符号弃用、增加了对 OpenAPI 规范中 $ref 处理的支持、增加 Apollo Explorer 支持（PoC）。

### C

- [Calico CNI 插件 v3.24.0 发布（CNCF 项目）](https://github.com/projectcalico/calico/blob/release-v3.24/calico/_includes/release-notes/v3.24.0-release-notes.md)

    该版本主要新特性：支持 IPv6 网络 wireguard 加密、通过 API 暴露 IPAM 配置和 IPAM block 亲和性、operator API 新增字段、支持分割 IP 池、从 pod 安全策略过渡到 pod 安全标准。

- [Carina 云原生本地存储项目 v0.11.0 发布](https://github.com/carina-io/carina/releases/tag/v0.11.0)  

    该版本主要新特性：支持 Cgroup v2、移除 HTTP Server、升级 CSI 官方镜像版本、移除 ConfigMap 同步控制器、carina 镜像移动到单独命名空间、增加 carina e2e 测试用以替代原有的 e2e 测试代码（开发测试中）、优化 Storageclass 参数的 pvc 调度逻辑。

- [cdk8s+：AWS 开源的 Kubernetes 开发框架正式可用](https://aws.amazon.com/blogs/containers/announcing-general-availability-of-cdk8s-plus-and-support-for-manifest-validation/)

    [cdk8s+](https://github.com/cdk8s-team/cdk8s) 允许用户使用熟悉的编程语言和面向对象的 API 来定义 Kubernetes 应用和可复用的抽象。
    相较于去年发布的 beta 版本，正式版本新增功能包括：隔离 pod 网络，只允许指定的通信；改进在同一节点上运行多个 pod的配置机制；集成 [Datree](https://github.com/datreeio/datree-cdk8s) 插件，使用第三方策略执行工具检查 Kubernetes 中的错误配置。

- [Cert-manager 云原生证书管理项目 v1.10.0 发布（CNCF 项目）](https://github.com/cert-manager/cert-manager/releases/tag/v1.10.0)

    该版本主要新特性：使用 trivy 扫描本地构建的容器；如果目标 Secret 配置错误或在请求后创建，重新同步签署请求；增加从 Kubernetes Secret 加载 Vault CA Bundle 的选项；支持在 chart 部署的所有资源上添加相同的标签。

- [Cert-manager 云原生证书管理项目升级成为 CNCF 孵化项目](https://www.cncf.io/blog/2022/10/19/cert-manager-becomes-a-cncf-incubating-project/)

    Cert-manager 是 Kubernetes 的一个插件，用于自动管理和颁发各种来源的 TLS 证书，为云原生工作负载提供加密保护。近日，CNCF 技术监督委员会已经投票接受 cert-manager 成为 CNCF 孵化项目。

- [Cert-manager 云原生证书管理项目 v1.9.0 发布（CNCF 项目）](https://github.com/cert-manager/cert-manager/releases/tag/v1.9.0)  

    该版本主要新特性：支持使用cert-manager certificate（alpha）、支持通过 Ingress 资源上的注释配置 ingress-shim 证书。

- [Chaosblade 混沌工程项目 v1.7.0 发布（CNCF 项目）](https://github.com/rook/rook/releases/tag/v1.10.0)

    该版本主要新特性：添加 time travel 实验、添加插件 zookeeper 和 clickhouse、jvm 性能优化、支持 blade 服务器的 mTLS 认证。

- [Chaos Mesh 混沌工程平台 v2.5.0 发布（CNCF 项目）](https://github.com/chaos-mesh/chaos-mesh/releases/tag/v2.5.0)

    该版本主要新特性：支持多集群混沌实验、HTTPChaos 增加 TLS 支持、允许在 Helm 模板中为 controller manager 和仪表盘配置 Pod 安全上下文、StressChaos 支持 cgroups v2。

- [Cilium CNI 插件 v1.12.0 发布（CNCF 项目）](https://github.com/cilium/cilium/releases/tag/v1.12.0)  

    该版本主要新特性：推出 Cilium Service Mesh（多控制平面、边车/无边车、Envoy CRD)、集成 Ingress Controller、增加 K8s 服务拓扑感知提示、初始 NAT46/64 实现、支持 Pod 启用 BBR 拥堵控制并将带宽管理器移出 beta、支持在集群池 v2 IPAM 模式下动态分配 pod CIDR、支持设置服务后端状态、出口网关升级到稳定状态。

- [Cloud Custodian 云资源管理工具 v0.9.20 发布（CNCF 项目）](https://github.com/cloud-custodian/cloud-custodian/releases/tag/0.9.20.0)

    该版本主要新特性：增加 K8s admission controller 模式、添加角色和集群角色资源。

- [Cloud Custodian 云资源管理工具升级为 CNCF 孵化项目](https://mp.weixin.qq.com/s/Z3knP5tJ4om3nW1nqXEjsA)  

    [Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)是一个云治理即代码工具，允许用户通过代码来管理和自动执行云安全、合规性、运营和成本优化的策略，包括编写管理 Kubernetes 资源的策略。与其他基于云的治理工具相比，提供了一个非常简单的 DSL 来编写策略及其跨云平台的一致性。

- [Cluster API 声明式集群生命周期管理工具 v1.3.0 发布（CNCF 项目）](https://github.com/kubernetes-sigs/cluster-api/releases/tag/v1.3.0)

    该版本主要新特性：支持自动更新由Kubeadm 控制平面提供商提供的机器证书、可以从新的容器镜像注册中心 registry.k8s.io 发布和消费集群 API 镜像、允许在控制平面节点上创建没有污点的集群、clusterctl 现在可以管理 IPAM 和 RuntimeExtension 提供者。

- [Clusternet 多云多集群管理项目 v0.13.0 发布](https://github.com/clusternet/clusternet/releases/tag/v0.13.0)

    该版本主要新特性：增加从父集群到子集群 pod 的路由功能、添加调度器配置并支持自定义调度器插件、支持 discovery v1beta1、只为 k8s v1.21.0 及更高版本提供发现 endpointslice 的支持、使用阈值聚合工作节点标签、支持按集群 subgroup 进行调度、为在 capi 中运行的 clusternet-agent 更新 RBAC 规则。

- [Constellation：Edgeless Systems 开源首个机密计算 Kubernetes](https://blog.edgeless.systems/hi-open-source-community-confidential-kubernetes-is-now-on-github-2347dedd8b0c)  

    [Constellation](https://github.com/edgelesssys/constellation) 旨在提供一个端到端的机密 K8s 框架。
    它将 K8 集群包裹在一个机密的上下文中，与底层云基础设施屏蔽开。
    其支持运行和扩展所有容器；提供基于 Sigstore 的节点和工件证明；提供基于 Cilium 的网络方案等。

- [Consul 服务发现框架 v1.13.0 发布（CNCF 项目）](https://github.com/hashicorp/consul/releases/tag/v1.13.0)

    该版本主要新特性：移除对 Envoy 1.19 的支持；Cluster Peering 支持联合 Consul 集群用于服务网格和传统服务发现；允许在不修改目录的情况下，通过透明代理模式的终端网关路由出口流量。

- [Contour Kubernetes ingress 控制器 v1.22.0 发布（CNCF 项目）](https://github.com/projectcontour/contour/releases/tag/v1.22.0)  

    该版本主要新特性：支持 Gateway API v0.5.0、允许在单一的路由中为一组条件配置一个直接响应、可以为用户证书验证启用撤销检查、合并访问记录和 TLS 密码套件验证。

- [Cortex 分布式 Prometheus 服务 v1.13.0 发布（CNCF 项目）](https://github.com/cortexproject/cortex/releases/tag/v1.13.0)  

    该版本主要新特性：新增元数据 API 查询器的 streaming 功能、为 compactor 提供实验性的shuffle sharding 支持、修复 Distributor 和 Ruler的内存泄漏、在分发请求时加入一个抖动来重置每个 pod 的初始时间。

- [CRI-O 容器运行时 v1.25.0 发布（CNCF 项目）](https://github.com/cri-o/cri-o/releases/tag/v1.25.0)  

    该版本主要新特性：支持设置运行时 pod 的最大日志文件大小、能够执行 Kubelet 的用户命名空间配置、新增注释用于配置容器的电源管理、 增加最小 checkpoint/restore 支持、通过 sigstore 签名来签署静态二进制包。

- [CubeFS 分布式存储系统 v3.1.0 发布（CNCF 项目）](https://github.com/cubefs/cubefs/releases/tag/v3.1.0)  

    该版本主要新特性：提供 QoS 服务以完善多租户隔离功能、优化混合云多级读缓存功能、支持两个副本的数据存储、卷支持配置 posixAcl 进行权限管理、为 datanode 添加数据分区总数限制。

- [CubeFS 分布式存储系统从 CNCF 沙箱升级为孵化项目](https://mp.weixin.qq.com/s/sAVaCa-yGEsJk3bUaJizmA)
  
    [CubeFS](https://github.com/cubefs) 是国内首个具备完整的对象及文件存储能力的云原生存储产品。
    CubeFS 支持多副本和纠删码引擎，提供多租户、多 AZ 部署、跨区域复制等特性；适用于大数据、AI、容器平台、数据库及中间件存算分离等广泛场景。

### D, E, F, G

- [Dapr 分布式应用运行时 v1.9.0 发布（CNCF 项目）](https://github.com/dapr/dapr/releases/tag/v1.9.0)

    该版本主要新特性：允许自定义可插拔组件、支持 OTel 协议、增加弹性观测指标、支持应用健康检查、支持设置默认弹性策略、允许使用任何中间件组件进行服务见调用、新增 pub/sub 命名空间消费者组、支持 Podman 容器运行时。

- [DeepFlow 自动化云原生可观测平台的首个开源版本正式发布](https://mp.weixin.qq.com/s/79wZ00RKoei_boZfiUmqgg)  

    [DeepFlow](https://github.com/deepflowys/deepflow) 是云杉网络研发的可观测性平台，基于 eBPF 等技术，实现自动同步资源、服务、K8s 自定义 Label 并作为标签统一注入到观测数据中。
    它能够自动采集应用性能指标和追踪数据而无需插码，SmartEncoding 创新机制将标签存储的资源消耗降低 10 倍。
    此外，还能集成广泛的数据源，并基于 SQL 提供北向接口。

- [DevSpace K8s 开发工具 v6.0 发布](https://github.com/loft-sh/devspace/releases/tag/v6.0.0)  

    该版本主要新特性：引入 pipeline 用于 管理 devspace.yaml 中的任务、新增导入功能将不同 devspace.yaml 文件合并在一起、新增 proxy command 在本地计算机上运行在容器中执行的命令。

- [Envoy Gateway API 网关 v0.2 发布](https://github.com/envoyproxy/gateway/releases/tag/v0.2.0)

    该版本主要新特性：支持 Kubernetes、支持 Gateway API 资源。

- [Envoy v1.23.0 发布（CNCF 项目）](https://www.envoyproxy.io/docs/envoy/v1.23.0/version_history/v1.23/v1.23.0)  

    该版本主要新特性：在一个 SDS 请求中发送多个集群或监听器的 SDS 资源、通过 HTTP 过滤器的配置名称来获取过滤器配置、监听器过滤器统计更新、dns_resolver 增加对多个地址的支持、为监听器过滤器添加动态监听器过滤器配置等。

- [eunomia-bpf：eBPF 轻量级开发框架正式开源](https://mp.weixin.qq.com/s/fewVoIKbLn5fYbXUaDyTpQ)

    [eunomia-bpf](https://gitee.com/anolis/eunomia) 由各高校和龙蜥社区共同开发，旨在简化 eBPF 程序的开发、分发、运行。在 eunomia-bpf 中，只需编写内核态代码即可正确运行，在部署时不需要重新编译，并提供 JSON/WASM 的标准化分发方式。

- [Flagger 渐进式交付攻击 v1.22.0 发布（CNCF 项目）](https://github.com/fluxcd/flagger/blob/main/CHANGELOG.md#1220)  

    该版本主要新特性：支持以 KEDA ScaledObjects 替代 HPA、在参数表中添加命名空间参数、为 Canary.Service 添加可选的 ``appProtocol`` 字段。

- [Fluent Bit 日志处理工具 v2.0.0 发布 （CNCF 项目）](https://github.com/fluent/fluent-bit/releases/tag/v2.0.0)

    该版本主要新特性：增加对 Traces 的支持（与 Prometheus 和 OpenTelemetry 完全集成）、允许 input 插件在一个单独的线程中运行、所有需启用安全的网络传输层将使用 OpenSSL、input 插件新增原生 TLS 功能、支持将更多的插件类型与 Golang 和 WebAssembly 集成、支持检查流经管道的数据、引入收集和处理内部指标的新 input 插件。

- [Flux 持续交付工具成为 CNCF 毕业项目](https://mp.weixin.qq.com/s/3F3DHuKEZqqd7M6-im6B-A)

    [Flux](https://github.com/fluxcd/flux2) 是一套面向 Kubernetes 的持续渐进交付解决方案，支持开发者和基础设施团队的 GitOps 和渐进交付。自 2021 年 3 月成为 CNCF 孵化项目以来，Flux 及其子项目 Flagger 在用户群、集成、软件使用、用户参与度、贡献等方面增长了 200-500%。

- [Flux 持续交付工具 v0.34.0 发布（CNCF 项目）](https://github.com/fluxcd/flux2/releases/tag/v0.34.0)

    该版本主要新特性：Flux 控制器的日志与 Kubernetes 的结构化日志保持一致、允许为非 TLS 容器仓库定义 OCI 源、从多租户集群的容器仓库处提取 OCI 工件时优先考虑静态凭证而非 OIDC 提供者。

- [Gatekeeper 策略引擎 v3.10.0 发布 （CNCF 项目）](https://github.com/open-policy-agent/gatekeeper/releases/tag/v3.10.0)

    该版本主要新特性：移除 Pod 安全策略并迁移到 Pod 安全准入、Mutation 功能升级为稳定、引入工作负载资源的验证（alpha）、性能改进。

- [Gatekeeper 策略引擎 v3.9.0 发布（CNCF 项目）](https://github.com/open-policy-agent/gatekeeper/releases/tag/v3.9.0)  

    该版本主要新特性：增加约束模式验证测试、增加对外部数据提供商的 TLS 支持、增加 pod 安全上下文变量、支持验证子资源、允许在 gator 验证中跳过测试、为 gator 添加 dockerfile、添加 opencensus 和 stackdriver exporter。

### H

- [Harbor 容器镜像仓库 v2.6.0 发布（CNCF 项目）](https://github.com/goharbor/harbor/releases/tag/v2.6.0)

    该版本主要新特性：引入缓存层，改善高并发情况下拉取工件的性能；增加 CVE 导出功能，允许项目所有者和成员导出由扫描仪生成的 CBR 数据；支持定期清理审计日志或按需运行，支持转发审计日志到远程系统日志终端；支持 WebAssembly 工件。

- [Helm 包管理工具 v3.10.0 发布（CNCF 项目）](https://github.com/helm/helm/releases/tag/v3.10.0)  

    该版本主要新特性：支持通过命令行设置 json 值、允许在执行 helm list 的时候不输出表头、增加参数用于配置客户端节流限制、支持控制是否要跳过 kube-apiserver 的证书校验。

- [Helm Dashboard：Komodor 开源 Helm 图形界面](https://github.com/komodorio/helm-dashboard)

    Helm Dashboard 可在本地运行并在浏览器中打开，可用于查看已安装的 Helm Chart，查看其修订历史和相应的 k8s 资源。此外，还可以执行简单的操作，如回滚到某个版本或升级到较新的版本。

- [Higress：阿里云开源的云原生网关](https://mp.weixin.qq.com/s/dgvd9TslzhX1ZuUNIH2ZXg)

    [Higress](https://github.com/alibaba/higress) 遵循 Ingress/Gateway API 标准，将流量网关、微服务网关、安全网关三合一，并在此基础上扩展了服务管理插件、安全类插件和自定义插件，高度集成 K8s 和微服务生态，包括 Nacos 注册和配置、Sentinel 限流降级等能力，并支持规则变更毫秒级生效等热更新能力。

### I, J

- [iLogtail 可观测数据采集器的全部代码开源](https://mp.weixin.qq.com/s/Cam_OjPWhcEj77kqC0Q1SA)

    近日，阿里云正式发布完整功能的 [iLogtail](https://github.com/alibaba/ilogtail) 社区版。
    本次更新开源全部 C++ 核心代码，该版本在内核能力上首次对齐企业版。新增日志文件采集、容器文件采集、无锁化事件处理、多租户隔离、基于 Pipeline 的新版配置方式等诸多重要特性。

- [Istio v1.16 发布（CNCF 项目）](https://istio.io/latest/news/releases/1.16.x/announcing-1.16/)

    该版本主要新特性：三个功能升级为 beta：外部授权功能、Kubernetes Gateway API 实现、基于路由的 JWT 声明；增加对 sidecar 和入口网关的 HBONE 协议的实验性支持、支持 MAGLEV 负载均衡算法、通过 Telemetry API 支持 OpenTelemetry tracing provider。

- [Istio 正式成为 CNCF 孵化项目](https://istio.io/latest/blog/2022/istio-accepted-into-cncf/)  

    [Istio](https://github.com/istio/istio) 指导委员会于今年 4 月向 CNCF 呈递了移交项目的申请。经过近 5 个月的审核，现成为孵化项目。

- [Istio 社区推出无 sidecar 代理的 Istio 数据平面模式 Ambient Mesh](https://mp.weixin.qq.com/s/JpLPuqbPggXsQzFR5pii8A)  

    [Ambient Mesh](https://github.com/istio/istio/tree/experimental-ambient) 将数据面的代理从应用 pod 中剥离出来独立部署，彻底解决 mesh 基础设施和应用部署耦合的问题。
    通过引入零信任隧道（ztunnel）和 Waypoint proxy（路径点代理）实现零信任且减少了网格的资源占用，同时还可以与 sidecar 模式无缝互通，降低了用户的运维开销。

- [Jaeger 分布式追踪系统 v1.36.0 发布（CNCF 项目）](https://github.com/jaegertracing/jaeger/releases/tag/v1.36.0)  

    该版本主要新特性：支持报告 span size 指标、增加多租户支持。

- [Jakarta EE 10 基于 Java 的框架发布，开启云原生 Java 时代](https://mp.weixin.qq.com/s/BQBy5AWFOc7kS55JBtBjiQ)

    [Jakarta EE 10](https://github.com/jakartaee/jakarta.ee) 引入了用于构建现代化和轻量级云原生 Java 应用的功能。
    具体包括：新增配置文件规范，定义一个用于轻量级 Java 应用和微服务的多供应商平台；针对适合微服务开发的较小运行时，提供了规范子集，包括用于构建应用的新 CDI-Lite 规范；支持多态类型；将 UUID 标准化为基本类型并扩展查询语言和查询 API。

### K

- [k8gb Kubernetes 全局负载均衡器  v0.10.0 发布（CNCF 项目）](https://github.com/k8gb-io/k8gb/releases/tag/v0.10.0)

    该版本主要新特性：可以通过环境变量访问 LeaderElection、支持 OpenTelemetry 的 tracing 方案、支持创建 K8GB 指标的Grafana 仪表盘样本、实现一致的轮询负载均衡策略。

- [Karmada 多云多集群容器编排平台 v1.4.0 发布（CNCF 项目）](https://github.com/karmada-io/karmada/releases/tag/v1.4.0)

    该版本主要新特性：新增声明式资源解释器、支持声明分发策略/集群分发策略的优先级、通过指标和事件增强可观测性能力、故障切换/优雅驱逐 FeatureGate 升级为 Beta 且默认开启。

- [Karmada 多云多集群容器编排平台  v1.3.0 发布（CNCF 项目）](https://github.com/karmada-io/karmada/releases/tag/v1.3.0)  

    该版本主要新特性：支持基于污点的优雅工作负载驱逐、引入多集群资源访问的全局代理、支持集群资源建模、新增基于 Bootstrap token 的集群注册方式、优化系统可扩展性等。

- [Karpenter 自动扩缩容工具 v0.19.0 发布](https://github.com/aws/karpenter/releases/tag/v0.19.0)

    该版本主要新特性：默认驱逐无控制器的 pod、将 AWS 设置从 CLI Args 迁移到 ConfigMap、支持 IPv6 自动发现、将 webhook和控制器合并为一个二进制文件。

- [Kata Containers 安全容器运行时 v3.0.0 发布](https://github.com/kata-containers/kata-containers/releases/tag/3.0.0)

    该版本主要新特性：新增 Rust 语言重写的容器运行时组件以及一个可选的集成虚拟机管理组件、支持主流的云原生生态组件（包括 Kubernetes、CRI-O、Containerd 以及 OCI 容器运行时标准等）、支持 cgroupv2、支持最新的 Linux 内核稳定版本。

- [Kata Container 容器安全项目 v2.5.0 发布](https://github.com/kata-containers/kata-containers/releases/tag/2.5.0)  

    该版本主要新特性：支持 containerd shimv2 日志插件、支持 virtio-block 多队列、支持 QEMU 沙箱功能、支持 containerd 的核心调度、kata-runtime iptables 子命令可在 guest 中操作 iptables、支持直接分配的卷。

- [KEDA 基于 Kubernetes 的事件驱动自动伸缩工具 v2.8.0 发布（CNCF 项目）](https://github.com/kedacore/keda/releases/tag/v2.8.0)

    该版本主要新特性：支持 NATS streaming、支持自定义 HPA 名称、支持在 ScaledJob 中指定最小 pod 副本数、允许 cpu/memory scaler 只对 pod 中的一个容器进行扩展。

- [Keptn 云原生应用程序生命周期编排项目 v0.19.0 发布（CNCF 项目）](https://github.com/keptn/keptn/releases/tag/0.19.0)

    该版本主要新特性：Helm-service 和 Jmeter-service 移到 keptn 贡献仓库、支持验证入站事件、引入签名的 Keptn Helm chart、支持通过 sigstore/cosign 签名所有发布/预发布的容器镜像。

- [Keptn 云原生应用程序生命周期编排项目 v0.18.0 发布（CNCF 项目）](https://github.com/keptn/keptn/releases/tag/0.18.0)

    该版本主要新特性：安装/卸载/升级命令不可用，改用 Helm 来操作 Keptn；在资源 API 中，尾部``/``将返回 404；弃用配置服务，所有 Keptn 的核心服务都依赖于资源服务。

- [Keptn 云原生应用生命周期编排引擎升级为 CNCF 孵化项目](https://mp.weixin.qq.com/s/gkv_fSnrRv0ao1AHUzBB5A)  

    [Keptn](https://github.com/keptn/keptn) 是基于事件的控制平面，使用声明式编程方法实现应用的连续交付和自动修复。Keptn 未来将支持 GitOps 和控制仓库的管理方式、RBAC、执行平面的远程管理等。

- [Knative 基于 Kubernetes 的 serverless 架构方案 v1.8.0 发布（CNCF 项目）](https://github.com/knative/serving/releases/tag/knative-v1.8.0)

    该版本主要新特性：修改默认域、升级 HPA 到 v2 版本、允许设置 seccompProfile 以启用使用受限的安全配置文件、最低 k8s 支持版本升至 v1.23、调和超时时间提高到 30 秒、默认启用 EmptyDir 卷功能参数。

- [Koordinator 云原生混部系统 v1.0 发布](https://github.com/koordinator-sh/koordinator/releases/tag/v1.0.0)

    该版本主要新特性：优化任务调度、优化 ElasticQuota 调度、支持细粒度的设备调度管理机制、支持根据节点的负载水位调整 BestEffort 类型 Pod 的 CPU 资源额度、支持使用 CPU Burst 来提高延迟敏感应用的性能、实现基于内存安全阈值和资源满足的驱逐机制、精细化 CPU 调度、支持在不侵入 Kubernetes 已有的机制和代码前提下预留资源、简化自定义重调度策略的操作。

- [Koordinator 云原生混部系统 v0.6.0 发布](https://github.com/koordinator-sh/koordinator/releases/tag/v0.6.0)

    该版本主要新特性：完善 CPU 精细化编排策略、支持在不侵入 Kubernetes 已有机制和代码的前提下实现资源预留、支持 Pod 腾挪（PodMigrationJob）、发布了全新的 Descheduler 框架。

- [Kruise Rollout 渐进式交付框架 v0.2.0 发布](https://openkruise.io/docs/)  

    该版本主要新特性：支持 Gateway API、支持有状态应用的分批发布、新增了“Pod 批次打标”能力、集成到 KubeVela 之中实现 Helm Charts 金丝雀发布能力。

- [KubeClipper：九州云开源的 K8s 多集群全生命周期管理工具](https://mp.weixin.qq.com/s/RVUB5Pw6-A5zZAQktl8AcQ)  

    [KubeClipper](https://github.com/KubeClipper-labs) 基于 kubeadm 工具进行二次封装，提供在企业自有基础设施中快速部署 K8S 集群和持续化全生命周期管理（安装、卸载、升级、扩缩容、远程访问等）能力，
    支持在线、代理、离线等多种部署方式，还提供了丰富可扩展的 CRI、CNI、CSI、以及各类 CRD 组件的管理服务。

- [KubeEdge 云原生边缘计算平台 v1.12 发布（CNCF 项目）](https://github.com/kubeedge/kubeedge/blob/master/CHANGELOG/CHANGELOG-1.12.md)

    该版本主要新特性：引入下一代云原生设备管理接口（DMI）、新版本的轻量级引擎 Edged 升级为 GA、EdgeMesh 新增高可用模式、支持边缘节点从云端升级、支持边缘 Kube-API 端点的授权、支持 GigE Device Mapper。

- [KubeEdge 审计报告发布](https://github.com/kubeedge/community/blob/master/sig-security/sig-security-audit/KubeEdge-security-audit-2022.pdf)  

    OSTIF（Open Source Technology Improvement Fund，开源技术改进基金会）完成了对 KubeEdge 的安全审计。审计发现了 12 个严重程度为中等的问题，建立了威胁模型，并集成到 OSS Fuzz。KubeEdge 安全团队已经在新发布的 v1.11.1、v1.10.2 和 v1.9.4 中对所有问题进行了修复。

- [KubeKey 集群部署工具 v3.0 发布](https://github.com/kubesphere/kubekey/releases/tag/v3.0.0)

    该版本主要新特性：为 docker 构建和推送添加 GitHub 工作流、支持执行自定义设置脚本、添加 k3s 控制平面控制器和启动控制器、添加 k3s 容器运行时配置、添加 k3s e2e 测试支持、自定义 OpenEBS 基本路径、重构 KubeKey 项目、支持更多的 Kubernetes 和 k3s 版本。

- [KubeKey 集群部署工具 v2.3.0 发布](https://github.com/kubesphere/kubekey/releases/tag/v2.3.0)

    该版本主要新特性：添加 kubelet pod pid 限制、使用 Jenkins Pipeline 替代 GitHub Actions、在创建集群或添加节点时增加安全增强命令、删除集群或节点时清理 vip、支持 kube-vip BGP 模式、支持清理 CRI、支持  kube-vip、支持 k8s 最近发布的补丁版本。

- [Kubernetes 1.26 抢先看](https://sysdig.com/blog/kubernetes-1-26-whats-new/)

    Kubernetes 1.26 即将发布，包括 37 项增强功能，11 个将升级为稳定，10 个是现有功能的改进，16 个是全新功能，还有一个是废弃功能。
    其中，有个新功能非常值得注意，可能改变用户与 Kubernetes 的交互方式——用其他命名空间的快照来配置卷。
    还有一些针对机器学习等高性能工作负载的新功能，以及简化集群管理员操作的功能（对OpenAPIv3 的支持）。

- [Kubernetes 发布 Kubernetes CVE 订阅列表](https://kubernetes.io/blog/2022/09/12/k8s-cve-feed-alpha/)

    Kubernetes 现在支持通过订阅一个自动更新的 [JSON feed](https://kubernetes.io/docs/reference/issues-security/official-cve-feed/index.json)，跟踪 Kubernetes 的安全问题（也称为 "CVE"，来自于不同产品和供应商的公共安全问题的数据库）。

- [Kubernetes v1.25 发布（CNCF 项目）](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.25.md)  

    该版本主要新特性：升级到 Stable：Pod Security Admission 、临时容器、cgroups v2 支持、网络策略中的 endPort、本地临时存储容量隔离、核心 CSI Migration、CSI 临时卷升级；升级到 Beta：SeccompDefault、CRD 验证表达式语言；引入 KMS v2 API 等。

- [Kubernetes Gateway API v0.5.0 发布](https://github.com/kubernetes-sigs/gateway-api/releases/tag/v0.5.0)  

    该版本主要新特性：三个 API 升级为beta：``GatewayClass``、``Gateway``和``HTTPRoute``；引入了 experimental 和 standard 版本渠道；通过指定端口号，路由可以连接到网关；支持 URL 重写和路径重定向。

- [Kubespray Kubernetes 集群部署工具 v2.20.0 发布](https://github.com/kubernetes-sigs/kubespray/releases/tag/v2.20.0)

    该版本主要新特性：支持 Rocky Linux 8 和 Kylin Linux、在重置角色中添加 “flush ip6tables” 任务、支持 NTP 配置、添加 kubelet systemd 服务加固选项、为 CoreDNS/NodelocalDNS 添加重写插件、为 kubelet 添加 SeccompDefault admission 插件、为 k8s_nodes 增加 extra_groups 参数、新增 ingress nginx webhook、增加对节点和 pod pid 限制的支持、支持启用默认的 Pod 安全配置。

- [KubeVela 混合多云环境应用交付平台 v1.6.0 发布（CNCF 项目）](https://github.com/kubevela/kubevela/releases/tag/v1.6.0)

    该版本主要新特性：支持资源交付可视化、提供可观测基础设施搭建、面向应用的可观测、可观测即代码的能力、支持多环境流水线统一管理、支持应用间配置的共享并与第三方外部系统做配置集成。

- [KubeVela 混合多云环境应用交付平台 v1.5.0 发布（CNCF 项目）](https://github.com/kubevela/kubevela/releases/tag/v1.5.0)  

    该版本主要新特性：插件框架优化，提供创建脚手架、打包、推送到插件注册表等整个插件生命周期的管理；支持以 CUE 格式定义插件，并使用 CUE 参数来渲染部分插件；新增大量 vela cli 命令；VelaUX 支持管理由 CLI 创建的应用程序。

- [KubeVirt 虚拟机管理插件 v0.58.0 发布（CNCF 项目）](https://github.com/kubevirt/kubevirt/releases/tag/v0.58.0)

    该版本主要新特性：在 cluster-deploy 中默认启用 DataVolume 垃圾回收、能够在启用受限的 Pod 安全标准时运行、添加 tls 配置、修复在有 containerd 的系统上带有 containerdisks 的虚拟机迁移失败问题。

- [KubeVirt 虚拟机管理插件 v0.57.0 发布（CNCF 项目）](https://github.com/kubevirt/kubevirt/releases/tag/v0.57.0)  

    该版本主要新特性：弃用 SR-IOV 热迁移功能门、弃用虚拟机实例预设资源、增加对虚拟机输出资源类型的支持、支持 DataVolume 垃圾回收、允许对配置虚拟机拓扑分布约束的支持。

- [KubeVirt 虚拟机运行项目 v0.55.0 发布（CNCF 项目）](https://github.com/kubevirt/kubevirt/releases/tag/v0.55.0)  

    该版本主要新特性：引入克隆 CRD、控制器和 API、引入弃用策略、增加 virt-launcher 的内存开销、启用内存转储到 VMSnapshot 中、支持监控 VMI 迁移对象从创建到某个特定阶段所需的时间、允许 VMI 从根目录迁移到非根目录。

- [KubeVirt 虚拟机运行项目 v0.55.0 发布（CNCF 项目）](https://github.com/kubevirt/kubevirt/releases/tag/v0.55.0)  

    该版本主要新特性：引入克隆 CRD、控制器和 API、引入弃用策略、增加 virt-launcher 的内存开销、启用内存转储到 VMSnapshot 中、支持监控 VMI 迁移对象从创建到某个特定阶段所需的时间、允许 VMI 从根目录迁移到非根目录。

- [KubeWharf：字节跳动开源云原生项目集](https://mp.weixin.qq.com/s/uNbT3Ss0rBYc9pqlZe3n8Q)

    [KubeWharf](https://github.com/kubewharf) 是一套以 Kubernetes 为基础构建的分布式操作系统，由一组云原生组件构成，专注于提高系统的可扩展性、资源利用率、可观测性、安全性等，支持大规模多租集群、在离线混部、存储等场景。
    KubeWharf 第一批计划开源三个项目：高性能元信息存储系统 KubeBrain、kube-apiserver 七层网关 KubeGateway、轻量级多租户方案 KubeZoo。

- [Kuma 服务网格 v2.0 发布（CNCF 项目）](https://github.com/kumahq/kuma/releases/tag/2.0.0)

    该版本主要新特性：在 CNI 和 init 容器配置中增加对 eBPF 的支持、新增 3 个“下一代”策略、优化用户界面、支持配置控制平面/API 服务器所支持的 TLS 版本和密码、允许配置多个 UID 使其被流量重定向忽略、允许在使用 iptables 进行流量重定向时开启日志功能。

- [Kuma 服务网格项目 v1.8.0 发布（CNCF 项目）](https://github.com/kumahq/kuma/releases/tag/1.8.0)  

    该版本主要新特性：跨网格网关支持多区域运行、网格网关/内置网关增加可观测性功能、重写 CNI、网格网关支持路径重写和报头添加/删除、支持过滤代理的指标、简化 TCP 流量日志实现、支持 Projected Service Account Tokens。

- [KusionStack：蚂蚁集团开源的可编程云原生协议栈](https://mp.weixin.qq.com/s/EZrVKdZ_hG5-p_HltaTCMg)

    [KusionStack](https://github.com/KusionStack) 通过自研的 DSL（KCL）沉淀运维模型（[Kusion Model](http://github.com/KusionStack/konfig)），将基础设施部分能力的使用方式从白屏转为代码化，同时结合 DevOps 工具链（Kusion CLI）实现配置快速验证和生效，以此提升基础设施的开放性和运维效率。

- [Kusk Gateway 自助式 API 网关 v1.1.0 发布](https://github.com/kubeshop/kusk-gateway/releases/tag/v1.1.0)

    该版本主要新特性：支持指定服务或主机验证 authentication header、支持速率限制策略、通过在 OpenAPI 规范中注释简化 HTTP 缓存的复杂性、由 Envoy 本地处理所有 mocking。

- [Kyverno 云原生策略引擎 v1.8.0 发布（CNCF 项目）](https://github.com/kyverno/kyverno/releases/tag/v1.8.0)

    该版本主要新特性：新增 podSecurity 验证子规则，集成 Pod Security Admission 库；支持 YAML 清单签名验证；允许生成规则在单个规则中生成多个资源；支持OpenTelemetry；支持测试生成策略；支持 Kubernetes 1.25。

- [Kyverno 云原生策略引擎升级成为 CNCF 孵化项目](https://mp.weixin.qq.com/s/GijHJm6-JcqfcLn91vSs6g)  

    [Kyverno](https://github.com/kyverno/kyverno) 是为 Kubernetes 打造的策略引擎，为 K8s 配置管理提供了自动化和安全性。
    接下来项目计划添加一些特性，如 YAML 签名和验证、OpenTelemetry 支持、幂等（idempotent）自动生成的 pod 控制器策略、增强的 pod 安全标准集成、基于 OCI 的策略捆绑、集群内 API 调用等。

### L, M, N

- [Linkerd 服务网格项目 v2.12.0 发布（CNCF 项目）](https://github.com/linkerd/linkerd2/releases/tag/stable-2.12.0)  

    该版本主要新特性：允许用户以完全零信任的方式定义和执行基于 HTTP 路由的授权策略；支持使用 Kubernetes Gateway API 进行配置；初始化容器增加对 ``iptables-nft`` 的支持。

- [Litmus 混沌工程框架 v2.14.0 发布（CNCF 项目）](https://github.com/litmuschaos/litmus/releases/tag/2.14.0)

    该版本主要新特性：在 DNS 实验中添加对 containerd CRI 支持、支持在service mesh 环境下执行 http-chaos 实验、在网络实验中增加源和目的端口支持、支持为混沌运行器的 pod 提供自定义标签、优化混沌结果中探针状态模式的描述。

- [MetalLB Kubernetes 负载均衡器 v1.3.2 发布（CNCF 项目）](https://metallb.universe.tf/release-notes/#version-0-13-2)  

    该版本主要新特性：支持通过 CRD 进行配置（不再支持 ConfigMap）；可以在 L2 或 BGP 模式中广播地址，或者只分配 IP 不广播地址；为 L2 Announcement 和 BGP Announcement 增加节点选择器支持；新增 BGPPeer 选择器；支持使用 kustomize 进行更灵活的部署；增加 LoadBalancerClass 支持；支持多协议 BGP。

- [MicroK8s 轻量级 Kubernetes 发行版 v1.25 发布](https://github.com/canonical/microk8s/releases/tag/v1.25)

    该版本主要新特性：新增“严格限制”（strict confinement）的隔离级别以限制主机系统访问和实施更严格的安全态势、snap 大小减少了 25%、支持镜像侧加载（sideloading）、新增插件 kube-ovn 和 osm-edge。

- [Mimir Prometheus 长期存储项目 v2.4.0 发布](https://github.com/grafana/mimir/releases/tag/mimir-2.4.0)

    该版本主要新特性：引入查询调度器 query-scheduler，并支持 DNS-based 和 ring-based 两种服务发现机制；新增 API 端点暴露每个租户的 limit；增加新的 TLS 配置选项；允许限制最大范围查询长度。

- [Mimir Prometheus 长期存储项目 v2.3.0 发布](https://github.com/grafana/mimir/releases/tag/mimir-2.3.0)

    该版本主要新特性：支持摄取 OpenTelemetry 格式的指标、新增用于元数据查询的租户联盟、简化对象存储配置、支持导入历史数据、优化即时查询功能、默认启用查询分片。

- [Mimir 新功能：将 Graphite、Datadog、Influx 和 Prometheus 的指标纳入统一的存储后端](https://grafana.com/blog/2022/07/25/new-in-grafana-mimir-ingest-graphite-datadog-influx-and-prometheus-metrics-into-a-single-storage-backend/)  

    [Mimir](https://github.com/grafana/mimir) 是 Grafana Labs 在 Cortex 基础上开源的时序数据库。
    Mimir 现在开源了[三个代理](https://github.com/grafana/mimir-proxies)，用于从 Graphite、Datadog 和 InfluxDB 摄取指标，并将这些指标存储在 Mimir 中，这为 Mimir 从任何系统摄取指标奠定了基础。
    未来将支持本地摄取 OpenTelemetry 的 OTLP。

- [Nightgale 夜莺监控 v5.10 发布](https://github.com/ccfos/nightingale/releases/tag/v5.10.0)  

    该版本主要新特性：支持 recording rule 的管理、告警规则支持生效到多集群、仪表盘变量支持 TextBox、告警屏蔽支持更多操作符、更灵活的自定义告警内容。

### O

- [OCM 多集群管理平台 v0.9 发布（CNCF 项目）](https://www.cncf.io/blog/2022/10/31/open-cluster-management-november-2022-update/)

    该版本主要新特性：降低托管集群上的worker agent 的权限、支持访问 kube-apiserver 及托管集群中的其他服务、支持使用 AddOn API 参考 AddOn 配置。

- [OPA 通用策略引擎 v0.44.0 发布（CNCF 项目）](https://github.com/open-policy-agent/opa/releases/tag/v0.44.0)  

    该版本主要新特性：修复 3 个 CVE 漏洞、Set Element Addition 优化、内置 Set union 优化、在 OPA 评估命令中添加优化参数、允许将更多的捆绑程序编译到 WASM 中。

- [OPA 通用策略引擎 v0.43.0 发布（CNCF 项目）](https://github.com/open-policy-agent/opa/releases/tag/v0.43.0)

    该版本主要新特性：Rego Object 插入的线性扩展优化、状态和日志插件现在可以接受 HTTP 2xx 状态代码、OPA bundle 命令现在支持 .yml 文件、存储系统修复、Rego 编译器和运行环境 bug 修复和优化。

- [OpenEBS 云原生存储 v3.3.0 发布（CNCF 项目）](https://github.com/openebs/openebs/releases/tag/v3.3.0)  

    该版本主要新特性：弃用 arch-specific 容器镜像、为 LocalPV Hostpath 强制执行带有 ext4 文件系统的主机路径配额、增强 NDM 功能、在 cstor 中添加日志以改善调试能力、增加速率限制器以减少 LocalPV LVM 中的日志泛滥问题。

- [OpenKruise 云原生应用自动化管理套件 v1.3.0 发布（CNCF 项目）](https://github.com/openkruise/kruise/releases/tag/v1.3.0)

    该版本主要新特性：支持自定义探针并将结果返回给 Pod yaml、SidecarSet 支持在 kube-system 和 kube-public 命名空间下注入 pod、增加对上游 AdvancedCronJob 的 timezone 支持、WorkloadSpread 支持 StatefulSet。

- [Open Service Mesh 服务网格 v1.2.0 发布（CNCF 项目）](https://github.com/openservicemesh/osm/releases/tag/v1.2.0)  

    该版本主要新特性：支持自定义信任域（即证书通用名）、Envoy 更新到 v1.22，并且使用 envoyproxy/envoy-distroless 镜像、增加对 Kubernetes 1.23 和 1.24 的支持、支持限制 TCP 连接和 HTTP 请求的本地 per-instance 速率、修复 Statefulset 和 headless service。

- [OpenShift Toolkit 1.0，简化云原生应用的开发](https://cloud.redhat.com/blog/announcing-openshift-toolkit-enhance-cloud-native-application-development-in-ides)

    [OpenShift Toolkit](https://github.com/redhat-developer/vscode-openshift-tools) 是一套 VS Code 和 IntelliJ 扩展。其功能包括：支持连接和配置 OpenShift；提供混合云支持，开发者可以连接到任何正在运行的 OpenShift 实例；可通过本地工作区、git 仓库或默认的 devfile 模板来开发应用程序；允许采用一键式策略，将仓库代码直接部署到 OpenShift；提供 Kubernetes 资源管理、无缝 Kube 配置上下文切换；多平s台支持。

- [OpenTelemetry v1.13.0 发布（CNCF 项目）](https://github.com/open-telemetry/opentelemetry-specification/releases/tag/v1.13.0)  

    该版本主要新特性：在设置 span 时Context 是不可变的、支持实验性的配置 OTLP 指标输出器的默认直方图聚合、允许日志处理器修改日志记录、添加实验性的事件和日志 API 规范、在流程语义约定中添加网络指标、为 GraphQL 添加语义约定。

- [Openyurt 云原生边缘计算项目 v1.1.0 发布（CNCF 项目）](https://github.com/openyurtio/openyurt/releases/tag/v1.1.0)

    该版本主要新特性：支持 DaemonSet 工作负载的 OTA/自动升级模式、支持 e2e 测试的自治功能验证、启用数据过滤功能、增加统一云计算边缘通信方案的建议、改进 health checker。

- [Openyurt 云原生边缘计算项目 v1.0.0 发布（CNCF 项目）](https://github.com/openyurtio/openyurt/releases/tag/v1.0.0)  

    该版本主要新特性：NodePool API 版本升级到 v1beta1、使用 CodeCov 跟踪单元测试覆盖率、新增两份 OpenYurt 组件的性能测试报告。

- [osm-edge：易衡科技 Flomesh 开源的边缘服务网格](https://mp.weixin.qq.com/s/tbCxbKFQkvx84Ku5IWg38g)

    [osm-edge](https://github.com/flomesh-io/osm-edge) 采用 [osm](https://github.com/openservicemesh/osm) 作为控制平面，可编程网关 [Pipy](https://github.com/flomesh-io/pipy) 作为数据平面。
    支持 SMI 规范；支持 ingress、gateway API、跨集群服务发现的 [fsm](https://github.com/flomesh-io/fsm)，提供“k8s 集群内+多集群”的“东西+南北”流量管理和服务治理能力。
    其开发和测试环境采用 k3s、k8e 等，因此用户可以快速低成本地在 x86、arm、RISC-V、龙芯等硬件平台上部署低资源高性能的服务网格。

### P

- [Pixie Kubernetes 观测平台 发布 Plugin System](https://www.cncf.io/blog/2022/07/06/easy-observability-with-open-standards-introducing-the-pixie-plugin-system/)  

    [Pixie Plugin System](https://github.com/pixie-io/pixie-plugin) 允许用户将其 Pixie 数据导出到任何支持 OpenTelemetry 的服务中。这意味着用户可以利用外部数据存储长期保留数据，在现有工作流和仪表盘中无缝采用 Pixie，将 Pixie 数据与其他数据流结合。

- [Phlare：Grafana 开源的大规模持续性能分析数据库](https://grafana.com/blog/2022/11/02/announcing-grafana-phlare-oss-continuous-profiling-database/)

    [Phlare](https://github.com/grafana/phlare) 是一个水平可扩展、高可用、多租户的持续分析数据聚合系统，与 Grafana 完全集成，可以与指标、日志和追踪等观测指标相关联。安装只需一个二进制文件，无需其他依赖项。
    Phlare 使用对象存储进行长期数据存储，并兼容多种对象存储实现。其原生多租户和隔离功能集允许多个独立团队或业务部门运行一个数据库。

- [Podman 容器引擎 v4.3.0 发布](https://github.com/containers/podman/releases/tag/v4.3.0)

    命令更新：支持改变容器的资源限制、删除 K8s YAML 创建的 pod 和容器、支持 K8s secret、支持从 URL 读取 YAML、支持 emptyDir 卷类型、支持 ConfigMap 中的二进制数据；支持重复的卷挂载。

- [Podman 容器运行时项目 v4.2.0 发布](https://github.com/containers/podman/releases/tag/v4.2.0)  

    该版本主要新特性：支持 GitLab Runner、新增命令用于创建现有 pod 的副本、新增命令用于同步数据库和任何卷插件之间的状态变化、pod 新增退出策略、自动清理未使用的缓存 Podman 虚拟机镜像、允许不同容器的多个 overlay 卷重复使用同一个 workdir 或 upperdir。

- [Prometheus v2.40.0 发布（CNCF 项目）](https://github.com/prometheus/prometheus/releases/tag/v2.40.0)

    该版本主要新特性：增加对原生直方图的实验性支持、Kubernetes 发现客户端支持使用 protobuf 编码、改善排序速度、增加企业管理分区。

- [Prometheus v2.39.0 发布（CNCF 项目）](https://github.com/prometheus/prometheus/releases/tag/v2.39.0)

    该版本主要新特性：增加对摄取无序样本的实验性支持、优化内存资源用量。

- [Prometheus v2.37.0 发布（CNCF 项目）](https://github.com/prometheus/prometheus/releases/tag/v2.37.0)  

    该版本主要新特性：允许 Kubernetes 服务发现从端点角色向目标添加节点标签、TSDB 内存优化、读取 WAL 时减少睡眠时间、优化签名创建、添加超时和 User-Agent header。

- [Prometheus v2.37.0 发布（CNCF 项目）](https://github.com/prometheus/prometheus/releases/tag/v2.37.0)  

    该版本主要新特性：允许 Kubernetes 服务发现从端点角色向目标添加节点标签、TSDB 内存优化、读取 WAL 时减少睡眠时间、优化签名创建、添加超时和User-Agent header。

### R, S

- [Rainbond 云原生多云应用管理平台 v5.9.0 发布](https://github.com/goodrain/rainbond/releases/tag/v5.9.0-release)

    该版本主要新特性：支持 Containerd 容器运行时、支持使用 grctl 命令更改 cluster API 地址、支持 K8s 1.24 和 1.25、支持 MiniKube 部署、支持自定义监控规则。

- [Rainbond 云原生多云应用管理平台 v5.8.0 发布](https://github.com/goodrain/rainbond/releases/tag/v5.8.0-release)  

    该版本主要新特性：支持一键导入 Kubernetes 集群中已存在的应用、支持直接通过 Jar、War 包或 Yaml 文件部署组件、支持创建 Job/CronJob 类型任务、支持扩展应用和组件支持的属性、支持 Dockerfile 使用私有镜像构建。

- [Serverless-cd：Serverless Devs 发布基于 Serverless 架构的轻量级 CI/CD 框架——](https://mp.weixin.qq.com/s/ps_ZFsv7KGwV2V61SvvWIA)

    Serverless Devs 是业内首个支持主流 Serverless 服务/框架的云原生全生命周期管理的平台。[Serverless-cd](https://github.com/Serverless-Devs/serverless-cd) 基于 Serverless Devs 打造，完全遵循 Serverless 架构最佳实践，在规范和生态层面参考 Github Action 的实现。其采用 Master Worker 模型和事件驱动的架构，可用于快速构建企业内部应用管理 PaaS 平台。

- [Serverless Devs 进入 CNCF 沙箱，成首个入选的 Serverless 工具项目](https://mp.weixin.qq.com/s/ICVDO3U5Ea1DzP3LFJq8mQ)

    [Serverless Devs](https://github.com/Serverless-Devs/Serverless-Devs) 由阿里云开源，致力于为开发者提供强大的工具链体系。借此，开发者不仅可以一键体验多云 Serverless 产品，极速部署 Serverless 项目，还可以在 Serverless 应用全生命周期进行项目管理，与其他工具/平台集成，提升研发运维效能。

- [Skywalking 应用性能监控系统 v9.2.0 发布](https://github.com/apache/skywalking/releases/tag/v9.2.0)  

    该版本主要新特性：新增 K8s Pod 的 eBPF 网络分析功能、支持 MySQL 和 PostgreSQL 监控、关联事件组件和追踪、日志组件。

- [SPIFFE 与 SPIRE 项目正式成为 CNCF 毕业项目](https://www.cncf.io/announcements/2022/09/20/spiffe-and-spire-projects-graduate-from-cloud-native-computing-foundation-incubator/)

    [SPIFFE](https://github.com/spiffe/spiffe) 为现代生产环境中的各种工作负载提供安全身份，消除了机密信息的共享需求，有望成为更高级别的平台中立安全控制方案的实现基础。
    [SPIRE](https://github.com/spiffe/spire)（SPIFFE 运行时环境）则负责在各种平台上实现 SPIFFE 规范，并强制发布身份的多因素证明。

- [Strimzi 消息中间件 Kafka 的 K8s operator v0.31.0 发布（CNCF 项目）](https://github.com/strimzi/strimzi-kafka-operator/releases/tag/0.31.0)  

    该版本主要新特性：支持 Kafka 3.2.1；可插拔的 Pod 安全配置文件，内置支持受限的 Kubernetes 安全配置文件；支持 leader 选举和运行多个 operator 副本；支持在 Strimzi 签发的证书中使用 IPv6 地址。

- [SuperEdge 边缘容器管理系统 v0.8.0 发布（CNCF 项目）](https://github.com/superedge/superedge/releases/tag/v0.8.0)  

    该版本主要新特性：将 edgeadm 从SuperEdge 项目中分离出来、tunnel 支持 http_proxy 能力、Lite-apiserver 支持在边缘节点缓存一些关键资源（节点、service 等）和 ExternalName Service 转发。

- [Sylva 云原生基础设施堆栈由 Linux 基金会欧洲分部推出，为电信服务奠定云原生的基础](https://www.prnewswire.com/news-releases/linux-foundation-europe-announces-project-sylva-to-create-open-source-telco-cloud-software-framework-to-complement-open-networking-momentum-301678955.html)

    [Sylva](https://gitlab.com/sylva-projects/sylva) 利用容器网络功能（CNF）和 Kubernetes 等云原生平台来创建电信云技术栈，以减少电信和边缘服务的云基础设施的分散性。
    Sylva 提供的技术栈由 5 个部分组成：网络性能（SRIOV、DPDK、指定 CNI 等）、分布式云（多集群 Kubernetes、裸机自动化）、能源效率、安全性（加固和合规性）以及开放性和标准化 API。

### T

- [TDengine 云原生时序数据库 v3.0 发布](https://github.com/taosdata/TDengine/releases/tag/ver-3.0.0.0)  

    该版本主要新特性：支持 10 亿个设备采集的数据、100 个节点；支持存储与计算分离，引入计算节点，并重构了整个计算引擎；优化了对消息队列、流式计算和缓存的支持，引入事件驱动的流式计算；支持容器和 Kubernetes 部署。

- [Tekton 云原生 CI/CD 框架 v0.42.0 发布](https://github.com/tektoncd/pipeline/releases/tag/v0.42.0)

    该版本主要新特性：支持配置 Webhook 端口号、支持为集群资源设置源值、新增一个和状态治理字段有关的 feature flag、支持记录远程资源的来源、在 reconciler 中添加验证功能。

- [Tekton 云原生 CI/CD 框架 v0.40.0 发布](https://github.com/tektoncd/pipeline/releases/tag/v0.40.0)

    该版本主要新特性：添加任务运行模板、支持在 pipelinerun 中传播 workspace 以简化规范编写、优化 git 远程解析支持、添加集群远程解析器、合并 podtempalte 和 affinity-assistant 的亲和力参数。

- [ThreatMapper 云原生安全观测平台 v1.4.0 发布](https://github.com/deepfence/ThreatMapper/releases/tag/v1.4.0)  

    该版本主要新特性：新功能 ThreatGraph 能够结合网络等运行时环境来确定威胁扫描结果的优先级、支持对云资产进行无代理的云安全态势管理、集成云原生环境恶意程序扫描工具 [YaraHunter](https://github.com/deepfence/YaraHunter)。

- [Trivy 容器漏洞扫描工具 v0.35.0 发布（CNCF 项目）](https://github.com/aquasecurity/trivy/releases/tag/v0.35.0)

    该版本主要新特性：为虚拟机镜像新增扫描器、多架构镜像支持 OS 通配符、支持按 digest 扫描镜像、增加慢速模式以降低 CPU 和内存利用率。

- [Trivy 容器漏洞扫描工具 v0.33.0 发布（CNCF 项目）](https://github.com/aquasecurity/trivy/releases/tag/v0.33.0)

    该版本主要新特性：禁用非 amd64 架构的 containerd 集成测试、重构 k8s 自定义报告、支持 non-packaged 二进制文件、修复 golang x/text 漏洞。

- [Trivy 容器漏洞扫描工具 v0.32.0 发布（CNCF 项目）](https://github.com/aquasecurity/trivy/releases/tag/v0.32.0)

    该版本主要新特性：增加对 SPDX 的扫描、支持 Rust 二进制文件的依赖扫描、增加对  gradle.lockfile 和 conan.lock 文件的支持。

- [Trivy 容器漏洞扫描工具 v0.31.0 发布（CNCF 项目）](https://github.com/aquasecurity/trivy/releases/tag/v0.31.0)

    该版本主要新特性：支持扫描 SBOM 证明、为dockerfile 的 misconf 处理程序添加测试、增加对 Cosign 漏洞证明的支持、允许用户为 token 定义一个已有的 secret、增加两个新漏洞。

- [Trivy 容器漏洞扫描工具 v0.30.0 发布（CNCF 项目）](https://github.com/aquasecurity/trivy/releases/tag/v0.30.0)

    该版本主要新特性：支持扫描许可证、推送 canary 构建镜像到注册表、Trivy k8s 支持扫描 single argument 资源、支持扫描 Cyclonedx 软件物料清单（SBOM）、增加 pnpm 支持。

### V, W, X

- [Vcluster 虚拟 Kubernetes 集群实现方案 v0.13.0 发布](https://github.com/loft-sh/vcluster/releases/tag/v0.13.0)

    该版本主要新特性：增加日志和备份功能、增加具有外部数据存储的 k3s 的高可用性支持、vcluster 调度器开启时自动同步 CSI 资源。

- [Velero 备份容灾工具 v1.10.0 发布（CNCF 项目）](https://github.com/vmware-tanzu/velero/releases/tag/v1.10.0)

    该版本主要新特性：引入统一存储库架构、集成跨平台备份工具 [Kopia](https://github.com/kopia/kopia)、重构文件系统备份、使用 Kubebuilder v3 对控制器进行重构、允许为卷快照位置添加凭证、增强 CSI 快照的稳健性、支持暂停备份计划、重命名部分模块和参数。

- [Virtink：由 SmartX 开源的轻量 Kubernetes 原生虚拟化管理引擎](https://mp.weixin.qq.com/s/LOZ8RhFE_9SZKwcdV90dPw)

    不同于 KubeVirt，[Virtink](https://github.com/smartxworks/virtink) 并不支持遗留硬件设备的模拟以及桌面应用场景能力，而是使用 [Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) 作为底层虚拟化管理器，只支持现代化的云负载，可以在任何虚拟化 CPU 平台的 Kubernetes 中进行安装，以更安全轻量的方式支撑虚拟化负载。

- [Wolfi：Chainguard 发布首个保障软件供应链安全的 Linux 发行版，专为容器和云原生环境设计](https://www.chainguard.dev/unchained/introducing-wolfi-the-first-linux-un-distro)  

    [Wolfi](https://github.com/wolfi-dev) 是一个为云原生设计的精简版 Linux 发行版，但其没有 Linux 内核，而是依靠环境（如容器运行时）来提供内核。主要功能：为所有软件包提供高质量构建时的 SBOM 作为标准；软件包是细粒度和相互独立的，以支持轻量级镜像；使用成熟可靠的 apk 包格式、完全声明性的、可重复的构建系统、支持 glibc 和 musl。

- [Xline 由 DatenLord 开源：实现跨数据中心数据一致性管理](https://mp.weixin.qq.com/s/NqScUOjUA1t4gdNeLEcPwg)

    [Xline](https://github.com/datenlord/Xline) 旨在解决 etcd 无法完全满足跨云跨数据中心场景需求的问题。Xline 是一个分布式的 KV 存储，用来管理少量的关键性数据，并在跨云跨数据中心的场景下仍然保证高性能和数据强一致性。其兼容 etcd 接口，让用户使用和迁移更加流畅。