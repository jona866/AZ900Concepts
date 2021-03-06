# Describe core Azure architectural components

> En este m贸dulo, examinar谩 los diversos conceptos, recursos y terminolog铆a necesarios para trabajar con la arquitectura de Azure.

## 馃摎 Contenido 

- [Jerarqu铆a de organizaci贸n en Azure](#Jerarqu铆a-Azure)
  - Recursos
  - Grupos de recursos
  - Suscripciones
  - Grupos de administraci贸n
- [Suscripciones de Azure](#Suscripciones-Azure)
  - Suscripci贸n de Azure
  - L铆mite de facturaci贸n
  - L铆mite de control de acceso
  - Administrador de Recursos de Azure
- [Centros de datos](#Centros-de-datos)
  - Regi贸n
  - Zona de disponibilidad
  - Pares de regiones

___

## 馃摑 Conceptos

### Jerarqu铆a Azure

- ***Recursos***

Instancias de servicios que el usuario crea, como m谩quinas virtuales, almacenamiento o bases de datos SQL.

- ***Grupos de recursos***

Los recursos se combinan en grupos de recursos, que act煤an como un contenedor l贸gico en el que se implementan y administran recursos de Azure, como aplicaciones web, bases de datos y cuentas de almacenamiento.

- ***Suscripciones***

Una suscripci贸n agrupa las cuentas de usuario y los recursos que han sido creados por esas cuentas de usuario. Para cada suscripci贸n, existen l铆mites o cuotas en la cantidad de recursos que puede crear y usar. Las organizaciones pueden usar suscripciones para administrar los costos y los recursos que crean los usuarios, equipos o proyectos.

- ***Grupos de administraci贸n***

Ayudan a administrar el acceso, la pol铆tica y el cumplimiento de varias suscripciones. Todas las suscripciones en un grupo de administraci贸n heredan autom谩ticamente las condiciones aplicadas al grupo de administraci贸n.

### Suscripciones Azure

***Suscripci贸n de Azure***

Una suscripci贸n le proporciona acceso autenticado y autorizado a los productos y servicios de Azure. Tambi茅n le permite aprovisionar recursos. Una suscripci贸n de Azure es una unidad l贸gica de los servicios de Azure que se vincula a una cuenta de Azure, que es una identidad en Azure Active Directory (Azure AD) o en un directorio en el que Azure AD conf铆a.

***L铆mite de facturaci贸n***

Este tipo de suscripci贸n determina c贸mo se factura una cuenta de Azure por usar Azure. Puede crear varias suscripciones para diferentes tipos de requisitos de facturaci贸n. Azure genera informes de facturaci贸n y facturas independientes para cada suscripci贸n para que pueda organizar y administrar los costos.

***L铆mite de control de acceso***

Azure aplica pol铆ticas de administraci贸n de acceso a nivel de suscripci贸n y puede crear suscripciones independientes para reflejar las diferentes estructuras organizativas. Este modelo de facturaci贸n le permite administrar y controlar el acceso a los recursos que los usuarios proveen con suscripciones espec铆ficas.

***Administrador de recursos de Azure***

Azure Resource Manager es el servicio de implementaci贸n y administraci贸n de Azure. Proporciona una capa de administraci贸n que le permite crear, actualizar y eliminar recursos en su cuenta de Azure. Utiliza funciones de administraci贸n como control de acceso, cerraduras y etiquetas para proteger y organizar sus recursos despu茅s de la implementaci贸n.

### Centros de datos

***Regi贸n***

Una regi贸n es un 谩rea geogr谩fica del planeta que contiene al menos uno, pero potencialmente varios, centros de datos cercanos y conectados en red con una red de baja latencia. Azure asigna y controla de manera inteligente los recursos dentro de cada regi贸n para garantizar que las cargas de trabajo est茅n equilibradas de manera adecuada.

***Zona de disponibilidad***

Las zonas de disponibilidad son centros de datos f铆sicamente separados dentro de una regi贸n de Azure. Cada zona de disponibilidad se compone de uno o m谩s centros de datos equipados con alimentaci贸n, refrigeraci贸n y redes independientes. Una zona de disponibilidad est谩 configurada para ser un l铆mite de aislamiento . Si una zona se cae, la otra sigue funcionando. Las zonas de disponibilidad est谩n conectadas a trav茅s de redes de fibra 贸ptica privadas de alta velocidad.

***Pares de regiones***

Cada regi贸n de Azure siempre est谩 emparejada con otra regi贸n dentro de la misma geograf铆a al menos a 300 millas de distancia. Este enfoque permite la replicaci贸n de recursos en una geograf铆a que ayuda a reducir la probabilidad de interrupciones debido a eventos como desastres naturales, disturbios civiles, cortes de energ铆a o interrupciones de la red f铆sica que afectan ambas regiones a la vez. Si una regi贸n de un par se ve afectada por un desastre natural, por ejemplo, los servicios se conmutar铆an autom谩ticamente por error a la otra regi贸n de su par de regiones.

___



| 猬嗭笍 | 猬咃笍 | 馃彔 |
| --- | --- | --- |
| [Inicio](#Describe-core-Azure-architectural-components) | [Anterior](https://github.com/jona866/AZ900Concepts/blob/main/Content/DAFC.md) | [Home](https://github.com/jona866/AZ900Concepts/blob/main/README.md) |

Recuperado de: [M贸dulo: Describe core Azure architectural components](https://docs.microsoft.com/en-gb/learn/modules/azure-architecture-fundamentals/?WT.mc_id=cloudskillschallenge_1b157d7d-b99e-4cf8-8523-9c8b51f93c1b&ns-enrollment-type=Collection&ns-enrollment-id=ddkzhpd6gqn7)
