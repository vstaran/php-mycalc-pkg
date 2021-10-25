# Калькулятор

Класс калькулятора PHP, который будет принимать два значения в качестве аргументов, и складывать, вычитать, умножать и делить их.


```php
$mycalc = new MyCalc(12, 6);
```

Складывать:
```php
echo $mycalc->add();
```

Вычитать:
```php
echo $mycalc->subtract();
```

Умножать:
```php
echo $mycalc->multiply();
```

Делить:
```php
echo $mycalc->divide();
```

# Подключение

Через https://packagist.org/ :
```json
"require": {
  "vstaran/mycalc": "*"
}
```

Через файловую систему:
```json
"repositories": [
  {
     "type":"path",
     "url":"/home/project-name"
  }
]

```

после добавления исполнить команду:
```sh
composer update
```
