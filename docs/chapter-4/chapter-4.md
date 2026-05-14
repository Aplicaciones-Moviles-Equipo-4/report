# Capítulo IV: Product Implementation & Validation

## 4.1. Software Configuration Management

En esta sección se describen las herramientas y configuraciones utilizadas para gestionar el desarrollo del software, incluyendo el entorno de desarrollo, el control de versiones, las convenciones de estilo de código y la configuración del despliegue.

### 4.1.1. Software Development Environment Configuration

En esta sección, se incluirá los productos de software que se usaron en el proyecto.

#### Project Management:

* Trello: Herramienta de gestión de proyectos basada en tableros Kanban. Permite organizar tareas, asignar responsabilidades y hacer seguimiento del progreso del proyecto.

#### Product UX/UI Design:

* Figma: Herramienta de diseño colaborativo para crear prototipos, wireframes y diseños de interfaces de usuario.
* Uxpressia: Plataforma para crear mapas de experiencia de usuario, customer journey maps y user personas.
* Visual Paradigm: Herramienta de modelado UML y diseño de arquitectura de software.

#### Software Development:

* Intellij IDEA: Entorno de desarrollo integrado (IDE) para Java, Kotlin y lenguajes basados en JVM.
* Webstorm: IDE para desarrollo web, soporta HTML, CSS, JavaScript y frameworks modernos.
* GitHub: Plataforma de alojamiento de código fuente y control de versiones utilizando Git.
* Visual Studio Code: Editor utilizado únicamente para la exportación del reporte de formato markdown a PDF.

#### Software Deployment:

* GitHub Pages: Servicio de alojamiento web estático proporcionado por GitHub, ideal para desplegar sitios web y documentación.

### 4.1.2. Source Code Management

Para la gestion del código fuente se utilizó GitHub, una plataforma de alojamiento de código fuente y control de versiones utilizando Git.
Se creó un repositorio en la organización de GitHub, donde se almacenó todo el código fuente del proyecto. 
El repositorio se estructuró de la siguiente manera:

* Organización en Github: [https://github.com/Aplicaciones-Moviles-Equipo-4](https://github.com/Aplicaciones-Moviles-Equipo-4)
* Repositorio de el informe: [https://github.com/Aplicaciones-Moviles-Equipo-4/report](https://github.com/Aplicaciones-Moviles-Equipo-4/report)  
* Repositorio de la Landing Page: [https://github.com/Aplicaciones-Moviles-Equipo-4/eventify-landing-page-realtec](https://github.com/Aplicaciones-Moviles-Equipo-4/eventify-landing-page-realtec)
* Repositorio del Frontend: [https://github.com/Aplicaciones-Moviles-Equipo-4/Frontend](https://github.com/Aplicaciones-Moviles-Equipo-4/Frontend)
* Repositorio del Backend: [https://github.com/Aplicaciones-Moviles-Equipo-4/Backend](https://github.com/WASwarm1/Backend)

### 4.1.3. Source Code Style Guide & Conventions

Se adoptaron las siguientes guías y convenciones de estilo de código para asegurar la calidad y consistencia del código fuente, el idioma estándar para el desarrollo fue el **inglés**.

#### Principios generales:

* **Idioma estándar**: Inglés
* **Legibilidad ante todo**: El código debe ser fácil de leer y entender.
* **Consistencia**: Seguir las mismas convenciones en todo el proyecto.
* **Nombres semánticos**: Utilizar nombres descriptivos para variables, funciones y clases. 
Se usan **sustantivos** para clases y **verbos** para funciones.

#### HTML:

* Archivos HTML deben tener la extensión `.html`.
* Se incluye `alt` en todas las imágenes.
* Usar comillas dobles para atributos.
* Usar etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<footer>`, etc.).

#### CSS:

* Archivos CSS deben tener la extensión `.css`.
* Usar guiones para nombres de clases y IDs (e.g., `.main-header`).
* Se agrupan estilos relacionados y se separan con comentarios.

#### JavaScript:

* Archivos JS deben tener la extensión `.js`.
* Usar camelCase para nombres de variables y funciones.
* Usar `const` y `let` en lugar de `var`.
* Usar funciones flecha y nombres explícitos.
* Los archivos deben tener una unica responsabilidad (Single Responsibility Principle).

#### Java:

* Archivos Java deben tener la extensión `.java`.
* Usar `PascalCase` para nombres de clases, métodos y propiedades.
* Usar `camelCase` para nombres de variables y parámetros.

#### Kotlin:

* Archivos Kotlin deben tener la extensión `.kt`.
* Usar `PascalCase` para nombres de clases, métodos y propiedades.
* Usar `camelCase` para nombres de variables y parámetros.
* Usar Jetpack Compose como kit de desarrollo.
* Usar Material 3.

### 4.1.4. Software Deployment Configuration

En esta sección se describen las configuraciones y herramientas utilizadas para el despliegue del software desarrollado.
El objetivo es asegurar que el proceso de despliegue sea eficiente, automatizado y confiable.

#### Despliegue de la Landing Page:

La **Landing Page** fue desarrollada utilizando tecnologías web estándar como HTML, CSS y JavaScript. Y fue desplegada utilizando **GitHub Pages**, un servicio de alojamiento web estático proporcionado por GitHub.

#### Pasos para el despliegue:

1. **Creación del repositorio**: Se creó un repositorio en la organización de GitHub llamado `Landing-Page`.
2. **Desarrollo del sitio**: El código fuente de la landing page se desarrolló y organizó en el repositorio.
3. **Configuración de GitHub Pages**: En la configuración del repositorio, se habilitó GitHub Pages seleccionando la rama `main` como fuente.
4. **Despliegue automático**: Cada vez que se realiza un push a la rama `main`, GitHub Pages actualiza automáticamente el sitio web.

<div style="page-break-after: always;"></div>

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

<div style="page-break-after: always;"></div>

## 4.3. Validation Interviews

### 4.3.1. Diseño de Entrevistas

A continuación se presentan las preguntas de validación utilizadas para las entrevistas con usuarios. El objetivo es evaluar tanto la landing page como la aplicación móvil de Eventify para asegurar que la experiencia de navegación sea clara, coherente y útil para quienes organizan y gestionan eventos desde sus dispositivos.

**Preguntas sobre la Landing Page**
*   ¿Al ingresar a la landing page, entiendes rápidamente qué es Eventify y a quién está dirigido?
*   ¿La información sobre las funcionalidades de la plataforma te resulta clara y atractiva?
*   ¿El diseño visual (colores, imágenes, tipografías) te transmite confianza y profesionalismo?
*   ¿Consideras que la estructura de la landing page está bien organizada y fácil de navegar?
*   ¿Te motivaría registrarte o saber más sobre Eventify luego de explorar la landing page?

**Preguntas sobre la Aplicación Móvil**
*   ¿Nota coherencia visual y funcional entre las distintas secciones (perfil, eventos, cotizaciones) desde la pantalla de su dispositivo móvil?
*   ¿El proceso de revisión y gestión de las cotizaciones le resulta intuitivo con la interacción táctil?
*   ¿Cómo evalúa la longitud y distribución de la información en las pantallas (ej. mucho *scroll*)?
*   ¿El tablero de tareas (Kanban) le ayuda a organizar su flujo de trabajo? ¿Es fácil cambiar el estado de las tareas?
*   ¿La velocidad de carga y transición entre las pantallas de la aplicación cumple sus expectativas?
*   ¿Qué funcionalidades adicionales agregaría para mejorar la experiencia general al usar la aplicación móvil?

### 4.3.2. Registro de Entrevistas

Para validar la usabilidad y la experiencia de usuario (UX) de la aplicación móvil de Eventify, se realizó una sesión de pruebas con un usuario representativo del público objetivo (perfil de anfitriona/organizadora junior). A continuación, se presenta el registro formal de la entrevista, omitiendo la transcripción coloquial para enfocarnos en los hallazgos técnicos.

**Ficha Técnica del Usuario**
*   **Nombre:** Camila Pérez
*   **Edad:** 25 años
*   **Ocupación:** Estudiante de Negocios Internacionales (USIL).
*   **Rol en la prueba:** Usuario de prueba (Tester UX/UI).
*   **Dispositivo utilizado:** Smartphone Android (Pantalla de 6.1 pulgadas).
*   **Fecha de la sesión:** 13 de mayo de 2026.

**Evidencia de la Entrevista**
A continuación se adjunta la captura de la sesión de validación y el enlace a la grabación correspondiente:

*   **Enlace de la grabación:** [https://tinyurl.com/Entrevista1Camila]

![Captura de la Entrevista con Camila Pérez](../../assets/chapter-4/Entrevista1Camila.png)

**Resumen de Hallazgos y Respuestas Obtenidas**
El usuario interactuó con la versión móvil de Eventify durante 15 minutos, enfocándose en las vistas de Mis Eventos, Estado Financiero (Cotizaciones) y el tablero de Tareas. 

1.  **Impresión visual y coherencia:** La usuaria destacó que la aplicación tiene una apariencia profesional, formal y moderna. Los colores y el diseño le transmitieron la sensación de ser una herramienta de negocios seria, ideal para la organización de eventos corporativos.
2.  **Gestión de Cotizaciones (Navegación y Scroll):** Encontró que las tarjetas de montos y los botones de acción ("Pagar", "Revisar") tienen un tamaño adecuado. Sin embargo, observó que cuando una cotización incluye múltiples servicios, la pantalla exige un exceso de desplazamiento (*scroll*). Sugirió agrupar los gastos por categorías (ej. catering, logística) para compactar la vista.
3.  **Tablero Kanban y Ergonomía Táctil:** Aunque el concepto visual del tablero le resultó muy útil para organizar el flujo de trabajo, reportó dificultades en la interacción táctil. Los botones/flechas para mover una tarea de "Pendiente" a "En progreso" resultaron demasiado pequeños (touch target deficiente), requiriendo varios toques. Sugirió implementar gestos de deslizamiento (*swipe*) para cambiar los estados de manera más natural.
4.  **Funcionalidades adicionales:** Solicitó la inclusión de notificaciones emergentes (*push notifications*) dentro de la app para avisos en tiempo real (ej. cuando se aprueba una cotización). Además, recomendó añadir un botón de contacto directo a WhatsApp en el perfil del organizador para agilizar la comunicación.
5.  **Rendimiento:** Destacó positivamente la velocidad de carga y la fluidez de las transiciones entre pantallas, sin experimentar bloqueos.

### 4.3.3. Evaluaciones según heurísticas

A partir del registro de la entrevista con Camila Pérez, se realizó una evaluación aplicando las Heurísticas de Usabilidad de Jakob Nielsen enfocadas en entornos móviles:

*   **Heurística 8: Diseño estético y minimalista (Aprobado):** La interfaz cumple satisfactoriamente con esta heurística. El usuario percibió un diseño limpio, profesional y sin información irrelevante que compita por su atención.
*   **Heurística 7: Flexibilidad y eficiencia de uso (Oportunidad de Mejora):** La necesidad de hacer un *scroll* excesivo en cotizaciones largas afecta la eficiencia. Se tomará la recomendación del usuario de agrupar los ítems por categorías (Acordeones o *Collapsibles*) para mejorar la navegación de usuarios expertos.
*   **Heurística 4: Consistencia y estándares (Aprobado / Observación táctil):** Aunque visualmente es consistente, el estándar de aplicaciones móviles dicta que las acciones de mover elementos en un tablero (Kanban) se realicen mediante gestos táctiles (*Drag and Drop* o *Swipe*). Los botones direccionales pequeños violan los principios de diseño de interacción táctil (Touch Targets de al menos 48x48 dp), por lo que este componente será rediseñado.
*   **Heurística 1: Visibilidad del estado del sistema (Oportunidad de Mejora):** La falta de notificaciones en tiempo real al aprobarse una cotización deja al usuario sin retroalimentación inmediata si se encuentra en otra pantalla. Se planificará la integración de notificaciones *Push* o *Snackbars* globales.

<div style="page-break-after: always;"></div>

## Conclusiones

### Conclusiones Y Recomendaciones

El desarrollo de los Capítulos I y II ha permitido establecer una base sólida para la comprensión del problema, el contexto de la startup y la definición de la solución propuesta. A través del análisis inicial, se logró identificar claramente la problemática, los antecedentes y los segmentos objetivo, lo cual facilita una orientación estratégica adecuada del producto.

Asimismo, la aplicación del enfoque Lean UX permitió estructurar hipótesis, supuestos y propuestas de valor centradas en el usuario, promoviendo una visión iterativa y validable del desarrollo. En el Capítulo II, el levantamiento de información mediante entrevistas y técnicas de needfinding contribuyó a comprender mejor las necesidades reales de los usuarios, traduciéndose en artefactos clave como user personas, user journeys y empathy maps.

Se recomienda continuar con procesos de validación constante con usuarios reales, de manera que las hipótesis planteadas en Lean UX puedan confirmarse o ajustarse oportunamente. Esto permitirá mejorar la calidad del producto y su adecuación al mercado.

### Video App Validation

### Video About the product

### Video About the team

<div style="page-break-after: always;"></div>

## Glosario

<div style="page-break-after: always;"></div>

## Bibliografia

## Anexos
