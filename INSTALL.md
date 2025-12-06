u# 🚀 Быстрая установка GraberPro

## Шаг 1: Установка Python
Скачайте и установите Python 3.7+ с официального сайта: https://python.org

## Шаг 2: Установка зависимостей
Откройте командную строку в папке с ботом и выполните:
```bash
pip install telethon aiogram asyncio
```

## Шаг 3: Получение API данных
1. Перейдите на https://my.telegram.org/apps
2. Создайте приложение и получите `api_id` и `api_hash`
3. Создайте бота через @BotFather и получите `bot_token`
4. Узнайте свой ID через @userinfobot

## Шаг 4: Настройка config.json
Замените значения в файле `config.json`:
```json
{
    "api_id": 12345678,
    "api_hash": "ваш_api_hash",
    "bot_token": "ваш_bot_token",
    "my_id": ваш_telegram_id,
    "technical_channel_id": -100123456789,
    "new_link": "http://t.me/ваш_канал",
    "new_username": "@ваш_username"
}
```

## Шаг 5: Запуск
```bash
python main.py
```

При первом запуске введите номер телефона и код подтверждения.

## ✅ Готово!
Найдите своего бота в Telegram и отправьте `/start`