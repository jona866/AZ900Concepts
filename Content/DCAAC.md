# Describe core Azure architectural components

> En este módulo, examinará los diversos conceptos, recursos y terminología necesarios para trabajar con la arquitectura de Azure.

## 📚 Contenido 

- [Jerarquía de organización en Azure](#Jerarquía-Azure)
  - Recursos
  - Grupos de recursos
  - Suscripciones
  - Grupos de administración
- [Suscripciones de Azure](#Suscripciones-Azure)
  - Suscripción de Azure
  - Límite de facturación
  - Límite de control de acceso
  - Administrador de Recursos de Azure
- [Centros de datos](#Centros-de-datos)
  - Región
  - Zona de disponibilidad
  - Pares de regiones

___

## 📝 Conceptos

### Jerarquía Azure

- ***Recursos***

Instancias de servicios que el usuario crea, como máquinas virtuales, almacenamiento o bases de datos SQL.

- ***Grupos de recursos***

Los recursos se combinan en grupos de recursos, que actúan como un contenedor lógico en el que se implementan y administran recursos de Azure, como aplicaciones web, bases de datos y cuentas de almacenamiento.

- ***Suscripciones***

Una suscripción agrupa las cuentas de usuario y los recursos que han sido creados por esas cuentas de usuario. Para cada suscripción, existen límites o cuotas en la cantidad de recursos que puede crear y usar. Las organizaciones pueden usar suscripciones para administrar los costos y los recursos que crean los usuarios, equipos o proyectos.

- ***Grupos de administración***

Ayudan a administrar el acceso, la política y el cumplimiento de varias suscripciones. Todas las suscripciones en un grupo de administración heredan automáticamente las condiciones aplicadas al grupo de administración.

### Suscripciones Azure

***Suscripción de Azure***

Una suscripción le proporciona acceso autenticado y autorizado a los productos y servicios de Azure. También le permite aprovisionar recursos. Una suscripción de Azure es una unidad lógica de los servicios de Azure que se vincula a una cuenta de Azure, que es una identidad en Azure Active Directory (Azure AD) o en un directorio en el que Azure AD confía.

***Límite de facturación***

Este tipo de suscripción determina cómo se factura una cuenta de Azure por usar Azure. Puede crear varias suscripciones para diferentes tipos de requisitos de facturación. Azure genera informes de facturación y facturas independientes para cada suscripción para que pueda organizar y administrar los costos.

***Límite de control de acceso***

Azure aplica políticas de administración de acceso a nivel de suscripción y puede crear suscripciones independientes para reflejar las diferentes estructuras organizativas. Este modelo de facturación le permite administrar y controlar el acceso a los recursos que los usuarios proveen con suscripciones específicas.

***Administrador de recursos de Azure***

Azure Resource Manager es el servicio de implementación y administración de Azure. Proporciona una capa de administración que le permite crear, actualizar y eliminar recursos en su cuenta de Azure. Utiliza funciones de administración como control de acceso, cerraduras y etiquetas para proteger y organizar sus recursos después de la implementación.

### Centros de datos

***Región***

Una región es un área geográfica del planeta que contiene al menos uno, pero potencialmente varios, centros de datos cercanos y conectados en red con una red de baja latencia. Azure asigna y controla de manera inteligente los recursos dentro de cada región para garantizar que las cargas de trabajo estén equilibradas de manera adecuada.

***Zona de disponibilidad***

Las zonas de disponibilidad son centros de datos físicamente separados dentro de una región de Azure. Cada zona de disponibilidad se compone de uno o más centros de datos equipados con alimentación, refrigeración y redes independientes. Una zona de disponibilidad está configurada para ser un límite de aislamiento . Si una zona se cae, la otra sigue funcionando. Las zonas de disponibilidad están conectadas a través de redes de fibra óptica privadas de alta velocidad.

***Pares de regiones***

Cada región de Azure siempre está emparejada con otra región dentro de la misma geografía al menos a 300 millas de distancia. Este enfoque permite la replicación de recursos en una geografía que ayuda a reducir la probabilidad de interrupciones debido a eventos como desastres naturales, disturbios civiles, cortes de energía o interrupciones de la red física que afectan ambas regiones a la vez. Si una región de un par se ve afectada por un desastre natural, por ejemplo, los servicios se conmutarían automáticamente por error a la otra región de su par de regiones.

___

[Inicio](#Describe-core-Azure-architectural-components)

Recuperado de: [Módulo: Describe core Azure architectural components](https://docs.microsoft.com/en-gb/learn/modules/azure-architecture-fundamentals/?WT.mc_id=cloudskillschallenge_1b157d7d-b99e-4cf8-8523-9c8b51f93c1b&ns-enrollment-type=Collection&ns-enrollment-id=ddkzhpd6gqn7)
