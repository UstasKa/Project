## Задача:
- сделать GCE инстанс с Ubuntu 20.04
- поставить на нем Docker Engine
- сделать каталог /var/lib/postgres
- развернуть контейнер с PostgreSQL 13 смонтировав в него /var/lib/postgres
- развернуть контейнер с клиентом postgres
- подключится из контейнера с клиентом к контейнеру с сервером и сделать таблицу с парой строк
- подключится к контейнеру с сервером с ноутбука/комьютера вне инстансов GCP
- удалить контейнер с сервером
- создать его заново
- подключится снова из контейнера с клиентом к контейнеру с сервером
- проверить, что данные остались на месте
- оставляйте в ЛК ДЗ комментарии что и как вы делали и как боролись с проблемами

## Решение