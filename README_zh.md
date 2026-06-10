# CKS 培训 Certification Prep Path

## 支持语言

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/zh/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/开始路径-whitesmoke?style=for-the-badge)](https://labex.io/zh/learn/cks)

通过结构化的动手学习路径备考 Certified Kubernetes Security Specialist（CKS）考试。本路线图侧重 Kubernetes 上的集群加固、系统加固、微服务漏洞最小化、供应链安全，以及监控、日志与运行时安全，以及贴近 CKS 风格的性能型考试任务与真实场景。后续将逐步加入 CKS 课程、实验环境与模拟考试练习，帮助你建立与 CKS 目标一致的能力。

**课程**: 3 · **实验**: 85

## 课程

### 1. [CKS 备考指南](https://labex.io/zh/courses/cks-prep)

这是一门面向初学者的 CKS 备考课程，包含 45 个引导式 Kubernetes 安全实验。课程内容由浅入深，涵盖安全基础、集群搭建、加固、工作负载安全、供应链安全、审计及运行时调查等核心领域。

[开始课程](https://labex.io/zh/courses/cks-prep) · 实验: 45

#### Kubernetes 安全基础

|   序号 | 名称                            | 难度   | 练习                                                                                             |
|------|-------------------------------|------|------------------------------------------------------------------------------------------------|
|    1 | 🧩  映射 Kubernetes 安全边界         | 初级   | [开始实验](https://labex.io/zh/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|    2 | 🧩  使用 kubectl 收集安全证据          | 初级   | [开始实验](https://labex.io/zh/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|    3 | 🧩  回顾命名空间与租户隔离                | 初级   | [开始实验](https://labex.io/zh/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|    4 | 🧩  检查 RBAC 主体与权限              | 初级   | [开始实验](https://labex.io/zh/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|    5 | 🧩  检查 ServiceAccount Token 行为 | 初级   | [开始实验](https://labex.io/zh/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|    6 | 🧩  应用 Pod 安全标准                | 初级   | [开始实验](https://labex.io/zh/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### 集群配置安全

|   序号 | 名称                             | 难度   | 练习                                                                                                    |
|------|--------------------------------|------|-------------------------------------------------------------------------------------------------------|
|    1 | 🧩  使用 NetworkPolicy 限制命名空间流量   | 初级   | [开始实验](https://labex.io/zh/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|    2 | 🧩  允许 DNS 通过默认拒绝的出站流量策略        | 初级   | [开始实验](https://labex.io/zh/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|    3 | 🧩  使用 TLS 发布 Ingress           | 初级   | [开始实验](https://labex.io/zh/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|    4 | 🧩  拒绝工作负载访问节点元数据               | 初级   | [开始实验](https://labex.io/zh/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|    5 | 🧩  验证 Kubernetes 二进制文件         | 初级   | [开始实验](https://labex.io/zh/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|    6 | 🧩  使用 kube-bench 审查 CIS 安全基准发现 | 初级   | [开始实验](https://labex.io/zh/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|    7 | 🧩  检查准入与 Pod 安全就绪状态            | 初级   | [开始实验](https://labex.io/zh/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### 集群加固

|   序号 | 名称                            | 难度   | 练习                                                                                                  |
|------|-------------------------------|------|-----------------------------------------------------------------------------------------------------|
|    1 | 🧩  最小化角色权限                    | 初级   | [开始实验](https://labex.io/zh/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|    2 | 🧩  缩减权限过大的 ClusterRoleBinding | 初级   | [开始实验](https://labex.io/zh/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|    3 | 🧩  禁用默认 ServiceAccount 令牌挂载   | 初级   | [开始实验](https://labex.io/zh/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|    4 | 🧩  限定命名空间操作员的角色权限             | 初级   | [开始实验](https://labex.io/zh/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|    5 | 🧩  阻止 API Server 代理提权         | 初级   | [开始实验](https://labex.io/zh/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|    6 | 🧩  包含泄露的 ServiceAccount 令牌    | 初级   | [开始实验](https://labex.io/zh/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|    7 | 🧩  审计敏感资源访问权限                 | 初级   | [开始实验](https://labex.io/zh/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### 系统与节点加固

|   序号 | 名称                             | 难度   | 练习                                                                                                        |
|------|--------------------------------|------|-----------------------------------------------------------------------------------------------------------|
|    1 | 🧩  安全检查主机攻击面                   | 初级   | [开始实验](https://labex.io/zh/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|    2 | 🧩  禁用主机调试服务                    | 初级   | [开始实验](https://labex.io/zh/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|    3 | 🧩  审查 Kubelet 暴露情况             | 初级   | [开始实验](https://labex.io/zh/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|    4 | 🧩  审查工作负载的 AppArmor 配置文件强制执行情况 | 初级   | [开始实验](https://labex.io/zh/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|    5 | 🧩  安装本地 seccomp 配置文件           | 初级   | [开始实验](https://labex.io/zh/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|    6 | 🧩  移除工作负载的 HostPath 访问权限       | 初级   | [开始实验](https://labex.io/zh/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### 工作负载与微服务安全

|   序号 | 名称                       | 难度   | 练习                                                                                               |
|------|--------------------------|------|--------------------------------------------------------------------------------------------------|
|    1 | 🧩  加固 Pod 安全上下文          | 初级   | [开始实验](https://labex.io/zh/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|    2 | 🧩  移除 Linux Capabilities | 初级   | [开始实验](https://labex.io/zh/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|    3 | 🧩  以非 Root 用户身份运行容器      | 初级   | [开始实验](https://labex.io/zh/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|    4 | 🧩  使用投射文件保护密钥            | 初级   | [开始实验](https://labex.io/zh/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|    5 | 🧩  旋转并限制应用密钥             | 初级   | [开始实验](https://labex.io/zh/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|    6 | 🧩  隔离高风险的 Sidecar 边界     | 初级   | [开始实验](https://labex.io/zh/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|    7 | 🧩  强制执行不可变运行时容器          | 初级   | [开始实验](https://labex.io/zh/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|    8 | 🧩  隔离可疑工作负载              | 初级   | [开始实验](https://labex.io/zh/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### 供应链安全

|   序号 | 名称                           | 难度   | 练习                                                                                               |
|------|------------------------------|------|--------------------------------------------------------------------------------------------------|
|    1 | 🧩  构建最小化合规镜像                 | 初级   | [开始实验](https://labex.io/zh/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|    2 | 🧩  使用 kube-linter 扫描工作负载清单   | 初级   | [开始实验](https://labex.io/zh/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|    3 | 🧩  使用 kube-linter 扫描 Helm 输出 | 初级   | [开始实验](https://labex.io/zh/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|    4 | 🧩  验证 SBOM 和校验和证据            | 初级   | [开始实验](https://labex.io/zh/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|    5 | 🧩  强制执行受信任的镜像仓库              | 初级   | [开始实验](https://labex.io/zh/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|    6 | 🧩  从镜像中移除构建密钥                | 初级   | [开始实验](https://labex.io/zh/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### 监控、审计与运行时安全

|   序号 | 名称                   | 难度   | 练习                                                                                            |
|------|----------------------|------|-----------------------------------------------------------------------------------------------|
|    1 | 🧩  审查 Secret 访问的审计事件 | 初级   | [开始实验](https://labex.io/zh/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|    2 | 🧩  调查未经授权的 API 活动    | 初级   | [开始实验](https://labex.io/zh/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|    3 | 🧩  检测可疑运行时进程         | 初级   | [开始实验](https://labex.io/zh/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|    4 | 🧩  检测运行时文件漂移         | 初级   | [开始实验](https://labex.io/zh/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|    5 | 🧩  从审计证据中恢复策略        | 初级   | [开始实验](https://labex.io/zh/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

### 2. [CKS 模拟考试 01](https://labex.io/zh/courses/cks-practice-exam-01)

这是一套实战型 CKS 模拟考试，包含 20 个独立的 Kubernetes 安全挑战，涵盖集群设置、集群加固、系统加固、微服务漏洞缓解、供应链安全以及运行时安全等核心领域。

[开始课程](https://labex.io/zh/courses/cks-practice-exam-01) · 实验: 20

#### 集群搭建

|   序号 | 名称                           | 难度   | 练习                                                                                                                |
|------|------------------------------|------|-------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用 NetworkPolicy 限制命名空间流量 | 初级   | [开始挑战](https://labex.io/zh/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|    2 | 🎯  使用 TLS Ingress 发布管理控制台    | 初级   | [开始挑战](https://labex.io/zh/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|    3 | 🎯  部署前验证 Kubernetes 二进制文件    | 初级   | [开始挑战](https://labex.io/zh/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### 集群加固

|   序号 | 名称                             | 难度   | 练习                                                                                                              |
|------|--------------------------------|------|-----------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  缩减权限过大的 ClusterRoleBinding  | 初级   | [开始挑战](https://labex.io/zh/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|    2 | 🎯  禁用默认 ServiceAccount 令牌挂载    | 初级   | [开始挑战](https://labex.io/zh/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|    3 | 🎯  限制 Incident Reader API 访问权限 | 初级   | [开始挑战](https://labex.io/zh/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### 系统加固

|   序号 | 名称                          | 难度   | 练习                                                                                                            |
|------|-----------------------------|------|---------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  在工作负载上强制执行 AppArmor 配置文件 | 初级   | [开始挑战](https://labex.io/zh/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|    2 | 🎯  安装本地 Seccomp 配置文件        | 初级   | [开始挑战](https://labex.io/zh/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### 微服务漏洞最小化

|   序号 | 名称                  | 难度   | 练习                                                                                                       |
|------|---------------------|------|----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  强制执行受限 Pod 安全策略  | 初级   | [开始挑战](https://labex.io/zh/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|    2 | 🎯  使用投影卷保护 Secret   | 初级   | [开始挑战](https://labex.io/zh/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|    3 | 🎯  加固运行时安全上下文       | 初级   | [开始挑战](https://labex.io/zh/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|    4 | 🎯  隔离高风险 Sidecar 边界 | 初级   | [开始挑战](https://labex.io/zh/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### 供应链安全

|   序号 | 名称                        | 难度   | 练习                                                                                                          |
|------|---------------------------|------|-------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  构建最小化合规镜像              | 初级   | [开始挑战](https://labex.io/zh/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|    2 | 🎯  验证 SBOM 和校验和证据         | 初级   | [开始挑战](https://labex.io/zh/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|    3 | 🎯  使用 KubeLinter 扫描工作负载清单 | 初级   | [开始挑战](https://labex.io/zh/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|    4 | 🎯  将工作负载固定为已批准的镜像摘要       | 初级   | [开始挑战](https://labex.io/zh/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### 监控、日志与运行时安全

|   序号 | 名称                   | 难度   | 练习                                                                                                        |
|------|----------------------|------|-----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  审查 Secret 访问的审计事件 | 初级   | [开始挑战](https://labex.io/zh/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|    2 | 🎯  检测可疑的运行时进程        | 初级   | [开始挑战](https://labex.io/zh/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|    3 | 🎯  强制执行不可变运行时容器      | 初级   | [开始挑战](https://labex.io/zh/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|    4 | 🎯  调查未经授权的 API 活动    | 初级   | [开始挑战](https://labex.io/zh/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 3. [CKS 模拟考试 02](https://labex.io/zh/courses/cks-practice-exam-02)

第二套独立的 CKS 风格模拟考试，包含 20 个 Kubernetes 安全挑战，涵盖了 CKS 公开考试大纲中涉及的各类操作安全场景。

[开始课程](https://labex.io/zh/courses/cks-practice-exam-02) · 实验: 20

#### 集群搭建

|   序号 | 名称                         | 难度   | 练习                                                                                                           |
|------|----------------------------|------|--------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  拒绝工作负载访问节点元数据           | 初级   | [开始挑战](https://labex.io/zh/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|    2 | 🎯  审查 Kubelet 暴露的 CIS 调查结果 | 初级   | [开始挑战](https://labex.io/zh/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|    3 | 🎯  为拆分式 Ingress 路由重新签发 TLS | 初级   | [开始挑战](https://labex.io/zh/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### 集群加固

|   序号 | 名称                         | 难度   | 练习                                                                                                        |
|------|----------------------------|------|-----------------------------------------------------------------------------------------------------------|
|    1 | 🎯  限定命名空间操作员的角色权限          | 初级   | [开始挑战](https://labex.io/zh/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|    2 | 🎯  包含泄露的 ServiceAccount 令牌 | 初级   | [开始挑战](https://labex.io/zh/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|    3 | 🎯  拦截 API Server 代理提权      | 初级   | [开始挑战](https://labex.io/zh/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### 系统加固

|   序号 | 名称             | 难度   | 练习                                                                                                          |
|------|----------------|------|-------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  禁用主机调试服务    | 初级   | [开始挑战](https://labex.io/zh/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|    2 | 🎯  限制主机日志收集器权限 | 初级   | [开始挑战](https://labex.io/zh/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### 微服务漏洞最小化

|   序号 | 名称                           | 难度   | 练习                                                                                                            |
|------|------------------------------|------|---------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  应用租户 Pod 安全边界             | 初级   | [开始挑战](https://labex.io/zh/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|    2 | 🎯  轮换并限制应用密钥                 | 初级   | [开始挑战](https://labex.io/zh/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|    3 | 🎯  使用 DNS 例外隔离租户出口流量         | 初级   | [开始挑战](https://labex.io/zh/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|    4 | 🎯  从 Web Pod 中移除 HostPath 缓存 | 初级   | [开始挑战](https://labex.io/zh/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### 供应链安全

|   序号 | 名称                          | 难度   | 练习                                                                                                     |
|------|-----------------------------|------|--------------------------------------------------------------------------------------------------------|
|    1 | 🎯  强制执行受信任的镜像仓库             | 初级   | [开始挑战](https://labex.io/zh/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|    2 | 🎯  验证已签名的发布清单               | 初级   | [开始挑战](https://labex.io/zh/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|    3 | 🎯  从镜像中移除构建机密               | 初级   | [开始挑战](https://labex.io/zh/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|    4 | 🎯  使用 KubeLinter 扫描 Helm 输出 | 初级   | [开始挑战](https://labex.io/zh/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### 监控、日志与运行时安全

|   序号 | 名称            | 难度   | 练习                                                                                                     |
|------|---------------|------|--------------------------------------------------------------------------------------------------------|
|    1 | 🎯  从审计证据中恢复策略 | 初级   | [开始挑战](https://labex.io/zh/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|    2 | 🎯  隔离信标工作负载   | 初级   | [开始挑战](https://labex.io/zh/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|    3 | 🎯  检测运行时文件漂移  | 初级   | [开始挑战](https://labex.io/zh/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|    4 | 🎯  控制受损的作业令牌  | 初级   | [开始挑战](https://labex.io/zh/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## 关于 LabEx

[LabEx](https://labex.io) 是一个专注于编程和技术的交互式动手学习平台。它结合了实验室、AI 辅助和虚拟机，提供无视频的实践学习体验。采用严格的'边学边做'方法，浏览器内的交互式在线环境具有自动化的逐步检查，基于技能树的结构化内容组织系统，以及不断增长的学习资源（包含 30 个技能树和超过 6,000 个实验），[LabEx](https://labex.io) 提供全面的实践教育。该平台包含基于最新 AI 模型构建的学习助手 Labby，提供对话式学习体验。

