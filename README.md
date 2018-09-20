# Инвентаризатор

Небольшой демонстрационный пример мобильного приложения для проведения инвентаризации на базе платформы [Naviaddress](https://naviaddress.com).

Приложение поддерживает следующие функции:
* Создание карточки объекта имущества
* Сканирование QR-кода и вызов карточки объекта
* Поиск по названию или навиадресу
* Поиск ближайших объектов
* Показ карточки объекта
* Печать наклейки с QR-кодом

При разработка приложения были использованы следующие библиотеки и API:
* [Naviaddress API](https://developer.naviaddres.com)
* Библиотека для сканирования QR-кодов [Instascan](https://github.com/schmich/instascan)
* Библиотека для печати QR-кодов [qrcodejs](https://github.com/davidshimjs/qrcodejs)
* CSS-фреймворк [Ratchet](http://goratchet.com/) для разработки мобильных приложений

Ознакомиться с рабочей версией программы можно по адресу: http://agershun.github.io/inventarizator.

## Примечание

Для работы программы нужно создать файл `config.js`, содержащий следующие строки, в которых нужно
указать логин и пароль, зарегистрированные на сайте [https://staging.naviaddress.com/map](https://staging.naviaddress.com/map):
```js
let email = 'test@test.com';
let password = 'password';
```

(c) А.Гершун, 2018
