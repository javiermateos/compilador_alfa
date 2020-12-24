# Compilador ALFA

Repositorio para realizar la practica 5 del proyecto de automatas y lenguajes, 
correspondiente al compilador completo.

# Contenido del repositorio

- bison : carpeta con los archivos de bison.
- fllex : carpeta con los archivos de flex.
- include : archivos cabecera del proyecto.
- lib : librerias complementarias del proyecto.
- ref : archivos de referencia de teoria.
- src : archivos de codigo fuente del proyecto.
- test: archivos en lenguaje alfa y sus pruebas.
- compile.sh : script de compilacion de los programas alfa.
- Makefile : archivo con las intrucciones de compilacion del compilador.
- programa.json: archivo con un mapa conceptual de las reglas del compilador.
- index.png: imagen del mapa conceptual.

nota: para poder abrir y modificar el archivo _programa.json_ es necesario utilizar
la pagina web [Mindmap Make](https://app.mindmapmaker.org/#m:new).

# Instrucciones de compilacion y pruebas

```sh
make # genera el ejecutable del compilador
make test # ejecuta todas las pruebas
```
nota: alguno de los test muestran como diferencias lineas en blanco. Esto es
por que alguno de los outputs tienen al final del documento una linea de más.
