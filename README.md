# Итоговая проверочная работа

Данная работа необходима для проверки знаний и навыков по итогу прохождения первого блока обучения
на программе разработчик. Необходимо убедиться, что базовое знакомство с языком программирования __С#__ прошло успешно.
___
### *Задача алгоритмически не самая сложная, однако для полценного выполнения проверочной работы необходимо:*
___
1. Создать репозиторий на GitHub;
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части);
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md);
4. Написать программу на языке программирования C#, решающую поставленную задачу;
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что все залито одним коммитом, как минимум этапы 2, 3 и 4 должны быть расположены в разных коммитах).
___
## **Задача:**
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше, либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте
выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

*Примеры:*

>["hello", "2", "world", ":-)" -> ["2", ";-)"]

> ["1234", "1567", "-2", "comruter science"] -> ["-2"]

> ["Russia", "Denmark", "Kazan"] -> [  ]
___

## **Решение задачи**
### **Алгоритм решения:**
1. Задаем массив значений;
2. Далее программа проверяет все значения заданного массива на соответствие условию: ***длина значения меньше или равна 3 символа***;
3. Если значение удовлетворяет условию, то оно добавляется в конечный массив;
4. Цикл длится до тех пор, пока не будет реализован перебор всех значений заданного массива;
5. Программа выводит конечный массив, результатом которого будут заданные элемент, состоящие из трех и менее символов.
___
### **Блок-схема:**
![Блок-схема](/Verification%20work/solution%20algorithm.drawio.png)
___
### **Программа:**
Программа решения содержится в файле **Program.cs**, который находится в папке **Verification work**, расположенной в данном репозитории.
