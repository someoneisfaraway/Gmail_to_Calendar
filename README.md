# Gmail to Calendar Automation

Автоматическое создание событий в Google Calendar из писем Gmail

## Особенности
- Создает события для непрочитанных писем
- Добавляет текст письма в описание
- Защита от дубликатов
- Настраиваемое время событий

## Настройка
1. Развернуть скрипт в Google Apps Script
2. Добавить триггер (например, каждые 10 минут)
3. Настроить отправителей в `senderEmails`

```javascript
const senderEmails = ["noreply@github.com", "example@gmail.com"];
