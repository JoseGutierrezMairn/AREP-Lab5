# Taller de Modularización con Virtualización e Introducción a Docker y a AWS
En este taller se realiza un servicio web sencillo donde el objetivo es almacenar un mensaje en una base de datos,   
haciendo uso de contenedores (Docker) y de servicios en la nube como los que nos brinda AWS que en este caso es una máquina virtual  
donde vamos a desplegar nuestro servidor con sus respectivos contenedores para cumplir con el objetivo del laboratorio.

## Prerrequisitos
Debemos tener los siguientes programas instalados o cuentas para poder hacer uso de las herramientas:
~~~
* Maven
* Git
* Java
* CircleCI
* AWS
* MongoDB
* Java IDE de preferencia
~~~

# Instalando 
Para descargar el proyecto realizaremos los siguientes pasos desde el **Simbolo del sistema** o **Command prompt**:  
1. Nos dirigimos a la ubicación donde queremos descargar el proyecto desde el simbolo del sistema.  
2. Escribimos el siguiente comando para realizar la descarga:  
~~~
git clone https://github.com/JoseGutierrezMairn/AREP-Lab5.git
~~~
3. Esperamos a que el simbolo de sistema nos diga que ya se realizó la descarga  
4. El proyecto ya se encuentra en nuestros computadores y está listo para ser editado o probado.  
  
# Documentación
Para compilar el código con maven solo debemos correr el siguiente codigo en el símbolo del sistema ubicado en la raíz del proyecto (Carpeta que contiene el archivo README.md)
`mvn package`

Si queremos ejecutar el programa de manera local, debemos compilar el proyecto con maven y posteriormente ir a nuestro IDE y ejecutar el código fuente.  
Una vez el programa este ejecutandose podemos ir a nuestro navegador de preferencia y escribir en la url la siguiente dirección:  
~~~
`http://localhost:4567/index.html`  
~~~
El resultado debe ser el siguiente:  
![servicioLocal](https://github.com/JoseGutierrezMairn/AREP-Lab5/blob/master/img/servicioLocal.PNG?raw=true)  


# Servicio en la nube  
Como se mencionó en la introducción del taller el objetivo es tener estos servicios funcionando en la nube, en este caso se hizo uso del  
las máquinas virtuales que ofrece AWS en la nube y de docker, para probar el servicio en la nube hay que tener en cuenta que se corre por dos puertos  
y que en este servicio si funciona el uso de la base de datos.
## Puertos
* 8087
* 34000

## Links AWS Service 
* [Aws Service Port: 8087](http://ec2-3-85-141-52.compute-1.amazonaws.com:8087/)  
* [Aws Service Port: 34000](https://powerful-stream-65068.herokuapp.com/)  
### ¿Como funciona?
Para hacer uso del servicio lo primero es entrar a uno de los links del servicio de aws educate el resultado será igual que cuando se corre el codigo  
de manera local.  
 ![AWSService](https://github.com/JoseGutierrezMairn/AREP-Lab5/blob/master/img/AwsService.PNG?raw=true)  
Una vez adentro podemos ingresar cualquier mensaje en el espacio que nos provee el servicio.  
![AWSService](https://github.com/JoseGutierrezMairn/AREP-Lab5/blob/master/img/newMessage.PNG?raw=true)  
Hacer clic en el botón "Save" y recargar la página.
![AWSService](https://github.com/JoseGutierrezMairn/AREP-Lab5/blob/master/img/messageSaved.PNG?raw=true)  

# CircleCI  
[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/JoseGutierrezMairn/AREP-Lab5)  


# Desarrollo  
Construido con:
* [Maven](https://maven.apache.org/)
* [Java](https://www.java.com/es/)
* [CircleCI](https://circleci.com/)
* [MongoDb](https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_americas_colombia_search_brand_atlas_desktop&utm_term=%2Bmongodb%20%2Bdownload&utm_medium=cpc_paid_search&utm_ad=b&utm_ad_campaign_id=2030069987&gclid=CjwKCAiA4rGCBhAQEiwAelVti7jXc13bI8kf9nhTa_LFDAziy4FK4p0VoQXknfzEhyL2rX50XPExERoCN84QAvD_BwE)
* [AWS educate](https://aws.amazon.com/education/awseducate/)
# Autor
* [Jose Gutierrez](https://github.com/JoseGutierrezMairn)