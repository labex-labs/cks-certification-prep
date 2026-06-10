# Formación CKS Certification Prep Path

## Idiomas

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/es/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Iniciar-Ruta-whitesmoke?style=for-the-badge)](https://labex.io/es/learn/cks)

Prepárate para el examen Certified Kubernetes Security Specialist (CKS) con una ruta de aprendizaje estructurada y práctica. Este plan se centra en endurecimiento de clústeres, endurecimiento del sistema, minimización de vulnerabilidades en microservicios, seguridad de la cadena de suministro, y monitorización, registro y seguridad en tiempo de ejecución en Kubernetes, tareas basadas en rendimiento al estilo CKS y escenarios reales. Los cursos CKS, laboratorios y exámenes simulados se irán incorporando para reforzar habilidades alineadas con los objetivos CKS.

**Cursos**: 3 · **Laboratorios**: 85

## Cursos

### 1. [Preparación para CKS](https://labex.io/es/courses/cks-prep)

Un curso de preparación para CKS ideal para principiantes, que incluye 45 experimentos guiados de seguridad en Kubernetes, organizados desde los fundamentos de seguridad hasta la configuración de clústeres, endurecimiento, seguridad de cargas de trabajo, cadena de suministro, auditoría e investigación en tiempo de ejecución.

[Iniciar Curso](https://labex.io/es/courses/cks-prep) · Laboratorios: 45

#### Fundamentos de seguridad para Kubernetes

|   Índice | Nombre                                                            | Dificultad   | Práctica                                                                                                      |
|----------|-------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Mapeo de límites de seguridad en Kubernetes                    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|        2 | 🧩  Recopilación de evidencia de seguridad con kubectl             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|        3 | 🧩  Revisión de Namespaces y Aislamiento de Inquilinos             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|        4 | 🧩  Inspeccionar sujetos y permisos de RBAC                        | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|        5 | 🧩  Inspeccionar el comportamiento de los tokens de ServiceAccount | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|        6 | 🧩  Aplicar estándares de seguridad de Pods                        | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### Seguridad en la configuración del clúster

|   Índice | Nombre                                                                       | Dificultad   | Práctica                                                                                                             |
|----------|------------------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Restringir el tráfico del Namespace con NetworkPolicy                     | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|        2 | 🧩  Permitir DNS a través de una política de denegación de salida por defecto | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|        3 | 🧩  Publicar Ingress con TLS                                                  | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|        4 | 🧩  Denegar el acceso de la carga de trabajo a los metadatos del nodo         | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|        5 | 🧩  Verificar binarios de Kubernetes                                          | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|        6 | 🧩  Revisar hallazgos de CIS con kube-bench                                   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|        7 | 🧩  Verificar la preparación de la admisión y la seguridad de los Pods        | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### Endurecimiento del clúster

|   Índice | Nombre                                                               | Dificultad   | Práctica                                                                                                           |
|----------|----------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Minimizar los permisos de un Role                                 | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|        2 | 🧩  Reducir un ClusterRoleBinding con privilegios excesivos           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|        3 | 🧩  Deshabilitar el montaje automático de tokens de ServiceAccount    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|        4 | 🧩  Limitar el alcance de un rol de operador en un espacio de nombres | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|        5 | 🧩  Bloqueo de escalada mediante proxy del servidor API               | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|        6 | 🧩  Contener un token de ServiceAccount filtrado                      | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|        7 | 🧩  Auditar el acceso a recursos confidenciales                       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### Endurecimiento del sistema y de los nodos

|   Índice | Nombre                                                                   | Dificultad   | Práctica                                                                                                                 |
|----------|--------------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Inspeccionar la superficie de ataque del host de forma segura         | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|        2 | 🧩  Deshabilitar un servicio de depuración del host                       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|        3 | 🧩  Revisión de la exposición del kubelet                                 | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|        4 | 🧩  Revisar la aplicación de perfiles de AppArmor en una carga de trabajo | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|        5 | 🧩  Instalar un perfil de seccomp local                                   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|        6 | 🧩  Eliminar el acceso hostPath de una carga de trabajo                   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### Seguridad de cargas de trabajo y microservicios

|   Índice | Nombre                                                    | Dificultad   | Práctica                                                                                                        |
|----------|-----------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Endurecer el contexto de seguridad de un Pod           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|        2 | 🧩  Eliminar capacidades de Linux                          | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|        3 | 🧩  Ejecutar contenedores como usuario no root             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|        4 | 🧩  Proteger secretos con archivos proyectados             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|        5 | 🧩  Rotación y restricción de secretos de aplicación       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|        6 | 🧩  Aislar un límite de sidecar de riesgo                  | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|        7 | 🧩  Aplicar contenedores de tiempo de ejecución inmutables | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|        8 | 🧩  Poner en cuarentena una carga de trabajo sospechosa    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### Seguridad de la cadena de suministro

|   Índice | Nombre                                                      | Dificultad   | Práctica                                                                                                        |
|----------|-------------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Construir una imagen mínima aprobada                     | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|        2 | 🧩  Analizar manifiestos de carga de trabajo con kube-linter | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|        3 | 🧩  Analizar la salida de Helm con kube-linter               | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|        4 | 🧩  Verificar SBOM y evidencia de suma de comprobación       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|        5 | 🧩  Aplicar registros de imágenes de confianza               | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|        6 | 🧩  Eliminar secretos de compilación de una imagen           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### Monitoreo, auditoría y seguridad en tiempo de ejecución

|   Índice | Nombre                                                       | Dificultad   | Práctica                                                                                                     |
|----------|--------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Revisar eventos de auditoría para el acceso a Secretos    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|        2 | 🧩  Investigar actividad no autorizada en la API              | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|        3 | 🧩  Detectar procesos de tiempo de ejecución sospechosos      | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|        4 | 🧩  Detectar desviación de archivos en tiempo de ejecución    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|        5 | 🧩  Restaurar una política a partir de evidencia de auditoría | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

### 2. [Examen de práctica CKS 01](https://labex.io/es/courses/cks-practice-exam-01)

Un examen de práctica práctico de CKS con 20 desafíos independientes de seguridad de Kubernetes que cubren la configuración del clúster, el endurecimiento del clúster, el endurecimiento del sistema, la reducción de vulnerabilidades en microservicios, la seguridad de la cadena de suministro y la seguridad en tiempo de ejecución.

[Iniciar Curso](https://labex.io/es/courses/cks-practice-exam-01) · Laboratorios: 20

#### Configuración del clúster

|   Índice | Nombre                                                         | Dificultad   | Práctica                                                                                                                     |
|----------|----------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Restringir el tráfico del Namespace con NetworkPolicy       | Principiante | [Iniciar Desafío](https://labex.io/es/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|        2 | 🎯  Publicar una consola de administración con Ingress TLS      | Principiante | [Iniciar Desafío](https://labex.io/es/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|        3 | 🎯  Verificar binarios de Kubernetes antes de la implementación | Principiante | [Iniciar Desafío](https://labex.io/es/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### Fortalecimiento del clúster

|   Índice | Nombre                                                                        | Dificultad   | Práctica                                                                                                                   |
|----------|-------------------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Reducir un ClusterRoleBinding con privilegios excesivos                    | Principiante | [Iniciar Desafío](https://labex.io/es/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|        2 | 🎯  Deshabilitar el montaje automático de tokens de ServiceAccount por defecto | Principiante | [Iniciar Desafío](https://labex.io/es/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|        3 | 🎯  Limitar el acceso a la API del lector de incidentes                        | Principiante | [Iniciar Desafío](https://labex.io/es/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### Fortalecimiento del sistema

|   Índice | Nombre                                                  | Dificultad   | Práctica                                                                                                                 |
|----------|---------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Aplicar un perfil de AppArmor a una carga de trabajo | Principiante | [Iniciar Desafío](https://labex.io/es/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|        2 | 🎯  Instalar un perfil de Seccomp local                  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### Minimización de vulnerabilidades en microservicios

|   Índice | Nombre                                                       | Dificultad   | Práctica                                                                                                            |
|----------|--------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Aplicar seguridad de Pods restringida                     | Principiante | [Iniciar Desafío](https://labex.io/es/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|        2 | 🎯  Proteger secretos con archivos proyectados                | Principiante | [Iniciar Desafío](https://labex.io/es/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|        3 | 🎯  Endurecer un contexto de seguridad en tiempo de ejecución | Principiante | [Iniciar Desafío](https://labex.io/es/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|        4 | 🎯  Aislar un límite de sidecar de riesgo                     | Principiante | [Iniciar Desafío](https://labex.io/es/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### Seguridad de la cadena de suministro

|   Índice | Nombre                                                                | Dificultad   | Práctica                                                                                                               |
|----------|-----------------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Construir una imagen mínima aprobada                               | Principiante | [Iniciar Desafío](https://labex.io/es/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|        2 | 🎯  Verificar SBOM y evidencia de suma de comprobación                 | Principiante | [Iniciar Desafío](https://labex.io/es/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|        3 | 🎯  Analizar manifiestos de carga de trabajo con KubeLinter            | Principiante | [Iniciar Desafío](https://labex.io/es/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|        4 | 🎯  Anclar cargas de trabajo a resúmenes (digests) de imagen aprobados | Principiante | [Iniciar Desafío](https://labex.io/es/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### Monitoreo, registro y seguridad en tiempo de ejecución

|   Índice | Nombre                                                    | Dificultad   | Práctica                                                                                                             |
|----------|-----------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Revisar eventos de auditoría para acceso a Secret      | Principiante | [Iniciar Desafío](https://labex.io/es/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|        2 | 🎯  Detectar un proceso de tiempo de ejecución sospechoso  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|        3 | 🎯  Aplicar contenedores de tiempo de ejecución inmutables | Principiante | [Iniciar Desafío](https://labex.io/es/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|        4 | 🎯  Investigar actividad no autorizada en la API           | Principiante | [Iniciar Desafío](https://labex.io/es/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 3. [Examen de práctica CKS 02](https://labex.io/es/courses/cks-practice-exam-02)

Un segundo examen de práctica independiente al estilo CKS con 20 desafíos de seguridad de Kubernetes que cubren los dominios públicos de CKS a través de diferentes escenarios de seguridad operativa.

[Iniciar Curso](https://labex.io/es/courses/cks-practice-exam-02) · Laboratorios: 20

#### Configuración del clúster

|   Índice | Nombre                                                               | Dificultad   | Práctica                                                                                                                |
|----------|----------------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Denegar el acceso de la carga de trabajo a los metadatos del nodo | Principiante | [Iniciar Desafío](https://labex.io/es/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|        2 | 🎯  Revisar hallazgos CIS para exposición de Kubelet                  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|        3 | 🎯  Reemitir TLS para una ruta Ingress dividida                       | Principiante | [Iniciar Desafío](https://labex.io/es/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### Fortalecimiento del clúster

|   Índice | Nombre                                                                      | Dificultad   | Práctica                                                                                                             |
|----------|-----------------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Delimitar el rol de un operador de Namespace                             | Principiante | [Iniciar Desafío](https://labex.io/es/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|        2 | 🎯  Contener un token de ServiceAccount filtrado                             | Principiante | [Iniciar Desafío](https://labex.io/es/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|        3 | 🎯  Bloqueo de la escalada de privilegios mediante el proxy del servidor API | Principiante | [Iniciar Desafío](https://labex.io/es/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### Fortalecimiento del sistema

|   Índice | Nombre                                                          | Dificultad   | Práctica                                                                                                               |
|----------|-----------------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Deshabilitar un servicio de depuración del host              | Principiante | [Iniciar Desafío](https://labex.io/es/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|        2 | 🎯  Restringir los permisos del recolector de registros del host | Principiante | [Iniciar Desafío](https://labex.io/es/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### Minimización de vulnerabilidades en microservicios

|   Índice | Nombre                                                            | Dificultad   | Práctica                                                                                                                 |
|----------|-------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Aplicar límites de seguridad de Pods para inquilinos           | Principiante | [Iniciar Desafío](https://labex.io/es/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|        2 | 🎯  Rotar y restringir secretos de la aplicación                   | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|        3 | 🎯  Aislar la salida (egress) del inquilino con excepciones de DNS | Principiante | [Iniciar Desafío](https://labex.io/es/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|        4 | 🎯  Eliminar la caché de tipo HostPath de un Pod web               | Principiante | [Iniciar Desafío](https://labex.io/es/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### Seguridad de la cadena de suministro

|   Índice | Nombre                                            | Dificultad   | Práctica                                                                                                          |
|----------|---------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Aplicar registros de imágenes de confianza     | Principiante | [Iniciar Desafío](https://labex.io/es/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|        2 | 🎯  Validar un manifiesto de lanzamiento firmado   | Principiante | [Iniciar Desafío](https://labex.io/es/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|        3 | 🎯  Eliminar secretos de compilación de una imagen | Principiante | [Iniciar Desafío](https://labex.io/es/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|        4 | 🎯  Analizar la salida de Helm con KubeLinter      | Principiante | [Iniciar Desafío](https://labex.io/es/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### Monitoreo, registro y seguridad en tiempo de ejecución

|   Índice | Nombre                                                    | Dificultad   | Práctica                                                                                                          |
|----------|-----------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Restaurar política a partir de evidencia de auditoría  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|        2 | 🎯  Cuarentena de una carga de trabajo con beaconing       | Principiante | [Iniciar Desafío](https://labex.io/es/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|        3 | 🎯  Detectar desviación de archivos en tiempo de ejecución | Principiante | [Iniciar Desafío](https://labex.io/es/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|        4 | 🎯  Contener un token de trabajo comprometido              | Principiante | [Iniciar Desafío](https://labex.io/es/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## Acerca de LabEx

[LabEx](https://labex.io) es una plataforma de aprendizaje interactiva y práctica dedicada a la programación y la tecnología. Combina laboratorios, asistencia de IA y máquinas virtuales para proporcionar una experiencia de aprendizaje práctica sin videos. Con un enfoque estricto de 'Aprender Haciendo', entornos en línea interactivos dentro del navegador con verificaciones paso a paso automatizadas, organización de contenido estructurada con el sistema basado en Árbol de Habilidades, y un recurso de aprendizaje en crecimiento de 30 Árboles de Habilidades y más de 6,000 Laboratorios, LabEx ofrece educación práctica integral. La plataforma incluye al asistente de aprendizaje Labby, construido sobre los últimos modelos de IA, que proporciona una experiencia de aprendizaje conversacional.

