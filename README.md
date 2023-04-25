# Домашнее задание к занятию "Zabbix. Часть 2" - Лебедев Антон


---

### Задание 1

Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

![Задание 1](https://github.com/lebedun/9-03-hw/blob/main/img/Screenshot_1.jpg)


---

### Задание 2

Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. 

(Скриншот в задании 3, в качестве одного из хостов использовался сам сервер заббикс).

---

### Задание 3

Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

Тут я не совсем понял автора задания. Поскольку в шаблоне Linux by Zabbix Agent уже есть итемы, которые я использовал для мониторинга загрузки CPU и RAM (в этом шаблоне вообще есть всё), то одновременно добавить оба эти шаблона одному хосту невозможно. Заббикс серверу я не могу добавить свой учебный шаблон, тестовому хосту - шаблон "из коробки". Либо мне пришлось бы "портить" шаблон из коробки, выкидывая из него два использованных мной параметра, что явно не лучшая идея.

![Задание 2-3](https://github.com/lebedun/9-03-hw/blob/main/img/Screenshot_2.jpg)

### Задание 4

Создайте свой кастомный дашборд.

![Задание 4](https://github.com/lebedun/9-03-hw/blob/main/img/Screenshot_3.jpg)


---