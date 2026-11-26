# STR. — портфолио веб-разработчика

Статический сайт: HTML, CSS и JavaScript без сборки. Работает на GitHub Pages как есть.

## Публикация на GitHub Pages
1. Создайте на GitHub новый публичный репозиторий. Если назвать его `esik13.github.io`, сайт откроется по адресу https://esik13.github.io/. С любым другим именем, например `str-portfolio`, адрес будет https://esik13.github.io/str-portfolio/.
2. В репозитории нажмите Add file → Upload files и перетащите СОДЕРЖИМОЕ этой папки (index.html, img, 404.html, robots.txt, .nojekyll), а не саму папку. Нажмите Commit changes.
3. Откройте Settings → Pages. В Build and deployment выберите Source: Deploy from a branch, Branch: main, папка /(root), затем Save.
4. Через 1–2 минуты сайт откроется по адресу, который покажет GitHub вверху страницы Pages.

## Что можно поменять
- Telegram: переменная `TG_USERNAME` в конце index.html (сейчас Str_wed).
- Проекты и ссылки: массив `PROJECTS` в index.html.
- Скриншоты: файлы в папке img/ (замените файл с тем же именем).

## Форма
Серверной отправки нет: после проверки полей форма открывает Telegram с готовым текстом заявки и копирует его в буфер обмена.
