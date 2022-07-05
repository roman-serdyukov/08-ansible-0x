# Репозиторий для домашнего задания к занятию "08.02 Работа с Playbook"

## Playbook site.yml
1. Playbook состоит из 2х play:
- Устанавлиет и запускает clickhouse
- Устанавливает vector

2. Playbook работает как в Debian ОС так и в RedHat ОС (тестировался с ubuntu 20.04 и centos 7)

3. В inventory-файле prod.ru создано 3 группы серверов: локальной сети; в YC; для localhost.