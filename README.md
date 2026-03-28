# tasks_planning_website_2026
project for discipline program engineering 2 sem mag: planning tasks on https://www.leadertask.ru

Individual version of task:

# 10 Планирование задач https://www.leadertask.ru/
Приложение должно содержать следующие данные:
- цель
- задача
- исполнитель

Реализовать API:
- Создание нового пользователя
- Поиск пользователя по логину
- Поиск пользователя по маске имя и фамилии
- Создание новой цели
- Получение списка всех целей
- Создание новой задачи на пути к цели
- Получение всех задач цели
- Изменение статуса задачи в цели

### 2.1 Roles
 - Worker
    - create and delete its own user (only 1)
    - search other users by login, see them open tasks (if granted by Worker or Manager or if ) and change their statuses
 - Manager
    - create and delete his own user (only 1) and create workers (not more than 1000). Can only delete workers, that were created by itself.
    - search other users by login and see them open tasks,
 - Administrator (for developers and support only)
    - create/delete all other users

In every objective/task there are next roles:
 - Creator: who created objective/task.
 - Co-creator: who can watch and manage objective/task/statuses.
 - Manager: who can watch and manage task/statuses.
 - Watcher: who can only watch objective/task statuses.

### 2.2 External systems
 - E-mail server
 - SMS server
 - subscribe/donate payment server?
