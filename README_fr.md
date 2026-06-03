# Formation CKS Parcours de Préparation à la Certification

## Langues

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/fr/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Commencer-le-Parcours-whitesmoke?style=for-the-badge)](https://labex.io/fr/learn/cks)

Préparez-vous à l'examen Certified Kubernetes Security Specialist (CKS) grâce à un parcours structuré et orienté pratique. Ce plan met l'accent sur durcissement de cluster, durcissement système, réduction des vulnérabilités des microservices, sécurité de la chaîne d'approvisionnement, surveillance, journalisation et sécurité à l'exécution dans Kubernetes, les tâches en mode performance au style CKS et des scénarios réalistes. Des cours CKS, des labs et des examens blancs seront ajoutés progressivement.

**Cours**: 2 · **Labs**: 40

## Cours

### 1. [Examen blanc CKS 01](https://labex.io/fr/courses/cks-practice-exam-01)

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

### 2. [Examen blanc CKS 02](https://labex.io/fr/courses/cks-practice-exam-02)

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

