# Spring Boot Actuator with Grafana and Prometheus

## Introduction
The objective of this example is to visualize Spring Boot Actuator Prometheus metrics in Grafana, which are previously dumped into Prometheus.

The Spring Boot application is a simple example of Spring Boot Actuator with all the endpoints enabled within the application.properties file.

## Post

 * SPANISH [Spring Boot Actuator con Grafana y Prometheus](https://refactorizando.com/spring-boot-actuator-prometheus-grafana/)

 * ENGLISH [Spring Boot Actuator with Grafana and Prometheus](https://refactorizando.com/en/spring-boot-actuator-with-prometheus-and-grafana/)

 * SPANISH [Spring Boot Actuator configuración y uso](https://refactorizando.com/spring-boot-actuator-uso-configuracion/)

   
## Configuration

In the **configuration** folder, you have the Docker commands to download Prometheus and Grafana.
In the **configuration** folder, you have the prometheus.yml file required to start Prometheus.

**Prometheus** start at `localhost:9090`
**Grafana** start at localhost:3000.



## How does it run?


git clone https://github.com/refactorizando-web/metrics-prometheus.git

`
mvn spring-boot:run
`

The application start at localhost:8080



[]: https://refactorizando.com/spring-boot-actuator-prometheus-grafana/
