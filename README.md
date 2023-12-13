Time Management

Увеличивать скорость разработки. DevOps-инженер благодаря автоматизации и интеграции процессов позволяет сократить время, необходимое для запуска новых функций или исправления ошибок, и сделать процесс разработки более гибким и быстрым.
Улучшать сотрудничество и коммуникации. DevOps-инженер снимает барьеры между разработчиками и операционными командами. 
Улучшать качества продукта. DevOps-инженер обнаруживает и исправляет ошибки, снижает риски сбоев и инцидентов, связанных с человеческим фактором, повышает надёжность системы в целом.
Сокращение затрат и оптимизация ресурсов. DevOps стремится к автоматизации и оптимизации процессов разработки и развёртывания, что позволяет сократить издержки и использование ресурсов, таких как время и оборудование.

https://www.youtube.com/@KirillSemaev/videos

Открытое собеседование https://www.youtube.com/watch?v=QXiCTmwAzCc&t=734s

https://slurm.io/devops-upgrade?utm_medium=article&utm_source=habr&utm_campaign=roadmap

https://habr.com/ru/companies/slurm/articles/773618/
Автоматизация + оптимизация

## 1. Железо
```
  CPU
  RAM
  HDD/SSD/NVMe включая PCI-e
  Сетевые карты и железо
  Видео-карты + PCI-e
  Пользовательский I/O
```

## 2. Язык программирования (определяемся Python/Go/Ruby + SQL)
```
  +инструменты, библиотеки, фреймворки
  
  https://slurm.io/course-python-for-ops?utm_medium=article&utm_source=habr&utm_campaign=roadmap
  https://slurm.io/go-for-ops?utm_medium=article&utm_source=habr&utm_campaign=roadmap
  
  «Python и Go хороши для начала, Java — сложнее, придётся сильно углубиться. Нужно знать, какие типы там есть, как с ними работать, какой синтаксис у языка, как правильно применить линтеры, чтобы они не мешали разработчикам. Хороший вариант — знать best practices по языкам и по паттернам безопасности и кода»
```

## 3. ОС - Ubuntu
```
  Создавать и редактировать файлы
  Запускать программы, создавать и настраивать сервисы (например, в Systemd)
  Управлять пользователями, группами и правами доступа
  Устанавливать ПО из репозиториев, производить сборку и компиляцию, в т.ч. ядер
  Делать обновления и бэкапы
  Настраивать сетевые соединения и фаерволы
  Мониторить процессы
  Автоматизировать рутину, писать скрипты на Bash

  «Нужно чётко понять, насколько человек разбирается в сетях, в линуксовом ядре, в том, как работает память и процессы. Ещё важно, какие команды он знает и как их применяет. Я должен быть уверен, что человек в Linux не вводит каждую команду в обнимку с гуглом»

  https://slurm.io/linux-admin-base
  https://slurm.io/linux-mega-course
```

## 4. Терминал
```
  vim
  bash
    process monitoring
    perfomance monitoring
    networking tools
    text manipulation
```

## 5. Контроль версий
```
  git
    github
    gitlab (затронем)
    bitbucket (затронем)
      Обязательно понимать отличия разных систем

  git diff
  git add
  git commit
  git log
  git reset
  git branch
  git merge
  git rebase
  git cherry-pick
  git stash
  git push
  git fetch
  git pull
  git remote

  Визуалочка https://learngitbranching.js.org/?locale=ru_RU
  https://slurm.io/git
  Дока https://www.atlassian.com/ru/git/tutorials/comparing-workflows/feature-branch-workflow

  DevOps-инженер должен не только разбираться в коммитах, тегах и ветках, но и понимать workflow — набор процессов, процедур и подходов, которые команда разработки использует в своих проектах и, в частности, как работает в Git

Создавать репозитории, организовывать к ним доступ для разных типов пользователей.
  Решать сложные кейсы по слиянию веток и разрешению конфликтов слияния.
  Иметь представление, что такое CI/CD (а ещё лучше — разбираться) и как в этом задействован Git
```

## 6. Ставим и изучаем
```
  Reverse proxy
  Forward proxy
  Firewall
  Nginx
  Tomcat
  Apache
  Chaching Server
  Load Balancer
```

## 7. Контейнеризация
```  
  Docker
    Знать абстракции и команды Docker и Docker Compose (один из плагинов Docker).
    Уметь собирать свои образы контейнеров.
    Знать, что под капотом у Docker.
    Запускать контейнеры в Kubernetes.
    Писать Dockerfile, знать ключевые инструкции и их применение.
    Работать с образами и реестрами образов.
    Знать о существующих альтернативах и иметь общее представление об их отличиях от Docker’а
    
    Тесты https://github.com/slurmio/devopscases
    Best practices https://docs.docker.com/develop/develop-images/dockerfile_best-practices/
```

## 8. Cloud Providers
```  
  Яндекс.Облако
  AWS - через VPN (организовать)
```

## 9. Сеть, защита и протоколы
```
  HTTP/HTTPS
  SSL/TLS
  FTP/SFTP
  DNS
  SSH

  Модель OSI
  Email
    White/Grey Listing
    SMTP
    IMAP
    POP3
    DMARC
    SPF
    Domain Keys
```

## 10. Serverless
```
  Яндекс.Облако
  AWS
```

## 11. Провиженинг инфраструктуры
```  
  Terraform
```

## 12. Управление конфигурациями
```
  Ansible
    Знать основные примитивы (плейбуки, модули, плагины).
    Знать, что такое идемпотентность.
    Уметь читать и писать плейбуки.
    Уметь работать с модулями, ролями и плагинами.
  Puppet
  Chef
```

## 13. CI/CD tools
```
  Gitlab CI
  GitHub Actions
  Jenkins
  TeamCity (?)
  
  ввод в тему https://www.atlassian.com/ru/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment
  видео-курс https://slurm.io/gitlab-ci-cd?utm_medium=article&utm_source=habr&utm_campaign=roadmap
  jenkins https://slurm.io/jenkins-course?utm_medium=article&utm_source=habr&utm_campaign=roadmap
```

## 14. Secret Management
```
  Vault
  Sealed Secrets (?)
  Облачные ништяки
  SOPS (?)
```

## 15. Мониторинг инфраструктуры
```
  Zabbix
  Prometeus
  Grafana
  
  PromQL
  
  Алертинг
  
  Blackbox & Whitebox
  4 golden signals https://www.youtube.com/watch?v=Q_fKb0nrfCg
  предназначение RED и USE
  
  прометеус видеокурс https://slurm.io/prometheus?utm_medium=article&utm_source=habr&utm_campaign=roadmap
  графана https://slurm.io/monitoring-grafana?utm_medium=article&utm_source=habr&utm_campaign=roadmap
  мониторинг и логирование k8s https://slurm.io/monitoring?utm_medium=article&utm_source=habr&utm_campaign=roadmap
```

## 16. Application monitoring
```
  Jaeger
  New Relic
  Datadog
  AppDynamics
  OpenTelemetry
```

## 17. Управление логами
```
  Elastic Stack
  Loki
  Graylog (?)
```

## 18. Оркестрация
```
  kubernetes
    Kubespray
    Helm-чарты
  Apache Kafka
  AWS ECS/ЯО
  
  https://kubernetes.io/
  
  База
    Знаете компоненты и абстракции Kubernetes.
    Понимаете, как устроен и работает кластер.
    Можете поднять кластер с помощью одного из готовых инструментов (например, Kubespray).
    Знаете, как реализованы сетевые абстракции в K8s.
    Умеете создавать Helm-чарты и темплейтировать приложение.
    Знаете, как подключать систему хранения данных.
    Можете автоматизировать работу с сертификатами.
    Понимаете, как строить пайплайны доставки приложения в кластер Kubernetes.
  Продвинутый
    Настраивать аутентификацию пользователей в кластере.
    Работать с сетевыми плагинами для Kubernetes.
    Настраивать безопасность кластера.
    Понимать, как работают компоненты Kubernetes под капотом.
    Создавать собственные операторы.
    Понимать, как работает автоскейлинг приложений в кластере.
    Делать резервное копирование кластера.
    Реализовывать Blue-Green, Canary deployment.
    Использовать Open Policy Agent.
    Выстраивать service mesh. 
  Специализации
    администратора кластера;
    разработчика;
    архитектора;
    специалиста по мониторингу;
    специалиста по безопасности.
    
  Навигатор курсов https://slurm.io/kubernetes-navigator?utm_medium=article&utm_source=habr&utm_campaign=roadmap

  База https://slurm.io/kubernetes-baza?utm_medium=article&utm_source=habr&utm_campaign=roadmap
  Для разрабов https://slurm.io/kubernetes-for-developers?utm_medium=article&utm_source=habr&utm_campaign=roadmap
  Вебинары https://www.youtube.com/playlist?list=PL8D2P0ruohOA4Y9LQoTttfSgsRwUGWpu6
  Для разрабов https://www.youtube.com/playlist?list=PL8D2P0ruohOBSA_CDqJLflJ8FLJNe26K-
  Погружение https://slurm.io/kubernetes-megapotok?utm_medium=article&utm_source=habr&utm_campaign=roadmap
```

## 19. Artifact Management
```
  Artifactory
  Nexus (?)
```

## 20. GitOps
```
  ArgoCD
  FluxCD
```

## 21. Service Mesh
```
  Istio
  Consul
```

## 22. Cloud Design Patterns
```
  Availability
  Data Management
  Design and Implementation
  Management and Monitoring
  slurm.io (https://slurm.io/kubernetes-baza?utm_source=vk&utm_medium=social&utm_campaign=kubernetes-baza&utm_content=post_8-12-2023&utm_term=i_odmin)
```