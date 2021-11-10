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
