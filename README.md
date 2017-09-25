Простой вариант добавления обсуждений групп vk
=============================

Установка
------------

Файловая структура build (Old, не обновляется):

      template.html       шаблон
      style.css           стили
      script.js           функционал

> 1. На сайте должен быть подключён JQuery
> 2. Добавить содержимое template перед закрытым тегом body
> 3. Подключить стили и скрипт
> 4. Создаём контейнер в том месте, где Вы хотите разместить обсуждения с vk. Создаём div с class="discussions-vk" .
> 5. В файлах есть подсказки, которые помогут исправить содержимое

Файловая структура fast - build (Update 21.09.2017):

	  index.html                страница скрипта
      js/jquery-3.2.1.min.js    jquery
      js/script.js              функционал
	  css/normalize.css         сброс стилей
	  css/style.css             стили

> 1. Залить проект в корень вашего хостинга
> 2. Поменять данные в js/script.js

Update 25.09.2017

> 1. Сделал добавление всех комментариев разом, а не отдельными частями
> 2. Добавил адаптивность
> 3. Ссылку на пользователя, кому было адресовано сообщение

Update 21.09.2017

> 1. добавил просмотр лайков
> 2. добавил сортировку списка с начала или с конца
> 3. добавил даты комментариев
> 4. добавил настройку, нужно ли выводить фото/стикеры в комментарии

по любым вопросам пишите на почту main.main2014@yandex.ru
