* Тестовые данные: Негативная проверка. Смена пароля юр.лица с неправильно заполненным полем «Старый пароль».

	тестовый сервер - https://test2.stroyrem-nn.ru/   продовый сервер - https://stroyrem-nn.ru/

* Предусловие: пользователь авторизован, открыт «Личный кабинет»

* Шаги:
1.	Выбрать "Редактировать данные"
2.	Выбрать "Юридическое лицо"
3.	В поле "Новый пароль" ввести новый пароль
4.	В поле "Старый пароль" ввести неправильный пароль
5.	Нажать "Сохранить"

* Ожидаемый результат: появляется уведомление "Неверно указан текущий пароль!", данные не сохраняются

* Постусловие: удалить тестовые данные

Автор: Надежда

* Отчет о тестировании
  
Тестовый сервер
| Дата | Время | Версия браузера Десктоп | Результат/Баг в Трелло Десктоп|  Версия браузера и ОС Тач |Результат/Баг в Трелло Тач| Дата релиза| QA  |
| --- | --- | --- | --- |  --- | --- | --- | --- |   
| 17.07.23 | 17:19 | Chrome версия 114.0.5735.199 Firefox версия 115.0.2 | PASS | Chrome версия 114.0.5735.196 MIUI 12.5.13 | SKIPPED https://trello.com/c/u4yGtNdR/143 | 16.06.23 | Надежда |  

Продовый сервер
| Дата | Время | Версия браузера Десктоп | Результат/Баг в Трелло Десктоп|  Версия браузера и ОС Тач |Результат/Баг в Трелло Тач| Дата релиза| QA |
| --- | --- | --- | --- |  --- | --- | --- | --- |   
| 17.07.23 | 17:24 | Chrome версия 114.0.5735.199 Firefox версия 115.0.2 | PASS | Chrome версия 115.0.5790.171 MIUI 12.5.13 | SKIPPED https://trello.com/c/u4yGtNdR/143 | 16.06.23 | Надежда |
| 14.08.23 | 13:10 | Yandex версия 23.7.2.768  Microsoft Edge версия 115.0.1901.204 | PASS | Chrome версия 114.0.5735.196 Samsung Galaxy A50 | SKIPPED https://trello.com/c/u4yGtNdR/143 | 13.08.23 | Наталья К. |  