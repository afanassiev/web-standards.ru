# Веб-стандарты
![](https://github.com/web-standards-ru/web-standards.ru/workflows/EditorConfig/badge.svg)
![](https://github.com/web-standards-ru/web-standards.ru/workflows/Markdown/badge.svg)
![](https://github.com/web-standards-ru/web-standards.ru/workflows/HTML/badge.svg)
![](https://github.com/web-standards-ru/web-standards.ru/workflows/CSS/badge.svg)

Новый сайт сообщества: статьи, конференция, календарь, подкаст и всё остальное.

## Дизайн

[Макет в Figma](https://www.figma.com/file/kHj7Cs5lJsKDgFZS0UjOij/milestone-1).

## Разработка

- Установка зависимостей: `npm install`
- Старт сервера для локальной разработки: `npm start`
- Запуск сборки для деплоя: `npm run build`

## Участие в разработке

Вы можете выбрать [ишью из списка](https://github.com/web-standards-ru/web-standards.ru/issues) и сказать, что берётесь за работу. Этапы разработки сайта заведены [в проектах](https://github.com/web-standards-ru/web-standards.ru/projects). Для удобства, у задач указаны требуемые навыки в лейблах — фильтруйте по ним, выбирайте подходящие.

Форкните и присылайте пулреквесты.

Для разработчиков проекта есть чат в Телеграме, где можно синхронизироваться, обсуждать и планировать процесс. Постучите [@pepelsbey](https://t.me/pepelsbey) или [@higimo](https://t.me/higimo) в Телеграме, если хотите попасть туда.

## Окружение и технологии

Движок [Eleventy](https://www.11ty.io/) собирает Markdown или JSON по Nunjucks-шаблонам и генерирует статичные HTML-страницы. Стили пишутся на чистом CSS, соединяются импортами, сжимаются и оптимизируются. Браузерная совместимость пока уточняется, но пока «без IE11».

## Принципы верстки

**Mobile-first.** Сначала мы делаем мобильную версию интерфейса, а потом начинаем увеличивать с помощью `@media`. Например, кнопка открытия главного меню спрячется, когда для меню будет достаточно места на экране.

**Нет брекпоинтов для адаптации.** Каждый компонент для себя решает, когда ему адаптироваться. Например, когда пункты меню начинают помещаться — пора развернуть его во всю ширину и спрятать кнопку-гамбургер.

---
Работает на [Eleventy](https://www.11ty.io/).
