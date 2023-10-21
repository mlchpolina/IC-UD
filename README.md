# Integrating-and-Deploying-Software-with-Containers
# Using Containers for Working with Data

## Полезные ссылки

- [Лекция 1. Микросервисы и контейнеры](#лекция-1-микросервисы-и-контейнеры)
- [Лекция 2. Docker](#лекция-2-docker)
- [Лекция 3. Введение в Kubernetes](#лекция-3-введение-в-kubernetes)
- [Лекция 4. Хранение данных и ресурсы](#лекция-4-хранение-данных-и-ресурсы)
- [Лекция 5. Сетевые абстракции Kubernetes](#лекция-5-сетевые-абстракции-kubernetes)
- [Лекция 6. Устройство кластера](#лекция-6-устройство-кластера)

## Текущая успеваемость
 [АДЭУ-201](https://docs.google.com/spreadsheets/d/1rldI1A9V3_WH9H8McTe3qNr6o0migXObak8nKQSQg-E/edit?usp=sharing)
 
## Лекция 1. Микросервисы и контейнеры

[МГПУ 02-09-23](/lectures/1%20-%20intro%20Применение%20контейнеров.pptx)

**Перед второй лекцией нужно установить Docker**

[установить Docker](https://docs.docker.com/get-docker/) на свой компьютер или виртуальную машину с Linux.

А так же использовать онлайн сервисы:

🔹 [Play with Docker](https://labs.play-with-docker.com/)

🔹 [Katacoda](https://www.katacoda.com/)

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

## Лекция 4. Хранение данных и ресурсы

🔹 [Рациональное использование ресурсов в Kubernetes](https://habr.com/ru/company/timeweb/blog/560670/)

## Лекция 5. Сетевые абстракции Kubernetes

🔹 [Configure Liveness, Readiness and Startup Probes](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/#configure-probes)

🔹 [iptables: How Kubernetes Services Direct Traffic to Pods](https://dustinspecker.com/posts/iptables-how-kubernetes-services-direct-traffic-to-pods/)

## Лекция 6. Устройство кластера

🔹 [Kubernetes is so Simple You Can Explore it with Curl](https://blog.tilt.dev/2021/03/18/kubernetes-is-so-simple.html)

🔹 [Как увеличить скорость реакции Kubernetes на отказ узлов кластера?](https://habr.com/ru/company/timeweb/blog/561084/)


## Практические работы

- `ПР 1`. [First Alpine Linux Containers](https://training.play-with-docker.com/ops-s1-hello/).
 
- `ПР 2`. [Docker for Beginners - Linux](https://training.play-with-docker.com/beginner-linux/).

- `ПР 4`.
   - [Swarm Mode Introduction for IT Pros](https://training.play-with-docker.com/ops-s1-swarm-intro/).

   - [Swarm mode introduction](https://training.play-with-docker.com/swarm-mode-intro/).

- `ПР 5`. [Application Containerization and Microservice Orchestration](https://training.play-with-docker.com/microservice-orchestration/).

- `ПР 6`. [Docker images deeper dive](https://training.play-with-docker.com/docker-images/).

- `ПР 7`. [Docker Orchestration Hands-on Lab](https://training.play-with-docker.com/orchestration-hol/).
  
- `ПР 9`. [workflow1-self-contained](https://github.com/BosenkoTM/using-docker-containers-for-data/tree/main/workflow1-self-contained).
    

## ТЕСТ 1.   

`14.10.2023`

[Контейнеры](https://forms.gle/2k3z94t1wUXqfj776)

## ТЕСТ 2.  
`25.11.2023`

[Оркестрация данных]()


## Семинары

Семинар `1`. `16/09/2023` [Установка Docker](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/1%20%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0%20DOCKER#1-%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-docker---ubuntu).

Семинар `2`. `16/09/2023` [Первый контейнер](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/2%20%D0%9F%D0%B5%D1%80%D0%B2%D1%8B%D0%B9%20%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80#%D0%BF%D0%B5%D1%80%D0%B2%D1%8B%D0%B9-%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80).

Семинар `3`. `16/09/2023` [Создание образа](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/3%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%B0#%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%B0).

Официальный контейнер [Ubuntu 14](https://github.com/dockerfile/ubuntu).
 - скачать репо `https://github.com/dockerfile/ubuntu.git`;
```
 git clone https://github.com/dockerfile/ubuntu.git
``` 
 - зайти в корневой каталог Ubuntu;
 - выполнить команду:

```
 sudo docker build .
```

 Проверяем наличие образа на ПК:
 ```
 sudo docker image ls
```

Семинар `4`. `23/09/2023` [Работа с файлами](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/4%20%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20%D1%84%D0%B0%D0%B9%D0%BB%D0%B0%D0%BC%D0%B8#%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%D1%81-%D1%84%D0%B0%D0%B9%D0%BB%D0%B0%D0%BC%D0%B8---%D1%82%D0%B5%D0%BE%D1%80%D0%B8%D1%8F).

Создание [TG-BOT 2022](https://github.com/BosenkoTM/tg_bot_2022.git).

Семинар `5`. `23/09/2023` [Переменные окружения, логи и порты](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/5%20%D0%9F%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5%20%D0%BE%D0%BA%D1%80%D1%83%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%2C%20%D0%BB%D0%BE%D0%B3%D0%B8%20%D0%B8%20%D0%BF%D0%BE%D1%80%D1%82%D1%8B#%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5-%D0%BE%D0%BA%D1%80%D1%83%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F).

Семинар `6`. [Введение в сети](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/6%20%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%20%D1%81%D0%B5%D1%82%D0%B8#%D1%81%D0%B5%D1%82%D0%B8-%D0%B2-docker).

Семинар `7`. [Веб-приложение в контейнерах](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/7%20%D0%92%D0%B5%D0%B1-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%20%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80%D0%B0%D1%85#%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%D0%B2%D0%B5%D0%B1-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%D1%81-%D0%BE%D0%B4%D0%BD%D0%B8%D0%BC-%D0%B8-%D0%B4%D0%B2%D1%83%D0%BC%D1%8F-%D0%B2%D0%B5%D0%B1-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%B0%D0%BC%D0%B8).

Семинар `8`. [YAML и docker-compose](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/8%20YAML%20%D0%B8%20docker-compose#yaml).

Семинар `9`. [Веб-приложение в docker-compose](https://github.com/BosenkoTM/IC-UD_Practice/tree/main/9%20%D0%92%D0%B5%D0%B1-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%20docker-compose#%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D0%B8-docker-compose).

Семинар `10`. `07/10/2023` [Kubernetes for Beginners](https://training.play-with-kubernetes.com/kubernetes-workshop/).

Семинар `11`. `14/10/2023` 
- [Установка minikube лекция-инструкция](/lectures/4%20Установка%20minikube%20лекция-инструкция.pdf).
- [.yaml](/practice/practice_for_lecture_4/setup).
- Задание:
1. Установить minikube. Создайте модуль pod под управлением `Nginx`.
2. Провести тестирование `minikube` и `kubectl`.
3. Развернуть многоузловой кластер `minikube`.
4. Установить `Kind`. Создайте модуль под управлением `Nginx`.
5. Провести тестирование `Kind`.

Семинар `12`. `k8s_1 Общие команды kubectl`
1. Написать приложение на Python + Flask.
2. Упаковать приложение в контейнер Docker.
3. Разместить контейнер в репозитории Docker hub.  
4. Сделать Deployment и Service в кластере k8s.

[Пример решения задания](https://github.com/BosenkoTM/IC-UD/assets/38157538/762a25a9-d96c-4a2b-abfd-b764db6dd78d)

## Основная литература
1. Иан Милл, Эйдан Хобсон Сейерс Docker на практике / пер. с англ. Д. А. Беликов. – М.: ДМК Пресс, 2020. – 516 с. [скачать](https://disk.yandex.ru/d/mrcntkbTLAfHPQ).
2. Моуэт Э. Использование Docker / пер. с англ. А. В. Снастина; науч. ред. А. А. Маркелов. – М.: ДМК Пресс, 2017. – 354 с. [скачать](https://disk.yandex.ru/d/mrcntkbTLAfHPQ).
3. Liz Rice Container Security: Fundamental Technology Concepts that Protect Containerized Applications. O'Reilly Media, 2020, 175 с.[скачать](https://disk.yandex.ru/d/mrcntkbTLAfHPQ).
4. Jordan Lioy Software Containers: The Complete Guide to Virtualization Technology. Create, Use and Deploy Scalable Software with Docker and Kubernetes. 2023, 673с.[скачать](https://disk.yandex.ru/d/mrcntkbTLAfHPQ).
5. Play with Docker Classroom [link](https://training.play-with-docker.com/).
6. Container Training [link](https://container.training/)
7. Certified Kubernetes Application Developer (CKAD) Exam Success Guide [скачать](https://disk.yandex.ru/i/BNsogUl6SAa5Kg).
8. [Linux-контейнеры: изоляция как технологический прорыв](https://habr.com/ru/company/redhatrussia/blog/352052/).
9. [Namespaces](https://habr.com/ru/company/selectel/blog/279281/).
10. [Cgroups](https://habr.com/ru/company/selectel/blog/303190/).
11. [Capabilities](https://habr.com/ru/company/otus/blog/471802/).
12. [Могут ли контейнеры быть безопасными?](https://habr.com/ru/company/oleg-bunin/blog/480630/).
13. [Митап "Stateful-приложения в 2020 году"](https://www.youtube.com/watch?v=ykIh4-616Ic&list=PL8D2P0ruohODzihD0D0FZXkVHXtXbb6w3&index=4&ab_channel=HighLoadChannel).
14. [Jobs & Cronjobs in Kubernetes Cluster](https://medium.com/avmconsulting-blog/jobs-cronjobs-in-kubernetes-cluster-d0e872e3c8c8).
15. [Tоп-10 PromQL запросов для мониторинга Kubernetes](https://habr.com/ru/company/timeweb/blog/562374/).

