# Python

## Hvordan finder jeg hjælp?
- [What is Python?](https://docs.microsoft.com/en-us/learn/modules/intro-to-python/2-what-is-python) - forklarer Python/overordnet 

## Udfør Python kode ....

Python kode/script kan udføres i to forskellige modes:

- **Interactive mode** - dette er default mode hvis der ikke overgives en fil
    - Alle kommandoer udføres omgående når der trykkes *enter*
- **Script mode**
	- Her udføres indholdet af en **.py** fil 

## REPL - **R**ead-**E**val-**P**rint-**L**oop

Er en intern utility til at afprøve/verificere "stumper" af Python kode

- `python` opstarter denne utility
- Hjælp
  - `help()` - så viser forskellige kommandoer
  - `help([object])` hvor *object* er kommando eller lignende


## Variable

Variable har både navn og datatype.
Typen defineres af det data der tildeles. 
Variable er case sensitive.

- `x = 1`         # assign variable x the value 1
- `y = x + 5`     # assign variable y the value of x plus 5
- `z = y`         # assign variable z the value of y
- `x = True`
- `x = 'This is a string'`
- `x = 'Hello' + ' ' + 'World!'`

Typer: integer, decimal, boolean (intern repræsenteret som integer hvor **True=1**), string    

### type()
Denne funktion returnerer typen af en variabel.

```
x = 1
print(type(x)) # outputs: <class 'int'>
```	

## print til consolen

`print('Hello World!')`

## Keyboard input

```
name = input('Enter your name:')
print(name)
```







---
