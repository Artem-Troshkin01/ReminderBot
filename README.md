# Reminder Bot

Этот проект помогает сохранить напоминания в
базе данных при помощи телеграм-бота. Также
предоставляет простой REST API для обращений
к базе данных и извлечения и/или добавления
напоминаний

## Установка

1. Клонировать репозиторий:
    ```shell
    git clone https://github.com/Artem-Troshkin01/ReminderBot

2. Установка библиотек и модулей:
   ```shell
   pip install -r requirements.txt

3. Создание и активация виртуального окружения (Windows):
   ```shell
   python -m venv venv
   cd venv/Scripts
   activate.bat

4. Изменения в config/config.ini:
* **BOT_TOKEN** - Токен бота, полученный у @BotFather
* **HOST_URL** - Ссылка на домен
* **ADMIN_ID** - ID администратора бота Telegram
* **TIMEDELTA** - Отклонение локального времени от серверного (в часах)

## Запуск проекта

Запуск app/main.py 
   ```shell
   uvicorn app.main: app --reload
   ```

## Контакты
Artem Troshkin

**Telegram:** [evil_kekc](https://t.me/evil_kekc)