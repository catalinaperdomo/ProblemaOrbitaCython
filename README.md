# ProblemaOrbitaCython

El repositorio contiene el problema del Planeta en Orbita, con el fin de comparar el rendimiento de la solucion del problema al ejecutarlo en Cython y Python.

Para la solución del problema se crearon los siguientes programas:

orbita_cy.pyx: Este programa resuelve el problema del planeta en orbita en lenguaje cython
orbita_py.py: Este programa que resuelve el problema del planeta en orbita en lenguaje python
principal.py: Se combina el programa de python y de cython y se calcula el tiempo de ejecución de cada uno
setup.py: Lo convierte en un objeto compartido, es un fichero de comparación
