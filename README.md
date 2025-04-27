# Sistema de Gestión de Torneos de eSports 

## Autor 
Andrés Alberto Budiziszewski González 

AndresBudziszewski

## Descripción del Proyecto 
La idea de este trabajo de la asignatura de Entornos de Desarollo es la creación de una aplicación de gestión de torneos de eSports.
 
EL objetivo de dicha tarea es afianzar conceptos de UML y del propio Paradigma de Orientación a objetos. En este repositorio he creado un diagrama de clases y uno de usos sobre la parte de Gestion de equipos y jugadores de la aplicación.

Tras analizar el enunciado y de cara al diseño del diagrama de usos encontré 1 actor, el administrador, y 2 entidades, equipo y jugador.

[](https://github.com/AndresBudziszewski/AD3_UML_Torneo_eSports.git)

## Diagramas UML 
### Diagrama de Casos de Uso 
![Diagrama de casos de uso](diagramas/DiagramaDeUsos.jpg)
 
### Diagrama de Clases 
![Diagrama de clases](diagramas/DiagramaDeClases.jpg)

## Justificación del diseño

Como mencionaba en la descripción, a la hora de plantear los diagramas encontré los siguientes casos: Registrar jugadores, añadir jugadores a un equipo, consultar lista de equipos y jugadores. El primer caso, el de registrar jugador no venía especificado en el enunciado pero decidí incluirlo ya que al igual que hay una opción de registrar equipos y de añadir jugadores a los equipos debería de existir un caso de registrar a los propios jugadores. Estos cuatro casos los considero independientes ya que no dependen entre si para poder realizarse, pero si que veo relación entre ellas.

Decidi incluir dos casos nuevos al esquema justamente por eso, y son: Comprobar si jugador está registrado y Comprobar si equipo esta registrado. Estos casos serían implementados tanto por los casos de registro como por el de añadir a equipo ya que así evitaríamos que se intente añadir un jugador o un equipo no registrado o que se intente registrar un jugador o un equipo que ya registrado.

Tambien observé que entre los registros y el añadir jugadores hay una relacion de herencia ya que esto podría ser un método que los registros puedan heredar tal cual para utilizar, no algo que implementen y tengan que reescribir. 

Como actor solo encontre la figura del administrador, no vi que ninguna otra figura calificara como actor.

## Conclusiones  
Este proyecto me ha servido para entender mucho mejor, no solo UML y su representación con los diagramas de uso y clases, si no también ha ver el propio paradigma de orientación a objetos de una manera mas gráfica. Además, cabría destacar que me ha sido útil para entender mucho mejor como organizar el codigo en distintas capas y las funciones que tiene cada parte de un proyecto.