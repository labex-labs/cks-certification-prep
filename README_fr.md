# Formation CKS Parcours de Préparation à la Certification

## Langues

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/fr/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Commencer-le-Parcours-whitesmoke?style=for-the-badge)](https://labex.io/fr/learn/cks)

Préparez-vous à l'examen Certified Kubernetes Security Specialist (CKS) grâce à un parcours structuré et orienté pratique. Ce plan met l'accent sur durcissement de cluster, durcissement système, réduction des vulnérabilités des microservices, sécurité de la chaîne d'approvisionnement, surveillance, journalisation et sécurité à l'exécution dans Kubernetes, les tâches en mode performance au style CKS et des scénarios réalistes. Des cours CKS, des labs et des examens blancs seront ajoutés progressivement.

**Cours**: 3 · **Labs**: 85

## Cours

### 1. [Préparation CKS](https://labex.io/fr/courses/cks-prep)

Un cours de préparation au CKS adapté aux débutants, comprenant 45 laboratoires Kubernetes guidés, structurés des bases de la sécurité à la configuration des clusters, au durcissement, à la sécurité des charges de travail, à la chaîne d'approvisionnement, à l'audit et à l'analyse du runtime.

[Commencer le Cours](https://labex.io/fr/courses/cks-prep) · Labs: 45

#### Security Foundations for Kubernetes

|   Index | Nom                                                       | Difficulté   | Pratique                                                                                                   |
|---------|-----------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Cartographier les frontières de sécurité Kubernetes    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|       2 | 🧩  Collecter des preuves de sécurité avec kubectl         | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|       3 | 🧩  Examen des Namespaces et de l'isolation des locataires | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|       4 | 🧩  Inspecter les sujets et les permissions RBAC           | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|       5 | 🧩  Inspecter le comportement des jetons ServiceAccount    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|       6 | 🧩  Appliquer les standards de sécurité des Pods           | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### Cluster Setup Security

|   Index | Nom                                                                          | Difficulté   | Pratique                                                                                                          |
|---------|------------------------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Restreindre le trafic d'un namespace avec NetworkPolicy                   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|       2 | 🧩  Autoriser le DNS via une politique de refus par défaut en sortie (Egress) | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|       3 | 🧩  Publier une ressource Ingress avec TLS                                    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|       4 | 🧩  Refuser l'accès des charges de travail aux métadonnées du nœud            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|       5 | 🧩  Vérification des binaires Kubernetes                                      | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|       6 | 🧩  Examen des résultats CIS avec kube-bench                                  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|       7 | 🧩  Vérification de l'admission et de la préparation à la sécurité des Pods   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### Cluster Hardening

|   Index | Nom                                                               | Difficulté   | Pratique                                                                                                        |
|---------|-------------------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Minimiser les permissions d'un rôle                            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|       2 | 🧩  Réduire une liaison ClusterRoleBinding surprivilégiée          | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|       3 | 🧩  Désactiver le montage automatique des jetons de ServiceAccount | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|       4 | 🧩  Définir le périmètre d'un rôle d'opérateur dans un namespace   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|       5 | 🧩  Blocage de l'escalade via le proxy de l'API Server             | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|       6 | 🧩  Contenir un jeton de ServiceAccount ayant fuité                | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|       7 | 🧩  Auditer l'accès aux ressources sensibles                       | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### System and Node Hardening

|   Index | Nom                                                                             | Difficulté   | Pratique                                                                                                              |
|---------|---------------------------------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Inspecter la surface d'attaque de l'hôte en toute sécurité                   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|       2 | 🧩  Désactiver un service de débogage hôte                                       | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|       3 | 🧩  Examen de l'exposition du kubelet                                            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|       4 | 🧩  Vérification de l'application d'un profil AppArmor sur une charge de travail | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|       5 | 🧩  Installer un profil seccomp local                                            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|       6 | 🧩  Supprimer l'accès HostPath d'une charge de travail                           | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### Workload and Microservice Security

|   Index | Nom                                                        | Difficulté   | Pratique                                                                                                     |
|---------|------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Renforcer le contexte de sécurité d'un Pod              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|       2 | 🧩  Suppression des capacités Linux                         | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|       3 | 🧩  Exécuter des conteneurs en tant qu'utilisateur non-root | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|       4 | 🧩  Protéger les secrets avec des fichiers projetés         | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|       5 | 🧩  Rotation et restriction des secrets d'application       | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|       6 | 🧩  Isoler une limite de sidecar à risque                   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|       7 | 🧩  Appliquer des conteneurs d'exécution immuables          | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|       8 | 🧩  Mise en quarantaine d'une charge de travail suspecte    | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### Supply Chain Security

|   Index | Nom                                                                               | Difficulté   | Pratique                                                                                                     |
|---------|-----------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Construire une image minimale approuvée                                        | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|       2 | 🧩  Analyser les manifestes de charge de travail avec kube-linter                  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|       3 | 🧩  Analyser la sortie Helm avec kube-linter                                       | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|       4 | 🧩  Vérifier la nomenclature logicielle (SBOM) et les preuves de somme de contrôle | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|       5 | 🧩  Appliquer des registres d'images de confiance                                  | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|       6 | 🧩  Supprimer les secrets de build d'une image                                     | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### Monitoring, Audit, and Runtime Security

|   Index | Nom                                                       | Difficulté   | Pratique                                                                                                  |
|---------|-----------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Examen des événements d'audit pour l'accès aux Secrets | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|       2 | 🧩  Enquêter sur une activité API non autorisée            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|       3 | 🧩  Détecter les processus d'exécution suspects            | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|       4 | 🧩  Détecter la dérive de fichiers au runtime              | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|       5 | 🧩  Restaurer une politique à partir des preuves d'audit   | Débutant     | [Commencer le Lab](https://labex.io/fr/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

### 2. [Examen blanc CKS 01](https://labex.io/fr/courses/cks-practice-exam-01)

Un examen blanc pratique pour la certification CKS composé de 20 défis de sécurité Kubernetes indépendants, couvrant la configuration et le durcissement des clusters, le renforcement des systèmes, la réduction des vulnérabilités des microservices, la sécurité de la chaîne d'approvisionnement et la sécurité à l'exécution.

[Commencer le Cours](https://labex.io/fr/courses/cks-practice-exam-01) · Labs: 20

#### Cluster Setup

|   Index | Nom                                                        | Difficulté   | Pratique                                                                                                                       |
|---------|------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Restreindre le trafic d'un Namespace avec NetworkPolicy | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|       2 | 🎯  Publier une console d'administration avec TLS Ingress   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|       3 | 🎯  Vérifier les binaires Kubernetes avant le déploiement   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### Cluster Hardening

|   Index | Nom                                                                          | Difficulté   | Pratique                                                                                                                     |
|---------|------------------------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Réduire une liaison ClusterRoleBinding surprivilégiée                     | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|       2 | 🎯  Désactiver le montage automatique des jetons de ServiceAccount par défaut | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|       3 | 🎯  Restreindre l'accès API de l'incident-reader                              | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### System Hardening

|   Index | Nom                                                       | Difficulté   | Pratique                                                                                                                   |
|---------|-----------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Appliquer un profil AppArmor sur une charge de travail | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|       2 | 🎯  Installer un profil Seccomp local                      | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### Minimize Microservice Vulnerabilities

|   Index | Nom                                                | Difficulté   | Pratique                                                                                                              |
|---------|----------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Appliquer la sécurité restreinte des Pods       | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|       2 | 🎯  Protéger les secrets avec des fichiers projetés | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|       3 | 🎯  Renforcer un contexte de sécurité d'exécution   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|       4 | 🎯  Isoler une limite de sidecar à risque           | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### Supply Chain Security

|   Index | Nom                                                                                      | Difficulté   | Pratique                                                                                                                 |
|---------|------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Construire une image minimale approuvée                                               | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|       2 | 🎯  Vérification de la nomenclature logicielle (SBOM) et des preuves de somme de contrôle | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|       3 | 🎯  Analyser les manifestes de charge de travail avec KubeLinter                          | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|       4 | 🎯  Épingler les charges de travail aux digests d'images approuvés                        | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### Monitoring, Logging and Runtime Security

|   Index | Nom                                                       | Difficulté   | Pratique                                                                                                               |
|---------|-----------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Examen des événements d'audit pour l'accès aux secrets | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|       2 | 🎯  Détecter un processus d'exécution suspect              | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|       3 | 🎯  Appliquer l'immuabilité des conteneurs à l'exécution   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|       4 | 🎯  Enquêter sur une activité API non autorisée            | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 3. [Examen blanc CKS 02](https://labex.io/fr/courses/cks-practice-exam-02)

Un second examen blanc indépendant de type CKS, composé de 20 défis de sécurité Kubernetes couvrant les domaines officiels du CKS à travers divers scénarios de sécurité opérationnelle.

[Commencer le Cours](https://labex.io/fr/courses/cks-practice-exam-02) · Labs: 20

#### Cluster Setup

|   Index | Nom                                                                | Difficulté   | Pratique                                                                                                                  |
|---------|--------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Refuser l'accès de la charge de travail aux métadonnées du nœud | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|       2 | 🎯  Examen des conclusions CIS pour l'exposition du Kubelet         | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|       3 | 🎯  Réémettre le TLS pour une route Ingress scindée                 | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### Cluster Hardening

|   Index | Nom                                                         | Difficulté   | Pratique                                                                                                               |
|---------|-------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Définir la portée d'un rôle d'opérateur d'espace de noms | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|       2 | 🎯  Contenir un jeton ServiceAccount ayant fuité             | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|       3 | 🎯  Bloquer l'escalade via le proxy de l'API Server          | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### System Hardening

|   Index | Nom                                                       | Difficulté   | Pratique                                                                                                                 |
|---------|-----------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Désactiver un service de débogage hôte                 | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|       2 | 🎯  Restreindre les permissions du collecteur de logs hôte | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### Minimize Microservice Vulnerabilities

|   Index | Nom                                                                 | Difficulté   | Pratique                                                                                                                   |
|---------|---------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Appliquer les limites de sécurité des Pods pour les locataires   | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|       2 | 🎯  Rotation et restriction des secrets d'application                | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|       3 | 🎯  Isoler la sortie (egress) d'un locataire avec des exceptions DNS | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|       4 | 🎯  Supprimer le cache HostPath d'un Pod Web                         | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### Supply Chain Security

|   Index | Nom                                              | Difficulté   | Pratique                                                                                                            |
|---------|--------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Appliquer des registres d'images de confiance | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|       2 | 🎯  Valider un manifeste de version signé         | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|       3 | 🎯  Supprimer les secrets de build d'une image    | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|       4 | 🎯  Analyser la sortie Helm avec KubeLinter       | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### Monitoring, Logging and Runtime Security

|   Index | Nom                                                                 | Difficulté   | Pratique                                                                                                            |
|---------|---------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Restaurer une politique à partir de preuves d'audit              | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|       2 | 🎯  Mise en quarantaine d'une charge de travail émettant des signaux | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|       3 | 🎯  Détecter la dérive de fichiers au moment de l'exécution          | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|       4 | 🎯  Contenir un jeton de tâche compromis                             | Débutant     | [Commencer le Défi](https://labex.io/fr/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## À propos de LabEx

[LabEx](https://labex.io) est une plateforme d'apprentissage interactive et pratique dédiée au codage et à la technologie. Elle combine des laboratoires, une assistance IA et des machines virtuelles pour offrir une expérience d'apprentissage pratique sans vidéo. Avec une approche stricte 'Apprendre en Faisant', des environnements en ligne interactifs dans le navigateur avec des vérifications automatisées étape par étape, une organisation structurée du contenu avec le système basé sur l'Arbre de Compétences, et une ressource d'apprentissage croissante de 30 Arbres de Compétences et plus de 6 000 Laboratoires, [LabEx](https://labex.io) offre une éducation pratique complète. La plateforme comprend l'assistant d'apprentissage Labby, construit sur les derniers modèles d'IA, offrant une expérience d'apprentissage conversationnelle.

