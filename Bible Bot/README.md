# Bible Bot - Telegram Bot

Telegram бот для чтения Библии с функциями поиска, заметок и совместного чтения.

## Функции

- 📖 Чтение книг Библии по главам
- 🔍 Поиск по названиям книг
- 📝 Добавление заметок к главам
- 🔗 Создание ссылок на Telegraph
- 👥 Совместное чтение в группах
- 📅 Рассылка стихов дня

## Деплой на Render

1. Создайте новый Web Service на Render
2. Подключите ваш GitHub репозиторий
3. Настройте следующие параметры:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `python bot.py`
   - **Environment Variables**: Добавьте `BOT_TOKEN` с вашим токеном бота

## Переменные окружения

- `BOT_TOKEN` - токен вашего Telegram бота (получите у @BotFather)

## Локальный запуск

1. Установите зависимости:
```bash
pip install -r requirements.txt
```

2. Запустите бота:
```bash
python bot.py
```

## Структура файлов

- `bot.py` - основной файл бота
- `bible.json` - данные Библии
- `requirements.txt` - зависимости Python
- `Procfile` - конфигурация для Render
- `runtime.txt` - версия Python 