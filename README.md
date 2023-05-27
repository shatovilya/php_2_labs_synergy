# 2_labs

## Исходные данные

1. Создай скрипт, который обрабатывает массив чисел arr и получает новый массив, который содержит только числа из arr из диапазона от a до b. То есть, проверка имеет вид a ≤ arr[i] ≤ b.
Числа a , b и массив из 20 элементов формируется случайным образом в диапазоне [-20, 50]. В результате в окно браузера выводится исходный массив, границы диапазона a и b, и результирующий массив.

2. Cоздать php-скрипт, в котором создать массив, содержащий названия фильмов, организованных по жанрам. пусть это будет массив, в котором имена ключей будут жанрами ("мелодрама", "боевик", "детектив" и пр.), а элементами – названия фильмов. Просмотреть созданный массив в цикле, выводя название жанра и связанные с ним фильмы в окно браузера

## Пояснение к програмному коду

### 1 задание

Файл 1.php

В этом скрипте мы сначала создаем массив из 20 случайных чисел в диапазоне [-20, 50] с помощью цикла for и функции rand(). Затем мы генерируем случайные числа a и b в том же диапазоне с помощью функции rand().

Далее мы создаем новый массив $newArr и заполняем его только теми числами из исходного массива $arr, которые находятся в диапазоне от a до b. Мы используем цикл foreach для перебора всех элементов массива $arr и проверяем каждый элемент на соответствие условию a ≤ arr[i] ≤ b. Если элемент удовлетворяет условию, то мы добавляем его в новый массив $newArr.

Наконец, мы выводим результаты на экран с помощью тегов HTML. Если в заданном диапазоне нет чисел из исходного массива, то выводится соответствующее сообщение.

### 2 задание

Файл 2.php

В этом скрипте мы создаем массив $movies, в котором имена ключей являются жанрами фильмов, а элементами являются массивы с названиями фильмов. Затем мы используем два вложенных цикла foreach, чтобы перебрать все жанры и связанные с ними фильмы, и выводим их на экран в виде HTML-тегов.

Каждый жанр выводится в заголовке второго уровня h2, а связанные с ним фильмы выводятся в виде маркированного списка <ul> с помощью цикла foreach. Мы используем теги HTML для форматирования вывода и улучшения читабельности.
