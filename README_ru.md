# Обучение CKS Certification Prep Path

**Языки:** [English](README.md) · [简体中文](README_zh.md) · [日本語](README_ja.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ru/learn/cks">
    <img width="128" src="https://file.labex.io/path/dzeGx0xsrUuR.png" alt="Обучение CKS">
  </a>
</p>

Готовьтесь к экзамену Certified Kubernetes Security Specialist (CKS) по структурированной практической программе. Акцент на усиление кластера, усиление системы, минимизация уязвимостей микросервисов, безопасность цепочки поставок, мониторинг, логирование и безопасность выполнения в Kubernetes, практических заданиях в стиле CKS и сценариях из практики. Курсы CKS, лаборатории и пробные экзамены будут добавляться постепенно.

[Начать путь на LabEx](https://labex.io/ru/learn/cks)

**Курсы**: 3 · **Лаборатории**: 85

## Курсы

### 1. [Практический экзамен CKS 01](https://labex.io/ru/courses/cks-practice-exam-01)

[![Практический экзамен CKS 01](https://course-cover.labex.io/cks-practice-exam-01.png?lang=ru)](https://labex.io/ru/courses/cks-practice-exam-01)

Практический экзамен CKS с 20 независимыми заданиями по безопасности Kubernetes, охватывающими настройку кластера, его усиление, защиту системы, устранение уязвимостей в микросервисах, безопасность цепочки поставок и защиту среды выполнения.

[Начать Курс](https://labex.io/ru/courses/cks-practice-exam-01) · Лаборатории: 20

#### Cluster Setup

|   Индекс | Название                                                      | Сложность   | Практика                                                                                                                      |
|----------|---------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------|
|        1 | Ограничение трафика пространства имен с помощью NetworkPolicy | Средний     | [Начать испытание](https://labex.io/ru/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|        2 | Публикация консоли администратора через TLS Ingress           | Средний     | [Начать испытание](https://labex.io/ru/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|        3 | Проверка бинарных файлов Kubernetes перед развертыванием      | Средний     | [Начать испытание](https://labex.io/ru/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### Cluster Hardening

|   Индекс | Название                                                                    | Сложность   | Практика                                                                                                                    |
|----------|-----------------------------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------------|
|        1 | Ограничение прав чрезмерно привилегированного ClusterRoleBinding            | Средний     | [Начать испытание](https://labex.io/ru/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|        2 | Отключение автоматического монтирования токенов ServiceAccount по умолчанию | Средний     | [Начать испытание](https://labex.io/ru/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|        3 | Ограничение доступа к API для Incident Reader                               | Средний     | [Начать испытание](https://labex.io/ru/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### System Hardening

|   Индекс | Название                                       | Сложность   | Практика                                                                                                                  |
|----------|------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------|
|        1 | Применение профиля AppArmor к рабочей нагрузке | Продвинутый | [Начать испытание](https://labex.io/ru/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|        2 | Установка локального профиля Seccomp           | Продвинутый | [Начать испытание](https://labex.io/ru/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### Minimize Microservice Vulnerabilities

|   Индекс | Название                                                               | Сложность   | Практика                                                                                                             |
|----------|------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | Принудительное применение профиля безопасности Pod Security Restricted | Средний     | [Начать испытание](https://labex.io/ru/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|        2 | Защита секретов с помощью проецируемых файлов                          | Средний     | [Начать испытание](https://labex.io/ru/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|        3 | Усиление контекста безопасности среды выполнения                       | Средний     | [Начать испытание](https://labex.io/ru/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|        4 | Изоляция рискованного sidecar-контейнера                               | Продвинутый | [Начать испытание](https://labex.io/ru/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### Supply Chain Security

|   Индекс | Название                                                      | Сложность   | Практика                                                                                                                |
|----------|---------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | Создание минимального одобренного образа                      | Средний     | [Начать испытание](https://labex.io/ru/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|        2 | Проверка SBOM и контрольных сумм                              | Средний     | [Начать испытание](https://labex.io/ru/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|        3 | Сканирование манифестов рабочих нагрузок с помощью KubeLinter | Средний     | [Начать испытание](https://labex.io/ru/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|        4 | Привязка рабочих нагрузок к утвержденным дайджестам образов   | Продвинутый | [Начать испытание](https://labex.io/ru/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### Monitoring, Logging and Runtime Security

|   Индекс | Название                                                                  | Сложность   | Практика                                                                                                              |
|----------|---------------------------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | Анализ событий аудита для выявления доступа к секретам                    | Средний     | [Начать испытание](https://labex.io/ru/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|        2 | Обнаружение подозрительного процесса во время выполнения                  | Продвинутый | [Начать испытание](https://labex.io/ru/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|        3 | Принудительное использование неизменяемых контейнеров во время выполнения | Средний     | [Начать испытание](https://labex.io/ru/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|        4 | Расследование несанкционированной активности API                          | Продвинутый | [Начать испытание](https://labex.io/ru/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 2. [Практический экзамен CKS 02](https://labex.io/ru/courses/cks-practice-exam-02)

[![Практический экзамен CKS 02](https://course-cover.labex.io/cks-practice-exam-02.png?lang=ru)](https://labex.io/ru/courses/cks-practice-exam-02)

Второй независимый практический экзамен в стиле CKS, включающий 20 задач по безопасности Kubernetes, которые охватывают все ключевые области CKS через различные сценарии операционной безопасности.

[Начать Курс](https://labex.io/ru/courses/cks-practice-exam-02) · Лаборатории: 20

#### Cluster Setup

|   Индекс | Название                                                 | Сложность   | Практика                                                                                                                 |
|----------|----------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | Запрет доступа рабочей нагрузки к метаданным узла        | Средний     | [Начать испытание](https://labex.io/ru/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|        2 | Анализ результатов CIS для выявления уязвимостей Kubelet | Средний     | [Начать испытание](https://labex.io/ru/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|        3 | Перевыпуск TLS для разделенного маршрута Ingress         | Средний     | [Начать испытание](https://labex.io/ru/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### Cluster Hardening

|   Индекс | Название                                             | Сложность   | Практика                                                                                                              |
|----------|------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | Ограничение прав оператора пространства имен         | Средний     | [Начать испытание](https://labex.io/ru/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|        2 | Изоляция скомпрометированного токена ServiceAccount  | Продвинутый | [Начать испытание](https://labex.io/ru/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|        3 | Блокировка эскалации через прокси-сервер API-сервера | Продвинутый | [Начать испытание](https://labex.io/ru/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### System Hardening

|   Индекс | Название                                      | Сложность   | Практика                                                                                                                |
|----------|-----------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | Отключение отладочной службы хоста            | Средний     | [Начать испытание](https://labex.io/ru/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|        2 | Ограничение прав доступа сборщика логов хоста | Средний     | [Начать испытание](https://labex.io/ru/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### Minimize Microservice Vulnerabilities

|   Индекс | Название                                                        | Сложность   | Практика                                                                                                                  |
|----------|-----------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------|
|        1 | Применение границ безопасности Pod для арендатора               | Средний     | [Начать испытание](https://labex.io/ru/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|        2 | Ротация и ограничение секретов приложения                       | Средний     | [Начать испытание](https://labex.io/ru/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|        3 | Изоляция исходящего трафика арендатора с помощью исключений DNS | Продвинутый | [Начать испытание](https://labex.io/ru/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|        4 | Удаление кэша hostPath из веб-пода                              | Средний     | [Начать испытание](https://labex.io/ru/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### Supply Chain Security

|   Индекс | Название                                                 | Сложность   | Практика                                                                                                           |
|----------|----------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------|
|        1 | Принудительное использование доверенных реестров образов | Продвинутый | [Начать испытание](https://labex.io/ru/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|        2 | Проверка подписанного манифеста релиза                   | Средний     | [Начать испытание](https://labex.io/ru/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|        3 | Удаление секретов сборки из образа                       | Продвинутый | [Начать испытание](https://labex.io/ru/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|        4 | Сканирование вывода Helm с помощью KubeLinter            | Средний     | [Начать испытание](https://labex.io/ru/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### Monitoring, Logging and Runtime Security

|   Индекс | Название                                                                   | Сложность   | Практика                                                                                                           |
|----------|----------------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------|
|        1 | Восстановление политики на основе данных аудита                            | Средний     | [Начать испытание](https://labex.io/ru/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|        2 | Изоляция подозрительной рабочей нагрузки (Quarantine a Beaconing Workload) | Продвинутый | [Начать испытание](https://labex.io/ru/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|        3 | Обнаружение отклонений файлов во время выполнения                          | Средний     | [Начать испытание](https://labex.io/ru/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|        4 | Изоляция скомпрометированного токена задания                               | Продвинутый | [Начать испытание](https://labex.io/ru/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

### 3. [Подготовка к CKS](https://labex.io/ru/courses/cks-prep)

[![Подготовка к CKS](https://course-cover.labex.io/cks-prep.png?lang=ru)](https://labex.io/ru/courses/cks-prep)

Курс по подготовке к CKS для начинающих, включающий 45 практических лабораторных работ по безопасности Kubernetes. Программа охватывает всё: от основ безопасности и настройки кластера до защиты рабочих нагрузок, цепочек поставок, аудита и анализа инцидентов в среде выполнения.

[Начать Курс](https://labex.io/ru/courses/cks-prep) · Лаборатории: 45

#### Security Foundations for Kubernetes

|   Индекс | Название                                                          | Сложность   | Практика                                                                                                     |
|----------|-------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------|
|        1 | Отображение границ безопасности Kubernetes                        | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/map-kubernetes-security-boundaries-663929?course=cks-prep)     |
|        2 | Сбор доказательств безопасности с помощью kubectl                 | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep) |
|        3 | Обзор пространств имен и изоляции арендаторов                     | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep) |
|        4 | Изучение субъектов и прав доступа RBAC                            | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep)  |
|        5 | Изучение поведения токенов ServiceAccount                         | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep)  |
|        6 | Применение стандартов безопасности подов (Pod Security Standards) | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/apply-pod-security-standards-663906?course=cks-prep)           |

#### Cluster Setup Security

|   Индекс | Название                                                      | Сложность   | Практика                                                                                                            |
|----------|---------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------|
|        1 | Ограничение трафика пространства имен с помощью NetworkPolicy | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep) |
|        2 | Разрешение DNS при политике egress default-deny               | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep)         |
|        3 | Публикация Ingress с использованием TLS                       | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/publish-ingress-with-tls-663932?course=cks-prep)                      |
|        4 | Запрет доступа рабочих нагрузок к метаданным узла             | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep)         |
|        5 | Проверка бинарных файлов Kubernetes                           | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/verify-kubernetes-binaries-663948?course=cks-prep)                    |
|        6 | Анализ результатов CIS с помощью kube-bench                   | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep)           |
|        7 | Проверка готовности Admission и Pod Security                  | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep)    |

#### Cluster Hardening

|   Индекс | Название                                                                    | Сложность   | Практика                                                                                                          |
|----------|-----------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------|
|        1 | Минимизация прав доступа роли                                               | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/minimize-a-role-s-permissions-663930?course=cks-prep)               |
|        2 | Ограничение прав чрезмерно привилегированного ClusterRoleBinding            | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep) |
|        3 | Отключение автоматического монтирования токенов ServiceAccount по умолчанию | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep) |
|        4 | Ограничение прав оператора в пространстве имен                              | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/scope-a-namespace-operator-role-663947?course=cks-prep)             |
|        5 | Блокировка эскалации через прокси API-сервера                               | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/block-api-server-proxy-escalation-663908?course=cks-prep)           |
|        6 | Локализация скомпрометированного токена ServiceAccount                      | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep)       |
|        7 | Аудит доступа к конфиденциальным ресурсам                                   | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/audit-access-to-sensitive-resources-663907?course=cks-prep)         |

#### System and Node Hardening

|   Индекс | Название                                                  | Сложность   | Практика                                                                                                                |
|----------|-----------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | Безопасная проверка поверхности атаки хоста               | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/inspect-host-attack-surface-safely-663923?course=cks-prep)                |
|        2 | Отключение отладочной службы хоста                        | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/disable-a-host-debug-service-663916?course=cks-prep)                      |
|        3 | Анализ доступности kubelet                                | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/review-kubelet-exposure-663941?course=cks-prep)                           |
|        4 | Проверка применения профиля AppArmor для рабочей нагрузки | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep) |
|        5 | Установка локального профиля seccomp                      | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/install-a-local-seccomp-profile-663926?course=cks-prep)                   |
|        6 | Удаление доступа hostPath из рабочей нагрузки             | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep)            |

#### Workload and Microservice Security

|   Индекс | Название                                                                  | Сложность   | Практика                                                                                                       |
|----------|---------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------|
|        1 | Усиление контекста безопасности пода                                      | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/harden-a-pod-security-context-663922?course=cks-prep)            |
|        2 | Ограничение возможностей Linux (Linux Capabilities)                       | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/drop-linux-capabilities-663918?course=cks-prep)                  |
|        3 | Запуск контейнеров от имени пользователя без прав root                    | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/run-containers-as-non-root-663944?course=cks-prep)               |
|        4 | Защита секретов с помощью проецируемых файлов                             | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/protect-secrets-with-projected-files-663931?course=cks-prep)     |
|        5 | Ротация и ограничение доступа к секретам приложения                       | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep) |
|        6 | Изоляция рискованного sidecar-контейнера                                  | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep)         |
|        7 | Принудительное использование неизменяемых контейнеров во время выполнения | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/enforce-immutable-runtime-containers-663920?course=cks-prep)     |
|        8 | Карантин подозрительной рабочей нагрузки                                  | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/quarantine-a-suspicious-workload-663933?course=cks-prep)         |

#### Supply Chain Security

|   Индекс | Название                                                       | Сложность   | Практика                                                                                                       |
|----------|----------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------|
|        1 | Создание минимального одобренного образа                       | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/build-a-minimal-approved-image-663909?course=cks-prep)           |
|        2 | Сканирование манифестов рабочих нагрузок с помощью kube-linter | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep) |
|        3 | Сканирование вывода Helm с помощью kube-linter                 | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep)        |
|        4 | Проверка SBOM и контрольных сумм                               | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep)        |
|        5 | Принудительное использование доверенных реестров образов       | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/enforce-trusted-image-registries-663921?course=cks-prep)         |
|        6 | Удаление секретов сборки из образа                             | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/remove-build-secrets-from-an-image-663935?course=cks-prep)       |

#### Monitoring, Audit, and Runtime Security

|   Индекс | Название                                                 | Сложность   | Практика                                                                                                    |
|----------|----------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------|
|        1 | Анализ событий аудита для доступа к секретам             | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/review-audit-events-for-secret-access-663939?course=cks-prep) |
|        2 | Расследование несанкционированной активности API         | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/investigate-unauthorized-api-activity-663927?course=cks-prep) |
|        3 | Обнаружение подозрительных процессов во время выполнения | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/detect-suspicious-runtime-processes-663915?course=cks-prep)   |
|        4 | Обнаружение отклонений файлов во время выполнения        | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/detect-runtime-file-drift-663914?course=cks-prep)             |
|        5 | Восстановление политики на основе данных аудита          | Начинающий  | [Начать лабораторию](https://labex.io/ru/labs/restore-policy-from-audit-evidence-663937?course=cks-prep)    |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

