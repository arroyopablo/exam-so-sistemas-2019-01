#

# Examen sistemas operativos
#### Curso:  Sistemas Operativos
#### Nombre : Pablo Andres Arroyo

##Pregunta 1:
## Utilizando la puerta por fuera del for{}
tiempos (Con un argumento de 100000): 

- 0.000721 
- 0.000724 - descartado segun la guia
- 0.000723
- 0.000720
- 0.000719 - descartado segun la guia

## Utilizando la puerta por dentro del fork{}
tiempos (Con un argumento de 100000):
- 0.013656
- 0.015766 
- 0.016694
- 0.011743 - descartado segun la guia
- 0.019906 - descartado segun la guia

El programa se demora mas dado que va a estar constantemente abriendo y cerrando la puerta lo que 
conduce a que cuando esta en el ciclo utilice un tiempo para abrir y cerrar y este tiempo se va a ir 
sumando hasta que el ciclo se detenga cosa que cuando esta por fuera no sucede dado que entra hace su ejecucion y vuelve a salir solo una vez
