# flow1-NodeRed
Este repositorio contiene el primer ejercicio de NodeRed para el curso Internet de las Cosas de Código IoT

## Introducción

El flow 1 representa el primer ejercicio a realizar con NodeRed. Este ejercicio consiste únicamente en conectar un nodo Inject con un nodo Debug y automatizarlo para que genere un TimeStamp cada 1 segundo. Esta acción permite demostrar el uso de la pestaña Debug.

## Material Necesario

Para realizar este flow necesitas lo siguiente

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [NodeJS](https://nodejs.org/es/)
    - [NPM](https://www.npmjs.com/)
    - [NodeRed](https://nodered.org/docs/getting-started/local)

## Material de referencia

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realiar las configuraciones necesarias

- [Introducción a Docker](https://edu.codigoiot.com/course/view.php?id=996)
- [Introducción a NodeRed](https://edu.codigoiot.com/course/view.php?id=278)

## Instrucciones

### Requisitos previos

Para que este flow funcione, debes cumplir con los siguientes requisitos previos

1. Tener instalado Docker Engine.
2. Tener instalado nodeRed por Docker Compose
3. Tener el contenedor de nodeRed con el volumen de data activado


### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar NodeRed con el comando 

            docker start $(docker ps -a -q)
2. Diregirse al [localhost:1880](localhost:1880)
3. Importar el flow desde el repositorio
4. Hacer clic en el boton Deploy

### Instrucciones de operación

Para observar el resutlado de este flow, sólo es necesario abrir la pestaña Debug.

## Resultados

A continuación puede verse una vista previa del resultado de este flow.


![](https://github.com/RaulRodriguez050221/mi-proyecto/blob/main/flow1img.png?raw=true)


## Evidencias

- [YouTube](https://youtu.be/8U-K6bgMQwE)

# Créditos
Desarrollado por Raul Rodriguez
- [GitHub](https://github.com/RaulRodriguez050221)

Desarrollado por Hugo Escalpelo
- [hugoescalpelo.com](https://hugoescalpelo.com/)
- [Página en Facebook](https://www.facebook.com/Hugo-Escalpelo-Profesional-337708683840136)
- [GitHub](https://github.com/hugoescalpelo)
