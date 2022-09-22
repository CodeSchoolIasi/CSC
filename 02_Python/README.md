# Python 

### Python vs C++

In C++ folosesti un compilator care converteste codul tau sursa in codul masina, limbajul calculatorului si creeaza un fisier executabil care poate fi apelat separat.

![alt text](https://github.com/cezarovici/CSC/blob/master/02_Python/Translation.png "logo title")


Locul in care rulati Python se numeste __interpretor__
__Interpretorul__ este un program care converteste codul scris intr-un limbaj intermediar, numit *byte code*. Acest cod, este tot binar(contine doar 1 si 0) dar nu este recunoscut de catre procesor, acest lucru facandu-l mai lent, deoarece este rulat print-o masina virtuala.

**-Nu este nevoie sa declari variabile asa cum faceam in C++**
**-Nu este nevoie de ```;```**

### How to print something 

```python
print("Hello World!")
```
Spre deosebire de C++, functia print("") afiseaza si un rand nou(```endl```) la final

Asa cum ziceam si mai sus, Python nu are nevoie de prea multe caractere aditionale ```{ } ;``` pentru rularea codului, dar e foarte strict in privinta cu organizarea lui. Acest lucru se cheama **indentare**

Indentarea este modul de a delimita blocurile de comenzi. De obicei se foloseste spatierea prin tab-uri, dar merge si printr-un numar stabilit de prima comanda indentata

**Exemplu**
```python
Asa da
x = 1
if x == 1:
    # indented four spaces
    print("x is 1.")
    if x < 0 :
        print("x > 0")
        print("Stop if 'x<0')
    else
        print("x < 0 )
        print('Stop else')
    
    print('out of second if and else')
    print('stop first if')
```
Nu mai folosim acolada pentru delimtarea comenzilor care se vor executa daca expresiile sunt adevarate sau false, se executa cele delimitate de acestea cu 4 spatii

```python
# Asa nu ( This is a python comment )
x = 1 
if x == 1:
    print("x=1")
  print("ouf of if")

# Se va genera o eroare de indentare ( This is a python comment )
```




### Resurces
```
https://realpython.com/python-vs-cpp/
https://pythongeeks.org/interpreter-in-python/
```