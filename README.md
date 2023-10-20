# Итоговая работа 
## первого блока обучения на программе Разработчик.
### *Была поставлена следующая задача:*  
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

Данная работа содержит блок схему показывающу работу основного метода и решение задачи на языке C#
Единственное затруднение, которое я испытал при работе над блок схемой - это описание условия сравнения. Не смог найти вариант грамотного указания условия. Писать словами посчитал не совсем верным, поэтому вынужден был указать длину элемента массива используя язык программирования, а именно **N[i].Length**

### Описание основного метода:    
В нем поочередно(изпользуя цикл **for**) сравнивается длинна каждого элемента имеющегося массива с условием задачи, а именно: он должен быть меньше, либо равен 3 символам. Элементы, соответствущие условиям записыватся в список, который по итогу преобразуется в массив, а затем выводится на экран.  
В работе дополнительно было реализовано использование конструкции **switch-case**, которая позволяет сделать выбор относительно стартового массива: либо он будет задан по умолчанию, либо задается пользователем самостоятельно.