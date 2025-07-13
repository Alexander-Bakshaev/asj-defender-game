# Домашняя работа к лекции «Стандарты и Рабочее окружение»

## Технологический стек

[![Node.js](https://img.shields.io/badge/Node.js-18.19.0-green.svg)](https://nodejs.org)
[![npm](https://img.shields.io/badge/npm-9.8.1-blue.svg)](https://npmjs.com)
[![Babel](https://img.shields.io/badge/Babel-7.28.0-orange.svg)](https://babeljs.io)
[![ESLint](https://img.shields.io/badge/ESLint-9.31.0-purple.svg)](https://eslint.org)

## Цель проекта

Проект демонстрирует настройку современного рабочего окружения для разработки браузерных игр с использованием последних инструментов JavaScript.

## Выполненные задачи

1. Настройка npm package
   - Имя: defender-game
   - Версия: 1.0.0
   - Описание: "Browser based game"
   - Точка входа: index.js
   - Репозиторий: GitHub
   - Ключевые слова: game
   - Автор: Alex
   - Лицензия: ISC

2. Настройка Babel
   - Установлены пакеты: @babel/core@7.28.0, @babel/cli@7.28.0, @babel/preset-env@7.28.0
   - Настроен скрипт build в package.json
   - Настроен babel.config.json
   - Установлен core-js@3.44.0

3. Настройка ESLint (задача со звёздочкой)
   - Установлены пакеты: @eslint/js@9.31.0, @eslint/json@0.13.0, eslint@9.31.0
   - Настроен скрипт lint в package.json
   - Создан конфиг eslint.config.mjs
   - Настроены исключения для директории dist

## Структура проекта

```
asj-defender-game/
├── dist/               # Скомпилированный код
├── node_modules/       # Зависимости
├── src/               # Исходный код
│   └── app.js          # Основной файл приложения
├── .gitignore          # Правила игнорирования Git
├── babel.config.json   # Конфигурация Babel
├── eslint.config.mjs    # Конфигурация ESLint
├── package.json        # Конфигурация проекта
└── README.md           # Документация
```

## Запуск

1. Сборка проекта:
```bash
npm run build
```

2. Проверка стиля кода:
```bash
npm run lint
```

## Лицензия

ISC

---

## Дополнительная информация

Домашняя работа выполнена в рамках курса по JavaScript от Нетологии. Проект демонстрирует правильную настройку рабочего окружения с использованием современных инструментов разработки.
