# 🤖 Telegram Moderator Bot

Продвинутый модератор-бот на **aiogram 3** для чатов и супергрупп.

## ✨ Возможности
- Фильтр запрещённых слов
- Анти-ссылки с белым списком
- Управление наказаниями (Warn / Mute / Ban / None)
- Админ-панель только через inline-кнопки
- Настройка сообщений Warn/Mute/Ban
- Включение/выключение бота
- Режимы работы: all / admins
- Сохранение настроек в `data.json`

## 🚀 Установка и запуск
```bash
git clone https://github.com/username/moderator-bot.git
cd moderator-bot
python -m venv venv
source venv/bin/activate   # или venv\Scripts\activate на Windows
pip install -r requirements.txt
python main.py
