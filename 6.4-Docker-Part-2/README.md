# Homework task 6.4 - Docker. Part 2

**Student:** Menschikova E.D.

## Description

As part of the homework assignment I will set up a multi-container application using Docker Compose.

## Tehnologies used:

- Ubuntu Linux
- Docker
- Docker Compose
- Prometheus
- Pushgateway
- Grafana
- Git
- GitHub

## Completing the tasks:

- Task 1. Docker Compose
- Task 2. Creating a configuration
- Task 3. Prometheus
- Task 4. Pushgateway
- Task 5. Grafana
- Task 6. Launch settings
- Task 7. Work verification
- Task 8. Container stop

### Задание 1. Docker Compose

Docker Compose - это инструмент для управления многоконтейнерными приложениями Docker.
С его помощью можно описать необходимые сервисы, сети, тома и параметры запуска в 
одном YAML-файле, а затем запускать всю инфраструктуру одной лишь командой. 
Лично мне Docker Compose помогает экономить время, и быстро запускать и 
останавливать приложения и использовать одинаковую конфигурацию на разных компьютерах.

## 6.4. Задание 2.

Выполнено с использованием Docker Compose.

Развернуты три сервиса:
- Prometheus
- Pushgateway
- Grafana

Настроены:
- Docker Compose и общая сеть контейнеров.
- Именованные тома для хранения данных.
- Конфигурация Prometheus.
- Источник данных Prometheus в Grafana.
- Передача метрики `menschikova_ed` через Pushgateway.
- Дашборд Grafana с графиком метрики.

Проверено получение метрики в Prometheus и отображение графика в Grafana.


### Скриншоты выполнения задания

1. `grafana.png` — график метрики menschikova_ed в Grafana.
2. `docker-ps.png` — работающие контейнеры Prometheus, Pushgateway и Grafana.
3. `docker-compose-down.png` — остановка и удаление контейнеров командой Docker Compose.


