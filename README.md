# Examen Final Arquitectura de Computadores

## Objetivo

Este proyecto tiene como objetivo crear y desplegar una infraestructura en AWS utilizando CloudFormation y GitHub Actions.

La aplicación permite crear una máquina virtual EC2 automáticamente y publicar una página web mediante un despliegue automatizado.


## Tecnologías utilizadas

- AWS EC2
- AWS CloudFormation
- GitHub Actions
- Git


## Deploy

El workflow de Deploy permite validar el template de CloudFormation y crear automáticamente:

- Una instancia EC2 Amazon Linux.
- Un Security Group con acceso por el puerto 80.
- Una página web ejecutada mediante UserData.


## Destroy

El workflow de Destroy permite eliminar el stack creado en AWS y borrar los recursos utilizados para evitar costos adicionales.


## Template EC2

El archivo ec2.yaml contiene la configuración necesaria para crear la infraestructura en AWS y desplegar la página web automáticamente.