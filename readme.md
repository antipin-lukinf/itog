__Itog__

**Задача :**

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

Описание алгоритма решения:

1. Объявляем два массива: array1 (с введенными стоками) и array2 (пустой) такой же длины. 
2. метод СompletionArray2, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да элемент массива array1[i] присваивается элементу массива array2[j]. 
3. После присвоения увеличивается переменная j на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.
4. метод PrintArray распечатывает получившийся массив array2
   
Графическое представление метода в файлах: blok_shema.drawio, blok_shema.png .

