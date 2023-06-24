<h1 align="center">Домашнє завдання №8</h1>

Запуск докер-контейнера з Redis
- docker run --name cache -d -p 6379:6379 redis

Запуск докер-контейнера з RabbitMQ

- docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.12-management

<h3>Перша частина домашнього завдання/<h3>


Наповнення бази даних

- python3 seeds.py


Запуск main.py

 - python3 main.py

