# Определение критериев определяющиех успешность игры 

<div style="border:solid Chocolate 2px; padding: 40px">
    
**Статус проекта:**

Завершен

**Библиотеки:**

python, pandas , numpy, matplotlib, seaborn, scipy

**Описание проекта**
    
Имеются данные о работе интернет-магазина по продаже компьютерных игр. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Необходимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.  
Данные включают в себя игры до 2016. Дата на момент исследования - декабрь 2016 года и необходимо продумать кампанию на 2017 год.  
В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».
    
**Описание данных**
    
* Name — название игры
* Platform — платформа
* Year_of_Release — год выпуска
* Genre — жанр игры
* Rating — рейтинг
    

**Общий вывод**  
    
Исходные данные представляют собой двумерную таблицу с 16715 записями и 11 признаками (столбцами). При первоначальном анализе было обнаружено больше количество пропусков в столбцах с рейнигом, годом издания игры, оценками критиков и оценками пользователей.  

Был проведен анализ исторических данных о продажах игр, оценках пользователей и экспертов, жанрах и платформах. По результатам проведенной предобработки данных были изменены названия столбцов, приведены к нужным типы данных и обработаны пропуски. После этого провели исследовательский анализ по результатам которого выяснили:

самые популярные платформы на данный момент - PS3,PS4,X360,3DS,XOne
самые прибыльные игры жанра шутер
самый выпускаемый жанр - экшн
портрет пользователя почти везде схож кроме Японии
рейтинг ESRB не влияет на продажи игр
самой перспективной в будущие годы будет приставка Playstation_4(рядом с ней будет Xbox_one) и можно предпологать в районе 2019-2020 года выпуск новых версий этих приставок


В различные года на рынке доминировали различные платформы, но набольшие продажи за всё время показала PS2. Как было выяснено из анализа распределения продаж игр на различных платформах по годам, медианное время жизни платформы составляет 10 лет, однако из графиков видно, что портативные консоли живут меньше (примерно в 2 раза).

В различные годы пользователей предпочитали различные платформы, но в период с 2007 по 2016 пользователей в большей степени интересовали Wii (2007-2009), Xbox 360 (2010), PS3 (2011-2013), PS4(2014-2016). При анализе продаж на различные платформы было выяснено, что хоть разброс значений у различных платформ и сильно отличается (игровые индустрии выпускают хиты для отдельных платформ) средние значения для всех платформ почти одинаковые: 250 тыс для стационарных консолей и 125 тыс для портативных и ПК

При анализе корреляции между оценками и продажами было выяснено, оценки пользователей вообще не коррелируют с продажами, а оценки критиков иммеют очень слабую корреляцию, что также является недостаточным для составления рекламной кампании.

Из года в год самыми популярными жанрами остаются игры в жанрах Action, Shooter и RPG.

Портрет пользователей для различных регионов имеет преимущественно одинаковый вид для всего мира. Однако в Японии люди склонны играть на портативных консолях и поэтому для них характерным жанром игр является RPG и именно японцы предпочитают игры для Teen в большей степени, по сравнению с остальным миром.

При анализе гипотез было выяснено, что оценки пользователей для платформ Xbox One и PC одинаковы, но при этом оценки для разных игровых жанров у пользователей отличаются.

самые популярные платформы на данный момент - PS3,PS4,X360,3DS,XOne
самые прибыльные игры жанра шутер
самый выпускаемый жанр - экшн
портрет пользователя почти везде схож кроме Японии
рейтинг ESRB не влияет на продажи игр
самой перспективной в будущие годы будет приставка Playstation_4(рядом с ней будет Xbox_one) и можно предпологать в районе 2019-2020 года выпуск новых версий этих приставок

Рекламную кампанию надо планировать с упором на Playstation_4 и Xbox_one    
    
