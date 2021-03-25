# Template para la tarea 2 — Programación 2, FING

A continuación detallo instrucciones para desarrollar la tarea 2 de manera más cómoda ✌

## Letra de la tarea

Antes de empezar [LEE LA LETRA](https://github.com/pragmare/tarea-2-template/raw/master/LetraTarea2.pdf).

## Ejecución

Recomiendo ejecutar y testear el programa en un sistema unix, mediante los targets del Makefile.

Para compilar, basta con correr `make`, luego:

```
./principal
```

## Testeo automático

Pasos para realizar las pruebas de manera automática:

Darle permiso de ejecución a `./tester.sh`:

```
chmod +x ./tester.sh
```

Correr el script:

```
./tester.sh
```

Por defecto el script no usa **valgrind** para analizar fallos en el manejo de memoria.

Para ello se debe instalar **valgrind** en el sistema y ejecutar el script de la siguiente manera:

```
./tester.sh --valgrind
```

> ⚠ Resolver errores de manejo de memoria es más sencillo al realizar las pruebas manualmente.

## Entorno de desarrollo

### CLion

Configura una [Toolchain](https://www.jetbrains.com/help/clion/how-to-create-toolchain-in-clion.html) acorde a tu sistema para poder realizar el trabajo. Este repositorio viene con un CMakeLists.txt listo 😉.

### Visual Studio Code

Instala la extensión [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) para usar apropiadamente las características de VSCode con el lenguaje C.

## Clonar el repo

Con un sistema que cuente con git, claro:

SSH (Recomendado):

```
git clone git@github.com:pragmare/tarea-2-template.git
```

HTTPS:

```
git clone https://github.com/pragmare/tarea-2-template.git
```
