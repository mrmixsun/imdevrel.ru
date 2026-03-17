# imdevrel.ru — Портфолио

Сайт-портфолио на [Astro](https://astro.build), хостинг на [Vercel](https://vercel.com).

## Требования

- **Node.js** v22.12.0 или выше ([скачать](https://nodejs.org/) или установить через [nvm](https://github.com/nvm-sh/nvm))

## Разработка

```bash
# Установка зависимостей
npm install

# Запуск dev-сервера
npm run dev
```

Сайт будет доступен на [http://localhost:4321](http://localhost:4321).

## Сборка

```bash
npm run build
```

Статические файлы появятся в папке `dist/`.

## Деплой на Vercel

1. Залейте репозиторий на GitHub
2. Подключите репозиторий в [Vercel](https://vercel.com/new)
3. Vercel автоматически определит Astro и настроит сборку

## Структура проекта

```
├── public/          # Статические файлы (favicon, robots.txt)
├── src/
│   └── pages/       # Страницы (index.astro = /)
├── astro.config.mjs
├── package.json
└── tsconfig.json
```
