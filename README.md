# sistema-Yair-Mauricio-Macgrego-perez-Cristian-Osorio-Mujica-devops

## Descripción
Sistema educativo distribuido en microservicios: usuarios, asignaturas y matrículas. Cada microservicio es independiente, comunicándose vía Feign y protegido con JWT.

## Microservicios
- usuarios-servicio: gestiona usuarios y autenticación.
- asignaturas-servicio: gestiona asignaturas.
- matriculas-servicio: gestiona el proceso de matrícula.

## Arquitectura
- Microservicios independientes (Spring Boot + WebFlux)
- Comunicación via Feign + Eureka
- Configuración centralizada (Spring Cloud Config)
- Seguridad JWT
- CI/CD con GitHub Actions
- Despliegue con Docker Compose
- Monitoreo con Prometheus y Grafana
