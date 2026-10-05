# Solución de Administración de Sistemas Gestores de Bases de Datos (ASGBD)

## 1. Descripción de la solución

La solución propuesta consiste en diseñar e implementar una base de datos MySQL para centralizar y organizar la información necesaria para la actividad de la asesoría.

La base de datos permitirá gestionar de forma organizada la información relacionada con los clientes, empleados, servicios, incidencias y proyectos de la empresa.

Esta solución facilitará la administración de la información y permitirá que posteriormente pueda ser utilizada por la aplicación web del proyecto.

## 2. Entidades de la base de datos

La base de datos estará formada inicialmente por cinco entidades principales:

| Entidad | Información que gestionará |
|---|---|
| Clientes | Información de las empresas que contratan los servicios de la asesoría. |
| Empleados | Información de los trabajadores de la asesoría y su puesto o función. |
| Servicios | Información de los servicios informáticos que ofrece la asesoría. |
| Incidencias | Información sobre problemas, solicitudes o incidencias comunicadas por los clientes. |
| Proyectos | Información sobre los proyectos y trabajos específicos realizados para los clientes. |

Estas entidades permitirán organizar la información necesaria para la actividad de la asesoría y establecer posteriormente las relaciones entre los diferentes datos.

## 3. Relaciones entre las entidades

Las entidades de la base de datos estarán relacionadas para evitar información duplicada y facilitar la gestión de los datos.

Las principales relaciones serán las siguientes:

- Un **cliente** podrá tener varias **incidencias**.
- Un **cliente** podrá contratar varios **servicios**.
- Un **cliente** podrá tener varios **proyectos**.
- Un **empleado** podrá participar en varios **proyectos**.
- Un **empleado** podrá gestionar varias **incidencias**.
- Un **proyecto** podrá estar relacionado con uno o varios **servicios**.

Estas relaciones permitirán consultar de forma organizada la información de los clientes, empleados, servicios, incidencias y proyectos.

## 4. Administración y mantenimiento de la base de datos

La base de datos será administrada y mantenida para garantizar que la información de la asesoría se pueda gestionar correctamente.

Las tareas principales de administración y mantenimiento serán:

1. Comprobar periódicamente el estado de la base de datos.
2. Revisar que la información almacenada sea correcta y esté actualizada.
3. Realizar copias de seguridad de la información almacenada.
4. Revisar los usuarios y permisos de acceso a la base de datos.
5. Comprobar que las operaciones de consulta, inserción, modificación y eliminación de información funcionan correctamente.

Estas tareas permitirán mantener la base de datos en unas condiciones adecuadas y reducir el riesgo de pérdida o acceso no autorizado a la información.

## 5. Comprobación del funcionamiento

Una vez implementada la base de datos, se realizarán diferentes pruebas para comprobar que funciona correctamente y que permite gestionar la información necesaria para la actividad de la asesoría.

Las comprobaciones principales serán:

1. Insertar información de prueba en las diferentes entidades.
2. Consultar la información almacenada.
3. Modificar información existente.
4. Eliminar información de prueba.
5. Comprobar que las relaciones entre las entidades funcionan correctamente.
6. Verificar que las operaciones realizadas no generan errores y que la información se mantiene correctamente.

Las pruebas permitirán comprobar que la base de datos cumple su función y que la información de clientes, empleados, servicios, incidencias y proyectos puede gestionarse adecuadamente.

