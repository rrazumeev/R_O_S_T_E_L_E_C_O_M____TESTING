* Тестовые данные:

 Функцонал формы "Оплата заказа" шаг 2 поле адресная строка
 
 e-mail - sabina.test60@gmail.com
 
 password - СШ123456
 
 тест сервер - https://test2.stroyrem-nn.ru/
 
 прод сервер - https://stroyrem-nn.ru/
 
 * Окружение: 

	Десктоп: браузер Chrome версия 114.0.5735.199, Yandex Версия 23.7.0.2526
	
	Тач: Cмартфон Xiaomi mi 9 lite MIUI 12.5.2
 
* Предусловие:
 
 1.Пользователь авторизован
 
 2.В корзину добавлен один товар
 
 3.Открыта форма оплаты заказа "Доставка и оплата"
 
 4.В поле населенный пункт внесен -  "Нижний Новгород"
 

* Шаги:

  1.В поле "Адрес" внести "улица Королёва 1" (адрес за пределами Нижнего Новгорода)
 

* Ожидаемый результат:

   1.Поле не находит указанный адрес, так как такой улице нет в Нижнем Новгороде
   
   2.В выпадающем списке предлагаются возможные адреса из Нижегородской обл., или под полем краcными буквами прописано "Адреса в базе нет, укажите точку на карте"
  

Автор: Сабина

1. Десктоп
* Тестовый сервер 

Тест выполнен
| Дата | Время | Результат | Имя | Баг № Trello |
| --- | --- | --- | --- | --- |
| 2023-08-05 | 14:52 | PASS | Сабина |   |
| 2023-08-12 | 23:38 | PASS | Алёна |   |

* Продовый сервер

Тест выполнен
| Дата | Время | Результат | Имя | Баг № Trello |
| --- | --- | --- | --- | --- |
| 2023-07-13 | 14:25 |  | Сабина |   | 

2. Тач
   Тест выполнен
   | Дата | Время | Результат | Имя | Баг № Trello |
   | --- | --- | --- | --- | --- |
   | 2023-08-12 | 23:39 | PASS | Алёна |   |

* Продовый сервер

Тест выполнен
| Дата | Время | Результат | Имя | Баг № Trello |
| --- | --- | --- | --- | --- |
