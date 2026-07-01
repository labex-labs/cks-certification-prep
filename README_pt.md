# Treinamento CKS Certification Prep Path

**Idiomas:** [English](README.md) · [简体中文](README_zh.md) · [日本語](README_ja.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/pt/learn/cks">
    <img width="128" src="https://file.labex.io/path/dzeGx0xsrUuR.png" alt="Treinamento CKS">
  </a>
</p>

Prepare-se para o exame Certified Kubernetes Security Specialist (CKS) com um percurso de aprendizagem estruturado e prático. O foco está em endurecimento de cluster, endurecimento de sistema, minimização de vulnerabilidades em microserviços, segurança da cadeia de suprimentos, monitoramento, logging e segurança em runtime no Kubernetes, tarefas baseadas em desempenho ao estilo CKS e cenários do mundo real. Cursos CKS, laboratórios e exames simulados serão adicionados ao longo do tempo.

[Iniciar trilha no LabEx](https://labex.io/pt/learn/cks)

**Cursos**: 3 · **Labs**: 85

## Cursos

### 1. [Exame Prático CKS 01](https://labex.io/pt/courses/cks-practice-exam-01)

[![Exame Prático CKS 01](https://course-cover.labex.io/cks-practice-exam-01.png?lang=pt)](https://labex.io/pt/courses/cks-practice-exam-01)

Um exame prático e prático de CKS com 20 desafios independentes de segurança em Kubernetes, abrangendo configuração de cluster, endurecimento de cluster, endurecimento de sistema, redução de vulnerabilidades em microsserviços, segurança da cadeia de suprimentos e segurança em tempo de execução.

[Iniciar Curso](https://labex.io/pt/courses/cks-practice-exam-01) · Labs: 20

#### Cluster Setup

|   Índice | Nome                                                  | Dificuldade   | Prática                                                                                                                      |
|----------|-------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------------------------|
|        1 | Restringir o tráfego do Namespace com NetworkPolicy   | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|        2 | Publicar um Console de Administração com TLS Ingress  | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|        3 | Verificar Binários do Kubernetes Antes da Implantação | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### Cluster Hardening

|   Índice | Nome                                                      | Dificuldade   | Prática                                                                                                                    |
|----------|-----------------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------------|
|        1 | Reduzir uma ClusterRoleBinding com privilégios excessivos | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|        2 | Desativar montagens de token de ServiceAccount padrão     | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|        3 | Limitar o Acesso à API do Leitor de Incidentes            | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### System Hardening

|   Índice | Nome                                                | Dificuldade   | Prática                                                                                                                  |
|----------|-----------------------------------------------------|---------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | Aplicar um Perfil AppArmor em uma Carga de Trabalho | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|        2 | Instalar um Perfil Seccomp Local                    | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### Minimize Microservice Vulnerabilities

|   Índice | Nome                                          | Dificuldade   | Prática                                                                                                             |
|----------|-----------------------------------------------|---------------|---------------------------------------------------------------------------------------------------------------------|
|        1 | Impor Segurança de Pod Restrita               | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|        2 | Proteger Segredos com Arquivos Projetados     | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|        3 | Endurecer um Contexto de Segurança de Runtime | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|        4 | Isolar um Sidecar de Risco                    | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### Supply Chain Security

|   Índice | Nome                                                      | Dificuldade   | Prática                                                                                                                |
|----------|-----------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------------------|
|        1 | Construir uma Imagem Mínima Aprovada                      | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|        2 | Verificar SBOM e Evidências de Checksum                   | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|        3 | Analisar Manifestos de Carga de Trabalho com o KubeLinter | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|        4 | Fixar Cargas de Trabalho a Digests de Imagem Aprovados    | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### Monitoring, Logging and Runtime Security

|   Índice | Nome                                                 | Dificuldade   | Prática                                                                                                              |
|----------|------------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | Analisar Eventos de Auditoria para Acesso a Segredos | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|        2 | Detectar um Processo de Runtime Suspeito             | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|        3 | Impor Contêineres de Runtime Imutáveis               | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|        4 | Investigar Atividade Não Autorizada na API           | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 2. [Exame Prático CKS 02](https://labex.io/pt/courses/cks-practice-exam-02)

[![Exame Prático CKS 02](https://course-cover.labex.io/cks-practice-exam-02.png?lang=pt)](https://labex.io/pt/courses/cks-practice-exam-02)

Um segundo exame prático independente no estilo CKS, com 20 desafios de segurança em Kubernetes que abrangem os domínios públicos do CKS por meio de diferentes cenários de segurança operacional.

[Iniciar Curso](https://labex.io/pt/courses/cks-practice-exam-02) · Labs: 20

#### Cluster Setup

|   Índice | Nome                                                  | Dificuldade   | Prática                                                                                                                 |
|----------|-------------------------------------------------------|---------------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | Negar Acesso da Carga de Trabalho aos Metadados do Nó | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|        2 | Revisar Descobertas do CIS para Exposição do Kubelet  | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|        3 | Reemitir TLS para uma Rota de Ingress Dividida        | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### Cluster Hardening

|   Índice | Nome                                                  | Dificuldade   | Prática                                                                                                              |
|----------|-------------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | Definir o Escopo de uma Role de Operador de Namespace | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|        2 | Conter um Token de ServiceAccount Vazado              | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|        3 | Bloquear a Escalação de Proxy do Servidor de API      | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### System Hardening

|   Índice | Nome                                             | Dificuldade   | Prática                                                                                                                |
|----------|--------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------------------|
|        1 | Desativar um Serviço de Depuração do Host        | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|        2 | Restringir Permissões do Coletor de Logs do Host | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### Minimize Microservice Vulnerabilities

|   Índice | Nome                                                  | Dificuldade   | Prática                                                                                                                  |
|----------|-------------------------------------------------------|---------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | Aplicar Limites de Segurança de Pod para Locatários   | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|        2 | Rotacionar e Restringir Segredos da Aplicação         | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|        3 | Isolar a Saída (Egress) do Tenant com Exceções de DNS | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|        4 | Remover Cache HostPath de um Pod Web                  | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### Supply Chain Security

|   Índice | Nome                                        | Dificuldade   | Prática                                                                                                           |
|----------|---------------------------------------------|---------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | Impor Registros de Imagem Confiáveis        | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|        2 | Validar um Manifesto de Lançamento Assinado | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|        3 | Remover segredos de build de uma imagem     | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|        4 | Analisar a saída do Helm com o KubeLinter   | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### Monitoring, Logging and Runtime Security

|   Índice | Nome                                                   | Dificuldade   | Prática                                                                                                           |
|----------|--------------------------------------------------------|---------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | Restaurar Política a partir de Evidências de Auditoria | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|        2 | Quarentena de uma Carga de Trabalho com Beaconing      | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|        3 | Detectar Desvio de Arquivo em Tempo de Execução        | Intermediário | [Iniciar Desafio](https://labex.io/pt/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|        4 | Conter um Token de Job Comprometido                    | Avançado      | [Iniciar Desafio](https://labex.io/pt/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

### 3. [Preparatório para CKS](https://labex.io/pt/courses/cks-prep)

[![Preparatório para CKS](https://course-cover.labex.io/cks-prep.png?lang=pt)](https://labex.io/pt/courses/cks-prep)

Um curso preparatório para CKS ideal para iniciantes, com 45 experimentos guiados de segurança em Kubernetes, organizados desde os fundamentos de segurança até a configuração de clusters, endurecimento (hardening), segurança de cargas de trabalho, cadeia de suprimentos, auditoria e investigação em tempo de execução.

[Iniciar Curso](https://labex.io/pt/courses/cks-prep) · Labs: 45

#### Security Foundations for Kubernetes

|   Índice | Nome                                                   | Dificuldade   | Prática                                                                                               |
|----------|--------------------------------------------------------|---------------|-------------------------------------------------------------------------------------------------------|
|        1 | Mapear Limites de Segurança do Kubernetes              | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|        2 | Coleta de Evidências de Segurança com kubectl          | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|        3 | Revisão de Namespaces e Isolamento de Tenants          | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|        4 | Inspecionar Assuntos e Permissões de RBAC              | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|        5 | Inspecionar o Comportamento do Token de ServiceAccount | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|        6 | Aplicar Padrões de Segurança de Pods                   | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### Cluster Setup Security

|   Índice | Nome                                                  | Dificuldade   | Prática                                                                                                      |
|----------|-------------------------------------------------------|---------------|--------------------------------------------------------------------------------------------------------------|
|        1 | Restringir o tráfego de Namespace com NetworkPolicy   | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|        2 | Permitir DNS através de Egress Default-Deny           | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|        3 | Publicar Ingress com TLS                              | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|        4 | Negar Acesso da Carga de Trabalho aos Metadados do Nó | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|        5 | Verificar Binários do Kubernetes                      | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|        6 | Revisar descobertas do CIS com o kube-bench           | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|        7 | Verificar a Prontidão de Admissão e Segurança de Pods | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### Cluster Hardening

|   Índice | Nome                                                     | Dificuldade   | Prática                                                                                                    |
|----------|----------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------|
|        1 | Minimizar as Permissões de uma Role                      | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|        2 | Reduzir um ClusterRoleBinding com privilégios excessivos | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|        3 | Desativar Montagens de Token de ServiceAccount Padrão    | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|        4 | Delimitar uma Role de Operador de Namespace              | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|        5 | Bloqueio de Escalação via Proxy do Servidor de API       | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|        6 | Conter um Token de ServiceAccount Vazado                 | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|        7 | Auditar Acesso a Recursos Sensíveis                      | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### System and Node Hardening

|   Índice | Nome                                                            | Dificuldade   | Prática                                                                                                          |
|----------|-----------------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------------|
|        1 | Inspecione a Superfície de Ataque do Host com Segurança         | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|        2 | Desativar um serviço de depuração do host                       | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|        3 | Revisão da Exposição do Kubelet                                 | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|        4 | Revisar a Aplicação de Perfil AppArmor em uma Carga de Trabalho | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|        5 | Instalar um Perfil seccomp Local                                | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|        6 | Remover acesso HostPath de uma carga de trabalho                | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### Workload and Microservice Security

|   Índice | Nome                                                 | Dificuldade   | Prática                                                                                                 |
|----------|------------------------------------------------------|---------------|---------------------------------------------------------------------------------------------------------|
|        1 | Endurecer um Contexto de Segurança de Pod            | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|        2 | Remover Capabilities do Linux                        | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|        3 | Executar Containers como Não-Root                    | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|        4 | Proteger Segredos com Arquivos Projetados            | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|        5 | Rotacionar e Restringir Segredos da Aplicação        | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|        6 | Isolar um Limite de Sidecar de Risco                 | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|        7 | Impor Contêineres de Runtime Imutáveis               | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|        8 | Colocar uma Carga de Trabalho Suspeita em Quarentena | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### Supply Chain Security

|   Índice | Nome                                                       | Dificuldade   | Prática                                                                                                 |
|----------|------------------------------------------------------------|---------------|---------------------------------------------------------------------------------------------------------|
|        1 | Construir uma Imagem Mínima Aprovada                       | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|        2 | Analisar Manifestos de Carga de Trabalho com o kube-linter | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|        3 | Analisar a saída do Helm com o kube-linter                 | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|        4 | Verificar SBOM e Evidências de Checksum                    | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|        5 | Impor Registros de Imagem Confiáveis                       | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|        6 | Remover Segredos de Build de uma Imagem                    | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### Monitoring, Audit, and Runtime Security

|   Índice | Nome                                                   | Dificuldade   | Prática                                                                                              |
|----------|--------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------|
|        1 | Revisar Eventos de Auditoria para Acesso a Segredos    | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|        2 | Investigar Atividade Não Autorizada na API             | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|        3 | Detectar Processos de Runtime Suspeitos                | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|        4 | Detectar Desvio de Arquivo em Tempo de Execução        | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|        5 | Restaurar Política a partir de Evidências de Auditoria | Iniciante     | [Iniciar Lab](https://labex.io/pt/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

