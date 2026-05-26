# ЮрПомощь РБ

Юридические консультации по законодательству Республики Беларусь.

## Деплой на Vercel

1. Загрузи эту папку на GitHub
2. Подключи репозиторий в vercel.com
3. Добавь переменную окружения: `ANTHROPIC_API_KEY` = твой ключ
4. Нажми Deploy

## Локальный запуск

```bash
npm install
npm run dev
```

## Структура

- `src/legal-belarus.jsx` — основное приложение
- `api/chat.js` — прокси для Anthropic API (ключ в секрете)
- `public/` — PWA файлы (manifest, service worker, иконки)
