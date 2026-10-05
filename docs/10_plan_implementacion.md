# Plan de Implementación

## 1. Introducción

El plan de implementación define las actuaciones necesarias para llevar a cabo las soluciones propuestas en el proyecto de mejora de la infraestructura informática de la asesoría.

La implementación se realizará de forma organizada, siguiendo las soluciones definidas para los sistemas operativos, la base de datos, la aplicación web, los servicios de red, la seguridad y la trazabilidad de los requisitos.

Cada actuación será comprobada una vez realizada para verificar que funciona correctamente y que cumple con los requisitos establecidos en el proyecto.

## 2. Orden de implementación

La implementación se realizará siguiendo un orden que permita preparar primero la infraestructura básica y posteriormente desplegar los servicios y soluciones que dependen de ella.

El orden previsto será el siguiente:

1. Actualización y preparación de los sistemas operativos.
2. Diseño e implementación de la base de datos.
3. Diseño y configuración de los servicios de red e Internet.
4. Implementación de la aplicación web.
5. Aplicación de las medidas de seguridad y alta disponibilidad.
6. Comprobación de los requisitos mediante la matriz de trazabilidad.

Este orden permitirá realizar las actuaciones de forma progresiva y comprobar cada parte antes de continuar con la siguiente.

## 3. Implementación de Administración de Sistemas Operativos (ASO)

La primera actuación consistirá en preparar los sistemas operativos de los equipos informáticos de la asesoría.

Se revisarán los 15 equipos identificados en la solución de ASO y se comprobará el estado de actualización de cada uno.

Los equipos PC-01 a PC-05 serán actualizados a Windows 11 Pro. Antes de realizar cada actualización se comprobará el estado del equipo y se revisarán los datos y configuraciones necesarios para garantizar la continuidad de su funcionamiento.

Una vez realizada cada actualización, se comprobará que el equipo se inicia correctamente, que las aplicaciones principales funcionan y que puede continuar utilizándose para las tareas asignadas.

Los equipos PC-06 a PC-15 se mantendrán con Windows 11 Pro actualizado y se incluirán en el procedimiento periódico de mantenimiento establecido.


## 4. Implementación de Administración de Sistemas Gestores de Bases de Datos (ASGBD)

La segunda actuación consistirá en implementar la base de datos MySQL definida en la solución de ASGBD.

En primer lugar, se crearán las tablas
necesarias para almacenar la información de clientes, empleados, servicios, incidencias y proyectos.

Posteriormente, se establecerán las relaciones entre las diferentes tablas para organizar correctamente la información y evitar duplicidades.

Una vez creada la estructura de la base de datos, se realizarán pruebas de inserción, consulta, modificación y eliminación de datos para comprobar su funcionamiento.

También se establecerán las medidas básicas de administración y mantenimiento, incluyendo la realización de copias de seguridad y la revisión de usuarios y permisos de acceso.


## 5. Implementación de Servicios de Red e Internet

La tercera actuación consistirá en configurar la infraestructura de red de la asesoría para permitir la comunicación entre los equipos y el funcionamiento de los servicios informáticos.

Se utilizará la red `192.168.1.0/24`, con el router configurado con la dirección `192.168.1.1` y el switch con la dirección `192.168.1.2`.

Los equipos PC-01 a PC-15 obtendrán su configuración de red mediante DHCP.

También se configurará el servicio DNS para permitir la resolución de nombres dentro de la infraestructura y se comprobará el acceso a Internet a través del router.

Una vez configurados los servicios, se realizarán pruebas de conectividad entre los equipos, comunicación con el router, asignación de direcciones mediante DHCP, resolución de nombres mediante DNS y acceso a Internet.


## 6. Implementación de Implantación de Aplicaciones Web (IAW)

La cuarta actuación consistirá en implementar la aplicación web interna de la asesoría.

La aplicación utilizará HTML y CSS para la interfaz, PHP para la parte del servidor y MySQL para almacenar y gestionar la información.

Se implementarán las funcionalidades necesarias para gestionar clientes, servicios, incidencias y proyectos, permitiendo consultar, añadir, modificar y eliminar la información correspondiente.

La aplicación se conectará con la base de datos implementada en la solución de ASGBD para utilizar la información de forma centralizada.

Una vez implementada, se realizarán pruebas de las principales funcionalidades y se comprobará que los datos introducidos o modificados mediante la aplicación se almacenan correctamente en la base de datos.


## 7. Implementación de Seguridad y Alta Disponibilidad

La quinta actuación consistirá en aplicar las medidas de seguridad y disponibilidad definidas para la infraestructura informática de la asesoría.

Se configurará un firewall para controlar las conexiones de red y bloquear aquellas que no estén autorizadas.

Los equipos dispondrán de protección antivirus y antimalware y se mantendrán actualizados mediante las correspondientes actualizaciones de seguridad.

También se establecerá un sistema de copias de seguridad periódicas de la información importante y se configurarán usuarios y permisos adecuados para controlar el acceso a los recursos.

Finalmente, se establecerán procedimientos básicos de recuperación ante posibles fallos o incidencias.

Una vez aplicadas las medidas, se realizarán pruebas para comprobar el funcionamiento del firewall, la protección antivirus, las copias de seguridad, los permisos de acceso y los procedimientos de recuperación.


## 8. Comprobación final mediante la matriz de trazabilidad

Una vez implementadas las diferentes soluciones del proyecto, se realizará una comprobación final mediante la matriz de trazabilidad de requisitos.

Se revisará cada requisito definido en el proyecto y se comprobará que dispone de una solución implementada y de una prueba asociada.

Esta revisión permitirá detectar posibles requisitos pendientes y verificar que las necesidades identificadas inicialmente en la asesoría han sido cubiertas.

Finalmente, se documentarán los resultados de las comprobaciones realizadas y se indicará si cada requisito ha sido cumplido correctamente.
