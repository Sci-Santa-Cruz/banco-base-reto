
# Test GFB DS team

## Sobre el repositorio 

El presente repositorio contiene la solucíon a los dos problemas del reto Test GFB DS team.


El código que representa la solución del ejercicio uno fue implentado utilizando un Jupyter Nokebook basado en Docker. La base de la imagen Docker es obtenida del repositorio oficial de Jupyter (jupyter/datascience-notebook: https://hub.docker.com/r/jupyter/datascience-notebook)

A continuación se prensenta las intrucciones para reproducir el ambiente.


## Requirements

- Instalar Docker Desktop según el tipo de SO:  https://docs.docker.com/desktop/
- Instalar Docker Compose: https://docs.docker.com/compose/

## How to build the image
- Clona or Descarga este repositorio
- Usa el comando cd para colocarte en el root path del repositorio
- Ejecuta: sudo docker-compose -f jupyter-notebook.yml up


# Estructura del projecto

```
├── README.md          <- The top-level README for developers using this project.
├── Ejercicio_1
    |
    ├── Arquitectura.pdf    
    ├── Aruitectura.png
    |
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    ├── images              <- Images and figures - Jupyter Book
├── Ejercicio_2
    |
    ├── Respuestas_y_arquitectura.pdf

```
# Referencias 
https://drivendata.github.io/cookiecutter-data-science/