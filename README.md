# Notes-AWS

Repositorio de cosas importantes de AWS

<h1> Servicios de informática de AWS </h1>

<h2> EC2 Elastic Compute Cloud </h2>

<p> Basicamente lo que entendi es que son maquinas virtuales en la nube que se pagan bajo demanda </p>

<h3> Tipos de instancias </h3>
<p> Son diferentes tipos de instancias de lo mismo y dependen de que quieras almacenamiento o procesamiento de datos </p>

<p> Como regla general esta tipodeinstacia.tamaño algunos <strong>Ejemplos:</strong> </p> 

<ol>
<li>c6g.medium</li> 
<li>c6g.large </li>
<li>c6g.xlarge</li>
</ol>

<h2> Amazon Lightsail </h2>

<p> Testing¹ revela que las instancias de Lightsail, de hecho, son instancias EC2, de la t2clase de instancias burstables.
Fuente(https://qastack.mx/programming/40927189/what-is-difference-between-lightsail-and-ec2)</p>

<p> servidor privado virtual (o instancia de Lightsail).</p>

<h2> Amazon Elastic Block Store (EBS) </h2>

<p> 
Elastic block store (EBS) para almacenamiento persistente se refiere si cuando termine la ejecucion de una maquina o virtual private server si los datos van a quedar almacenados o no se borran.</p>

<h2> AWS Management Console </h2>

<p> La AWS Management Console es una aplicación web que engloba y hace referencia a un amplio conjunto de consolas de servicios para la administración de Amazon Web Services.</p>

<h2> Amazon Elastic Container Service (ECS) </h2>

<p> Dockers  en la nube! Amazon ECS makes it easy to deploy, manage, and scale Docker containers running applications, services, and batch processes. Amazon ECS places containers across your cluster based on your resource needs and is integrated with familiar features like Elastic Load Balancing, EC2 security groups, EBS volumes and IAM roles. Amazon ECS uses Docker images in task definitions to launch containers as part of tasks in your clusters. </p> 

<h2>  Amazon Machine Image (AMI) </h2> 

<p> Una Amazon Machine Image (AMI) proporciona la información necesaria para lanzar una instancia. Debe especificar una AMI al lanzar una instancia. Cuando necesite varias instancias con la misma configuración, puede lanzarlas desde una misma AMI. Cuando necesite instancias con distintas configuraciones, puede usar distintas AMI para lanzarlas.  <p>
  
<h2> ¿Qué diferencia hay entre utilizar el almacén de instancias local y Amazon Elastic Block Storage (Amazon EBS) para el dispositivo raíz? </h2> 

<p> Cuando lanza las instancias de Amazon EC2, tiene la opción de almacenar los datos del dispositivo raíz en Amazon EBS o en el almacén de instancias local. Mediante el uso de Amazon EBS, los datos en el dispositivo raíz persistirán independientemente del ciclo de vida de la instancia. Esto le permite detener y reiniciar la instancia con posterioridad de un modo similar a cuando apaga un portátil y lo enciende cuando lo vuelve a necesitar.

De forma alternativa, el almacén de instancias local solo persiste durante la vida de la instancia. Esta es una forma económica de lanzar instancias en la que los datos no se almacenan en el dispositivo raíz. Por ejemplo, algunos clientes utilizan esta opción para ejecutar sitios web de gran tamaño en los que cada instancia es un clon para gestionar tráfico web. </p>

<h2> Elastic Load Balancing </h2> 

<p> distribuye automáticamente el tráfico entrante entre varios destinos, por ejemplo, instancias EC2, contenedores y direcciones IP en una o varias zonas de disponibilidad. Monitorea el estado de los destinos registrados y enruta el tráfico solamente a destinos en buen estado. Elastic Load Balancing escala el balanceador de carga a medida que el tráfico entrante va cambiando con el tiempo. Puede escalarse automáticamente para adaptarse a la mayoría de las cargas de trabajo. </p>

<h2> AWS Fargate </h2>

<p> AWS Fargate es un motor informático sin servidor de pago por uso que permite centrarse en la creación de aplicaciones sin tener que administrar los servidores. AWS Fargate es compatible con Amazon Elastic Container Service (ECS) y Amazon Elastic Kubernetes Service (EKS). </p>

<h2> Amazon Elastic Container Registry (Amazon ECR) </h2>

<p> Es como Dockerhub por lo que entiendo osea tu subes tu docker image la encriptas y en cualquier lado la bajan y la usan </p>


<h2>IAM - AWS Identity and Access Management</h2>

<p> Con AWS Identity and Access Management (IAM) puede administrar el acceso a los servicios y recursos de AWS de manera segura. Además, puede crear y administrar usuarios y grupos de AWS, así como utilizar permisos para conceder o negar el acceso de estos a los recursos de AWS.</p>

<h1> Servicios de AWS Analytics </h1>

<h2>Amazon ElasticSearch </h2>

<p> Amazon Elasticsearch Service is a managed service that makes it easy to deploy, operate, and scale Elasticsearch in the AWS Cloud. Elasticsearch is a popular open-source search and analytics engine for use cases such as log analytics, real-time application monitoring, and click stream analytics.</p>

<h2>  Amazon Elastic MapReduce </h2> 

<p> Amazon EMR (previously called Amazon Elastic MapReduce) is a managed cluster platform that simplifies running big data frameworks, such as Apache Hadoop and Apache Spark , on AWS to process and analyze vast amounts of data. </p>

<h2> Amazon Kinesis </h2> 

<p> Amazon Kinesis makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information. Amazon Kinesis offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application. With Amazon Kinesis, you can ingest real-time data such as video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning, analytics, and other applications. Amazon Kinesis enables you to process and analyze data as it arrives and respond instantly instead of having to wait until all your data is collected before the processing can begin.</p>


<h2> Amazon Athena </h2>

<p> Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run. Athena is easy to use.</p>

<h1> Servicios de base de datos de AWS </h1>

<h2> Amazon DynamoDB </h2> 

<p> Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. DynamoDB lets you offload the administrative burdens of operating and scaling a distributed database so that you don't have to worry about hardware provisioning, setup and configuration, replication, software patching, or cluster scaling. DynamoDB also offers encryption at rest, which eliminates the operational burden and complexity involved in protecting sensitive data </p> 

<h2> Amazon Relational Database Service  </h2> 

<p> Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups. It frees you to focus on your applications so you can give them the fast performance, high availability, security and compatibility they need.</p>

<h2> Amazon Redshift </h2> 

<p> Welcome to the Amazon Redshift Cluster Management Guide. Amazon Redshift is a fully managed, petabyte-scale data warehouse service in the cloud. You can start with just a few hundred gigabytes of data and scale to a petabyte or more. This enables you to use your data to acquire new insights for your business and customers. </p>

<h2> Amazon Aurora </h2>

<p> Amazon Aurora is a MySQL and PostgreSQL-compatible relational database built for the cloud that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.</p>

<h1> Herramientas para desarrolladores de AWS </h1> 

<h2> Amazon CodeCommit </h2> 

<p> AWS CodeCommit is a managed source control system that hosts Git repositories and works with all Git-based tools.

AWS CodeCommit will store code, binaries, and metadata in a redundant fashion with high availability. You will be able to collaborate with local and remote teams to edit, compare, sync, and revise your code. </p>

<h2> Amazon CodePipeline </h2> 

<p> AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. This enables you to rapidly and reliably deliver features and updates. You can easily integrate AWS CodePipeline with third-party services such as GitHub or with your own custom plugin. With AWS CodePipeline, you only pay for what you use. There are no upfront fees or long-term commitments </p>

<p>  CodePipeline crea, prueba e implementa su código siempre que hay un cambio de código, con base en los modelos de proceso de la versión que define. Esto le permite brindar rápida y confiablemente características y actualizaciones. </p>

<h2> AWS CodeBuild </h2>

<p> AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers. </p> 

<h2> What are the differences? </h2>

<p> The main difference between the two is; AWS CodeBuild can be classified as a tool in the Continuous Integration category, while AWS CodePipeline is grouped under Continuous Deployment.</p>

<h2> What is Continuous Integration? </h2> 

<p>Continuous integration is a software development method where members of the team can integrate their work at least once a day. In this method, every integration is checked by an automated build to search the error.

In continuous integration after a code commit, the software is built and tested immediately. In a large project with many developers, commits are made many times during a day. With each commit code is built and tested. If the test is passed, build is tested for Deployment. If the Deployment is a success, the code is pushed to production. This commit, build, test, and deploy is a continuous process, and hence the name continuous integration/deployment.</p>

<h2> What is Continuous Delivery? </h2>

<p> Continuous delivery is a software engineering method in which a team develops software products in a short cycle. It ensures that software can be easily released at any time.

The main aim of continuous delivery is to build, test, and release software with good speed and frequency. It helps you to reduce the cost time and risk of delivering changes by allowing for frequent updates in production. </p>

<h2> Ejemplos </h2>

<p> Jenkins es un servidor open source para la integración continua. Es una herramienta que se utiliza para compilar y probar proyectos de software de forma continua, lo que facilita a los desarrolladores integrar cambios en un proyecto y entregar nuevas versiones a los usuarios.</p>

<h2> Amazon CodeDeploy </h2> 

<p> AWS CodeDeploy is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. ... You can use AWS CodeDeploy to automate software deployments, eliminating the need for error-prone manual operations.</p>

<h1> Herramientas de administración de AWS </h1> 

<p> AWS proporciona cuatro tipos de herramientas de administración que trabajan juntas y están integradas en cada parte de la plataforma AWS, desde Amazon EC2 hasta Amazon DynamoDB, con el fin de que usted controle con facilidad todas las partes en la infraestructura de la nube.</p>

<h2> Amazon CloudFormation </h2>

<p> AWS CloudFormation is a service that gives developers and businesses an easy way to create a collection of related AWS and third-party resources, and provision and manage them in an orderly and predictable fashion.</p>
  
  <h2> Amazon CloudWatch </h2> 
  
  <p> Amazon CloudWatch is a monitoring service for Amazon Web Services cloud resources and the applications you run on Amazon Web Services. You can use Amazon CloudWatch to collect and track metrics, collect and monitor log files, set alarms, and automatically react to changes in your Amazon Web Services resources.</p> 
  
  <h2>  AWS Systems Manager </h2> 
  
  <p> AWS Systems Manager (formerly known as SSM) is an AWS service that you can use to view and control your infrastructure on AWS. Using the Systems Manager console, you can view operational data from multiple AWS services and automate operational tasks across your AWS resources. </p> 
  
  <h1> Servicios de almacenamiento de AWS </h1>
  
  <h2> Amazon Elastic Block Store (EBS) </h2>
  
  <p> Amazon Elastic Block Store (Amazon EBS) es un servicio de almacenamiento en bloque fácil de usar, escalable y de alto rendimiento diseñado para Amazon Elastic Compute Cloud (Amazon EC2). </p>
  
  <h2> Amazon EFS resources </h2> 
  
  <p> Amazon Elastic File System (Amazon EFS) is a simple, serverless, set-and-forget, elastic file system. There is no minimum fee or setup charge. You pay only for the storage you use, for read and write access to data stored in Infrequent Access storage classes, and for any provisioned throughput. </p>
  
  <h2> Amazon S3 </h2> 
  
  <p>Amazon S3 is an object storage service that stores data as objects within buckets. An object is a file and any metadata that describes the file.</p>
  
  <h2> Amazon Glacier </h2>
  
  <p> Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 storage class for data archiving and long-term backup. With S3 Glacier, customers can store their data cost effectively for months, years, or even decades. </p>
  
  <p> Amazon S3 is a durable, secure, simple, and fast storage service, while Amazon S3 Glacier is used for archiving solutions. Use S3 if you need low latency or frequent access to your data. ... S3 and Glacier are designed for availability of 99.99%. S3 can be used to host static web content, while Glacier cannot.</p>
  
  <h1> Servicios de entrega de contenido y redes de AWS </h1>
  
  <h2>Amazon Virtual Private Cloud (VPC)  </h2> 
  
  <p>  Amazon Virtual Private Cloud (VPC) gives you complete control over your virtual networking environment, including resource placement, connectivity, and security. The first step is to create your VPC. Then you can add resources to it, such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, you can define how your VPCs communicate with each other across accounts, Availability Zones (AZs), or Regions. In the example below, network traffic is shared between two VPCs within each region.
  </p>
  
<h2> Amazon Route 53 </h2> 

<p> Amazon Route 53 provides highly available and scalable Domain Name System (DNS), domain name registration, and health-checking web services. It is designed to give developers and businesses an extremely reliable and cost effective way to route end users to Internet applications by translating names like example.com into the numeric IP addresses, such as 192.0.2.1, that computers use to connect to each other. </p>

<h2> Amazon DirectConnect </h2>
<p>  AWS Direct Connect is a cloud service that links your network directly to AWS, bypassing the internet to deliver more consistent, lower-latency performance.</p>

<h2> Elastic Load Balancing </h2>

<p>Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets and virtual appliances in one or more Availability Zones (AZs). </p> 

<h2> Amazon CloudFront Content Delivery Network (CDN) </h2> 

<p> Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users. CloudFront delivers your content through a worldwide network of data centers called edge locations. When a user requests content that you're serving with CloudFront, the request is routed to the edge location that provides the lowest latency (time delay), so that content is delivered with the best possible performance. ( entrega rapida de contenido )  </p> 

<h1> 
  <h2> Regiones  </h2>
  
  <p>     zonas de disponibilidad Se puede decir que estas entrando a la region.
    cada region tiene zonas de disponibilidad normalmente 3 minimo 2 maximo 6
    por ejemplo ap-southeast-2a ap-southeast-2b ap-southeast-2c </p>
  
  
  <h2> AWS Point of Present </h2>
  
  <p>   en que suidades o lugares que esta presente Amazon
  </p>
  
  
  <h2> AWS has Global Services: </h2>
  
  <p> Identity and Access Management (IAM),
Route 53 (DNS service),
CloudFront (Content Delivery Network) and
    WAF (Web Application Firewall) </p>

  <h2> Most AWS services are Region-scoped: </h2>
  
  <p> Amazon EC2 (Infrastructure as a Service),
Elastic Beanstalk (Platform as a Service),
Lambda (Function as a Service) and
    Rekognition (Software as a Service) </p>
  
  
<h2> 
  Edge Locations</h2> 
  
  <p>  Are caching sites to deliver content to end users with lower latency. They are located in Availability Zones. They are not used to deploy infrastructure, but for caching content.
  </p> 
  
  <h2> AWS Identity and Access Management (IAM) </h2>
  
  <p> AWS Identity and Access Management (IAM) provides fine-grained access control across all of AWS. With IAM, you can specify who can access which services and resources, and under which conditions. With IAM policies, you manage permissions to your workforce and systems to ensure least-privilege permissions.</p> 
  
  <h3> IAM Security Tools </h3> 
  <h4> 
    IAM Credentials Report </h4>
  <p>  Lista de usuarios si cuentan con mfa status de las credenciales. </p> 
  
  <h4> IAM Access Advisor </h4> 
  
  <p> Los servicios y que usuario tiene que privilegios y cuando se consumieron y que se consumion </p> 
  
  <h4> What are IAM Policies? </h4>
  
  <p> JSON documents to define Users,Groups or Roles permissions </p> 
  
  <h4> What is a proper definition of IAM Roles? </h4> 
  
  <p> An IAM entity that defines a set of permissions for making AWS service request that will be
    used by AWS services. </p> 
  
  <h2> Amazon EC2 </h2> 


<p> EC2 is a virtual machine that represents a physical server for you to deploy your applications. Instead of purchasing your own hardware and connecting it to a network, Amazon gives you nearly unlimited virtual machines to run your applications while they take care of the hardware. </p> 


<h2> Bootstrapping </h2>

<p> Running scripts or commands only in the first start only once. </p>


<h3>EC2 instance types    </h3>   
<h3>General Purpose       </h3>   
<h3>Compute Optimized     </h3>   
<h3>Memory Optimized      </h3>   
<h3>Accelerated Computing </h3>   
<h3>Storage Optimized     </h3>   


<ol> 
  <p> <strong> For example m5.2xlarge </strong> </p>

<li> m: instance class                      </li>
<li> 5:generations                            </li>   
<li> 2xlarge:size within the instance class  </li>


</ol>

  # Resumen
  
  ##IAM Identity and Access Management
  
  ### Users
  
  Cada usuario de la compañia sera mapeado a un usuario el cual tendra acceso al AWS console con su respectivo password.
  
  ### Groups 
  
  Contienen a los usuarios
  
  ### Policies 
  
  Se representan por archivos JSON. Son los permisos que tendra un grupo de usuarios por ejemplo los developers tendran algunos permisos y los operadores otros pero podemos tener un grupo de auditores el cual contenga un usuario de developers este heredara ambos permisos o policies. Para dar policies a un usuario solamente se llama ***INLINE***
  
  ### IAM Roles
  
  Son permisos que se le van a asignar a una entidad no a un usuario como tal por ejemplo roles a:
  
  1 EC2 Instances
  2 Lambda Function Roles
  3 Roles para CloudFormation
  
  ### Security
  
  MFA factor de doble autenticacion mas password policy
  
  ### AWS CLI AWS SDK 
  
  El primero es para manejar AWS desde la consola(una que esta en el portal) La segunda es para manejar AWS desde un lenguaje de programacion
  
 ### Access Keys 
  
  AccedeAWS usando AWS CLI AWS SDK 
  
  ### Audit
  
  Para auditar nuestros accesos se usa ***Credential Reports & IAM Access Advisor***
  
  ## EC2 Elastic Compute Cloud
  
  ### EC2 Instance
  
  Es una maquina virutal en la nube y se compone de: ***EC2 Instance AMI(OS) + Intance Size(CPU+RAM) + Storage + Security Groups(Firewall) + EC2 User Data ( scripts de inicio par automatizar por ejemplo instalacion de programas).
  
 ### Security Groups
  
  Firewall attached to the EC2 instance
  
 ### SSH 
  
  Puerto 22 ...
  
  ### EC2 Instance Role
  
  Link to IAM roles
  
  ### Puchasing Options OPCIONES de COMPRA
  
Se pueden alquilar diferentes tipos de instancias EC2 dependiendo del uso que se le quiera dar las cuales son:
  
 #### On-Demand Bajo demanda
  
  Se usan para trabajos cortos su costo es predesible. Paga por lo que usaas pagar por segundo despues del primer minuto. No hay plazos
  
  >Con Instancias bajo demanda, pagas la capacidad informática en la segunda , sin compromisos a largo plazo. Tiene control total sobre su ciclo de vida— usted decide cuándo ejecutarlo, detenerlo, hibernarlo, iniciarlo, reiniciarlo o terminarlo.
>Recomendamos que use Instancias bajo demanda para aplicaciones con cargas de trabajo irregulares a corto plazo que no pueden interrumpirse.

>Para ahorros importantes en instancias bajo demanda, utilice los Savings Plans de AWS
, Spot Instances o Reserved Instances.  
  
  
 #### Spot ( Punto lugar etc) El mas barato hasta 90% de descuento

  Short workloads baratas pero poco confiables se pueden perder.
  
  >Una instancia de spot es una instancia que utiliza la capacidad sobrante de EC2 que está disponible por un precio inferior con respecto al precio bajo demanda. Dado que las Instancias de spot permiten solicitar instancias EC2 no utilizadas con grandes descuentos, es posible reducir considerablemente los costos de Amazon EC2. El precio por hora de una instancia de spot se denomina precio de spot. Amazon EC2 establece el precio de spot de cada tipo de instancia en cada zona de disponibilidad, y este fluctúa en función de la oferta y la demanda a largo plazo de las Instancias de spot. Su instancia de spot se ejecuta siempre que haya capacidad disponible y que el precio máximo por hora de su solicitud sea superior al precio de spot.

Las Instancias de spot son una opción económica si es flexible con respecto a cuándo es necesario ejecutar las aplicaciones y si las aplicaciones se pueden interrumpir. Por ejemplo, las Instancias de spot son adecuadas para análisis de datos, trabajos por lotes, procesamiento en segundo plano y tareas opcionales. Para obtener más información, consulte Amazon EC2 Instancias de spot
.
  
 #### Reserved (Standard  + Convertible + Scheduled) barato hasta 75% de descuento
  
 Son instancias ec2 que se resevan por periodos lardos de tiempo hay tres tipos ***Reserved Instances,(long workloads) Convertible Reserved Instances(long workloads with flexible instances osea puedes cambiar el tamaño igual con descuento) y Scheduled Reserved Instances(por ejemplo cada Jueves between 3 and 6PM igual tiene descuento pero se compromete de 1 a 3 años)*** . Mientras mas plazo te comprometas mas descuento hacen ademas si das todo el dinero igual hay descuento. Se reserva un tipo de instancia en especifico no puedes cambiarla. Por ejemplo es ideal para una base de datos.
 
  
#### Dedicated Host
  
 Un server completo fisico 
  
  
#### Dedicated Instnace 
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
