## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?(valor 1.5)
                         
                         
                  1. Asegurar el buen funcionamiento de las BD
                  2. Retención de información de las BD
                  3. Evitar pérdida de datos
                  4. Solucionar incidencias y pérdidas de datos
                  5.  Asegurar la seguridad de los datos



           

2. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)


                 1. Instalar, configurar y gestionar bases de datos.
                 2. Dar soporte al equipo de desarrollo, seguridad informática y redes.
                 3. Definir el esquema del diccionario de datos.
                 4. Especificar restricciones de integridad para asegurar los datos.
                 5. Garantizar la alta disponibilidad de la base de datos.


           
           

3. En una BD al usuario del sistema se le brindarán recursos para realizar diversas
operaciones sobre estos archivos, tales como: (valor 1.5)


                 1. Sólo agregar, eliminar y actualizar datos en archivos existentes de la BD
                 2. Agregar archivos nuevos en la BD, insertar, eliminar, actualizar y obtener datos de archivos existentes de la BD
                 3. Actualizar sólo datos de archivos existentes
                 4. Eliminar sólo archivos ya existentes en la BD.


4. ¿Qué es un Sistema de Información? (valor 1.5)

                    Conjunto de elementos orientados al tratamiento y administración de datos e información, 
                    organizados y listos para su posterior uso, 
                    generados para cubrir necesidad.

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
![si](https://user-images.githubusercontent.com/101351242/169093777-7a4325ce-9f9d-43fa-8ca0-6c9dbf9f775c.png)


https://www.db-fiddle.com/f/hNDyXF96xKzCYJewhJwNjX/0
