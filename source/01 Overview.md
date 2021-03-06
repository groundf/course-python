### Stage 1

In the *Stage 1* you will not only learn the basics of Python programming language, but also how to setup your development environment, how to use the command line interface and how to use another services as `GitHub` together with *Git* tool. Your knowledge after this stage will be shallow but you will be able to solve some basic and practical problems.

### Stage 2

In the *Stage 2* you will learn how to solve general and practical problems with Python.

### Stage 3

Choode your path:

1. Python for data analysis.
2. Python for automated testing.
3. Python for scientific programming.

## Setup

- Installation and usage of command line interface.
- Installation of Python (v3) interpeter.
- Overview of GitHub service and creation of an account (GitHub Web and CLI).
- Installation of Git and basic commands.
- Your first Python program ("hello world").

## Basics

- package, module and import
- constant and variable: name, type, value (binding)
- named function, anonymous function aka Lambda, scope and closure
- built-in functions: an overview
- decorator

- conditions: `if`, `elif`, `else`
- iterations: `while`, `for`


## Class and Object

- custom types via `class` definition
- regular class vs data class `@dataclass(...)` decorato
- abstratc class and protocol class
- property, instance method, class method, static method
- speacial (magic) methods `__method__`
- mutable vs immutable
- refence (`id(obj)`) vs attribute equality, overloading `__eq__`, `__hash__` and so on
- `Enum` class

## Collections

- `Mutable` vs `Immutable`
- `List` and `Tuple`
- `Dict`, `DefaultDict`
- ...
- Comprehension: list, dict
- iterator, generator aka lazy evaluation, continuation



## Data types and data structures

- Number (int, float, decimal, fraction)
- String

### Containters

- Sequence: List, Tuple, Set
- Mapping: Dictionary
- Array, Matrix
- Comprehension (list, dict) and slicing
- sorting: https://docs.python.org/3/howto/sorting.html

## Type annotations

Type annotations also called *type hints* are usually not a mandatory in dynamically typed languages such as Pytho, Ruby etc., but in many cases, they can help you to better understand of source code. Althought we can easily anotate tho code such as this without any problems

- Dynamic vs static typing
- Type hints and static analysis
- MyPy and Pylance and

```python
def plus(a: int, b: int) -> int:
    return a + b
```

, for an advanced type annotations we have to import a typing module which contains many usefull classes and functions or decorators.

```python
import typing
```

## Code formatting

- Indentation
- Using `black`!

## Functions

- What is a function (builtin vs custom).
- What if function doesn't return value?
- Funtion without arguments
- Function with one argument
- Function with one argument and default value
- Funtionn with multiple arguments
- Using named and default arguments (How to define default empty list!)
- Using `*args`and `*kwargs*`
- How to write proper function comment.
- closure, variable scope
- higher order functions and functional programming

## Modules & Packages

- module definition
- module import and export
- package definition

## Decorators

## Classes & Methods

- abstract classes & inheritance
- single vs multiple inheritance
- special (magic) methods and operators
  - `__init__`, `__new__`, `__dict__`
  - `[]`, ``
- properties, abstract, static and class methods
- dataclasses https://docs.python.org/3/library/dataclasses.html; https://realpython.com/python-data-classes/
- `__slots__`
- protocols, nominal vs structurel subtyping

### Methods

### Properties

## Exceptions

Error handling and exceptions.

## File IO

- How to read and write to/from file, synchronous (blocking) API.
- Using `pathlib`
-  `with` statement; using cotext manager (`with open(...) as _`)

## Context manager

- Writing `__enter__`,` __exit__` for your class.
- https://peps.python.org/pep-0343/

## Calendar, Date and Time

How to work with date and time.

- `date` module
- `date`, `time`, `datetime`, `timedelta` classes
- `time.min`, `time.max` properties
- `datetime.combine(datetime.now(), time.min)`

## Pattern Matching

- https://peps.python.org/pep-0636/

## Iterators and Generators

- `__iter__`, `__next__`, `yield`, `yield from`

## Jupyter and Notebooks

How to work with interactive notebooks.
- Using Jupyter and JupyterLab web interface.
- Using Visual Studio Code Editor interface.
- Convert script to netobook and vice versa.
- Manage code and notes in notebook and best practices.

## Async/Await

Asynchronous (non-blocking) programming.

## Metaprogramming

- Reflection

## Testing

- Unit tests with `pytest`
- `assert`, `fixture`, `test-case`
- https://docs.pytest.org/en/6.2.x/fixture.html
- `pytest.mark`
- `pytest.parametrize`

## Style guide

prefer

    week_start: date

over

    start_of_week: date


## Typed and Functional features

- Higher-order functions
- Referential transparency and pure functions
- Function composition (nesting)
- map, filter enumerate, zip
- itertools, functools
- Currying and partial application
- Typing module in depth

## Standard Library

An overview of some useful standard library modules.

## Resources

- https://github.com/groundf/python-cheatsheet
- https://pythontic.com/
- https://medium.com/@jorlugaqui/how-to-get-the-latest-earliest-moment-from-a-day-in-python-aa8999bea945
- https://stackoverflow.com/questions/36731949/2359-vs-0000-as-start-end-time

- [More Monads in Python](https://medium.com/swlh/more-monads-in-python-178492f482f6)
- [Haskell: The List Monad](https://www.schoolofhaskell.com/school/starting-with-haskell/basics-of-haskell/13-the-list-monad)
- [Mimic the behavior of a class in Python with currying](https://towardsdatascience.com/classes-in-functional-programming-ee48a50b6235)

## P??ebrat

Co V??s nau????me
????astn??ci kurzu se nau???? z??klad??m jazyka Python, sezn??m?? se s jeho syntax??, nau???? se pou????vat moduly, p??istupovat k soubor??m, zachyt??vat v??jimky, pou????vat objektov?? orientovan?? techniky, vytv????et velk?? projekty a pou????vat Python nap????klad p??i tvorb?? WWW.
Po??adovan?? vstupn?? znalosti
Z??kladn?? znalosti programov??n??
Metody v??uky
Odborn?? v??klad s praktick??mi uk??zkami, cvi??en?? na po????ta????ch.
Studijn?? materi??ly
Ti??t??n?? prezentace prob??ran?? l??tky
Osnova kurzu
??vod

z??kladn?? vlastnosti Pythonu
porovn??n?? s ostatn??mi jazyky (C, Pascal, Visual Basic, Perl, atd.)
pro?? a k ??emu lze pou????vat Python
Z??klady jazyka

struktura k??du, koment????e
prom??nn?? a p??i??azen??, z??kladn?? datov?? typy
oper??tory, aritmetick?? v??razy a logick?? v??razy
????sla a ??et??zce -- form??tov??n??, modul string
z??kladn?? datov?? struktuty: seznam, n-tice, slovn??k

+ ????zen?? b??hu programu
    + p????kazy pro v??tven??
    + p????kazy pro opakov??n??

+ Funkce a procedury
    + definice funkc??, procedur a jejich pou??it??
    + platnost prom??nn??ch, p??ed??v??n?? parametr??, atd.

+ Moduly
    + sezn??men?? s moduly
    + standardn?? moduly Pythonu
    + pravidla rozsahu, atd.

+ Pr??ce se soubory

    + z??klady pr??ce se soubory
    + otev??r??n?? soubor??, ??ten??, z??pis
    + souborov?? objekty

+ Chyby a v??jimky

sezn??men?? s v??jimkami
typy, vyvol??n??, zachycen?? a obsluha v??jimek
slo??it??j???? pou??it?? v??jimek
Skripty

vytvo??en?? skriptu a jeho spu??t??n??
argumenty p????kazov??ho ????dku
p??esm??rov??n??
skripty v UNIXu a ve Windows
Objektov?? orientovan?? programov??n??

z??klady OOP
t????dy, vlastnosti a metody
konstruktory a destruktory
d??di??nost a v??cen??sobn?? d??di??nost
dal???? vlastnosti OOP v Pythonu
