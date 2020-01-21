# Php-syntax-guide
#### Complete guide to PHP syntax including descriptions and examples

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


## PHP If & Else & Elseif



## PHP Functions



## PHP Arrays



## PHP Loop



Go to [W3Schools](https://www.w3schools.com/php) for more information on PHP syntax 

