**Задача**: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. 
При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
**Примеры**:
["hello", "2", "world", ":-)"] -> ["2", ":-)"]
["1234", "1567", "-2", "computer science"] -> ["-2"]
["Russia", "Denmark", "Kazan"] -> []
# Решение задачи
### Блок ввода массива из строк:
Согласно заданию, первоначальный массив вводися либо с клавиатуры, либо он задан на старте.
Переменная **lengthLimit** - согласно заданию равна 3

### **CheckArray** - Метод подсчёта количества элементов, размер которых меньше lengthLimit
Подсчёт осуществляется перебором элементов массива **arrayOfStrings** и сравнением количества их элементов с переменной  **lengthLimit**.
Результат выводится в переменную **numbersItems**.
* Подсчёт осуществляется перебором элементов массива **arrayOfStrings** и сравнением количества их элементов с переменной  **lengthLimit**.
* Результат выводится в переменную **numbersItems**.

Инициализируется новый массив строк **newArrayOfStrings**, размером, равным переменной **numbersItems**.

### **FillNewArray** - Метод формирования нового массива строк
* Формирование осуществляется перебором элементов массива **arrayOfStrings**, сравнением количества их элементов с переменной  
**lengthLimit** и добавлением в массив **newArrayOfStrings** элемента, удовлетворяющего условию.
* На выходе метода получается заполненный массив строк **newArrayOfStrings**, удовлетворяющий условию, что и является решением задачи.
* Для наглядности выводим его на экран с помощью метода **PrintArray**.
* На выходе метода получается заполненный массив строк **newArrayOfStrings**, удовлетворяющий условию, _что и является решением задачи_.

Для наглядности выводим его на экран с помощью метода **PrintArray**