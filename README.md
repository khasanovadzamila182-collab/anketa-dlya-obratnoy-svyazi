# TreeFire Mentorligi — Yakuniy Anketa

Это HTML форма для сбора обратной связи от учеников. Данные собираются в Google Sheets автоматически.

## Быстрый деплой на Vercel

### Способ 1: Через GitHub (рекомендуется)

1. **Создай GitHub репозиторий:**
   - Зайди на https://github.com/new
   - Назови его `treefire-anketa`
   - Создай репо (пусто)

2. **Загрузи эти файлы в репо:**
   - `index.html`
   - `vercel.json`
   - `README.md` (этот файл)

3. **Подключи Vercel:**
   - Зайди на https://vercel.com
   - Кликни "New Project"
   - Выбери свой GitHub репозиторий `treefire-anketa`
   - Нажми "Deploy"
   - Ждёшь 30 секунд
   - **Готово!** Vercel даст тебе публичный URL вида `https://treefire-anketa.vercel.app`

### Способ 2: Прямо через Vercel (без GitHub)

1. Зайди на https://vercel.com
2. Нажми "Upload"
3. Загрузи эту папку целиком
4. Vercel сам разберётся

---

## Как это работает

1. **Форма открывается** по твоему URL
2. **Люди заполняют анкету** в браузере
3. **При нажатии "Отправить"** данные уходят в Google Apps Script
4. **Apps Script добавляет строку** в твой Google Sheet
5. **Ты видишь все ответы** в таблице в реальном времени

---

## Где найти ответы

Все ответы собираются в твоём Google Sheet:
`https://docs.google.com/spreadsheets/d/1JUtcsQeoYRkfU1eYIfb-rYOBjlL-0fvXWRUFJSaxHCI`

Каждый новый ответ = новая строка в таблице.

---

## Что отправлять людям в Telegram

После деплоя на Vercel ты получишь ссылку вида:
```
https://treefire-anketa.vercel.app
```

Вот эту ссылку и кидаешь в Telegram группу. Все остальное работает само.

---

**Готово к деплою!** 🚀
