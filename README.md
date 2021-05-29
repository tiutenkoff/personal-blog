# Personal blog

## Описание проекта:

Верстка многостраничного адаптивного сайта персонального блога с помощью графического редактора `Figma`, который содержал дизайн данного сайта.

## Цель:

Продемонстрировать навыки верстки, возможности gulp, удобство css-препроцессора `scss` при верстке, использование `JavaScript` для оживления сайта (Модальные окна, формы бургер-меню и др.)

<!-- Сайт предназначен для личного блога пользователя, возможно использование в качестве демонстрации личных н -->

## Использованные технологии и инструменты:

![JavaScript](https://img.shields.io/badge/-JavaScript-282727?style=for-the-badge&logo=JavaScript)
![html](https://img.shields.io/badge/-html-282727?style=for-the-badge&logo=html)
![scss](https://img.shields.io/badge/-scss-282727?style=for-the-badge&logo=scss)
<br> ![gulp](https://img.shields.io/badge/-gulp-282727?style=for-the-badge&logo=gulp)
![node.js](https://img.shields.io/badge/-node.js-282727?style=for-the-badge&logo=node.js)
<br> ![figma](https://img.shields.io/badge/-figma-282727?style=for-the-badge&logo=figma)

---

## Сборка проекта:

### Необходимо установить:

1. Консоль Git Bash:

[`Установить Git Bash (ссылка)`](https://git-scm.com/downloads)

2. Node.js:

[`Установить Node.js (ссылка)`](https://nodejs.org/en/)

3. Gulp, с помощью Git Bash:

```
$ npm install --global gulp-cli
```

4. Модуль для обновления зависимостей плагинов, с помощью Git Bash:

```
$ npm install -g npm-check-updates
```

---

## Запуск проекта:

- Проверим версии всех наших зависимостей наших плагинов:

```
$ ncu -u --packageFile package.json
```

- Установим все зависимости:

```
$ npm i
```

- Соберем проект и запустим локальный сервер:

```
$ gulp
```
