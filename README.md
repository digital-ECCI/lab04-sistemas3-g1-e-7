[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/0V8i2zWk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23618644&assignment_repo_type=AssignmentRepo)
# Lab04: Visualización de Datos en Raspberry Pi con Node-RED 

## Integrantes

### Juan Barragan-
### Julian Montaño
### Jesus Bojaca

## Documentación

El desarrollo del taller consistió en instalar y configurar Node-RED sobre una Raspberry Pi utilizando una conexión remota por SSH.

Inicialmente se realizó la conexión desde la terminal del computador hacia la Raspberry Pi mediante el protocolo SSH, evitando el uso de entornos gráficos remotos debido al mayor consumo de memoria y procesador. Una vez establecida la conexión, se ejecutó el script oficial de instalación de Node-RED, el cual instaló automáticamente:


Node.js

npm

Node-RED

Nodos específicos para Raspberry Pi

Posteriormente se verificó el funcionamiento de Node-RED ejecutándolo manualmente con el comando:


node-red-pi --max-old-space-size=256

Dentro de la interfaz se instaló el complemento Dashboard, el cual permite crear interfaces gráficas interactivas para el usuario.

Para la implementación del flujo se utilizaron los siguientes nodos:

-color picker

-text input

-function

-debug

-write file

## Conclusiones
-Se logró instalar y configurar correctamente Node-RED en la Raspberry Pi, comprobando que puede ejecutarse tanto manualmente como automáticamente al iniciar el sistema. 

-El uso de una conexión SSH desde la terminal resultó más eficiente que trabajar mediante entornos remotos gráficos, ya que redujo el consumo de recursos durante la instalación.

-El Dashboard de Node-RED facilitó la creación de una interfaz gráfica sencilla sin necesidad de programar páginas web manualmente.

-El flujo implementado permitió comprender la lógica de conexión 
entre nodos y el procesamiento de mensajes dentro de Node-RED.

-Los nodos debug y write file fueron útiles para verificar el correcto funcionamiento del flujo y almacenar la información generada.
