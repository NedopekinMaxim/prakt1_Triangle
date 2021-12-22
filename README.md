# Практическая работа № 1
Работа по  дисциплине "Введению в информационные технологии"

Московский технический университет свзяи и информации

Выполнил: Недопекин Максим Алексеевич БВТ2105

Проверил: Грач Маратович

Задание: написать алгоритм для решения задачи с треугольником

1.Цель работы: создать алгоритм, который из введеных чисел находит 3 максимальных из которых можно составить треугольник, а затем находит площадь такого треугольника. Если из предложенных чисел невозможно создать треугольник, алгоритм должен выводить ошибку. Затем выложить выполненную работу на репозиторий Git.

2.Ход работы :

a) Создаем новый проект в PyCharm, файл main.py, в котором будет реализован алгоритм. При помощи input() вводим через запятую входные данные, стороны треугольника

b) При промощи split() создаём список с нашими введенными данными, преобразуем строковые данные списка в целочисленные, сортируем массив по убыванию.

c) Создаем цикл, в котором находим наибольшие стороны, при которых возможно построить треугольник, находим периметр из этих сторон и площадь такого треугольника.

d) Результат выполненной работы: алгоритм выводит значения максимальных сторон, максимальную площадь треугольника.

e) Выкладываем выполненную работу на репозиторий Git.
