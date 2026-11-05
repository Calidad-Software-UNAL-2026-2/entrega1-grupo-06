# Mapa de Procesos de FinAnalyze

> Generado mediante el workflow de flujo único.
> Los procesos se ejecutan secuencialmente dentro de cada incremento.
> El modelo de ciclo de vida se describe formalmente en la Wiki,
> página `04c-Modelo-Ciclo-Vida`.

## Proceso: Análisis y definición de requisitos

- **Entradas:** Modelo verbal extendido, necesidades del negocio, necesidades de los interesados y actores identificados
- **Actividades:** Identificación, análisis, especificación, priorización y organización de requisitos funcionales y no funcionales
- **Salidas:** Requisitos documentados, módulos identificados y criterios de aceptación
- **Recursos:** Equipo del proyecto, BABOK v3 como referencia, GitHub Issues, GitHub Projects y GitHub Wiki

## Proceso: Diseño de arquitectura y componentes

- **Entradas:** Requisitos funcionales y no funcionales, módulos identificados y restricciones técnicas
- **Actividades:** Definición de la arquitectura, diseño de la base de datos, separación del frontend y backend y especificación de interfaces de comunicación
- **Salidas:** Diseño de arquitectura, modelo de datos y especificación de interfaces
- **Recursos:** Equipo de desarrollo, Python, JavaScript, D3.js, SQL y herramientas de documentación

## Proceso: Implementación del backend

- **Entradas:** Requisitos del sistema, diseño de arquitectura, modelo de datos y especificación de interfaces
- **Actividades:** Implementación de la lógica de negocio, desarrollo de servicios y API, conexión con la base de datos e implementación de funcionalidades financieras
- **Salidas:** Código fuente del backend, servicios implementados, API disponibles y documentación técnica
- **Recursos:** Equipo de desarrollo, Python, SQL, Git, GitHub y entorno de ejecución

## Proceso: Pruebas del backend

- **Entradas:** Código fuente del backend, requisitos funcionales, criterios de aceptación y servicios implementados
- **Actividades:** Diseño y ejecución de pruebas, verificación de cálculos financieros, validación de API, identificación y corrección de defectos
- **Salidas:** Resultados de pruebas, defectos registrados y servicios del backend verificados
- **Recursos:** Equipo de desarrollo, herramientas de pruebas, entorno de ejecución y GitHub Issues

## Proceso: Implementación del frontend

- **Entradas:** Requisitos de interfaz, diseño de arquitectura, especificación de las API y servicios del backend verificados
- **Actividades:** Construcción de interfaces, desarrollo de formularios y dashboards, implementación de gráficos y consumo de servicios del backend
- **Salidas:** Código fuente del frontend, interfaces implementadas y componentes visuales
- **Recursos:** Equipo de desarrollo, JavaScript, D3.js, documentación de API, Git y GitHub

## Proceso: Integración y pruebas del sistema

- **Entradas:** Backend verificado, frontend implementado, interfaces de comunicación y requisitos del sistema
- **Actividades:** Integración de componentes, configuración de conexiones, ejecución de pruebas de integración y sistema, validación de requisitos y corrección de defectos
- **Salidas:** Sistema integrado, resultados de pruebas, defectos corregidos y versión candidata para entrega
- **Recursos:** Equipo de desarrollo, entorno de pruebas, herramientas de integración, GitHub y documentación del sistema

## Proceso: Despliegue y transición

- **Entradas:** Sistema integrado y verificado, versión candidata, documentación técnica y configuración del entorno de ejecución
- **Actividades:** Preparación del entorno, configuración de la aplicación, publicación de la versión aprobada, verificación del funcionamiento y entrega de documentación
- **Salidas:** Versión desplegada de FinAnalyze, documentación de instalación y utilización y registro de entrega
- **Recursos:** Equipo de desarrollo, repositorio GitHub, entorno de despliegue, documentación técnica y herramientas de configuración

