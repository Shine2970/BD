ЛР 1

1.Выберите из таблицы orders все заказы

SELECT * FROM orders;

![image](https://github.com/user-attachments/assets/23460e5a-748e-4c98-af98-3b637623958c)

2.Выберите из таблицы orders все заказы кроме новых. У новых заказов status равен "new". Использовать in

SELECT * FROM orders WHERE STATUS IN ('cancelled','in_progress','delivery')

![image](https://github.com/user-attachments/assets/37ed988f-4a88-4c2b-bc07-a68dc8c8b53f)

3.Выберите из таблицы orders все новые и отмененные заказы. У отмененных заказов status равен "cancelled". У новых заказов status равен "new".

![image](https://github.com/user-attachments/assets/9bc193b2-02e3-4e4e-aaef-d6ea182e538e)

4.Выберите из таблицы orders все заказы содержащие более 3 товаров (products_count). Вывести нужно только номер (id) и сумму (sum) заказа.

![image](https://github.com/user-attachments/assets/2f208a4d-1ca9-4cfb-8e36-058f3dc827e7)

ЛР 2

1.Выберите из таблицы orders 3 самых дешевых заказа за всё время. Данные нужно отсортировать в порядке убывания цены. Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/6de610d5-391d-46e1-b894-db1ed9330e77)

2.Выберите из таблицы orders 2 самых дорогих заказов за всё время. Данные нужно отсортировать в порядке убывания цены. Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/3f8fe9e3-d4f4-4b08-b5ed-0d374fe9bebf)

3.Добавьте в таблицу orders данные о новом заказе стоимостью 8000 рублей. В заказе 4 товара (products).

