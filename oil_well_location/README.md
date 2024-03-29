# Проект "Выбор локации для скажины"

## Описание проекта
Добывающей компании «ГлавРосГосНефть» нужно решить, где бурить новую скважину.

В качестве данных предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. 

Шаги для выбора локации:

- В избранном регионе ищут месторождения, для каждого определяют значения признаков;
- Строят модель и оценивают объём запасов;
- Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
- Прибыль равна суммарной прибыли отобранных месторождений.

## Структура проекта
1. Загрузка и подготовка данных.
2. Обучение и проверка модели.
3. Подготовка к расчету прибыли.
4. Расчет прибыли и рисков.
5. Выводы.

## Использованные библиотеки
- *numpy*
- *pandas* 
- *matplotlib*
- *seaborn*
- *sklearn*