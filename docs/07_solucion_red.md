# Solución de Servicios de Red e Internet

## 1. Descripción de la solución

La solución propuesta consiste en diseñar y configurar una infraestructura de red local (LAN) para la asesoría informática que permita conectar los equipos y facilitar el funcionamiento de los servicios informáticos de la empresa.

La red estará formada por 15 equipos informáticos, un switch para interconectar los equipos y un router que proporcionará la comunicación con Internet.

La infraestructura utilizará IPv4 y contará con los servicios DHCP y DNS para facilitar la configuración de los equipos y la resolución de nombres dentro de la red.

Esta solución permitirá disponer de una red organizada y adecuada para la comunicación entre los equipos y el funcionamiento de los servicios informáticos de la asesoría.

## 2. Estructura y direccionamiento de la red

La red local de la asesoría utilizará una única red IPv4 para conectar los equipos y los dispositivos de red.

Se utilizará la red `192.168.1.0/24`, que permitirá disponer de suficientes direcciones IP para los equipos y dispositivos de la infraestructura.

La distribución inicial del direccionamiento será la siguiente:

| Dispositivo | Direccionamiento |
|---|---|
| Router | 192.168.1.1 |
| Switch | 192.168.1.2 |
| PC-01 a PC-15 | Direcciones asignadas mediante DHCP |
| Servidor DNS | Servicio proporcionado dentro de la infraestructura de red |

Los equipos utilizarán el router como puerta de enlace para acceder a otras redes e Internet.

## 3. Servicios de red e Internet

La infraestructura contará con diferentes servicios de red para facilitar la comunicación entre los equipos y el acceso a los recursos necesarios.

Los principales servicios serán:

- **DHCP:** asignará automáticamente las direcciones IP a los equipos de la asesoría, evitando tener que configurar manualmente cada equipo.
- **DNS:** permitirá resolver nombres de dispositivos y servicios de la red mediante sus correspondientes direcciones IP.
- **Acceso a Internet:** el router proporcionará la salida de la red local hacia Internet.

La configuración de estos servicios permitirá que los equipos puedan comunicarse entre sí y acceder a los servicios de Internet necesarios para la actividad de la asesoría.

## 4. Comprobación del funcionamiento

Una vez configurada la infraestructura de red, se realizarán diferentes pruebas para comprobar que los equipos y los servicios funcionan correctamente.

Las comprobaciones principales serán:

1. Comprobar que los equipos reciben correctamente una dirección IP mediante DHCP.
2. Comprobar que los equipos pueden comunicarse entre sí dentro de la red local.
3. Comprobar que los equipos pueden comunicarse con el router.
4. Comprobar que la resolución de nombres mediante DNS funciona correctamente.
5. Comprobar que los equipos pueden acceder a Internet.
6. Comprobar que los servicios de red configurados funcionan correctamente.

Estas pruebas permitirán verificar que la infraestructura de red proporciona una comunicación adecuada entre los equipos y permite el acceso a los servicios necesarios para la actividad de la asesoría.

