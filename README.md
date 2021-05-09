> # Mi repositorio para el Reto 1  
> ## Conceptos básicos de Azure
> - <p>Computo <br>
> Un equipo de computo es un dispositivo electrónico que cuenta con una tarjeta madre que es la que controla los demás componentes del equipo, un procesador, una memoria RAM (almacenamiento temporal de la información), Memoria de almacenamiento (donde se guarda la infomación del usuario y del sistema) y sofrware que es la conección entre el usuario y el equipo, gracias al cual el usuario puede asignar órdenes al equipo para realizar procesos. </p>
> Esta es la estructura base de un equipo de computo, dependiendo del tipo de equipo puede estar acompañando en un teclado, ratón y monitor o solamente una pantalla tactil que suple las funciones del teclado y ratón como es el caso de los celulares y tabletas. </p>
> ![partes de la computadora](/fotos/principales-partes-del-computador.jpg)
> - <p>Comunicación entre equipos de computo <br>
> Los equipos de computo pueden comunicarse o transmitir información principalmente a través de señales infrarojas (en el pasado), por señales de radio bluethood y redes (eternet y wifi). Además para que los equipos de computo se puedan comunicar requierende un lenguaje o protocolo de comunicación </p>
La comunicación por medio de redes es la que permite la transferencia de datos con la mayor velocidad y es la más utilizada en la comunicación entre computadoras. </p>
El lenguaje de comunicación se conoce como TCP/IP (Protocolo de Control de Transmisión/Protocolo de Internet). Mediante este leguaje se pueden transferir datos entre equipos de computo dentro de una misma infraestructura 8red local) o servidor y por medio de internet entre diferentes infraestructuras o servidores los cuales pueden estar ubicados incluso continentes diferentes, además esta comunicación permite que de manera remota se pueda operar un equipo de computo desde otra ubicación física </p>
El modelo OSI explica las redes de comunicación en 7 capas o niveles: </p>
    - Nivel físico: Señal y transmisión binaria </p>
    - Nivel de enlace de datos: direccionamiento físico </p>
    - Nivel red: Determinación de rutae IP (direccionamiento lógico) </p>
    - Nivel de transporte: conexión extremo- extremo y fiabilidad de los datos </p>
    - Nivel sesión: comunicación entre dispositivos de la red </p>
    - Nivel de Presentación: Representación de los datos </p>
    - Nivel aplicación: servicios de red a aplicaciones </p>
> 
> - <p> Nube <br>
Conocido como el computo en la nube, es un sevicio que permite la disponibilidad y uso de recursos de almacenamiento y capacidad de computo, como memoria RAM y procecadores, de forma remota desde otro dispositivo de computo mediante el uso de redes. </p>
Los recursos y servicios que ofrecen las nubes son impresionantes y le permiten al usuario disponer de datos sin tener que almacenarlos físicamente en su dispositivo, además permite de manera sencilla y rápida el compartir esta información, también funciona como un respaldo de esta información. </p>
Pero el almacenamiento no es lo único, también se puede usar de forma remota que equipos de computo con mayor capacidad de procesamiento y memoria sin tener que comprar una computadora muy potente, puesto que se puede rentar por un determinado tiempo reduciendo de esta forma los gastos de capital. </p>
Por último otro de los servición de la nube es el uso de aplicaciones especializadas. <p>
Existen tres tipos de nubes: <p>
> ![nube](/fotos/AzureNube.jpg)
>   - <p> Nube privada: <br> 
Una persona, organización o empresa es dueña de la infraestructura, es decir, de los servidores, el espacio físico donde estos se encuentran, se encarga del software y su configuración. El uso de este recurso es restringido y el mantenimiento es responsabilidad del dueño de la nube </p>
    - Nube pública: </p>
Se denomina así cuando los recursos y servicios de la nube están a disposición de cualquier usuario que desee contratar dicho servicio. Bajo este esquema el mantenimiento de la nube corre bajo la responsabilidad del dueño de la nube y el usuario no tiene de que preocuparse por eso. </p>
    - Nube híbrida </p>
En este esquema el usuario (organización o empresa) es dueño de su nube pero además contrata los servicios de una nube pública para y correr algunas aplicaciones en estos servidores, de esta forma el usuario pude incrementar su capacidad de operación cuando lo requiera. </p>
> - Servicios que ofrece las nubes
    <p> - IAAS: Infraestructura como servicio <br>
    La nube provee el servidor, maquina virtual con la memoria y procesamiento deseado pero el software y configuración corren por cuenta del usuario </p>
        - PAAS: Plataforma como servicio </p>
    La nube provee el servidor, memoria, procesamiento y sistema operativo pero el usuario debe instalar sus aplicaciones así como encargarse de toda la configuración de estas </p>
        - SAAS: Software como servicio </p>
    La nube provee tanto la infraestructura como el software que neesita el usuario para correr sus procesos </p>
> 
> ### Servicios Azure
> Azure es la nube de Microsoft que permite el uso de recursos y aplicaciones al rededor del mundo. Azure provee más de 100 servicios que permiten hacer cualquier cosa desde correr una aplicación existente hasta explorar nuevos paradigmas en software como inteligancia artificial y realidad aumentada.
>   Los servicios más utilizados de Azure se pueden resumir de la siguiente forma:
> - Servicios de infraestructura
>   - Computo: Maquinas vituales y Contenedores
>   - Almacenamiento: BLOB Storage, Azzure files, Premium Storage
>   - Redes: Virtual Network, Load Balancer, DNS, Express Router, Traffic Manager, VPN Gateway y Application Gateway
> - Servicios de plataforma
>   - Computo: Cloud Services, Services Fabric, Batch y Remote App
>   - Web and mobile: Web Apps, API Apps, API Managment, Mobile Apps, Logic Apps y Notification Hubs
>   - Servicios de desarrollador: Visual Studio, Azure SDK, Team Project y Applications Insights
>   - Integración: Storage Queues, BizTalk Services, Hybrid Connections y Service Bus
>   - Analytics and IOT: HDInsight, Machine Learning, Data Factory, Event Hubs, Stream Analytics y Mobile Engagement
>   - Datos: SQL Database, SQL Data Warehouse, Redis Cache, Search, cosmos DB y Tables
>   - Media and CDN: Media Services y Content Delivery Network (CDN)
> - Operaciones Híbridas:
> Azure AD Connect Health, Ad Privileged Identity Management, Backup, Operational Insights, Import/Export, Site Recovery y StorSimple
> - Servicios de Seguridad
> Portal, Active Directory, multi-Factor Authentication, Automation, Key Vault, Store/Marketplace y VM Image Gallery and VM Depot
> ### Arquitectura de Azure
> - Regiones: 
> Son áreas geográficas del planeta que tienen al menos uno centro de datos, pero potencialmente más, que son cercanos entre sí con una red de baja latencia.
> - Geografías
> Son regiones geopolíticas o fronteras entre paíces que tienen 2 o más regiones que preservan el almacenamiento de los datos. La geografía esta dividida en las siguientes áreas:
>   - Americas
>   - Europa
>   - Asia Pacífico
>   - Oriente Medio y África
>   - Zonas de disponibilidad
> Se llama así a las zonas conformada por centros de datos que interactuan entre sí guardando la información como duplicado una de otras, es decir la inforación de un centro de datos también esta almacenada en el otro centro de datos. Una condición importante es que los centros de datos deben estar lo suficiente separados uno de otro para no ser afectados por los mismos fenómenos naturales.
 > ### Cualidades de la nube Azure
 > - Escalabilidad
 >      - Horizontal: es la capacidad de incrementar los recursos agregando máquinas virtuales.
 >      - Vertical: es la capacidad de incrementar memoria y procesador al servisio que ya se tiene.
 > - Elasticidad
 > - Agilidad
 > - Tolerancia a fallos: es la abilidad del sistema de recuperarse de fallos y poder continuar
 > - Alta disponibilidad: debe estar disponible todo el tiempo

 > - Acuerdo de Nivel de Servicio (SLA)
 > Microsoft realiza un acuerdo de calidad de servicio con los usuarios a través de un decumento denominado SLA, este documento contiene los términos que definen los estándares de ejecución  que aplican para Azure
 >      - SLA describe los compromisos de Microsoft Azure con estandares específicos de ejecución
 >      - Existen SLAs para cada producto y servicio de Azure de forma individual
 >      - SLAs también especifica que pasa si el servicio o producto falla
 > En base a esto existen tres caraterísticas para las SLAs de Azure para productos y servicios:
 >      - Etiquetas de desarrollo
 >      - Garantía de conectividad
 >      - Crédito de servicio: si Azure falla en sus acuerdos, ellos bonificarán un credito al usuario

 > ### Creación de cuenta en Azure
 >Con la creación de una cuenta Azure se pueden crear, probar e implementar aplicaciones empresariales. Además de crear aplicaciones web y experiencia mobiles, así como obtenger información de sus datos a través del aprendizaje automático y
analítico 
> - Existen diferentes tipos de cuentas:
> todas las cuentas se debe especificar el nomnre, email, información de contacto, información de facturación y tarjeta de crédito.
>       - Subscripción gratuita: 
> Esta suscripción incluye un crédito de 200 usd para ser utilizados en cualquier servicio durante un lapso de 30 días. libre acceso a los productos más populares de Azure durante 12 meses. Para crearla se necesita un número telefónico, una tarjeta de crédito y una cuenta de Microsoft.
>       - Subscripción Pay-as-you-go:
> En esta subscripción se cobra mensualmente por los servicios utilizados durante el periodo. esta es la más apropiada para la mayoría de los usuarios desde individuos hasta pequeñas empresas y algunas organizaciones grandes.
>       - Subcripción Pay-as-you-go DEV/TEST
> Esta esta diseñada para subcriptores de Visual Studio y se limita exclusivamente para desarrollo y pruebas
>       - Azure Enterprise Agreement
> esta provee la mayor flexibilidaden la compra de servicios en la nube, ademas de contar con descuentos de nuevas licencias de seguros de Softwares.
>       - Subcripción Azure para estudiantes
> Esta incluye un crédito de 100 usd para ser usado en los primeros 12 meses además de poder seleccionar servicios sin requerimeinto de tarjeta de crédito. Solo se tiene que demostrar que se es estudiante.
>       - Múltiples subcripciones con una misma cuenta:
> Es muy utilizado por empresas para controlar el acceso y facturación.
> - Facturación en Azure
> - Como crear una cuenta en Azure
> - Como obtener ayuda y soporte
