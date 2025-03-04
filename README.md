# Домашнее задание к занятию "`Teamcity`" - `Дедюрин Денис`

---
## Задание.

## Основная часть

1. Создайте новый проект в teamcity на основе fork.
2. Сделайте autodetect конфигурации.
3. Сохраните необходимые шаги, запустите первую сборку master.

### Ответ:
Развернуты 3 ВМ:

<img src = "img/01.png" width = 100%>

<img src = "img/02.png" width = 100%>




Установлен **nexus** с помощью **ansible-playbook** командой:
```
ansible-playbook -i inventory/cicd/hosts.yml site.yml
```
<img src = "img/03.png" width = 100%>

<img src = "img/04.png" width = 100%>