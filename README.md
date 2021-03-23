# BVL - ConectorTRKDStreaming

_Conexión WebSocket al módulo de RKD Streaming para obtener las actualizaciones de las emisoras tic by tic_

## Comenzando 

_Instrucciones para descargar el código de forma local y empezar con el desarrollo._

```
- git clone https://github.com/IsanchezFS/example-readme.git
- git checkout develop && git pull origin develop
- git checkout -b feature_module
```


Mira **Deployment** para conocer como desplegar el proyecto en los ambientes de AWS.


### Pre-requisitos 

_Necesitas el siguiente software recomendado para trabajar este proyecto_

```
- Eclipse https://www.eclipse.org/downloads/packages/release/2021-03/r/eclipse-ide-java-developers
- Mave https://maven.apache.org/guides/getting-started/windows-prerequisites.html
- Redis (Almacenamiento de info)
- Mysql (Obtención de instrumentos a consultar)
```

<!-- ### Instalación 

_Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutandose_

_Dí cómo será ese paso_

```
Da un ejemplo
```

_Y repite_

```
hasta finalizar
```

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_ -->

<!-- ## Ejecutando las pruebas 

_Explica como ejecutar las pruebas automatizadas para este sistema_

### Analice las pruebas end-to-end 

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación 

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
``` -->

## Despliegue 

_Para el compilado de ConectorTRKDStreaming_

```
- Raiz del proyecto ejecutar mvn clean Install
- Generará un artifact ConectorTRKDStreaming-jar-with-dependencies.jar
- Copiar artifact y el settings.properties del proyecto al s3 deseado.
```

## Construido con 

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Maven](https://maven.apache.org/) - Manejador de dependencias
 
## Autores 

_Desarrolladores activos_

* **isanchez@financialsolutions.mx**
* **menriquez@financialsolutions.mx** 
* **ivazquez@financialsolutions.mx** 

---
Financial Solutions LTS 
