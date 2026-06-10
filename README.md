# CKS Training Certification Prep Path

## Languages

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Start-Path-whitesmoke?style=for-the-badge)](https://labex.io/learn/cks)

Prepare for the Certified Kubernetes Security Specialist (CKS) exam with a structured, hands-on learning path. This roadmap focuses on practical Kubernetes security across cluster and system hardening, minimizing microservice vulnerabilities, supply chain security, and monitoring, logging, and runtime security, plus performance-based exam tasks and real-world cloud-native scenarios. Guided CKS courses, labs, and mock exam practice will be added over time to help you build skills aligned with CKS objectives.

**Courses**: 3 · **Labs**: 85

## Courses

### 1. [CKS Prep](https://labex.io/courses/cks-prep)

A guided Certified Kubernetes Security Specialist (CKS) preparation course with 45 Kubernetes security labs arranged from security foundations to cluster setup, hardening, workload security, supply chain, audit, and runtime investigation.

[Start Course](https://labex.io/courses/cks-prep) · Labs: 45

#### Security Foundations for Kubernetes

|   Index | Name                                      | Difficulty   | Practice                                                                                         |
|---------|-------------------------------------------|--------------|--------------------------------------------------------------------------------------------------|
|       1 | 🧩  Map Kubernetes Security Boundaries     | Beginner     | [Start Lab](https://labex.io/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|       2 | 🧩  Collect Security Evidence with kubectl | Beginner     | [Start Lab](https://labex.io/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|       3 | 🧩  Review Namespaces and Tenant Isolation | Beginner     | [Start Lab](https://labex.io/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|       4 | 🧩  Inspect RBAC Subjects and Permissions  | Beginner     | [Start Lab](https://labex.io/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|       5 | 🧩  Inspect ServiceAccount Token Behavior  | Beginner     | [Start Lab](https://labex.io/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|       6 | 🧩  Apply Pod Security Standards           | Beginner     | [Start Lab](https://labex.io/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### Cluster Setup Security

|   Index | Name                                             | Difficulty   | Practice                                                                                                |
|---------|--------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Restrict Namespace Traffic with NetworkPolicy | Beginner     | [Start Lab](https://labex.io/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|       2 | 🧩  Allow DNS Through Default-Deny Egress         | Beginner     | [Start Lab](https://labex.io/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|       3 | 🧩  Publish Ingress with TLS                      | Beginner     | [Start Lab](https://labex.io/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|       4 | 🧩  Deny Workload Access to Node Metadata         | Beginner     | [Start Lab](https://labex.io/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|       5 | 🧩  Verify Kubernetes Binaries                    | Beginner     | [Start Lab](https://labex.io/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|       6 | 🧩  Review CIS Findings with kube-bench           | Beginner     | [Start Lab](https://labex.io/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|       7 | 🧩  Check Admission and Pod Security Readiness    | Beginner     | [Start Lab](https://labex.io/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### Cluster Hardening

|   Index | Name                                           | Difficulty   | Practice                                                                                              |
|---------|------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Minimize a Role's Permissions               | Beginner     | [Start Lab](https://labex.io/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|       2 | 🧩  Reduce an Overprivileged ClusterRoleBinding | Beginner     | [Start Lab](https://labex.io/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|       3 | 🧩  Disable Default ServiceAccount Token Mounts | Beginner     | [Start Lab](https://labex.io/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|       4 | 🧩  Scope a Namespace Operator Role             | Beginner     | [Start Lab](https://labex.io/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|       5 | 🧩  Block API Server Proxy Escalation           | Beginner     | [Start Lab](https://labex.io/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|       6 | 🧩  Contain a Leaked ServiceAccount Token       | Beginner     | [Start Lab](https://labex.io/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|       7 | 🧩  Audit Access to Sensitive Resources         | Beginner     | [Start Lab](https://labex.io/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### System and Node Hardening

|   Index | Name                                                 | Difficulty   | Practice                                                                                                    |
|---------|------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Inspect Host Attack Surface Safely                | Beginner     | [Start Lab](https://labex.io/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|       2 | 🧩  Disable a Host Debug Service                      | Beginner     | [Start Lab](https://labex.io/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|       3 | 🧩  Review kubelet Exposure                           | Beginner     | [Start Lab](https://labex.io/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|       4 | 🧩  Review AppArmor Profile Enforcement on a Workload | Beginner     | [Start Lab](https://labex.io/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|       5 | 🧩  Install a Local seccomp Profile                   | Beginner     | [Start Lab](https://labex.io/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|       6 | 🧩  Remove HostPath Access from a Workload            | Beginner     | [Start Lab](https://labex.io/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### Workload and Microservice Security

|   Index | Name                                        | Difficulty   | Practice                                                                                           |
|---------|---------------------------------------------|--------------|----------------------------------------------------------------------------------------------------|
|       1 | 🧩  Harden a Pod Security Context            | Beginner     | [Start Lab](https://labex.io/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|       2 | 🧩  Drop Linux Capabilities                  | Beginner     | [Start Lab](https://labex.io/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|       3 | 🧩  Run Containers as Non-Root               | Beginner     | [Start Lab](https://labex.io/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|       4 | 🧩  Protect Secrets with Projected Files     | Beginner     | [Start Lab](https://labex.io/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|       5 | 🧩  Rotate and Constrain Application Secrets | Beginner     | [Start Lab](https://labex.io/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|       6 | 🧩  Isolate a Risky Sidecar Boundary         | Beginner     | [Start Lab](https://labex.io/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|       7 | 🧩  Enforce Immutable Runtime Containers     | Beginner     | [Start Lab](https://labex.io/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|       8 | 🧩  Quarantine a Suspicious Workload         | Beginner     | [Start Lab](https://labex.io/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### Supply Chain Security

|   Index | Name                                        | Difficulty   | Practice                                                                                           |
|---------|---------------------------------------------|--------------|----------------------------------------------------------------------------------------------------|
|       1 | 🧩  Build a Minimal Approved Image           | Beginner     | [Start Lab](https://labex.io/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|       2 | 🧩  Scan Workload Manifests with kube-linter | Beginner     | [Start Lab](https://labex.io/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|       3 | 🧩  Scan Helm Output with kube-linter        | Beginner     | [Start Lab](https://labex.io/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|       4 | 🧩  Verify SBOM and Checksum Evidence        | Beginner     | [Start Lab](https://labex.io/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|       5 | 🧩  Enforce Trusted Image Registries         | Beginner     | [Start Lab](https://labex.io/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|       6 | 🧩  Remove Build Secrets from an Image       | Beginner     | [Start Lab](https://labex.io/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### Monitoring, Audit, and Runtime Security

|   Index | Name                                     | Difficulty   | Practice                                                                                        |
|---------|------------------------------------------|--------------|-------------------------------------------------------------------------------------------------|
|       1 | 🧩  Review Audit Events for Secret Access | Beginner     | [Start Lab](https://labex.io/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|       2 | 🧩  Investigate Unauthorized API Activity | Beginner     | [Start Lab](https://labex.io/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|       3 | 🧩  Detect Suspicious Runtime Processes   | Beginner     | [Start Lab](https://labex.io/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|       4 | 🧩  Detect Runtime File Drift             | Beginner     | [Start Lab](https://labex.io/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|       5 | 🧩  Restore Policy from Audit Evidence    | Beginner     | [Start Lab](https://labex.io/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

### 2. [CKS Practice Exam 01](https://labex.io/courses/cks-practice-exam-01)

A hands-on CKS practice exam with 20 independent Kubernetes security challenges covering cluster setup, cluster hardening, system hardening, microservice vulnerability reduction, supply chain security, and runtime security.

[Start Course](https://labex.io/courses/cks-practice-exam-01) · Labs: 20

#### Cluster Setup

|   Index | Name                                             | Difficulty   | Practice                                                                                                                  |
|---------|--------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Restrict Namespace Traffic with NetworkPolicy | Beginner     | [Start Challenge](https://labex.io/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|       2 | 🎯  Publish an Admin Console with TLS Ingress     | Beginner     | [Start Challenge](https://labex.io/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|       3 | 🎯  Verify Kubernetes Binaries Before Deployment  | Beginner     | [Start Challenge](https://labex.io/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### Cluster Hardening

|   Index | Name                                           | Difficulty   | Practice                                                                                                                |
|---------|------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Reduce an Overprivileged ClusterRoleBinding | Beginner     | [Start Challenge](https://labex.io/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|       2 | 🎯  Disable Default ServiceAccount Token Mounts | Beginner     | [Start Challenge](https://labex.io/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|       3 | 🎯  Limit Incident Reader API Access            | Beginner     | [Start Challenge](https://labex.io/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### System Hardening

|   Index | Name                                         | Difficulty   | Practice                                                                                                              |
|---------|----------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Enforce an AppArmor Profile on a Workload | Beginner     | [Start Challenge](https://labex.io/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|       2 | 🎯  Install a Local Seccomp Profile           | Beginner     | [Start Challenge](https://labex.io/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### Minimize Microservice Vulnerabilities

|   Index | Name                                    | Difficulty   | Practice                                                                                                         |
|---------|-----------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Enforce Restricted Pod Security      | Beginner     | [Start Challenge](https://labex.io/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|       2 | 🎯  Protect Secrets with Projected Files | Beginner     | [Start Challenge](https://labex.io/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|       3 | 🎯  Harden a Runtime Security Context    | Beginner     | [Start Challenge](https://labex.io/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|       4 | 🎯  Isolate a Risky Sidecar Boundary     | Beginner     | [Start Challenge](https://labex.io/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### Supply Chain Security

|   Index | Name                                       | Difficulty   | Practice                                                                                                            |
|---------|--------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Build a Minimal Approved Image          | Beginner     | [Start Challenge](https://labex.io/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|       2 | 🎯  Verify SBOM and Checksum Evidence       | Beginner     | [Start Challenge](https://labex.io/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|       3 | 🎯  Scan Workload Manifests with KubeLinter | Beginner     | [Start Challenge](https://labex.io/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|       4 | 🎯  Pin Workloads to Approved Image Digests | Beginner     | [Start Challenge](https://labex.io/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### Monitoring, Logging and Runtime Security

|   Index | Name                                     | Difficulty   | Practice                                                                                                          |
|---------|------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Review Audit Events for Secret Access | Beginner     | [Start Challenge](https://labex.io/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|       2 | 🎯  Detect a Suspicious Runtime Process   | Beginner     | [Start Challenge](https://labex.io/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|       3 | 🎯  Enforce Immutable Runtime Containers  | Beginner     | [Start Challenge](https://labex.io/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|       4 | 🎯  Investigate Unauthorized API Activity | Beginner     | [Start Challenge](https://labex.io/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 3. [CKS Practice Exam 02](https://labex.io/courses/cks-practice-exam-02)

A second independent CKS-style practice exam with 20 Kubernetes security challenges covering the public CKS domains through different operational security scenarios.

[Start Course](https://labex.io/courses/cks-practice-exam-02) · Labs: 20

#### Cluster Setup

|   Index | Name                                        | Difficulty   | Practice                                                                                                             |
|---------|---------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Deny Workload Access to Node Metadata    | Beginner     | [Start Challenge](https://labex.io/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|       2 | 🎯  Review CIS Findings for Kubelet Exposure | Beginner     | [Start Challenge](https://labex.io/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|       3 | 🎯  Reissue TLS for a Split Ingress Route    | Beginner     | [Start Challenge](https://labex.io/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### Cluster Hardening

|   Index | Name                                     | Difficulty   | Practice                                                                                                          |
|---------|------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Scope a Namespace Operator Role       | Beginner     | [Start Challenge](https://labex.io/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|       2 | 🎯  Contain a Leaked ServiceAccount Token | Beginner     | [Start Challenge](https://labex.io/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|       3 | 🎯  Block API Server Proxy Escalation     | Beginner     | [Start Challenge](https://labex.io/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### System Hardening

|   Index | Name                                       | Difficulty   | Practice                                                                                                            |
|---------|--------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Disable a Host Debug Service            | Beginner     | [Start Challenge](https://labex.io/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|       2 | 🎯  Restrict Host Log Collector Permissions | Beginner     | [Start Challenge](https://labex.io/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### Minimize Microservice Vulnerabilities

|   Index | Name                                         | Difficulty   | Practice                                                                                                              |
|---------|----------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Apply Tenant Pod Security Boundaries      | Beginner     | [Start Challenge](https://labex.io/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|       2 | 🎯  Rotate and Constrain Application Secrets  | Beginner     | [Start Challenge](https://labex.io/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|       3 | 🎯  Isolate Tenant Egress with DNS Exceptions | Beginner     | [Start Challenge](https://labex.io/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|       4 | 🎯  Remove HostPath Cache from a Web Pod      | Beginner     | [Start Challenge](https://labex.io/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### Supply Chain Security

|   Index | Name                                  | Difficulty   | Practice                                                                                                       |
|---------|---------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Enforce Trusted Image Registries   | Beginner     | [Start Challenge](https://labex.io/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|       2 | 🎯  Validate a Signed Release Manifest | Beginner     | [Start Challenge](https://labex.io/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|       3 | 🎯  Remove Build Secrets from an Image | Beginner     | [Start Challenge](https://labex.io/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|       4 | 🎯  Scan Helm Output with KubeLinter   | Beginner     | [Start Challenge](https://labex.io/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### Monitoring, Logging and Runtime Security

|   Index | Name                                  | Difficulty   | Practice                                                                                                       |
|---------|---------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Restore Policy from Audit Evidence | Beginner     | [Start Challenge](https://labex.io/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|       2 | 🎯  Quarantine a Beaconing Workload    | Beginner     | [Start Challenge](https://labex.io/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|       3 | 🎯  Detect Runtime File Drift          | Beginner     | [Start Challenge](https://labex.io/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|       4 | 🎯  Contain a Compromised Job Token    | Beginner     | [Start Challenge](https://labex.io/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## About LabEx

[LabEx](https://labex.io) is an interactive, hands-on learning platform dedicated to coding and technology. It combines labs, AI assistance, and virtual machines to provide a no-video, practical learning experience. With a strict 'Learn by Doing' approach, interactive online environments in the browser with automated step-by-step checks, structured content organization through the [Skill Tree](https://labex.io/learn) learning system, and a growing resource of 30 Skill Trees and over 6,000 Labs, [LabEx](https://labex.io) offers comprehensive practical education. The platform includes Labby, an AI learning assistant built on latest AI models, providing a conversational learning experience.

