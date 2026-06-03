# Обучение CKS Путь подготовки к сертификации

## Языки

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<a href="https://labex.io/ru/learn/cks"><img width="128px" src="https://file.labex.io/path/dzeGx0xsrUuR.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Начать-путь-whitesmoke?style=for-the-badge)](https://labex.io/ru/learn/cks)

Готовьтесь к экзамену Certified Kubernetes Security Specialist (CKS) по структурированной практической программе. Акцент на усиление кластера, усиление системы, минимизация уязвимостей микросервисов, безопасность цепочки поставок, мониторинг, логирование и безопасность выполнения в Kubernetes, практических заданиях в стиле CKS и сценариях из практики. Курсы CKS, лаборатории и пробные экзамены будут добавляться постепенно.

**Курсы**: 2 · **Лаборатории**: 40

## Курсы

### 1. [Практический экзамен CKS 01](https://labex.io/ru/courses/cks-practice-exam-01)

Практический экзамен CKS с 20 независимыми заданиями по безопасности Kubernetes, охватывающими настройку кластера, его усиление, защиту системы, устранение уязвимостей в микросервисах, безопасность цепочки поставок и защиту среды выполнения.

[Начать курс](https://labex.io/ru/courses/cks-practice-exam-01) · Лаборатории: 20

#### Cluster Setup

|   Индекс | Название                                                         | Сложность   | Практика                                                                                                                      |
|----------|------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Ограничение трафика пространства имен с помощью NetworkPolicy | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01) |
|        2 | 🎯  Публикация консоли администратора через TLS Ingress           | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01)     |
|        3 | 🎯  Проверка бинарных файлов Kubernetes перед развертыванием      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01)  |

#### Cluster Hardening

|   Индекс | Название                                                                       | Сложность   | Практика                                                                                                                    |
|----------|--------------------------------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Ограничение прав чрезмерно привилегированного ClusterRoleBinding            | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01) |
|        2 | 🎯  Отключение автоматического монтирования токенов ServiceAccount по умолчанию | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01) |
|        3 | 🎯  Ограничение доступа к API для Incident Reader                               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01)            |

#### System Hardening

|   Индекс | Название                                          | Сложность   | Практика                                                                                                                  |
|----------|---------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Применение профиля AppArmor к рабочей нагрузке | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01) |
|        2 | 🎯  Установка локального профиля Seccomp           | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01)           |

#### Minimize Microservice Vulnerabilities

|   Индекс | Название                                                                  | Сложность   | Практика                                                                                                             |
|----------|---------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Принудительное применение профиля безопасности Pod Security Restricted | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01)      |
|        2 | 🎯  Защита секретов с помощью проецируемых файлов                          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01) |
|        3 | 🎯  Усиление контекста безопасности среды выполнения                       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01)    |
|        4 | 🎯  Изоляция рискованного sidecar-контейнера                               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01)     |

#### Supply Chain Security

|   Индекс | Название                                                         | Сложность   | Практика                                                                                                                |
|----------|------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Создание минимального одобренного образа                      | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01)          |
|        2 | 🎯  Проверка SBOM и контрольных сумм                              | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01)       |
|        3 | 🎯  Сканирование манифестов рабочих нагрузок с помощью KubeLinter | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01) |
|        4 | 🎯  Привязка рабочих нагрузок к утвержденным дайджестам образов   | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01) |

#### Monitoring, Logging and Runtime Security

|   Индекс | Название                                                                     | Сложность   | Практика                                                                                                              |
|----------|------------------------------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Анализ событий аудита для выявления доступа к секретам                    | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01) |
|        2 | 🎯  Обнаружение подозрительного процесса во время выполнения                  | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01)   |
|        3 | 🎯  Принудительное использование неизменяемых контейнеров во время выполнения | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01)  |
|        4 | 🎯  Расследование несанкционированной активности API                          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01) |

### 2. [Практический экзамен CKS 02](https://labex.io/ru/courses/cks-practice-exam-02)

Второй независимый практический экзамен в стиле CKS, включающий 20 задач по безопасности Kubernetes, которые охватывают все ключевые области CKS через различные сценарии операционной безопасности.

[Начать курс](https://labex.io/ru/courses/cks-practice-exam-02) · Лаборатории: 20

#### Cluster Setup

|   Индекс | Название                                                    | Сложность   | Практика                                                                                                                 |
|----------|-------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Запрет доступа рабочей нагрузки к метаданным узла        | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02)    |
|        2 | 🎯  Анализ результатов CIS для выявления уязвимостей Kubelet | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02) |
|        3 | 🎯  Перевыпуск TLS для разделенного маршрута Ingress         | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02)    |

#### Cluster Hardening

|   Индекс | Название                                                | Сложность   | Практика                                                                                                              |
|----------|---------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Ограничение прав оператора пространства имен         | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02)       |
|        2 | 🎯  Изоляция скомпрометированного токена ServiceAccount  | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02) |
|        3 | 🎯  Блокировка эскалации через прокси-сервер API-сервера | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02)     |

#### System Hardening

|   Индекс | Название                                         | Сложность   | Практика                                                                                                                |
|----------|--------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Отключение отладочной службы хоста            | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02)            |
|        2 | 🎯  Ограничение прав доступа сборщика логов хоста | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02) |

#### Minimize Microservice Vulnerabilities

|   Индекс | Название                                                           | Сложность   | Практика                                                                                                                  |
|----------|--------------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Применение границ безопасности Pod для арендатора               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02)      |
|        2 | 🎯  Ротация и ограничение секретов приложения                       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02)  |
|        3 | 🎯  Изоляция исходящего трафика арендатора с помощью исключений DNS | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02) |
|        4 | 🎯  Удаление кэша hostPath из веб-пода                              | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02)      |

#### Supply Chain Security

|   Индекс | Название                                                    | Сложность   | Практика                                                                                                           |
|----------|-------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Принудительное использование доверенных реестров образов | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02)   |
|        2 | 🎯  Проверка подписанного манифеста релиза                   | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02) |
|        3 | 🎯  Удаление секретов сборки из образа                       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02) |
|        4 | 🎯  Сканирование вывода Helm с помощью KubeLinter            | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02)   |

#### Monitoring, Logging and Runtime Security

|   Индекс | Название                                                                      | Сложность   | Практика                                                                                                           |
|----------|-------------------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Восстановление политики на основе данных аудита                            | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02) |
|        2 | 🎯  Изоляция подозрительной рабочей нагрузки (Quarantine a Beaconing Workload) | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02)    |
|        3 | 🎯  Обнаружение отклонений файлов во время выполнения                          | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02)          |
|        4 | 🎯  Изоляция скомпрометированного токена задания                               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02)    |

## О LabEx

[LabEx](https://labex.io) - это интерактивная практическая обучающая платформа, посвященная программированию и технологиям. Она объединяет лаборатории, ИИ-помощь и виртуальные машины для обеспечения практического обучения без видео. Со строгим подходом 'Учись делая', интерактивными онлайн-средами в браузере с автоматизированными пошаговыми проверками, структурированной организацией контента с системой на основе Дерева Навыков, и растущим учебным ресурсом из 30 Деревьев Навыков и более 6,000 Лабораторий, [LabEx](https://labex.io) предлагает всестороннее практическое образование. Платформа включает ассистента обучения Labby, построенного на последних моделях ИИ, обеспечивающего разговорный опыт обучения.

