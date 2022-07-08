# Репозиторий для домашнего задания к занятию "08.02 Работа с Playbook"

## Файл  requirements.yml
Настроен для скачивания следующих ролей:
- Clickhouse
- Vector
- Lighthouse

Запустить командой:
``` 
ansible-galaxy role install -r requirements.yml -p roles
```
При повторном запуске добавить '--force'

## Playbook site.yml
Настроен для запуска ролей:
- Clickhouse
- Vector
- Lighthouse

## Совместимость
Роли тестировались в ОС ubuntu 20.04 и centos 7

## Group vars
Переменные для inventory