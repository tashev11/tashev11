<img src="https://raw.githubusercontent.com/tashev11/tashev11/main/assets/header.png" alt="Ринат Ташев — Digital-архитектор для роста бизнеса" width="100%">

Делаю инструменты и автоматизацию для малого бизнеса, цифровые продукты и open-source инструменты для AI-разработки — от идеи до работающего продакшна.

**[tashev.ru](https://tashev.ru)**

---

## Tashev Relay — продолжай разработку с того же места

**Open-source continuity layer для AI-разработки.** Relay сохраняет текущую задачу, Git-состояние, следующий шаг и контекст работы, чтобы переключиться между Claude Code, OpenAI Codex, Cursor, Gemini CLI, другим терминалом или компьютером и продолжить без повторного объяснения проекта.

```bash
relay save --task "Fix auth" --next "Run integration tests" --agent claude
relay handoff codex --stdout
relay resume
```

[**GitHub →**](https://github.com/tashev11/tashev-relay) &nbsp;·&nbsp; [**v0.1.0 →**](https://github.com/tashev11/tashev-relay/releases/tag/v0.1.0) &nbsp;·&nbsp; `Node.js` `Git` `AI agents` `MIT` `zero dependencies`

> **Git remembers your code. Relay remembers your work.**

---

## Tashev Crew — совместная работа без скрытых конфликтов

**Open-source realtime coordination layer для людей и AI, работающих над одним Git-репозиторием.** Crew показывает, кто сейчас работает, над какой задачей, в какой ветке и какие файлы меняет локально — ещё до commit. Если Claude, Codex, Cursor или разработчики начинают трогать один и тот же файл, Crew предупреждает об этом заранее.

<p align="center">
  <a href="https://github.com/tashev11/tashev-crew"><img src="https://raw.githubusercontent.com/tashev11/tashev-crew/main/assets/hero.svg" alt="Tashev Crew" width="100%"></a>
</p>

```bash
crew status
crew start "Fix payment flow"
crew done
```

[**GitHub →**](https://github.com/tashev11/tashev-crew) &nbsp;·&nbsp; `Node.js` `GitHub` `realtime` `AI agents` `MIT` `zero runtime dependencies`

> **See who is working. See what they touch. Never collide.**

---

## Tashev Proof — AI сказал «готово», Proof проверяет

**Open-source proof-of-done для AI-разработки.** Proof превращает человеческую задачу в acceptance contract, запускает реальные доказательства — тесты, HTTP, файлы и ручную приёмку — и выдаёт итоговый статус **PROVEN / PARTIAL / FAILED** перед релизом.

```bash
proof init --task "Add password reset"
proof run
proof ship
```

[**Сайт →**](https://tashev11.github.io/tashev-proof/) &nbsp;·&nbsp; [**GitHub →**](https://github.com/tashev11/tashev-proof) &nbsp;·&nbsp; [**v0.1.0 →**](https://github.com/tashev11/tashev-proof/releases/tag/v0.1.0) &nbsp;·&nbsp; `Node.js` `verification` `vibe-coding` `MIT` `zero dependencies`

> **AI said done. Proof checks if it is.**

---

## Swapl — работа за свайп

**Платформа поиска работы и сотрудников через взаимный интерес.** Соискатели свайпают вакансии, работодатели — кандидатов; при взаимном интересе создаётся матч и открывается прямой чат. Есть профили, вакансии, отклики, матчи, сообщения, уведомления, кабинеты работодателя и соискателя.

Продукт работает как веб-сервис и Android-приложение в Google Play. Мобильная версия построена на Capacitor и загружает production-интерфейс Swapl, поэтому веб и приложение развиваются как единый продукт.

<a href="https://swapl.ru"><img src="https://raw.githubusercontent.com/tashev11/tashev11/main/assets/swapl.svg" alt="Swapl — работа за свайп" width="100%"></a>

[**Открыть Swapl →**](https://swapl.ru) &nbsp;·&nbsp; [**Google Play →**](https://play.google.com/store/apps/details?id=swapl.ru) &nbsp;·&nbsp; [**GitHub-витрина →**](https://github.com/tashev11/swapl_) &nbsp;·&nbsp; `Next.js` `TypeScript` `Prisma` `Capacitor` `Android` `PWA`

Production-исходники закрыты; публичный репозиторий используется как витрина продукта, roadmap и канал обратной связи.

---

## Ракета

**Портал бесплатных инструментов для предпринимателей.** 83 шаблона документов и шесть налоговых калькуляторов 2026: УСН, патент, НПД, НДС, взносы ИП, возврат НДФЛ, проверка реквизитов по контрольным суммам. Всё считается и заполняется прямо в браузере — данные не уходят на сервер.

Статика без сборки и без единой зависимости, живёт на GitHub Pages.

<a href="https://tashev11.github.io/raketa/"><img src="https://raw.githubusercontent.com/tashev11/tashev11/main/assets/raketa.png?v=2" alt="Ракета — портал инструментов для малого бизнеса" width="100%"></a>

[**Открыть →**](https://tashev11.github.io/raketa/) &nbsp;·&nbsp; [Исходники](https://github.com/tashev11/raketa) &nbsp;·&nbsp; `vanilla JS` `CC BY-NC 4.0`

---

## Дзен

**AI-автопостинг в Яндекс Дзен как услуга.** Сервис анализирует поисковый спрос, пишет SEO-статьи о бизнесе клиента и публикует их каждый день. Внутри — Telegram Mini App с контент-планом, генерацией текстов и обложек, расписанием публикаций и партнёрской программой.

React 19 и Vite на фронте, Fastify, Telegraf и Firestore на бэке. Исходники закрыты.

<a href="https://dzen.tashev.ru"><img src="https://raw.githubusercontent.com/tashev11/tashev11/main/assets/dzen.png?v=2" alt="Дзен — AI-автопостинг и SEO-трафик" width="100%"></a>

[**Открыть →**](https://dzen.tashev.ru) &nbsp;·&nbsp; `TypeScript` `React` `Fastify` `OpenAI`

---

## TASH.coin

**Токен TASHEV в сети TON.** Покупка напрямую через смарт-контракт, реферальная программа, Telegram-мини-приложение и накопление токенов. Готовится заявка на добавление в реестр токенов Tonkeeper.

<a href="https://coin.tashev.ru"><img src="https://raw.githubusercontent.com/tashev11/tashev11/main/assets/tash.png?v=2" alt="TASH.coin — токен на блокчейне TON" width="100%"></a>

[**Открыть →**](https://coin.tashev.ru) &nbsp;·&nbsp; [Смотреть в TON Explorer →](https://tonviewer.com/EQCW4dRx9_IRF_zN6A8-XFi8K8nSMNs_xO0GUDu4eAY1fE9p) &nbsp;·&nbsp; `TON` `смарт-контракт`

---

## Стек

| | |
|---|---|
| **Фронтенд** | TypeScript · React · Next.js · Vite · Tailwind · vanilla JS |
| **Бэкенд** | Node.js · Fastify · Prisma · Python |
| **Мобайл** | Capacitor · Android · PWA |
| **Сервисы** | Telegram Bot API · OpenAI · Firebase / Firestore · TON |
| **Инфраструктура** | nginx · GitHub Pages · Google Play |

## Как я работаю

Беру задачу целиком: продукт, код, деплой, тексты. Предпочитаю простые решения — статику вместо фреймворка, если фреймворк не нужен, и рабочий прототип вместо длинного плана.
