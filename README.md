## Установка

1. Добавить в /etc/hosts: 
   * `127.0.0.1 learn-docker.com`.
   * `127.0.0.1 learn-docker.local`.
2. Изменить значения в `.env` и `.env.dev` на настоящие.
3. Для запуска на продакшене перейти в папку `prod` и выполнть: `docker-compose up`.
4. Для запуска на локальной машине нужно перейти в папку `dev` и выполниь: `docker-compose -f docker-compose.development.yml up`.
