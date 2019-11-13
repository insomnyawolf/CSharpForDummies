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
| false| && | false | --> | true  |

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

#### Chainin If Statements

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

// ToDo 

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

// ToDo 

#### ForFach Loop

// ToDo 