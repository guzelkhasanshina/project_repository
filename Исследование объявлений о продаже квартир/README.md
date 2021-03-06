# Исследование объявлений о продаже квартир


В распоряжении имеется архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно определить рыночную стоимость объектов недвижимости. Задача — установить параметры, которые позволят построить автоматизированную систему: отследить аномалии и мошенническую деятельность.  
По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.   

В ходе работы:  
1. Проведена предобработка данных.
2. Изучены следующие параметры: площадь, цена, число комнат, высота потолков. Пострены гистограммы для каждого параметра.
3. Изучено время продажи квартиры.
4. Определены факторы больше всего влияющие на стоимость квартиры
5. Выделено 10 населённых пунктов с наибольшим числом объявлений. Посчитана средняя цена квадратного метра в этих населённых пунктах.

Анализ данных проведен средствами Python с использованием библиотек *Pandas*, *Matplotlib*. 


