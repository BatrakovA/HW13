# Homework13	Домашнее задание к лекции «Основы парсинга и работы с API»
## todo

### 

***Задание 1***

Будем парсить страницу со свежеми новостям на habr.com/ru/all/.

Вам необходимо собирать только те статьи, в которых встречается хотя бы одно требуемое ключевое слово. Эти слова определяем в начале кода в переменной, например:

KEYWORDS = ['python', 'парсинг']

Поиск вести по всей доступной preview-информации (это информация, доступная непосредственно с текущей страницы).

В итоге должен формироваться датафрейм вида: <дата> - <заголовок> - <ссылка>


***Задание 2***

Написать скрипт, который будет проверять список e-mail адресов на утечку при помощи сервиса Avast Hack Ckeck. Список email-ов задаем переменной в начале кода:
EMAIL = [xxx@x.ru, yyy@y.com]

В итоге должен формироваться датафрейм со столбцами: <дата утечки> - <источник утечки> - <описание утечки>

Подсказка: сервис работает при помощи "скрытого" API. Внимательно изучите post-запросы.