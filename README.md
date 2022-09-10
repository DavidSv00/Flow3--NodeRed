# Flow3--NodeRed
Este repositorio contiene el tercer ejercicio realizado con NodeRed.

## Introducción
El flow 3 representa el tercer ejercicio realizado con NodeRed. Este ejercicio se trata en conectar un nodo "Inject" con un nodo "Debug" a traves de un nodo "function" cuyo resultado sera mandado al dashboard. Esta acción permite generar un TimeStamp legible mediante un dashboard.

## Material Necesario
Para realizar este flow se utilizara lo siguiente;

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [NodeJS](https://nodejs.org/es/)
    - [NPM](https://www.npmjs.com/)
    - [NodeRed](https://nodered.org/docs/getting-started/local)

## Material de Referencia

- [Instalar VirtualBox y Ubuntu 20.4](https://www.youtube.com/watch?v=rYkKjmwuot0)
- [Instalacion de NodeRed en ubuntu 20.4](https://www.arubacloud.com/tutorial/how-to-install-node-red-on-ubuntu-20-04.aspx)
- [Introduccion a NodeRed](https://www.codigoiot.com/curso/introduccion-a-node-red/)

## Instrucciones

### Requisitos Previos

Para que este flow funcione, debes cumplir con los siguientes requisitos previos
1. Instalación de NodeJS. Se recomienda tener instalado NodeJS en alguna versión LTS. Al momento de creación de este documento, se usó la versión 16.17.0LTS. Esta instalación debe incluir las Build-Tools para hacer uso de NPM
2. Instalación de NodeRed. La instalación se realiza por NPM. Al momento de la creación de este contenido, se usó la versión 3.0.2

### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar NodeRed con el comando `node-red`
2. Clonar el Flow 2 que hemos creado anteriormente
3. Agregar los nodos node-red-dashboard
4. Mandar el resultado del nodo funcition al dashboard
5. Hacer clic en el boton Deploy
6. Dirigirse al dashboard en http://localhost:1880/ui

### Instrucciones de Operación

Para ver los resultados de nuestro Flow, lo unico que necesitamos hacer es abrir la pestaña "Debug" y nos dirigiremos a la dirección http://localhost:1880/ui/ para poder ver los resultados.

## Resultados
A continuación se muestra una vista previa del resultado de este flow.
![image](https://user-images.githubusercontent.com/111893490/189473878-191cf04b-929d-4888-9718-363449c80ee8.png)
![image](https://user-images.githubusercontent.com/111893490/189473900-0e58b364-509f-4558-ae65-365b1716c900.png)



## Evidencias


## Créditos

Desarrollado por David Sanchez Vazquez
- [GitHub](https://github.com/DavidSv00)
