## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?
(valor 1.5)

estar seguro de que funcione las BD
guardar la informacion de las BD
que se pierdan los datos datos
Solucionar problemas que existan de los datos
Asegurar bien cada uno de los datos

2. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)

Instalar, configurar y gestionar bases de datos.
Dar soporte al equipo de desarrollo, seguridad informática y redes.
Definir el esquema del diccionario de datos.
Especificar restricciones de integridad para asegurar los datos.
Garantizar la alta disponibilidad de la base de datos.

3. En una BD al usuario del sistema se le brindarán recursos para realizar diversas
operaciones sobre estos archivos, tales como: (valor 1.5)

ingresar, eliminar y renovarar datos en archivos que ya existen de la BD
ingresar archivos nuevos en la BD, insertar, eliminar, renovar y obtener datos de archivos que ya existen en la BD
Actualizar sólo datos de archivos existentes
Eliminar archivos que existan en la BD

4. ¿Qué es un Sistema de Información? (valor 1.5)

es un conjunto  de información o datos que se estructuran o se organizan,y que por lo general almacena de forma electrónica su informacion

## Práctica 2.

2. Diseño de un modelo relacional

Objetivo: Representar desde un modelo entidad relación un problema


Ejercicio:

Tenemos que diseñar una base de datos sobre proveedores y disponemos de la siguiente
información:

Realiza el modelo entidad relación. (valor 6)

Tenemos esta información sobre una cadena editorial:

● La editorial tiene varias sucursales, con su domicilio, teléfono y un código de
sucursal.

● Cada sucursal tiene varios empleados, de los cuales tendremos su nombre,
apellidos, NIF y teléfono. Un empleado trabaja en una única sucursal.

● En cada sucursal se publican varias revistas, de las que almacenaremos su título,
número de registro, periodicidad y tipo.

● Una revista puede ser publicada por varias sucursales.

● La editorial tiene periodistas (que no trabajan en las sucursales) que pueden
escribir artículos para varias revistas. Almacenaremos los mismos datos que para
los empleados, añadiendo su especialidad.

● También es necesario guardar las secciones fijas que tiene cada revista, que
constan de un título y una extensión.

● Para cada revista, almacenaremos información de cada ejemplar, que incluirá la
fecha, número de páginas y el número de ejemplares vendidos.

![image](https://user-images.githubusercontent.com/103066839/169415228-fc7598e8-b027-48bd-8d32-35cdafb8daa9.png)

![image](https://user-images.githubusercontent.com/103066839/169568145-078561e1-910f-497a-977a-ebda53518b55.png)

https://www.db-fiddle.com/f/oo2Eqenh5ntvTEW81A8ZU3/5
