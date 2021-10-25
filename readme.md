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

## Подключение

В зависимости он нужного способа подключения, добавить в файл composer.json

Через packagist.org:
```json
"require": {
  "vstaran/mycalc": "*"
}
```


Через github:
```json
"repositories": [
  {
     "type":"github",
     "url":"git@github.com:vstaran/php-mycalc-pkg.git"
  }
]

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
