# CKS-Schulung Zertifizierungsvorbereitung

## Sprachen

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/de/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Pfad-Starten-whitesmoke?style=for-the-badge)](https://labex.io/de/learn/cks)

Bereiten Sie sich mit einem strukturierten, praxisorientierten Lernpfad auf die Prüfung Certified Kubernetes Security Specialist (CKS) vor. Der Fokus liegt auf Cluster-Härtung, System-Härtung, Minimierung von Microservice-Schwachstellen, Supply-Chain-Sicherheit sowie Monitoring, Logging und Runtime-Sicherheit in Kubernetes, leistungsbasierten CKS-Aufgaben und realistischen Szenarien. CKS-Kurse, Labs und Übungsprüfungen werden schrittweise ergänzt.

**Kurse**: 3 · **Labs**: 85

## Kurse

### 1. [CKS-Vorbereitung](https://labex.io/de/courses/cks-prep)

Ein einsteigerfreundlicher CKS-Vorbereitungskurs mit 45 geführten Kubernetes-Sicherheitsexperimenten, die von den Grundlagen der Sicherheit bis hin zu Cluster-Einrichtung, Härtung, Workload-Sicherheit, Lieferketten, Audits und Laufzeituntersuchungen reichen.

[Kurs Starten](https://labex.io/de/courses/cks-prep) · Labs: 45

#### Security Foundations for Kubernetes

|   Index | Name                                                     | Schwierigkeit   | Übung                                                                                                   |
|---------|----------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Kubernetes-Sicherheitsgrenzen abbilden                | Anfänger        | [Labor Starten](https://labex.io/de/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|       2 | 🧩  Sicherheitsnachweise mit kubectl sammeln              | Anfänger        | [Labor Starten](https://labex.io/de/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|       3 | 🧩  Namespaces und Mandantentrennung überprüfen           | Anfänger        | [Labor Starten](https://labex.io/de/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|       4 | 🧩  RBAC-Subjekte und Berechtigungen untersuchen          | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|       5 | 🧩  Untersuchung des Verhaltens von ServiceAccount-Tokens | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|       6 | 🧩  Pod Security Standards anwenden                       | Anfänger        | [Labor Starten](https://labex.io/de/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### Cluster Setup Security

|   Index | Name                                                           | Schwierigkeit   | Übung                                                                                                          |
|---------|----------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Einschränkung des Namespace-Datenverkehrs mit NetworkPolicy | Anfänger        | [Labor Starten](https://labex.io/de/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|       2 | 🧩  DNS-Zugriff bei Default-Deny-Egress erlauben                | Anfänger        | [Labor Starten](https://labex.io/de/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|       3 | 🧩  Ingress mit TLS veröffentlichen                             | Anfänger        | [Labor Starten](https://labex.io/de/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|       4 | 🧩  Zugriff von Workloads auf Node-Metadaten verweigern         | Anfänger        | [Labor Starten](https://labex.io/de/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|       5 | 🧩  Kubernetes-Binärdateien verifizieren                        | Anfänger        | [Labor Starten](https://labex.io/de/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|       6 | 🧩  Überprüfung von CIS-Ergebnissen mit kube-bench              | Anfänger        | [Labor Starten](https://labex.io/de/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|       7 | 🧩  Überprüfung der Zulassungs- und Pod-Sicherheitsbereitschaft | Anfänger        | [Labor Starten](https://labex.io/de/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### Cluster Hardening

|   Index | Name                                                       | Schwierigkeit   | Übung                                                                                                        |
|---------|------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Minimierung von Rollenberechtigungen                    | Anfänger        | [Labor Starten](https://labex.io/de/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|       2 | 🧩  Reduzierung eines überprivilegierten ClusterRoleBinding | Anfänger        | [Labor Starten](https://labex.io/de/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|       3 | 🧩  Standardmäßige ServiceAccount-Token-Mounts deaktivieren | Anfänger        | [Labor Starten](https://labex.io/de/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|       4 | 🧩  Eingrenzung einer Namespace-Operator-Rolle              | Anfänger        | [Labor Starten](https://labex.io/de/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|       5 | 🧩  Blockierung der API-Server-Proxy-Eskalation             | Anfänger        | [Labor Starten](https://labex.io/de/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|       6 | 🧩  Eindämmung eines geleakten ServiceAccount-Tokens        | Anfänger        | [Labor Starten](https://labex.io/de/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|       7 | 🧩  Zugriff auf sensible Ressourcen prüfen                  | Anfänger        | [Labor Starten](https://labex.io/de/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### System and Node Hardening

|   Index | Name                                                               | Schwierigkeit   | Übung                                                                                                              |
|---------|--------------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Sichere Untersuchung der Angriffsfläche eines Hosts             | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|       2 | 🧩  Einen Host-Debug-Dienst deaktivieren                            | Anfänger        | [Labor Starten](https://labex.io/de/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|       3 | 🧩  Überprüfung der Kubelet-Exposition                              | Anfänger        | [Labor Starten](https://labex.io/de/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|       4 | 🧩  Überprüfung der AppArmor-Profil-Durchsetzung bei einer Workload | Anfänger        | [Labor Starten](https://labex.io/de/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|       5 | 🧩  Installieren eines lokalen seccomp-Profils                      | Anfänger        | [Labor Starten](https://labex.io/de/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|       6 | 🧩  Entfernen des HostPath-Zugriffs von einer Workload              | Anfänger        | [Labor Starten](https://labex.io/de/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### Workload and Microservice Security

|   Index | Name                                                  | Schwierigkeit   | Übung                                                                                                     |
|---------|-------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Härtung eines Pod Security Context                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|       2 | 🧩  Linux-Capabilities entziehen                       | Anfänger        | [Labor Starten](https://labex.io/de/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|       3 | 🧩  Container als Non-Root ausführen                   | Anfänger        | [Labor Starten](https://labex.io/de/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|       4 | 🧩  Secrets mit Projected Files schützen               | Anfänger        | [Labor Starten](https://labex.io/de/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|       5 | 🧩  Anwendungs-Secrets rotieren und einschränken       | Anfänger        | [Labor Starten](https://labex.io/de/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|       6 | 🧩  Isolierung einer riskanten Sidecar-Grenze          | Anfänger        | [Labor Starten](https://labex.io/de/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|       7 | 🧩  Erzwingen von unveränderlichen Laufzeit-Containern | Anfänger        | [Labor Starten](https://labex.io/de/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|       8 | 🧩  Quarantäne für einen verdächtigen Workload         | Anfänger        | [Labor Starten](https://labex.io/de/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### Supply Chain Security

|   Index | Name                                                | Schwierigkeit   | Übung                                                                                                     |
|---------|-----------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Erstellen eines minimalen, genehmigten Images    | Anfänger        | [Labor Starten](https://labex.io/de/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|       2 | 🧩  Workload-Manifeste mit kube-linter scannen       | Anfänger        | [Labor Starten](https://labex.io/de/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|       3 | 🧩  Helm-Ausgabe mit kube-linter scannen             | Anfänger        | [Labor Starten](https://labex.io/de/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|       4 | 🧩  SBOM und Prüfsummen-Nachweise verifizieren       | Anfänger        | [Labor Starten](https://labex.io/de/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|       5 | 🧩  Erzwingen vertrauenswürdiger Image-Registries    | Anfänger        | [Labor Starten](https://labex.io/de/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|       6 | 🧩  Entfernen von Build-Geheimnissen aus einem Image | Anfänger        | [Labor Starten](https://labex.io/de/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### Monitoring, Audit, and Runtime Security

|   Index | Name                                                          | Schwierigkeit   | Übung                                                                                                  |
|---------|---------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Überprüfung von Audit-Ereignissen auf Secret-Zugriffe      | Anfänger        | [Labor Starten](https://labex.io/de/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|       2 | 🧩  Untersuchung unbefugter API-Aktivitäten                    | Anfänger        | [Labor Starten](https://labex.io/de/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|       3 | 🧩  Verdächtige Laufzeitprozesse erkennen                      | Anfänger        | [Labor Starten](https://labex.io/de/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|       4 | 🧩  Laufzeit-Dateidrift erkennen                               | Anfänger        | [Labor Starten](https://labex.io/de/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|       5 | 🧩  Wiederherstellung einer Policy anhand von Audit-Nachweisen | Anfänger        | [Labor Starten](https://labex.io/de/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

### 2. [CKS-Übungsprüfung 01](https://labex.io/de/courses/cks-practice-exam-01)

Eine praxisorientierte CKS-Übungsprüfung mit 20 unabhängigen Kubernetes-Sicherheitsherausforderungen, die die Bereiche Cluster-Einrichtung, Cluster-Härtung, System-Härtung, Reduzierung von Microservice-Schwachstellen, Supply-Chain-Sicherheit und Laufzeitsicherheit abdecken.

[Kurs Starten](https://labex.io/de/courses/cks-practice-exam-01) · Labs: 20

#### Cluster Setup

|   Index | Name                                                              | Schwierigkeit   | Übung                                                                                                                          |
|---------|-------------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Einschränkung des Namespace-Traffics mit NetworkPolicy         | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|       2 | 🎯  Veröffentlichung einer Admin-Konsole mit TLS Ingress           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|       3 | 🎯  Überprüfung von Kubernetes-Binärdateien vor der Bereitstellung | Anfänger        | [Challenge Starten](https://labex.io/de/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### Cluster Hardening

|   Index | Name                                                                | Schwierigkeit   | Übung                                                                                                                        |
|---------|---------------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Reduzierung eines überprivilegierten ClusterRoleBinding          | Anfänger        | [Challenge Starten](https://labex.io/de/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|       2 | 🎯  Deaktivieren der standardmäßigen ServiceAccount-Token-Einbindung | Anfänger        | [Challenge Starten](https://labex.io/de/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|       3 | 🎯  API-Zugriff für Incident-Reader einschränken                     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### System Hardening

|   Index | Name                                                  | Schwierigkeit   | Übung                                                                                                                      |
|---------|-------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Erzwingen eines AppArmor-Profils für eine Workload | Anfänger        | [Challenge Starten](https://labex.io/de/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|       2 | 🎯  Installieren eines lokalen Seccomp-Profils         | Anfänger        | [Challenge Starten](https://labex.io/de/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### Minimize Microservice Vulnerabilities

|   Index | Name                                         | Schwierigkeit   | Übung                                                                                                                 |
|---------|----------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Erzwingen der Restricted Pod Security     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|       2 | 🎯  Secrets mit Projected Files schützen      | Anfänger        | [Challenge Starten](https://labex.io/de/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|       3 | 🎯  Härtung eines Runtime Security Context    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|       4 | 🎯  Isolierung einer riskanten Sidecar-Grenze | Anfänger        | [Challenge Starten](https://labex.io/de/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### Supply Chain Security

|   Index | Name                                             | Schwierigkeit   | Übung                                                                                                                    |
|---------|--------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Erstellen eines minimalen, genehmigten Images | Anfänger        | [Challenge Starten](https://labex.io/de/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|       2 | 🎯  SBOM und Prüfsummen-Nachweise verifizieren    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|       3 | 🎯  Workload-Manifeste mit KubeLinter scannen     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|       4 | 🎯  Workloads an genehmigte Image-Digests binden  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### Monitoring, Logging and Runtime Security

|   Index | Name                                                     | Schwierigkeit   | Übung                                                                                                                  |
|---------|----------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Überprüfung von Audit-Ereignissen auf Secret-Zugriffe | Anfänger        | [Challenge Starten](https://labex.io/de/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|       2 | 🎯  Einen verdächtigen Laufzeitprozess erkennen           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|       3 | 🎯  Erzwingen von unveränderlichen Laufzeit-Containern    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|       4 | 🎯  Unbefugte API-Aktivitäten untersuchen                 | Anfänger        | [Challenge Starten](https://labex.io/de/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 3. [CKS-Übungsprüfung 02](https://labex.io/de/courses/cks-practice-exam-02)

Eine zweite, unabhängige CKS-Übungsprüfung mit 20 Kubernetes-Sicherheitsherausforderungen, die die offiziellen CKS-Themenbereiche anhand verschiedener operativer Sicherheitsszenarien abdeckt.

[Kurs Starten](https://labex.io/de/courses/cks-practice-exam-02) · Labs: 20

#### Cluster Setup

|   Index | Name                                                       | Schwierigkeit   | Übung                                                                                                                     |
|---------|------------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Zugriff von Workloads auf Node-Metadaten verweigern     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|       2 | 🎯  Überprüfung von CIS-Ergebnissen für Kubelet-Exponierung | Anfänger        | [Challenge Starten](https://labex.io/de/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|       3 | 🎯  TLS für eine geteilte Ingress-Route neu ausstellen      | Anfänger        | [Challenge Starten](https://labex.io/de/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### Cluster Hardening

|   Index | Name                                                | Schwierigkeit   | Übung                                                                                                                  |
|---------|-----------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Einschränkung einer Namespace-Operator-Rolle     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|       2 | 🎯  Eindämmung eines geleakten ServiceAccount-Tokens | Anfänger        | [Challenge Starten](https://labex.io/de/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|       3 | 🎯  Blockieren der API-Server-Proxy-Eskalation       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### System Hardening

|   Index | Name                                                   | Schwierigkeit   | Übung                                                                                                                    |
|---------|--------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Einen Host-Debug-Dienst deaktivieren                | Anfänger        | [Challenge Starten](https://labex.io/de/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|       2 | 🎯  Berechtigungen des Host-Log-Collectors einschränken | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### Minimize Microservice Vulnerabilities

|   Index | Name                                               | Schwierigkeit   | Übung                                                                                                                      |
|---------|----------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Pod-Sicherheitsgrenzen für Mandanten anwenden   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|       2 | 🎯  Anwendungs-Secrets rotieren und einschränken    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|       3 | 🎯  Isolierung von Tenant-Egress mit DNS-Ausnahmen  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|       4 | 🎯  Entfernen des HostPath-Caches aus einem Web-Pod | Anfänger        | [Challenge Starten](https://labex.io/de/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### Supply Chain Security

|   Index | Name                                                | Schwierigkeit   | Übung                                                                                                               |
|---------|-----------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Erzwingen vertrauenswürdiger Image-Registries    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|       2 | 🎯  Validierung eines signierten Release-Manifests   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|       3 | 🎯  Entfernen von Build-Geheimnissen aus einem Image | Anfänger        | [Challenge Starten](https://labex.io/de/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|       4 | 🎯  Helm-Ausgabe mit KubeLinter scannen              | Anfänger        | [Challenge Starten](https://labex.io/de/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### Monitoring, Logging and Runtime Security

|   Index | Name                                                          | Schwierigkeit   | Übung                                                                                                               |
|---------|---------------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Wiederherstellung einer Policy anhand von Audit-Nachweisen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|       2 | 🎯  Quarantäne für eine Beaconing-Workload                     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|       3 | 🎯  Erkennung von Runtime-File-Drift                           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|       4 | 🎯  Eindämmung eines kompromittierten Job-Tokens               | Anfänger        | [Challenge Starten](https://labex.io/de/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## Über LabEx

[LabEx](https://labex.io) ist eine interaktive, praktische Lernplattform für Programmierung und Technologie. Sie kombiniert Labore, KI-Unterstützung und virtuelle Maschinen für eine videofreie, praktische Lernerfahrung. Mit einem strikten 'Learning by Doing'-Ansatz, interaktiven Online-Umgebungen im Browser mit automatisierten Schritt-für-Schritt-Überprüfungen, strukturierter Inhaltsorganisation mit dem Skill-Tree-basierten System, und einer wachsenden Lernressource von 30 Skill Trees und über 6.000 Laboren, [LabEx](https://labex.io) bietet umfassende praktische Bildung. Die Plattform umfasst den Lernassistenten Labby, aufgebaut auf den neuesten KI-Modellen, der eine konversationelle Lernerfahrung bietet.

