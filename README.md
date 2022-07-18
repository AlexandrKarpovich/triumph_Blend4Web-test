В рамках тестового задания предлагается реализовать на языке JavaScript с использованием
чистых Web-components без фреймворков примитивный редактор табличных данных.
Данные — массив записей. Каждая запись — объект со значениями: name, type, color
Пример:
[{name:"name1", type="main", color=''#f4f4f4'},{name:"name2", type="side", color=''#f8f8f8'}]
Интерфейс должен быть сверстан в соответствии с макетом. Ссылка на файл макета:
https://disk.yandex.ru/d/-9C1uBcZl4YAHQ



Необходимо реализовать следующий функционал:
1 Просмотр, добавление, изменение, удаление данных, в том числе изменение порядка
записей путем перетаскивания отдельных строк с использованием drag & drop
2 Загрузка и сохранение данных в localstorage.
3 Кроссбраузерность, адаптивность
4 Цвет должен меняться с помощью colorpicker (можно использовать готовый,
соответствие макету данного компонента не обязательно), значение должно быть можно


задавать в Hex / Rgb / sRgb.
Пункт № 4 будет оцениваться отдельно
Полезные ссылки для решения данного тестового задания:
1 https://medium.com/webbdev/web-1370a1426072
2 https://developers.google.com/web/fundamentals/web-components/customelements?hl=ru
3 https://habr.com/ru/post/461153/
4 https://developers.google.com/web/fundamentals/web-components
Подсказка.
Вам необходимо представить некоторые элементы в виде пользовательских (см.
window.customElements.define) и также осуществить взаимодействие между этими
компонентами с использованием биндингов (https://medium.com/swlh/https-medium-com-
drmoerkerke-data-binding-for-web-components-in-just-a-few-lines-of-code-33f0a46943b3) и
отправки и обработки пользовательских сообщений (dispatchEvent, addEventListener)

![Image alt](https://github.com/AlexandrKarpovich/triumph_Blend4Web-test/img/demo.jpg)