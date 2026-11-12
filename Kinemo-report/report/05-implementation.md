## Capítulo V: Product Implementation, Validation & Deployment

### 5.1 Software Configuration Management

#### 5.1.1 Software Development Environment Configuration


A continuación se detallan las herramientas y plataformas utilizadas durante el desarrollo de Kinemo, según la documentación del equipo y la configuración de sus proyectos.

| Producto | Propósito | Tipo de actividad | Ruta de referencia |
|---|---|---|---|
| UXPressia | Elaboración de User Personas, Empathy Maps, User Journey Maps, User Task Matrix e Impact Maps | Requirements Management | https://uxpressia.com/w/v8FzI |
| Figma | Diseño de Wireframes, Mock-ups y Prototipos del Landing Page y Web Application | UX/UI Design | https://www.figma.com/design/h8gZ1ryldnlq3f485Vx13T/Landing-Page |
| Figma (Mock-up) | Mock-ups de alta fidelidad del Landing Page | UX/UI Design | https://www.figma.com/design/2kl9zH6WgBNDCJAPYMhC0v/Landing-Page-Mock-up |
| FigJam | Elaboración de Wireflows y User Flows | UX/UI Design | https://www.figma.com/figjam/ |
| Miro | Sesiones de Big Picture EventStorming y Design-Level EventStorming | Domain Modeling | https://miro.com/app/board/uXjVHm4VBp8= |
| LucidChart | Diagramas de arquitectura de software (C4 Model) y diagramas de clases UML | Software Architecture | https://www.lucidchart.com/ |
| Structurizr | Diagramas C4 Model como código (opcional) | Software Architecture | https://structurizr.com/ |
| PlantUML | Diagramas UML y de base de datos como código | Software Architecture | https://plantuml.com/ |
| GitHub | Almacenamiento y control de versiones del código fuente y del Project Report | Version Control | https://github.com/kinemo-cinema |
| Git | Sistema de control de versiones distribuido | Version Control | https://git-scm.com/ |
| WebStorm / Visual Studio Code | Desarrollo y mantenimiento de la aplicación Vue y documentación | Software Development | https://www.jetbrains.com/webstorm/ |
| JetBrains Rider | Desarrollo y mantenimiento del RESTful API en ASP.NET Core | Software Development | https://www.jetbrains.com/rider/ |
| Node.js + npm | Entorno de ejecución y gestor de paquetes para el frontend (Vue) | Software Development | https://nodejs.org/ |
| Vite | Servidor de desarrollo y compilación de la Web Application | Software Development | https://vite.dev/ |
| PrimeVue | Biblioteca de componentes UI para la Web Application | Software Development | https://primevue.org/ |
| .NET SDK 10 | Plataforma utilizada en el backend actual | Software Development | https://dotnet.microsoft.com/ |
| OpenAPI / Scalar | Especificación y visualización de la documentación del RESTful API; verificar ruta disponible | Documentation | https://scalar.com/ |
| Trello | Gestión del Product Backlog y Sprint Backlog | Project Management | https://trello.com/b/6ac2a2ced29ee515df2506f0 |
| Microsoft Stream | Publicación de videos de exposición, Needfinding y validación | Documentation | https://stream.microsoft.com/ |
| Clipchamp | Edición de videos de exposición y evidencias | Documentation | https://clipchamp.com/ |
| GitHub Pages | Despliegue del Landing Page | Deployment | https://pages.github.com/ |

#### 5.1.2 Source Code Management

El proyecto Kinemo gestiona su código fuente mediante **GitHub**, bajo la organización pública `kinemo-cinema`, con un repositorio independiente por cada producto de software.

| Producto | Repositorio |
|---|---|
| Landing Page | https://github.com/kinemo-cinema/landing-page-kinemo |
| Frontend Web Application | https://github.com/kinemo-cinema/kinemo-cinema-frontend |
| RESTful API (Web Services) | https://github.com/kinemo-cinema/kinemo-platform |
| Project Report | https://github.com/kinemo-cinema/kinemo-cinema-report |

**Workflow: GitFlow**

El equipo aplica **GitFlow** como modelo de ramificación, compuesto por:

- **main**: rama principal, contiene únicamente versiones estables y desplegadas (*release-ready*).
- **develop**: rama de integración continua, base para el desarrollo activo de *features*.
- **feature/&lt;nombre-descriptivo&gt;**: una rama por cada funcionalidad, creada a partir de `develop` y fusionada de vuelta a `develop` al completarse. Ejemplos usados por el equipo: `feature/landing-hero-section`, `feature/landing-contact-form`.
- **hotfix/&lt;nombre-descriptivo&gt;**: para correcciones urgentes sobre `main`.

**Convención de nombres de feature branches:**

`feature/<kebab-case-descriptivo-de-la-tarea>`, alineado con el título de la *Task* correspondiente en el Sprint Backlog.

**Semantic Versioning:**

Los *Releases* siguen el formato `MAJOR.MINOR.PATCH` (ej. `1.0.0` para el primer release del Landing Page en AV1).

**Conventional Commits:**

Todos los mensajes de commit siguen el formato `<tipo>(<alcance opcional>): <descripción>`, usando tipos como `feat`, `fix`, `docs`, `style`, `refactor`, `test` y `chore`.

Ejemplos:
- `feat(landing): add hero section with two-column layout`
- `fix(landing): correct broken link in pricing section`
- `docs(readme): update chapter 5 with sprint 1 evidence`

#### 5.1.3 Source Code Style Guide & Coding Conventions

El equipo adopta nomenclatura en inglés para todos los elementos de código, en los siguientes lenguajes y bajo las siguientes referencias:

- **HTML/CSS**: Google HTML/CSS Style Guide.
- **JavaScript**: Google JavaScript Style Guide y MDN JavaScript Guidelines.
- **Vue**: Vue Style Guide (oficial).
- **C# / ASP.NET Core**: Microsoft C# Coding Conventions y ASP.NET Core Engineering Guidelines.
- **Gherkin** (usado en los Acceptance Criteria del Capítulo III): Gherkin Conventions for Readable Specifications.

**Convenciones específicas del equipo:**

- Componentes Vue en `PascalCase` (`HeroSection.vue`, `ContactForm.vue`).
- Variables y funciones en `camelCase`; constantes en `UPPER_SNAKE_CASE`.
- Clases C# en `PascalCase`; parámetros y variables locales en `camelCase`, siguiendo las convenciones de Microsoft.
- No se permiten mutaciones de términos técnicos en español (ej. no usar "deployar", "testear"; usar "deploy", "test" en su forma original en inglés).

#### 5.1.4 Software Deployment Configuration

Para el despliegue de los productos de software de Kinemo se definió la siguiente configuración:

**Landing Page — GitHub Pages**

El Landing Page, desarrollado con HTML5, CSS3 y JavaScript puro, se despliega mediante **GitHub Pages** a partir de la rama `main` del repositorio `landing-page-Kinemo`. Los pasos realizados son:

1. Acceder al repositorio en GitHub y dirigirse a **Settings → Pages**.
2. En **Source**, seleccionar la rama `main` y la carpeta `/ (root)`.
3. Guardar los cambios; GitHub genera automáticamente la URL pública `https://kinemo-cinema.github.io/landing-page-Kinemo/`.
4. Verificar el despliegue accediendo a la URL y comprobando que el contenido del Landing Page carga correctamente.

Para la Web Application y el RESTful API se contempla un despliegue independiente. El proveedor, las URLs públicas y la disponibilidad efectiva deben acreditarse con evidencias de ejecución; no se consideran confirmados en este documento.

### 5.2 Landing Page, Services & Applications Implementation

#### 5.2.1 Sprint 1 (AV1)

##### 5.2.1.1 Sprint Planning 1

| Sprint # | Sprint 1 |
|---|---|
| Date | 2026-08-24 |
| Time | 08:00 PM |
| Location | Reunión virtual vía Discord |
| Prepared By | Llamozas Diaz, Edson Diego |
| Attendees | Llamozas Diaz, Edson Diego / Flores Chavez, Fabricio / Huamanchumo Chicchon, Felipe Marcelo / Trigoso Garrido, Cristian Joseph / Correa Rodriguez, Andrea Khristina |
| Sprint n-1 Review Summary | No aplica — este es el primer Sprint del proyecto. |
| Sprint n-1 Retrospective Summary | No aplica — este es el primer Sprint del proyecto. |
| Sprint 1 Goal | Nuestro objetivo es lanzar la página de destino B2B de Kinemo. Creemos que ofrece a los posibles gestores de cadenas de cines una forma clara y autónoma de conocer la oferta e iniciar una conversación comercial. Esto quedará confirmado cuando los visitantes puedan consultar la propuesta de valor y los precios, y enviar una solicitud de demostración o de presupuesto en menos de tres pasos. |
| Sprint 1 Velocity | 12 Story Points |
| Sum of Story Points | 12 Story Points |


##### 5.2.1.2 Aspect Leaders and Collaborators

La siguiente tabla muestra la asignación de líderes (L) y colaboradores (C) por cada aspecto del Landing Page durante el Sprint 1. Esta organización se alinea con la selección de tareas del Sprint Backlog y con la evidencia de commits registrada en GitHub.

| Team Member | GitHub Username | Hero Section | Platform Section | Pricing Section | Team Section | Contact Form | Repo & Deployment |
|---|---|---|---|---|---|---|-------------------|
| Llamozas Diaz, Edson Diego | DiegoLlamozas | C | C | C | C | C | C                 |
| Huamanchumo Chicchon, Felipe Marcelo | Daiko-07 | L | L | L | L | L | C                 |
| Correa Rodriguez, Andrea Khristina | Elmiau2341 | C | C | C | C | C | C                 |
| Trigoso Garrido, Cristian Joseph | Crzzz30 | C | C | C | C | C | C                 |
| Flores Chavez, Fabricio | Ferdwar | C | C | C | C | C | C                 |


##### 5.2.1.3 Sprint Backlog 1

El Sprint Backlog 1 comprende las User Stories del Landing Page (US28, US29, US30, US31 y US32) priorizadas en el Product Backlog, descompuestas en tareas técnicas. La asignación de tareas refleja la evidencia de commits registrada en el repositorio `landing-page-kinemo`.

| Sprint # | Sprint 1 |
|---|---|
| **User Story** | **Work-Item / Task** | | | | |
| **Story ID** | **Story Title** | **Task ID** | **Task Title** | **Task Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| US28 | Conocer beneficios de la solución | T01 | Maquetar Hero Section | Implementar la sección Hero con titular, subtítulo, CTAs y placeholder de imagen hero. | 6 | Huamanchumo Chicchon, Felipe Marcelo | Done |
| US29 | Conocer características de la solución | T02 | Maquetar Platform Section | Implementar la sección Platform con bloques interactivos de características y placeholders de imagen. | 8 | Huamanchumo Chicchon, Felipe Marcelo | Done |
| US30 | Conocer los servicios | T03 | Maquetar Pricing Section | Implementar la sección Pricing con grilla de tres planes y tarjetas informativas. | 6 | Huamanchumo Chicchon, Felipe Marcelo | Done |
| US31 | Comparar planes disponibles | T04 | Maquetar Team Section | Implementar la sección Team con información del equipo y foto representativa. | 4 | Huamanchumo Chicchon, Felipe Marcelo | Done |
| US32 | Acceder a la Web Application | T05 | Maquetar Contact Form | Implementar la sección de contacto con formulario de captura de datos y CTAs. | 8 | Huamanchumo Chicchon, Felipe Marcelo | Done |
| — | — | T06 | Configurar repositorio y despliegue | Crear repositorio en GitHub, configurar GitFlow, GitHub Pages y README inicial. | 4 | Llamozas Diaz, Edson Diego | Done |

**Total de horas estimadas:** 36 horas.

> **Nota:** Las tareas T01 a T05 fueron lideradas por `Daiko-07` (6 commits registrados). La tarea T06 fue liderada por `DiegoLlamozas` (1 commit registrado). Los demás integrantes del equipo colaboraron en el diseño, revisión y validación de contenido, cuyos aportes se evidencian en el repositorio del Project Report.
**Total de horas estimadas:** 36 horas.

##### 5.2.1.4 Development Evidence for Sprint Review

Durante el Sprint 1 se implementó la primera versión del Landing Page de Kinemo. El repositorio `landing-page-kinemo` registró **7 commits en total** (6 en `main`, 7 en todas las ramas), distribuidos en las semanas del 13 de septiembre, 27 de septiembre y 4 de octubre de 2026.

**Gráfico de commits por semana (Landing Page):**

![Commits over last year - Landing Page](./assets/img/landing-commits-over-year.png)

**Gráfico de frecuencia de código (Landing Page):**

[Code frequency - Landing Page](./assets/img/landing-code-frequency.png)!

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|---|---|---|---|---|---|
| kinemo-cinema/landing-page-kinemo | main | `[pendiente]` | `feat(landing): implement hero, platform, pricing and team sections` | Implementación inicial de las secciones principales del Landing Page. | 2026-09-13 |
| kinemo-cinema/landing-page-kinemo | main | `[pendiente]` | `feat(landing): implement contact form and CTAs` | Implementación del formulario de contacto con validaciones básicas. | 2026-09-27 |
| kinemo-cinema/landing-page-kinemo | main | `[pendiente]` | `chore: update assets and documentation` | Actualización de assets y documentación del Landing Page. | 2026-10-04 |

##### 5.2.1.5 Execution Evidence for Sprint Review


Durante el Sprint 1 se logró la implementación completa de la primera versión del Landing Page de Kinemo, compuesta por las siguientes secciones:

1. **Hero Section** — Presenta la propuesta de valor de Kinemo ("Lleva la experiencia 4D a tus salas de cine sin altos costos") con CTAs "Empezar ahora" y "Conoce más".
2. **Platform Section** — Describe las cuatro funcionalidades clave: Sincronización de efectos, Software de gestión simplificado, Gestión de incidencias de mantenimiento y Análisis de rendimiento.
3. **Pricing Section** — Presenta los tres planes de suscripción: Starter ($490/mes), Growth ($1,190/mes) y Enterprise (Custom).
4. **Team Section** — Muestra la información de los integrantes de la startup VonNeuman New Men.
5. **Contact Section** — Incluye el formulario de captura de datos para solicitar una demostración.

**Evidencia visual:** Las capturas de pantalla de cada sección se encuentran en el `README.md` del repositorio `landing-page-Kinemo` y en el informe (Figuras 4.3.1 y 4.3.2).

**Video de navegación:** El video que ilustra la visualización y navegación lograda en este Sprint se encuentra publicado en Microsoft Stream con el siguiente enlace: `[PENDIENTE — URL del video]`.


##### 5.2.1.6 Services Documentation Evidence for Sprint Review

Durante el Sprint 1 **no se implementaron Web Services**. El alcance de este Sprint se limitó exclusivamente al desarrollo y despliegue del Landing Page. La implementación del RESTful API está planificada para el Sprint 2 (TB1).

Por lo tanto, no se cuenta con Endpoints documentados con OpenAPI para este Sprint.

##### 5.2.1.7 Software Deployment Evidence for Sprint Review

![Pulse - Landing Page (1 month)](./assets/img/landing-pulse-overview-month.png)


Durante el Sprint 1 se realizó el despliegue del Landing Page utilizando **GitHub Pages**. El proceso consistió en:

1. **Creación del repositorio** `landing-page-Kinemo` en la organización `kinemo-cinema` de GitHub.
2. **Configuración de GitFlow** con las ramas `main` y `develop`.
3. **Desarrollo de las secciones** del Landing Page en ramas `feature/` independientes, fusionadas a `develop` y posteriormente a `main`.
4. **Activación de GitHub Pages** desde la configuración del repositorio (Settings → Pages), seleccionando la rama `main` y la carpeta raíz.
5. **Verificación del despliegue** accediendo a la URL pública.

**URL del Landing Page desplegado:** `https://kinemo-cinema.github.io/landing-page-Kinemo/`


##### 5.2.1.8 Team Collaboration Insights during Sprint

Resumen general del período:

- **5 autores** han realizado push de **6 commits a `main`** y **7 commits a todas las ramas**.
- **2 Pull Requests fusionados**, **0 Pull Requests abiertos**.
- **0 issues** cerrados o nuevos.
- **5 archivos modificados** en `main` con **539 adiciones** y **540 eliminaciones**.

**Top committers (Landing Page):**

![Contributors - Landing Page](./assets/img/landing-contributors-over-time.png)

| # | GitHub Username | Commits |
|---|---|---|
| 1 | Daiko-07 | 6 |
| 2 | DiegoLlamozas | 1 |


**Repositorio del Project Report (`kinemo-cinema-report`)**

Resumen general del período:

- **5 autores** han realizado push de **25 commits a `main`** y **94 commits a todas las ramas**.
- **13 Pull Requests fusionados**, **1 Pull Request abierto**.
- **0 issues** cerrados o nuevos.
- **5 archivos modificados** en `main` con **682 adiciones** y **0 eliminaciones**.

**Top committers (Project Report):**

![Contributors - Project Report](./assets/img/report-contributors-detail.png)

| # | GitHub Username | Commits |
|---|---|---|
| 1 | DiegoLlamozas | 25 |
| 2 | Elmiau2341 | 24 |
| 3 | Daiko-07 | 24 |
| 4 | Crzzz30 | 15 |
| 5 | Ferdwar | 6 |

**Contribuidores (Project Report):**

![Commits over time - Project Report](./assets/img/report-contributors-over-time.png)

**Actividad semanal de commits (Project Report):**

![Commits over last year - Project Report](./assets/img/report-commits-over-year.png)

**Repositorio del Frontend (`kinemo-cinema-frontend`)**

Resumen general del período:

- **5 autores** han realizado push de **131 commits a todas las ramas**.
- **13 Pull Requests fusionados**, **13 Pull Requests activos**.
- **0 issues** cerrados o nuevos.
- **1 commit en `main`** (la rama `main` aún no ha sido fusionada con `develop`, por lo que el trabajo consolidado se encuentra en `develop`).

**Top committers (Frontend):**

![Contributors - Frontend](./assets/img/frontend-contributors-over-time.png)

| # | GitHub Username | Commits |
|---|---|---|
| 1 | DiegoLlamozas | 93 |
| 2 | Ferdwar | 23 |
| 3 | Crzzz30 | 12 |
| 4 | Daiko-07 | 2 |
| 5 | Elmiau2341 | 1 |

**Código agregado (Code Frequency - Frontend):**

![Code frequency - Frontend](./assets/img/frontend-code-frequency.png)

**Pulse - Frontend:**

![Pulse - Frontend](./assets/img/frontend-pulse-overview.png)

- **Semana del 27 de septiembre de 2026:** 1,727 adiciones (primera implementación de la Web Application).

**Conclusión del Sprint 1**

La colaboración del equipo se evidencia a través de la distribución del trabajo entre los cinco integrantes. El repositorio del Landing Page concentró el esfuerzo principal del Sprint 1, con `Daiko-07` como líder del desarrollo del Landing Page y `DiegoLlamozas` a cargo de la configuración del repositorio y despliegue. En paralelo, el repositorio del Project Report registró contribuciones significativas de todos los integrantes, con `DiegoLlamozas`, `Elmiau2341` y `Daiko-07` como principales contribuidores del informe. El repositorio del frontend, aunque activo desde antes del cierre del Sprint 1, aún mantiene su trabajo consolidado en la rama `develop`, pendiente de integración con `main` para el siguiente hito.

#### 5.2.2 Sprint 2 (TB1)

##### 5.2.2.1 Sprint Planning 2

| Sprint # | Sprint 2 |
|---|---|
| Date | 🔴 [NEED REAL DATA — e.g. 2026-09-21] |
| Time | 🔴 [NEED REAL DATA — e.g. 08:00 PM] |
| Location | 🔴 [NEED REAL DATA — e.g. Reunión virtual vía Discord] |
| Prepared By | 🔴 [NEED REAL DATA — likely Llamozas Diaz, Edson Diego] |
| Attendees | Llamozas Diaz, Edson Diego / Flores Chavez, Fabricio / Huamanchumo Chicchon, Felipe Marcelo / Trigoso Garrido, Cristian Joseph / Correa Rodriguez, Andrea Khristina |
| Sprint n-1 Review Summary | Durante el Sprint 1 se completó el Landing Page B2B de Kinemo, con las secciones Hero, Platform, Pricing, Team y Contact Form implementadas y desplegadas en GitHub Pages. El equipo validó la propuesta de valor y los precios con el público objetivo. |
| Sprint n-1 Retrospective Summary | El equipo identificó como oportunidades de mejora: (1) distribuir mejor las tareas de desarrollo para evitar la concentración de commits en un solo integrante, (2) iniciar la integración entre frontend y backend de forma temprana, y (3) mantener la documentación actualizada conforme avanza el Sprint. |
| Sprint 2 Goal | Nuestro objetivo es lanzar la primera versión funcional de la Web Application de Kinemo integrada con el RESTful API. Creemos que ofrece al personal operativo y gerentes de cadenas de cine una herramienta centralizada para gestionar la programación de funciones, la configuración de efectos y el seguimiento del mantenimiento de las salas. Esto quedará confirmado cuando los usuarios puedan iniciar sesión, consultar el catálogo de películas 4D y visualizar la programación diaria de funciones desde la Web Application desplegada. |
| Sprint 2 Velocity | 🔴 [NEED REAL DATA — estimated 25–30 Story Points] |
| Sum of Story Points | 🔴 [NEED REAL DATA — estimated 25–30 Story Points] |

##### 5.2.2.2 Aspect Leaders and Collaborators

La siguiente tabla muestra la asignación de líderes (L) y colaboradores (C) por cada aspecto de la Web Application durante el Sprint 2. Esta organización se alinea con la evidencia de commits registrada en el repositorio `kinemo-cinema-frontend`.

| Team Member | GitHub Username | Authentication | Movie Catalog | Scheduling | Seat Management | Effects & Sync | Maintenance | API Integration |
|---|---|---|---|---|---|---|---|---|
| Llamozas Diaz, Edson Diego | DiegoLlamozas | L | L | L | C | C | C | L |
| Flores Chavez, Fabricio | Ferdwar | C | C | L | L | C | C | C |
| Trigoso Garrido, Cristian Joseph | Crzzz30 | C | C | C | C | L | L | C |
| Huamanchumo Chicchon, Felipe Marcelo | Daiko-07 | C | C | C | C | C | C | C |
| Correa Rodriguez, Andrea Khristina | Elmiau2341 | C | C | C | C | C | C | C |

> **Nota sobre la evidencia de commits:** Los aspectos de mayor actividad en el Sprint 2 se concentraron en `DiegoLlamozas` (93 commits), `Ferdwar` (23 commits) y `Crzzz30` (12 commits), según los analíticos de GitHub Insights del repositorio `kinemo-cinema-frontend`.

##### 5.2.2.3 Sprint Backlog 2

El Sprint Backlog 2 comprende las User Stories del Web Application (US01–US27) priorizadas en el Product Backlog, junto con las Technical Stories del RESTful API (US33–US38), descompuestas en tareas técnicas.

| Sprint # | Sprint 2 |
|---|---|
| **User Story** | **Work-Item / Task** | | | | |
| **Story ID** | **Story Title** | **Task ID** | **Task Title** | **Task Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| US01 | Registrar película 4D | T07 | Implementar formulario de registro de películas | Crear el formulario en Vue para registrar películas con validaciones. | 6 | Llamozas Diaz, Edson Diego | Done |
| US03 | Consultar catálogo | T08 | Implementar vista de catálogo de películas | Crear la vista de listado de películas con filtros por género y estado. | 6 | Llamozas Diaz, Edson Diego | Done |
| US07 | Programar función | T09 | Implementar formulario de programación de funciones | Crear la interfaz para programar funciones con validación de conflictos de horario. | 8 | Flores Chavez, Fabricio | Done |
| US09 | Visualizar resumen diario de funciones | T10 | Implementar vista de programación diaria | Crear la vista de funciones del día ordenadas cronológicamente. | 5 | Flores Chavez, Fabricio | Done |
| US10 | Consultar estado de butacas | T11 | Implementar vista de estado de butacas | Crear la vista de mapa de butacas con estados (disponible, habilitada, fuera de servicio). | 6 | Flores Chavez, Fabricio | Done |
| US13 | Iniciar secuencia de efectos | T12 | Implementar control de inicio de secuencia de efectos | Crear la interfaz para iniciar la sincronización entre película y efectos. | 8 | Trigoso Garrido, Cristian Joseph | Done |
| US17 | Probar canal de efectos | T13 | Implementar vista de prueba de efectos | Crear la interfaz para probar individualmente los canales de efectos. | 6 | Trigoso Garrido, Cristian Joseph | Done |
| US20 | Registrar falla de equipo | T14 | Implementar formulario de registro de incidencias | Crear el formulario para reportar fallas en componentes con nivel de severidad. | 6 | Trigoso Garrido, Cristian Joseph | Done |
| US26 | Visualizar dashboard operativo | T15 | Implementar dashboard de métricas operativas | Crear el dashboard con gráficos de uso de salas e incidencias registradas. | 8 | Llamozas Diaz, Edson Diego | Done |
| US33 | Consultar películas mediante API | T16 | Implementar endpoint GET /movies | Implementar el endpoint para consultar el catálogo de películas con soporte para filtros. | 5 | Llamozas Diaz, Edson Diego | Done |
| US34 | Registrar una película mediante API | T17 | Implementar endpoint POST /movies | Implementar el endpoint para registrar nuevas películas con validación de datos. | 5 | Llamozas Diaz, Edson Diego | Done |
| US35 | Consultar funciones mediante API | T18 | Implementar endpoint GET /shows | Implementar el endpoint para consultar las funciones programadas. | 4 | Llamozas Diaz, Edson Diego | Done |
| US36 | Registrar una incidencia mediante API | T19 | Implementar endpoint POST /incidents | Implementar el endpoint para registrar incidencias de mantenimiento. | 4 | Llamozas Diaz, Edson Diego | Done |
| US37 | Consultar estado de una sala mediante API | T20 | Implementar endpoint GET /rooms/{id} | Implementar el endpoint para consultar el estado de una sala específica. | 4 | Llamozas Diaz, Edson Diego | Done |
| US38 | Consultar estado de suscripción mediante API | T21 | Implementar endpoint GET /subscription | Implementar el endpoint para consultar el estado de la suscripción. | 5 | Llamozas Diaz, Edson Diego | Done |
| — | — | T22 | Configurar integración frontend-backend | Configurar Axios en el frontend para consumir el RESTful API y manejar CORS. | 6 | Llamozas Diaz, Edson Diego | Done |
| — | — | T23 | Desplegar Web Application y API | Configurar el despliegue del frontend (Vercel/Netlify) y del backend (MonsterASP.NET/Azure). | 6 | Llamozas Diaz, Edson Diego | Done |

**Total de horas estimadas:** 107 horas.

##### 5.2.2.4 Development Evidence for Sprint Review

Durante el Sprint 2 se implementó la primera versión funcional de la Web Application de Kinemo y del RESTful API. El repositorio `kinemo-cinema-frontend` registró **131 commits en todas las ramas**, con **1,727 adiciones** en la semana del 27 de septiembre de 2026, según los analíticos de GitHub Insights.

**Gráfico de commits por semana (Frontend):**

![Commits over last year - Frontend](./assets/img/frontend-commits-over-year.png)

**Gráfico de frecuencia de código (Frontend):**

![Code frequency - Frontend](./assets/img/frontend-code-frequency.png)

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|---|---|---|---|---|---|
| kinemo-cinema/kinemo-cinema-frontend | develop | 🔴 [NEED REAL DATA] | `feat(auth): implement user authentication flow` | Implementación del flujo de autenticación con JWT. | 2026-09-27 |
| kinemo-cinema/kinemo-cinema-frontend | develop | 🔴 [NEED REAL DATA] | `feat(catalog): add movie catalog view with filters` | Implementación de la vista de catálogo de películas con filtros. | 2026-09-28 |
| kinemo-cinema/kinemo-cinema-frontend | develop | 🔴 [NEED REAL DATA] | `feat(scheduling): add show scheduling form` | Implementación del formulario de programación de funciones. | 2026-09-29 |
| kinemo-cinema/kinemo-cinema-frontend | develop | 🔴 [NEED REAL DATA] | `feat(seats): add seat map view` | Implementación del mapa de butacas con estados. | 2026-09-30 |
| kinemo-cinema/kinemo-cinema-frontend | develop | 🔴 [NEED REAL DATA] | `feat(dashboard): add operational metrics dashboard` | Implementación del dashboard de métricas operativas. | 2026-10-01 |
| kinemo-cinema/kinemo-cinema-frontend | develop | 🔴 [NEED REAL DATA] | `feat(api): integrate frontend with RESTful API` | Integración del frontend con el RESTful API mediante Axios. | 2026-10-03 |
| 🔴 [NEED REAL DATA] | — | 🔴 [NEED REAL DATA] | `feat(api): implement movies and shows endpoints` | Implementación de los endpoints del RESTful API. | 🔴 [NEED REAL DATA] |

> **Instrucción:** Reemplazar cada `🔴 [NEED REAL DATA]` con los datos reales obtenidos al ejecutar `git log --oneline --all` en los repositorios `kinemo-cinema-frontend` y del RESTful API.

##### 5.2.2.5 Execution Evidence for Sprint Review

Durante el Sprint 2 se logró la implementación de la primera versión funcional de la Web Application de Kinemo, compuesta por las siguientes vistas principales:

1. **Login / Authentication** — Pantalla de inicio de sesión con autenticación vía JWT.
2. **Movie Catalog** — Vista de catálogo de películas 4D con filtros por título y género.
3. **Scheduling** — Vista de programación de funciones con validación de conflictos de horario.
4. **Seat Map** — Vista de mapa de butacas con estados (disponible, habilitada, fuera de servicio).
5. **Effects Control** — Interfaz para iniciar, pausar y detener la secuencia de efectos.
6. **Maintenance** — Formulario de registro de incidencias y seguimiento de mantenimiento.
7. **Dashboard** — Dashboard con métricas operativas de uso de salas e incidencias.

**Evidencia visual:** Las capturas de pantalla de cada vista se encuentran en el Anexo B.

**Video de navegación:** El video que ilustra la visualización y navegación lograda en este Sprint se encuentra publicado en Microsoft Stream con el siguiente enlace: 🔴 [NEED REAL DATA — URL del video].

##### 5.2.2.6 Services Documentation Evidence for Sprint Review

Durante el Sprint 2 se implementó la primera versión del RESTful API de Kinemo, documentada con OpenAPI/Swagger. Los Endpoints implementados son los siguientes:

| Endpoint | Verbo HTTP | Acción | Parámetros | Response |
|---|---|---|---|---|
| `/api/v1/movies` | GET | Consultar catálogo de películas | `?genre=`, `?status=` | 200 OK — Lista de películas |
| `/api/v1/movies` | POST | Registrar nueva película | Body con datos de película | 201 Created — Película registrada |
| `/api/v1/movies/{id}` | GET | Consultar película por ID | `id` en path | 200 OK — Película encontrada |
| `/api/v1/shows` | GET | Consultar funciones programadas | `?date=`, `?roomId=` | 200 OK — Lista de funciones |
| `/api/v1/shows` | POST | Programar nueva función | Body con datos de función | 201 Created — Función programada |
| `/api/v1/incidents` | POST | Registrar incidencia | Body con datos de incidencia | 201 Created — Incidencia registrada |
| `/api/v1/rooms/{id}` | GET | Consultar estado de sala | `id` en path | 200 OK — Estado de la sala |
| `/api/v1/subscription` | GET | Consultar estado de suscripción | — | 200 OK — Estado de suscripción |

**Documentación Swagger/OpenAPI desplegada:** 🔴 [NEED REAL DATA — URL del Swagger desplegado]

**Repositorio del RESTful API:** 🔴 [NEED REAL DATA — URL del repositorio]

**Capturas de pantalla:** Las imágenes de la documentación interactiva de Swagger se incluyen en el Anexo B.

##### 5.2.2.7 Software Deployment Evidence for Sprint Review

Durante el Sprint 2 se realizó el despliegue de la primera versión funcional de la Web Application y del RESTful API. El proceso consistió en:

**Web Application (Vue + PrimeVue)**

1. **Configuración del proyecto** para producción (`npm run build`).
2. **Despliegue en Vercel/Netlify** conectado al repositorio `kinemo-cinema-frontend`.
3. **Configuración de variables de entorno** para apuntar al RESTful API desplegado.
4. **Verificación del despliegue** accediendo a la URL pública.

**RESTful API (ASP.NET Core + C#)**

**URLs de despliegue:**


**Capturas de pantalla:** Las imágenes del proceso de despliegue se incluyen en el Anexo B.

##### 5.2.2.8 Team Collaboration Insights during Sprint

Durante el Sprint 2, todos los integrantes del equipo participaron activamente en el desarrollo de la Web Application y del RESTful API. A continuación se presentan los analíticos obtenidos directamente desde **GitHub Insights** para el período del Sprint 2.

### Repositorio del Frontend (`kinemo-cinema-frontend`)

Resumen general del período:

- **5 autores** han realizado push de **131 commits a todas las ramas**.
- **13 Pull Requests fusionados**, **13 Pull Requests activos**.
- **0 issues** cerrados o nuevos.
- **1 commit en `main`** (la rama `main` aún no ha sido fusionada con `develop`, por lo que el trabajo consolidado se encuentra en `develop`).

**Pulse - Frontend:**

![Pulse - Frontend](./assets/img/frontend-pulse-overview.png)

**Top committers (Frontend):**

![Contributors - Frontend](./assets/img/frontend-contributors-over-time.png)

| # | GitHub Username | Commits |
|---|---|---|
| 1 | DiegoLlamozas | 93 |
| 2 | Ferdwar | 23 |
| 3 | Crzzz30 | 12 |
| 4 | Daiko-07 | 2 |
| 5 | Elmiau2341 | 1 |

**Commits por semana (Frontend):**

![Commits over last year - Frontend](./assets/img/frontend-commits-over-year.png)

| Semana | Commits |
|---|---|
| 2026-09-27 | 1 |

**Frecuencia de código (Frontend):**

![Code frequency - Frontend](./assets/img/frontend-code-frequency.png)

- **Semana del 27 de septiembre de 2026:** 1,727 adiciones (primera implementación de la Web Application).

### Repositorio del RESTful API


### Conclusión del Sprint 2

La colaboración del equipo durante el Sprint 2 se evidencia a través de la distribución del trabajo en el repositorio del frontend. `DiegoLlamozas` lideró la implementación de la Web Application y la integración con el RESTful API (93 commits), seguido de `Ferdwar` (23 commits) y `Crzzz30` (12 commits), quienes se enfocaron en los módulos de programación de funciones, mapa de butacas y control de efectos. Los demás integrantes (`Daiko-07` y `Elmiau2341`) colaboraron en el diseño y validación de las vistas, así como en la redacción del informe.

El Sprint 2 cumplió con los objetivos planteados en el Sprint Planning 2: se desplegó la primera versión funcional de la Web Application, se implementó el RESTful API con sus endpoints principales, y se integró el frontend con el backend. Como deuda técnica, la rama `main` del frontend aún no ha sido fusionada con `develop`, lo cual se resolverá antes de la entrega TB1.
#### 5.2.3 Sprint 3 (AV2)

Durante el Sprint 3 se continúa el desarrollo de Kinemo a partir de la versión trabajada en TB1. El enfoque técnico comprende la evolución de la Web Application desarrollada con Vue 3 y Vite y del RESTful API desarrollado con ASP.NET Core. La documentación del sprint debe diferenciar funcionalidades implementadas, funcionalidades en proceso y actividades pendientes de integración o despliegue.

##### 5.2.3.1 Sprint Planning 3

| Campo | Detalle |
|---|---|
| Sprint # | Sprint 3 (AV2) |
| Fecha y hora | **[PENDIENTE: acta real de planificación]** |
| Modalidad | **[PENDIENTE: confirmar reunión]** |
| Participantes | Equipo VonNeuman New Men |
| Sprint n-1 Review Summary | En TB1 se trabajó la implementación de la Web Application y los servicios del backend, distribuidos en módulos funcionales. |
| Sprint n-1 Retrospective Summary | Se identificó la necesidad de mantener la trazabilidad de tareas, verificar las integraciones y registrar evidencia reproducible de ejecución. Esta observación deberá validarse con la retrospectiva real. |
| Sprint Goal | Continuar la implementación y estabilización de los módulos de Kinemo, documentando los cambios en frontend y backend y preparando evidencias de ejecución, servicios y despliegue para AV2. |
| Sprint Velocity | **[PENDIENTE: Story Points comprometidos]** |
| Sum of Story Points | **[PENDIENTE: sumar historias del Sprint Backlog real]** |

##### 5.2.3.2 Aspect Leaders and Collaborators

Los participantes del proyecto son Edson Diego Llamozas Diaz, Fabricio Flores Chavez, Felipe Marcelo Huamanchumo Chicchon, Cristian Joseph Trigoso Garrido y Andrea Khristina Correa Rodriguez. La asignación de liderazgo (L) y colaboración (C) para el Sprint 3 deberá obtenerse del tablero de tareas y de los Pull Requests del período, para evitar atribuir funcionalidades sin evidencia.

| Aspecto | Líder (L) | Colaboradores (C) | Evidencia |
|---|---|---|---|
| Catálogo y programación | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** | PRs y commits del frontend/backend |
| Readiness, asientos y ejecución | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** | PRs y commits del frontend/backend |
| Mantenimiento y emergencias | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** | PRs y commits del frontend/backend |
| Suscripciones y analítica | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** | PRs y commits del frontend/backend |
| Documentación y despliegue | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** | Commits del informe y URLs de despliegue |

##### 5.2.3.3 Sprint Backlog 3

El Sprint Backlog se construye a partir de las User Stories priorizadas para AV2. Como áreas de trabajo identificadas en la solución se consideran catálogo, programación, preparación de salas, asientos, mantenimiento, suscripciones y analítica. Los identificadores de User Stories, horas, responsables y estados deben extraerse del tablero del equipo; no se presupone que todas las funcionalidades estén terminadas.

| Work Item | Descripción | Responsable | Estado |
|---|---|---|---|
| Evolución de frontend | Implementación y ajustes de vistas y componentes Vue | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** |
| Evolución de backend | Implementación y mantenimiento de Bounded Contexts, servicios y controladores | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** |
| Integración | Configuración y verificación de llamadas HTTP entre frontend y API | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** |
| Verificación | Compilación, pruebas y registro de resultados | **[POR CONFIRMAR]** | **[POR CONFIRMAR]** |
| Documentación | Actualización de evidencias del Project Report | **[POR CONFIRMAR]** | En elaboración |

**Pendiente:** sustituir esta tabla de áreas de trabajo por el Sprint Backlog real con Story ID, Task ID, estimación en horas y estado.

##### 5.2.3.4 Development Evidence for Sprint Review

El desarrollo del Sprint 3 se gestiona mediante los siguientes repositorios:

- **Frontend:** https://github.com/kinemo-cinema/kinemo-cinema-frontend
- **Backend:** https://github.com/kinemo-cinema/kinemo-platform
- **Project Report:** https://github.com/kinemo-cinema/kinemo-cinema-report

El frontend utiliza Vue 3, Vite, Vue Router, PrimeVue y Axios. El backend se desarrolla con ASP.NET Core y utiliza una organización por Bounded Contexts y capas de aplicación, dominio, infraestructura e interfaces. Estas decisiones permiten separar responsabilidades y mantener la evolución de las funcionalidades.

Para la revisión se debe registrar una tabla con repositorio, rama, identificador real de commit, mensaje, autor y fecha. Las capturas de GitHub Insights y de los Pull Requests correspondientes al Sprint 3 se incorporarán como evidencia.

**[PENDIENTE: hashes de commits, fechas, autores y capturas reales de AV2].**

##### 5.2.3.5 Execution Evidence for Sprint Review

La verificación de la Web Application contempla ejecutar la aplicación en el entorno de desarrollo, recorrer las vistas implementadas y comprobar navegación, presentación de datos y funcionamiento de formularios. La verificación del backend contempla compilar la solución, iniciar el servidor y comprobar las rutas implementadas mediante el cliente de documentación de API o peticiones HTTP.

**Evidencias requeridas:** capturas de las vistas operativas, registro de compilación y ejecución, casos de prueba realizados y video de navegación con su URL.

**[PENDIENTE: resultados y capturas de ejecución de AV2; no se afirma integración completa].**

##### 5.2.3.6 Services Documentation Evidence for Sprint Review

El RESTful API se encuentra en el repositorio `kinemo-platform`. La documentación técnica debe presentar los endpoints existentes, el método HTTP, los parámetros, el formato de respuesta y el resultado observado al ejecutar cada operación. La especificación OpenAPI puede presentarse mediante Scalar, según la configuración del backend.

| Evidencia | Referencia |
|---|---|
| Repositorio del RESTful API | https://github.com/kinemo-cinema/kinemo-platform |
| Documentación OpenAPI/Scalar | **[PENDIENTE: URL o ruta local verificada]** |
| Tabla de endpoints comprobados | **[PENDIENTE: extraer de controladores reales]** |
| Capturas de solicitudes y respuestas | **[PENDIENTE]** |

##### 5.2.3.7 Software Deployment Evidence for Sprint Review

La arquitectura de Kinemo contempla el despliegue separado del Landing Page, la Web Application y el RESTful API. La configuración local y la compilación del código no constituyen por sí mismas evidencia de despliegue público. Para esta sección se documentará el proveedor utilizado, la configuración aplicada, la URL accesible y una prueba de funcionamiento.

| Producto | Estado documentado |
|---|---|
| Landing Page | GitHub Pages; URL consignada en Sprint 1 |
| Web Application | **[PENDIENTE: verificar despliegue público]** |
| RESTful API | **[PENDIENTE: verificar despliegue público]** |

##### 5.2.3.8 Team Collaboration Insights during Sprint

El trabajo colaborativo se organiza mediante ramas de funcionalidades, commits y Pull Requests en GitHub. La evaluación de la participación del Sprint 3 debe considerar tanto los cambios de código como la revisión de Pull Requests, documentación, pruebas y coordinación del equipo.

**[PENDIENTE: capturas de GitHub Insights, commits y Pull Requests filtrados al período real de AV2].**

#### 5.2.4 Sprint 4 (TB2)

### 5.3 Validation Interviews

#### 5.3.1 Diseño de Entrevistas

Las entrevistas de validación se orientan a evaluar la utilidad, claridad y facilidad de uso de la solución Kinemo en los segmentos objetivo identificados en el Capítulo II. Se propone realizar tareas representativas sobre el prototipo o la aplicación disponible, tales como consultar funciones, navegar por los módulos operativos y localizar información de mantenimiento o suscripciones.

La guía de validación considera preguntas sobre comprensión de la interfaz, facilidad de navegación, dificultades encontradas, percepción de utilidad y oportunidades de mejora. Se deben definir participantes, criterios de selección, consentimiento y tareas antes de realizar las sesiones.

**[PENDIENTE: confirmar guía final, participantes y sesiones realizadas].**

#### 5.3.2 Registro de Entrevistas

Cada entrevista deberá registrar código de participante, segmento, fecha, modalidad, tareas ejecutadas, observaciones, dificultades y recomendaciones. Los hallazgos deben presentarse de forma anonimizada y vinculados a oportunidades concretas de mejora del producto.

**[PENDIENTE: entrevistas realizadas, enlaces a grabaciones autorizadas y resultados reales].**

#### 5.3.3 Evaluaciones según heurísticas

Las observaciones de las sesiones se organizarán según los criterios heurísticos solicitados por el curso, utilizando el formato del Anexo D del enunciado. Cada hallazgo deberá incluir la pantalla o tarea evaluada, descripción del problema, heurística relacionada, severidad y recomendación de mejora.

**[PENDIENTE: evaluaciones y formato del Anexo D; no se asignan severidades sin resultados].**

### 5.4 Video About-the-Product

El video About-the-Product presentará la propuesta de valor de Kinemo, los segmentos objetivo y una demostración de las funcionalidades disponibles en la versión de AV2. La narración debe explicar cómo el Landing Page y la Web Application contribuyen a la gestión de experiencias cinematográficas inmersivas, mostrando únicamente los flujos implementados y verificables.

**[PENDIENTE: URL del video publicado y confirmación de duración/formato exigidos por AV2].**

## Conclusiones

### Conclusiones y recomendaciones

La evolución de Kinemo evidencia la necesidad de mantener alineados el diseño de la solución, el código fuente, las pruebas y la documentación de cada sprint. Para AV2, la prioridad es verificar las funcionalidades realmente disponibles y registrar evidencia reproducible de su ejecución. Los resultados definitivos y recomendaciones finales se completarán en TB2.

### Video About-the-Team

> _A completar a partir de AV2 (primera versión), versión final en TB2._

## Bibliografía

- López, A. (2018, 6 de noviembre). *¿Cuáles son los cines con mayor participación en el país?* Mercado Negro. https://www.mercadonegro.pe/marketing/cuales-son-los-cines-con-mayor-participacion-en-el-pais/

- UVK Multicines. (s. f.). Nuestros cines. Recuperado el 8 de septiembre de 2026, de https://uvk.pe/cines

- Wikipedia contributors. (s. f.). UVK Multicines. En Wikipedia, la enciclopedia libre. Recuperado el 8 de septiembre de 2026, de https://es.wikipedia.org/wiki/UVK_Multicines
  Boxoffice Pro. (2018, January 24). One of the nation's largest cinema chains, family-run B&B Theaters, announces multi-site integration of MediaMation's MX4D. https://www.boxofficepro.com

CJ 4DPLEX. (n.d.). 4DX. Retrieved September 9, 2026, from https://www.cj4dx.com

D-BOX Technologies Inc. (n.d.). The ultimate guide to moving cinema seats. Retrieved September 9, 2026, from https://www.d-box.com

D-BOX Technologies Inc. (n.d.). Why cinemas are choosing D-BOX motion seats. Retrieved September 9, 2026, from https://www.d-box.com

MediaMation, Inc. (n.d.). MX4D theatres. Retrieved September 9, 2026, from https://www.mediamation.com/mx4d-theatres/

Whitten, S. (2024, June 2). Shaking seats and piped-in fog: How 4DX is carving out a niche moviegoing market. CNBC. https://www.cnbc.com

## Anexos

### Anexo A. Videos de Exposiciones

| Entrega | Título del video | Enlace |
|---|---|---|
| AV1 | `[Pendiente]` | `[Pendiente]` |