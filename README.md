## Лабораторные работы по дисциплине Биостатистика и анализ систем 

1) lab1.ipynb
   
Целью лабораторной работы является построение эмпирической функции дожития, условной функции дожития (при условии дожития до момента t, где t возможно задать в качестве параметра), гистограммы по экспериментальным данным, а также аппроксимации эмпирической функции дожития кривой дожития Гомперца. Оценку параметров кривой Гомперца при аппроксимации можно производить любым методом (методом максимального правдоподобия, методом наименьших квадратов). В качестве экспериментальных данных берется выборка моментов гибели (измеряется в днях) лабораторных животных при различных биологических экспериментах - life_expectancy.txt

 Результатом лабораторной работы № 1 является компьютерная программа,которая выводит в графическом режиме эмпирическую функцию дожития, условную функцию дожития (на произвольно заданный момент) и гистограмму по предложенным экспериментальным данным, а также оценивает параметры аппроксимирующей кривой Гомперца и строит данную кривую.

Нелинейная минимизация метода наименьших квадратов и подбор кривых для Python:
 https://lmfit.github.io/lmfit-py/

 Установка pip install lmfit 

