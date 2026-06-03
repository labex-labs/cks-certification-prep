# Treinamento CKS Trilha de Preparação para Certificação

## Idiomas

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/pt/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Iniciar-Trilha-whitesmoke?style=for-the-badge)](https://labex.io/pt/learn/cks)

Prepare-se para o exame Certified Kubernetes Security Specialist (CKS) com um percurso de aprendizagem estruturado e prático. O foco está em endurecimento de cluster, endurecimento de sistema, minimização de vulnerabilidades em microserviços, segurança da cadeia de suprimentos, monitoramento, logging e segurança em runtime no Kubernetes, tarefas baseadas em desempenho ao estilo CKS e cenários do mundo real. Cursos CKS, laboratórios e exames simulados serão adicionados ao longo do tempo.

**Cursos**: 2 · **Labs**: 40

## Cursos

### 1. [Exame Prático CKS 01](https://labex.io/pt/courses/cks-practice-exam-01)

Um exame prático e prático de CKS com 20 desafios independentes de segurança em Kubernetes, abrangendo configuração de cluster, endurecimento de cluster, endurecimento de sistema, redução de vulnerabilidades em microsserviços, segurança da cadeia de suprimentos e segurança em tempo de execução.

[Iniciar Curso](https://labex.io/pt/courses/cks-practice-exam-01) · Labs: 20

#### Cluster Setup

|   Índice | Nome                                                     | Dificuldade   | Prática                                                                                                                      |
|----------|----------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Restringir o tráfego do Namespace com NetworkPolicy   | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|        2 | 🎯  Publicar um Console de Administração com TLS Ingress  | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|        3 | 🎯  Verificar Binários do Kubernetes Antes da Implantação | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### Cluster Hardening

|   Índice | Nome                                                         | Dificuldade   | Prática                                                                                                                    |
|----------|--------------------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Reduzir uma ClusterRoleBinding com privilégios excessivos | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|        2 | 🎯  Desativar montagens de token de ServiceAccount padrão     | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|        3 | 🎯  Limitar o Acesso à API do Leitor de Incidentes            | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### System Hardening

|   Índice | Nome                                                   | Dificuldade   | Prática                                                                                                                  |
|----------|--------------------------------------------------------|---------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Aplicar um Perfil AppArmor em uma Carga de Trabalho | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|        2 | 🎯  Instalar um Perfil Seccomp Local                    | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### Minimize Microservice Vulnerabilities

|   Índice | Nome                                             | Dificuldade   | Prática                                                                                                             |
|----------|--------------------------------------------------|---------------|---------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Impor Segurança de Pod Restrita               | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|        2 | 🎯  Proteger Segredos com Arquivos Projetados     | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|        3 | 🎯  Endurecer um Contexto de Segurança de Runtime | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|        4 | 🎯  Isolar um Sidecar de Risco                    | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### Supply Chain Security

|   Índice | Nome                                                         | Dificuldade   | Prática                                                                                                                |
|----------|--------------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Construir uma Imagem Mínima Aprovada                      | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|        2 | 🎯  Verificar SBOM e Evidências de Checksum                   | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|        3 | 🎯  Analisar Manifestos de Carga de Trabalho com o KubeLinter | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|        4 | 🎯  Fixar Cargas de Trabalho a Digests de Imagem Aprovados    | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### Monitoring, Logging and Runtime Security

|   Índice | Nome                                                    | Dificuldade   | Prática                                                                                                              |
|----------|---------------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Analisar Eventos de Auditoria para Acesso a Segredos | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|        2 | 🎯  Detectar um Processo de Runtime Suspeito             | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|        3 | 🎯  Impor Contêineres de Runtime Imutáveis               | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|        4 | 🎯  Investigar Atividade Não Autorizada na API           | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 2. [Exame Prático CKS 02](https://labex.io/pt/courses/cks-practice-exam-02)

Um segundo exame prático independente no estilo CKS, com 20 desafios de segurança em Kubernetes que abrangem os domínios públicos do CKS por meio de diferentes cenários de segurança operacional.

[Iniciar Curso](https://labex.io/pt/courses/cks-practice-exam-02) · Labs: 20

#### Cluster Setup

|   Índice | Nome                                                     | Dificuldade   | Prática                                                                                                                 |
|----------|----------------------------------------------------------|---------------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Negar Acesso da Carga de Trabalho aos Metadados do Nó | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|        2 | 🎯  Revisar Descobertas do CIS para Exposição do Kubelet  | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|        3 | 🎯  Reemitir TLS para uma Rota de Ingress Dividida        | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### Cluster Hardening

|   Índice | Nome                                                     | Dificuldade   | Prática                                                                                                              |
|----------|----------------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Definir o Escopo de uma Role de Operador de Namespace | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|        2 | 🎯  Conter um Token de ServiceAccount Vazado              | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|        3 | 🎯  Bloquear a Escalação de Proxy do Servidor de API      | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### System Hardening

|   Índice | Nome                                                | Dificuldade   | Prática                                                                                                                |
|----------|-----------------------------------------------------|---------------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Desativar um Serviço de Depuração do Host        | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|        2 | 🎯  Restringir Permissões do Coletor de Logs do Host | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### Minimize Microservice Vulnerabilities

|   Índice | Nome                                                     | Dificuldade   | Prática                                                                                                                  |
|----------|----------------------------------------------------------|---------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Aplicar Limites de Segurança de Pod para Locatários   | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|        2 | 🎯  Rotacionar e Restringir Segredos da Aplicação         | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|        3 | 🎯  Isolar a Saída (Egress) do Tenant com Exceções de DNS | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|        4 | 🎯  Remover Cache HostPath de um Pod Web                  | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### Supply Chain Security

|   Índice | Nome                                           | Dificuldade   | Prática                                                                                                           |
|----------|------------------------------------------------|---------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Impor Registros de Imagem Confiáveis        | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|        2 | 🎯  Validar um Manifesto de Lançamento Assinado | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|        3 | 🎯  Remover segredos de build de uma imagem     | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|        4 | 🎯  Analisar a saída do Helm com o KubeLinter   | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### Monitoring, Logging and Runtime Security

|   Índice | Nome                                                      | Dificuldade   | Prática                                                                                                           |
|----------|-----------------------------------------------------------|---------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Restaurar Política a partir de Evidências de Auditoria | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|        2 | 🎯  Quarentena de uma Carga de Trabalho com Beaconing      | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|        3 | 🎯  Detectar Desvio de Arquivo em Tempo de Execução        | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|        4 | 🎯  Conter um Token de Job Comprometido                    | Iniciante     | [Iniciar Desafio](https://labex.io/pt/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## Sobre LabEx

[LabEx](https://labex.io) é uma plataforma de aprendizagem interativa e prática dedicada à programação e tecnologia. Combina laboratórios, assistência de IA e máquinas virtuais para fornecer uma experiência de aprendizagem prática sem vídeos. Com uma abordagem rigorosa de 'Aprender Fazendo', ambientes online interativos no navegador com verificações automatizadas passo a passo, organização de conteúdo estruturada com o sistema baseado em Árvore de Habilidades, e um recurso de aprendizagem crescente de 30 Árvores de Habilidades e mais de 6.000 Laboratórios, [LabEx](https://labex.io) oferece educação prática integral. A plataforma inclui o assistente de aprendizagem Labby, construído sobre os últimos modelos de IA, fornecendo uma experiência de aprendizagem conversacional.

