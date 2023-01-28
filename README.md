# Домашнее задание к занятию 9.4 «Prometheus» Баранов Сергей


---

### Задание 1

Установите Prometheus.

*Приведите скриншот systemctl status prometheus, где будет написано: prometheus.service — Prometheus Service Netology Lesson 9.4 — [Ваши ФИО].*

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-1.png)


---

### Задание 2

Установите Node Exporter.

*Приведите скриншот systemctl status node-exporter, где будет написано: node-exporter.service — Node Exporter Netology Lesson 9.4 — [Ваши ФИО].*

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-2%20vm1systemctl.png)

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-2%20vm2systemctl.png)


---

### Задание 3

Подключите Node Exporter к серверу Prometheus.

*Приложите скриншот конфига из интерфейса Prometheus вкладки Status > Configuration.*

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-31%20configuration.png)

*Приложите скриншот из интерфейса Prometheus вкладки Status > Targets, чтобы было видно минимум два эндпоинта.*

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-32%20Targets.png)

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-33%20Graph.png)


---

### Задание 4*

Установите Grafana.

*Приложите скриншот левого нижнего угла интерфейса, чтобы при наведении на иконку пользователя были видны ваши ФИО.*

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-4%20Grafana%20%D0%A4%D0%98%D0%9E.png)


---

### Задание 5*

Интегрируйте Grafana и Prometheus.

*Приложите скриншот дашборда (ID:11074) с поступающими туда данными из Node Exporter.*

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-5_Prometheus_localhost.png)

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-5_Prometheus_node_192.168.0.16.png)

![monitoring](https://github.com/12sergey12/9.4_Prometheus/blob/main/images/9.4-5_Prometheus_node_192.168.0.18.png)
