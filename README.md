ISD
===

http://dpzz.github.io/TODO/html/index.html - working page

Запускать index.html

VERSION 2
Работают попапы. Чтобы их вызвать, нужно нажать на соотв иконку, или ввести в поле ввода 'What to do?':
@ - person;
'#' - tags;
tomorrow - datepicker.
Datepicker до конца не реализован, понадобится дополнительно часа 4 для стилизации и навешивания событий, если писать руками.

При нажатии на фамилию, меняется параметр App.Task.name, который потом отправляется на сервер.
Отмеченные чекбоксы будут добавлены в параметр App.Task.tags.

Задачи добавляются визуально при нажатии "Add task". При добавлении в консоли выводится объект App.Task, готовый к отправке в методе App.AJAX(). 

Под разные платформы не тестил. Затраченное время = 10 часов.

Все на голых скриптах, никаких фреймворков.

Шаблонизаторов не писал, чтоб не возникало трудносте с проверкой запуска приложения (настройкой сервера и т.д.).
