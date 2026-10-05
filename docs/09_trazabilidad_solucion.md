# Solución de la Matriz de Trazabilidad de Requisitos

## 1. Descripción de la solución

La solución propuesta consiste en utilizar una matriz de trazabilidad para relacionar las necesidades de la asesoría con los requisitos definidos, las soluciones desarrolladas y las comprobaciones realizadas durante el proyecto.

La matriz permitirá realizar un seguimiento de cada requisito desde su definición hasta su implementación, facilitando la comprobación de que las necesidades identificadas quedan cubiertas.

La trazabilidad se aplicará a los diferentes módulos del proyecto: Administración de Sistemas Operativos (ASO), Administración de Sistemas Gestores de Bases de Datos (ASGBD), Implantación de Aplicaciones Web (IAW), Servicios de Red e Internet y Seguridad y Alta Disponibilidad.

## 2. Organización de la trazabilidad

La matriz de trazabilidad se organizará relacionando cada requisito con la solución que permite cumplirlo y con las comprobaciones que se realizarán para verificar su cumplimiento.

Para cada requisito se indicará el módulo al que pertenece, la solución implementada y la comprobación asociada.

La matriz permitirá identificar fácilmente qué requisitos han sido implementados y comprobar que todos ellos han sido considerados durante el desarrollo del proyecto.

## 3. Trazabilidad de Administración de Sistemas Operativos (ASO)

| Requisito | Solución implementada | Comprobación |
|---|---|---|
| ASO-01 | Actualización de los equipos PC-01 a PC-05 a Windows 11 Pro y comprobación posterior de su funcionamiento. | Comprobar que los equipos se actualizan correctamente, se inician y permiten utilizar sus aplicaciones principales. |
| ASO-02 | Establecimiento de un procedimiento periódico de mantenimiento para los 15 equipos de la asesoría. | Comprobar periódicamente las actualizaciones, el almacenamiento, el funcionamiento general y las aplicaciones necesarias. |
| ASO-03 | Identificación de los equipos que necesitan actualización y planificación de la actuación correspondiente. | Revisar el estado de cada equipo y verificar que PC-01 a PC-05 están identificados como equipos pendientes de actualización. |

## 4. Trazabilidad de Administración de Sistemas Gestores de Bases de Datos (ASGBD)

| Requisito | Solución implementada | Comprobación |
|---|---|---|
| ASGBD-01 | Diseño e implementación de una base de datos MySQL con las entidades Clientes, Empleados, Servicios, Incidencias y Proyectos. | Comprobar que la base de datos contiene las entidades necesarias y que la información puede almacenarse y gestionarse correctamente. |
| ASGBD-02 | Establecimiento de tareas de administración y mantenimiento, incluyendo copias de seguridad y revisión de usuarios y permisos. | Comprobar periódicamente el estado de la base de datos, los permisos de acceso y la realización de copias de seguridad. |
| ASGBD-03 | Realización de pruebas de inserción, consulta, modificación, eliminación y comprobación de las relaciones entre las entidades. | Verificar que las operaciones sobre los datos funcionan correctamente y que las relaciones entre las entidades se mantienen. |

## 5. Trazabilidad de Implantación de Aplicaciones Web (IAW)

| Requisito | Solución implementada | Comprobación |
|---|---|---|
| IAW-01 | Diseño e implementación de una aplicación web interna desarrollada con HTML, CSS y PHP, conectada a la base de datos MySQL. | Comprobar que la aplicación permite gestionar la información de clientes y servicios. |
| IAW-02 | Implementación de funcionalidades para consultar, añadir, modificar y eliminar información de clientes, servicios, incidencias y proyectos. | Verificar que los usuarios autorizados pueden consultar y administrar correctamente la información mediante la aplicación. |
| IAW-03 | Realización de pruebas sobre las principales funcionalidades de la aplicación y su conexión con la base de datos. | Comprobar que los cambios realizados desde la aplicación se almacenan correctamente y que la información puede consultarse y administrarse sin errores. |

## 6. Trazabilidad de Servicios de Red e Internet

| Requisito | Solución implementada | Comprobación |
|---|---|---|
| RED-01 | Diseño de una red local `192.168.1.0/24` para conectar los 15 equipos de la asesoría mediante un switch y un router. | Comprobar que los equipos están conectados a la red y pueden comunicarse entre sí. |
| RED-02 | Configuración de DHCP, DNS y acceso a Internet mediante el router de la infraestructura. | Comprobar que los equipos reciben correctamente su configuración de red, resuelven nombres y tienen acceso a Internet. |
| RED-03 | Realización de pruebas de comunicación entre los equipos, el router y los servicios de red configurados. | Verificar la comunicación entre los equipos y comprobar el funcionamiento de DHCP, DNS y acceso a Internet. |

## 7. Trazabilidad de Seguridad y Alta Disponibilidad

| Requisito | Solución implementada | Comprobación |
|---|---|---|
| SEG-01 | Identificación de riesgos como malware, accesos no autorizados, pérdida de datos, fallos de equipos, ataques de red y falta de actualizaciones de seguridad. | Revisar los riesgos identificados y comprobar que se han considerado las principales amenazas para la infraestructura. |
| SEG-02 | Aplicación de firewall, antivirus y antimalware, actualizaciones de seguridad, copias de seguridad, control de usuarios y permisos y procedimientos de recuperación. | Comprobar que las medidas de seguridad están configuradas y que las copias de seguridad y los procedimientos de recuperación funcionan correctamente. |
| SEG-03 | Realización de pruebas sobre el firewall, antivirus, actualizaciones, copias de seguridad, permisos y recuperación ante fallos. | Verificar que las medidas implementadas funcionan correctamente y permiten responder ante posibles incidencias. |

## 8. Trazabilidad de los Requisitos del Proyecto

| Requisito | Solución implementada | Comprobación |
|---|---|---|
| TRA-01 | Identificación y definición de los requisitos a partir de las necesidades detectadas en la asesoría. | Comprobar que las necesidades identificadas tienen asociados requisitos concretos y definidos. |
| TRA-02 | Relación de cada requisito con las soluciones y tareas desarrolladas en los diferentes módulos del proyecto. | Revisar la matriz para comprobar que cada requisito está relacionado con una solución y una comprobación. |
| TRA-03 | Elaboración y revisión de la matriz de trazabilidad para comprobar que las necesidades quedan cubiertas por las soluciones implementadas. | Verificar que todos los requisitos definidos aparecen en la matriz y que existe una solución y una comprobación asociada a cada uno. |

## 9. Conclusión

La matriz de trazabilidad permitirá realizar un seguimiento de los requisitos definidos durante el proyecto y comprobar su relación con las soluciones implementadas.

De esta forma, se podrá verificar que las necesidades identificadas en la asesoría han sido tenidas en cuenta y que cada requisito dispone de una solución y una comprobación asociada.

La matriz se utilizará como referencia durante la revisión final del proyecto para comprobar el grado de cumplimiento de los requisitos establecidos.

