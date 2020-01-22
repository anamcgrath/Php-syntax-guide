# Php-syntax-guide
#### Complete guide to PHP syntax including descriptions and examples

Note: All php code must be enclosed in php brackets, even when you are writing to a file with the php extension. Php coded like this: `<?php echo "those are the php brackets"; ?>`
## PHP Comments

```
// two double slashes represent a single line php comment like this 

/* A multi-line comment begins with forward slash and asterisk and ends with an asterisk and backslash  */ 
```

## PHP Variables

A variable is used to store values like numbers, characters, names and strings. 
```
$name = “A variable starts with a dollar sign and is followed by the value or name.”;
```


## PHP Echo / Print

Echo and print statements are used to output values onto the page. They are used in a very similar way. The difference between the two though is, “echo” can take multiple parameters while “print” can only take one argument and can only ever return one. 
```
echo "Hey there!”;

print "Hey there!“;

```
## PHP Data Types

Php data types are the values that can be assigned to a variable. These are the data types that a variable accepts:

### Integers, Decimals and Fractions
These could be expressed in decimal, hexadecimal numbers or octal notation. They can be positive or negative numbers.
E.g.` 1, -1, 0x1A, 01, 1.23, 10.2e3, 16e-10 `

### Strings
Strings are a line of characters. Each character is the size of a byte. Any data type can be inside of a string but it most be enclosed by single or double quotes.
E.g ` $variable = “string” or $variable = ’string’ `

### Booleans
True(1) or false(0)
E.g. `$variable = true; `

### Arrays
Arrays hold multiple variables at one time.
e.g.
```
$animals = array(
    “Mammal” => “horse”,
    “Reptile” => “alligator”,
    “Amphibian” => “salamander”
);
```


### Objects
Objects can store both values and functions.

### Null 

A variable with no value. It is represented as “NULL”.
E.g. ` $variable= NULL; `

### Resources
These are used to store or call references to an external php resource.

## PHP Strings

A string is a series of characters and one character is the same as a byte. They can be single or double quoted.
``` 
echo ‘this is a simple string’; 
```


## PHP Numbers
Php numbers can be integers(positive and negative), floats(decimal numbers), infinity and NaN(no number).
A way to check if a numeric value is boolean is by using the `is_numeric()` function.
E.g. 
``` 
$a = -456.78;
var_dump(is_numeric($a)); 
```
Returns:
```
bool(true)
```



## PHP Constants
A constant is a value that cannot change. It is the same throughout the whole script. You can create a constant with the ` define() ` function. Remember that constants are case sensitive.
```
define(“Name”, “My name is Ana McGrath“);
echo Name;
```


## PHP Operators

The operators perform operations on variables and values. There are Arithmetic Operators, Assignment Operators, Comparison Operators, Incrementing and Decrementing Operators, Logical Operators, String Operators, Array Operators. For some examples check out this [website](https://www.tutorialrepublic.com/php-tutorial/php-operators.php).

## PHP If & Else & Elseif
The if statement will execute code if the parameters in the condition statement are true. The else statement will execute if the if statement was false. The elseif statement will execute if the if statement was false and its condition statement is true.
```
if ($decision = true) {
    echo “You are correct!”;
} elseif ($decision = false) {
    echo “Your answer is incorrect.”
} else {
   echo “Please select an answer.”
}
```



## PHP Functions

A function is a block statement that is created in code and can be executed throughout the page by calling the function. PHP has many built in functions. A list of over 1000 built in php functions is found on [php.net](https://www.php.net/manual/en/indexes.functions.php).


```
function birth($name, $year) {
    echo $name . “was born in” .  $year;
}
birth("Ana", "1976");
```

## PHP Arrays
An array uses one variable to store multiple values.
```
$fruits = array(“oranges”, ”apples”, “nectarines”, “grapes”);
echo “My favourite fruits are “ . $fruits[0] . “, “ . $fruits[1] . “, “ . $fruits[2] . “and “ . $fruits[3] ;

```

## PHP Loop
Loops are used to repeat certain lines of code as long as a conditional statement remains true.

### While loop
A while loop will continue to execute as long as the condition statement is true.
```
$x = 1;

while($x < 3) {
    echo $x;
    $x++;
}
```
### Do while
The do while loop is very similar to the while loop except it runs through the code once and then will continue to do it while the constraint stays true.
```
$x = 1;
do {
 echo $x;
    $x++;
 } while($x  < 3); 
   
```
### For 
The for loop is used when you already know how many times the script should run before running it.
```
for ($x= 0, $x< 3, $x++) {
    echo $x;
}
```

### For each
The for each loop is used on arrays and loops through each element in the array.
```
$fruits = array(“oranges”, ”apples”, “nectarines”, “grapes”);
foreach($fruits as $val) {
  echo $val;
}
```

Go to [W3Schools](https://www.w3schools.com/php) for more information on PHP syntax 

