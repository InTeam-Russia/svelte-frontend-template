# Клиентский сервис &mdash; `{название проекта}`

`{краткое описание нашего проекта}`

## Оглавление

1. [Архитектура](#архитектура)
1. [Стек](#стек)
   - [Основной фреймворк](#основной-фреймворк)
   - [Библиотека компонентов](#библиотека-компонентов)
   - [Сборка и CI/CD](#сборка-и-cicd)
1. [Настройка проекта](#настройка-проекта)
   - [Требования](#требования)
   - [Установка](#установка)
1. [Полезные ссылки](#полезные-ссылки)

## Архитектура

В проекте используется упрощённая FSD-архитектура:

- `src/routes` &mdash; директория для SvelteKit Router
- `src/utils` &mdash; базовые алгоритмы и функции
- `src/services` &mdash; код для работы с внешним API, хранением глобальных состояний и т.п.
- `src/components` &mdash; компоненты и элементы UI
- `src/widgets` &mdash; самостоятельные виджеты, состоящие из компонентов
- `src/features` &mdash; модули, состоящие из виджетов, выполняющие определённую задачу

## Стек

<img src="https://skillicons.dev/icons?i=svelte,typescript,tailwind,vite" />

### Основной фреймворк

- SvelteKit
- Typescript
- TailwindCSS

### Библиотека компонентов

- Shadcn-UI
- Lucida Icons

### Сборка и CI/CD

- Vite
- ESLint
- Prettier
- Husky
- Lint-staged

## Настройка проекта

### Требования

- Node.js
- npm
- git

### Установка

```bash
# clone the repository
git clone git@github.com:InTeam-Russia/svelte-template-frontend.git
cd svelte-template-frontend

# install yarn (if necessary)
npm i -g yarn

# setup project
yarn
yarn dev
```

## Полезные ссылки

1. [Документация Svetle](https://svelte.dev/docs/svelte/overview)
2. [Документация SvelteKit](https://svelte.dev/docs/kit/introduction)
3. [Документация ShadCN-svelte](https://shadcn-svelte.com/)
4. [Документация TailwindCSS](https://tailwindcss.com/docs/)
