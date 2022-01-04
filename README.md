# project_hse_insurance_2021_2022

Добрый день!

Данный программный продукт предназанчен для предсказания платежеспособности страховой компании по имеющейся статистике показателей (см. подробнее разъяснение ниже). 

Просто запустите jupyter-файл ('проект (игрушечная модель на python).ipynb') и введите интересующий сценарий.

Для обучения модели используются данные, загруженные с информационного портала Спарк Интерфакс. Они с сгруппированы в файлы spark2019.xlsx, spark2018.xlsx, spark2017.xlsx и spark2016.xlsx.

Тестовые данные расположены в папке test_data. Для добавления статистике о новой компании, создайте excel-файл с такой же структурой, как и все находящиеся там файлы (просто скопируйте имеющися тестовый файл и изменяйте уже там). Новый файл назовите test_, где вместо _ стоит следующий после последнего номер: то есть, если, например, последний файл test4.xlsx, то следующий файл назовите test5.xlsx.

Обратите внимание, что если введеная вами компания не содержит данные хотя бы по одному из перечисленных ниже показателей хотя бы за один год, программа работать не будет.

Показатели, которые используются в модели:

1) 'Заключено договоров'
2) 'Средняя страховая премия, RUB'
3) 'Количество страховых выплат, разы'
4) 'Средняя страховая выплата, RUB'
5) 'Капитал/Активы'
6) 'Страховые резервы/Активы'
7) 'Кредиторская задолженность/Активы'
8) 'Доля отказов выплат, %'
9) 'Доля расходов на ведение дела (РВД), %'
