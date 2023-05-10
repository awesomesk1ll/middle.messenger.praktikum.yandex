<p align="center">
    <img src="https://img.shields.io/badge/astro-%5E2.4.1-B845ED" />
    <img src="https://img.shields.io/badge/node-%5E16.14.0-blue" />
    <img src="https://img.shields.io/badge/express-%5E4.18.2-green" />
    <img src="https://img.shields.io/badge/PostCSS-powered-DD3735" />
    <img src="https://img.shields.io/badge/typescript-%5E5.0.4-blue" />
</p>

## Макет проекта в Figma

https://www.figma.com/file/BRvBsUtiTgFinefVXv49x1/Chat

## Пощупать в Netlify:

https://awesomesk1ll-messenger-s1.netlify.app/ (1 спринт)

### Описание

Проект с практической работой выполняемой в рамках курса "Мидл фронтенд-разработчик" Яндекса. 

#### На текущем этапе разработки (спринт №1) реализовано:

* Настроена сборка статики с использованием [Astro](https://astro.build)
* Настроен процессинг для стилей PostCSS
* Свёрстаны прототипы экранов: 
- Авторизация ([тык](https://awesomesk1ll-messenger-s1.netlify.app/auth))
- Регистрация ([тык](https://awesomesk1ll-messenger-s1.netlify.app/reg))
- Ошибки 404 и 500 ([тык](https://awesomesk1ll-messenger-s1.netlify.app/asdf))
* Прикручен деплой из ветки на Netlify
* Прикручена сборка статики и раздача через Express

### Установка проекта

Установка зависимостей:

```bash
npm i
```

### Запуск проекта

Для разработки на локалхосте (с hot-reload), на порту 3000.

```bash
npm run dev
```

Для сборки статики и проверки на порту 3000 (Express).

```bash
npm start
```

### Дополнительные команды 

Сборка проекта в статику (для хостинга статики):

```bash
npm run build
```
