# Тестовое задание для кандидатов на позицию парсинг сайтов

### Задание
Запарсить информацию из личного кабинета FIX Price (https://fix-price.ru/personal/):
* личные данные пользователя/данные карты
* список товаров в Избранном со всей информацией
* список действующих акций (доступны по ссылке выше после авторизации)

Реализовать в виде python3 скрипта, который должен запрашивать логин и пароль, парсить и сохранять информацию в текстовый файлик в произвольном («человекопонятном») формате.
В качестве учётной записи можно использовать следующие данные авторизации:
Логин: aleksandra.grinina@mail.ru
Пароль: Fixprice123
Необходимо также учесть, что парсинг не должен зависеть от учетной записи и работать на любой, а также поддерживать все виды авторизации.

### Ограничения
Всё должно быть реализовано на выполнении http запросов из кода (нельзя использовать библиотеки наподобие selenium).
В качестве библиотек рекомендуется использовать BeautifulSoup, requests (или их аналоги).
