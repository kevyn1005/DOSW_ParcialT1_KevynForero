# DOSW_ParcialT1_KevynForero


1. Diagrama de contexto

![img.png](img.png)

2. Identifique 2 patrones de diseño que puedan aplicarse al caso de estudio,
   especificando por cada uno:

 - Patron Strategy el cual es de comportamiento ya que el sistema maneja multiples tipos de recursos y cada recurso maneja ciertas reglas de validacion de reserva distintas
 Por ejemplo: Los salones validan materias mientras que las salas de estudio validan un minimo de estudiantes
Este patron nos permite encapsular cada logica de validacion en distintas clases lo cual facilita la seleccion del algoritmo de reserva que se use, mejorando los tiempos de ejecucion

 - Patron Adapter el cual es estructural ya que Silabinfo debe integrarse con sistemas externos como lo es Enlace y Recursos humanos los cuales entregan informacion en formatos de cadena especificos como lo es el id o correo, ya que este solo acepta datos especificos como el correo institucional, se necesita de un adaptador que transforme las interfaces y formatos de los sistemas externos para que sean compatibles con la logica interna
s
git merge nombre de la rama