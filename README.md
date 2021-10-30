# Notes-AWS

Repositorio de cosas importantes de AWS

<h2> E2C Elastic Compute Cloud </h2>

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

<p> Dockers  en la nube! Amazon ECS makes it easy to deploy, manage, and scale Docker containers running applications, services, and batch processes. Amazon ECS places containers across your cluster based on your resource needs and is integrated with familiar features like Elastic Load Balancing, EC2 security groups, EBS volumes and IAM roles. </p> 

<h2>  Amazon Machine Image (AMI) </h2> 

<p> Una Amazon Machine Image (AMI) proporciona la información necesaria para lanzar una instancia. Debe especificar una AMI al lanzar una instancia. Cuando necesite varias instancias con la misma configuración, puede lanzarlas desde una misma AMI. Cuando necesite instancias con distintas configuraciones, puede usar distintas AMI para lanzarlas.  <p>
  
<h2> ¿Qué diferencia hay entre utilizar el almacén de instancias local y Amazon Elastic Block Storage (Amazon EBS) para el dispositivo raíz? </h2> 

<p> Cuando lanza las instancias de Amazon EC2, tiene la opción de almacenar los datos del dispositivo raíz en Amazon EBS o en el almacén de instancias local. Mediante el uso de Amazon EBS, los datos en el dispositivo raíz persistirán independientemente del ciclo de vida de la instancia. Esto le permite detener y reiniciar la instancia con posterioridad de un modo similar a cuando apaga un portátil y lo enciende cuando lo vuelve a necesitar.

De forma alternativa, el almacén de instancias local solo persiste durante la vida de la instancia. Esta es una forma económica de lanzar instancias en la que los datos no se almacenan en el dispositivo raíz. Por ejemplo, algunos clientes utilizan esta opción para ejecutar sitios web de gran tamaño en los que cada instancia es un clon para gestionar tráfico web. </p>

<h2> Elastic Load Balancing </h2> 

<p> distribuye automáticamente el tráfico entrante entre varios destinos, por ejemplo, instancias EC2, contenedores y direcciones IP en una o varias zonas de disponibilidad. Monitorea el estado de los destinos registrados y enruta el tráfico solamente a destinos en buen estado. Elastic Load Balancing escala el balanceador de carga a medida que el tráfico entrante va cambiando con el tiempo. Puede escalarse automáticamente para adaptarse a la mayoría de las cargas de trabajo. </p>
