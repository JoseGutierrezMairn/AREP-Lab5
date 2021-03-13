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
`git clone https://github.com/JoseGutierrezMairn/AREP-Lab5.git`
3. Esperamos a que el simbolo de sistema nos diga que ya se realizó la descarga  
4. El proyecto ya se encuentra en nuestros computadores y está listo para ser editado o probado.  
  
# Documentación
Para compilar el código con maven solo debemos correr el siguiente codigo en el símbolo del sistema ubicado en la raíz del proyecto (Carpeta que contiene el archivo README.md)
`mvn package`

Si queremos ejecutar el programa de manera local, debemos compilar el proyecto con maven y posteriormente ir a nuestro IDE y ejecutar el código fuente.  
Una vez el programa este ejecutandose podemos ir a nuestro navegador de preferencia y escribir en la url la siguiente dirección:
`http://localhost:4567/index.html`
El resultado debe ser el siguiente:
![servicioLocal](https://github.com/JoseGutierrezMairn/AREP-Lab5/blob/master/img/servicioLocal.PNG?raw=true)  


# Heroku  
Para probar el programa desplegado en heroku  
seguir el siguiente link:  
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://powerful-stream-65068.herokuapp.com/)  
[Rusia 2018 - Jose Gutierrez Marin](https://powerful-stream-65068.herokuapp.com/)  

# CircleCI  
[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/JoseGutierrezMairn/Lab3-Arep)  


# Desarrollo  
Construido con:
* [Maven](https://maven.apache.org/)
* [Java](https://www.java.com/es/)
* [CircleCI](https://circleci.com/)
* [Heroku](https://dashboard.heroku.com/)
* [DBeaver](https://dbeaver.io/)
# Autor
* [Jose Gutierrez](https://github.com/JoseGutierrezMairn)