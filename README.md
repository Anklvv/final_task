# FinalTask 
### Задача :
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

*Описание алгоритма решения:*

- Запрашиваем у пользователя кол-во элементов массива, далее пользователь вводит стороковые значения для каждого элемента массива.
-  Далее создаем функцию, которая принимает на вход полученный массив, пробегаемся по нему циклом и считаем кол-во строк <= 3. 
- После создаем новый массив (длина массива будет равна полученному кол-ву строк <= 3) и снова пробегаемся по первоначальному массиву и добавляем в новый массив строки <= 3. 
- В конце выводим полученный массив.


_Диаграмма представлена в файле FirstTask.drawio_


_Реализация алгоритма в папке Workshop/Program.cs_