# Проектная работа 11-го спринта

[Макет](<https://www.figma.com/file/vIywAvqfkOIRWGOkfOnReY/React-Fullstack_-Проектные-задачи-(3-месяца)_external_link?type=design&node-id=0-1&mode=design>)

[Чеклист](https://www.notion.so/praktikum/0527c10b723d4873aa75686bad54b32e?pvs=4)

## Этапы работы:

1. Разверните проект и ознакомьтесь с кодом. Все необходимые вам компоненты уже созданы и лежат в папке `src/components`

2. Настройте роутинг.

3. Напишите функционал запросов данных с сервера, используя `Redux` и глобальный `store`. Сами "ручки" уже прописаны и лежат в `utils/burger-api.ts`

4. Настройте авторизацию и создайте защищённые роуты.

## Важно:

Для корректной работы запросов к серверу необходимо добавить переменную BURGER_API_URL в окружение. Сама ссылка находится в файле `.env.example`.

## Доступные скрипты

### `npm start`

Запускает приложение в режиме разработке на локальном сервере http://localhost:3000.

### `npm test`

Исполняет все написанные файлы тестирования

### `npm run build`

Генерирует оптимизированную сборку проекта в папке `build/`

### `npm run eject`

После запуска команды CRA необратимо копирует все инфраструктурные файлы конфигурации из пакета react-scripts в сам
проект и редактирует package.json файл

## Запустить проект

- Клонировать проект - `git clone git@github.com:julfy-bs/stellar-burgers.git`
- Установить зависимости `npm install`
- Запустить сервер для разработки `npm run start`

&copy; Автор - [Сутужко Богдан][author-github]

[//]: # 'Общие переменные для проектов Yandex'

[yandex-practicum-web-plus]: https://practicum.yandex.ru/promo/long-courses/web

[yandex-practicum-url]: https://practicum.yandex.ru/

[yandex-styleguide]: https://code.s3.yandex.net/web-developer/static/design-rules/index.html

[//]: # 'Общие переменные автора'

[author-github]: https://github.com/julfy-bs

[//]: # 'Переменные приложения'

[project-checklist-1]: https://code.s3.yandex.net/web-plus/checklists/checklist_pdf/checklist_7.pdf

[project-checklist-2]: https://code.s3.yandex.net/web-plus/checklists/checklist_pdf/checklist_8.pdf

[project-checklist-3-1]: https://code.s3.yandex.net/web-plus/checklists/checklist_pdf/checklist_9-1.pdf

[project-checklist-3-2]: https://code.s3.yandex.net/web-plus/checklists/checklist_pdf/checklist_9-2.pdf

[project-checklist-4]: https://code.s3.yandex.net/web-plus/checklists/checklist_pdf/checklist_10.pdf

[project-figma-1]: https://www.figma.com/file/zFGN2O5xktHl9VmoOieq5E/React-_-%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BD%D1%8B%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8_external_link?node-id=0%3A1

[project-figma-2]: https://www.figma.com/file/ocw9a6hNGeAejl4F3G9fp8/React-_-%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BD%D1%8B%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8-(3-%D0%BC%D0%B5%D1%81%D1%8F%D1%86%D0%B0)_external_link?type=design&node-id=2973-2131&t=yKnqfxFYJJXliLJ3-0

[project-figma-3]: https://www.figma.com/file/ocw9a6hNGeAejl4F3G9fp8/React-_-%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BD%D1%8B%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8-(3-%D0%BC%D0%B5%D1%81%D1%8F%D1%86%D0%B0)_external_link?type=design&node-id=6291-2799&mode=design

[project-ui-library]: https://yandex-practicum.github.io/react-developer-burger-ui-components/

[//]: # 'Переменные используемых технологий'

[tech-html]: https://html5.org/

[tech-css]: https://www.w3.org/Style/CSS/Overview.en.html

[tech-js]: https://www.javascript.com/

[tech-ts]: https://www.typescriptlang.org/

[tech-react]: https://react.dev/

[tech-react-router]: https://reactrouter.com/en/main

[tech-redux]: https://redux.js.org/

[tech-redux-toolkit]: https://redux-toolkit.js.org/
