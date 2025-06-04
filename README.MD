# GitHub actions 
Practicas del bootcamp de Github Actions en Código Facilito

## Clase 1 - Introducción

GitHub actions es una herramienta de GitHub que permite automatizar tareas relacionadas en nuestro repositorios.


### Conceptos claves.

- Workflows
    - Conjunto de procesos automatizados en formato YAML en .github/workflows 
- Triggers **on**
    - Eventos accionan el workflow 
- Jobs **jobs**
    - Unidades independientes de trabajo dentro de un workflow (jobs)
    - Se ejecutan de paralelo por defecto.
    - Un Job puede poseer multiples pasos.
    - Cada Job corre en un runner.
- Steps **name,uses/run**
    - Pasos individuales dentro de un Job.
    - Se ejecutan secuencialmente en el mismo runner.
- Runners **runs-on**
    - Entornos (Máquinas virtuales) donde se ejecutan los jobs.


## Clase 2 - YAML y Workflows

Los **Jobs** se ejecutan de forma paralela por lo que si necesitamos hacerlo de forma secuencial podemos usar **needs** que acepta una lista de
nombre de jobs.





