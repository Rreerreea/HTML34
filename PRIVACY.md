# HTML34 — Privacy Policy

_Last updated: 2026-07-02_

HTML34 is an open-source Figma plugin that imports a website into Figma as editable layers. Source code: https://github.com/Rreerreea/HTML34

## What data is processed

- **The URL you enter** is sent to the author's render server, which opens the page in a headless browser, serializes its layout and downloads its images, and returns the result to the plugin. Nothing else from your Figma file ever leaves Figma.
- The server processes requests transiently: page data is rendered in memory, returned to you, and not stored. Standard technical logs (request URL, timestamp, IP for rate-limiting) may be kept briefly for abuse prevention.
- The server code is open source — you can audit it or run your own instance from the repository.
- **Feedback form** (optional): the text you type is forwarded to the author.
- **Radio player** (optional): streams audio directly from SomaFM (somafm.com); their own privacy policy applies.
- **Credits counter and settings** are stored locally via Figma's `clientStorage` and never uploaded.

## What is NOT collected

No accounts, no analytics, no tracking pixels, no cookies, no selling of data. The plugin has no access to your Figma documents' contents beyond inserting the imported layers you asked for.

## Your responsibility

Import only websites you have the right to use. The plugin is a tool; you are responsible for how the imported content is used.

## Contact

Author: George Kazakov — https://goshakazakov.ru · gosha122@proton.me

---

## Кратко по-русски

Плагин отправляет на рендер-сервер только введённый вами URL; сервер обрабатывает страницы на лету и не хранит их. Код сервера открыт — можно проверить или поднять свой инстанс из репозитория. Аккаунтов, аналитики и трекинга нет. Счётчик кредитов хранится локально в Figma. Импортируйте только сайты, на которые у вас есть права.
