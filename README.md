# SkyMailing
Сервис для создания и отправки рассылок

Команды:
- python manage.py csu - создает суперюзера
- python manage.py start_mailing - отправка писем в ручную

## Для запуска сервиса:
1. Склонировать репозиторий в PyCharm (команда: git clone https://github.com/MihailEro/mailing.git)
2. Установить зависимости, из файла requirements.txt
3. Заполнить файл .env своими данными
4. Cоздайте миграции: python manage.py makemigrations
5. Примените миграции: python manage.py migrate
6. Запустить команду python3 manage.py csu для создания суперюзера
7. Запустить сервис, автоотправка срабатываем раз в минуту
8. Для ручной отправки подходящих рассылок запустить команду python manage.py start_mailing