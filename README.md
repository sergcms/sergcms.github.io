Учебный проект "landing-page"
================================

### Используемые технологии

1. Сборщик проектов  Gulp.js

### Используемые шрифты и иконки

1. Roboto light, regular, medium, bold
2. Font-Awesome - иконочный шрифт

### Стандартные компоненты и классы

***Компоненты***
1. Задаем отступы внутри блока:
```
    .default-section - стандартная секция
```
2. Задаем стили шапке и меню
```
    .header - шапка
    .logo - логотип
```
3. Стилизируем заголовки:
```
    .title - стандартный заголовок
    .title.small - переопределяем жирность и размер шрифта
```
4. Стилизируем стандартные кнопки:
```
    .btn 
    .btn.btn-default
    .btn.small
```

***Классы***
1. Задаем цвет:
```
    .bg-white
    .bg-grey
    .text-white
```
---

### Контрольные точки media-запросов

1. @media (max-width: 991px) - устройства c разрешением до 991px
2. @media (max-width: 767px) - устройства c разрешением до 767px
3. @media (max-width: 599px) - мобильные устройства c разрешением до 599px
4. @media (max-width: 479px) - мобильные устройства c разрешением до 479px
---

**Структура папок**

Название папок  | Содержание файла
----------------|----------------------
app             | Директория с готовым проектом
app/css         | Готовые стили к продакшену
app/img         | Готовые картинки к продакшену
app/fonts       | Шрифты
src             | Директория с исходными файлыми
src/css         | Исходные стили, здесь мы пишем наши стили и они будут конвертироваться в app/css
---

**Поставленные задачи для Gulp**
* Добавление вендорных префиксов в css
---