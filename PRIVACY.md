# HTML34 — Privacy Policy

_Last updated: 2026-07-07_

HTML34 is an open-source project for importing a website into Figma as editable layers. It has two parts: a **Figma plugin** (renders a URL via the author's server) and a **browser extension** (captures your live tab locally). This policy covers both. Source code: https://github.com/Rreerreea/HTML34

## What data is processed

- **The URL you enter** is sent to the author's render server, which opens the page in a headless browser, serializes its layout and downloads its images, and returns the result to the plugin. Nothing else from your Figma file ever leaves Figma.
- The server processes requests transiently: page data is rendered in memory, returned to you, and not stored. Standard technical logs (request URL, timestamp, IP for rate-limiting) may be kept briefly for abuse prevention.
- The server code is open source — you can audit it or run your own instance from the repository.
- **Feedback form** (optional): the text you type is forwarded to the author.
- **Radio player** (optional): streams audio directly from SomaFM (somafm.com); their own privacy policy applies.
- **Credits counter and settings** are stored locally via Figma's `clientStorage` and never uploaded.

## Browser extension (HTML34 for Chrome)

The browser extension is separate from the Figma plugin and runs entirely on your device.

- **Capturing makes zero network requests.** The extension reads the current tab you invoke it on, builds an SVG and places it on your clipboard. Nothing about the page or your browsing is uploaded, collected or stored remotely — the capture never leaves your clipboard.
- **Local storage only:** a single UI preference (text mode / skin) and a session-only list of your recent captures, kept in the browser's local/session storage and never uploaded.
- **"Found a bug?" form** (optional): the only network call. When you type a message and press Send, that text and the current page URL are forwarded to the author (via the author's server) solely to deliver your feedback. Nothing is sent unless you click Send.
- No accounts, no analytics, no tracking, no automatic data collection.

## What is NOT collected

No accounts, no analytics, no tracking pixels, no cookies, no selling of data. The plugin has no access to your Figma documents' contents beyond inserting the imported layers you asked for.

## Your responsibility

Import only websites you have the right to use. The plugin is a tool; you are responsible for how the imported content is used.

## Contact

Author: George Kazakov — https://goshakazakov.ru · gosha122@proton.me

---

## Кратко по-русски

Плагин отправляет на рендер-сервер только введённый вами URL; сервер обрабатывает страницы на лету и не хранит их. Код сервера открыт — можно проверить или поднять свой инстанс из репозитория. Аккаунтов, аналитики и трекинга нет. Счётчик кредитов хранится локально в Figma. Импортируйте только сайты, на которые у вас есть права.

**Расширение для браузера** работает полностью на вашем устройстве: захват страницы не делает сетевых запросов и ничего не отправляет — результат остаётся в буфере обмена. Локально хранятся только настройка интерфейса и список недавних захватов (в сессии). Единственный сетевой вызов — форма «Нашли ошибку?»: введённый текст и адрес страницы отправляются автору только по нажатию кнопки, чтобы доставить отзыв. Аккаунтов, аналитики и трекинга нет.
