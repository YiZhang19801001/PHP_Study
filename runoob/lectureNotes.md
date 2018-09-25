### PHP Tutorial [runoob]

***
#### variables
- 简单的声明变量`$x=2`
- 数组`$cars=array("Volvo","BMW","Toyota");`
- 对象 
```php
<?php
class Car
{
  var $color;
  function __construct($color="green") {
    $this->color = $color;
  }
  function what_color() {
    return $this->color;
  }
}
?>
```
- `var_dump`可以输出变量的类型和数值。可以用于代码调试。

#### print vs echo

- print has return value and always be "1" and only output one string
- echo has not return value, and could output multiple strings in a row