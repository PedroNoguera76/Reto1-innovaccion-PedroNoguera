# Conceptos básicos de Azure
## <p>Computo <br>
Un equipo de computo es un dispositivo electrónico que cuenta con una tarjeta madre que es la que controla los demás componentes del equipo, un procesador, una memoria RAM (almacenamiento temporal de la información), Memoria de almacenamiento (donde se guarda la infomación del usuario y del sistema) y software que es la conección entre el usuario y el equipo, gracias al cual el usuario puede asignar órdenes al equipo para realizar procesos. </p>
Esta es la estructura base de un equipo de computo, dependiendo del tipo de equipo puede estar acompañando en un teclado, ratón y monitor o solamente una pantalla táctil que suple las funciones del teclado y ratón como es el caso de los celulares y tabletas. </p>
![partes de la computadora](http://www.accesoriosparacomputadores.co/blog/wp-content/uploads/2015/03/principales-partes-del-computador.jpg)
## Comunicación entre equipos de computo <br>
Los equipos de computo pueden comunicarse o transmitir información principalmente a través de señales infrarojas (en el pasado), por señales de radio bluethood y redes (eternet y wifi). Además para que los equipos de computo se puedan comunicar requierende un lenguaje o protocolo de comunicación </p>
La comunicación por medio de redes es la que permite la transferencia de datos con la mayor velocidad y es la más utilizada en la comunicación entre computadoras. </p>
El lenguaje de comunicación se conoce como TCP/IP (Protocolo de Control de Transmisión/Protocolo de Internet). Mediante este leguaje se pueden transferir datos entre equipos de computo dentro de una misma infraestructura 8red local) o servidor y por medio de internet entre diferentes infraestructuras o servidores los cuales pueden estar ubicados incluso continentes diferentes, además esta comunicación permite que de manera remota se pueda operar un equipo de computo desde otra ubicación física </p>
El modelo OSI explica las redes de comunicación en 7 capas o niveles: </p>
- **Nivel físico**: Señal y transmisión binaria </p>
- **Nivel de enlace de datos**: direccionamiento físico </p>
- **Nivel red**: Determinación de ruta e IP (direccionamiento lógico) </p>
- **Nivel de transporte**: conexión extremo- extremo y fiabilidad de los datos </p>
- **Nivel sesión**: comunicación entre dispositivos de la red </p>
- **Nivel de Presentación**: Representación de los datos </p>
- **Nivel aplicación**: servicios de red a aplicaciones </p>
![Comunicacion entre equipos de cómputo](http://www.alegsa.com.ar/Diccionario/Imagenes/modelo_osi.png)
## <p> Nube <br>
Conocido como el computo en la nube, es un sevicio que permite la disponibilidad y uso de recursos de almacenamiento y capacidad de computo, como memoria RAM y procecadores, de forma remota desde otro dispositivo de computo mediante el uso de redes. </p>
Los recursos y servicios que ofrecen las nubes son impresionantes y le permiten al usuario disponer de datos sin tener que almacenarlos físicamente en su dispositivo, además permite de manera sencilla y rápida el compartir esta información, también funciona como un respaldo de esta información. </p>
Pero el almacenamiento no es lo único, también se puede usar de forma remota que equipos de computo con mayor capacidad de procesamiento y memoria sin tener que comprar una computadora muy potente, puesto que se puede rentar por un determinado tiempo reduciendo de esta forma los gastos de capital, otro de los servición de la nube es el uso de aplicaciones especializadas.
<br>
![nube](https://www.muycomputer.com/wp-content/uploads/2015/02/Almacenamiento_Nube-630x450.jpg)
<br>
## Tipos de nubes
#### Existen tres tipos de nube:
- **Nube privada**:
Una persona, organización o empresa es dueña de la infraestructura, es decir, de los servidores, el espacio físico donde estos se encuentran, se encarga del software y su configuración. El uso de este recurso es restringido y el mantenimiento es responsabilidad del dueño de la nube

- **Nube pública**:
Se denomina así cuando los recursos y servicios de la nube están a disposición de cualquier usuario que desee contratar dicho servicio. Bajo este esquema el mantenimiento de la nube corre bajo la responsabilidad del dueño de la nube y el usuario no tiene de que preocuparse por eso.
- **Nube híbrida**:
En este esquema el usuario (organización o empresa) es dueño de su nube pero además contrata los servicios de una nube pública para y correr algunas aplicaciones en estos servidores, de esta forma el usuario pude incrementar su capacidad de operación cuando lo requiera.
![Tipos de nubes](https://www.muycomputerpro.com/wp-content/uploads/2018/07/nube-hibrida.jpg)
## Servicios que ofrecen las nubes
- **IAAS (Infraestructura como servicio)**: La nube provee el servidor, maquina virtual con la memoria y procesamiento deseado pero el software y configuración corren por cuenta del usuario
- **PAAS (Plataforma como servicio)**: La nube provee el servidor, memoria, procesamiento y sistema operativo pero el usuario debe instalar sus aplicaciones así como encargarse de toda la configuración de estas
- **SAAS (Software como servicio)**: La nube provee tanto la infraestructura como el software que neesita el usuario para correr sus procesos

La nube provee tanto la infraestructura como el software que neesita el usuario para correr sus procesos

![Servicios que ofrecen las nubes](https://profile.es/wp-content/media/modelos-servicios-cloud-iaas-paas-saas.jpg)

## Servicios Azure
Azure es la nube de Microsoft que permite el uso de recursos y aplicaciones al rededor del mundo. Azure provee más de 100 servicios que permiten hacer cualquier cosa desde correr una aplicación existente hasta explorar nuevos paradigmas en software como inteligancia artificial y realidad aumentada. Los servicios más utilizados de Azure se pueden resumir de la siguiente forma:
<ul>
<li><h3>Servicios de infraestructura</h3>
<ul>
<li><b>Computo</b>: Maquinas vituales y Contenedores</li>
<li><b>Almacenamiento</b>: BLOB Storage, Azzure files, Premium Storage</li>
<li><b>Redes</b>: Virtual Network, Load Balancer, DNS, Express Router, Traffic Manager, VPN Gateway y Application Gateway</li>
</ul>
</li>
<li><h3>Servicios de plataforma</h3>
<ul>
<li><b>Computo</b>: Cloud Services, Services Fabric, Batch y Remote App</li>
<li><b>Web and mobile</b>: Web Apps, API Apps, API Managment, Mobile Apps, Logic Apps y Notification Hubs</li>
<li><b>Servicios de desarrollador</b>: Visual Studio, Azure SDK, Team Project y Applications Insights</li>
<li><b>Integración</b>: Storage Queues, BizTalk Services, Hybrid Connections y Service Bus</li>
<li><b>Analytics and IOT</b>: HDInsight, Machine Learning, Data Factory, Event Hubs, Stream Analytics y Mobile Engagement</li>
<li><b>Datos</b>: SQL Database, SQL Data Warehouse, Redis Cache, Search, cosmos DB y Tables</li>
<li><b>Media and CDN</b>: Media Services y Content Delivery Network (CDN)</li>
</ul>
</li>
<li><b>Operaciones Híbridas</b>: Azure AD Connect Health, Ad Privileged Identity Management, Backup, Operational Insights, Import/Export, Site Recovery y StorSimple</li>
<li><b>Servicios de Seguridad</b>: Portal, Active Directory, multi-Factor Authentication, Automation, Key Vault, Store/Marketplace y VM Image Gallery and VM Depot</li>
</ul>
<img src="https://www.keykumo.com/wp-content/uploads/2016/08/azure-keykumo.png"></img>
<h2>Zonas de Azure</h2>
<b>Regiones</b>: Son áreas geográficas del planeta que tienen al menos uno centro de datos, pero potencialmente más, que son cercanos entre sí con una red de baja latencia.
<br>
<b>Geograficas</b>: Son regiones geopolíticas o fronteras entre paíces que tienen 2 o más regiones que preservan el almacenamiento de los datos. La geografía esta dividida en las siguientes áreas:
<ul>
<li><b>Americanas</b></li>
<li><b>Europa</b></li>
<li><b>Asia-Pacífico</b></li>
<li><b>Oriente medio y África</b></li>
<li><b>Zonas de disponibilidad</b>: Se llama así a las zonas conformada por centros de datos que interactuan entre sí guardando la información como duplicado una de otras, es decir la inforación de un centro de datos también esta almacenada en el otro centro de datos. Una condición importante es que los centros de datos deben estar lo suficiente separados uno de otro para no ser afectados por los mismos fenómenos naturales.</li></ul>
<img src="https://azurecomcdn.azureedge.net/cvt-93da322b8e36592b6fa17faa77857ee4467225501ecd84a7c5466e5d0f790b30/images/shared/regions-map-mobile.svg"/>
<h2> Creación de la cuenta de Azure</h2>
Con la creación de una cuenta Azure se pueden crear, probar e implementar aplicaciones empresariales. Además de crear aplicaciones web y experiencia mobiles, así como obtenger información de sus datos a través del aprendizaje automático y analítico.
En odas las cuentas se debe especificar el nombre, email, información de contacto, información de facturación y tarjeta de crédito, existen varios tipos de cuentas: 
<ul>
<li> Subscripción gratuita: Esta suscripción incluye un crédito de 200 usd para ser utilizados en cualquier servicio durante un lapso de 30 días. libre acceso a los productos más populares de Azure durante 12 meses. Para crearla se necesita un número telefónico, una tarjeta de crédito y una cuenta de Microsoft. - Subscripción Pay-as-you-go: En esta subscripción se cobra mensualmente por los servicios utilizados durante el periodo. esta es la más apropiada para la mayoría de los usuarios desde individuos hasta pequeñas empresas y algunas organizaciones grandes.</li>
<li> Subcripción Pay-as-you-go DEV/TEST Esta esta diseñada para subcriptores de Visual Studio y se limita exclusivamente para desarrollo y pruebas
- Azure Enterprise Agreement esta provee la mayor flexibilidaden la compra de servicios en la nube, ademas de contar con descuentos de nuevas licencias de seguros de Softwares.
<li> Subcripción Azure para estudiantes Esta incluye un crédito de 100 usd para ser usado en los primeros 12 meses además de poder seleccionar servicios sin requerimeinto de tarjeta de crédito. Solo se tiene que demostrar que se es estudiante.</li>
<li> Múltiples subcripciones con una misma cuenta: Es muy utilizado por empresas para controlar el acceso y facturación.</li>
</ul>
<ul><img src="https://i1.wp.com/gerardoverduzco.com/wp-content/uploads/2017/02/Microsoft-Azure-Registro-de-Prueba.png?resize=640%2C387"/>
<br>
<a href="https://docs.microsoft.com/es-es/azure/cost-management-billing/">Facturación de Azure</a>
<br>
<a href="https://azure.microsoft.com/es-es/free/">Como crear una cuenta en Azure</a>
<br>
<a href="https://azure.microsoft.com/es-mx/support/options/#overview">Ayuda y soporte</a>
</ul>

> ## Servicios de almacenamiento Azure
> Una cuenta de almacenamiento proporciona un espacio de nombres únicos para los datos de Azure Storage, al que se puede acceder desde cualquier lugar del mundo a través de HTTP o HTTPs.
- Azure Blob Storage: Puede almacenar grandes cantidades de datos, como datos de texto o binarios. No hay restricción en cuanto a los tipos de datos que puede contener. Se puede administrar miles de cargas simultáneas, cantidades de datos de video, registro en constatante crecimeinto y se puede acceder desde cualquier lugar con conexión a internet. No equiere que los desarrolladores piensen en discos. Almacenan en contenedores.
        - Visualización de imágenes o documentos directamente en un explorador.
        - almacenamiento de archivos para acceso distribuido.
        - Streaming de audio y video
        - Almacenamiento de datos para copia de seguridad y restauración, recuperación ante desastres y archivado.
        - Almacenamiento de datos para el análisis en local o en un servicio hospedado de Azure.
        - Almacenamiento de hasta 8 TB de datos para máquinas virtuales.
- Azure disk storage: usado por la máquinas virtuales. Los datos se almacenan de forma persistente y se pueden acceder desde un disco virtual conectado.
- Azure Files: Recursos compartidos de archivos totalmente administrados en la nube. Se tiene acceso mediante el protocolo del Bloque de mensaje del servidor y Network File Sytem. Se pueden montar simultaneamente en Windows, Linux y Macos en la nube o locales. (SMB)
- Niveles de acceso de blob de Azure: son proporcionados para equilibrar los costos de almacenamiento con sus necesidades de acceso. Ayuda a almacenar datos de objetos de la manera más rentable.
        - Nivel de acceso frecuente: optimizado para almecenar datos a los que se accede con frecuencia.
        - Niveles de acceso esporádicos: optimizado para datos a los que se accede con poca frecuencia y que se almacena al menos durante 30 días
        - Niveles de acceso de archivos: conviene para datos a los que raramente se accede y que se almacena durante al menos 180 días con requisito de latencia flexible.
> - Los niveles de acceso frecuente y esporádico se puede establecer con nivel de cuenta. 
> - Los niveles frecuente, esporádico y de archivo se pueden establecer en el nivel de blob durante la carga o después de esta.
> - Los datos de nivel de acceso esporádico pueden tolerar una disponibilidad ligeramente inferior pero con características de rendimeinto similares a las de datos de acceso frecuente
> - El almacenamiento de archivos almacena datos sin conexión y ofrece los menores costos de almacenamiento pero los mayores costos de acceso.

> # Almacenamiento de datos en Azure

>   Cosmos DB y SQL
> - Estructuradas: Datos relacionados, son datos que se ajustan a un esquema estricto por lo que tienen un mismo campo y propiedades. Es fácil con SQL (Lenguaje de consulta estructurado). Son fáciles de escribir, consultar y analizar. Todos siguen el mismo formato
> - Semiestructuradas: Son menos organizados y no se almacenan en forma racional. Contienen etiquetas que hacen evidentes la organización y jerarquía. Datos no relacionados o NoSQL. Lenguaje de serialización.
        - XML: Extensible Markup Language. <>
        - JSON: JavaScript Objet Notation. {} 
        - YAML: YAML Ain´t Markup Language. Espacios
    - Key- value: 
    - Graph
    - Document: 
> - no estructurados: La organización es ambigua, a menudo se entrgan en archivos, fotos o videos. 
Ejemplo: 
        - Archivo multimedia, como fotos, videos y archivos de audio.
        - Archivos de Office, como word
        - Archivos de texto
        - Archivos de registro

> ### Necesidades de Operación
> - Datos de catálogo de productos: Se requiere rapidez 
> - Fotografías y videos: tiempos de recuperación rápidos solo se tienen que recuperar por su identificador. Las actualizaciones serían menos frecuentes y menos prioritarias.
> - Datos empresariales: El análisis se produce en datos históricos, ningún datos se actualizara por el análisis, son de solo lectura. se puede tener cierta latencia en los resultados y se almacenaran en varios conjuntos de de datos.
> - Resumen:  

> ### Transacción
Es un grupo lógico de operaciones que se ejecutan juntas
> Garantías ACID: Atomicidad, Coherencia, aIslamiento y Durabilidad 
>   - Atomicidad: Una transacción debe ejecutarse una vez y debe ser atómica, realizar el trabajo en su totalidad.
>   - La coherencia: garantía que los datos sean coherentes tanto antes como después de la transacción
>   - El aislamiento: garantiza que una transacción no se vea afectada por otra. 
>   - La durabilidad: significa que los cambios realizados debido a la transacción se guardan de forma permanente en el sistema.
> - Diferencias entre OLTP y OLAP: Bases de datos trancicionales (OLTP), admiten muchos usuarios, tienen tiempo de respuesta rápidos y controlan grandes volúmenes de datos, son altamente disponibles y controlan transacciones relativamente sencillas o pequeñas. Los sitemas OALP tienen tiempos de respuesta más largos, su disponibilidad puede ser menor y controlan transacciones grandes y complejas
> - datos de catálogo de productos: se almacenan en datos transaccionales (OLTP)
> - Fotografías y videos: No son transaccionales por naturaleza
> - datos empresariales: No requieren ser transaccionales

> ### Elección de una solución de amacenamiento en Azure
> - datos de catálogo de productos
>       - Clasificación de los datos: Semiestructurados
        - alto rendimeinto y baja latencia
        - Capacidad transaccional
    - Se recomienda Azure Cosmos DB:
    admite datos NoSQL, es compatible con ACID, es más adecuada que Azure SQL, Azure Table Storage, Azure HBase y Azure Cache


> # Servicios de Azure Storage
> - Duradero: la redundancia garantiza que los datos estén seguros. Lo datos replicados permaneces con una alta disponibilidad
> - Seguro: El servicio cifra todos los datos escritos
> - escalable: Se puede escalar de forma masiva
> - Administrativo: Microsoft azure se encarga del matenimeinto y de cualquier problema

> ## Servicios de datos Azure
> - Blobs: un almacén de objetos que se pueden escalar de forma masiva
> - Archivos: Recursos compartidos
> - Colas: Un almacén de mensajería confiable
> - table storage: un Nosql para el almacenamiento sin esquema de datos estructurados
>Todos son accesibles desde cualquier lugar del mundo FTTP o HTTPS, proporcionan SDK y una API REST.
> - Blob Storage:
Es una solución de almacenamiento de objetos para el almacenamiento de cantidades masivas de datos no estructurados como texto o binarios
        - Blobs en bloques
        - blobs en páginas
        - Blobs anexos
> - Queues: se usa para almacenar y recuperar mensajes, pueden tener tamaños de hasta 64 kb

> ## Creación de una cuanta de Azure Storage
> - azure proporciona mucas formas de almacenar datos: Azure SQL Database, Azure Cosmos DB y Azure Table Storage. 
> - Varias maneras de almacenar y enviar mensajes: Azure Queue y Event Hubs.
> - almacenamiento de archivos dinámicos como Azure files y Azure Blobs.
> - Azure Storage: son todos los servicios de almacenamiento primitivos basados en la nube
>       - Azure Blobs
>       - Azure files
>       - Colas de Azure (Queues)
>       - azure tablas

> ### cuenta de almacenamiento
es un contenedor que agrupa un conjunto de servicios de almacenamiento de Azure, en las cuentas de almacenamiento solo se pueden incluir servicios de Azure Storage.
> - La cuenta incluye un grupo de recursos y un grupo de recursos puede contener 1 o más cuentas de almacenamiento
> - Los servicios Azure SQL y Cosmos DB se administran como recursos independientes y no se pueden incluir en la cuenta de almacenamiento.

>### Configuración de cuentas de almacenamiento
Opciones de configuración que controla la cuenta:
> - suscripción: a la que se facturan
> - Location: centro de datos en el que almacenan
> Rendimiento: discos físicos, servicio de datos:
>       - Estándar: cualquier servicio de datos y discos magnéticos
>       - Premiun: Servicios adicionales y unidades sólidas
> - replicación: Es la estrategia que se usa para realizar copias de datos. De forma automática 3 copias, LRS redundancia local. GRS replicación en otros centros de datos de cualquier parte del mundo
> - nivel de acceso: rapidez de acceso a los blobs de la cuenta. Frecuente y esporádico
> - Se requiere transferencia segura: característica de seguridad: HTTO y HTTPs
> - redes virtuales: característica de seguridad de recibir solicitudes de acceso para las redes virtuales especificadas

> - diversidad de datos: lugar de consumo, grado de confiabilidad, grupo de facturación.
Mayor diversidad implica mayor número de cuentas de almacenamiento
> - susceptibilidad a los costos: la configuración afecta al costo de los servicios. La redundancia geográfica cuesta más que el local, el nivel de acceso premium aumenta el costo. Para reducir los costos se pueden crear varias cuentas en función del tipo de datos, críticos y no críticos. 
> tolerancia a la sobrecarga de administración: Se recomeinda analizar los datos agrupandolos según la ubicación, facturación y estrategia de replicación.

>### Configuración de la cuenta
Opciones de configuración:
        - Nombre: Debe ser único de forma Global en Azure, alfanumérico y debe tener entre 3 y 24 caracteres
        - Modelo de implementación:
                - Resource Manager: (modelo actual) permite decidir fácilmente qué modelo elegir. 
                - Clásico: (oferta heredada)
        - Tipo de cuenta:
                - storageV2: oferta actual, compatible con todos los tipos de almacenamiento
                - Storage: tipo heredado que admite todos los tipos de almacenamiento pero no todas las características
                - Blob Storage: Tipo heredado que solo permite bloques y blobs en anexos

>### Elección de una herramienta
Interfaz gráfica y automatización, importantes para tomar la decisión:
> Herramientas disponibles:
>       - Azure portal
>       - CLI de Azure
>       - Azure PowerShell
>       - Bibliotecas de clientes de administración: permite crear una aplicación cliente

 ## Disco de almacenamiento VM
 Discos locales y administrados no administrados
 > - Roles de discos
 >      - Disco SO: Sistema operativo, el disco tiene una capacidad maxima de 2048 GB
 >      - Discos de datos: Puede agregar uno o más datos a cada máquina virtual para lamecenar datos, la capacidad máxima de cada disco es de 32767 GB
 >      - Disco temporal: es solo uno, almacenamiento a corto plazo, se pierde la información en el mantenimiento

 > - Discos OP efímeros: almacena localmente los datos, tienen una latencia más rápida que el administrado. Pero un error podría destruir toda la información. No incurren en costos de almacenamiento y son gratuitos.
 > - discos Administrados: son fáciles de usar, Azure los administra, se almacenan como blobs en páginas Azure Storage, pero no se necesita crear personalmente la cuenta. Las ventajas se resumen:
 >              - Escalabilidad sencilla: se pueden crear hasta 50000 discos administrados en cada región.
 >              - Alta disponibilidad: 99.999%, almacenan los datos 3 veces.
 >              - integración con conjuntos de disponibilidad y zonas: 
 >              - Compatibilidad con Azure blackup: admite de forma nativa los discos administrados.
 > - Control de aceso pormenorizado: se puede usar RBAC, acceso basado en rol
 >              - compatibilidad con cifrado: Storage Service Encryption (SSE). Azure Disk encryption (ADE) y DM-Crupt

 > - Discos no administrados: se almacena como blob en páginas de Azure Storage. Se crea y se mantiene de forma manual. Se debe administrar la seguridad. No se usan con tanta frecuencia.

 > ### Rendimiento de discos 
 Operaciones de entrada y salida por segundo (IOPS). Velocidad del disco. Rendimiento velocidad de transferencia de datos.
 > - SSD: disco sólido tienen mayor capacidad IOPS
 >        - SSD Ultra: el mayor IOPS y rendimiento: no admiten imagenes de máquinas virtuales
 >        - SSD premiun: intermedio
 >        - SSD: estándar: bajo. Proporciona 25MBS pero no los garantiza
 > - HDD estándar:  menor IOPS que SSD estándar pero mayor rendimiento

 >## cosmos DB
 Es fexible, almacena los datos en forma de registro de átomos (ARS). Como opciones se incluyen: SQL, MongoDB, Cassandra, Tables y Gremlin. por lo que se puede migrar facilmente entre diferentes empresas.