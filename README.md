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
