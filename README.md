1.Выберите из таблицы orders все заказы
SELECT * FROM orders;
![image](https://github.com/user-attachments/assets/23460e5a-748e-4c98-af98-3b637623958c)
2.Выберите из таблицы orders все заказы кроме новых. У новых заказов status равен "new". Использовать in
SELECT * FROM orders WHERE STATUS IN ('cancelled','in_progress','delivery')
![image](https://github.com/user-attachments/assets/37ed988f-4a88-4c2b-bc07-a68dc8c8b53f)
3.Выберите из таблицы orders все новые и отмененные заказы. У отмененных заказов status равен "cancelled". У новых заказов status равен "new".
![image](https://github.com/user-attachments/assets/9bc193b2-02e3-4e4e-aaef-d6ea182e538e)
4.Выберите из таблицы orders все заказы содержащие более 3 товаров (products_count). Вывести нужно только номер (id) и сумму (sum) заказа.
