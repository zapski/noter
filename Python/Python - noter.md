# Python

## Hvordan finder jeg hjælp?
- [Python?](https://www.python.org/) - Officiel Python side 
- [Beginners guide?](http://wiki.python.org/moin/BeginnersGuide/Programmers) - Officiel Python side 
- [Tutorial?](https://python.land/python-tutorial) - Officiel Python side 
- [Official Python documentation](https://docs.python.org/3/library/stdtypes.html#textseq) - Officiel Python side 
- [w3schools Python?](https://www.w3schools.com/python/default.asp) - w3schools Python side 
- [Python?](https://www.python.org/) - Officiel Python side 
- [Python?](https://www.python.org/) - Officiel Python side 
- [Python?](https://www.python.org/) - Officiel Python side 
- [Python?](https://www.python.org/) - Officiel Python side 
- [Python?](https://www.python.org/) - Officiel Python side 

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

### Navngivning af variable

Variabelnavn skal starte med et bogstav eller underscore
Variabelnavne er case sensitive
Navngivning må indeholde :
- store/små bogstaver
- numeriske værdier
- `_` underscore

### type()
Denne funktion returnerer typen af en variabel.

```
x = 1
print(type(x)) # outputs: <class 'int'>
```	

#### String

Ved tildeling kan både enkelt og dobbelt gnyg bruges.

##### Escaping karakterer

Hvis behov for specialtegn kan disse escapes med `\`

##### Multible linier.

Her benyttes 3 gnyg's (`'`,`"`)
Med denne teknik kan strengen både indeholde enkelt/dobbelt gnyg. 

`line = """He said: "Hello, I've got a question" from the audience"""`

##### len
Finder længden af en streng

`len(mystring)`

##### split

`'Hello world'.split(' ')` splitter på mellemrum
`'Hello \t\n there,\t\t\t stranger.'.split()` splitter på "whitespace" (space, tabs, newlinne)

##### reverse

Der findes ikke en funktion til dette. Men strenge behandles i Python som lister og følgende kode kan "reverse" en streng

```
mystring = 'Hello world'
mystring[::-1]
```
#### f-strings - formatted strings

```
my_age = 40
f'My age is {my_age}'
```

```
>>> f'3 + 4 = {3+4}'
'3 + 4 = 7'
>>> my_age = 40
>>> f'My age is, unfortunately, not {my_age-8}'
'My age is, unfortunately, not 32'
```

Se flere gode eksempler : https://docs.python.org/3/tutorial/inputoutput.html#formatted-string-literals






## print til consolen

`print('Hello World!')`

## Keyboard input

```
name = input('Enter your name:')
print(name)
```

## Operatorer

Fungerer som forventet.
Brug paranteser for at overstyre den matamatisk præsedens.

Det "sidste" resultat kan benyttes i den efterfølgende operation hvor det kan refereres med `_` (underscore).

```
3 + 3
_ + 3

Dette resulterer i 9
```







---
