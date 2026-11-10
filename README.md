# Richard Grichukin Mendez — Portafolio

Egresado de Ingeniería de Sistemas de la **Universidad Autónoma Gabriel René Moreno**, en proceso de titulación mediante un diplomado en DevSecOps, con la defensa de monografía pendiente.

Estoy construyendo un portafolio de proyectos de desarrollo de software, automatización CI/CD, seguridad, infraestructura cloud y análisis de datos. Busco oportunidades laborales en las que pueda aportar, aprender y continuar creciendo profesionalmente.

Este repositorio es el índice general de mi portafolio. Cada proyecto tendrá su propio repositorio, documentación y evidencias de ejecución.

## Proyectos

El Proyecto 01 ya cuenta con una **primera versión funcional publicada, en desarrollo**. Los proyectos 02 a 07 permanecen planificados; sus alcances son propuestas iniciales. Los repositorios y evidencias se incorporan conforme avanza cada proyecto.

| Proyecto | Alcance | Estado |
| --- | --- | --- |
| [01 · Maestranza ERP — Full Stack](https://github.com/richardgrim/erp-fullstack) | Clientes, órdenes, roles, inventario y resumen operativo para un taller. | Primera versión funcional · En desarrollo |
| 02 · Aplicación Full Stack | Aplicación web centrada en resolver una necesidad concreta, con frontend, backend y base de datos. | Planificado |
| 03 · Arquitectura de Microservicios | Servicios independientes, comunicación entre componentes y documentación de la arquitectura. | Planificado |
| 04 · Data Analytics / Business Intelligence | Preparación y análisis de datos, indicadores y visualización de resultados. | Planificado |
| 05 · DevSecOps CI/CD | Automatización de integración, pruebas, controles de seguridad y entrega de una aplicación. | Planificado |
| 06 · Infraestructura Cloud AWS con Terraform | Infraestructura como código, gestión de accesos y documentación de despliegue y eliminación de recursos. | Planificado |
| 07 · Aplicación móvil | Aplicación móvil con un caso de uso definido y documentación de ejecución y pruebas. | Planificado |

## Proyecto destacado: Maestranza ERP

Aplicación para organizar la recepción y seguimiento de trabajos de una maestranza y controlar el consumo de materiales por orden. Proyecto de demostración con datos ficticios y ejecución local.

**Tecnologías:** Angular 21, Java 21, Spring Boot, Spring Security, PostgreSQL 17, Flyway, Docker Compose y GitHub Actions.

- Registro de clientes y órdenes; seguimiento desde pendiente hasta entregada, con historial de cambios.
- Inicio de sesión y permisos diferenciados de administrador y operador.
- Entradas de materiales y consumos asociados a órdenes en proceso, con control de stock y autoría de movimientos.
- Resumen de órdenes por estado, búsqueda y filtros por fecha de creación.
- 33 pruebas automatizadas (17 del servidor y 16 de interfaz); primera ejecución de CI aprobada con compilaciones e informes disponibles.

[Repositorio](https://github.com/richardgrim/erp-fullstack) · [Arquitectura](https://github.com/richardgrim/erp-fullstack/blob/main/docs/architecture.md) · [Ejecución local](https://github.com/richardgrim/erp-fullstack/blob/main/docs/runbook.md) · [Evidencias](https://github.com/richardgrim/erp-fullstack/tree/main/evidence) · [CI aprobado](https://github.com/richardgrim/erp-fullstack/actions/runs/42743654992)

**Estado y límites:** primera versión funcional en desarrollo; no es un sistema productivo ni una aplicación desplegada públicamente. No incluye facturación ni valoración económica del inventario. Código disponible bajo [licencia MIT](https://github.com/richardgrim/erp-fullstack/blob/main/LICENSE).

## Práctica técnica y formación

### Laboratorio CI/CD

[Ver repositorio ci-cd-labs](https://github.com/richardgrim/ci-cd-labs)

Repositorio académico y técnico utilizado para practicar integración y despliegue continuo:

- Integración continua con GitHub Actions y Azure Pipelines.
- Compilación y pruebas de una aplicación Java con Maven.
- Publicación de artefactos y despliegue en Docker local mediante un agente propio de Azure Pipelines.
- Verificaciones HTTP con Postman/Newman y publicación de resultados de pruebas.
- Comprobación de salud y recuperación de la versión anterior ante un fallo de despliegue.

Este laboratorio se mantiene separado de los siete proyectos del portafolio.

## Tecnologías y áreas de desarrollo

**Utilizadas en Maestranza ERP:** Angular, TypeScript, Java, Spring Boot, Spring Security, PostgreSQL, Flyway y GitHub Actions.

**Utilizadas en los laboratorios:** Git, GitHub, GitHub Actions, Azure DevOps, Azure Pipelines, Docker, Java, Maven, PowerShell y Postman/Newman.

**Áreas previstas para los próximos proyectos:** desarrollo full stack, microservicios, DevSecOps, análisis de datos y Business Intelligence, AWS, Terraform y desarrollo móvil. Las tecnologías específicas se definirán para cada proyecto según su alcance.

## Documentación de cada proyecto

Cada repositorio incorporará progresivamente:

- Objetivo, problema que resuelve y alcance.
- Arquitectura y decisiones técnicas.
- Tecnologías y requisitos de ejecución.
- Instrucciones de instalación, configuración y uso.
- Pruebas, capturas o evidencias de funcionamiento.
- CI/CD y controles de seguridad cuando correspondan.
- Limitaciones conocidas y próximos pasos.

## Contacto

- **GitHub:** [richardgrim](https://github.com/richardgrim)
- **Disponibilidad:** abierto a oportunidades laborales.

Los enlaces a LinkedIn y al currículum se incorporarán cuando estén preparados para su publicación.
