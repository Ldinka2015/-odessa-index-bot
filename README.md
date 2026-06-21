# Odessa.Index Bot

Бот репутаційного індексу забудовників Одеси на Railway.

## Підготовка до розгортування

1. **GitHub репозиторій:**
   - Створити репо на github.com
   - Клонувати його на Mac
   - Закинути туди всі файли (bot.py, requirements.txt, Procfile, runtime.txt, .gitignore)
   - Залити на GitHub (git push)

2. **Railway:**
   - Зареєструватися на railway.app
   - Підключити GitHub репо
   - Встановити змінну окружения:
     - TELEGRAM_BOT_TOKEN = твій токен
   - Deploy!

## Файли

- `bot.py` - основний код бота
- `requirements.txt` - залежності Python
- `Procfile` - інструкція для Railway
- `runtime.txt` - версія Python
- `.env.example` - шаблон змінних окружения

## Локальне тестування

```bash
pip install -r requirements.txt
export TELEGRAM_BOT_TOKEN="твій_токен_тут"
python bot.py
```

## Примітка

Токен прочитується з змінної окруження TELEGRAM_BOT_TOKEN, а не жорстко вписаний у код. Це безпечніше!
