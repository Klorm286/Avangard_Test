# Avangard_Test

Этот репозиторий содержит проект, посвященный анализу и визуализации данных о продажах товаров для дома и мебели

# Задачи

* Найти самые популярные подгруппы товаров за все время, предыдущие 2 года, предыдущие 4 года

* Построить boxplot («Ящик с усами») на основе продаж, избавиться от аномалий и представить четкую картину распределения величин.

* Определить основные тенденции и паттерны по регионам и подгруппам товаров. Выделить наиболее «прибыльную» группу.

# Стек

<p float="left">
  <img alt="Python" height="50" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Python_logo_and_wordmark.svg/486px-Python_logo_and_wordmark.svg.png" width="169" />
  <img alt="Pandas" height="50" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/512px-Pandas_logo.svg.png?20200209204934" width="124" />
  <img alt="Matplotlib" height="50" src="https://upload.wikimedia.org/wikipedia/en/thumb/5/56/Matplotlib_logo.svg/540px-Matplotlib_logo.svg.png?20090730120601" width="270" />
</p>

# Этапы работы

## Вычисление самых популярных групп товаров

* Фильтрация данных по дате (если нужно)

* Группировка по подкатегориям товаров и подсчет количества покупок

* Выбор топ 4 подгрупп товаров с наибольшим количеством покупок

* Построение гистограммы с помощью Matplotlib

Во всех периодах чаще всего покупали товары из категорий "Binders", "Paper", "Furnishings" и "Phones"

## Построение boxplot на основе продаж

* Выявление выбросов с помощью правила трех сигм - выбросов найдено не было

* Расчет среднего арифметического и медианы для опредения мажоритарной черты распределения продаж

Аномальных значений найдено не было, распределение продаж немного смещено вправо (справа от медианы больше данных).

## Определение основных тенденций и паттернов по регионам и подгруппам товаров.

* Разделение товаров на "группы продаж" - "Маленькие" (<10 000), "Средние" (10 000 - 30 000), "Высокие" (>30 000)

* Вычисление для каждой группы в каждом регионе общей суммы продаж, средней суммы продаж и количества сделок.

* Создание столбчатой диаграммы для сравнения сумм продаж по группам в каждом регионе

* Создание boxplot для отображения распределения продаж в разных регионах

* Создание гистограммы для сравнения количества продаж по группам и регионам

  Анализ таблицы с агрегированными данными о продажах по регионам и группам выявляет следующие основные тенденции:

1) **Калиниград** демонстрирует наибольшую сумму продаж среди всех регионов, за ним следует **Владивосток**, затем **Урал** и **Москва**.
2) **Группа "Высокие"** является наиболее прибыльной во всех регионах, демонстрируя наибольшую сумму и среднюю стоимость продаж.
3) **Группа "Средние"** показывает наибольшее количество сделок во всех регионах.

## Дополнительная информация

Этот проект может быть интересен для студентов, начинающих аналитиков, маркетологов, а также для всех, кто интересуется анализом данных в сфере продаж. 

## Как использовать проект:

1. Клонируйте репозиторий.
2. Установите необходимые библиотеки.
3. Запустите скрипты.


## Автор: 

Варламов Евгений

## Контакты: 

VarlamovEvgA@gmail.com
