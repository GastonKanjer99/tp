# Propuesta TP DSW

## Grupo
### Integrantes
* 45976 - Bustos, Martin Emanuel
* 45810 - Kanjer, Gaston Alberto

### Repositorios
* [fullstack app](https://github.com/GastonKanjer99/tp-dsw)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
*Aplicación web para crear y gestionar personajes de Dungeons & Dragons. Los usuarios pueden crear, editar y visualizar sus personajes, incluyendo raza, clase, habilidades, objetos y trasfondo.*

### Modelo
[Mermaid](https://www.mermaidchart.com/app/projects/1807a2ba-b39c-45ee-9920-2f86883f2b7b/diagrams/f333d543-72fd-4054-bc65-bf3c643f86e4/version/v0.1/edit)

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Raza<br>2. CRUD Clase<br>3. CRUD Trasfondo|
|CRUD dependiente|1.CRUD Personaje {depende de} Raza, Clase y Trasfondo<br>2.  CRUD Hechizos {depende de} Clase|
|Listado<br>+<br>detalle| 1. Listado de personajes filtrado por clase, muestra nombre, raza y clase => detalle muestra atributos completos del personaje<br> 2.  Listado de hechizos filtrado por clase, muestra nombre, nivel y descripción breve => detalle con descripción completa y condiciones de uso|
|CUU/Epic|1. --<br>2. Editar hoja de personaje y exportarla como PDF|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1.CRUD Raza<br>2. CRUD Clase<br>3. CRUD Trasfondo<br>4. CRUD Hechizo<br>5. CRUD Objeto Mágico<br>6. CRUD Equipamiento<br>7. CRUD Usuario (jugador)|
|CUU/Epic|1. --<br>2. Editar personaje existente<br>3. Exportar hoja de personaje a PDF con su ficha completa|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Listado de personajes de un usuario, filtrado por nivel, raza o clase <br>2. Listado de objetos mágicos por tipo o rareza|
|CUU/Epic|1.Subida de avatar del personaje<br>2. Visualización de estadísticas de personajes creados (cantidad por clase, raza, etc.)|
|Otros|1. Exportación a formato PDF o impresión de la hoja de personaje|

