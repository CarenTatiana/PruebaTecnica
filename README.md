# PruebaTecnica
Tarjeta Credito
Es un crud, apoyado en lenguaje java 1.8, que contiene cuatro servicios de tipo REST
enlazado a una base de datos en el entorno de POSTGRES

Comenzando 🚀

Mira Deployment para conocer como desplegar el proyecto.

# Pre-requisitos 📋

# Instalación 🔧
Es necesario contar con la version de Angular 13.2
para lo cual hay que ejecutar el comando npm i @angular/cli 
luego de ello, es primordial crear o ejecutar el sript de la base de datos 
en el entorno para esta que es Postgrest, el cual se encontrara casi al final 
del documento. 
Luego de esto es necesario crear las tablas, sin embargo el Hibernate, de la mano 
del JPA, utilizados en el desarrollo del BACK y creacion de servicios, se encarga de esto, 
solo basta ejecutarlo. 

Ahora bien, por el encriptamiento que se debe realizar al numero de la tarjeta de credito 
se debe realizar a traves de pgCrypto, junto con el tipo que es 'AES_KEY'
el Query se encontrara anexo en este mismo. 

En cuanto a la parte Front, esta dividida en servicio y ejecutables. 


# Construido con 🛠️
Menciona las herramientas que utilizaste para crear tu proyecto

Dropwizard - El framework web usado 
Maven - Manejador de dependencias


CREACION BASE DE DATOS 
CREATE DATABASE "TarjeCredito"
    WITH 
    OWNER = postgres
    ENCODING = 'UTF8'
    LC_COLLATE = 'Spanish_Colombia.1252'
    LC_CTYPE = 'Spanish_Colombia.1252'
    TABLESPACE = pg_default
    CONNECTION LIMIT = -1;



# Autores ✒️


Caren Tatiana Rodriguez- Trabajo Inicial 
Caren Tatiana Rodriguez - Documentación 


# Licencia 📄
Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo LICENSE.md para detalles

Expresiones de Gratitud 🎁

 gracias 🤓.
etc.
