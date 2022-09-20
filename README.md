# Simple Exercises to start coding

## Documentation

### Arithmetic Operations

#### Plus ( + )

* Number

```
2 + 3 = 5
```

On some language you can use '+' to concatenate strings

```
"Hello" + "Tav" = "HelloTav"
```

#### Minus ( Modulus )

* Number

```
10 - 3 = 7
```

#### Multiply ( * )

* Number

```
3 * 5 = 15
```

#### Divide ( / )

* Result: Quotient of a division

```
11 / 2 = 5
```

#### Modulus ( % )

* Result: Remainder of a division

```
11 % 2 = 1
```

### Boolean Operations

#### And ( && )

| Value 1 | Comparator | Value 2 | | Result |
| :---: | :---: | :---: | :---: | :---: |
| true | && | true  | --> | true  |
| true | && | false | --> | false |
| false| && | true  | --> | false |
| false| && | false | --> | false |

#### Or ( || )

| Value 1 | Comparator | Value 2 | | Result |
| :---: | :---: | :---: | :---: | :---: |
| true | \|\| | true  | --> | true  |
| true | \|\| | false | --> | true  |
| false| \|\| | true  | --> | true  |
| false| \|\| | false | --> | false |

#### Greater ( > )

| Value 1 | Comparator | Value 2 | | Result |
| :---: | :---: | :---: | :---: | :---: |
| 1 | > | 0 | --> | true  |
| 1 | > | 1 | --> | false |
| 0 | > | 1 | --> | false |

#### Greater or Equal ( >= )

| Value 1 | Comparator | Value 2 | | Result |
| :---: | :---: | :---: | :---: | :---: |
| 1 | >= | 0 | --> | true  |
| 1 | >= | 1 | --> | true  |
| 0 | >= | 1 | --> | false |

#### Lesser ( < )

| Value 1 | Comparator | Value 2 | | Result |
| :---: | :---: | :---: | :---: | :---: |
| 1 | < | 0 | --> | false |
| 1 | < | 1 | --> | false |
| 0 | < | 1 | --> | true  |

#### Lesser or Equal ( <= )

| Value 1 | Comparator | Value 2 | | Result |
| :---: | :---: | :---: | :---: | :---: |
| 1 | <= | 0 | --> | false |
| 1 | <= | 1 | --> | true  |
| 0 | <= | 1 | --> | true  |

#### Equal ( == )

| Value 1 | Comparator | Value 2 | | Result |
| :---: | :---: | :---: | :---: | :---: |
| 1 | == | 0 | --> | false |
| 1 | == | 1 | --> | true |
| "Hello" | == | "Hello" | --> | true  |
| "Hello" | == | "World" | --> | false  |


#### Not ( ! )

| Expresion | | Result |
| :---: | :---: | :---: |
| !true  | --> | false |
| !false | --> | true  |

### Conditional Sentences

#### If

##### True

```cs
if (true)
{
    // This piece of code is executed
}
```

##### False

```cs
if (false)
{
    // This piece of code is not executed
}
```

#### Chaining If Statements

```cs
if (false)
{
    // This piece of code is not executed
}
else if (true)
{
    // This piece of code is executed
}
else
{
    // This piece of code is not executed
}
```

```cs
if (false)
{
    // This piece of code is not executed
}
else if (false)
{
    // This piece of code is not executed
}
else
{
    // This piece of code is executed
}
```

#### Switch

Simple `==` comparationm the code that will be executed is the one with the matching pattern branch.
If none of the branches match the code executed will be the une under the `default` keyword

```cs
int foo = 2;
switch (foo){
    case 1:
        break;
    case 2:
        break;
    case 3:
        break;
    default:
        break;
}
```

### Data Types


#### Integer types

Can hold a Integer number without any decimal part.

##### Signed

They store the value and if they are positive or negative numbers

| Type | Range | Size |
| :---: | :---: | :---: |
| sbyte | -128 to 127 | 1 byte |
| short | -32.768 to 32.767 | 2 bytes |
| int | -2.147.483.648 to 2.147.483.647 | 4 bytes |
| long | -9.223.372.036.854.755.808 to 9.223.372.036.854.775.807 | 8 bytes |

##### UnsignedSigned

Can store larger numbers but they cannot store if they are positive or negative

| Type | Range | Size |
| :---: | :---: | :---: |
| byte | 0 to 255 | 1 byte |
| ushort | 0 to 65.535 | 2 bytes |
| uint | 0 to 4.294.967.295 | 4 bytes |
| ulong | 0 to 18.446.744.073.709.551.615 | 8 bytes |

#### Floating point numeric types

// To Do

#### Boolean

Can hold exactly two states: `true` or `false`

```cs
bool isEnabled = true;
//Code
isEnabled = false;
```

#### Character

Can hold a single character of a text. This datatype depends on the encoding. UTF8 has variable sizes of each character, cause the table is extended.

```cs
char myChar;
myChar = 'h';
string myString = "Hello";
myString+=myChar; //Append the character
//Content in myString: Helloh
```

#### Enum

Enums are enumerables, which is a pseudo data type that can hold several enumerable states.

```cs
enum AudioFormat : byte
{
    MP3 = 0,
    AAC = 1,
    OPUS = 2,
    VORBIS = 3
}

AudioFormat format;

format = AudioFormat.MP3;
```
This is used when you want to store a state or a type in a variable but make it easier for the human to be readable in code.

#### Struct

With a struct, you can put multiple variables into one variable.

```cs
struct Vector
{
    double x;
    double y;
    double z;
}

Vector myVec = { 1.1231, 1.44533, 4.232323 };

Console.WriteLine(myVec.x);
Console.WriteLine(myVec.y);
Console.WriteLine(myVec.z);

/* Prints
 * 1.1231
 * 1.44533
 * 4.232323
 */
```

### Variables

A variable is something that keeps a value in a way so it can be used / changed later in the code

### Loops

They are used to repeat a piece of code multiple times 

#### For Loop

```cs 
for (int i = 0; i < 10; i++)
{
    // This code is repeated 10 times
}
```

#### While Loop

```cs 
while (condition)
{
    // This code is repeated till the condition is false
}
```

#### DoWhile Loop

Same as do loop but the code inside will be executed at least once.

```cs 
do
{
    // This code is repeated till the condition is false
} while (condition):
```

#### ForFach Loop

Iterates trougth all the elements in a collection 

```cs
List<Things> = new List<Tings>();
foreach(Thing in things)
{
    // Code Here
}
```

## Exercises

### Arithmetic

#### Simple

* Check if a number is odd or even

#### With loops
