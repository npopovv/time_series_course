# Homework 1.
## Базовые понятия для анализа временных рядов. Авторегрессионные модели.

1. (2 балла) Для чего нужно понятие стационарности в анализе временных рядов? Перечислите все случаи и распишите свой ответ.
2. (1 балл) Рассмотрите картинку data/images/ts_types.png.
a. Назовите ряды с гетероскедастичностью 
b. Какие ряды имеют сезонность? 
с. Какие ряды имеют цикличность? 
d. Какие ряды можно приблизить моделью интегрированного ряда?
e. Какие ряды можно считать стационарными? 
3. (3 балла) Рассмотрите один из графиков индекса Доу-Джонса (data/dataset/dow_jones.csv). Предположим, вы можете сделать только одно преобразование ряда, чтобы сделать его стационарным.
Какое преобразование вы выберете и почему? Сделайте это преобразование, проверьте, получили ли вы стационарный ряд. Какой ARMA моделью можно описать получившийся стационарный ряд? 
4. (2 балла) Рассмотрите ряд data/dataset/stl_example.csv. Постройте для него график автокорреляции.̆ Обьясните закономерности, которые вы видите. 
5. (4 балла) На семинаре, посвященном stl разложению мы находили период сезонности сезонных временных рядов при помощи графика автокорреляций.
    Однако, если бы мы захотели построить автоматическую систему определения периода, мы бы уже не могли “вручную” анализировать каждый график.
    Таким образом вам необходимо написать функцию get_seasonal_period(), которая бы автоматически определяла период сезонных временных рядов, использую автокорреляционную функцию.  
6. (4 балла) Используя подход box-jenkins построит̆е модель ARIMA для временного ряда dow_jones_0. Сделайте прогноз на 30 точек вперед. Интерпретируйте полученный результат.
7. (7 баллов) Доделать семинар **stl.ipynb**
8. (7 баллов) Доделать семинар **arima.ipynb**
