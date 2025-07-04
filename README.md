# Проект: Mesto

## Описание проекта

**Mesto** — это интерактивная страница, куда пользователи могут добавлять фотографии своих любимых мест, ставить лайки и удалять карточки. Проект реализован с использованием современного стека веб-разработки и демонстрирует применение модульного подхода в JavaScript.

### Функциональность:
- Редактирование данных профиля.
- Добавление новых карточек с фото и названием.
- Удаление своих карточек.
- Установка и снятие "лайков".
- Плавное открытие и закрытие модальных окон (попапов).
- Валидация всех форм в реальном времени.
- Закрытие попапов по клику на оверлей или по нажатию клавиши `Esc`.

## Технологии

- **HTML5**
- **CSS3** (Flexbox, Grid Layout)
- **JavaScript** (ES6+ модули, асинхронность)
- **Webpack** для сборки проекта
- **Babel** для транспиляции JS-кода
- **PostCSS** (с плагинами Autoprefixer и CSSnano)
- **Методология БЭМ** (Nested) для именования CSS-классов

## Установка и запуск

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Crivoru4e4ka/mesto_project.git
   ```
2. Перейдите в директорию проекта:
   ```bash
   cd mesto-project
   ```
3. Установите зависимости:
   ```bash
   npm install
   ```
4. Запустите проект в режиме разработки:
   ```bash
   npm run dev
   ```
   Проект будет доступен по адресу `http://localhost:3000`.

5. Для сборки production-версии выполните:
   ```bash
   npm run build
   ```
   Готовые файлы появятся в папке `dist`.
