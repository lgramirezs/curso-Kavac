# Introducción

---

## Introducción y características

KAVAC es una plataforma integral de gestión empresarial que optimiza la planificación y el control de todos los recursos organizacionales. Desde la administración financiera y económica hasta la gestión de activos materiales y humanos, KAVAC ofrece una visión holística de la empresa. Su funcionalidad se extiende a la gestión de las relaciones con clientes y proveedores, integrando y automatizando los procesos administrativos para una mayor eficiencia. La seguridad de la información es primordial, con características como la firma electrónica que aseguran la autenticidad y la integridad de cada documento. El sistema se destaca por su interfaz intuitiva, con herramientas analíticas y gráficas que facilitan la comprensión de la información. Los reportes en tiempo real sobre el estado de cada departamento permiten una toma de decisiones más informada y oportuna, contribuyendo al logro de los objetivos estratégicos de la organización.

### Módulos

El sistema KAVAC se caracteriza por su arquitectura modular, lo que proporciona una alta flexibilidad y escalabilidad. Cada módulo opera de forma independiente, permitiendo la implementación gradual y personalizada según las necesidades específicas de cada organización. Esta independencia entre módulos no impide su interoperabilidad; KAVAC está diseñado para que los módulos coexistan y se integren de forma eficiente, compartiendo datos y funcionalidades cuando sea necesario. La implementación inicial puede limitarse a un conjunto selecto de módulos, con la posibilidad de añadir funcionalidades adicionales posteriormente, adaptándose así a la evolución de los requerimientos de la organización. Cada módulo dispone de un panel de control y opciones de configuración individualizadas, permitiendo un ajuste preciso a las necesidades particulares de la institución. Esta arquitectura modular asegura la eficiencia, la adaptabilidad y la optimización de los recursos, ofreciendo una solución a medida para la gestión de recursos organizacionales.

### Un Software Innovador

KAVAC tiene como propósito aprovechar las potencialidades y herramientas de un lenguaje de programación y un framework moderno. Un framework que permite entre otras cosas la posibilidad de extender funcionalidades sin mayor complejidad, instrucciones de código más sencillas, entendibles y orientadas a objetos.

Esta estructura de desarrollo permite a la aplicación extender otras potencialidades:

-   Flexibilidad en la gestión de información.
-   Implementación de auditoria de registros.
-   Posibilidad en la implementación de lenguaje de desarrollo a su última versión estable permitiendo solventar inconvenientes con la obsolesencia.
-   Código fuente bajo un patrón de arquitectura de software Modelo Vista Controlador (MVC) lo cual permite separar los procesos y hacer más fácil el mantenimiento del código fuente.
-   Desarrollo enfocado bajo un esquema modular lo cual hace factible la implementación de funcionalidades sin mayores inconvenientes.
-   Interfaz de usuario adecuada para la correcta visualización en distintos dispositivos y/o resoluciones de pantalla.
-   Ampliamente documentado tanto en código fuente como en documentación para el usuario.
-   Enfoque preciso en cuanto a cada funcionalidad del sistema.
-   Aseguramiento de la información mediante métodos implementados por el framework e implementación de estándares de código fuente.

KAVAC se desarrolla en lenguaje PHP y el framework Laravel bajo un esquema de Programación orientada a objetos (POO) y una arquitectura cliente - servidor, el uso de este framework permite solventar algunas deficiencias del lenguaje en sí como lo es la gestión de grandes volúmenes de datos y cálculos inherentes a la información, con la implementación de métodos dispuestos en la capa ORM (mapeo objeto-relacional) que optimizan la respuesta obtenida por el servidor de base de datos ante distintas magnitudes de consultas, además de contar con funciones que permiten realizar diferentes tareas enfocadas al mejor rendimiento de la aplicación.

PHP es considerado uno de los lenguajes Open Source más utilizados en el desarrollo de aplicaciones web y es el lenguaje primordial en la mayor parte de servidores de hospedaje. Como parte de su constante proceso de evolución, en sus últimas versiones (a partir de la 7.x) ha mejorado en cuanto a sintaxis (menos código por el mismo resultado y mejoras en sus funcionalidades), rendimiento, de fácil configuración, con una amplia gama de paquetes disponibles para su uso libre y mejoras en el tratamiento de información.

Por su parte, Laravel es un framework de desarrollo para PHP el cual cuenta con una gran cantidad de funcionalidades que permite: mejorar el rendimiento de los procesos, prevenir la exposición ante ataques conocidos, continua actualización en pro de mejoras sustanciales, amplia comunidad de desarrollo, núcleo basado en Symfony, documentación sustancial en todos los componentes del framework, disponibilidad de una gran diversidad de paquetes Open Source que pueden ser implementados sin complejidad, configuración sencilla, gestión de recursos del servidor de aplicación, base de datos de una forma óptima y sintaxis intuitiva.

En el desarrollo de la aplicación administrativa para la gestión de recursos KAVAC se plantea implementar, en cuanto a la optimización de algunos procesos que requieren cálculos a gran escala, el uso de:



-   Procedimientos almacenados: No dependen del lenguaje de desarrollo sino de la capacidad del gestor de base de datos en las tareas de cálculo y gestión de la información.

-   Tareas programadas o delegadas: Permite delegar tareas de cómputo a la capacidad de cálculo del servidor sin obstruir el funcionamiento de la aplicación.

-   Interacción directa con el servidor: Posibilidad de interactuar directamente con el servidor de base de datos sin depender del lenguaje de desarrollo acelerando el proceso de consulta y gestión de la información.

-   Disparadores de eventos: Generar notificaciones al usuario cuando una tarea haya sido culminada por el servidor.

-   Gestión de caché: Almacenar información en la caché del servidor para no repetir consultas cada vez que esta sea solicitada a menos que la misma haya sido modificada, lo cual permitirá tiempos de respuesta casi imperceptibles.

-   Configuraciones sugeridas en un entorno en producción de aplicaciones web.

-   Lenguaje de Desarrollo: Optimización de las variables de configuración dispuestas por el lenguaje para mejorar su rendimiento y aumentar las capacidades del mismo (aplica para cualquier lenguaje de desarrollo).

-   Clúster de Servidores de Base de Datos: Permite la optimización y mejoras en cuanto al tiempo de respuesta en la capacidad de cálculo. Importante tomar en cuenta para la gestión de grandes volúmenes de datos pero no limitativo.

-   Balanceo de Cargas: Configuración de un esquema de cargas balanceadas tanto en la capa del servidor de aplicación.



## Metodología para el Desarrollo Colaborativo de Software Libre (MDCSL)

El sistema KAVAC se fundamenta en los procesos que aborda la segunda versión de la Metodología para el Desarrollo Colaborativo de Software Libre (MDCSL), procesos que se encuentran orientados a la conceptualización, administración y construcción del sistema. 

La metodología de desarrollo de software libre elaborada e impulsada por el Centro Nacional de Desarrollo e Investigación en Tecnologías Libres (CENDITEL) incorpora nuevas técnicas de gestión, así como la simplificación de flujos de trabajo, la adición de actividades no contempladas inicialmente, tales como el empaquetado y la gestión de versiones, además de una actualización de la lista de herramientas informáticas que incluye la disponibilidad de un complemento para la plataforma Trac (plataforma para la gestión de proyectos) que está específicamente diseñado para la aplicación de esta metodología.

### ¿Por qué usar la Metodología para el Desarrollo Colaborativo de Software Libre (MDCSL)?

Las metodologías de desarrollo de software tienen como objetivo presentar un conjunto de técnicas tradicionales y modernas de modelado de sistemas que permitan desarrollar software de calidad, la segunda versión de la Metodología para el Desarrollo Colaborativo de Software Libre se fundamenta en el concepto de práctica virtuosa definido por MacIntyre en el libro “Tras la Virtud”, en el cual una práctica se define como una actividad humana cooperativa, socialmente establecida, mediante la cual se busca la mejora continua de lo producido en ésta, lo que implica un proceso de cultivo de conocimiento asociado a la práctica en pro de la excelencia en la ejecución de la misma, buscando promover un proceso de enseñanza – aprendizaje en torno a la práctica de desarrollo de software, proceso que contribuye a la mejora continua de la práctica de desarrollo en en este ámbito, así como en base a modelos y patrones de excelencia que las comunidades de software libre han ido cultivando en el transcurrir del tiempo. 

En lo que respecta al sentido social de la práctica, se tiene como propósito consolidar una práctica de desarrollo en la cual se otorgue especial énfasis a la documentación del software y proceso de construcción(especificación de casos de uso y codificación), a fin de facilitar procesos de apropiación que apunten no sólo al uso, sino también al mantenimiento y mejora del software por parte de usuarios e interesados.

### Propuesta Metodológica 

#### Proceso de Conceptualización de Proyectos de Software Libre

En este proceso, el equipo de desarrollo del Sistema de Gestión de Recursos KAVAC se encargó de recopilar y analizar información concerniente a los procesos que se requieren automatizar en una aplicación de software, con el objetivo de comprender el dominio de la aplicación a desarrollar así como los problemas o necesidades de los usuarios, con la finalidad de plantear una propuesta de desarrollo de software acorde con los requerimientos necesarios. 

#### Proceso de Administración de Proyectos de Software Libre

En este proceso se realizaron actividades de planificación, coordinación y seguimiento de las tareas del equipo de desarrollo, con el objetivo de lograr una correcta ejecución de la práctica de desarrollo que tribute a la colaboración en la ejecución de la misma y a la apropiación del software. 

#### Proceso de Construcción de Aplicaciones de Software Libre

El proceso de Construcción realiza un conjunto de actividades que se agrupan en las siguientes fases: Especificación de Requerimientos, Análisis y Diseño, Codificación, Pruebas y Liberación.

La Fase de Especificación de Requerimientos, se encarga de detallar los requerimientos funcionales y no funcionales, el primero de ellos constituye la descripción de los casos de uso, en los cuales se indica la interacción entre los usuarios y las funcionalidades del software, a su vez los no funcionales corresponden a la definición de todas aquellas restricciones sobre el software que limitan la construcción del mismo.

Seguidamente se encuentra la Fase de Análisis y Diseño comprendiendo la definición de la arquitectura del software, la especificación de los datos persistentes y el diseño de la interfaz de usuario.

La Fase de Codificación es la encargada de desarrollar las funcionalidades de la aplicación de software correspondientes a la iteración actual, fase donde se construye la interfaz de usuario y la base de datos.

Desde la Fase de Pruebas se elaboran y aplican pruebas funcionales y no funcionales a cada versión del software, así como pruebas de regresión y de instalación/desinstalación, con lo cual se facilita la detección temprana de errores y/o incompatibilidades en el código, esta fase se encuentra a cargo de probadores de software, quienes por lo general son personas distintas a quienes codifican la aplicación.

Finalmente se encuentra la Fase de Liberación encargada de llevar a cabo actividades asociadas a la liberación de versiones del software, así como la elaboración de manuales, empaquetado del software y publicación de versiones beta como versiones estables. 

Para conocer más sobre la Metodología para el Desarrollo Colaborativo de Software Libre, por favor visite:  
[https://www.cenditel.gob.ve/node/1557](https://www.cenditel.gob.ve/node/1557)

## Validar requerimientos previos

### Requerimientos previos

    php >= 8.2.x
    php-gd
    php-mbstring
    php-xml
    php-tokenizer
    php-zip
    php-pgsql
    php-cli
    php-curl
    php-redis
    curl
    composer
    zip
    unzip
    nodejs
    postgresql
    versión de nodejs requerida: v14.18.2
    versión de npm requerida: v8.11.0
