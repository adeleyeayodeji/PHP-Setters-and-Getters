# PHP-Setters-and-Getters
Getters and setters are used to control the access to class properties. They are used to set and get the values of a class's properties.

[![Video](https://img.youtube.com/vi/19KmJghCHdE/maxresdefault.jpg)](https://www.youtube.com/watch?v=19KmJghCHdE)

```php
<?php

/**
 * What are getters and setters methods in PHP?
 * 
 * Getters and setters are used to control the access to class properties. They are used to set and get the values of a class's properties.
 * 
 */

class Person
{
    private $name;

    //setter
    function setter($name): void
    {
        $this->name = $name;
    }

    //getter
    function getter(): string
    {
        return $this->name;
    }
}

//init
$person = new Person();
//set name 
$person->setter("BiggiDroid 3");
//display
echo $person->getter();


```
