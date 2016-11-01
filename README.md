# Elena landing page (пример вёрстки)

## Описание

Вёрстка выполнялась в соответствии с дизайном PSD файла ( изображение шаблона можно посмотреть в репозитории `HTML-Layouts-Elena/images-of-psd-template/` ), распространяемого в бесплатном доступе. Вёрстка включает в себя HTML файл и несколько CSS файлов, которые создавались для улучшения архитектуры стилей и облегчения дальнейшей поддержки проекта. Структура HTML файла создавалась при помощи [HTML5 Boilerplate](https://html5boilerplate.com) с учётом полного отсутствия стилевого оформления для сохранения логики использования проекта.

Также использовались относительные размеры элементов для создания Responsive дизайна, благодаря чему структура не ломается при изменении объёма контента и изменении размеров экрана.   


## Структура стилей

Стили структурированы по следующим файлам ( перечислю в порядке их подключения в файле `index.html` ):

* `reset.css` - установка по умолчанию требуемым в данном проекте селекторам и классам
* `wrappers.css` - обёртки, в данном случае для центрирования блоков
* `grid.css` - стили сеток расположения элементов
* `fonts.css` - подключение шрифтов
* `text.css` - оформление шрифтов
* `elements-dimensions.css` - размеры блоков проекта
* `elements-background-colors.css` - цвета заливки блоков
* `elements-background-images.css` - стили для изображений подключённых через свойство ```background```
* `images.css` - стили для изображений подключённых через тег ```<img>```
* `forms.css` - формы входа, обратной связи и другие
* `lists.css` - общие стили списков
* `menus.css` - меню навигации по сайту и другие меню
* `links.css` - ссылки
* `buttons.css` - кнопки
* `geometric-shapes.css` - стили геометрических фигур используемых в проекте
* `customs.css` - стили завершающие внешний вид проекта

Также в шаблоне **HTML5 Boilerplate** созданы стили, описание которых можно найти в оффициальной документации  ( [HTML5 Boilerplate](https://html5boilerplate.com) ):

* `main.css`
* `normalize.css`