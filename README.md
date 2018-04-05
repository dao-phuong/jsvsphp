# JS vs PHP Syntax

## Print data

```js
echo 'hello';
```

```php
console.log('hello');
```

## Variable assignment

var x = 1;
$x = 1;

## Constant assignment

const X = 1; 
define('X', 1);

## Assigning a value to multiple variables

var one, two, three = [];
$one = $two = $three = [];

## Array creation

var x = [];
$x = [];
$x = array()

## Key/value storage

var x = {
    name: 'Weltall',
    age: 50
};

$x = [
    'name' => 'Weltall',
    'age'  => 50
];

## Foreach Loop

x.forEach(function(y) { });
foreach(x as y) {}


