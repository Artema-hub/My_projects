# 10_Online_food_shop
______________________________________

Продажа продуктов питания. Нужно разобраться, как ведут себя пользователи мобильного приложения. Изучить воронку продаж, узнайть, как пользователи доходят до покупки. Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах и на каких именно? Кроме этого дизайнеры захотели поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно. Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. Необходимо выяснить, какой шрифт лучше.

>#### Библиотеки
>* pandas
>* matplotlib
>* seaborn
>* scipy
>* numpy
>* math

### Часть 1. Загрузка данных и подготовьте их к анализу

### Часть 2. Подготовка данных
* Замена названий столбцов;
* Проверка пропусков;
* Удаление дубликатов;
* Добавляем столбец даты и времени, а также отдельный столбец дат;

### Часть 3. Изучение и проверка данных
* Количество событий в логе;
* Количество пользователей в логе;
* Среднее количество событий на пользователя;
* Данными за какой период располагаем? Гистограма по дате и времени. Определение периода в котором имеем полные данные.

### Часть 4. Изучите воронку событий
* Какие события есть в логах и как часто они встречаются;
* Количество пользователей совершивших каждое из событий, доля пользователей, которые хоть раз совершали событие;
* Порядок в котором происходят события, определение событий по которым стоит расчитать воронку;
* Расчет воронки и ее изучение;

### Часть 5. Изучение результатов эксперимента
* Количество пользователей в каждой экспериментальной группе;
* Проверим, находят ли статистические критерии разницу между выборками 246 и 247;
* Посчитаем число пользователей, совершивших каждое событие в каждой из контрольных групп. Посчитаем долю пользователей, совершивших каждое событие. Проверим, будет ли отличие между группами статистически достоверным;

### Общие выводы и рекомендации