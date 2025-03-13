ЛР 1

1.Выберите из таблицы orders все заказы

'''
SELECT * FROM orders;
'''

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

![image](https://github.com/user-attachments/assets/11d54dfc-f39b-4381-8b39-08db0a22c9a2)

![image](https://github.com/user-attachments/assets/7472531a-e42f-458c-9899-9699d2e65cea)

4.Добавьте в таблицу products новый товар — «VR-очки», стоимостью 70000 рублей в количестве (count) 2 штук.

 ![image](https://github.com/user-attachments/assets/dabf7dc4-b441-4a55-8bea-48950d5cd7dc)

 ![image](https://github.com/user-attachments/assets/0154c806-38a1-45b6-b78f-ca24592eaeb0)

5.В таблицу products внесли данные с ошибкой, вместо "PS5" в наименовании написали IMAC. Исправьте ошибку.

![image](https://github.com/user-attachments/assets/45f95fbc-ed0f-4fd9-bc35-5b8a190ecc46)

![image](https://github.com/user-attachments/assets/1288a625-6daf-4162-8be0-1e61b328eea4)

Лр 3 

Создайте таблицу users с полем id типа INT и двумя текстовыми полями, которые будут хранить имя (first_name) и фамилию (last_name). Длина имени и фамилии не превышает 50 символов.

Добавьте в таблицу трех пользователей: Дмитрия Иванова, Анатолия Белого и Дениса Давыдова.

![image](https://github.com/user-attachments/assets/d729b1c5-e31a-4e60-88c1-ad851c497f26)

![image](https://github.com/user-attachments/assets/4096d56a-3ebb-4e19-a839-ecc0fd60b75a)



