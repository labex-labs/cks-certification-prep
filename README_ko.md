# CKS 교육 Certification Prep Path

## 언어

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/ko/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/경로-시작-whitesmoke?style=for-the-badge)](https://labex.io/ko/learn/cks)

Certified Kubernetes Security Specialist(CKS) 시험을 위해 구조화된 실습 중심 학습 경로로 준비하세요. Kubernetes 에서 클러스터 강화, 시스템 강화, 마이크로서비스 취약점 최소화, 공급망 보안, 모니터링·로깅·런타임 보안, CKS 형태의 성능 기반 작업, 현실 시나리오에 초점을 맞춥니다. CKS 과정, 랩, 모의고사 연습이 단계적으로 추가됩니다.

**코스**: 3 · **실습**: 85

## 코스

### 1. [CKS 준비 과정](https://labex.io/ko/courses/cks-prep)

보안 기초부터 클러스터 설정, 강화, 워크로드 보안, 공급망, 감사, 런타임 조사까지 총 45 개의 가이드형 Kubernetes 보안 실습으로 구성된 초보자 맞춤형 CKS 준비 과정입니다.

[코스 시작](https://labex.io/ko/courses/cks-prep) · 실습: 45

#### Kubernetes 보안 기초

|   인덱스 | 이름                         | 난이도   | 연습                                                                                              |
|-------|----------------------------|-------|-------------------------------------------------------------------------------------------------|
|     1 | 🧩  Kubernetes 보안 경계 매핑     | 초급    | [실습 시작](https://labex.io/ko/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|     2 | 🧩  kubectl 을 이용한 보안 증거 수집  | 초급    | [실습 시작](https://labex.io/ko/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|     3 | 🧩  네임스페이스 및 테넌트 격리 검토      | 초급    | [실습 시작](https://labex.io/ko/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|     4 | 🧩  RBAC 주체 및 권한 검사         | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|     5 | 🧩  ServiceAccount 토큰 동작 검사 | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|     6 | 🧩  Pod 보안 표준 적용하기          | 초급    | [실습 시작](https://labex.io/ko/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### 클러스터 설정 보안

|   인덱스 | 이름                                         | 난이도   | 연습                                                                                                     |
|-------|--------------------------------------------|-------|--------------------------------------------------------------------------------------------------------|
|     1 | 🧩  NetworkPolicy 를 사용한 네임스페이스 트래픽 제한       | 초급    | [실습 시작](https://labex.io/ko/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|     2 | 🧩  기본 거부 (Default-Deny) 이그레스 환경에서 DNS 허용하기 | 초급    | [실습 시작](https://labex.io/ko/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|     3 | 🧩  TLS 를 사용한 Ingress 게시                    | 초급    | [실습 시작](https://labex.io/ko/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|     4 | 🧩  워크로드의 노드 메타데이터 접근 차단                    | 초급    | [실습 시작](https://labex.io/ko/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|     5 | 🧩  Kubernetes 바이너리 검증                      | 초급    | [실습 시작](https://labex.io/ko/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|     6 | 🧩  kube-bench 를 이용한 CIS 결과 검토              | 초급    | [실습 시작](https://labex.io/ko/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|     7 | 🧩  Admission 및 Pod 보안 준비 상태 확인             | 초급    | [실습 시작](https://labex.io/ko/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### 클러스터 강화

|   인덱스 | 이름                                     | 난이도   | 연습                                                                                                   |
|-------|----------------------------------------|-------|------------------------------------------------------------------------------------------------------|
|     1 | 🧩  역할 (Role) 권한 최소화                    | 초급    | [실습 시작](https://labex.io/ko/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|     2 | 🧩  과도한 권한이 부여된 ClusterRoleBinding 축소하기 | 초급    | [실습 시작](https://labex.io/ko/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|     3 | 🧩  기본 ServiceAccount 토큰 마운트 비활성화       | 초급    | [실습 시작](https://labex.io/ko/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|     4 | 🧩  네임스페이스 오퍼레이터 역할 범위 지정               | 초급    | [실습 시작](https://labex.io/ko/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|     5 | 🧩  API 서버 프록시 권한 상승 차단                 | 초급    | [실습 시작](https://labex.io/ko/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|     6 | 🧩  유출된 ServiceAccount 토큰 격리            | 초급    | [실습 시작](https://labex.io/ko/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|     7 | 🧩  민감한 리소스에 대한 액세스 감사                  | 초급    | [실습 시작](https://labex.io/ko/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### 시스템 및 노드 강화

|   인덱스 | 이름                             | 난이도   | 연습                                                                                                         |
|-------|--------------------------------|-------|------------------------------------------------------------------------------------------------------------|
|     1 | 🧩  호스트 공격 표면 안전하게 검사하기         | 초급    | [실습 시작](https://labex.io/ko/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|     2 | 🧩  호스트 디버그 서비스 비활성화            | 초급    | [실습 시작](https://labex.io/ko/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|     3 | 🧩  kubelet 노출 검토               | 초급    | [실습 시작](https://labex.io/ko/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|     4 | 🧩  워크로드에 대한 AppArmor 프로필 적용 검토 | 초급    | [실습 시작](https://labex.io/ko/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|     5 | 🧩  로컬 seccomp 프로필 설치           | 초급    | [실습 시작](https://labex.io/ko/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|     6 | 🧩  워크로드에서 HostPath 액세스 제거      | 초급    | [실습 시작](https://labex.io/ko/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### 워크로드 및 마이크로서비스 보안

|   인덱스 | 이름                                         | 난이도   | 연습                                                                                                |
|-------|--------------------------------------------|-------|---------------------------------------------------------------------------------------------------|
|     1 | 🧩  Pod 보안 컨텍스트 강화                          | 초급    | [실습 시작](https://labex.io/ko/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|     2 | 🧩  Linux Capabilities 제한하기                 | 초급    | [실습 시작](https://labex.io/ko/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|     3 | 🧩  컨테이너를 Non-Root 로 실행하기                   | 초급    | [실습 시작](https://labex.io/ko/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|     4 | 🧩  프로젝티드 파일 (Projected Files) 을 사용한 시크릿 보호 | 초급    | [실습 시작](https://labex.io/ko/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|     5 | 🧩  애플리케이션 시크릿 (Secret) 교체 및 권한 제한          | 초급    | [실습 시작](https://labex.io/ko/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|     6 | 🧩  위험한 사이드카 경계 격리하기                        | 초급    | [실습 시작](https://labex.io/ko/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|     7 | 🧩  불변 런타임 컨테이너 강제 적용                       | 초급    | [실습 시작](https://labex.io/ko/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|     8 | 🧩  의심스러운 워크로드 격리                           | 초급    | [실습 시작](https://labex.io/ko/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### 공급망 보안

|   인덱스 | 이름                                 | 난이도   | 연습                                                                                                |
|-------|------------------------------------|-------|---------------------------------------------------------------------------------------------------|
|     1 | 🧩  최소한의 승인된 이미지 빌드                 | 초급    | [실습 시작](https://labex.io/ko/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|     2 | 🧩  kube-linter 를 사용한 워크로드 매니페스트 스캔 | 초급    | [실습 시작](https://labex.io/ko/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|     3 | 🧩  kube-linter 를 사용하여 Helm 출력 스캔하기 | 초급    | [실습 시작](https://labex.io/ko/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|     4 | 🧩  SBOM 및 체크섬 증거 검증                | 초급    | [실습 시작](https://labex.io/ko/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|     5 | 🧩  신뢰할 수 있는 이미지 레지스트리 강제 적용        | 초급    | [실습 시작](https://labex.io/ko/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|     6 | 🧩  이미지에서 빌드 시크릿 제거하기               | 초급    | [실습 시작](https://labex.io/ko/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### 모니터링, 감사 및 런타임 보안

|   인덱스 | 이름                         | 난이도   | 연습                                                                                             |
|-------|----------------------------|-------|------------------------------------------------------------------------------------------------|
|     1 | 🧩  Secret 접근에 대한 감사 이벤트 검토 | 초급    | [실습 시작](https://labex.io/ko/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|     2 | 🧩  비인가 API 활동 조사           | 초급    | [실습 시작](https://labex.io/ko/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|     3 | 🧩  의심스러운 런타임 프로세스 탐지       | 초급    | [실습 시작](https://labex.io/ko/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|     4 | 🧩  런타임 파일 드리프트 탐지          | 초급    | [실습 시작](https://labex.io/ko/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|     5 | 🧩  감사 증적을 통한 정책 복구         | 초급    | [실습 시작](https://labex.io/ko/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

### 2. [CKS 실전 모의고사 01](https://labex.io/ko/courses/cks-practice-exam-01)

클러스터 설정, 클러스터 강화, 시스템 강화, 마이크로서비스 취약점 감소, 공급망 보안 및 런타임 보안을 아우르는 20 개의 독립적인 Kubernetes 보안 챌린지로 구성된 실습형 CKS 모의고사입니다.

[코스 시작](https://labex.io/ko/courses/cks-practice-exam-01) · 실습: 20

#### 클러스터 설정

|   인덱스 | 이름                                    | 난이도   | 연습                                                                                                                 |
|-------|---------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  NetworkPolicy 를 사용하여 네임스페이스 트래픽 제한 | 초급    | [도전 시작](https://labex.io/ko/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|     2 | 🎯  TLS Ingress 를 통한 관리자 콘솔 게시         | 초급    | [도전 시작](https://labex.io/ko/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|     3 | 🎯  배포 전 Kubernetes 바이너리 검증            | 초급    | [도전 시작](https://labex.io/ko/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### 클러스터 강화

|   인덱스 | 이름                                   | 난이도   | 연습                                                                                                               |
|-------|--------------------------------------|-------|------------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  과도한 권한이 부여된 ClusterRoleBinding 축소 | 초급    | [도전 시작](https://labex.io/ko/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|     2 | 🎯  기본 ServiceAccount 토큰 마운트 비활성화     | 초급    | [도전 시작](https://labex.io/ko/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|     3 | 🎯  Incident Reader API 액세스 제한        | 초급    | [도전 시작](https://labex.io/ko/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### 시스템 강화

|   인덱스 | 이름                         | 난이도   | 연습                                                                                                             |
|-------|----------------------------|-------|----------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  워크로드에 AppArmor 프로필 적용하기 | 초급    | [도전 시작](https://labex.io/ko/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|     2 | 🎯  로컬 Seccomp 프로필 설치       | 초급    | [도전 시작](https://labex.io/ko/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### 마이크로서비스 취약점 최소화

|   인덱스 | 이름                                        | 난이도   | 연습                                                                                                        |
|-------|-------------------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
|     1 | 🎯  제한된 파드 보안 (Restricted Pod Security) 적용 | 초급    | [도전 시작](https://labex.io/ko/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|     2 | 🎯  Projected Files 를 사용한 Secret 보호        | 초급    | [도전 시작](https://labex.io/ko/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|     3 | 🎯  런타임 보안 컨텍스트 강화                         | 초급    | [도전 시작](https://labex.io/ko/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|     4 | 🎯  위험한 사이드카 경계 격리                         | 초급    | [도전 시작](https://labex.io/ko/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### 공급망 보안

|   인덱스 | 이름                                | 난이도   | 연습                                                                                                           |
|-------|-----------------------------------|-------|--------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  최소화된 승인 이미지 빌드                 | 초급    | [도전 시작](https://labex.io/ko/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|     2 | 🎯  SBOM 및 체크섬 증거 검증               | 초급    | [도전 시작](https://labex.io/ko/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|     3 | 🎯  KubeLinter 를 사용한 워크로드 매니페스트 스캔 | 초급    | [도전 시작](https://labex.io/ko/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|     4 | 🎯  승인된 이미지 다이제스트로 워크로드 고정         | 초급    | [도전 시작](https://labex.io/ko/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### 모니터링, 로깅 및 런타임 보안

|   인덱스 | 이름                                 | 난이도   | 연습                                                                                                         |
|-------|------------------------------------|-------|------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  비밀 정보 (Secret) 접근에 대한 감사 이벤트 검토 | 초급    | [도전 시작](https://labex.io/ko/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|     2 | 🎯  의심스러운 런타임 프로세스 탐지               | 초급    | [도전 시작](https://labex.io/ko/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|     3 | 🎯  불변 런타임 컨테이너 강제 적용               | 초급    | [도전 시작](https://labex.io/ko/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|     4 | 🎯  비인가 API 활동 조사                   | 초급    | [도전 시작](https://labex.io/ko/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 3. [CKS 실전 모의고사 02](https://labex.io/ko/courses/cks-practice-exam-02)

공식 CKS 시험 범위를 포괄하는 다양한 운영 보안 시나리오를 바탕으로, 20 개의 쿠버네티스 보안 챌린지로 구성된 두 번째 독립형 CKS 실전 모의고사입니다.

[코스 시작](https://labex.io/ko/courses/cks-practice-exam-02) · 실습: 20

#### 클러스터 설정

|   인덱스 | 이름                           | 난이도   | 연습                                                                                                            |
|-------|------------------------------|-------|---------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  워크로드의 노드 메타데이터 접근 차단      | 초급    | [도전 시작](https://labex.io/ko/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|     2 | 🎯  Kubelet 노출에 대한 CIS 결과 검토  | 초급    | [도전 시작](https://labex.io/ko/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|     3 | 🎯  분할 Ingress 경로를 위한 TLS 재발급 | 초급    | [도전 시작](https://labex.io/ko/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### 클러스터 강화

|   인덱스 | 이름                          | 난이도   | 연습                                                                                                         |
|-------|-----------------------------|-------|------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  네임스페이스 오퍼레이터 역할 범위 지정    | 초급    | [도전 시작](https://labex.io/ko/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|     2 | 🎯  유출된 ServiceAccount 토큰 격리 | 초급    | [도전 시작](https://labex.io/ko/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|     3 | 🎯  API 서버 프록시 권한 상승 차단      | 초급    | [도전 시작](https://labex.io/ko/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### 시스템 강화

|   인덱스 | 이름                  | 난이도   | 연습                                                                                                           |
|-------|---------------------|-------|--------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  호스트 디버그 서비스 비활성화 | 초급    | [도전 시작](https://labex.io/ko/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|     2 | 🎯  호스트 로그 수집기 권한 제한 | 초급    | [도전 시작](https://labex.io/ko/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### 마이크로서비스 취약점 최소화

|   인덱스 | 이름                                 | 난이도   | 연습                                                                                                             |
|-------|------------------------------------|-------|----------------------------------------------------------------------------------------------------------------|
|     1 | 🎯  테넌트 Pod 보안 경계 적용                | 초급    | [도전 시작](https://labex.io/ko/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|     2 | 🎯  애플리케이션 시크릿 (Secret) 교체 및 제한     | 초급    | [도전 시작](https://labex.io/ko/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|     3 | 🎯  DNS 예외를 통한 테넌트 이그레스 (Egress) 격리 | 초급    | [도전 시작](https://labex.io/ko/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|     4 | 🎯  웹 파드에서 HostPath 캐시 제거           | 초급    | [도전 시작](https://labex.io/ko/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### 공급망 보안

|   인덱스 | 이름                              | 난이도   | 연습                                                                                                      |
|-------|---------------------------------|-------|---------------------------------------------------------------------------------------------------------|
|     1 | 🎯  신뢰할 수 있는 이미지 레지스트리 강제 적용     | 초급    | [도전 시작](https://labex.io/ko/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|     2 | 🎯  서명된 릴리스 매니페스트 검증             | 초급    | [도전 시작](https://labex.io/ko/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|     3 | 🎯  이미지에서 빌드 시크릿 제거하기            | 초급    | [도전 시작](https://labex.io/ko/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|     4 | 🎯  KubeLinter 를 사용한 Helm 출력물 스캔 | 초급    | [도전 시작](https://labex.io/ko/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### 모니터링, 로깅 및 런타임 보안

|   인덱스 | 이름                        | 난이도   | 연습                                                                                                      |
|-------|---------------------------|-------|---------------------------------------------------------------------------------------------------------|
|     1 | 🎯  감사 증적을 통한 정책 복구        | 초급    | [도전 시작](https://labex.io/ko/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|     2 | 🎯  비컨 (Beaconing) 워크로드 격리 | 초급    | [도전 시작](https://labex.io/ko/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|     3 | 🎯  런타임 파일 드리프트 탐지         | 초급    | [도전 시작](https://labex.io/ko/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|     4 | 🎯  손상된 작업 토큰 격리           | 초급    | [도전 시작](https://labex.io/ko/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

