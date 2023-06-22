# Spring Boot Actuator con Grafana y Prometheus

## Introducción
El objetivo de este ejemplo es poder visualizar en Grafana las métricas de Spring Boot Actuator Prometheus que previamente se vuelcan en Prometheus.

La aplicación Spring Boot es un ejemplo sencillo de Spring Boot Actuator con todos los endpoints activados dentro 
del application.properties.

## Artículos

 * [Spring Boot Actuator con Grafana y Prometheus](https://refactorizando.com/spring-boot-actuator-prometheus-grafana/)

 * ENGLISH [Spring Boot Actuator with Grafana and Prometheus](https://refactorizando.com/en/spring-boot-actuator-with-prometheus-and-grafana/)

 * [Spring Boot Actuator configuración y uso](https://refactorizando.com/spring-boot-actuator-uso-configuracion/)

   
## Configuración

En la carpeta **configuration** se tienen los comandos docker para descargar prometheus y grafana.
En la carpeta **configuration** se tiene el fichero prometheus.yml necesario para arrancar prometheus.

**Prometheus** se arranca en `localhost:9090`
**Grafana** se arrancará en `localhost:3000`

## Cómo arrancar la aplicación


git clone https://github.com/refactorizando-web/metrics-prometheus.git

`
mvn spring-boot:run
`

La aplicación se arráncara en localhost:8080



[]: https://refactorizando.com/spring-boot-actuator-prometheus-grafana/
