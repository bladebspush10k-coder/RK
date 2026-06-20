# RK — Brawl Stars Team

Статический сайт-презентация команды. Это один файл `index.html` (все картинки и шрифты внутри), поэтому деплой на Vercel идёт без сборки.

## Что внутри
- `index.html` — сам сайт
- `vercel.json` — конфиг (можно не трогать)
- `README.md` — этот файл

---

## Способ 1 — через Vercel CLI (самый быстрый)

1. Установи Node.js (https://nodejs.org).
2. Установи Vercel CLI:
   ```
   npm i -g vercel
   ```
3. Зайди в эту папку и выполни:
   ```
   vercel
   ```
   Залогинься (откроется браузер), на все вопросы можно жать Enter.
4. Для боевого домена:
   ```
   vercel --prod
   ```
   В консоли появится ссылка вида `https://rk-xxxx.vercel.app`.

## Способ 2 — через GitHub (удобно для обновлений)

1. Создай репозиторий на GitHub и залей туда содержимое этой папки.
2. На https://vercel.com → **Add New… → Project → Import** свой репозиторий.
3. Framework Preset: **Other**. Build Command и Output — оставь пустыми.
4. Жми **Deploy**. После каждого `git push` сайт будет обновляться сам.

## Способ 3 — drag & drop

На https://vercel.com можно просто перетащить эту папку в новый проект (Add New → Project), если у тебя включён drag-and-drop деплой.

---

## Свой домен
В проекте на Vercel: **Settings → Domains → Add** и привяжи свой домен (Vercel подскажет, какие DNS-записи добавить).
