# CKS トレーニング Certification Prep Path

## 言語

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/ja/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/パスを開始-whitesmoke?style=for-the-badge)](https://labex.io/ja/learn/cks)

Certified Kubernetes Security Specialist（CKS）試験に向けた、体系的かつ実践的な学習パスです。Kubernetes におけるクラスター強化、システム強化、マイクロサービスの脆弱性最小化、サプライチェーンセキュリティ、監視・ログ・ランタイムセキュリティ、および CKS 形式のパフォーマンスベースのタスクと現実的なシナリオに焦点を当てます。CKS コース、ラボ、模擬試験の演習は順次追加され、CKS の目標に沿ったスキルを育成します。

**コース**: 3 · **ラボ**: 85

## コース

### 1. [CKS 試験対策コース](https://labex.io/ja/courses/cks-prep)

Kubernetes セキュリティの基礎から、クラスターの構築、ハードニング、ワークロードの保護、サプライチェーン、監査、実行時の調査まで、45 のガイド付き実験を通じて体系的に学べる初心者向けの CKS 対策コースです。

[コースを開始](https://labex.io/ja/courses/cks-prep) · ラボ: 45

#### Kubernetes セキュリティの基礎

|   インデックス | 名前                             | 難易度   | 練習                                                                                              |
|----------|--------------------------------|-------|-------------------------------------------------------------------------------------------------|
|        1 | 🧩  Kubernetes セキュリティ境界のマッピング   | 初級    | [ラボを開始](https://labex.io/ja/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|        2 | 🧩  kubectl を使用したセキュリティエビデンスの収集 | 初級    | [ラボを開始](https://labex.io/ja/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|        3 | 🧩  ネームスペースとテナント分離の確認           | 初級    | [ラボを開始](https://labex.io/ja/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|        4 | 🧩  RBAC のサブジェクトと権限の調査          | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|        5 | 🧩  ServiceAccount トークンの動作を調査する | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|        6 | 🧩  Pod Security Standards の適用  | 初級    | [ラボを開始](https://labex.io/ja/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### クラスターセットアップのセキュリティ

|   インデックス | 名前                                            | 難易度   | 練習                                                                                                     |
|----------|-----------------------------------------------|-------|--------------------------------------------------------------------------------------------------------|
|        1 | 🧩  NetworkPolicy を使用した名前空間トラフィックの制限           | 初級    | [ラボを開始](https://labex.io/ja/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|        2 | 🧩  デフォルト拒否（Default-Deny）Egress における DNS 通信の許可 | 初級    | [ラボを開始](https://labex.io/ja/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|        3 | 🧩  Ingress を TLS で公開する                        | 初級    | [ラボを開始](https://labex.io/ja/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|        4 | 🧩  ワークロードによるノードメタデータへのアクセス拒否                  | 初級    | [ラボを開始](https://labex.io/ja/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|        5 | 🧩  Kubernetes バイナリの検証                         | 初級    | [ラボを開始](https://labex.io/ja/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|        6 | 🧩  kube-bench を使用した CIS ベンチマーク結果のレビュー         | 初級    | [ラボを開始](https://labex.io/ja/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|        7 | 🧩  アドミッションと Pod セキュリティの準備状況の確認                | 初級    | [ラボを開始](https://labex.io/ja/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### クラスターの堅牢化

|   インデックス | 名前                                      | 難易度   | 練習                                                                                                   |
|----------|-----------------------------------------|-------|------------------------------------------------------------------------------------------------------|
|        1 | 🧩  ロールの権限を最小化する                         | 初級    | [ラボを開始](https://labex.io/ja/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|        2 | 🧩  過剰な権限を持つ ClusterRoleBinding の削減      | 初級    | [ラボを開始](https://labex.io/ja/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|        3 | 🧩  デフォルトの ServiceAccount トークンマウントを無効化する | 初級    | [ラボを開始](https://labex.io/ja/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|        4 | 🧩  ネームスペーススコープのオペレーターロールの設定             | 初級    | [ラボを開始](https://labex.io/ja/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|        5 | 🧩  API サーバープロキシ昇格のブロック                  | 初級    | [ラボを開始](https://labex.io/ja/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|        6 | 🧩  漏洩した ServiceAccount トークンの封じ込め        | 初級    | [ラボを開始](https://labex.io/ja/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|        7 | 🧩  機密リソースへのアクセス監査                       | 初級    | [ラボを開始](https://labex.io/ja/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### システムおよびノードの堅牢化

|   インデックス | 名前                                   | 難易度   | 練習                                                                                                         |
|----------|--------------------------------------|-------|------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  ホストの攻撃対象領域を安全に調査する                | 初級    | [ラボを開始](https://labex.io/ja/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|        2 | 🧩  ホストデバッグサービスの無効化                   | 初級    | [ラボを開始](https://labex.io/ja/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|        3 | 🧩  kubelet の公開状況のレビュー                | 初級    | [ラボを開始](https://labex.io/ja/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|        4 | 🧩  ワークロードにおける AppArmor プロファイル適用状況の確認 | 初級    | [ラボを開始](https://labex.io/ja/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|        5 | 🧩  ローカル seccomp プロファイルのインストール        | 初級    | [ラボを開始](https://labex.io/ja/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|        6 | 🧩  ワークロードから hostPath アクセスを削除する       | 初級    | [ラボを開始](https://labex.io/ja/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### ワークロードとマイクロサービスのセキュリティ

|   インデックス | 名前                           | 難易度   | 練習                                                                                                |
|----------|------------------------------|-------|---------------------------------------------------------------------------------------------------|
|        1 | 🧩  Pod セキュリティコンテキストの強化       | 初級    | [ラボを開始](https://labex.io/ja/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|        2 | 🧩  Linux Capabilities の削除    | 初級    | [ラボを開始](https://labex.io/ja/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|        3 | 🧩  コンテナを非ルート（Non-Root）で実行する  | 初級    | [ラボを開始](https://labex.io/ja/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|        4 | 🧩  プロジェクテッドファイルによるシークレットの保護  | 初級    | [ラボを開始](https://labex.io/ja/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|        5 | 🧩  アプリケーションシークレットのローテーションと制限 | 初級    | [ラボを開始](https://labex.io/ja/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|        6 | 🧩  リスクのあるサイドカーの境界を分離する       | 初級    | [ラボを開始](https://labex.io/ja/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|        7 | 🧩  イミュータブル（不変）なランタイムコンテナの強制  | 初級    | [ラボを開始](https://labex.io/ja/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|        8 | 🧩  疑わしいワークロードの隔離             | 初級    | [ラボを開始](https://labex.io/ja/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### サプライチェーンセキュリティ

|   インデックス | 名前                                    | 難易度   | 練習                                                                                                |
|----------|---------------------------------------|-------|---------------------------------------------------------------------------------------------------|
|        1 | 🧩  最小限の承認済みイメージの構築                    | 初級    | [ラボを開始](https://labex.io/ja/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|        2 | 🧩  kube-linter を使用したワークロードマニフェストのスキャン | 初級    | [ラボを開始](https://labex.io/ja/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|        3 | 🧩  kube-linter を使用した Helm 出力のスキャン     | 初級    | [ラボを開始](https://labex.io/ja/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|        4 | 🧩  SBOM とチェックサムの証拠を検証する               | 初級    | [ラボを開始](https://labex.io/ja/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|        5 | 🧩  信頼できるイメージレジストリの強制                  | 初級    | [ラボを開始](https://labex.io/ja/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|        6 | 🧩  イメージからビルドシークレットを削除する               | 初級    | [ラボを開始](https://labex.io/ja/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### 監視、監査、およびランタイムセキュリティ

|   インデックス | 名前                           | 難易度   | 練習                                                                                             |
|----------|------------------------------|-------|------------------------------------------------------------------------------------------------|
|        1 | 🧩  シークレットアクセスに関する監査イベントのレビュー | 初級    | [ラボを開始](https://labex.io/ja/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|        2 | 🧩  不正な API アクティビティの調査        | 初級    | [ラボを開始](https://labex.io/ja/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|        3 | 🧩  不審なランタイムプロセスの検出           | 初級    | [ラボを開始](https://labex.io/ja/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|        4 | 🧩  ランタイムファイルのドリフト検知          | 初級    | [ラボを開始](https://labex.io/ja/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|        5 | 🧩  監査証跡からのポリシー復元             | 初級    | [ラボを開始](https://labex.io/ja/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

### 2. [CKS 模擬試験 01](https://labex.io/ja/courses/cks-practice-exam-01)

クラスターのセットアップ、クラスターの強化、システムの強化、マイクロサービスの脆弱性軽減、サプライチェーンセキュリティ、ランタイムセキュリティを網羅した、20 の独立した Kubernetes セキュリティ課題に取り組む実践的な CKS 模擬試験です。

[コースを開始](https://labex.io/ja/courses/cks-practice-exam-01) · ラボ: 20

#### クラスターのセットアップ

|   インデックス | 名前                                  | 難易度   | 練習                                                                                                                    |
|----------|-------------------------------------|-------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  NetworkPolicy を使用した名前空間トラフィックの制限 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|        2 | 🎯  TLS Ingress を使用した管理コンソールの公開      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|        3 | 🎯  デプロイ前の Kubernetes バイナリ検証         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### クラスターの強化

|   インデックス | 名前                                    | 難易度   | 練習                                                                                                                  |
|----------|---------------------------------------|-------|---------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  過剰な権限を持つ ClusterRoleBinding の削減    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|        2 | 🎯  デフォルトの ServiceAccount トークンマウントの無効化 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|        3 | 🎯  インシデントリーダーの API アクセス制限             | 初級    | [チャレンジを開始](https://labex.io/ja/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### システムの強化

|   インデックス | 名前                             | 難易度   | 練習                                                                                                                |
|----------|--------------------------------|-------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ワークロードへの AppArmor プロファイルの適用 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|        2 | 🎯  ローカル Seccomp プロファイルのインストール  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### マイクロサービスの脆弱性最小化

|   インデックス | 名前                          | 難易度   | 練習                                                                                                           |
|----------|-----------------------------|-------|--------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  制限付き Pod セキュリティの強制       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|        2 | 🎯  プロジェクテッドファイルによるシークレットの保護 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|        3 | 🎯  ランタイムセキュリティコンテキストの強化     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|        4 | 🎯  リスクのあるサイドカーの境界を分離する      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### サプライチェーンセキュリティ

|   インデックス | 名前                                   | 難易度   | 練習                                                                                                              |
|----------|--------------------------------------|-------|-----------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  最小限の承認済みイメージの構築                   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|        2 | 🎯  SBOM とチェックサムの証拠検証                 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|        3 | 🎯  KubeLinter を使用したワークロードマニフェストのスキャン | 初級    | [チャレンジを開始](https://labex.io/ja/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|        4 | 🎯  承認済みイメージダイジェストへのワークロード固定          | 初級    | [チャレンジを開始](https://labex.io/ja/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### 監視、ログ記録、およびランタイムセキュリティ

|   インデックス | 名前                           | 難易度   | 練習                                                                                                            |
|----------|------------------------------|-------|---------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  シークレットアクセスに関する監査イベントのレビュー | 初級    | [チャレンジを開始](https://labex.io/ja/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|        2 | 🎯  不審なランタイムプロセスの検出           | 初級    | [チャレンジを開始](https://labex.io/ja/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|        3 | 🎯  イミュータブル（不変）なランタイムコンテナの強制  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|        4 | 🎯  不正な API アクティビティの調査        | 初級    | [チャレンジを開始](https://labex.io/ja/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 3. [CKS 模擬試験 02](https://labex.io/ja/courses/cks-practice-exam-02)

CKS 試験の全範囲を網羅した、実践的なセキュリティシナリオに基づく 20 問の Kubernetes セキュリティ課題で構成される、独立した第 2 回模擬試験です。

[コースを開始](https://labex.io/ja/courses/cks-practice-exam-02) · ラボ: 20

#### クラスターのセットアップ

|   インデックス | 名前                               | 難易度   | 練習                                                                                                               |
|----------|----------------------------------|-------|------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ノードメタデータへのワークロードアクセスを拒否する     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|        2 | 🎯  Kubelet 露出に関する CIS 調査結果のレビュー  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|        3 | 🎯  分割された Ingress ルートのための TLS 再発行 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### クラスターの強化

|   インデックス | 名前                               | 難易度   | 練習                                                                                                            |
|----------|----------------------------------|-------|---------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  名前空間オペレーターのロールのスコープ設定         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|        2 | 🎯  漏洩した ServiceAccount トークンの封じ込め | 初級    | [チャレンジを開始](https://labex.io/ja/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|        3 | 🎯  API サーバープロキシ昇格のブロック           | 初級    | [チャレンジを開始](https://labex.io/ja/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### システムの強化

|   インデックス | 名前                 | 難易度   | 練習                                                                                                              |
|----------|--------------------|-------|-----------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ホストデバッグサービスの無効化 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|        2 | 🎯  ホストログ収集者の権限制限   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### マイクロサービスの脆弱性最小化

|   インデックス | 名前                               | 難易度   | 練習                                                                                                                |
|----------|----------------------------------|-------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  テナントの Pod セキュリティ境界の適用         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|        2 | 🎯  アプリケーションシークレットのローテーションと制限     | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|        3 | 🎯  DNS 例外を用いたテナントエグレスの分離         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|        4 | 🎯  Web Pod からの HostPath キャッシュの削除 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### サプライチェーンセキュリティ

|   インデックス | 名前                               | 難易度   | 練習                                                                                                         |
|----------|----------------------------------|-------|------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  信頼できるイメージレジストリの強制             | 初級    | [チャレンジを開始](https://labex.io/ja/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|        2 | 🎯  署名済みリリース・マニフェストの検証            | 初級    | [チャレンジを開始](https://labex.io/ja/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|        3 | 🎯  イメージからビルドシークレットを削除する          | 初級    | [チャレンジを開始](https://labex.io/ja/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|        4 | 🎯  KubeLinter を使用した Helm 出力のスキャン | 初級    | [チャレンジを開始](https://labex.io/ja/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### 監視、ログ記録、およびランタイムセキュリティ

|   インデックス | 名前                    | 難易度   | 練習                                                                                                         |
|----------|-----------------------|-------|------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  監査証跡からのポリシー復元      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|        2 | 🎯  ビーコン通信を行うワークロードの隔離 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|        3 | 🎯  ランタイムファイルドリフトの検出   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|        4 | 🎯  侵害されたジョブトークンの封じ込め  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## LabEx について

[LabEx](https://labex.io) は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ、ブラウザ内のインタラクティブなオンライン環境で自動化されたステップバイステップのチェック機能、スキルツリーベースのシステムによる構造化されたコンテンツ組織、30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソースにより、[LabEx](https://labex.io) は包括的な実践教育を提供します。プラットフォームには、最新の AI モデルを基盤とした学習アシスタント Labby が含まれており、対話型学習体験を提供します。

