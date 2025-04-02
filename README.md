# 📧 Gmail → Calendar Automator

**Автоматически создает события в Google Calendar из непрочитанных писем Gmail**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🔥 Особенности
- Фильтрация по отправителям
- Автонастройка времени:
  - Ночные письма → 8:00 утра
  - Дневные → время письма + 30 мин
- Текст письма в описании события
- Защита от дубликатов

## 🚀 Быстрый старт
1. Скопируйте код из `gmail_to_calendar.js` в [Google Apps Script](https://script.google.com/)
2. Настройте триггер (**Редактор скриптов** → ⏰ **Триггеры**)
3. Укажите своих отправителей:
```javascript
const senderEmails = ["noreply@github.com", "ваш@email.com"]; // ← Здесь