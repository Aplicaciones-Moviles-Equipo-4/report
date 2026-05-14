# Capítulo IV: Product Implementation & Validation

## 4.1. Software Configuration Management

Con el fin de garantizar la consistencia, trazabilidad y calidad a lo largo del ciclo de vida de Eventify, el equipo ha definido un conjunto de decisiones y convenciones orientadas a la gestión de configuraciones. Esta sección describe los mecanismos adoptados para controlar el código fuente, configurar los entornos de desarrollo y definir el proceso de despliegue de la aplicación móvil y la landing page.

Estas prácticas permiten asegurar que las versiones del software se mantengan estables, que el trabajo colaborativo sea eficiente y que las implementaciones sean controladas y reproducibles.

### 4.1.1. Software Development Environment Configuration

Para asegurar una colaboración eficiente y mantener la calidad en el desarrollo móvil de Eventify, se ha definido un entorno de desarrollo común para todos los miembros del equipo. A continuación, se listan los productos de software utilizados, indicando su propósito y su enlace de referencia o descarga correspondiente.

**Product UX/UI Design**
Para el diseño de la experiencia de usuario y la interfaz de la aplicación móvil y Landing page, se utilizaron las siguientes herramientas:
- **Figma:** Se empleó para la creación de wireframes, mock-ups y prototipos interactivos de la aplicación móvil. [https://www.figma.com/](https://www.figma.com/)
- **UXPressia:** Utilizada para elaborar User Personas, Empathy Maps, Journey Maps e Impact Maps. [https://uxpressia.com/](https://uxpressia.com/)
- **Miro:** Se utilizó para la creación de los mapas de escenarios As-Is y To-Be. [https://miro.com/es/](https://miro.com/es/)

**Software Development**
Para el desarrollo del software móvil, se adoptaron los siguientes productos:
- **Android Studio (Instalación local):** Entorno de desarrollo integrado (IDE) oficial utilizado para programar la aplicación móvil utilizando Kotlin y Jetpack Compose. [https://developer.android.com/studio](https://developer.android.com/studio)
- **Git (Instalación local):** Empleado para gestionar los cambios de código de manera local mediante commits y ramas. [https://git-scm.com/](https://git-scm.com/)
- **GitHub:** Plataforma de repositorio remoto para la gestión de versiones del código, implementando el flujo GitFlow para garantizar un desarrollo organizado. [https://github.com/](https://github.com/)

**Project Management and Collaboration**
En la gestión de proyectos y colaboración del equipo se utilizaron:
- **Trello:** Utilizado para la planificación y seguimiento de tareas, distribuidas en listas de "por hacer", "en progreso" y "hecho".
- **WhatsApp:** Medio de comunicación instantánea para coordinar avances, resolver dudas rápidas y hacer recordatorios. [https://web.whatsapp.com/](https://web.whatsapp.com/)
- **Discord:** Utilizado como plataforma de comunicación por voz y chat, facilitando reuniones rápidas y discusiones técnicas. [https://discord.com/](https://discord.com/)
- **Zoom:** Herramienta utilizada para realizar reuniones virtuales formales, presentaciones de avances y coordinación general. [https://www.zoom.com/es](https://www.zoom.com/es)

**Software Documentation**
Para la documentación de la arquitectura y datos se emplearon:
- **Vertabelo:** Herramienta utilizada para el diseño y documentación de bases de datos. [https://vertabelo.com/](https://vertabelo.com/)
- **PlantUML Editor:** Utilizada para la creación del diagrama de clases. [https://plantuml.com/](https://plantuml.com/)
- **Structurizr:** Herramienta usada para modelar la arquitectura de software mediante diagramas C4. [https://structurizr.com/](https://structurizr.com/)

### 4.1.2. Source Code Management

La gestión del código fuente es fundamental en el desarrollo colaborativo. Se describe el sistema de control de versiones implementado utilizando GitHub, detallando el modelo GitFlow y las convenciones de commit mediante Conventional Commits.

**Estructura de Ramas:**
Para mantener un flujo organizado, se ha implementado el modelo GitFlow:
- **Main / Master Branch:** Rama principal que contiene las versiones estables de la aplicación móvil.
- **Develop:** Rama secundaria donde se integran todas las características nuevas antes de fusionarse a la rama main.
- **Feature Branches:** Ramas dedicadas a cada funcionalidad del proyecto móvil (ej. `feature/cotizaciones_negociaciones`, `feature/gestion_eventos`).
- **Release Branches:** Ramas creadas cuando `develop` está lista para ser convertida en una nueva versión estable (APK/AAB).

**Convenciones de commits (Conventional Commits):**
Formato estándar para facilitar la lectura del historial de cambios:
```text
<type>[optional scope]: <description>

[optional body]

### 4.1.3. Source Code Style Guide & Conventions

### 4.1.4. Software Deployment Configuration

## 4.2. Landing Page & Mobile Application Implementation

### 4.2.1. Sprint n

#### 4.2.1.1. Sprint Planning n

#### 4.2.1.2. Sprint Backlog n

#### 4.2.1.3. Development Evidence for Sprint Review

#### 4.2.1.4. Testing Suite Evidence for Sprint Review

#### 4.2.1.5. Execution Evidence for Sprint Review

#### 4.2.1.6. Services Documentation Evidence for Sprint Review

#### 4.2.1.7. Software Deployment Evidence for Sprint Review

#### 4.2.1.8. Team Collaboration Insights during Sprint

## 4.3. Validation Interviews

### 4.3.1. Diseño de Entrevistas

### 4.3.2. Registro de Entrevistas

### 4.3.3. Evaluaciones según heurísticas

## Conclusiones

### Conclusiones Y Recomendaciones

### Video App Validation

### Video Abput the product

### Video About the team

## Glosario

## Bibliografia

## Anexos
