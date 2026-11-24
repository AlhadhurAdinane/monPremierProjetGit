# MyProject

Une application C++ qui calcule les nombres de fibonacci en parallèle.

## Prérequis
- g++ ≥ 9.0
- make ≥ 4.0 (ou CMake ≥ 3.15)

## Installation
```bash
sudo apt-get install build-essential cmake
```
## Code Fou
```cpp
#include<vector>
#include<iostream>
using namespace std;

cout << "Je suis une phrase folle" << endl;
```
## Compilation
```bash
make                     # utilise le Makefile fourni
# ou, avec CMake :
mkdir -p build && cd build
cmake .. && cmake --build .
```

## Exécution
```bash
./bin/monprojet 10000   # calcule Fib(10000)
```

## Structure du projet
```text
MyProject/
├─ README.md
├─ Makefile
├─ include/
│  └─ myproject.h
├─ src/
│  ├─ main.cpp
│  └─ utils/
│     └─ string_utils.cpp
└─ bin/
```

## Utilisation
```bash
./bin/monprojet 5000    # Affiche le résultat et le temps d'exécution
```

## Licence
MIT License 

## Contact
mailto:alhadhuradina@gmail.com
