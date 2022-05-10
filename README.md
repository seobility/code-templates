## BITRIX
- **class-translator.php**<br>
Класс для мультиязычности проекта на битриксе. Позволяет переводить строки в коде через google, а также, умеет переводить свойства элементов и поля разделов, что позволяет не дублировать инфоблоки на проекте.
------------
## WORDPRESS
- **custom-entity**<br>
Решение для создания пользовательских сущностей и упраления ими. Позволяет использовать свои таблицы в базе данных и выносить на редактирование в административную часть элементы используя все преимущества wordpress и плагина ACF. В качестве системы кэширования использует redis.
------------
## PHP
- **wm-web**<br>
Примеры классов взяты с веб версии решения web-manager. Решение позволяет управлять с веб интерфейса тестовыми проектами. Умеет авторизовываться в CMS, проверять доступность сайтов, упралять гитом (получать состояние, менять ветки, обновлять с удаленного репозитория и т.д.).
------------
## NODEJS
- **vkino**<br>
Примеры кода из решения vkino. Решение собирает плееры и информацию по фильмам с разных источников в одну базу данных. В итоге формируется полная база с примерно 70 000 материалами.
------------
## JAVASCRIPT
- **dom**<br>
небольшой класс, с набором вспомогательных методов, для работы с dom деревом. Помимо классических методов (addClass, removeClass, find ... ), реализована функция для работы с JSX разметкой.
- **file-login.ts**<br>
Небольшой модуль который позволяет провести авторизацию по паре ssh ключей.
На сервер отправляется публичный ключ, проверяется его наличие в списке авторизованных ключей, генерируется рандомная строка, шифруется публичным ключом и отправляется в ответе на запрос.
Модуль получает строку, расшифровует ее приватным ключом, и отправляет результат снова на сервер.
На сервере происходит сравнение расшиврованной строки и, если она совпадает с ранее сгенерированной, производится авторизация.
------------
## BASH
- **wm**<br>
примеры команд из cli решения web-manager. Решение позволяет автоматизировать некоторые рабочие процессы на сервере разработки. Умеет создавать сайты, копировать, собирать проект и т.д.
------------
*примеры кода в данном репозитории взяты с реальных проектов многие из которых не прошли стадию рефакторинга и тестирования, следовательно, могут быть орфографические и логические ошибки. Основная цель, показать подход к написанию, оформлению и ведению проектов.*
