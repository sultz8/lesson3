# Третье занятие


## Циклы.

### Проблема
```php
echo "Hello!";
echo "Hello!";
echo "Hello!";
echo "Hello!";
echo "Hello!";
...
echo "Hello!";
echo "Hello!";
echo "Hello!";
```
<br />

### Циклы в php
```php
while
do...while
for
foreach
```
<br />

### Цикл for
```php
for (expr1; expr2; expr3)
    statement
// Первое выражение (expr1) всегда вычисляется (выполняется)
// только один раз в начале цикла.

// В начале каждой итерации оценивается выражение expr2.
// Если оно принимает значение true,
// то цикл продолжается и выполняются вложенные операторы.
// Если оно принимает значение false,
// выполнение цикла заканчивается.

// В конце каждой итерации выражение expr3 вычисляется (выполняется).
```

<br />

### Пример for
```php
for ($i = 1; $i <= 10; $i++) {
    echo $i;
}
```

### Пример 2 for (бесконечный цикл)
```php
for ($i = 1; $i > 0; $i++) {
    echo $i;
}
```

### Пример 2 for (ложное условие)
```php
for ($i = 1; $i < 0; $i++) {
    echo $i;
}
```

<br />

### Цикл while
```php
while (условие) {
    // Действия
}
```

### Пример while
```php
$count = 1;
while ($count <= 5) {
    echo $count . " ";
    $count++;
}
```

### Пример while (бесконечный цикл)
```php
$count = 1;
while (true) {
    echo $count . " ";
    $count++;
}
```

<br />

### Цикл do...while
```php
do {
    // Действия
} while (условие);
```

### Пример do...while
```php
$count = 1;
do {
    echo $count . " ";
    $count++;
} while ($count <= 5);
```

<br />

### break, continue
```php
// break - досрочное завершение циклы
// continue - досрочный переход к следующей итерации цикла.

for ($x = 0; $x < 10; $x++) {
    if ($x == 4) {
        break;
    }
    echo "The number is: $x <br>";
}

for ($x = 0; $x < 10; $x++) {
    if ($x == 4) {
        continue;
    }
    echo "The number is: $x <br>";
}

```

<br />
<br />

### Вложенные циклы.
```php
...
```

<br />
<br />

### Задачи на уроке.
1. [Монетки](https://acmp.ru/asp/do/index.asp?main=topic&id_course=2&id_section=10&id_topic=3)
2. Посчитать сумму чисел от 1 до 100.
3. Подсчет четных и нечетных чисел от 1 до n.
4. Считывать числа с консоли пока не введется число 0. Посчитать сумму введенных чисел.
5. Вывести квадрат(n) из звездочек (*)
6. Вывести квадратную матрицу (n) из нулей с единицами на главной диагонали.
7. Вывести квадратную матрицу (n) из нулей с единицами на побочной диагонали.
---


### Домашнее задание.
1. [Счастливый билет](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=2&id_problem=9)
2. [Две окружности](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=2&id_problem=10)