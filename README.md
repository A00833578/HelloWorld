## HelloWorld
# Valeria López Barcelata A00833578
TC1033 Grupo 2: laboratorio, branch, commits, pull request, merge, markdown

**bold text**
*italicized text*

1. GitHub
2. Método de calcular las frecuencias
3. Descargar los nuevos archivos de Series y Episodios

- GitHub
- Método de calcular las frecuencias
- Descargar los nuevos archivos de Series y Episodios

``````c++
// Valeria López Barcelata A00833578
// Examen Práctico Presencial
// 29 de noviembre del 2021

#ifndef Fecha_hpp
#define Fecha_hpp

#include <iostream>
#include <stdio.h>
using namespace std;

class Fecha{
  private:
    int dia, mes;
  public:
    // Métodos constructores
    Fecha();
    Fecha(int _dia, int _mes);

    // Métodos modificadores
    void setDia(int _dia);
    void setMes(int _mes);

    // Métodos de acceso
    int getDia();
    int getMes();

    // Otros Métodos
    string str();
    
};

#endif

``````
[title](https://www.markdownguide.org/cheat-sheet/)
![title](perro.jpg)
| Syntax | Description |
| ------------ | ------------ |
| Header | Title |

- [x] Enchiladas
- [ ] Huevo Ranchero
- [ ] Tamales

