# Core Java
## What's enough for an SDET

---

# Chapter - 1

## Understanding Classes

+++

## What it contains ?
<font size = 6>
- Variables  <!-- .element: class="fragment" -->
- Methods  <!-- .element: class="fragment" -->
- Constructors  <!-- .element: class="fragment" -->
- Instance Block  <!-- .element: class="fragment" -->
- Static Block  <!-- .element: class="fragment" -->

+++

## We need to know
<font size = 6>
```
  DataTypes
  FlowControl
  ExceptionHandling
  Objects
  Methods
  SourceFiles
  Modifiers
```
<span class="code-presenting-annotation fragment current-only" data-code-focus="1">@color[red](byte, short, int, long, float, double, char, boolean)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="2">@color[red](if, else, switch, case, default, break, for, while, do, continue)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="3">@color[red](try, catch, finally, throws, throw)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="4">@color[red](new, this, super, instanceof)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="5">@color[red](void, return)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="6">@color[red](class, extends, interface, implements, package, import)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="7">@color[red](public, private, protected, final, static, abstract)</span>                                              

---

# Chapter - 2

## Handling data in variables

+++

## What are datatypes ???

+++

## Datatypes

<font size = 6>
```
    byte
    short
    int
    long
    float
    double
    char
    boolean
```

<span class="code-presenting-annotation fragment current-only" data-code-focus="1">@color[red](Size: 1 byte - Default: 0)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="2">@color[red](Size: 2 bytes - Default: 0)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="3">@color[red](Size: 4 bytes - Default: 0)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="4">@color[red](Size: 8 bytes - Default: 0)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="5">@color[red](Size: 4 bytes - Default: 0.0)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="6">@color[red](Size: 8 bytes - Default: 0.0)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="7">@color[red](Size: 2 bytes - Default: < > //space)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="8">@color[red](Size: NA - Default: false)</span>

+++

## What are variables ???

+++

## LOCAL

- Declared inside a method/constructor/block 
- Scope limits within the declared method/constructor/block 
- Memory allocated when execution of method/constructor/block begins 
- Memory released when execution of method/constructor/block completes 

+++

## Instance

- Declared inside the class, but outside of any method/constructor/block
- Scope limits within the class, across all method/constructor/block(s), with reference to class object
- Memory allocated when class object is created
- Memory released when class object is destroyed

+++

## Static

- Declared inside the class, but outside of any method with Static prefix
- Scope limits with the class
- Memory allocated when .class file loaded into JVM
- Memory released when JVM completes execution

+++

## Instance Vs Static

- Access instance variables from instance area
- Access instance variables from static area
- Access static variables from instance area
- Access static variables from static area

+++

## Variables Vs Default values

- Assignment vs Default for static
- Assignment vs Default for instance
- Assignment vs Default for local

+++

## Class Vs Objects

[Image](assets/C&O.png)

+++

## Classification
<font size = 6>
```
Primitive
Class
Array
ENUM
```

<span class="code-presenting-annotation fragment current-only" data-code-focus="1">@color[red](int i = 10)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="1">@color[red](float f = 10.0)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="2">@color[red](Test t = new Test())</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="2">@color[red](Employee e = new Employee())</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="3">@color[red](int[] numbers)</span>
<span class="code-presenting-annotation fragment current-only" data-code-focus="3">@color[red](String[] strings)</span>

---

# Chapter - 3

## Keep the flow in control

+++

## How, I ask, How ???

+++

## Logics

- IF
- FOR
- SWITCH
- WHILE

+++

## IF

- if
- if else
- if else if

+++

## FOR

+++

## Switch

+++

## While

- while
- do while

