<h1 align="center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br>
<br>
<br>
<br>
<br>
<br>
<p align="center">Лабораторная работа №12</p>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<p align="right">Алексеев Максим максимович</p>
<p align="right">Проверил: Соболев Е. И.</p>
<br>
<br>
<br>
<br>
<br>
<br>

<p align="center">г. Южно-Сахалинск <br> 2023 год</p>

<h2 align="center">Введение</h2>
<p align="justify">Задачи на php</p>

<h2>Цели и задачи</h2>
1.	Создайте массив, заполненный числами от 1 до 100. Найдите сумму элементов данного массива.
<br>
3.	Дан массив с элементами 'a', 'b', 'c', 'd', 'e'. С помощью функции array_map сделайте из него массив 'A', 'B', 'C', 'D', 'E'.
<br>
4.	Дан массив $arr. Подсчитайте количество элементов этого массива.
<br>
5.	Дан массив $arr. С помощью функции count выведите последний элемент данного массива.
<br>
6.	Дан массив с числами. Проверьте, что в нем есть элемент со значением 3.
<br>
7.	Дан массив [1, 2, 3, 4, 5]. Найдите сумму элементов данного массива.
<br>
8.	Дан массив [1, 2, 3, 4, 5]. Найдите произведение (умножение) элементов данного массива.
<br>
9.	Дан массив $arr. С помощью функций array_sum и count найдите среднее арифметическое элементов (сумма элементов делить на их количество) данного массива.
<br>
10.	Создайте массив, заполненный числами от 1 до 100.
<br>
11.	Создайте массив, заполненный буквами от 'a' до 'z'.
<br>
12.	 Создайте строку '1-2-3-4-5-6-7-8-9' не используя цикл.
<br>
13.	Найдите сумму чисел от 1 до 100 не используя цикл.
<br>
14.	 Найдите произведение чисел от 1 до 10 не используя цикл.
<br>
15.	Даны два массива: первый с элементами 1, 2, 3, второй с элементами 'a', 'b', 'c'. Сделайте из них массив с элементами 1, 2, 3, 'a', 'b', 'c'.
<br>
16.	Дан массив с элементами 1, 2, 3, 4, 5. С помощью функции array_slice создайте из него массив $result с элементами 2, 3, 4.
<br>
17.	Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice преобразуйте массив в [1, 4, 5].
<br>
18.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice запишите в новый массив элементы [2, 3, 4].
<br>
19.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice сделайте из него массив [1, 2, 3, 'a', 'b', 'c', 4, 5].
<br>
20.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice сделайте из него массив [1, 'a', 'b', 2, 3, 4, 'c', 5, 'e'].
<br>
21.	 Дан массив 'a'=>1, 'b'=>2, 'c'=>3'. Запишите в массив $keys ключи из этого массива, а в $values – значения.
<br>
22.	 Даны два массива: ['a', 'b', 'c'] и [1, 2, 3]. Создайте с их помощью массив 'a'=>1, 'b'=>2, 'c'=>3'.
<br>
23.	Дан массив 'a'=>1, 'b'=>2, 'c'=>3. Поменяйте в нем местами ключи и значения.
<br>
24.	 Дан массив с элементами 1, 2, 3, 4, 5. Сделайте из него массив с элементами 5, 4, 3, 2, 1.
<br>
25.	Дан массив ['a', '-', 'b', '-', 'c', '-', 'd']. Найдите позицию первого элемента '-'.
<br>
26.	 Дан массив ['a', '-', 'b', '-', 'c', '-', 'd']. Найдите позицию первого элемента '-' и удалите его с помощью функции array_splice.
<br>
27.	Дан массив ['a', 'b', 'c', 'd', 'e']. Поменяйте элемент с ключом 0 на '!', а элемент с ключом 3 - на '!!'.
<br>
28.	Дан массив '3'=>'a', '1'=>'c', '2'=>'e', '4'=>'b'. Попробуйте на нем различные типы сортировок.
<br>
29.	Дан массив с элементами 'a'=>1, 'b'=>2, 'c'=>3. Выведите на экран случайный ключ из данного массива.
<br>
30.	 Дан массив с элементами 'a'=>1, 'b'=>2, 'c'=>3. Выведите на экран случайный элемент данного массива.
<br>
31.	Дан массив $arr. Перемешайте его элементы в случайном порядке.
<br>
32.	 Заполните массив числами от 1 до 25 с помощью range, а затем перемешайте его элементы в случайном порядке.
<br>
33.	 Создайте массив, заполненный буквами от 'a' до 'z' так, чтобы буквы шли в случайном порядке и не повторялись.
<br>
34.	 Сделайте строку длиной 6 символов, состоящую из маленьких английских букв, расположенных в случайном порядке. Буквы не должны повторяться.
<br>
35.	Дан массив с элементами 'a', 'b', 'c', 'b', 'a'. Удалите из него повторяющиеся элементы.
<br>
36.	Дан массив с элементами 1, 2, 3, 4, 5. Выведите на экран его первый и последний элемент, причем так, чтобы в исходном массиве они исчезли.
<br>
37.	 Дан массив с элементами 1, 2, 3, 4, 5. Добавьте ему в начало элемент 0, а в конец - элемент 6.
<br>
38.	 Дан массив с элементами 1, 2, 3, 4, 5, 6, 7, 8. С помощью цикла и функций array_shift и array_pop выведите на экран его элементы в следующем порядке: 18273645. 
<br>
39.	 Дан массив с элементами 'a', 'b', 'c'. Сделайте из него массив с элементами 'a', 'b', 'c', '-', '-', '-'.
<br>
40.	 Заполните массив 10-ю буквами 'x'.
41.	 Создайте массив, заполненный целыми числами от 1 до 20. С помощью функции array_chunk разбейте этот массив на 5 подмассивов ([1, 2, 3, 4]; [5, 6, 7, 8] и т.д.).


<h2>Решение задач</h2>

```php
<!DOCTYPE html>
<html>
	<head>
		<title>Лабораторная 12</title>
	</head>
	
	<body>		
        <h4>Задание 1: </h4>
        <?php
             $arr = range(1, 100);
             $sum = array_sum($arr);
             echo $sum;
        ?>
        <br>

        <h4>Задание 2: </h4>
        <?php
            $arr = array('a', 'b', 'c', 'd', 'e');
            $arr = array_map('strtoupper', $arr);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 3: </h4>
        <?php
            $arr = array(1, 2, 3, 4, 5);
            $count = count($arr);
            echo $count;
        ?>
        <br>

        <h4>Задание 4: </h4>
        <?php
            $last = $arr[count($arr) - 1];
            echo $last;
        ?>
        <br>

        <h4>Задание 5: </h4>
        <?php
            $arr = array(1, 2, 3, 4, 5);
            $ech = "false";
            for($i = 0; $i < count($arr); $i++)
            {
                if($arr[$i] == 3)
                {
                    $ech = "true";
                }
            }
            echo $ech;
        ?>
        <br>

        <h4>Задание 6: </h4>
        <?php
            $arr = array(1, 2, 3, 4, 5);
            $sum = array_sum($arr);
            echo $sum;
        ?>
        <br>

        <h4>Задание 7: </h4>
        <?php
            $arr = range(1,5);
            $result = 1;
            for($i = 0; $i < count($arr); $i++)
            {
                $result *= $arr[$i];
            }
            echo $result
        ?>
        <br>

        <h4>Задание 8: </h4>
        <?php
            $arr = range(1,5);
            $Sred = array_sum($arr) / count($arr);
            echo $Sred;
        ?>
        <br>

        <h4>Задание 9: </h4>
        <?php
            $arr = range(1, 100);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 10: </h4>
        <?php
            $arr = range('a', 'z');
            print_r($arr);
        ?>
        <br>

        <h4>Задание 11: </h4>
        <?php
            $str = implode('-', range(1, 9));
            echo $str;
        ?>
        <br>

        <h4>Задание 12: </h4>
        <?php
            $sum = array_sum(range(1, 100));
            echo $sum;
        ?>
        <br>

        <h4>Задание 13: </h4>
        <?php
            $product = array_product(range(1, 10));
            echo $product;
        ?>
        <br>

        <h4>Задание 14: </h4>
        <?php
            $arr1 = array(1, 2, 3);
            $arr2 = array('a', 'b', 'c');
            $arr12 = array_merge($arr1, $arr2);
            print_r($arr12);
        ?>
        <br>

        <h4>Задание 15: </h4>
        <?php
            $arr = array(1, 2, 3, 4, 5);
            $arrresult = array_slice($arr, 1, 3);
            print_r($arrresult);
        ?>
        <br>

        <h4>Задание 16: </h4>
        <?php
            $arr = array(1, 2, 3, 4, 5);
            array_splice($arr, 1, 2);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 17: </h4>
        <?php
            $arr = array(1, 2, 3, 4, 5);
            $newArr = array_splice($arr, 1, 3);
            print_r($newArr);
        ?>
        <br>

        <h4>Задание 18: </h4>
        <?php
            $arr = range(1,5);
            array_splice($arr, 3, 0,array('a','b','c'));
            print_r($arr);
        ?>		
        <br>

        <h4>Задание 19: </h4>
        <?php
            $arr = range(1,5);
            array_splice($arr, 1, 0,array('a','b'));
            array_splice($arr, 6, 0, 'c');
            array_splice($arr, 8, 0, 'e');
            print_r($arr);
        ?>
        <br>

        <h4>Задание 20: </h4>
        <?php
            $arr = array('a' => 1, 'b' => 2, 'c' => 3);
            $keys = array_keys($arr);
            $values = array_values($arr);
            print_r($keys);
            print_r($values);
        ?>
        <br>

        <h4>Задание 21: </h4>
        <?php
            $arr1 = array('a', 'b', 'c');
            $arr2 = array(1, 2, 3);
            $arr = array_combine($arr1, $arr2);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 22: </h4>
        <?php
            $arr = array('a' => 1, 'b' => 2, 'c' => 3);
            $arr = array_flip($arr);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 23: </h4>
        <?php
            $arr = arr(1, 2, 3, 4, 5);
            $arr = array_reverse($arr);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 24: </h4>
        <?php
            $arr = array('a','-','b','-','c','-','d');
            echo array_search('-',$arr);
        ?>
        <br>

        <h4>Задание 25: </h4>
        <?php
            $arr = array('a','-','b','-','c','-','d');
            array_splice($arr, array_search('-', $arr), 1);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 26: </h4>
        <?php
            $arr = array('a', 'b', 'c', 'd', 'e');
            $arr[0] = '!';
            $arr[3] = '!!';
            print_r($arr);
        ?>
        <br>

        <h4>Задание 27: </h4>
        <?php

            $arr = array('3' => 'a', '1' => 'c', '2' => 'e', '4' => 'b');

            echo "Сортировка по значениям в возрастающем порядке";
            asort($arr);
            print_r($arr);

            echo "Сортировка по значениям в убывающем порядке";
            arsort($arr);
            print_r($arr);

            echo "Сортировка по ключам в возрастающем порядке";
            ksort($arr);
            print_r($arr);

            echo "Сортировка по ключам в убывающем порядке";
            krsort($arr);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 28: </h4>
        <?php
            $arr = array('a'=>1,'b'=>2,'c'=>3);
            echo array_rand($arr);
        ?>
        <br>

        <h4>Задание 29: </h4>
        <?php
            $arr = array('a'=>1,'b'=>2,'c'=>3);
            echo $arr[array_rand($arr)];
        ?>
        <br>

        <h4>Задание 30: </h4>
        <?php
            $arr = array(1, 2, 3, 4, 5);
            shuffle($arr);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 31: </h4>
        <?php
            $arr = range(1, 25);
            shuffle($arr);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 32: </h4>
        <?php
            $arr = range('a', 'z');
            shuffle($arr);
            print_r($arr);
        ?>
        <br>

        <h4>Задание 33: </h4>
        <?php
            $arr = range('a','z');
            shuffle($arr);
            $str = '';
            for($i = 0; $i < 6; $i++)
                $str.= $arr[$i];
            echo $str;
        ?>
        <br>

        <h4>Задание 34: </h4>
        <?php
            $arr = array('a','b','c','b','a');
            print_r(array_unique($arr));
        ?>
        <br>
        
        <h4>Задание 35: </h4>
        <?php
            $arr = range(1,5);
            echo array_shift($arr);
            echo " ";
            echo array_pop($arr);
            ?>
        <br>

        <h4>Задание 36: </h4>
        <?php
            $arr = range(1,5);
            array_unshift($arr, 0);
            array_push($arr, 6);
            print_r($arr);			
        ?>
        <br>

        <h4>Задание 37: </h4>
        <?php
            $arr = range(1,8);
            for ($i = 0; $i < count($arr);){
                echo array_shift($arr);
                echo array_pop($arr);
            }
        ?>
        <br>

        <h4>Задание 38: </h4>
        <?php
            $arr = array('a', 'b', 'c');
            $arr = array_merge($arr, array('-', '-', '-'));
            print_r($arr);
        ?>
        <br>

        <h4>Задание 39: </h4>
        <?php
            $arr = array_fill(0, 10, 'x');
            print_r($arr);
        ?>
        <br>

        <h4>Задание 40: </h4>
        <?php
            $arr = range(1, 20);
            $chunk = array_chunk($arr, 4);
            print_r($chunk);
        ?>
        <br>
	</body>
</html>	
```

<h2>Вывод</h2>
Я научился работать с php, и использовать методы
