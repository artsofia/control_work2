# Контрольная задача:

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Описание решения задачи:

1. Создаем метод для ввода с клавиатуры строки и возвращаем строку.

2. Создаем метод для ввода с клавиатуры строки и возвращаем число.

3. Создаем метод для заполнения массива элементами, используя первый метод и второй, чтобы задать длину массива.

4. Создаем метод для решения задачи, т.е. вывода нового массива. Перебираем каждый элемент массива и задаем **условие**: ***если*** длина строки <= 3, ***значит*** выводим данный элемент. 

5. Используем метод для заполнения массива и выводим результат, используя метод для вывода нового массива, указав в методе новый заполненный массив.