# Integrating-and-Deploying-Software-with-Containers
38.03.05_Бизнес-информатика_Аналитика данных и эффективное управление(Семестр: 8)

Практика и домашние задания находятся в соответсвующих директориях.

## Полезные ссылки

- [Лекция 1. Микросервисы и контейнеры](#лекция-1-микросервисы-и-контейнеры)
- [Лекция 2. Docker](#лекция-2-docker)
- [Лекция 3. Введение в Kubernetes](#лекция-3-введение-в-kubernetes)
- [Лекция 4. Хранение данных и ресурсы](#лекция-4-хранение-данных-и-ресурсы)
- [Лекция 5. Сетевые абстракции Kubernetes](#лекция-5-сетевые-абстракции-kubernetes)
- [Лекция 6. Устройство кластера](#лекция-6-устройство-кластера)
- [Лекция 7. Продвинутые абстракции](#лекция-7-продвинутые-абстракции)
- [Лекция 8. Деплой тестового приложения в кластер, CI/CD](#лекция-8-деплой-тестового-приложения-в-кластер)

## Лекция 1. Микросервисы и контейнеры

[МГПУ 01-09-23]()

**Перед второй лекцией нужно установить Docker**

Вы можете [установить Docker](https://docs.docker.com/get-docker/) на свой компьютер или виртуальную машину с Linux.

А так же использовать онлайн сервисы, чтобы немедленно приступить к обучению:

🔹 [Play with Docker](https://labs.play-with-docker.com/)

🔹 [Katacoda](https://www.katacoda.com/)

**Паттерны проектирования**

🔹 [The Twelwe-Factor App](https://12factor.net/ru/)

🔹 [GRASP](https://ru.wikipedia.org/wiki/GRASP)

🔹 Рекомендую книгу - [Чистая архитектура. Искусство разработки программного обеспечения](https://www.piter.com/product/chistaya-arhitektura-iskusstvo-razrabotki-programmnogo-obespecheniya)

**Механизмы контейнеризации**

🔹 [Linux-контейнеры: изоляция как технологический прорыв](https://habr.com/ru/company/redhatrussia/blog/352052/)

🔹 [Namespaces](https://habr.com/ru/company/selectel/blog/279281/)

🔹 [Cgroups](https://habr.com/ru/company/selectel/blog/303190/)

🔹 [Capabilities](https://habr.com/ru/company/otus/blog/471802/)

🔹 [Могут ли контейнеры быть безопасными?](https://habr.com/ru/company/oleg-bunin/blog/480630/)

## Лекция 2. Docker

**Docker**

🔹 [Сеть контейнеров — это не сложно](https://habr.com/ru/company/timeweb/blog/558612/)

🔹 [Overview of Docker CLI](https://docs.docker.com/engine/reference/run/)

🔹 [10 команд для Docker, без которых вам не обойтись](https://tproger.ru/translations/top-10-docker-commands/)

🔹 [Как начать использовать Docker в своих проектах](https://tproger.ru/translations/how-to-start-using-docker/)

🔹 [50 вопросов по Docker, которые задают на собеседованиях, и ответы на них](https://habr.com/ru/company/southbridge/blog/528206/)

**Dockerfile**

🔹 [20 лучших практик по работе с Dockerfile](https://habr.com/ru/company/domclick/blog/546922/)

🔹 [ENTRYPOINT vs CMD: назад к основам](https://habr.com/ru/company/southbridge/blog/329138/)

🔹 [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)

🔹 [Use multi-stage builds](https://docs.docker.com/develop/develop-images/multistage-build/)

🔹 [Best practices for writing Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/#add-or-copy%23add-or-copy)

**Docker Compose**

🔹 [Overview of docker-compose CLI](https://docs.docker.com/compose/reference/)

🔹 [Quickstart: Compose and Django](https://docs.docker.com/samples/django/)

🔹 [Compose file version 3 reference](https://docs.docker.com/compose/compose-file/compose-file-v3/)

🔹 [Compose file version 2 reference](https://docs.docker.com/compose/compose-file/compose-file-v2/)

## Лекция 3. Введение в Kubernetes

>Уважаемые студенты, просьба по возможности до начала занятия поставить себе утилиту для работы с Kubernetes – kubectl.
>Это можно сделать по инструкциям из официальной документации для вашей ОС.
>https://kubernetes.io/docs/tasks/tools/install-kubectl/

Делаем работу с kubectl удобнее:

🔹 [kubectl auto-complition](https://kubernetes.io/docs/tasks/tools/included/optional-kubectl-configs-bash-linux/)

🔹 [kubectl aliases](https://github.com/adterskov/kubectl-aliases)

🔹 [kubens - быстрый способ переключения между namespaces в kubectl](https://github.com/ahmetb/kubectx/)

🔹 [kubecolor - раскрашивает вывод kubectl](https://github.com/dty1er/kubecolor/)

Как получить в своё распоряжение полноценный кластер Kubernetes?

**Онлайн сервисы, чтобы немедленно приступить к обучению**

🔹 [Play with Kubernetes](https://labs.play-with-k8s.com/)

🔹 [Katacoda](https://www.katacoda.com/)

**Запустить локальный кластер Kubernetes**

🔹 [Minikube](https://kubernetes.io/ru/docs/tasks/tools/install-minikube/)

🔹 [Minishift (OpenShift)](https://www.okd.io/minishift/)

🔹 [KiND](https://kind.sigs.k8s.io/docs/user/quick-start/)

🔹 [Docker Desktop](https://docs.docker.com/desktop/kubernetes/)

**Запустить кластер Kubernetes в облаке**

🔹 [Google Cloud Platform (300$ на счет за регистрацию)](https://cloud.google.com/free)

🔹 Российские облачные провайдеры Yandex и MCS (mail.ru) периодически дают бонусы на счет, например за прохождение вебинаров

**Установить кластер самостоятельно**

🔹 [Установка в помощью kubeadm](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/)

🔹 [Установка с помощью kubesparay](https://kubernetes.io/docs/setup/production-environment/tools/kubespray/)

## Лекция 4. Хранение данных и ресурсы

🔹 [Рациональное использование ресурсов в Kubernetes](https://habr.com/ru/company/timeweb/blog/560670/)


## Лекция 5. Сетевые абстракции Kubernetes

🔹 [Configure Liveness, Readiness and Startup Probes](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/#configure-probes)

🔹 [iptables: How Kubernetes Services Direct Traffic to Pods](https://dustinspecker.com/posts/iptables-how-kubernetes-services-direct-traffic-to-pods/)

## Лекция 6. Устройство кластера

🔹 [Kubernetes is so Simple You Can Explore it with Curl](https://blog.tilt.dev/2021/03/18/kubernetes-is-so-simple.html)

🔹 [Как увеличить скорость реакции Kubernetes на отказ узлов кластера?](https://habr.com/ru/company/timeweb/blog/561084/)

## Лекция 7. Продвинутые абстракции

🔹 [Митап "Stateful-приложения в 2020 году"](https://www.youtube.com/watch?v=ykIh4-616Ic&list=PL8D2P0ruohODzihD0D0FZXkVHXtXbb6w3&index=4&ab_channel=HighLoadChannel)

🔹 [Jobs & Cronjobs in Kubernetes Cluster](https://medium.com/avmconsulting-blog/jobs-cronjobs-in-kubernetes-cluster-d0e872e3c8c8)

🔹 [Tоп-10 PromQL запросов для мониторинга Kubernetes](https://habr.com/ru/company/timeweb/blog/562374/)

## Лекция 8. Деплой тестового приложения в кластер

🔹 [Антипаттерны деплоя в Kubernetes. Часть 1](https://habr.com/ru/company/timeweb/blog/557320/)

🔹 [Антипаттерны деплоя в Kubernetes. Часть 2](https://habr.com/ru/company/timeweb/blog/560772/)

🔹 [Антипаттерны деплоя в Kubernetes. Часть 3](https://habr.com/ru/company/timeweb/blog/561570/)

🔹 [ПРОЕКТ «ФЕНИКС». КАК DEVOPS УСТРАНЯЕТ ХАОС И УСКОРЯЕТ РАЗВИТИЕ КОМПАНИИ](https://bombora.ru/book/64983/#.)

## Практические работы

- `Семинар 1`. [First Alpine Linux Containers](https://training.play-with-docker.com/ops-s1-hello/)
 
- `Семинар 2`. [Docker for Beginners - Linux](https://training.play-with-docker.com/beginner-linux/)

- `Семинар 3`. [Node.js with SQL Server on Docker](https://training.play-with-docker.com/node-sql-server-docker/).

- `Семинар 4`.
   - [Swarm Mode Introduction for IT Pros](https://training.play-with-docker.com/ops-s1-swarm-intro/)

   - [Swarm mode introduction](https://training.play-with-docker.com/swarm-mode-intro/)

- `Семинар 5`. [Application Containerization and Microservice Orchestration](https://training.play-with-docker.com/microservice-orchestration/)

- `Семинар 6`. [Docker images deeper dive](https://training.play-with-docker.com/docker-images/)

- `Семинар 7`. [Docker Orchestration Hands-on Lab](https://training.play-with-docker.com/orchestration-hol/)

- `Семинар 8`. [Docker images deeper dive](https://training.play-with-docker.com/docker-images/)
    

## ТЕСТ 1.   

`06.11.2023`

[]()

## ТЕСТ 2.  
`24.11.2023`

[]()

## Основная литература

1. Иан Милл, Эйдан Хобсон Сейерс Docker на практике / пер. с англ. Д. А. Беликов. – М.: ДМК Пресс, 2020. – 516 с. [скачать](https://disk.yandex.ru/d/mrcntkbTLAfHPQ)
   
2. Liz Rice Container Security: Fundamental Technology Concepts that Protect Containerized Applications. O'Reilly Media, 2020, 175 с.[скачать](https://disk.yandex.ru/d/mrcntkbTLAfHPQ)
   
3. Jordan Lioy Software Containers: The Complete Guide to Virtualization Technology. Create, Use and Deploy Scalable Software with Docker and Kubernetes. 2023, 673с.[скачать](https://disk.yandex.ru/d/mrcntkbTLAfHPQ)
  
4. Play with Docker Classroom [link](https://training.play-with-docker.com/)
   
5. Container Training [link](https://container.training/)
