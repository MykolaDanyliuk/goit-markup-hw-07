# goit-markup-hw-07

- Создай репозиторий `goit-markup-hw-07`.
- Склонируй созданный репозиторий и скопируй в него файлы предыдущей работы.
- Настрой `GitHub Pages` и добавь ссылку на живую страницу в шапку
  GitHub-репозитория.

## Структура файлов проекта

![Структура файлов проекта](./07-preview.png)

## Критерии приёма работы наставником

## Проект

**`«A1»`** Выполнен рефакторинг HTML-кода проекта используя методологию BEM.

**`«A2»`** Выполнен рефакторинг CSS-кода проекта используя препроцессор `SASS`.

**`«A3»`** В корне проекта создана папка `sass`, в которой лежат все файлы
стилей препроцессора.

**`«A4»`** В папке `sass` есть файл `main.scss` - главный файл в котрый
импортируются все SASS-фрагменты (partials, файлы `_имя.scss`).

**`«A5»`** Палитра цветов макета и наборы шрифтов вынесены в переменные в файле
`variables.scss`, который лежит в папке `sass/utils`. Можно использовать CSS или
SASS переменные (по желанию).

**`«A6»`** Для каждого компонента создан отдельный файл-фрагмент стилей в папке
`sass/components`. Напримпер `_page-header.scss`, `_logo.scss` и т. д.

**`«A7»`** В файлах `index.html` и `portfolio.html` подключен минифицированный
файл стилей `main.min.css` из папки `css`.

## Разметка

**`«B1»`** Правильное именование классов блоков по методологии BEM.

**`«B2»`** Правильное именование классов элементов по методологии BEM.

**`«B3»`** Правильное именование классов модификаторов по методологии BEM.

**`«B4»`** Правильное именование классов примесей по методологии BEM.

**`«B5»`** Имена классов по методологии BEM понятные и описательные, на
английском языке.

## Оформление

**`«C1»`** Использована вложенность селекторов.

**`«C2»`** Максимальная вложенность селекторов - 2 уровня.

**`«C3»`** Оператор конкатенации (`&`) использован для описания псевдоклассов и
псевдоэлементов.

### План занятия Александра Репеты (13-препроцессор)

- Как и чем компилировать SASS -> CSS. Пару слов о https://scout-app.io/
- Настроить расширение Live sass compiler для VSCode
- Разобрать базовые возможности SASS: переменные и вложенность
- Вложенность с оператором конкатенации: `& селектор` и `селектор &` на примере стилей при ховере по предку
- Структура файлов стилей, паршалы и @import
- Плейсхолдеры
- Миксины: дефолтные значения миксинов
- Плейсхолдеры vs миксины
- Директива each, интерполяция
- Миксин generateIcons

### План занятия Александра Репеты (15-дополнительное по бэм)

### Дополнительные материалы

[БЭМ](https://ru.bem.info/)

[BEM-шпаргалка](https://9elements.com/bem-cheat-sheet/)

[SassMeister - Sass-емулятор](https://www.sassmeister.com/)

[Документация Sass](https://sass-lang.com/documentation/)

[Приложение Scout App](https://scout-app.io/)

[Эстетичный Sass: архитектура и организация](http://prgssr.ru/development/estetichnyj-sass-chast-1-arhitektura-i-organizaciya.html)

[Автопрефиксер CSS онлайн](http://autoprefixer.github.io/ru/)

[Нужное количество версий выбирается в интерфейсе автопрефиксера в специальном формате Browserslist - конфигурации описывающей версии браузеров которые должен поддерживать код проекта](https://github.com/browserslist/browserslist)

[Корисний патерн для структури - Sass Guidelines](https://sass-guidelin.es/#the-7-1-pattern)
