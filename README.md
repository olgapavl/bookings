# bookings - учебный проект на данных системы бронирования авиабилетов. Для решения поставленных задач работа проводилась в PostgreSQL, DBeaver.

Необходимо было решить следующие задачи:
В каких городах больше одного аэропорта?
В каких аэропортах есть рейсы, выполняемые самолетом с максимальной дальностью перелета?Использовать подзапрос.
Вывести 10 рейсов с максимальным временем задержки вылета.Использовать Оператор limit.
Были ли брони, по которым не были получены посадочные талоны? Верный тип join                                   
Найдите свободные места для каждого рейса, их % отношение к общему количеству мест в самолете.Добавьте столбец с накопительным итогом - суммарное накопление количества вывезенных пассажиров из каждого аэропорта на каждый   день.Т.е. в этом столбце должна отражаться накопительная сумма - сколько человек уже вылетело из данного аэропорта на этом или более ранних рейсах за день.!Обязательное условие- оконная функция,подзапросы или/и cte.                                   
Найдите процентное соотношение перелетов по типам самолетов от общего количества.Обязательное условие - подзапрос,оператор ROUND                                               
Были ли города, в которые можно  добраться бизнес - классом дешевле, чем эконом-классом в рамках перелета?Обязательное условие - СТЕ.                                   
Между какими городами нет прямых рейсов? Обязательное условие   - Декартово произведение в предложении from,самостоятельно созданные представления,оператор  except             
Вычислите расстояние между аэропортами, связанными прямыми рейсами,сравните с допустимой максимальной дальностью перелетов  в самолетах, обслуживающих эти рейсы. Обязательное условие - Оператор RADIANS или использование sind/cosd,CASE 
                                           
                                                        
                                                        
                                                        
                                                        
