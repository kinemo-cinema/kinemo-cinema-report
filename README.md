_# Informe de Trabajo Final — Kinemo

![Logo UPC](Kinemo-report/assets/cover/logo-upc.png)

| Campo | Valor |
|---|---|
| Universidad | Universidad Peruana de Ciencias Aplicadas (UPC) |
| Carrera | Ingeniería de Software |
| Ciclo | 2026-20 |
| Código y Nombre del Curso | 1ASI0730 – Aplicaciones Web |
| NRC | 8155 |
| Profesor | Angel Augusto Velasquez Nuñez |
| Nombre del Startup | VonNeuman New Men |
| Nombre del Producto | Kinemo |
| Año | 2026 |

**Integrantes**

| Código | Apellidos y Nombres |
|---|---|
| u202319398 | Llamozas Diaz, Edson Diego |
| u202212327 | Flores Chavez, Fabricio |
| u20241b932 | Huamanchumo Chicchon, Felipe Marcelo |
| u202318865 | Trigoso Garrido, Cristian Joseph |
| u202412041 | Correa Rodriguez, Andrea Khristina |

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---|---|---|---|
| 1.0 | |  |  |

## Project Report Collaboration Insights

Repositorio del Project Report: `https://github.com/kinemo-cinema/kinemo-cinema-report`

> _Pendiente — a partir de AV1, agregar explicación del proceso de elaboración del informe y capturas de los analíticos de colaboración/commits de GitHub._

## Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1 Startup Profile](#11-startup-profile)
        - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2 Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3 Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1 Competidores](#21-competidores)
        - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2 Entrevistas](#22-entrevistas)
        - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3 Needfinding](#23-needfinding)
        - [2.3.1 User Personas](#231-user-personas)
        - [2.3.2 User Task Matrix](#232-user-task-matrix)
        - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.4 Big Picture EventStorming](#24-big-picture-eventstorming)
    - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1 User Stories](#31-user-stories)
    - [3.2 Impact Mapping](#32-impact-mapping)
    - [3.3 Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1 Style Guidelines](#41-style-guidelines)
        - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
    - [4.2 Information Architecture](#42-information-architecture)
        - [4.2.1 Organization Systems](#421-organization-systems)
        - [4.2.2 Labeling Systems](#422-labeling-systems)
        - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4 Searching Systems](#424-searching-systems)
        - [4.2.5 Navigation Systems](#425-navigation-systems)
    - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1 Design-Level EventStorming](#461-design-level-eventstorming)
        - [4.6.2 Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3 Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4 Software Architecture Component Diagrams](#464-software-architecture-component-diagrams)
    - [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1 Class Diagrams](#471-class-diagrams)
    - [4.8 Database Design](#48-database-design)
        - [4.8.1 Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1 Software Configuration Management](#51-software-configuration-management)
        - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2 Source Code Management](#512-source-code-management)
        - [5.1.3 Source Code Style Guide & Coding Conventions](#513-source-code-style-guide--coding-conventions)
        - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1 Sprint 1 (AV1)](#521-sprint-1-av1)
        - [5.2.2 Sprint 2 (TB1)](#522-sprint-2-tb1)
        - [5.2.3 Sprint 3 (AV2)](#523-sprint-3-av2)
        - [5.2.4 Sprint 4 (TB2)](#524-sprint-4-tb2)
    - [5.3 Validation Interviews](#53-validation-interviews)
        - [5.3.1 Diseño de Entrevistas](#531-diseño-de-entrevistas)
        - [5.3.2 Registro de Entrevistas](#532-registro-de-entrevistas)
        - [5.3.3 Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
    - [5.4 Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
    - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
    - [Anexo A. Videos de Exposiciones](#anexo-a-videos-de-exposiciones)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

| Criterio específico | Acciones realizadas | Conclusiones |
|--|---|---|
|  |  |  |

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

Kinemo es una startup de tecnología para entretenimiento cinematográfico que provee a cadenas de cine pequeñas y medianas una solución integral de experiencias inmersivas: butacas con movimiento y efectos físicos sincronizados, como viento y vibración, servicio de mantenimiento especializado y un software propio de gestión operativa.

Kinemo nace para cerrar la brecha entre las grandes cadenas de cine que ya cuentan con tecnología inmersiva propietaria, como 4DX o D-BOX, y las cadenas pequeñas y medianas, que actualmente presentan mayores dificultades para competir en experiencia de usuario debido al alto costo de inversión y a la falta de conocimiento técnico especializado para operar y mantener este tipo de tecnología por cuenta propia.

**Tagline:** “Cine que se siente.”

**Misión:** Democratizar el acceso a experiencias cinematográficas inmersivas, permitiendo que cadenas de cine de cualquier tamaño ofrezcan a sus espectadores sensaciones físicas sincronizadas con el contenido, a través de una solución accesible de hardware, mantenimiento y software de gestión.

#### 1.1.2. Perfiles de integrantes del equipo

| Carrera | Integrante | Foto |
|---|---|---|
| Ingeniería de Software | **Cristian Joseph Trigoso Garrido**  U202318865 | ![Cristian Joseph Trigoso Garrido](assets/cristian-trigoso.jpg) |
| **Descripción** | Me gusta la superación personal y el aprendizaje continuo en el ámbito del desarrollo de software. Me motiva explorar y dominar nuevas herramientas tecnológicas para aportar soluciones creativas y de impacto en proyectos colaborativos. | |

| Carrera | Integrante | Foto |
|---|---|---|
| Ingeniería de Software | **Felipe Marcelo Huamanchumo Chicchon**  U20241B932 | ![Felipe Marcelo Huamanchumo Chicchon](assets/felipe-huamanchumo.jpg) |
| **Descripción** | Cuento con conocimientos en programación con C++, bases de datos utilizando SQL y nociones de redes mediante Cisco Packet Tracer. Además, poseo conocimientos básicos en Microsoft Azure, diseño de interfaces con Figma y patrones de software. Dentro del equipo puedo aportar en la organización de tareas, investigación y resolución de problemas para el desarrollo del proyecto. | |

| Carrera | Integrante | Foto |
|---|---|---|
| Ingeniería de Software | **Fabricio Flores Chavez**  U202212327 | ![Fabricio Flores Chavez](assets/fabricio-flores.jpg) |
| **Descripción** | Me gusta mucho seguir aprendiendo cosas nuevas y poder ser un gran profesional, y siempre poder ayudar a los demás en lo que necesiten. | |

| Carrera | Integrante | Foto |
|---|---|---|
| Ingeniería de Software | **Andrea Khristina Correa Rodriguez**  U202412041 | ![Andrea Khristina Correa Rodriguez](assets/andrea-correa.jpg) |
| **Descripción** | Estudiante de Ingeniería de Software con enfoque en análisis de sistemas y arquitectura de software. Tiene conocimientos en modelado de procesos de negocio. Le motiva entender cómo funcionan los sistemas complejos y traducir requisitos en soluciones técnicas efectivas. | |

| Carrera | Integrante | Foto |
|---|---|---|
| Ingeniería de Software | **Edson Diego Llamozas Diaz**  U202319398 | ![Edson Diego Llamozas Diaz](assets/edson-llamozas.jpg) |
| **Descripción** | Estudiante de Ingeniería de Software, interesado en los sistemas de bajo nivel y lenguaje de ensamblador. | |

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

### Descripción de los antecedentes

La industria cinematográfica ha incorporado progresivamente tecnologías de entretenimiento inmersivo, como butacas con movimiento y efectos físicos sincronizados, con el propósito de ofrecer experiencias diferenciadas a los espectadores. Sin embargo, este tipo de soluciones se encuentra principalmente disponible en cadenas de cine de gran escala, debido a los elevados costos de adquisición, instalación, operación y mantenimiento.

Como consecuencia, las cadenas pequeñas y medianas encuentran mayores dificultades para adoptar estas tecnologías y competir mediante experiencias inmersivas, especialmente cuando disponen de recursos económicos y técnicos más limitados.

### Análisis 5W's y 2H's

**Who (¿Quién?):** Cadenas de cine pequeñas y medianas, operadas de forma independiente o con una cantidad reducida de complejos, así como su personal operativo y técnico, que actualmente no cuentan con tecnologías de entretenimiento inmersivo en sus salas.

**What (¿Qué?):** La dificultad para ofrecer experiencias de cine inmersivo, como butacas con movimiento y efectos físicos sincronizados, comparables a las ofrecidas por grandes cadenas, debido al alto costo de inversión y a la necesidad de conocimientos técnicos especializados para operar y mantener estas tecnologías.

**Where (¿Dónde?):** En salas de cine pertenecientes a cadenas pequeñas y medianas. Inicialmente, Kinemo orienta su propuesta al mercado peruano, considerando posteriormente la posibilidad de expansión hacia otros mercados latinoamericanos.

**When (¿Cuándo?):** El problema se presenta principalmente cuando estas cadenas buscan modernizar sus salas y diferenciar su oferta, así como durante la operación cotidiana de funciones, programación de efectos y mantenimiento de los equipos.

**Why (¿Por qué?):** Porque las soluciones tradicionales de entretenimiento inmersivo suelen requerir inversiones elevadas, infraestructura especializada y personal capacitado, factores que dificultan su adopción por parte de cadenas pequeñas y medianas.

**How (¿Cómo?):** Estas cadenas continúan operando principalmente salas convencionales y gestionando de forma poco integrada aspectos como programación, operación y mantenimiento, reduciendo sus posibilidades de incorporar experiencias inmersivas de manera accesible.

**How Much (¿Cuánto?):** En 2023, el mercado peruano de exhibición cinematográfica registró aproximadamente 45,9 millones de espectadores y S/485 millones en ingresos de taquilla (Apoyo & Asociados, 2024). Cineplanet concentró el 56% de la recaudación total, mientras que Cinemark alcanzó el 19,5% y Cinestar el 9%, evidenciando una concentración importante del mercado. Las fuentes públicas consultadas no presentan una estimación específica del impacto económico que genera la falta de experiencias inmersivas en las cadenas de cine pequeñas y medianas del Perú.

### Enunciado del problema

Las cadenas de cine pequeñas y medianas presentan dificultades para incorporar experiencias de entretenimiento inmersivo debido al elevado costo de las soluciones existentes, la necesidad de personal técnico especializado y la falta de herramientas digitales integradas que permitan administrar su operación.

Esta situación limita su capacidad para modernizar sus salas y ofrecer experiencias diferenciadas frente a cadenas de mayor escala.

### Puntos más importantes que debe resolver la solución propuesta

- Reducir la barrera de adopción de tecnologías de entretenimiento inmersivo para cadenas de cine pequeñas y medianas.
- Facilitar al personal operativo la gestión de funciones y efectos inmersivos mediante una aplicación web.
- Proporcionar herramientas para registrar y gestionar actividades relacionadas con el mantenimiento de las salas.
- Centralizar en una misma solución digital los principales procesos asociados a la operación de las experiencias inmersivas.
- Presentar mediante el Landing Page la propuesta de valor de Kinemo y dirigir a los segmentos objetivo hacia las funcionalidades correspondientes de la Web Application.

### Objetivos del proyecto

- Diseñar y desarrollar una solución web que permita administrar la operación de experiencias cinematográficas inmersivas dirigidas a cadenas de cine pequeñas y medianas.
- Permitir al personal operativo gestionar la programación de funciones, así como el control, la configuración y la sincronización de los efectos asociados a cada experiencia inmersiva.
- Facilitar el seguimiento de actividades de mantenimiento relacionadas con la infraestructura inmersiva.
- Proporcionar a los responsables de las cadenas de cine una solución digital centralizada que simplifique la gestión de estas experiencias.
- Desarrollar una experiencia consistente entre el Landing Page y la Web Application, adaptable a distintos dispositivos.

### Restricciones que delimitan el alcance del proyecto

- El alcance académico comprende el desarrollo del Landing Page, la Web Application y el RESTful API que soportará el modelo de negocio de Kinemo. La fabricación física de butacas, actuadores u otros dispositivos de efectos inmersivos no forma parte de los entregables de software del proyecto.
- El Landing Page debe desarrollarse utilizando HTML5, CSS3 y JavaScript.
- La Web Application debe desarrollarse utilizando Vue Framework, HTML5, CSS3 y JavaScript, empleando PrimeVue para los componentes de interfaz.
- Los Web Services deben seguir el estilo arquitectónico RESTful API y desarrollarse utilizando ASP.NET Core, Entity Framework Core y C#.
- La solución debe contar con una interfaz web adaptable a las dimensiones de los dispositivos cliente.
- La Web Application debe integrarse con el RESTful API desarrollado por el equipo y acceder además a por lo menos un servicio externo de terceros.
- El desarrollo está limitado al periodo académico correspondiente al ciclo 2026-20.

#### 1.2.2. Lean UX Process

Para abordar el dominio del problema se aplicó el Lean UX Process, cuyo objetivo es validar de forma temprana y económica las creencias del equipo sobre el negocio, los usuarios y la solución antes de invertir en su construcción completa.

A continuación se presenta el Problem Statement consolidado del proyecto, los Assumptions identificados por categoría, los Hypothesis Statements derivados de los Feature Assumptions y, finalmente, el Lean UX Canvas que resume el proceso.

##### 1.2.2.1. Lean UX Problem Statements

El estado actual del mercado peruano de exhibición cinematográfica se encuentra concentrado principalmente en cadenas de mayor escala. En 2023, el mercado registró aproximadamente 45,9 millones de espectadores y S/485 millones en ingresos de taquilla, mientras que Cineplanet concentró el 56% de la recaudación, Cinemark el 19,5% y Cinestar el 9%.

Dentro de este contexto, las cadenas pequeñas y medianas cuentan con menores recursos económicos y técnicos para incorporar tecnologías de entretenimiento inmersivo, como butacas con movimiento y efectos físicos sincronizados.

Lo que los productos y servicios existentes no logran abordar adecuadamente es una alternativa accesible dirigida específicamente a cadenas de cine pequeñas y medianas que combine la gestión de funciones inmersivas, la configuración de efectos y el seguimiento del mantenimiento dentro de una solución digital centralizada.

Las soluciones actuales requieren inversiones elevadas, infraestructura especializada y personal técnico capacitado, lo que dificulta su adopción por organizaciones de menor escala.

Kinemo abordará esta brecha mediante una propuesta de entretenimiento inmersivo orientada a cadenas pequeñas y medianas, acompañada de una solución digital compuesta por un Landing Page, una Web Application y un RESTful API.

La aplicación permitirá centralizar procesos relacionados con la programación de funciones, la configuración de efectos y el seguimiento de actividades de mantenimiento, buscando simplificar la operación para el personal que no necesariamente cuenta con conocimientos técnicos especializados.

El enfoque inicial estará dirigido a cadenas de cine pequeñas y medianas que operan en el mercado peruano y que actualmente no cuenten con tecnologías de entretenimiento inmersivo, considerando como usuarios principales a los responsables de la toma de decisiones y al personal operativo/técnico de sus salas.

Las grandes cadenas que ya disponen de infraestructura inmersiva propia no forman parte del segmento inicial del proyecto.

Dentro del alcance académico, Kinemo se limita al desarrollo de los componentes de software Landing Page, Web Application y RESTful API, por lo que la fabricación física de butacas, actuadores y otros dispositivos de efectos inmersivos no forman parte de los entregables del proyecto.

La solución deberá cumplir con las tecnologías y condiciones establecidas por el curso, incluyendo una interfaz responsive, integración con el RESTful API desarrollado por el equipo y acceso a un servicio externo de terceros.

Sabremos que la propuesta es exitosa cuando los representantes de cadenas pequeñas y medianas logren identificar claramente la propuesta de valor de Kinemo y manifiesten intención de evaluar su contratación, mientras que el personal operativo y técnico logre completar satisfactoriamente los principales flujos de programación de funciones, configuración de efectos y seguimiento de mantenimiento mediante la Web Application.

A nivel del modelo de negocio, el éxito se evidenciará posteriormente mediante la adopción recurrente de estas funcionalidades y la continuidad del servicio por parte de las cadenas.

##### 1.2.2.2. Lean UX Assumptions

###### Business Assumptions

- Creemos que existe una oportunidad de mercado en cadenas de cine pequeñas y medianas del Perú que actualmente no cuentan con tecnología de entretenimiento inmersivo y que consideran demasiado elevada la inversión requerida por soluciones propietarias orientadas a grandes cadenas.
- Creemos que un modelo comercial que integre hardware, mantenimiento y software de gestión puede reducir la barrera de entrada frente a una compra tradicional de equipamiento, al distribuir el costo del servicio durante el tiempo de contratación.
- Creemos que las cadenas de cine pequeñas y medianas valorarán más una propuesta integral que incluya instalación, soporte técnico y software de gestión que la adquisición aislada de hardware inmersivo.
- Creemos que Kinemo puede generar ingresos recurrentes mediante contratos de mantenimiento, soporte técnico y acceso continuo a funcionalidades del software de gestión.
- Creemos que las cadenas estarán dispuestas a mantener contratos de mediano o largo plazo si perciben que la solución reduce el riesgo operativo, simplifica el mantenimiento y les permite ofrecer una experiencia diferenciada a sus espectadores.
- Creemos que Kinemo podrá escalar progresivamente su operación siempre que estandarice los procesos de instalación, mantenimiento y soporte para atender más de una sala sin requerir un equipo técnico exclusivo por cada complejo.

###### Business Outcome Assumptions

- Creemos que una mayor claridad en la propuesta de valor facilitará que los gerentes comprendan los beneficios de Kinemo y avancen hacia la contratación y uso de los servicios digitales ofrecidos.
- Creemos que una operación más centralizada permitirá reducir el tiempo dedicado por el personal técnico a coordinar manualmente la programación de funciones y el seguimiento de incidencias.
- Creemos que una gestión estructurada del mantenimiento contribuirá a reducir el tiempo de atención de incidencias y el periodo de inactividad de una sala cuando presente una falla.
- Creemos que una experiencia satisfactoria de uso del sistema aumentará la probabilidad de renovación de los contratos de mantenimiento y servicio.
- Creemos que la incorporación de funcionalidades adicionales, como analítica operativa y seguimiento del estado de salas, puede aumentar el valor percibido del servicio y el ingreso generado por cada sala contratada.

###### User Assumptions

- Creemos que los gerentes de operaciones y propietarios de cadenas de cine pequeñas y medianas son los principales responsables de evaluar la inversión, comparar proveedores y aprobar la contratación de nuevas tecnologías para sus salas.
- Creemos que estos gerentes necesitan comprender con claridad el costo, los beneficios, los requerimientos técnicos y el soporte incluido antes de considerar la adopción de una solución inmersiva.
- Creemos que el personal operativo y técnico es responsable de actividades como programación de funciones, supervisión de sala, configuración de equipos y reporte de incidencias.
- Creemos que parte del personal operativo no cuenta con conocimientos especializados en sistemas de entretenimiento inmersivo y necesita una herramienta fácil de aprender y utilizar.

###### User Outcome and Benefit Assumptions

- Creemos que los gerentes desean diferenciar la oferta de sus cines frente a cadenas de mayor escala sin asumir una inversión inicial que comprometa significativamente su presupuesto.
- Creemos que los gerentes necesitan reducir la incertidumbre asociada a la adopción de nueva tecnología mediante información clara sobre soporte, mantenimiento y funcionamiento del servicio.
- Creemos que el personal operativo desea programar funciones y configurar los efectos asociados sin depender constantemente de especialistas externos.
- Creemos que el personal técnico desea registrar, consultar y dar seguimiento a incidencias desde un único sistema, evitando depender de comunicaciones dispersas por llamadas, mensajes u otros medios.
- Creemos que el personal operativo se beneficiará de una interfaz simple que reduzca el tiempo necesario para realizar tareas frecuentes de programación y supervisión.

###### Feature Assumptions

- Creemos que un panel de administración web que permita crear, consultar y modificar la programación de funciones ayudará al personal operativo a gestionar las actividades diarias de la sala desde un único sistema.
- Creemos que una funcionalidad para asignar y configurar perfiles de efectos por película o función reducirá la necesidad de realizar configuraciones manuales repetitivas.
- Creemos que un mecanismo de sincronización entre el contenido audiovisual y los efectos físicos permitirá ejecutar de forma coordinada movimientos de butacas, viento, vibración y otros efectos definidos para cada experiencia.
- Creemos que un módulo de mantenimiento permitirá registrar incidencias, consultar su estado y dar seguimiento a actividades preventivas y correctivas de cada sala.
- Creemos que un dashboard con indicadores sobre uso, funcionamiento e incidencias permitirá a los responsables de la cadena supervisar el estado general de sus salas.
- Creemos que una experiencia responsive permitirá que gerentes y personal operativo accedan a las principales funcionalidades desde distintos dispositivos.

##### 1.2.2.3. Lean UX Hypothesis Statements

#### H1 - Gestión de programación de funciones

Creemos que lograremos reducir el tiempo dedicado a la coordinación manual de la programación de funciones si el personal operativo y técnico de las salas de cine logra gestionar las actividades diarias de programación desde un único sistema, mediante un panel de administración web que permita crear, consultar y modificar la programación de funciones.

#### H2 - Configuración de perfiles de efectos

Creemos que lograremos reducir el tiempo dedicado a tareas operativas repetitivas si el personal operativo de las salas de cine logra configurar los efectos asociados a cada función sin depender constantemente de especialistas externos, mediante una funcionalidad que permita asignar y configurar perfiles de efectos por película o función.

#### H3 - Sincronización de efectos inmersivos

Creemos que lograremos mejorar la eficiencia de la operación de las experiencias inmersivas si el personal operativo y técnico logra ejecutar los efectos físicos de forma coordinada con el contenido audiovisual, mediante un mecanismo de sincronización entre el contenido audiovisual y los movimientos de butacas, viento, vibración y otros efectos configurados.

#### H4 - Gestión de mantenimiento

Creemos que lograremos reducir el tiempo de atención de incidencias y los periodos de inactividad de las salas si el personal técnico y operativo logra registrar, consultar y dar seguimiento a las incidencias desde un único sistema, mediante un módulo de gestión de mantenimiento preventivo y correctivo.

#### H5 - Dashboard de supervisión

Creemos que lograremos aumentar el valor percibido del servicio y facilitar una gestión más centralizada de las salas si los gerentes de operaciones y responsables de las cadenas de cine logran supervisar el funcionamiento y estado de sus salas con información centralizada, mediante un dashboard con indicadores de uso, funcionamiento e incidencias.

#### H6 - Experiencia responsive

Creemos que lograremos mejorar la experiencia de uso del sistema y aumentar la probabilidad de continuidad en el uso del servicio si los gerentes y el personal operativo logran acceder y realizar sus principales tareas desde distintos dispositivos, mediante una Web Application responsive adaptada a diferentes dimensiones de pantalla.

#### 1.2.2.4. Lean UX Canvas

| Bloque | Contenido |
|---|---|
| **1. Business Problem** | Las cadenas de cine pequeñas y medianas del Perú presentan dificultades para incorporar experiencias de entretenimiento inmersivo debido al elevado costo de las soluciones existentes, la necesidad de conocimientos técnicos especializados y la falta de herramientas digitales centralizadas para gestionar su operación. Esta situación limita su capacidad para modernizar sus salas y diferenciarse frente a cadenas de mayor escala. |
| **2. Business Outcomes** | Reducir el tiempo dedicado a la coordinación manual de la programación de funciones; reducir el tiempo de atención de incidencias y los periodos de inactividad de las salas; mejorar la eficiencia de la operación de experiencias inmersivas; aumentar el valor percibido del servicio; y favorecer la continuidad en el uso y renovación del servicio. |
| **3. Users** | Gerentes de operaciones y propietarios de cadenas de cine pequeñas y medianas. Personal operativo y técnico responsable de la programación, configuración, supervisión y mantenimiento de las salas. |
| **4. User Outcomes & Benefits** | Los gerentes buscan diferenciar la oferta de sus cines sin asumir una inversión inicial elevada y reducir la incertidumbre asociada a la adopción de tecnología inmersiva. El personal operativo y técnico busca gestionar la programación, configuración de efectos y mantenimiento desde un único sistema, reduciendo tareas manuales y la dependencia constante de especialistas externos. |
| **5. Solutions** | Panel de administración web para gestionar la programación de funciones; funcionalidad para asignar y configurar perfiles de efectos; mecanismo de sincronización entre contenido audiovisual y efectos físicos; módulo de mantenimiento preventivo y correctivo; dashboard de supervisión del estado de las salas; Web Application responsive y Landing Page integrado con la experiencia web. |
| **6. Hypotheses** | H1 - Gestión de programación de funciones; H2 - Configuración de perfiles de efectos; H3 - Sincronización de efectos inmersivos; H4 - Gestión de mantenimiento; H5 - Dashboard de supervisión; H6 - Experiencia responsive. |
| **7. What's the most important thing we need to learn first?** | Si las cadenas de cine pequeñas y medianas consideran que una solución que centralice programación, configuración de efectos y mantenimiento puede reducir la complejidad operativa y facilitar la adopción de experiencias inmersivas. |
| **8. What's the least amount of work we need to do to learn the next most important thing?** | Validar inicialmente con representantes de los segmentos objetivo un prototipo de baja fidelidad de los principales flujos de la Web Application y del Landing Page, para evaluar si la propuesta resulta comprensible, útil y adecuada para sus necesidades operativas y de gestión. |

### 1.3. Segmentos objetivo

El proyecto Kinemo considera dos segmentos objetivo principales dentro del mercado de exhibición cinematográfica: los responsables de la toma de decisiones en cadenas de cine pequeñas y medianas, y el personal operativo/técnico encargado de la gestión diaria de las salas. La selección de ambos segmentos responde a su participación directa en la adopción, gestión y operación de soluciones de entretenimiento inmersivo.

En 2023, el mercado peruano de exhibición cinematográfica registró aproximadamente 45,9 millones de espectadores y S/485 millones en ingresos de taquilla. Cineplanet concentró el 56% de la recaudación total, Cinemark el 19,5% y Cinestar el 9%, evidenciando una concentración importante del mercado en las principales cadenas. Este contexto permite identificar oportunidades para cadenas de menor escala que buscan modernizar y diferenciar su oferta.

#### Segmento 1: Gerentes de Operaciones / Propietarios de cadenas de cine pequeñas y medianas

Este segmento está conformado por las personas responsables de evaluar inversiones, seleccionar proveedores y tomar decisiones relacionadas con la incorporación de nuevas tecnologías en cadenas de cine pequeñas y medianas.

##### Perfil empresarial

- Responsables de cadenas de cine pequeñas y medianas que operan en el mercado peruano.
- Organizaciones con menor participación de mercado y menor capacidad de inversión que las principales cadenas del sector.
- Cadenas que actualmente no cuentan con infraestructura de entretenimiento inmersivo o cuya incorporación representa una inversión elevada.

##### Perfil demográfico

- Edad aproximada: 35–55 años.
- Rol: Gerente General, Gerente de Operaciones o Propietario/Socio de la cadena.
- Ubicación: principalmente Lima Metropolitana y otras ciudades donde operen los complejos de la cadena.

Las características demográficas específicas, así como las motivaciones, frustraciones, objetivos y comportamientos de este segmento, serán contrastadas posteriormente mediante las entrevistas y el análisis correspondiente del Capítulo II.

#### Segmento 2: Personal Operativo / Técnico de las salas de cine

Este segmento está conformado por los trabajadores responsables de las actividades operativas y técnicas necesarias para el funcionamiento cotidiano de las salas de cine.

##### Perfil laboral

- Personal encargado de la operación cotidiana de las salas.
- Participa en tareas como programación de funciones, supervisión de salas, configuración de equipos y seguimiento de incidencias.
- Incluye roles como jefe de sala, coordinador de operaciones, técnico de mantenimiento o proyeccionista.

##### Perfil demográfico

- Edad aproximada: 20–40 años.
- Ubicación: trabajan principalmente en los complejos de cine donde realizan sus actividades operativas.

Las características demográficas, tecnológicas, laborales y de comportamiento de este segmento serán validadas posteriormente mediante las entrevistas y el análisis estadístico realizado en el Capítulo II.

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

Para el análisis de competencia se identificaron tres competidores indirectos con ofertas parcialmente similares al modelo de negocio de Kinemo. Se consideran indirectos debido a que ofrecen tecnologías de entretenimiento inmersivo para salas de cine, como butacas con movimiento y efectos físicos sincronizados, pero presentan diferencias respecto al segmento objetivo, alcance del servicio y propuesta digital planteada por Kinemo. Estas diferencias serán desarrolladas posteriormente en el análisis competitivo.

- **Competidor 1: 4DX (CJ 4DPLEX)**

  Proveedor de tecnología de entretenimiento cinematográfico inmersivo que integra movimiento de butacas y efectos físicos sincronizados con el contenido audiovisual.

- **Competidor 2: Lumma (4D E-Motion)**

  Empresa especializada en soluciones de entretenimiento cinematográfico inmersivo que integra butacas con movimiento y efectos físicos sincronizados, como viento, agua, vibración y aromas, con el objetivo de enriquecer la experiencia audiovisual.

- **Competidor 3: MediaMation (MX4D)**

  Proveedor de soluciones de entretenimiento inmersivo para salas de cine que integra movimiento de butacas y distintos efectos físicos dentro de la experiencia cinematográfica.

#### 2.1.1. Análisis competitivo

##### ¿Por qué llevar a cabo este análisis?

Buscamos comprender cómo los proveedores actuales de tecnología de entretenimiento inmersivo para salas de cine abordan las necesidades del mercado y compararlos con la propuesta de Kinemo, con el objetivo de identificar oportunidades de diferenciación para cadenas de cine pequeñas y medianas.

| Aspecto | Kinemo | 4DX (CJ 4DPLEX) | Lumma (4D E-Motion) | MediaMation (MX4D) |
|---|---|---|---|---|
| **Overview** | Startup orientada a cadenas de cine pequeñas y medianas que propone una solución integral de entretenimiento inmersivo basada en butacas con movimiento, efectos físicos sincronizados, mantenimiento especializado y una plataforma web para la programación, configuración, supervisión y gestión de las salas. | Proveedor internacional de tecnología cinematográfica inmersiva. Su formato 4DX combina butacas con movimiento y efectos ambientales sincronizados con el contenido audiovisual. | Empresa dedicada al desarrollo de tecnologías para entretenimiento. Su solución 4D E-Motion integra butacas con movimiento y efectos como viento, agua, vibración, aromas y aire sincronizados con la película. | Empresa especializada en tecnología 4D/5D para cines y atracciones. MX4D integra butacas con movimiento, efectos físicos y sistemas de control para experiencias inmersivas. |
| **Ventaja competitiva** | Enfoque específico en cadenas pequeñas y medianas, combinando una propuesta de entretenimiento inmersivo con mantenimiento especializado y una solución digital centralizada para la gestión operativa. | Amplia presencia internacional, reconocimiento de marca y experiencia trabajando con operadores cinematográficos de diferentes mercados. | Desarrollo de tecnología propia de movimiento y efectos, junto con capacidad para realizar proyectos personalizados. | Experiencia en integración de sistemas completos y disponibilidad de soluciones que incluyen butacas, efectos, software, instalación y soporte. |
| **¿Qué valor ofrece a los clientes?** | Facilita la adopción y gestión de experiencias inmersivas mediante herramientas centralizadas para programación, efectos, mantenimiento y supervisión. | Permite a los exhibidores ofrecer una experiencia multisensorial mediante movimientos y efectos ambientales coordinados con la película. | Permite transformar una función convencional en una experiencia multisensorial mediante movimiento y distintos efectos físicos sincronizados. | Permite implementar una experiencia cinematográfica inmersiva mediante un paquete integrado de movimiento, efectos, sistemas audiovisuales y control. |
| **Mercado objetivo** | Cadenas de cine pequeñas y medianas del mercado peruano que buscan incorporar experiencias inmersivas. | Operadores y cadenas cinematográficas interesadas en incorporar formatos premium e inmersivos. | Cines, centros de entretenimiento y organizaciones interesadas en soluciones audiovisuales e inmersivas. | Cines, atracciones y otros espacios de entretenimiento que requieren soluciones 4D/5D integradas. |
| **Estrategias de marketing** | Comunicación B2B enfocada en accesibilidad, facilidad de gestión, soporte y diferenciación de las cadenas pequeñas y medianas. | Promoción de la marca 4DX mediante alianzas con exhibidores, contenidos cinematográficos y presencia internacional. | Presentación de 4D E-Motion y proyectos personalizados como soluciones para potenciar experiencias audiovisuales. | Promoción de soluciones integrales y casos de implementación de MX4D en cines y espacios de entretenimiento. |
| **Productos & Servicios** | Butacas con movimiento, efectos físicos sincronizados, mantenimiento especializado y software propio de gestión, programación, sincronización, mantenimiento y analítica. | Sistema 4DX con motion seats y efectos como viento, agua, niebla, nieve, aromas, vibraciones y otros efectos ambientales. | Sistema 4D E-Motion con butacas móviles y efectos como aire, vibración, aromas, agua, viento e iluminación; además de proyectos personalizados y producción audiovisual. | MX4D Motion EFX Seats, efectos ambientales, audio, proyección, pantallas, instalación, mantenimiento y software ShowFlow/VidShow. |
| **Precios & Costos** | Modelo comercial orientado a reducir la barrera de inversión inicial. Los precios específicos se definirán posteriormente como parte del modelo de negocio. | No se identifican precios públicos estandarizados para instalaciones completas; las condiciones dependen del proyecto y del operador. | No se identifican precios públicos estandarizados en su página oficial; las soluciones se configuran según el proyecto. | No se muestran precios estandarizados para sus paquetes de salas; la configuración depende de las necesidades de cada proyecto. |
| **Canales de distribución (Web y/o Móvil)** | Landing Page y Web Application responsive como canales digitales principales de interacción con los segmentos objetivo. | Sitio web corporativo y presencia digital asociada a 4DX y a los exhibidores que utilizan el formato. | Sitio web corporativo para presentar 4D E-Motion, servicios y proyectos. | Sitio web corporativo con información sobre MX4D, productos, servicios, soporte y soluciones. |

##### Análisis SWOT

| Empresa | Fortalezas | Debilidades | Oportunidades | Amenazas |
|---|---|---|---|---|
| **Kinemo** | Enfoque específico en cadenas pequeñas y medianas; solución digital centralizada; integración de programación, efectos, mantenimiento y supervisión. | Startup nueva sin trayectoria comprobada; capacidad operativa y soporte todavía en desarrollo; recursos inferiores a empresas internacionales consolidadas. | Atender cadenas pequeñas y medianas que busquen diferenciarse; crecimiento en el mercado peruano y posterior expansión regional. | Entrada de proveedores internacionales al mismo segmento; resistencia de potenciales clientes frente a la inversión en nuevas tecnologías; dificultades asociadas a infraestructura y equipamiento. |
| **4DX (CJ 4DPLEX)** | Reconocimiento internacional; tecnología multisensorial consolidada; amplia variedad de efectos; presencia junto a operadores cinematográficos internacionales. | Su escala y características pueden implicar una solución más compleja para operadores pequeños; menor enfoque específico en cadenas pequeñas y medianas del mercado peruano. | Continuar expandiendo sus formatos inmersivos hacia nuevos exhibidores y mercados. | Aparición de proveedores con soluciones más simples, flexibles o adaptadas a mercados locales. |
| **Lumma (4D E-Motion)** | Tecnología propia de movimiento y efectos; variedad de efectos físicos; capacidad de desarrollar proyectos personalizados. | Menor reconocimiento global frente a marcas como 4DX; información pública limitada sobre precios y herramientas de gestión operativa para cadenas de cine. | Expansión de 4D E-Motion hacia nuevos mercados y desarrollo de proyectos personalizados para diferentes tipos de operadores. | Competencia de proveedores internacionales de formatos inmersivos y aparición de soluciones regionales con servicios digitales complementarios. |
| **MediaMation (MX4D)** | Oferta integral de hardware, efectos, software, instalación, mantenimiento y soporte; experiencia internacional en tecnología 4D/5D. | Su propuesta incluye una infraestructura amplia que puede resultar más compleja para organizaciones de menor escala; no está orientada exclusivamente al segmento peruano de cadenas pequeñas y medianas. | Expansión hacia nuevos mercados y adaptación de sus soluciones a distintos tamaños y tipos de recintos. | Competencia de proveedores globales y regionales que desarrollen soluciones de menor complejidad o más adaptadas a necesidades locales. |

#### 2.1.2. Estrategias y tácticas frente a competidores

- **Frente al reconocimiento internacional y presencia consolidada de 4DX:** Kinemo se enfocará en cadenas de cine pequeñas y medianas del mercado peruano, ofreciendo una propuesta más cercana y adaptada a sus necesidades operativas. La estrategia será diferenciarse mediante atención personalizada, menor complejidad de adopción y una solución digital centralizada para la gestión de experiencias inmersivas.

- **Frente a la tecnología propia y capacidad de personalización de Lumma:** Kinemo buscará diferenciarse incorporando, además de la experiencia inmersiva basada en butacas y efectos físicos, una Web Application que centralice la programación de funciones, configuración de efectos, seguimiento de mantenimiento y supervisión de las salas.

- **Frente a la oferta integral de MediaMation (MX4D):** Kinemo se posicionará como una alternativa orientada específicamente a cadenas pequeñas y medianas, priorizando una solución de menor complejidad operativa y adaptada al contexto regional. Como táctica, se ofrecerán funcionalidades como dashboard de supervisión, gestión de incidencias y programación de funciones dentro de una misma plataforma.

- **Táctica general de precios:** Kinemo plantea un modelo comercial orientado a reducir la barrera de inversión inicial mediante contratos de servicio o suscripciones, evitando depender únicamente de una venta directa de equipamiento. Los precios específicos serán definidos posteriormente de acuerdo con el modelo financiero del negocio.

- **Táctica de posicionamiento regional:** Kinemo buscará desarrollar presencia inicialmente en el mercado peruano y fortalecer su propuesta para cadenas pequeñas y medianas antes de considerar una expansión regional, aprovechando el conocimiento del contexto local y las necesidades específicas del segmento.

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

Se diseñaron dos guías de entrevista, una por cada segmento objetivo identificado: (1) Gerentes de operaciones/propietarios de cadenas de cine pequeñas y medianas, y (2) Personal operativo/técnico de las salas de cine. Ambas guías buscan recolectar información relevante para la construcción de los User Persona, considerando datos de perfil y experiencia, así como características relacionadas con la forma de trabajo, habilidades, marcas e influencias, dispositivos de preferencia, canales digitales de interacción, objetivos, frustraciones y background de los entrevistados.

##### Guía de entrevista - Segmento: Gerentes/Propietarios de cadenas de cine pequeñas y medianas

**Objetivo de la entrevista:** Comprender el perfil, experiencia, objetivos, frustraciones y procesos de toma de decisiones de los gerentes o propietarios, así como su relación con la adopción de nuevas tecnologías en sus salas.

**Preguntas**

1. ¿Cuál es su nombre, edad, cargo, distrito donde reside y hace cuánto tiempo trabaja en este rubro?
2. ¿Podría contarme brevemente sobre su experiencia profesional y cómo llegó a su cargo actual?
3. ¿Cómo describiría su forma de trabajar y qué habilidades considera más importantes para desempeñar su cargo?
4. ¿Qué objetivos busca alcanzar actualmente en la gestión de sus salas y qué situaciones suelen generarle mayor frustración?
5. ¿Qué marcas de dispositivos como celular o laptop utiliza con mayor frecuencia para realizar sus actividades laborales? ¿Y qué navegador web utiliza habitualmente?
6. ¿Qué canales digitales, marcas, empresas o referentes consulta para informarse sobre nuevas tecnologías o tendencias del sector?
7. ¿Cómo es actualmente el proceso mediante el cual evalúa y decide invertir en una nueva tecnología para sus salas?
8. ¿Qué factores considera más importantes antes de adoptar una nueva tecnología, por ejemplo, costo, mantenimiento, soporte o facilidad de uso?
9. ¿Qué opina sobre las experiencias de cine inmersivo y qué podría motivarlo o dificultarle incorporarlas en sus salas?

**Cierre**

10. ¿Hay algo adicional sobre sus necesidades, objetivos o dificultades que considere importante mencionar?

##### Guía de entrevista - Segmento: Personal operativo/técnico de las salas de cine

**Objetivo de la entrevista:** Comprender el perfil, experiencia, habilidades, objetivos, frustraciones y actividades cotidianas del personal operativo y técnico, así como las herramientas y tecnologías que utiliza.

**Preguntas**

1. ¿Cuál es su nombre, edad, cargo, distrito donde reside y hace cuánto tiempo trabaja en este sector?
2. ¿Cuál es su formación o experiencia técnica y cómo describiría su forma de trabajar?
3. ¿Cuáles son sus principales tareas durante un día típico en la sala de cine?
4. ¿Qué marcas de dispositivos como celular o laptop utiliza con mayor frecuencia para realizar sus actividades laborales? ¿Y qué navegador web utiliza habitualmente?
5. ¿Qué canales utiliza para comunicarse con supervisores, compañeros o proveedores cuando necesita coordinar actividades o reportar una incidencia?
6. ¿Qué marcas, páginas, canales o personas consulta cuando necesita aprender sobre tecnología o resolver algún problema técnico?
7. ¿Qué tareas le resultan más difíciles o le generan mayor frustración durante su jornada?
8. ¿Qué habilidades considera que son sus principales fortalezas y qué le gustaría mejorar profesionalmente?
9. Cuando ocurre una falla en algún equipo, ¿qué procedimiento sigue normalmente y en qué casos necesita ayuda externa?

**Cierre**

10. ¿Hay algo adicional sobre su trabajo, necesidades o dificultades que considere importante mencionar?

#### 2.2.2. Registro de entrevistas

##### Segmento 1: Gerentes/Propietarios de cadenas de cine pequeñas y medianas

###### Entrevista N°1

**Datos del entrevistado:**

- **Nombre:** Johan
- **Apellido:** Contreras Granados
- **Edad:** 38
- **Distrito:** San Isidro
- **URL:** (Inicio: || Fin:)

**Resumen:**

El entrevistado es gerente de operaciones de una cadena de cines pequeña y cuenta con aproximadamente 10 años de experiencia en el rubro. Se considera una persona organizada, práctica y orientada a resultados. Busca mejorar la experiencia del cliente, diferenciar sus salas y reducir problemas durante las funciones, aunque le preocupan las fallas técnicas, los altos costos de mantenimiento y la demora del soporte.

Utiliza una laptop Lenovo, un iPhone y Google Chrome, y se informa mediante Google, YouTube, LinkedIn, páginas de proveedores, correo y WhatsApp. Al evaluar nuevas tecnologías considera principalmente el costo, mantenimiento, facilidad de uso, soporte técnico y recuperación de la inversión.

Considera atractivas las experiencias de cine inmersivo, pero identifica como principales barreras el costo inicial, el mantenimiento y la capacitación del personal.

###### Entrevista N°2

**Datos del entrevistado:**

- **Nombre:** Alexis
- **Apellido:**
- **Edad:** 36
- **Distrito:**
- **URL:** (Inicio: || Fin:)

**Resumen:**

El entrevistado es propietario y administrador de una pequeña cadena de cines, tiene 30 años y cuenta con aproximadamente 5 años de experiencia en el rubro. Se describe como una persona analítica, ordenada y cuidadosa con los gastos, orientada a planificar y tomar decisiones según el presupuesto disponible.

Su principal objetivo es aumentar la cantidad de clientes y modernizar las salas sin realizar inversiones excesivas, mientras que sus principales frustraciones son los costos inesperados, las fallas de equipos y la demora en conseguir repuestos o soporte técnico.

Utiliza principalmente una computadora Dell, un iPhone y Google Chrome, y se informa mediante Google, páginas oficiales de fabricantes, proveedores y recomendaciones de otros administradores.

Para invertir en nueva tecnología compara cotizaciones, costos, beneficios, mantenimiento y referencias. Considera atractivas las experiencias de cine inmersivo, aunque le preocupa especialmente el costo inicial y la recuperación de la inversión, por lo que prefiere soluciones que puedan implementarse por etapas y con costos claros desde el inicio.

###### Entrevista N°3

**Datos del entrevistado:**

- **Nombre:**
- **Apellido:**
- **Edad:**
- **Distrito:**
- **URL:** (Inicio: || Fin:)

**Resumen:**

El entrevistado tiene 38 años, vive en Miraflores y se desempeña como gerente general de una pequeña cadena de cines, con aproximadamente 5 años de experiencia en el rubro.

Se considera una persona analítica, organizada y prudente, enfocada en la planificación, negociación y priorización de inversiones. Sus principales objetivos son aumentar la asistencia, mejorar la experiencia del cliente y controlar los costos operativos, mientras que le frustran las propuestas que no se ajustan al presupuesto o no muestran beneficios claros.

Utiliza una MacBook Air, un iPhone y Safari, y se informa mediante YouTube, páginas de proveedores, ferias, demostraciones y casos de otros cines.

Para invertir en nueva tecnología evalúa la necesidad, compara propuestas y analiza su impacto económico. Considera importantes el retorno de inversión, la confiabilidad del proveedor, el mantenimiento y la facilidad de implementación.

Ve las experiencias inmersivas como una oportunidad para atraer nuevos públicos, aunque identifica como barreras el costo inicial y los cambios de infraestructura, por lo que prefiere probar primero la tecnología en una sola sala antes de ampliarla.

##### Segmento 2: Personal operativo/técnico de las salas de cine

###### Entrevista N°1

**Datos del entrevistado:**

- **Nombre:** Miguel
- **Apellido:** Málaga Gómez
- **Edad:** 23
- **Distrito:** Miraflores
- **URL:** (Inicio: || Fin:)

**Resumen:**

El entrevistado tiene 23 años, vive en Ate y trabaja como técnico de sala y soporte operativo, con aproximadamente 2 años de experiencia en cines.

Cuenta con formación técnica en electrónica y mantenimiento de equipos y se considera una persona práctica, responsable y atenta a los detalles. Sus principales tareas son revisar los equipos de proyección y sonido, verificar que las salas estén operativas y atender incidencias técnicas.

Utiliza un celular Samsung, una laptop HP y Google Chrome, y se comunica principalmente mediante WhatsApp, llamadas telefónicas y correo electrónico. Para resolver problemas consulta Google, YouTube, manuales de fabricantes y a su supervisor.

Sus principales dificultades son las fallas antes o durante las funciones, la falta de repuestos y la demora del soporte externo. Destaca como fortalezas la resolución de problemas, la rapidez de reacción y el trabajo bajo presión, y busca capacitarse en nuevas tecnologías de proyección y sistemas inmersivos, además de contar con mejores herramientas de diagnóstico y soporte técnico más rápido.

###### Entrevista N°2

**Datos del entrevistado:**

- **Nombre:**
- **Apellido:**
- **Edad:**
- **Distrito:**
- **URL:** (Inicio: || Fin:)

**Resumen:**

El entrevistado tiene 26 años y trabaja como encargado técnico de sala, con aproximadamente 3 años de experiencia en cines.

Cuenta con experiencia en mantenimiento de equipos audiovisuales y soporte técnico y se describe como una persona metódica, paciente y cuidadosa. Sus principales tareas son realizar revisiones preventivas, comprobar que las salas estén operativas y llevar el registro de mantenimiento.

Utiliza una laptop Lenovo, un Samsung Galaxy y Google Chrome, y se comunica principalmente mediante WhatsApp y correo electrónico. Para resolver problemas consulta Google, YouTube, páginas oficiales de fabricantes y compañeros con mayor experiencia.

Sus principales dificultades son coordinar mantenimientos sin interrumpir la programación y trabajar con equipos antiguos que requieren revisiones frecuentes.

Destaca por su organización, mantenimiento preventivo y seguimiento de procedimientos, y busca capacitarse en equipos audiovisuales modernos y planificación de mantenimiento, además de contar con mejores herramientas de diagnóstico.

###### Entrevista N°3

**Datos del entrevistado:**

- **Nombre:**
- **Apellido:**
- **Edad:**
- **Distrito:**
- **URL:** (Inicio: || Fin:)

**Resumen:**

El entrevistado tiene 27 años y trabaja como asistente de operaciones técnicas, con aproximadamente 4 años de experiencia en salas de cine.

Cuenta con formación técnica en sistemas y soporte informático y se considera una persona rápida y adaptable. Sus principales tareas incluyen revisar los sistemas de proyección, audio y control, realizar configuraciones y actualizaciones, y registrar incidencias.

Utiliza una laptop HP, un iPhone y Google Chrome, y se comunica principalmente mediante WhatsApp, apoyándose en fotos, capturas y videos para explicar problemas técnicos.

Para resolver incidencias consulta YouTube, comunidades técnicas y documentación en línea. Sus principales frustraciones aparecen cuando las fallas son difíciles de identificar o se presentan varias incidencias simultáneamente.

Destaca por su adaptación rápida, manejo de sistemas y resolución de problemas, y busca mejorar sus conocimientos en redes, automatización y equipos especializados. Además, considera necesario contar con mejores registros de mantenimiento y revisiones anticipadas para evitar interrupciones.

#### 2.2.3. Análisis de entrevistas

##### Segmento 1: Gerentes/Propietarios de cadenas de cine pequeñas y medianas

A partir de las 3 entrevistas realizadas, se identificó que el 100% de los entrevistados ocupa cargos de gestión y presenta características relacionadas con la organización y planificación. El 66.7% se considera analítico al momento de tomar decisiones. Sus principales objetivos se relacionan con mejorar la experiencia del cliente, atraer mayor público, modernizar o diferenciar las salas y mantener controlados los costos.

Respecto a la tecnología, el 100% utiliza iPhone, por lo que emplea iOS en sus dispositivos móviles. En computadoras, el 66.7% utiliza Windows y el 33.3% macOS. Asimismo, el 66.7% usa Google Chrome y el 33.3% Safari. Para informarse sobre nuevas tecnologías, el 100% consulta fabricantes o proveedores, mientras que el 66.7% utiliza Google y YouTube.

En cuanto a la adopción de nuevas tecnologías, el 100% considera relevante el costo y el impacto económico de la inversión. Además, el 100% considera atractivas las experiencias de cine inmersivo, aunque todos identifican el costo inicial como una barrera importante. Finalmente, el 66.7% muestra preferencia por implementar nuevas tecnologías de forma progresiva o mediante pruebas iniciales para reducir el riesgo de inversión.

##### Segmento 2: Personal operativo/técnico de las salas de cine

A partir de las 3 entrevistas realizadas, se identificó que el 100% cuenta con experiencia técnica relacionada con mantenimiento, sistemas o soporte, y realiza actividades vinculadas con la revisión de equipos y atención de incidencias. Asimismo, el 100% presenta características asociadas con la resolución o prevención de problemas técnicos. Sus principales dificultades están relacionadas con fallas de equipos, mantenimiento e interrupciones que pueden afectar las funciones.

Respecto a la tecnología, el 100% utiliza laptop para sus actividades laborales y Google Chrome como navegador. En computadoras, el 100% utiliza equipos asociados a Windows, como HP o Lenovo. En dispositivos móviles, el 66.7% utiliza Samsung con Android y el 33.3% utiliza iPhone con iOS.

Además, el 100% utiliza WhatsApp para la comunicación laboral y el 100% consulta YouTube para buscar información o resolver problemas técnicos, mientras que el 66.7% también utiliza Google.

En cuanto a sus necesidades profesionales, el 100% muestra interés en ampliar sus conocimientos sobre nuevas tecnologías o equipos especializados. Asimismo, el 66.7% menciona directamente la necesidad de contar con mejores herramientas de diagnóstico.

También se identifican necesidades relacionadas con mejorar los registros, la planificación del mantenimiento y el acceso a soporte técnico. En general, el segmento presenta un perfil técnico y orientado a la resolución de incidencias y prevención de fallas.

## 2.3. Needfinding

A partir de la información recopilada de los segmentos objetivo y de los resultados obtenidos en las entrevistas, se realizó el proceso de Needfinding mediante la elaboración de los User Personas, User Task Matrix, User Journey Maps y Empathy Maps. Estos artefactos permiten representar las características, actividades, objetivos, necesidades y dificultades identificadas en cada segmento y sirven como base para la definición de los requisitos de Kinemo.

## 2.3. Needfinding

A partir de la información recopilada de los segmentos objetivo y de los resultados obtenidos en las entrevistas, se realizó el proceso de Needfinding mediante la elaboración de los User Personas, User Task Matrix, User Journey Maps y Empathy Maps. Estos artefactos permiten representar las características, actividades, objetivos, necesidades y dificultades identificadas en cada segmento y sirven como base para la definición de los requisitos de Kinemo.

### 2.3.1. User Personas

**User persona 1 (Personal operativo/técnico de las salas de cine):** La ficha de Carlos Torres representa al personal encargado de las actividades técnicas y operativas de las salas de cine. El arquetipo refleja un perfil orientado a la resolución de problemas, mantenimiento preventivo y atención de incidencias. Sus principales objetivos son mantener los equipos operativos, detectar fallas con rapidez y mejorar el seguimiento del mantenimiento. Entre sus principales dificultades se encuentran las fallas durante las funciones, la demora del soporte técnico, la falta de repuestos y la necesidad de contar con mejores herramientas de diagnóstico y registro.

<img src="Kinemo-report/assets/img/2_3_1-User-personas/Carlos%20Torres.png" alt="Carlos Torres">

**User persona 2 (Gerentes/Propietarios de cadenas de cine pequeñas y medianas):** La ficha de Pepe Castillo representa al responsable de la toma de decisiones dentro de una cadena de cine pequeña o mediana. El arquetipo refleja un perfil organizado y analítico, orientado a evaluar inversiones, comparar proveedores y modernizar las salas sin asumir riesgos económicos excesivos. Entre sus principales objetivos se encuentran mejorar la experiencia del cliente, atraer mayor público y diferenciar la oferta de sus salas. Sus principales frustraciones están relacionadas con los altos costos de implementación, el mantenimiento, la disponibilidad de soporte técnico y la incertidumbre sobre el retorno de inversión.

<img src="Kinemo-report/assets/img/2_3_1-User-personas/Pepe%20Castillo.png" alt="Pepe Castillo">

Link de UXPressia: https://uxpressia.com/w/v8FzI/p/CvSDi?tagId=9BZKW

### 2.3.2. User Task Matrix

La siguiente User Task Matrix presenta las principales tareas realizadas por los dos User Personas identificados: Pepe Castillo, representante del segmento de Gerentes/Propietarios de cadenas de cine pequeñas y medianas, y Carlos Torres, representante del Personal operativo/técnico de las salas de cine. Las tareas se definieron a partir de los hallazgos obtenidos en las entrevistas y representan actividades que actualmente realizan los usuarios para cumplir sus objetivos, independientemente de la existencia de Kinemo. Cada tarea se evalúa según su frecuencia de realización y su nivel de importancia para cada User Persona.

<img src="Kinemo-report/assets/img/2_3_2-User-task-matrix/User%20Task%20Matrix.png" alt="User Task Matrix">

Link del Task Matrix: https://uxpressia.com/w/v8FzI/p/HWL53

### 2.3.3. User Journey Mapping

En esta sección se presentan los User Journey Maps correspondientes a los dos User Personas identificados. Cada mapa representa el recorrido actual As-Is de los usuarios, mostrando las actividades que realizan para alcanzar sus objetivos antes de la implementación de Kinemo. Los recorridos permiten identificar los principales puntos de contacto, dificultades, decisiones y oportunidades de mejora observadas durante las entrevistas.

**Segmento objetivo 1: Gerentes/Propietarios de cadenas de cine pequeñas y medianas:**

El User Journey Map de Pepe Castillo representa el proceso actual de evaluación y adopción de nuevas tecnologías por parte de un gerente o propietario de una cadena de cine pequeña o mediana. El recorrido abarca desde la identificación de una necesidad de modernización hasta el seguimiento posterior de la inversión.

<img src="Kinemo-report/assets/img/2_3_3-User-journey-mapping/User%20Journey%20Map%20-%20Pepe%20Castillo.png" alt="User Journey Map - Pepe Castillo">

**Segmento objetivo 2: Personal operativo/técnico de las salas de cine:**

El User Journey Map de Carlos Torres representa el recorrido cotidiano del personal técnico, desde la preparación de la jornada y revisión preventiva de los equipos hasta la atención, resolución y registro de incidencias técnicas.

<img src="Kinemo-report/assets/img/2_3_3-User-journey-mapping/User%20Journey%20Map%20-%20Carlos%20Torres.png" alt="User Journey Map - Carlos Torres">

Link del User Journey Mapping - Pepe Castillo: https://uxpressia.com/w/v8FzI/m/52UwW?tagId=9BZKW  
Link del User Journey Mapping - Carlos Torres: https://uxpressia.com/w/v8FzI/m/9xtmS?tagId=9BZKW

### 2.3.4. Empathy Mapping

El Empathy Map de Pepe Castillo evidencia un perfil orientado a la planificación, evaluación económica y reducción del riesgo antes de adoptar nuevas tecnologías. Sus principales preocupaciones se relacionan con el costo, mantenimiento, soporte y retorno esperado de la inversión.

<img src="Kinemo-report/assets/img/2_3_4-Empathy-mapping/Empathy%20map-Pepe%20Castillo.png" alt="Empathy Map - Pepe Castillo">

El Empathy Map de Carlos Torres refleja un perfil técnico enfocado en la prevención y resolución de incidencias. Sus principales dificultades aparecen ante fallas inesperadas, limitaciones de diagnóstico, falta de repuestos y demoras del soporte, mientras que sus objetivos se centran en mantener la continuidad operativa de las salas.

<img src="Kinemo-report/assets/img/2_3_4-Empathy-mapping/Empathy%20map-Carlos%20Torres.png" alt="Empathy Map - Carlos Torres">

### 2.4 Big Picture EventStorming

> _Pendiente — completar en `feature/event-storming-big-picture`._

### 2.5 Ubiquitous Language

**Usuarios del sistema:**

- **Cinema Manager (Administrador de Cine):** Responsable de la cadena o sala de cine encargado de afiliar el establecimiento, programar funciones y monitorear el rendimiento comercial.
- **Maintenance Technician (Técnico de Mantenimiento):** Especialista asignado a la calibración física, diagnóstico de actuadores y resolución de incidencias en las butacas sensoriales.
- **Moviegoer (Espectador / Espectador de Cine):** Cliente final que adquiere entradas, experimenta las sensaciones físicas durante la película y califica el nivel de inmersión sensorial.
- **Content Synchronizer (Sincronizador de Contenido):** Ingeniero o diseñador multimedia responsable de mapear y marcar los efectos en la línea de tiempo de la película.

**Infraestructura y hardware sensorial:**

- **Haptic Actuator (Actuador Háptico):** Dispositivo electromecánico embebido en la butaca que convierte datos digitales en vibraciones, inclinaciones e impactos físicos.
- **Kinemo Controller (Controlador Kinemo):** Módulo de hardware local en sala que recibe la señal del proyector (DCP) y comanda en milisegundos a la red de asientos sensoriales.
- **Sensory Room (Sala Sensorial):** Sala de exhibición comercial equipada y homologada con la infraestructura de hardware y red Kinemo.
- **Telemetry Data (Datos de Telemetría):** Flujo de métricas periódicas (temperatura, voltaje, latencia de respuesta) transmitidas por los sensores de cada butaca al panel de control.

**Procesamiento y sincronización multimedia:**

- **Sensory Track (Pista Sensorial):** Archivo digital estructurado con metadatos que contiene los eventos de vibración, viento y movimiento alineados al código de tiempo (timecode) de la película.
- **Cue Event (Disparo Sensorial):** Marcador individual en la línea de tiempo que activa un efecto físico determinado con duración e intensidad específicas.
- **Sync Drift (Desfase de Sincronización):** Desviación temporal en milisegundos entre la proyección audiovisual principal y la ejecución mecánica en la butaca.
- **Sync Pulse (Pulso de Sincronización):** Señal de sincronía periódica emitida por el proyector de cine que mantiene alineados los actuadores con el audio y video.

**Gestión comercial y reservas:**

- **Sensory Screening (Función Sensorial):** Proyección pública programada que cuenta con la pista háptica activa habilitada para los asistentes.
- **Seat Allocation (Asignación de Butacas):** Proceso de reservación y bloqueo de asientos motorizados operativos en el mapa de la sala.
- **Showtime Schedule (Cartelera / Programación):** Calendario de horarios y películas disponibles con experiencia inmersiva habilitada.

**Mantenimiento e incidencias:**

- **Hardware Incident (Incidente de Hardware):** Falla electromecánica o pérdida de enlace en una butaca durante o fuera de una función.
- **Calibration Profile (Perfil de Calibración):** Parámetros predefinidos de intensidad y sensibilidad del asiento adaptados al tipo de sala o público.
- **Preventive Maintenance Order (Orden de Mantenimiento Preventivo):** Solicitud generada automáticamente cuando la telemetría reporta desgaste o ciclos de uso elevados en los actuadores.

## Capítulo III: Requirements Specification

### 3.1 User Stories

<table style="width: 100%; border-collapse: collapse;">
  <!-- BARRA DE ARRIBA -->
  <tr>
    <th style="text-align: center;">Epic/Story ID</th>
    <th style="text-align: center;">Título</th>
    <th style="text-align: center;">Descripción</th>
    <th style="text-align: center;">Criterios de Aceptación</th>
    <th style="text-align: center;">Relacionado con (Epic ID)</th>
  </tr>
  <!-- EPICA 1 -->
  <tr>
    <td style="text-align: center;">EP01</td>
    <td style="text-align: center;">Gestión del Catálogo de Experiencias 4D</td>
    <td style="text-align: center;">
      Como administrador de la empresa de entretenimiento, quiero gestionar el catálogo de películas y sus archivos de efectos 4D para ofrecer una oferta inmersiva actualizada.
    </td>
    <td style="text-align: center;">
      - Permite registrar y editar las experiencias del catálogo<br>
      - Asocia archivos de efectos 4D a cada película.<br>
      - Permite consultar y filtrar contenidos según su disponibilidad.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 2 -->
  <tr>
    <td style="text-align: center;">EP02</td>
    <td style="text-align: center;">Programación de Funciones e Insumos de Sala</td>
    <td style="text-align: center;">
      Como administrador u operador, quiero programar las funciones en las salas 4D para garantizar la disponibilidad del servicio y la preparación de la sala.
    </td>
    <td style="text-align: center;">
      - Permite registrar funciones indicando fecha, hora, película y sala asignada.<br>
      - Notifica los insumos necesarios (agua, aire) requeridos para el día.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 3 -->
  <tr>
    <td style="text-align: center;">EP03</td>
    <td style="text-align: center;">Integración de Ocupación y Control de Sala</td>
    <td style="text-align: center;">
      Como personal operativo, quiero visualizar el estado de ocupación de la sala para habilitar únicamente las butacas vendidas y optimizar el uso del equipamiento.
    </td>
    <td style="text-align: center;">
      - Visualiza en un mapa de sala las butacas vendidas y disponibles.<br>
      - Permite activar o desactivar asientos de forma manual o automatizada.<br>
      - Mantiene inmóviles las butacas vacías durante la función.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 4 -->
  <tr>
    <td style="text-align: center;">EP04</td>
    <td style="text-align: center;">Control y Sincronización de Efectos 4D</td>
    <td style="text-align: center;">
      Como personal operativo, quiero coordinar y supervisar la sincronización del contenido audiovisual con los efectos físicos (movimiento, viento, agua).
    </td>
    <td style="text-align: center;">
      - Ejecuta la secuencia de efectos en sincronía con la película.<br>
      - Detiene automáticamente los componentes mecánicos al finalizar la función.<br>
      - Incluye una opción de parada rápida ante imprevistos o emergencias.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 5 -->
  <tr>
    <td style="text-align: center;">EP05</td>
    <td style="text-align: center;">Pruebas y Calibración de Equipos</td>
    <td style="text-align: center;">
      Como personal técnico, quiero probar y ajustar los efectos de la sala antes de cada función para asegurar una experiencia fluida.
    </td>
    <td style="text-align: center;">
      - Permite realizar pruebas individuales de los efectos (viento, vibración, agua).<br>
      - Permite ajustar la intensidad general de los efectos.<br>
      - Facilita el ajuste básico de las plataformas de movimiento.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 6 -->
  <tr>
    <td style="text-align: center;">EP06</td>
    <td style="text-align: center;">Gestor de Mantenimiento e Incidencias</td>
    <td style="text-align: center;">
      Como personal técnico, quiero registrar y dar seguimiento al mantenimiento de los equipos para prevenir fallas durante las funciones.
    </td>
    <td style="text-align: center;">
      - Permite registrar los componentes instalados por sala.<br>
      - Muestra alertas visuales de equipos que requieren revisión o presentan fallas.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 7 -->
  <tr>
    <td style="text-align: center;">EP07</td>
    <td style="text-align: center;">Reportes y Dashboard Operativo</td>
    <td style="text-align: center;">
      Como administrador, quiero visualizar métricas del desempeño de las salas y del equipamiento para tomar decisiones de negocio y mantenimiento.
    </td>
    <td style="text-align: center;">
      - Presenta gráficos del uso acumulado de las salas inmersivas.<br>
      - Genera reportes sobre las incidencias y fallas más frecuentes.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 8 -->
  <tr>
    <td style="text-align: center;">EP08</td>
    <td style="text-align: center;">Landing Page B2B</td>
    <td style="text-align: center;">
      Como visitante interesado en implementar una solución 4D, quiero conocer la propuesta de valor, características y servicios de la empresa, además de comparar los planes disponibles, para evaluar si la solución se adapta a las necesidades de mi organización.
    </td>
    <td style="text-align: center;">
      - Presenta información clara sobre la propuesta de valor de la solución 4D.<br>
      - Describe las principales características y servicios ofrecidos.<br>
      - Permite a los visitantes comparar y seleccionar los planes de suscripción B2B.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 9 -->
  <tr>
    <td style="text-align: center;">EP09</td>
    <td style="text-align: center;">API RESTful</td>
    <td style="text-align: center;">
      Como Developer, quiero disponer de una API RESTful para consultar y gestionar la información principal del sistema, para facilitar la integración entre los diferentes componentes de la solución.
    </td>
    <td style="text-align: center;">
      - Permite consultar información mediante solicitudes HTTP.<br>
      - Permite registrar y actualizar información mediante los métodos HTTP correspondientes.<br>
      - Retorna respuestas con códigos de estado HTTP según el resultado de la operación.<br>
      - Valida el estado de la suscripción del cliente para autorizar o bloquear dinámicamente el acceso a los endpoints protegidos.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- EPICA 10 -->
  <tr>
    <td style="text-align: center;">EP10</td>
    <td style="text-align: center;">Gestión de suscripción</td>
    <td style="text-align: center;">
      Como administrador de cine, deseo gestionar mi plan de suscripción en la plataforma para controlar los pagos, renovaciones y el límite de pantallas conectadas de mi cadena.
    </td>
    <td style="text-align: center;">
      - Permite al administrador contratar y realizar el pago de un plan de suscripción para su cadena de cines.<br>
      - Muestra en el panel el estado actualizado del plan y los límites de pantallas conectadas.<br>
      - Facilita la renovación o el cambio a un plan superior (upgrade) de manera autogestionada.<br>
      - Restringe automáticamente el registro de nuevas salas si se supera el límite del plan o si el pago falla.
    </td>
    <td style="text-align: center;">-</td>
  </tr>
  <!-- US01 -->
  <tr>
    <td style="text-align: center;">US01</td>
    <td style="text-align: center;">Registrar película 4D</td>
    <td style="text-align: center;">
      Como administrador, quiero registrar una película en la plataforma para ponerla a disposición de las salas inmersivas.
    </td>
    <td style="text-align: center;">
      - Given que el Administrador ingresa título, duración y género válidos, When guarda el registro, Then el sistema almacena la película en el catálogo.<br>
      - Given que faltan campos obligatorios, When el Administrador intenta guardar, Then el sistema bloquea el envío y resalta los errores.
    </td>
    <td style="text-align: center;">EP01</td>
  </tr>
  <!-- US02 -->
  <tr>
    <td style="text-align: center;">US02</td>
    <td style="text-align: center;">Asociar archivo de efectos</td>
    <td style="text-align: center;">
      Como personal técnico, quiero cargar el archivo de efectos 4D a una película para vincular el contenido con el hardware.
    </td>
    <td style="text-align: center;">
      - Given un archivo de secuencia de efectos válido, When el Personal Técnico lo asigna a una película, Then el sistema lo vincula y confirma la carga.<br>
      - Given un archivo con formato no permitido, When el Personal Técnico intenta subirlo, Then el sistema muestra un mensaje de error.
    </td>
    <td style="text-align: center;">EP01</td>
  </tr>
  <!-- US03 -->
  <tr>
    <td style="text-align: center;">US03</td>
    <td style="text-align: center;">Consultar catálogo</td>
    <td style="text-align: center;">
      Como administrador, quiero consultar las películas 4D disponibles para seleccionar cuáles programar en cartelera.
    </td>
    <td style="text-align: center;">
      - Given que existen películas registradas, When el Administrador entra al catálogo, Then el sistema muestra la lista con el estado de sus efectos.<br>
      - Given que el catálogo está vacío, When el Administrador consulta la sección, Then el sistema indica que no hay títulos y ofrece registrar uno.
    </td>
    <td style="text-align: center;">EP01</td>
  </tr>
  <!-- US04 -->
  <tr>
    <td style="text-align: center;">US04</td>
    <td style="text-align: center;">Desactivar contenido</td>
    <td style="text-align: center;">
      Como administrador, quiero cambiar el estado de una película a inactiva para evitar su programación.
    </td>
    <td style="text-align: center;">
      - Given una película activa, When el Administrador la marca como "Inactiva", Then el sistema la deshabilita para nuevas funciones.<br>
      - Given una película inactiva, When el Administrador abre la agenda, Then el título no aparece entre las opciones seleccionables.
    </td>
    <td style="text-align: center;">EP01</td>
  </tr>
  <!-- US05 -->
  <tr>
    <td style="text-align: center;">US05</td>
    <td style="text-align: center;">Programar función</td>
    <td style="text-align: center;">
      Como administrador, quiero programar una función 4D para organizar el calendario de la sala.
    </td>
    <td style="text-align: center;">
      - Given una sala y horario disponibles, When el Administrador asigna película, fecha y hora, Then el sistema guarda la función con sus efectos enlazados.<br>
      - Given que la sala está ocupada en ese bloque, When el Administrador intenta guardar, Then el sistema alerta del conflicto y rechaza el registro.
    </td>
    <td style="text-align: center;">EP01</td>
  </tr>
  <!-- US06 -->
  <tr>
    <td style="text-align: center;">US06</td>
    <td style="text-align: center;">Editar/Cancelar función</td>
    <td style="text-align: center;">
      Como personal operativo, quiero ajustar o cancelar una función para adaptar la programación ante eventualidades.
    </td>
    <td style="text-align: center;">
      - Given una función programada, When el Personal Operativo modifica la hora o cambia el estado a "Cancelada", Then el sistema actualiza la parrilla.<br>
      - Given una función cancelada, When el Personal Operativo la revisa, Then el sistema impide iniciar la ejecución de sus efectos.
    </td>
    <td style="text-align: center;">EP02</td>
  </tr>
  <!-- US07 -->
  <tr>
    <td style="text-align: center;">US07</td>
    <td style="text-align: center;">Consultar insumos del día</td>
    <td style="text-align: center;">
      Como personal de sala, quiero ver los insumos requeridos por la programación para preparar el agua y aire.
    </td>
    <td style="text-align: center;">
      - Given funciones 4D agendadas hoy, When el Personal de Sala revisa el panel diario, Then el sistema calcula y muestra los niveles de aire y agua necesarios.<br>
      - Given funciones que no usan efectos físicos, When se consulta el resumen, Then el sistema notifica que no se requieren cargas adicionales.
    </td>
    <td style="text-align: center;">EP02</td>
  </tr>
  <!-- US08 -->
  <tr>
    <td style="text-align: center;">US08</td>
    <td style="text-align: center;">Visualizar mapa de sala</td>
    <td style="text-align: center;">
      Como personal operativo, quiero ver la ocupación de la sala en tiempo real para identificar las butacas a utilizar.
    </td>
    <td style="text-align: center;">
      - Given una función próxima a iniciar, When el Personal Operativo abre el mapa de sala, Then el sistema diferencia butacas ocupadas, libres y fuera de servicio.<br>
      - Given nuevas ventas registradas en boletería, When el Personal Operativo actualiza la vista, Then el mapa refresca el estado de los asientos.
    </td>
    <td style="text-align: center;">EP03</td>
  </tr>
  <!-- US09 -->
  <tr>
    <td style="text-align: center;">US09</td>
    <td style="text-align: center;">Activar asientos ocupados</td>
    <td style="text-align: center;">
      Como personal operativo, quiero activar solo las butacas vendidas para evitar el desgaste de asientos vacíos.
    </td>
    <td style="text-align: center;">
      - Given las ventas confirmadas de una función, When el Personal Operativo envía la orden, Then el sistema activa los motores únicamente en butacas ocupadas.<br>
      - Given una butaca marcada como libre, When la función entra en proyección, Then el sistema la mantiene inmóvil durante todo el evento.
    </td>
    <td style="text-align: center;">EP03</td>
  </tr>
  <!-- US10 -->
  <tr>
    <td style="text-align: center;">US10</td>
    <td style="text-align: center;">Habilitación manual de butaca</td>
    <td style="text-align: center;">
      Como personal operativo, quiero activar manualmente una butaca para reubicar a un asistente.
    </td>
    <td style="text-align: center;">
      - Given una butaca desocupada en el mapa, When el Personal Operativo presiona "Activar Manualmente", Then el sistema la suma a la señal de efectos.<br>
      - Given una butaca activada manualmente, When se remueve dicha opción, Then el sistema la retorna a su estado inactivo.
    </td>
    <td style="text-align: center;">EP03</td>
  </tr>
  <!-- US11 -->
  <tr>
    <td style="text-align: center;">US11</td>
    <td style="text-align: center;">Iniciar secuencia de efectos</td>
    <td style="text-align: center;">
      Como personal operativo, quiero dar inicio a la función 4D para sincronizar el contenido con los efectos físicos.
    </td>
    <td style="text-align: center;">
      - Given la sala lista y verificada, When el Personal Operativo presiona "Iniciar Función", Then el sistema arranca la secuencia y pasa a "En Proyección".<br>
      - Given un error crítico detectado en el hardware, When se presiona iniciar, Then el sistema detiene el arranque y alerta de la falla.
    </td>
    <td style="text-align: center;">EP04</td>
  </tr>
  <!-- US12 -->
  <tr>
    <td style="text-align: center;">US12</td>
    <td style="text-align: center;">Parada de emergencia</td>
    <td style="text-align: center;">
      Como personal operativo, quiero presionar un botón de detención rápida, para frenar los movimientos ante cualquier contingencia en la sala.
    </td>
    <td style="text-align: center;">
      - Given una función en ejecución, When el Personal Operativo activa "Parada de Emergencia", Then el sistema corta los efectos e inmoviliza los asientos.<br>
      - Given el sistema detenido por emergencia, When se soluciona el evento, Then el sistema exige confirmación manual para restablecer el servicio.
    </td>
    <td style="text-align: center;">EP04</td>
  </tr>
  <!-- US13 -->
  <tr>
    <td style="text-align: center;">US13</td>
    <td style="text-align: center;">Concluir función</td>
    <td style="text-align: center;">
      Como sistema, quiero finalizar automáticamente la ejecución de efectos al terminar la película.
    </td>
    <td style="text-align: center;">
      - Given que la línea de tiempo llega a cero, When la película termina, Then el sistema apaga ventiladores e inyectores y pasa a "Finalizada".<br>
      - Given la conclusión de la función, When los espectadores se preparan a salir, Then el sistema posiciona las butacas en el nivel neutro.
    </td>
    <td style="text-align: center;">EP04</td>
  </tr>
  <!-- US14 -->
  <tr>
    <td style="text-align: center;">US14</td>
    <td style="text-align: center;">Probar canal de efectos</td>
    <td style="text-align: center;">
      Como personal técnico, quiero realizar una prueba de efectos individual para verificar el funcionamiento de viento, agua o movimiento.
    </td>
    <td style="text-align: center;">
      - Given la sala en modo pruebas, When el Personal Técnico selecciona un canal y presiona "Probar", Then el sistema lanza un pulso de 5 segundos.<br>
      - Given un canal que no responde, When el Personal Técnico ejecuta el test, Then el sistema informa "Prueba fallida en el canal".
    </td>
    <td style="text-align: center;">EP05</td>
  </tr>
  <!-- US15 -->
  <tr>
    <td style="text-align: center;">US15</td>
    <td style="text-align: center;">Ajustar nivel de intensidad</td>
    <td style="text-align: center;">
      Como personal operativo, quiero regular la potencia de los efectos para adaptarla a funciones infantiles o de menor impacto.
    </td>
    <td style="text-align: center;">
      - Given una función seleccionada, When el Personal Operativo ajusta el nivel a "Bajo", "Medio" o "Alto", Then el sistema escala la fuerza de los actuadores.<br>
      - Given una función infantil configurada en nivel "Bajo", When arranca la proyección, Then el sistema atenúa los movimientos bruscos.
    </td>
    <td style="text-align: center;">EP05</td>
  </tr>
  <!-- US16 -->
  <tr>
    <td style="text-align: center;">US16</td>
    <td style="text-align: center;">Nivelar butacas</td>
    <td style="text-align: center;">
      Como personal técnico, quiero recalibrar la posición base de los asientos para asegurar su alineación.
    </td>
    <td style="text-align: center;">
      - Given plataformas con inclinación desalineada, When el Personal Técnico ejecuta "Alineación Cero", Then el sistema retorna los asientos a nivel horizontal.<br>
      - Given que los sensores confirman la posición, When concluye el proceso, Then el sistema despliega el mensaje de ajuste exitoso.
    </td>
    <td style="text-align: center;">EP05</td>
  </tr>
  <!-- US17 -->
  <tr>
    <td style="text-align: center;">US17</td>
    <td style="text-align: center;">Registrar componentes de sala</td>
    <td style="text-align: center;">
      Como personal técnico, quiero dar de alta los equipos instalados en la sala para mantener un registro estructurado.
    </td>
    <td style="text-align: center;">
      - Given la instalación de un nuevo hardware, When el Personal Técnico ingresa tipo, código y ubicación, Then el sistema lo registra en la base de datos.<br>
      - Given un formulario con datos faltantes, When se intenta guardar, Then el sistema bloquea la acción indicando los campos requeridos.
    </td>
    <td style="text-align: center;">EP06</td>
  </tr>
  <!-- US18 -->
  <tr>
    <td style="text-align: center;">US18</td>
    <td style="text-align: center;">Registrar falla de equipo</td>
    <td style="text-align: center;">
      Como personal operativo, quiero reportar una avería en un componente específico para solicitar su reparación.
    </td>
    <td style="text-align: center;">
      - Given un equipo defectuoso, When el Personal Operativo lo selecciona y detalla el problema, Then el sistema cambia su estado a "En Revisión".<br>
      - Given una falla reportada, When el Personal Técnico ingresa al panel, Then el sistema le resalta la orden de revisión prioritaria.
    </td>
    <td style="text-align: center;">EP06</td>
  </tr>
  <!-- US19 -->
  <tr>
    <td style="text-align: center;">US19</td>
    <td style="text-align: center;">Registrar mantenimiento</td>
    <td style="text-align: center;">
      Como personal técnico, quiero guardar el reporte de mantenimiento realizado para actualizar el historial de la sala.
    </td>
    <td style="text-align: center;">
      - Given un trabajo técnico concluido, When el Personal Técnico redacta la acción correctiva y cierra la orden, Then el equipo vuelve a "Operativo".<br>
      - Given un reporte sin descripción técnica, When se intenta guardar, Then el sistema exige especificar la solución aplicada.
    </td>
    <td style="text-align: center;">EP06</td>
  </tr>
  <!-- US20 -->
  <tr>
    <td style="text-align: center;">US20</td>
    <td style="text-align: center;">Visualizar dashboard operativo</td>
    <td style="text-align: center;">
      Como administrador, quiero consultar gráficos de uso de salas y fallas frecuentes para evaluar el rendimiento.
    </td>
    <td style="text-align: center;">
      - Given datos de uso acumulados, When el Administrador abre el Dashboard Operativo, Then el sistema despliega gráficos de funciones, uso y averías.<br>
      - Given la necesidad de analizar métricas, When el Administrador presiona "Exportar", Then el sistema descarga el resumen en PDF o CSV.
    </td>
    <td style="text-align: center;">EP07</td>
  </tr>
  <!-- US21 -->
  <tr>
    <td style="text-align: center;">US21</td>
    <td style="text-align: center;">Buscar película por nombre</td>
    <td style="text-align: center;">
      Como administrador, quiero buscar películas por título o género para localizarlas rápidamente.
    </td>
    <td style="text-align: center;">
      - Given la lista del catálogo, When el Administrador ingresa un texto de búsqueda, Then el sistema filtra las coincidencias en tiempo real.<br>
      - Given un término sin coincidencias, When el Administrador realiza la consulta, Then el sistema muestra el mensaje "Sin resultados".
    </td>
    <td style="text-align: center;">EP01</td>
  </tr>
  <!-- US22 -->
  <tr>
    <td style="text-align: center;">US22</td>
    <td style="text-align: center;">Asignar etiquetas de efectos</td>
    <td style="text-align: center;">
      Como personal técnico, quiero clasificar las películas según la intensidad de sus efectos para alertar a la sala.
    </td>
    <td style="text-align: center;">
      - Given un contenido en el catálogo, When el Personal Técnico le asigna un nivel de intensidad y guarda, Then el sistema actualiza la ficha de la película.<br>
      - Given la etiqueta asignada, When el Administrador visualiza la cartelera, Then el sistema exhibe el distintivo de intensidad correspondiente.
    </td>
    <td style="text-align: center;">EP01</td>
  </tr>
  <!-- US23 -->
  <tr>
    <td style="text-align: center;">US23</td>
    <td style="text-align: center;">Duplicar configuración de película</td>
    <td style="text-align: center;">
      Como administrador, quiero clonar los datos y archivos de un contenido para agilizar el registro de entregas similares.
    </td>
    <td style="text-align: center;">
      - Given una película registrada, When el Administrador selecciona "Duplicar Configuración", Then el sistema genera una copia idéntica editable.<br>
      - Given la copia editable, When el Administrador modifica el título y guarda, Then se crea un nuevo registro sin alterar el original.
    </td>
    <td style="text-align: center;">EP01</td>
  </tr>
  <!-- US24 -->
  <tr>
    <td style="text-align: center;">US24</td>
    <td style="text-align: center;">Visualizar resumen diario de funciones</td>
    <td style="text-align: center;">
      Como personal de sala, quiero ver una vista resumida de las funciones del día para coordinar los turnos.
    </td>
    <td style="text-align: center;">
      - Given la programación del día, When el Personal de Sala accede al panel diario, Then el sistema lista las funciones en orden cronológico con su estado.<br>
      - Given una función completada, When se actualiza el resumen, Then el sistema la marca visualmente como finalizada.
    </td>
    <td style="text-align: center;">EP02</td>
  </tr>
  <!-- US25 -->
  <tr>
    <td style="text-align: center;">US25</td>
    <td style="text-align: center;">Bloquear función por mantenimiento</td>
    <td style="text-align: center;">
      Como personal técnico, quiero inhabilitar la programación de una sala para evitar asignaciones mientras está en reparación.
    </td>
    <td style="text-align: center;">
      - Given una sala que requiere reparación, When el personal Técnico reserva un rango de horas, Then la sala pasa a estado "En Mantenimiento".<br>
      - Given el bloqueo activo, When un Administrador intenta agendar una función en esa franja, Then el sistema prohíbe el registro.
    </td>
    <td style="text-align: center;">EP02</td>
  </tr>
  <!-- US26 -->
  <tr>
    <td style="text-align: center;">US26</td>
    <td style="text-align: center;">Alerta de coincidencia de horarios</td>
    <td style="text-align: center;">
      Como administrador, quiero alertas de traslape para evitar programar dos funciones a la misma hora en la misma sala.
    </td>
    <td style="text-align: center;">
      - Given una función ya agendada en un bloque horario, When el Administrador intenta ingresar otra función a la misma hora, Then el sistema bloquea el guardado.<br>
      - Given horarios continuos sin interferencia, When el Administrador establece el inicio, Then el sistema guarda la función correctamente.
    </td>
    <td style="text-align: center;">EP02</td>
  </tr>
  <!-- US27 -->
  <tr>
    <td style="text-align: center;">US27</td>
    <td style="text-align: center;">Bloquear butaca individual</td>
    <td style="text-align: center;">
      Como personal operativo, quiero inhabilitar una butaca averiada para evitar que sea asignada a un espectador.
    </td>
    <td style="text-align: center;">
      - Given el mapa interactivo, When el Personal Operativo selecciona un asiento y marca "Fuera de Servicio", Then el sistema bloquea la butaca.<br>
      - Given una butaca fuera de servicio, When inicia la función, Then el sistema excluye dicho asiento de cualquier señal de movimiento.
    </td>
    <td style="text-align: center;">EP03</td>
  </tr>
  <!-- US28 -->
  <tr>
    <td style="text-align: center;">US28</td>
    <td style="text-align: center;">Consultar resumen de ocupación</td>
    <td style="text-align: center;">
      Como administrador, quiero ver el porcentaje de ocupación por función para medir el rendimiento de la sala.
    </td>
    <td style="text-align: center;">
      - Given la información de entradas vendidas, When el Administrador consulta la lista de funciones, Then el sistema muestra el % de aforo ocupado.<br>
      - Given un rango de fechas seleccionado, When el Administrador filtra la vista, Then el sistema calcula el promedio de ocupación del periodo.
    </td>
    <td style="text-align: center;">EP03</td>
  </tr>
  <!-- US29 -->
  <tr>
    <td style="text-align: center;">US29</td>
    <td style="text-align: center;">Consultar estado de integración</td>
    <td style="text-align: center;">
      Como personal técnico, quiero consultar el estado de integración con la boletería para confirmar la recepción de datos.
    </td>
    <td style="text-align: center;">
      - Given el módulo de integraciones, When el Personal Técnico abre el panel, Then el sistema muestra el indicador de enlace y la última sincronización.<br>
      - Given una pérdida de conexión, When el Personal Técnico presiona "Reconectar", Then el sistema reintenta el enlace y actualiza el estado.
    </td>
    <td style="text-align: center;">EP03</td>
  </tr>
  <!-- US30 -->
  <tr>
    <td style="text-align: center;">US30</td>
    <td style="text-align: center;">Pausar y reanudar secuencia</td>
    <td style="text-align: center;">
      Como personal operativo, quiero pausar los efectos en vivo para resolver un inconveniente menor sin reiniciar el sistema.
    </td>
    <td style="text-align: center;">
      - Given efectos 4D en reproducción, When el Personal Operativo presiona "Pause", Then el sistema congela la línea de tiempo y actuadores.<br>
      - Given los efectos congelados, When el Personal Operativo presiona "Reanudar", Then la secuencia continúa exactamente desde el punto pausado.
    </td>
    <td style="text-align: center;">EP04</td>
  </tr>
  <!-- US31 -->
  <tr>
    <td style="text-align: center;">US31</td>
    <td style="text-align: center;">Simular rutina de inicio de sala</td>
    <td style="text-align: center;">
      Como personal operativo, quiero ejecutar una secuencia rápida de bienvenida para mover suavemente las butacas al ingresar el público.
    </td>
    <td style="text-align: center;">
      - Given la apertura de puertas, When el Personal Operativo activa "Rutina de Demo", Then las butacas ejecutan movimientos sutiles por 30 segundos.<br>
      - Given que concluyen los 30 segundos, When se agota el tiempo, Then el sistema apaga la rutina automáticamente.
    </td>
    <td style="text-align: center;">EP04</td>
  </tr>
  <!-- US32 -->
  <tr>
    <td style="text-align: center;">US32</td>
    <td style="text-align: center;">Probar inyectores de agua</td>
    <td style="text-align: center;">
      Como personal técnico, quiero probar el circuito de agua de la sala para asegurar que las boquillas no estén obstruidas.
    </td>
    <td style="text-align: center;">
      - Given el panel de calibración, When el Personal Técnico dispara la prueba de agua, Then el sistema emite una ráfaga corta de 2 segundos.<br>
      - Given falta de presión en la tubería, When se ejecuta la prueba, Then el sistema despliega una advertencia de baja presión.
    </td>
    <td style="text-align: center;">EP05</td>
  </tr>
  <!-- US33 -->
  <tr>
    <td style="text-align: center;">US33</td>
    <td style="text-align: center;">Probar ventiladores de viento</td>
    <td style="text-align: center;">
      Como personal técnico, quiero probar la potencia de las turbinas para verificar la respuesta del sistema de viento.
    </td>
    <td style="text-align: center;">
      - Given la consola de pruebas, When el Personal Técnico activa el viento al nivel deseado, Then los ventiladores operan durante 10 segundos.<br>
      - Given que transcurre el tiempo de test, When el cronómetro llega a cero, Then el sistema apaga el viento de forma automática.
    </td>
    <td style="text-align: center;">EP05</td>
  </tr>
  <!-- US34 -->
  <tr>
    <td style="text-align: center;">US34</td>
    <td style="text-align: center;">Restablecer configuración de fábrica</td>
    <td style="text-align: center;">
      Como personal técnico, quiero resetear los parámetros de sincronización para corregir desajustes tras ediciones fallidas.
    </td>
    <td style="text-align: center;">
      - Given ajustes con errores en los efectos, When el Personal Técnico presiona "Restablecer" y confirma, Then se restaura el archivo original.<br>
      - Given el cuadro de confirmación en pantalla, When el Personal Técnico selecciona "Cancelar", Then los cambios actuales permanecen intactos.
    </td>
    <td style="text-align: center;">EP05</td>
  </tr>
  <!-- US35 -->
  <tr>
    <td style="text-align: center;">US35</td>
    <td style="text-align: center;">Consultar hoja de vida del equipo</td>
    <td style="text-align: center;">
      Como personal técnico, quiero ver el historial completo de un componente para tomar decisiones de sustitución.
    </td>
    <td style="text-align: center;">
      - Given el listado de activos de la sala, When el Personal Técnico selecciona un equipo, Then el sistema muestra fecha de alta, fallas y horas de uso.<br>
      - Given un equipo con horas operativas excedidas, When se consulta su ficha, Then el sistema resalta una alerta de reemplazo sugerido.
    </td>
    <td style="text-align: center;">EP06</td>
  </tr>
  <!-- US36 -->
  <tr>
    <td style="text-align: center;">US36</td>
    <td style="text-align: center;">Programar mantenimiento preventivo</td>
    <td style="text-align: center;">
      Como personal técnico, quiero agendar fechas de revisión periódica para recibir un recordatorio del sistema.
    </td>
    <td style="text-align: center;">
      - Given el módulo de mantenimiento, When el Personal Técnico agenda una revisión futura, Then la tarea se guarda en el calendario técnico.<br>
      - Given el día de la revisión agendada, When el personal entra a la plataforma, Then el sistema despliega una alerta de tarea pendiente.
    </td>
    <td style="text-align: center;">EP06</td>
  </tr>
  <!-- US37 -->
  <tr>
    <td style="text-align: center;">US37</td>
    <td style="text-align: center;">Filtrar incidencias por severidad</td>
    <td style="text-align: center;">
      Como personal técnico, quiero filtrar los reportes de falla por gravedad para priorizar reparaciones urgentes.
    </td>
    <td style="text-align: center;">
      - Given múltiples reportes registrados, When el Personal Técnico aplica el filtro "Crítica", Then el sistema despliega únicamente las fallas graves.<br>
      - Given una falla crítica reparada, When se marca como resuelta, Then el sistema la remueve del listado prioritario.
    </td>
    <td style="text-align: center;">EP06</td>
  </tr>
  <!-- US38 -->
  <tr>
    <td style="text-align: center;">US38</td>
    <td style="text-align: center;">Generar reporte de insumos consumidos</td>
    <td style="text-align: center;">
      Como administrador, quiero exportar el consumo de agua y aire por sala para calcular los costos operativos.
    </td>
    <td style="text-align: center;">
      - Given los registros de uso de actuadores, When el Administrador genera el reporte del periodo, Then el sistema calcula el consumo de insumos.<br>
      - Given el resultado en pantalla, When el Administrador presiona exportar, Then el sistema descarga el archivo en formato PDF o CSV.
    </td>
    <td style="text-align: center;">EP07</td>
  </tr>
  <!-- US39 -->
  <tr>
    <td style="text-align: center;">US39</td>
    <td style="text-align: center;">Comparar rentabilidad de salas</td>
    <td style="text-align: center;">
      Como administrador, quiero comparar el uso entre salas inmersivas para identificar las de mayor rendimiento.
    </td>
    <td style="text-align: center;">
      - Given datos operativos de varios complejos, When el Administrador entra a la comparativa, Then el sistema grafica las horas trabajadas por sala.<br>
      - Given una sala con uso por debajo de la media, When se genera el gráfico, Then el sistema resalta visualmente la brecha de rendimiento.
    </td>
    <td style="text-align: center;">EP07</td>
  </tr>
  <!-- US40 -->
  <tr>
    <td style="text-align: center;">US40</td>
    <td style="text-align: center;">Consultar registro de bitácora del personal</td>
    <td style="text-align: center;">
      Como administrador, quiero leer las observaciones del turno anterior para dar seguimiento a la operación diaria.
    </td>
    <td style="text-align: center;">
      - Given los comentarios escritos por los operadores, When el Administrador abre la Bitácora, Then el sistema lista las entradas ordenadas por fecha y hora.<br>
      - Given la lista general de notas, When el Administrador filtra por un operador específico, Then el sistema muestra únicamente las entradas de ese usuario.
    </td>
    <td style="text-align: center;">EP07</td>
  </tr>
  <!-- US41 -->
  <tr>
    <td style="text-align: center;">US41</td>
    <td style="text-align: center;">Conocer beneficios de la solución</td>
    <td style="text-align: center;">
      Como visitante, deseo conocer los beneficios de la solución para entender el valor comercial que aporta la tecnología 4D a mi cine.
    </td>
    <td style="text-align: center;">
      - Given el visitante se encuentra en el Landing Page, When navega a la sección de beneficios, Then el sistema expone las ventajas competitivas de la solución 4D.
    </td>
    <td style="text-align: center;">EP08</td>
  </tr>
  <!-- US42 -->
  <tr>
    <td style="text-align: center;">US42</td>
    <td style="text-align: center;">Conocer las características</td>
    <td style="text-align: center;">
      Como visitante, deseo conocer las características de la solución para entender las especificaciones técnicas del hardware y software.
    </td>
    <td style="text-align: center;">
      - Given el visitante explora la plataforma, When accede a la sección de características, Then el sistema despliega el detalle de las butacas y el controlador Kinemo.
    </td>
    <td style="text-align: center;">EP08</td>
  </tr>
  <!-- US43 -->
  <tr>
    <td style="text-align: center;">US43</td>
    <td style="text-align: center;">Conocer los servicios</td>
    <td style="text-align: center;">
      Como visitante, deseo conocer los servicios ofrecidos para identificar qué nivel de soporte e instalación técnica se incluye.
    </td>
    <td style="text-align: center;">
      - Given el visitante revisa el modelo de negocio, When consulta la oferta, Then el sistema lista las opciones de integración de hardware y soporte técnico.
    </td>
    <td style="text-align: center;">EP08</td>
  </tr>
  <!-- US44 -->
  <tr>
    <td style="text-align: center;">US44</td>
    <td style="text-align: center;">Seleccionar plan de suscripción</td>
    <td style="text-align: center;">
      Como visitante, deseo comparar y seleccionar un plan de suscripción B2B para elegir el servicio que se adapte a las necesidades de mi cadena de cines.
    </td>
    <td style="text-align: center;">
      - Given el visitante accede a la sección de precios, When evalúa las opciones disponibles, Then el sistema muestra las diferencias de características entre los planes.<br>
      - Given el visitante ha elegido un plan, When hace clic en la acción de selección, Then el sistema redirige al flujo de contratación etiquetando el plan elegido.
    </td>
    <td style="text-align: center;">EP08</td>
  </tr>
  <!-- US45 -->
  <tr>
    <td style="text-align: center;">US45</td>
    <td style="text-align: center;">Consultar películas mediante API</td>
    <td style="text-align: center;">
      Como Developer, quiero consultar las películas disponibles mediante el RESTful API, para utilizar la información del catálogo en la aplicación.
    </td>
    <td style="text-align: center;">
      - Given existen películas registradas, When el Developer realiza una solicitud GET al recurso de películas, Then el API responde con código HTTP 200 y devuelve las películas disponibles.<br>
      - Given no existen películas registradas, When el Developer consulta el recurso, Then el API responde con código HTTP 200 y una lista vacía.
    </td>
    <td style="text-align: center;">EP09</td>
  </tr>
  <!-- US46 -->
  <tr>
    <td style="text-align: center;">US46</td>
    <td style="text-align: center;">Registrar una película mediante API</td>
    <td style="text-align: center;">
      Como Developer, quiero registrar una película mediante el RESTful API, para almacenar nuevos contenidos en el catálogo.
    </td>
    <td style="text-align: center;">
      - Given el Developer envía los datos obligatorios de una película, When realiza una solicitud POST al recurso correspondiente, Then el API registra la película y responde con un código HTTP 201.<br>
      - Given faltan datos obligatorios, When el Developer realiza la solicitud, Then el API responde con un código HTTP 400.
    </td>
    <td style="text-align: center;">EP09</td>
  </tr>
  <!-- US47 -->
  <tr>
    <td style="text-align: center;">US47</td>
    <td style="text-align: center;">Consultar funciones mediante API</td>
    <td style="text-align: center;">
      Como Developer, quiero consultar las funciones programadas mediante el RESTful API, para obtener información sobre la programación de las salas.
    </td>
    <td style="text-align: center;">
      - Given existen funciones programadas, When el Developer realiza una solicitud GET al recurso de funciones, Then el API responde con código HTTP 200 y devuelve las funciones registradas.<br>
      - Given no existen funciones programadas, When el Developer consulta el recurso, Then el API responde con código HTTP 200 y una lista vacía.
    </td>
    <td style="text-align: center;">EP09</td>
  </tr>
  <!-- US48 -->
  <tr>
    <td style="text-align: center;">US48</td>
    <td style="text-align: center;">Registrar una incidencia mediante API</td>
    <td style="text-align: center;">
      Como Developer, quiero registrar una incidencia de mantenimiento mediante el RESTful API, para almacenar los problemas reportados en una sala.
    </td>
    <td style="text-align: center;">
      - Given el Developer envía los datos requeridos de una incidencia, When realiza una solicitud POST al recurso de incidencias, Then el API registra la incidencia y responde con código HTTP 201.<br>
      - Given los datos enviados son incompletos, When el Developer realiza la solicitud, Then el API responde con código HTTP 400.
    </td>
    <td style="text-align: center;">EP09</td>
  </tr>
  <!-- US49 -->
  <tr>
    <td style="text-align: center;">US49</td>
    <td style="text-align: center;">Consultar estado de una sala mediante API</td>
    <td style="text-align: center;">
      Como Developer, quiero consultar el estado de una sala mediante el RESTful API, para conocer si se encuentra disponible, en funcionamiento o en mantenimiento.
    </td>
    <td style="text-align: center;">
      - Given existe una sala registrada, When el Developer realiza una solicitud GET al recurso de la sala, Then el API responde con código HTTP 200 y devuelve su estado actual.<br>
      - Given la sala solicitada no existe, When el Developer realiza la solicitud, Then el API responde con código HTTP 404.
    </td>
    <td style="text-align: center;">EP09</td>
  </tr>
  <!-- US50 -->
  <tr>
    <td style="text-align: center;">US50</td>
    <td style="text-align: center;">Consultar estado de suscripción mediante API</td>
    <td style="text-align: center;">
      Como Developer, deseo consultar el estado de la suscripción mediante el RESTful API para habilitar o bloquear dinámicamente funcionalidades en las aplicaciones web.
    </td>
    <td style="text-align: center;">
      - Given un cliente con plan válido, When el Developer realiza una solicitud GET al recurso de suscripción, Then el API responde con código HTTP 200 y devuelve los límites y permisos de acceso.<br>
      - Given un cliente con una suscripción inactiva, When el Developer consulta el recurso, Then el API responde con código HTTP 403 indicando restricción del servicio.
    </td>
    <td style="text-align: center;">EP09</td>
  </tr>
  <!-- US51 -->
  <tr>
    <td style="text-align: center;">US51</td>
    <td style="text-align: center;">Contratar servicio 4D</td>
    <td style="text-align: center;">
      Como administrador de cine, deseo contratar un plan de servicio 4D para obtener acceso a la solución y comenzar a utilizar el servicio en mis salas.
    </td>
    <td style="text-align: center;">
      - Given el administrador seleccionó un plan disponible, When confirma los datos de contratación, Then el sistema registra la contratación en estado pendiente de pago.<br>
      - Given el plan seleccionado no está disponible temporalmente, When intenta contratarlo, Then el sistema não permite completar la contratación y notifica la restricción.
    </td>
    <td style="text-align: center;">EP10</td>
  </tr>
  <!-- US52 -->
  <tr>
    <td style="text-align: center;">US52</td>
    <td style="text-align: center;">Realizar pago de suscripción</td>
    <td style="text-align: center;">
      Como administrador de cine, deseo realizar el pago de mi suscripción para activar el servicio contratado y enlazar mis salas.
    </td>
    <td style="text-align: center;">
      - Given existe una contratación pendiente, When el pago es procesado correctamente, Then la suscripción queda habilitada para su activación.<br>
      - Given el pago es rechazado por la pasarela, When se procesa la transacción, Then la suscripción permanece pendiente y el sistema informa el rechazo.
    </td>
    <td style="text-align: center;">EP10</td>
  </tr>
  <!-- US53 -->
  <tr>
    <td style="text-align: center;">US53</td>
    <td style="text-align: center;">Consultar estado y límites de suscripción</td>
    <td style="text-align: center;">
      Como administrador de cine, deseo consultar el estado y los límites de mi suscripción para conocer los recursos y cantidad de pantallas que tengo disponibles.
    </td>
    <td style="text-align: center;">
      - Given el administrador revisa su cuenta, When consulta la sección de suscripción, Then el sistema muestra el nombre del plan activo, fecha de vigencia y límites de pantallas permitidas.
    </td>
    <td style="text-align: center;">EP10</td>
  </tr>
  <!-- US54 -->
  <tr>
    <td style="text-align: center;">US54</td>
    <td style="text-align: center;">Renovar o cambiar plan de suscripción</td>
    <td style="text-align: center;">
      Como administrador de cine, deseo renovar o cambiar mi plan de suscripción para mantener o ampliar el servicio según el crecimiento de mi cadena.
    </td>
    <td style="text-align: center;">
      - Given un administrador con una suscripción activa, When selecciona la opción de cambiar plan a una categoría superior, Then el sistema inicia el flujo de upgrade de suscripción.<br>
      - Given una suscripción próxima a vencer, When faltan 15 días para el cierre de ciclo, Then el sistema emite una notificación de recordatorio de renovación.
    </td>
    <td style="text-align: center;">EP10</td>
  </tr>
</table>

### 3.2. Impact Mapping

El Impact Mapping de Kinemo se elaboró con el propósito de alinear los objetivos estratégicos de la startup con la entrega de valor del software. Esta técnica permite establecer la relación entre los Business Goals, los User Personas, los impactos esperados en su comportamiento, los Deliverables necesarios y las User Stories que permitirán materializarlos.

<img src="Kinemo-report/assets/img/3_2-Impact-mapping/Impact-mapping.png" alt="Impact Mapping">

Link de UXpressia: https://uxpressia.com/w/v8FzI/i/dBBww?tagId=9BZKW

### 3.3. Product Backlog

El Product Backlog de Kinemo organiza y prioriza las User Stories identificadas según el valor que aportan al negocio y a los segmentos objetivo. La priorización considera primero las historias relacionadas con la propuesta de valor, contratación y suscripción del servicio; posteriormente, las funcionalidades principales de operación, mantenimiento y supervisión; y finalmente, las Technical Stories necesarias para soportar la integración mediante el RESTful API. Cada User Story ha sido estimada utilizando Story Points de 1, 2, 3, 5 y 8.

| # Orden | User Story ID | Título | Descripción | Story Points |
| :---: | :---: | :--- | :--- | :---: |
| **1** | US28 | Conocer beneficios de la solución | Como visitante de una cadena de cine, quiero conocer los beneficios de Kinemo para comprender cómo la solución puede apoyar la incorporación y gestión de experiencias inmersivas. | 2 |
| **2** | US29 | Conocer características de la solución | Como visitante, quiero conocer las principales características de Kinemo para comprender cómo funciona la solución de entretenimiento inmersivo. | 3 |
| **3** | US30 | Conocer los servicios | Como visitante, deseo conocer los servicios ofrecidos para identificar qué nivel de soporte e instalación técnica se incluye. | 2 |
| **4** | US31 | Comparar planes disponibles | Como visitante, quiero comparar los planes disponibles de Kinemo para identificar cuál se ajusta mejor a las necesidades de mi organización. | 3 |
| **5** | US32 | Acceder a la Web Application | Como visitante, quiero acceder a la Web Application desde el Landing Page para continuar con las funcionalidades correspondientes a mi rol. | 2 |
| **6** | US39 | Contratar servicio 4D | Como administrador de cine, quiero contratar un plan de servicio de Kinemo para habilitar el uso de la solución en mi organización. | 5 |
| **7** | US40 | Realizar pago de suscripción | Como administrador de cine, deseo realizar el pago de mi suscripción para activar el servicio contratado y enlazar mis salas. | 8 |
| **8** | US41 | Consultar estado de suscripción | Como administrador de cine, quiero consultar el estado de mi suscripción para conocer la vigencia y condiciones del servicio contratado. | 3 |
| **9** | US42 | Renovar o cambiar suscripción | Como administrador de cine, quiero renovar o cambiar mi plan para mantener o adaptar el servicio contratado a las necesidades de mi organización. | 5 |
| **10** | US01 | Registrar película 4D | Como administrador, quiero registrar una película en la plataforma para ponerla a disposición de las salas inmersivas. | 3 |
| **11** | US02 | Asociar archivo de efectos | Como personal técnico, quiero asociar un archivo de efectos 4D a una película para disponer de la configuración necesaria durante sus funciones inmersivas. | 5 |
| **12** | US06 | Configurar perfil de efectos | Como personal técnico, quiero configurar el perfil de efectos asociado a una película para definir las características de su experiencia inmersiva. | 5 |
| **13** | US03 | Consultar catálogo | Como administrador, quiero consultar las películas 4D disponibles para seleccionar cuáles programar en cartelera. | 2 |
| **14** | US07 | Programar función | Como administrador, quiero programar una función 4D para organizar el calendario de la sala. | 5 |
| **15** | US09 | Visualizar resumen diario de funciones | Como personal de sala, quiero ver una vista resumida de las funciones del día para coordinar los turnos. | 2 |
| **16** | US08 | Editar/Cancelar función | Como personal operativo, quiero ajustar o cancelar una función para adaptar la programación ante eventualidades. | 3 |
| **17** | US13 | Iniciar secuencia de efectos | Como personal operativo, quiero iniciar la función 4D para sincronizar el contenido audiovisual con los efectos físicos. | 8 |
| **18** | US17 | Probar canal de efectos | Como personal técnico, quiero probar individualmente un efecto configurado en la sala para verificar su funcionamiento antes de una función. | 5 |
| **19** | US18 | Ajustar intensidad de efectos | Como personal técnico, quiero ajustar el nivel de intensidad de los efectos para adaptar la configuración de una experiencia inmersiva. | 3 |
| **20** | US10 | Consultar estado de butacas | Como personal operativo, quiero consultar el estado de las butacas de una sala para identificar cuáles se encuentran disponibles, habilitadas o fuera de servicio. | 3 |
| **21** | US11 | Habilitar butaca manualmente | Como personal operativo, quiero habilitar o deshabilitar manualmente una butaca para controlar su participación en una función inmersiva. | 3 |
| **22** | US12 | Marcar butaca fuera de servicio | Como personal operativo, quiero marcar una butaca averiada como fuera de servicio para impedir su utilización durante las funciones inmersivas. | 2 |
| **23** | US14 | Parada de emergencia | Como personal operativo, quiero detener rápidamente los efectos de una función para proteger a los asistentes y al equipamiento ante una contingencia. | 3 |
| **24** | US16 | Pausar y reanudar secuencia | Como personal operativo, quiero pausar temporalmente los efectos de una función para resolver un inconveniente sin reiniciar toda la secuencia. | 3 |
| **25** | US15 | Finalizar secuencia de efectos | Como personal operativo, quiero que la ejecución de los efectos finalice automáticamente cuando termine la función para asegurar el cierre correcto de la operación. | 3 |
| **26** | US19 | Registrar componentes de sala | Como personal técnico, quiero dar de alta los equipos instalados en la sala para mantener un registro estructurado. | 3 |
| **27** | US20 | Registrar falla de equipo | Como personal operativo, quiero reportar una avería en un componente específico para solicitar su reparación. | 3 |
| **28** | US21 | Registrar mantenimiento | Como personal técnico, quiero registrar el mantenimiento realizado a un componente para mantener actualizado su historial técnico. | 3 |
| **29** | US22 | Consultar historial de mantenimiento del componente | Como personal técnico, quiero consultar el historial de fallas y mantenimientos de un componente para evaluar su estado operativo. | 3 |
| **30** | US24 | Filtrar incidencias por severidad | Como personal técnico, quiero filtrar los reportes de falla por gravedad para priorizar reparaciones urgentes. | 2 |
| **31** | US23 | Programar mantenimiento preventivo | Como personal técnico, quiero agendar fechas de revisión periódica para recibir un recordatorio del sistema. | 3 |
| **32** | US25 | Bloquear sala por mantenimiento | Como personal técnico, quiero bloquear temporalmente una sala por mantenimiento para evitar que se programen funciones durante el periodo de indisponibilidad. | 3 |
| **33** | US26 | Visualizar dashboard operativo | Como administrador, quiero consultar métricas de uso de salas y fallas frecuentes para evaluar su rendimiento. | 5 |
| **34** | US27 | Comparar indicadores operativos entre salas | Como administrador, quiero comparar los indicadores de uso y funcionamiento entre las salas para identificar diferencias en su desempeño operativo. | 5 |
| **35** | US05 | Buscar películas | Como administrador, quiero buscar películas por título o género para localizar rápidamente el contenido que necesito gestionar. | 2 |
| **36** | US04 | Desactivar contenido | Como administrador, quiero cambiar el estado de una película a inactiva para evitar su programación. | 1 |
| **37** | US33 | Consultar películas mediante API | Como Developer, quiero consultar las películas disponibles mediante el RESTful API, para utilizar la información del catálogo en la aplicación. | 3 |
| **38** | US34 | Registrar una película mediante API | Como Developer, quiero registrar una película mediante el RESTful API, para almacenar nuevos contenidos en el catálogo. | 3 |
| **39** | US35 | Consultar funciones mediante API | Como Developer, quiero consultar las funciones programadas mediante el RESTful API, para obtener información sobre la programación de las salas. | 3 |
| **40** | US36 | Registrar una incidencia mediante API | Como Developer, quiero registrar una incidencia de mantenimiento mediante el RESTful API, para almacenar los problemas reportados en una sala. | 3 |
| **41** | US37 | Consultar estado de una sala mediante API | Como Developer, quiero consultar el estado de una sala mediante el RESTful API, para conocer si se encuentra disponible, en funcionamiento o en mantenimiento. | 2 |
| **42** | US38 | Consultar estado de suscripción mediante API | Como Developer, deseo consultar el estado de la suscripción mediante el RESTful API para habilitar o bloquear dinámicamente funcionalidades en las aplicaciones web. | 3 |

<img src="Kinemo-report/assets/img/3_3-Product-backlog/product-backlog.png" alt="Product Backlog">

Link de Trello: https://trello.com/invite/b/6ac2a2ced29ee515d72506f0/ATTIe716a1812addf4f49367eec67a7e7640A7DDBD9C/kinemo-product-backlog

## Capítulo IV: Product Design

### 4.1. Style Guidelines

En esta sección se establecen los lineamientos visuales y de comunicación utilizados en Kinemo. Estos lineamientos permiten mantener una identidad consistente en los productos digitales del proyecto, definiendo criterios para el uso de la marca, tipografía y paleta de colores.

La propuesta visual de Kinemo busca transmitir innovación, tecnología y entretenimiento inmersivo. Para ello, se emplea una interfaz predominantemente oscura acompañada de tonos morados que permiten destacar los elementos principales y mantener una estética relacionada con la experiencia cinematográfica.

#### 4.1.1. General Style Guidelines

##### Branding

**Concepto de Marca**

Kinemo es una propuesta tecnológica orientada a mejorar la gestión de experiencias cinematográficas 4D. Su identidad visual busca representar conceptos como tecnología, movimiento, inmersión y modernidad mediante una estética minimalista y digital.

El sistema visual de la marca combina fondos oscuros con acentos morados, generando contraste entre el contenido y los principales elementos interactivos. Esta combinación permite mantener una apariencia moderna y coherente con el entorno cinematográfico en el que se desarrolla la propuesta.

**Logotipo Principal**

![Logotipo de Kinemo](Kinemo-report/assets/img/4_1_1-General-Style/01-logo-kinemo.png)

El logotipo de Kinemo está compuesto por un símbolo gráfico acompañado del nombre de la marca. Su diseño mantiene una composición simple y reconocible que facilita su integración dentro de las diferentes interfaces del proyecto.

El símbolo utiliza el color morado característico de Kinemo, mientras que el nombre emplea un tono claro para mantener un contraste adecuado sobre fondos oscuros. Esta combinación permite conservar la identidad visual utilizada en el resto de la interfaz.

---

##### Typography

Kinemo utiliza **Inter** como familia tipográfica principal en sus interfaces. Esta tipografía fue seleccionada por su legibilidad en entornos digitales y por su apariencia moderna, permitiendo mantener consistencia entre títulos, textos descriptivos, botones, etiquetas y elementos de navegación.

La jerarquía tipográfica utiliza diferentes pesos y tamaños de Inter dependiendo de la importancia del contenido. Los títulos principales emplean pesos elevados para generar mayor impacto visual, mientras que los textos descriptivos utilizan pesos regulares que facilitan la lectura.

![Sistema tipográfico de Kinemo](Kinemo-report/assets/img/4_1_1-General-Style/02-typography.png)

| Uso | Familia | Peso | Aplicación |
| --- | --- | --- | --- |
| **Hero / Display** | Inter | 800 | Mensaje principal de la Landing Page |
| **H1** | Inter | 700-800 | Títulos principales |
| **H2** | Inter | 700-800 | Títulos de secciones |
| **H3** | Inter | 600-700 | Títulos de tarjetas y componentes |
| **Body** | Inter | 400 | Descripciones y contenido general |
| **Labels** | Inter | 600-700 | Etiquetas y categorías |
| **Navigation** | Inter | 500-600 | Opciones de navegación |
| **Buttons** | Inter | 600-700 | Llamados a la acción |

Esta jerarquía permite diferenciar visualmente los distintos niveles de información y facilita el recorrido del usuario a través de las interfaces de Kinemo.

---

##### Color Palette

La identidad visual de Kinemo utiliza una paleta predominantemente oscura con tonos morados como colores de acento. Los fondos oscuros permiten crear una apariencia asociada con el ambiente cinematográfico, mientras que los tonos morados destacan botones, etiquetas y otros elementos relevantes de la interfaz.

![Paleta de colores de Kinemo](Kinemo-report/assets/img/4_1_1-General-Style/03-color-palette.png)

**Paleta Principal**

| Color | HEX | RGB | Uso Principal |
| --- | --- | --- | --- |
| **Fondo Principal** | `#0E0F17` | 14, 15, 23 | Fondo general de la interfaz |
| **Fondo de Tarjetas** | `#16171E` | 22, 23, 30 | Cards y contenedores |
| **Fondo Secundario** | `#20212C` | 32, 33, 44 | Elementos secundarios |
| **Morado Principal** | `#8B5CF6` | 139, 92, 246 | CTAs y elementos destacados |
| **Morado Claro** | `#A78BFA` | 167, 139, 250 | Acentos, etiquetas y estados activos |
| **Blanco** | `#FFFFFF` | 255, 255, 255 | Títulos y texto principal |

**Colores Complementarios**

| Color | HEX | Uso Principal |
| --- | --- | --- |
| **Estado Activo** | `#272338` | Fondos de elementos seleccionados o destacados |
| **Texto Secundario** | `#94A3B8` | Descripciones y contenido de menor jerarquía |
| **Bordes** | `#2D2F45` | Separadores y contornos de componentes |
| **Borde Activo** | `#3B385D` | Contornos de elementos activos |
| **Éxito** | `#22C55E` | Estados correctos o resueltos |
| **Advertencia** | `#EAB308` | Alertas y estados en progreso |

**Justificación Cromática**

La combinación de colores utilizada en Kinemo responde a las características visuales y funcionales de la plataforma:

- **Fondos oscuros:** permiten relacionar visualmente la interfaz con el ambiente de una sala de cine y ayudan a destacar el contenido principal.
- **Morado principal:** funciona como el color representativo de Kinemo y se utiliza para resaltar acciones, elementos interactivos y secciones importantes.
- **Morado claro:** complementa el color principal y permite generar diferentes niveles de énfasis.
- **Blanco:** se utiliza principalmente en títulos y textos que requieren alta visibilidad sobre fondos oscuros.
- **Gris azulado:** se emplea para información secundaria, evitando competir visualmente con los títulos y llamados a la acción.
- **Verde y amarillo:** permiten diferenciar estados funcionales dentro de los componentes de la plataforma.

El uso consistente de esta paleta permite mantener una identidad visual uniforme entre las diferentes secciones de Kinemo.

---

##### Communication Tone

La comunicación de Kinemo mantiene un tono profesional, tecnológico y directo. Los mensajes buscan explicar las capacidades de la plataforma de forma breve y comprensible, evitando descripciones excesivamente técnicas cuando no son necesarias.

La comunicación de la marca se centra principalmente en:

- La innovación aplicada a experiencias cinematográficas 4D.
- La facilidad de gestión de las salas.
- La sincronización de efectos y tecnología inmersiva.
- El monitoreo y análisis de información.
- La mejora de la experiencia cinematográfica.
- La presentación clara de los beneficios de la plataforma.

Los llamados a la acción utilizan expresiones breves y reconocibles, facilitando que el usuario comprenda rápidamente cuál es el siguiente paso dentro de la interfaz.

---

##### General Visual Identity

La identidad visual de Kinemo mantiene una composición moderna y minimalista. Las interfaces priorizan espacios amplios, tarjetas claramente diferenciadas, bordes sutiles y una jerarquía visual basada en contraste, tamaño y peso tipográfico.

Los elementos más importantes utilizan el morado principal para captar la atención del usuario, mientras que los fondos y elementos secundarios mantienen tonalidades oscuras. De esta manera, el diseño evita una saturación visual excesiva y conserva una apariencia uniforme en toda la experiencia.

Las decisiones generales de diseño siguen los siguientes criterios:

- Uso consistente de la familia tipográfica Inter.
- Fondos oscuros como base de la interfaz.
- Morado como principal color de identidad y acción.
- Uso de blanco para información de alta jerarquía.
- Uso de tonos secundarios para descripciones y contenido complementario.
- Bordes y contenedores sutiles para organizar la información.
- Diseño visual coherente con un producto tecnológico orientado al entretenimiento cinematográfico.

#### 4.1.2 Web Style Guidelines

Los Web Style Guidelines de Kinemo establecen los criterios visuales y de interacción utilizados en la Landing Page y la Web Application. Estos lineamientos complementan la identidad visual definida previamente y permiten mantener consistencia entre los diferentes componentes de la interfaz.

##### Layout and Spacing

Las interfaces de Kinemo utilizan una estructura basada principalmente en contenedores, CSS Grid y Flexbox. Esta organización permite distribuir los elementos de manera ordenada y adaptar el contenido a diferentes tamaños de pantalla.

Los principales criterios utilizados son:

- Uso de contenedores centrados para organizar el contenido principal.
- Ancho máximo aproximado de 1200px en las secciones principales de la Landing Page.
- Separación clara entre secciones para facilitar la lectura del contenido.
- Uso de Grid para estructuras formadas por tarjetas, como Platform, About Us y Pricing.
- Uso de Flexbox para elementos de navegación, botones y componentes alineados horizontalmente.
- Márgenes y espacios internos consistentes para evitar la saturación visual.

##### Buttons

Los botones de Kinemo permiten diferenciar las acciones principales y secundarias dentro de la interfaz.

**Primary Button**

Utiliza el color morado principal `#8B5CF6` y texto claro. Se emplea para destacar las acciones de mayor importancia, como **Get Started** o **Sign In**.

**Secondary Button**

Utiliza un fondo oscuro acompañado de un borde sutil. Se emplea para acciones complementarias, como **Learn More**, evitando competir visualmente con la acción principal.

Los botones utilizan bordes redondeados y estados visuales de interacción para proporcionar retroalimentación al usuario.

##### Cards

Las tarjetas permiten agrupar información relacionada dentro de un mismo bloque visual. Son utilizadas en diferentes secciones de Kinemo, incluyendo funcionalidades de la plataforma, integrantes del equipo, planes de suscripción y módulos de la Web Application.

Las tarjetas utilizan principalmente:

- Fondo `#16171E` o `#20212C`.
- Bordes sutiles `#2D2F45`.
- Esquinas redondeadas.
- Espaciado interno para separar correctamente los elementos.
- Títulos en color blanco.
- Información secundaria en `#94A3B8`.
- Morado `#8B5CF6` o `#A78BFA` para elementos destacados.

Esta estructura permite mantener una presentación uniforme de la información en las diferentes interfaces.

##### Navigation

La navegación mantiene una estructura sencilla que permite identificar rápidamente las principales opciones disponibles.

En la Landing Page, la barra de navegación proporciona acceso a:

- Platform.
- About Us.
- Pricing.
- Contact.
- Selector de idioma EN / ES.

En la Web Application, la navegación proporciona acceso a las principales áreas disponibles para el usuario, incluyendo el Dashboard y opciones relacionadas con Operations, Maintenance y Analytics. Asimismo, incorpora el selector de idioma y el acceso al perfil del usuario.

Las barras de navegación utilizan fondos oscuros y separadores sutiles para mantener continuidad con el resto de la interfaz.

##### Form Elements

Los formularios de la Web Application mantienen la misma identidad visual del sistema. Los campos utilizan fondos oscuros, bordes sutiles y etiquetas claras para facilitar la identificación de la información solicitada.

En interfaces como Sign In se utilizan:

- Labels visibles para identificar cada campo.
- Inputs con contraste respecto al fondo.
- Placeholders como información complementaria.
- Botones principales en morado.
- Enlaces secundarios para acciones adicionales.

La distribución mantiene una separación suficiente entre los campos para facilitar la lectura y la interacción.

##### Interaction States

Los componentes interactivos utilizan cambios visuales para comunicar su estado al usuario.

Entre los principales estados se consideran:

- **Default:** estado inicial del componente.
- **Hover:** cambio visual al posicionar el cursor sobre elementos interactivos.
- **Active:** utiliza fondos o bordes destacados para representar una opción seleccionada.
- **Success:** utiliza `#22C55E` para representar estados satisfactorios o completados.
- **Warning:** utiliza `#EAB308` para representar advertencias o procesos que requieren atención.

Además del color, se utilizan etiquetas textuales e iconos cuando es necesario para evitar que la interpretación de un estado dependa exclusivamente de su representación cromática.

##### Responsive Design

Kinemo utiliza una estructura adaptable para mantener la correcta visualización de la Landing Page y la Web Application en diferentes tamaños de pantalla.

Las estructuras de múltiples columnas pueden reorganizarse verticalmente cuando disminuye el espacio disponible. Asimismo, las imágenes, tarjetas, botones y contenedores se ajustan al ancho disponible para evitar desplazamientos horizontales innecesarios.

La combinación de Grid, Flexbox y unidades adaptables permite conservar la jerarquía visual y facilitar la interacción con la plataforma en diferentes resoluciones.

### 4.2. Information Architecture

La arquitectura de información de Kinemo define la forma en que el contenido y las funcionalidades se organizan, etiquetan y presentan dentro de sus productos digitales. Su objetivo es facilitar la comprensión de la plataforma y permitir que cada usuario encuentre las funcionalidades necesarias de acuerdo con el contexto en el que se encuentra.

Kinemo cuenta con dos interfaces principales: la **Landing Page**, orientada a presentar públicamente la propuesta de valor del producto, y la **Web Application**, orientada a la gestión y operación de las experiencias cinematográficas 4D.

La Landing Page utiliza una estructura principalmente lineal, donde el visitante puede conocer progresivamente la plataforma, el equipo, los planes disponibles y las alternativas de contacto. Por otro lado, la Web Application utiliza una organización modular, permitiendo acceder a diferentes funcionalidades relacionadas con la operación de las salas de cine.

#### 4.2.1. Organization Systems

Kinemo utiliza diferentes sistemas de organización dependiendo del producto digital y del tipo de información presentada.

##### Landing Page

La Landing Page emplea principalmente un **sistema de organización por tópicos**, donde cada sección agrupa información relacionada con un aspecto específico de Kinemo.

La estructura principal se organiza de la siguiente manera:

| Tópico | Descripción |
| --- | --- |
| **Home** | Presenta la propuesta de valor principal de Kinemo y las acciones iniciales disponibles para el visitante. |
| **Platform** | Expone las principales capacidades de la solución para la gestión de experiencias cinematográficas 4D. |
| **About Us** | Presenta al equipo responsable del desarrollo de Kinemo. |
| **Pricing** | Permite conocer y comparar los diferentes planes disponibles. |
| **Contact** | Presenta la llamada a la acción final para iniciar el contacto con Kinemo. |
| **Terms and Conditions** | Proporciona acceso a la información relacionada con las condiciones de uso del servicio. |

El contenido mantiene una organización jerárquica que comienza presentando qué es Kinemo, continúa explicando sus principales capacidades y finaliza con información comercial y de contacto.

**Home**

La sección inicial comunica de manera directa la propuesta de valor de Kinemo como tecnología orientada a experiencias cinematográficas 4D. Incluye los llamados a la acción **Get Started** y **Learn More**, permitiendo al visitante continuar su recorrido hacia las secciones principales.

**Platform**

Las capacidades principales de Kinemo se organizan en cuatro categorías:

- Effects Synchronization.
- Simplified Management Software.
- Maintenance Incident Control.
- Performance Analytics.

La sección complementa estas categorías mediante elementos visuales relacionados con la sincronización de salas y el seguimiento de incidencias.

**About Us**

Presenta a los integrantes responsables del desarrollo de Kinemo mediante tarjetas individuales que contienen fotografía, nombre e información de identificación académica.

**Pricing**

Organiza las alternativas comerciales de Kinemo en tres planes:

- Starter.
- Growth.
- Enterprise.

Esta estructura permite comparar visualmente las características y alcance de cada alternativa.

**Contact**

Representa el cierre del recorrido principal de la Landing Page. Su propósito es dirigir al visitante hacia una acción concreta relacionada con el inicio del servicio o contacto comercial.

##### Web Application

La Web Application utiliza un **sistema de organización jerárquico y modular**. Después de autenticarse, el usuario accede al Dashboard, desde donde puede ingresar a los diferentes módulos de la plataforma según las tareas que necesite realizar.

La estructura de navegación identificada en la aplicación se organiza mediante los siguientes módulos. Estas etiquetas representan accesos funcionales de la interfaz y no necesariamente corresponden de forma directa con los nombres arquitectónicos de los Bounded Contexts definidos posteriormente.

| Módulo | Propósito |
| --- | --- |
| **Sign In** | Permite autenticar al usuario mediante correo electrónico y contraseña. |
| **Dashboard** | Funciona como punto central de acceso a las funcionalidades de la aplicación. |
| **Catalog** | Agrupa funcionalidades relacionadas con el catálogo de contenido 4D. |
| **Scheduling** | Agrupa funcionalidades relacionadas con la programación de funciones. |
| **Room Readiness** | Permite acceder a funcionalidades relacionadas con la preparación y disponibilidad de las salas. |
| **Maintenance** | Agrupa funcionalidades relacionadas con el mantenimiento y seguimiento de incidencias. |
| **Subscription** | Permite acceder a funcionalidades relacionadas con planes y suscripciones. |
| **Profile** | Presenta información relacionada con el usuario y su rol dentro de la plataforma. |
| **About** | Proporciona información complementaria sobre Kinemo. |

El **Dashboard** funciona como el nivel principal de navegación después del inicio de sesión y proporciona acceso a las funcionalidades disponibles mediante diferentes módulos y tarjetas.

En la interfaz se distinguen funcionalidades destinadas a la administración y operación de Kinemo. Entre los accesos mostrados se encuentran módulos relacionados con catálogo, programación, salas, ticketing, analítica, suscripción, control de asientos, ejecución y mantenimiento.

De esta manera, a diferencia del recorrido principalmente lineal de la Landing Page, la Web Application permite que el usuario seleccione directamente el módulo correspondiente a la tarea que necesita realizar.

#### 4.2.2. Labeling Systems

El sistema de etiquetado de Kinemo utiliza términos breves y relacionados directamente con las funcionalidades que representan. Se busca evitar nombres ambiguos y mantener consistencia entre los enlaces de navegación, botones, módulos y secciones.

##### Landing Page

Las principales etiquetas utilizadas son:

| Etiqueta | Propósito |
| --- | --- |
| **Platform** | Identifica la sección donde se presentan las capacidades principales de Kinemo. |
| **About Us** | Identifica la sección donde se presenta el equipo del proyecto. |
| **Pricing** | Identifica la sección de planes y precios. |
| **Contact** | Identifica la sección destinada al contacto con Kinemo. |
| **Get Started** | CTA principal que dirige al visitante hacia el inicio del proceso de contacto. |
| **Learn More** | CTA secundario que permite conocer las funcionalidades de la plataforma. |
| **Most Popular** | Destaca visualmente el plan comercial recomendado. |
| **EN / ES** | Permite seleccionar el idioma de la interfaz. |
| **Terms and Conditions** | Permite acceder a las condiciones de uso correspondientes. |

##### Web Application

Dentro de la aplicación se utilizan etiquetas orientadas a las tareas que puede realizar el usuario.

| Etiqueta | Propósito |
| --- | --- |
| **Sign In** | Acción utilizada para iniciar sesión. |
| **Dashboard** | Identifica el punto principal de acceso a los módulos. |
| **Operations** | Agrupa accesos relacionados con las operaciones de las salas. |
| **Maintenance** | Identifica las funcionalidades relacionadas con mantenimiento. |
| **Analytics** | Identifica el acceso a información y análisis del funcionamiento de la plataforma. |
| **Catalog** | Identifica el módulo de gestión del catálogo 4D. |
| **Scheduling** | Identifica el módulo relacionado con programación. |
| **Room Readiness** | Identifica las funcionalidades de preparación de salas. |
| **Subscription** | Identifica la gestión de planes y suscripciones. |
| **Profile** | Identifica la información asociada al usuario autenticado. |
| **EN / ES** | Permite alternar el idioma de la aplicación. |

Las etiquetas mantienen una relación directa con las acciones y contenidos disponibles para reducir el esfuerzo necesario para comprender la interfaz.

Además, los módulos del Dashboard utilizan elementos visuales e iconos como apoyo a las etiquetas textuales, facilitando su reconocimiento.

#### 4.2.3. SEO Tags and Meta Tags

La estrategia SEO de Kinemo se aplica principalmente a la **Landing Page**, debido a que corresponde a la interfaz pública del producto y funciona como uno de los principales puntos de entrada para potenciales clientes interesados en soluciones tecnológicas para experiencias cinematográficas 4D.

Por otro lado, la **Web Application** posee un propósito principalmente operativo y requiere autenticación para acceder a sus funcionalidades. Por esta razón, su contenido interno no constituye el principal objetivo de posicionamiento en motores de búsqueda.

##### Landing Page

Para la Landing Page se consideran etiquetas orientadas a describir correctamente el contenido del sitio, facilitar su indexación y mejorar la forma en que Kinemo se presenta al compartir la página en plataformas externas.

Las principales etiquetas consideradas son:

- **Title:** identifica el sitio y comunica que Kinemo está relacionado con tecnología para cine 4D.
- **Description:** resume la propuesta de valor de Kinemo, incluyendo la gestión de asientos de movimiento, efectos sincronizados y analítica.
- **Keywords:** documenta términos relacionados con tecnología de cine 4D, gestión de salas y experiencias inmersivas.
- **Author:** identifica al equipo responsable del producto.
- **Robots:** establece las indicaciones de indexación y seguimiento para los motores de búsqueda.
- **Canonical:** identifica la URL principal de la Landing Page.
- **Open Graph:** define cómo se presenta Kinemo al compartir la página en plataformas compatibles.
- **Twitter Card:** proporciona información para generar una vista previa enriquecida al compartir el sitio en plataformas compatibles.

Una posible implementación dentro del `<head>` de la Landing Page es la siguiente. Los valores `LANDING_PAGE_URL` y `LANDING_PAGE_IMAGE_URL` representan placeholders que deberán ser reemplazados por las direcciones públicas correspondientes una vez que la Landing Page se encuentre desplegada en su entorno definitivo:

```html
<head>
    <!-- Basic Metadata -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Kinemo | 4D Cinema Technology</title>

    <!-- SEO Metadata -->
    <meta
        name="description"
        content="Kinemo centralizes motion seat control, synchronized environmental effects, maintenance monitoring and real-time analytics for immersive 4D cinema experiences."
    >
    <meta
        name="keywords"
        content="Kinemo, 4D cinema technology, 4D theater management, motion seats, synchronized cinema effects, immersive cinema technology"
    >
    <meta name="author" content="Kinemo Team">
    <meta name="robots" content="index, follow">

    <!-- Canonical -->
    <link rel="canonical" href="LANDING_PAGE_URL">

    <!-- Open Graph -->
    <meta property="og:title" content="Kinemo | 4D Cinema Technology">
    <meta
        property="og:description"
        content="Technology for managing immersive 4D cinema experiences."
    >
    <meta property="og:type" content="website">
    <meta property="og:url" content="LANDING_PAGE_URL">
    <meta property="og:image" content="LANDING_PAGE_IMAGE_URL">
    <meta property="og:site_name" content="Kinemo">
    <meta property="og:locale" content="en_US">

    <!-- Twitter / X Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Kinemo | 4D Cinema Technology">
    <meta
        name="twitter:description"
        content="Technology for managing immersive 4D cinema experiences."
    >
    <meta name="twitter:image" content="LANDING_PAGE_IMAGE_URL">
</head>
```

#### 4.2.4. Searching Systems

La Landing Page de Kinemo no incorpora un sistema de búsqueda interno debido a que su contenido se encuentra organizado en un número reducido de secciones y puede recorrerse directamente mediante la barra de navegación.

El visitante puede acceder a **Platform, About Us, Pricing** y **Contact** sin necesidad de realizar búsquedas textuales. Esta decisión permite mantener una experiencia simple y evita incorporar un componente que no resulta necesario para la cantidad de información presentada.

En la Web Application, la localización de funcionalidades se realiza principalmente mediante la navegación por módulos y las opciones disponibles en el Dashboard. Cada funcionalidad se encuentra agrupada de acuerdo con su propósito dentro de la plataforma.

En aquellos módulos que manejan conjuntos de información más amplios, las búsquedas y filtros pueden implementarse dentro del contexto específico correspondiente, en lugar de utilizar un buscador global para toda la aplicación.

#### 4.2.5. Navigation Systems

Kinemo utiliza diferentes mecanismos de navegación dependiendo de la interfaz y del contexto del usuario.

##### Landing Page

La Landing Page utiliza una navegación principalmente global y contextual.

La **navegación global** se encuentra disponible mediante el header y permite acceder directamente a:

- Platform.
- About Us.
- Pricing.
- Contact.
- Selector de idioma EN / ES.

Asimismo, se utilizan llamados a la acción que permiten realizar desplazamientos contextuales dentro de la página:

- **Get Started:** dirige al usuario hacia la sección de contacto.
- **Learn More:** dirige al usuario hacia la sección Platform.

El footer complementa esta navegación proporcionando acceso a información legal mediante **Terms and Conditions**.

El recorrido principal puede representarse de la siguiente manera:

**Home → Platform → About Us → Pricing → Contact**

##### Web Application

La Web Application utiliza una navegación jerárquica y modular. El usuario inicia su recorrido en la pantalla de autenticación y, después de iniciar sesión, accede al Dashboard.

Desde el Dashboard puede dirigirse a los diferentes módulos disponibles según las tareas que necesite realizar. La barra superior mantiene accesos a áreas generales como **Dashboard, Operations, Maintenance** y **Analytics**, además de opciones relacionadas con el idioma y el perfil.

La navegación puede representarse de forma general de la siguiente manera:

**Sign In → Dashboard → Módulo seleccionado → Funcionalidad específica**

Esta estructura permite que el usuario acceda directamente a las funciones necesarias sin recorrer de forma secuencial toda la aplicación.

### 4.3 Landing Page UI Design

#### 4.3.1. Landing Page Wireframe

[Click here for Figma](https://www.figma.com/design/h8gZ1ryldnIq3f485Vx13T/Landing-Page?node-id=0-1&t=MqyMHgKjflZ9zmfu-1)

Los wireframes de la Landing Page de Kinemo definen la estructura fundamental de la interfaz, priorizando la organización del contenido y la jerarquía visual antes de aplicar elementos de diseño detallados. Se diseñaron utilizando elementos esquemáticos en escala de grises para facilitar la evaluación de la arquitectura de información sin distracciones visuales.

**1. Home (Hero Section)**

La propuesta inicial del wireframe Home presenta una estructura que guía la vista del usuario hacia la propuesta de valor y las principales acciones de la página. En la parte superior se ubica el logotipo de Kinemo acompañado de las principales opciones de navegación consideradas durante esta primera etapa del diseño.

El Hero Section presenta el mensaje principal **"Lleva la experiencia 4D a tus salas de cine sin altos costos"**, acompañado por una descripción relacionada con la centralización del control de asientos de movimiento, efectos ambientales sincronizados y analítica en tiempo real.

Debajo del mensaje principal se ubican los llamados a la acción **"Empezar ahora"** y **"Conoce más"**, permitiendo dirigir al usuario hacia las siguientes secciones de la Landing Page.

![Landing Wireframe - Home](Kinemo-report/assets/img/landing-page/wireframe-home.png)

---

**2. Plataforma (Platform Section)**

La sección de plataforma presenta las principales capacidades de Kinemo mediante una distribución que combina información textual con espacios destinados a representaciones visuales de la solución.

Las principales funcionalidades consideradas son:

- **Sincronización de efectos:** coordinación de los asientos de movimiento y efectos ambientales para mantenerlos alineados con la experiencia cinematográfica.
- **Software de gestión simplificado:** panel centralizado que facilita la administración de las diferentes salas desde una misma plataforma.
- **Gestión de incidencias de mantenimiento:** seguimiento de incidencias relacionadas con el funcionamiento de los equipos y recursos 4D.
- **Análisis de rendimiento:** presentación de información relacionada con la ocupación, operación y rendimiento de las salas.

La sección reserva además espacios para recursos visuales relacionados con el software y la información operativa de la plataforma.

![Landing Wireframe - Platform](Kinemo-report/assets/img/landing-page/wireframe-plataform.png)

---

**3. Planes (Pricing Section)**

La sección de **Pricing** adopta un layout centrado que facilita la comparación visual entre las diferentes opciones de suscripción.

El wireframe organiza los planes mediante una cuadrícula de tres columnas, donde cada tarjeta representa una alternativa disponible. Esta distribución permite comparar de forma rápida las opciones comerciales de Kinemo y mantiene una separación suficiente entre los diferentes bloques de información.

![Landing Wireframe - Pricing](Kinemo-report/assets/img/landing-page/wireframe-pricing.png)

---

**4. Contacto / Sección Final**

La sección final del wireframe funciona como un llamado a la acción orientado a que el visitante continúe con el proceso de contacto o contratación del servicio.

El bloque principal concentra el título, una descripción breve y la acción principal. El footer complementa esta sección mediante el logotipo de Kinemo, información de derechos reservados y accesos a información complementaria.

![Landing Wireframe - Contact](Kinemo-report/assets/img/landing-page/wireframe-contact.png)

---

##### Evolución del Wireframe al Mock-up

Durante la evolución del diseño desde los wireframes hacia el mock-up de alta fidelidad se realizaron algunos ajustes en la estructura de la Landing Page con el objetivo de mejorar la navegación y adaptar la interfaz a la propuesta final de Kinemo.

Entre los principales cambios realizados se encuentra la incorporación de la sección **About Us**, destinada a presentar al equipo responsable del proyecto. Asimismo, la navegación fue refinada incorporando un acceso directo a esta nueva sección y el selector de idioma **EN / ES**.

Las acciones preliminares **Sign In** y **Suscribe**, consideradas durante la etapa inicial de wireframing, fueron retiradas de la navegación principal de la versión final de la Landing Page. En su lugar, la página utiliza llamados a la acción integrados en las secciones correspondientes, como **Get Started** y **Learn More**.

Como resultado, la estructura final utilizada en el mock-up se organiza de la siguiente manera:

**Home → Platform → About Us → Pricing → Contact**

Estos cambios representan la evolución del diseño entre una representación estructural de baja fidelidad y la propuesta visual definitiva presentada en el mock-up.

#### 4.3.2. Landing Page Mock-up

[Link de Landing Page Mock-up](https://www.figma.com/design/2kl9zH6WgBNDCJAPYMhC0v/Landing-Page-Mock-up?node-id=0-1&t=01NT4lXX92lQUrnf-1)

Los mockups de alta fidelidad de la Landing Page de **Kinemo** fueron desarrollados siguiendo el sistema de diseño definido para la plataforma. La propuesta utiliza una estética oscura y tecnológica, orientada al sector del entretenimiento inmersivo 4D. Se emplea la tipografía **Inter**, una paleta basada en tonos oscuros y morados, bordes sutiles, tarjetas con esquinas redondeadas e indicadores visuales para representar estados y métricas del sistema.

La interfaz utiliza como colores principales el fondo oscuro **#0E0F17**, las tarjetas **#16171E** y **#20212C**, el morado principal **#8B5CF6**, el morado claro **#A78BFA**, el texto blanco **#FFFFFF** y el texto secundario **#94A3B8**.

---

**1. Home (Hero Section)**

El mockup de la sección **Home** presenta la propuesta principal de Kinemo mediante una composición visual relacionada con la experiencia cinematográfica 4D. La imagen utilizada como fondo permite contextualizar el servicio desde el primer contacto con la Landing Page, mientras que un overlay oscuro facilita la lectura del contenido.

**Header**

- Fondo oscuro **#090A10** con una línea inferior sutil.
- Logotipo de **Kinemo** ubicado en la parte izquierda.
- Menú de navegación con las opciones **Platform, About Us, Pricing** y **Contact**.
- Selector de idioma **EN / ES** ubicado en la parte derecha.
- Los enlaces mantienen una apariencia simple para facilitar el acceso directo a las principales secciones de la Landing Page.

**Hero Section**

- Imagen de fondo relacionada con una sala de cine equipada con asientos para una experiencia 4D.
- Overlay oscuro aplicado sobre la imagen para mejorar el contraste y la legibilidad.
- Etiqueta superior **"4D CINEMA TECHNOLOGY"**.
- Titular principal **"Bring the 4D experience to your cinema screens without high costs"**.
- La frase **"without high costs"** utiliza el color morado claro **#A78BFA** para generar énfasis visual.
- Descripción **"Centralize motion seat control, synchronized environmental effects, and real-time analytics without replacing your existing infrastructure."**
- Botón principal **"Get Started"**.
- Botón secundario **"Learn More"**.

La sección busca comunicar desde el primer momento la propuesta de valor de Kinemo, destacando la posibilidad de incorporar y gestionar experiencias 4D sin necesidad de reemplazar completamente la infraestructura existente.

![Landing Mock-up - Home](Kinemo-report/assets/img/4_3_2-landing-mock-up/landing-page-1.png)

---

**2. Plataforma (Platform Section)**

La sección **Platform** presenta las principales funcionalidades de Kinemo mediante una estructura de dos columnas. Esta distribución permite mostrar las capacidades principales del sistema junto con una representación visual de información operativa.

**Encabezado de sección**

- Etiqueta **"PLATFORM"** en color morado claro.
- Título principal **"Everything you need to manage your immersive theater"**.
- Fondo oscuro que mantiene continuidad con el resto de la Landing Page.

**Columna izquierda**

La columna izquierda presenta cuatro tarjetas funcionales con fondo oscuro, bordes sutiles y esquinas redondeadas:

- **Effects Synchronization:** coordinación de los asientos de movimiento y efectos ambientales relacionados con la experiencia 4D.
- **Simplified Management Software:** panel centralizado orientado a facilitar la administración de las diferentes salas.
- **Maintenance Incident Control:** seguimiento de incidencias relacionadas con el funcionamiento de los equipos.
- **Performance Analytics:** presentación de información relacionada con ocupación, operación y rendimiento de las salas.

Cada funcionalidad está acompañada por un icono que facilita su identificación visual.

**Columna derecha**

La columna derecha presenta dos módulos relacionados con la operación de la plataforma:

- **Live Synchronization:** muestra diferentes pantallas mediante indicadores como **OK** y **Alert**, acompañados por una representación gráfica de su actividad.
- **Recent Incidents:** muestra incidencias recientes junto con estados como **Resolved**, **In progress** y **Pending**.

Los estados utilizan diferentes colores acompañados por etiquetas textuales para facilitar su reconocimiento sin depender exclusivamente del color.

![Landing Mock-up - Platform](Kinemo-report/assets/img/4_3_2-landing-mock-up/landing-page-2.png)

---

**3. Nosotros / Equipo (About Us Section)**

La sección **About Us** presenta a los integrantes responsables del desarrollo de Kinemo. Mantiene la misma identidad visual oscura y utiliza tarjetas individuales para organizar la información de cada miembro.

**Encabezado**

- Etiqueta superior **"ABOUT US"** en color morado claro.
- Título principal **"Meet the Team"**.
- Texto descriptivo **"The creators behind Kinemo, building next-generation technology for modern cinema spaces."**

**Tarjetas del equipo**

La sección utiliza una cuadrícula de cuatro tarjetas con fondo oscuro, bordes sutiles y esquinas redondeadas.

Cada tarjeta contiene:

- Fotografía circular del integrante.
- Borde morado alrededor de la fotografía.
- Nombre completo.
- Código de estudiante en color morado claro.

Las tarjetas mantienen una estructura visual uniforme para conservar la consistencia de la interfaz.

**Video de presentación**

Debajo de las tarjetas del equipo se incorpora un recurso audiovisual relacionado con la tecnología utilizada en experiencias cinematográficas con movimiento.

El recurso complementa la información presentada en la Landing Page mediante una referencia visual de este tipo de tecnología y se integra dentro de un contenedor alineado con el resto de los elementos de la sección.

![Landing Mock-up - About Us](Kinemo-report/assets/img/4_3_2-landing-mock-up/landing-page-3.png)

---

**4. Planes (Pricing Section)**

La sección **Pricing** presenta los diferentes planes disponibles de Kinemo mediante tres tarjetas principales. La distribución permite comparar visualmente las características y precios de cada alternativa.

**Encabezado de sección**

- Etiqueta **"PRICING"** en color morado claro.
- Título principal **"Simple, transparent pricing"**.
- Banner informativo con el mensaje **"All plans include hardware leasing options with up to 20% savings"**.

**Grid de planes**

La información se organiza mediante una cuadrícula de tres columnas correspondiente a los planes **Starter**, **Growth** y **Enterprise**.

**Starter — $490/mo**

Incluye:

- Hasta **3 pantallas conectadas**.
- Sincronización básica.
- Panel de control unificado.
- Soporte por correo electrónico.
- Reportes analíticos mensuales.

**Growth — $1,190/mo**

Incluye:

- Hasta **12 pantallas conectadas**.
- Sincronización avanzada.
- Gestión de incidencias y telemetría.
- Soporte prioritario.
- Analítica en tiempo real.
- API de integración.

Este plan se diferencia visualmente mediante un borde morado y la etiqueta **"MOST POPULAR"**.

**Enterprise — Custom**

Incluye:

- Pantallas conectadas ilimitadas.
- SLA garantizado del **99.9%**.
- Integración con sistemas personalizados.
- Customer Success Manager dedicado.
- On-site onboarding.
- Contratos flexibles.

Las tres tarjetas utilizan fondos oscuros, bordes sutiles, esquinas redondeadas y una jerarquía tipográfica que permite diferenciar el nombre del plan, precio, descripción y características incluidas.

![Landing Mock-up - Pricing](Kinemo-report/assets/img/4_3_2-landing-mock-up/landing-page-4.png)

---

**5. Contacto / Call to Action y Footer**

La sección final de la Landing Page funciona como un **Call to Action (CTA)** orientado a incentivar al usuario a establecer contacto con Kinemo y conocer las alternativas disponibles para implementar la solución.

**Call to Action**

Está compuesta por:

- Etiqueta superior **"CONTACT"** en color morado claro.
- Título principal **"Ready to transform your cinema experience?"**.
- Texto descriptivo **"Talk to our team and discover how Kinemo can elevate your cinema screens."**
- Botón principal **"Get Started"**.
- Texto complementario relacionado con la aceptación de los **Terms & Conditions**.
- Enlace **"Need custom enterprise solutions? Contact sales"**.

**Footer**

El footer mantiene un fondo oscuro similar al utilizado en la barra de navegación, proporcionando continuidad visual entre el inicio y el cierre de la Landing Page.

Incluye:

- Nombre y logotipo de **Kinemo**.
- Texto **"© 2026 Kinemo · All rights reserved"**.
- Enlace **"terms and conditions"**.

![Landing Mock-up - Contact](Kinemo-report/assets/img/4_3_2-landing-mock-up/landing-page-5.png)

---

##### Consideraciones de Diseño Responsivo

La Landing Page utiliza una estructura adaptable para mantener la correcta visualización de sus componentes en diferentes tamaños de pantalla.

Las principales consideraciones son:

- El contenido se organiza mediante contenedores con un ancho máximo aproximado de **1200px**.
- Las secciones mantienen espacios amplios para diferenciar visualmente cada bloque.
- Las tarjetas utilizan estructuras basadas en **CSS Grid** y **Flexbox**.
- Las estructuras de varias columnas pueden reorganizarse verticalmente cuando disminuye el espacio disponible.
- Los botones utilizan áreas de interacción amplias y estados *hover*.
- Las imágenes se adaptan al espacio disponible.
- Los elementos visuales mantienen bordes redondeados de aproximadamente **8px y 16px**.
- La interfaz utiliza texto blanco para información principal y **#94A3B8** para información secundaria.
- **#8B5CF6** y **#A78BFA** se utilizan para destacar acciones y elementos importantes.

##### Identidad Visual

La propuesta visual busca mantener una apariencia tecnológica y consistente con el concepto de **entretenimiento inmersivo 4D**.

El uso de fondos oscuros permite relacionar visualmente la interfaz con el ambiente de una sala de cine, mientras que los tonos morados funcionan como elementos de identidad y permiten destacar las principales acciones.

Las tarjetas, indicadores de estado, botones, módulos de información y recursos audiovisuales mantienen una composición uniforme durante todo el recorrido de la Landing Page.

De esta manera, el diseño mantiene una identidad visual consistente entre las secciones **Home, Platform, About Us, Pricing** y **Contact**.

### 4.4 Web Applications UX/UI Design

#### 4.4.1 Web Applications Wireframes

> _Pendiente — completar en `feature/web-app-ux`._

#### 4.4.2 Web Applications Wireflow Diagrams

> _Pendiente — completar en `feature/web-app-ux`._

#### 4.4.3 Web Applications User Flow Diagrams

> _Pendiente — completar en `feature/web-app-ux`._

### 4.5 Web Applications Prototyping

> _Pendiente — completar en `feature/web-app-prototyping`._

### 4.6 Domain-Driven Software Architecture

#### 4.6.1. Design-Level EventStorming

El Design-Level EventStorming permitió al equipo refinar el modelo de dominio identificado durante el modelado inicial de Kinemo 4D. La sesión se enfocó en revisar las funcionalidades del dominio, agruparlas según sus responsabilidades y establecer límites claros entre las diferentes áreas del negocio.

Durante esta actividad se analizaron los eventos, comandos, consultas y responsabilidades asociadas a las principales funcionalidades de la solución. A partir de este refinamiento se identificaron y delimitaron los Bounded Contexts que representan las diferentes áreas del dominio de Kinemo 4D.

Como resultado del proceso de refinamiento, se identificaron los siguientes nueve Bounded Contexts:

1. **BC01 — Movie & Sensory Content Management**  
   Gestiona el registro y administración de las películas 4D y su contenido sensorial asociado, incluyendo la configuración de efectos, intensidades y archivos necesarios para su reproducción.

2. **BC02 — Scheduling & Calendar**  
   Gestiona la programación de las funciones 4D, considerando horarios, disponibilidad, conflictos de programación, reprogramación y cancelación de funciones.

3. **BC03 — Room & Resource Readiness**  
   Gestiona la preparación y disponibilidad de las salas para las funciones 4D, incluyendo el bloqueo de salas por mantenimiento y su posterior liberación.

4. **BC04 — Ticketing Integration**  
   Gestiona la integración con el sistema externo de boletería para sincronizar la información necesaria de las funciones y la ocupación de las salas.

5. **BC05 — Seat Allocation & Control**  
   Gestiona la asignación y control de las butacas asociadas a las funciones 4D, incluyendo la actualización de sus estados y la activación de las butacas vendidas.

6. **BC06 — 4D Execution & Synchronization**  
   Gestiona la ejecución de las funciones 4D y la sincronización de los efectos sensoriales con la película. También contempla la pausa, reanudación, desviaciones de sincronización y situaciones de emergencia durante la ejecución.

7. **BC07 — Resource Testing & Maintenance**  
   Gestiona las pruebas de los canales y componentes del sistema 4D, el registro de incidencias y las actividades de mantenimiento correctivo y preventivo de los recursos.

8. **BC08 — Operational Analytics & Reporting**  
   Gestiona la recopilación de métricas operativas y la generación de dashboards y reportes relacionados con la operación de las funciones y el mantenimiento.

9. **BC09 — Subscription & Service Management**  
   Gestiona los planes de suscripción del servicio, incluyendo la selección del plan, contratación, procesamiento del pago, activación, renovación y cambio de plan.

El refinamiento también permitió establecer las principales relaciones entre los Bounded Contexts mediante los eventos y comandos identificados durante la sesión. De esta manera, los cambios producidos en un contexto pueden desencadenar acciones en otro contexto cuando existe una dependencia dentro del dominio.

Por ejemplo, el evento **“Película 4D Registrada”** en el BC01 permite iniciar la programación de una función 4D en el BC02. Asimismo, el evento **“Función 4D Programada”** permite solicitar la verificación de la preparación de la sala en el BC03. De manera similar, la actualización de la ocupación proveniente del BC04 permite gestionar la activación de las butacas vendidas en el BC05.

En la ejecución de una función, el BC06 puede generar eventos relacionados con incidencias de hardware que son gestionados por el BC07. Posteriormente, los resultados de la ejecución y del mantenimiento pueden ser utilizados por el BC08 para generar métricas y reportes operativos. Finalmente, el BC09 permite gestionar la suscripción que habilita el acceso a los servicios de Kinemo 4D.

La siguiente imagen evidencia el resultado del Design-Level EventStorming realizado por el equipo:

![Design-Level EventStorming de Kinemo 4D](Kinemo-report/assets/img/4_6_1-Design-level-eventstorming/eventstorming.jpg)

#### 4.6.2. Software Architecture Context Diagram

El **Context Diagram** representa a **Kinemo 4D** como un único sistema central, mostrando los actores que interactúan con la solución y los sistemas externos con los que se integra. Este diagrama se elaboró aplicando la notación **C4 Model**, permitiendo visualizar el alcance de Kinemo 4D y sus principales relaciones con el entorno, sin mostrar todavía la estructura interna de la solución.

Los actores identificados son:

- **Gerente:** responsable de administrar la operación de Kinemo 4D, incluyendo la gestión de películas y contenido sensorial, programación de funciones, consulta de información operativa y gestión del servicio.
- **Técnico:** responsable de las actividades técnicas relacionadas con la preparación, pruebas, mantenimiento y atención de incidencias de los recursos 4D.

Asimismo, Kinemo 4D mantiene integración con los siguientes sistemas externos:

- **Sistema Externo de Boletería:** proporciona información relacionada con las funciones, ventas y ocupación de las salas.
- **Hardware 4D:** ejecuta los efectos sensoriales y las acciones físicas asociadas a las funciones 4D.
- **Pasarela de Pagos:** procesa los pagos asociados a las suscripciones del servicio.
- **Servicio de Facturación Electrónica:** permite gestionar la emisión de comprobantes relacionados con las suscripciones.
- **Almacenamiento de Archivos:** permite almacenar los archivos multimedia y contenido sensorial utilizados por las películas 4D.
- **Servicio de Notificaciones:** permite enviar alertas y notificaciones relacionadas con la operación, mantenimiento y suscripciones.

![Software Architecture Context Diagram - Kinemo 4D](Kinemo-report/assets/img/4_6_2-Software-architecture-context-diagram/diagram-context.png)

Como se observa en el diagrama, **Kinemo 4D centraliza la interacción entre el Gerente y el Técnico y los servicios externos necesarios para soportar la operación de la plataforma**. Esta vista permite identificar claramente el límite del sistema y sus principales dependencias externas, sin entrar todavía en el detalle de los Containers o Bounded Contexts que conforman la solución.

#### 4.6.3. Software Architecture Container Diagrams

El **Container Diagram** detalla los elementos de alto nivel que conforman la arquitectura de software de Kinemo 4D, las principales responsabilidades de cada container, las decisiones tecnológicas adoptadas y la manera en que estos containers se comunican entre sí.

La solución está compuesta por:

- **Landing Page B2B:** sitio de presentación de Kinemo 4D que comunica la propuesta de valor del servicio y permite consultar los planes disponibles.

- **Web Application:** aplicación web utilizada por el Gerente y el Técnico para acceder a las funcionalidades de gestión y operación de Kinemo 4D, según las responsabilidades de cada actor.

- **RESTful API:** punto de entrada para las solicitudes provenientes de la aplicación web y encargado de permitir el acceso a las funcionalidades proporcionadas por el backend.

- **9 Bounded Contexts:** áreas independientes encargadas de representar responsabilidades específicas del dominio de Kinemo 4D: **BC01 — Movie & Sensory Content Management**, **BC02 — Scheduling & Calendar**, **BC03 — Room & Resource Readiness**, **BC04 — Ticketing Integration**, **BC05 — Seat Allocation & Control**, **BC06 — 4D Execution & Synchronization**, **BC07 — Resource Testing & Maintenance**, **BC08 — Operational Analytics & Reporting** y **BC09 — Subscription & Service Management**.

- **Persistencia:** cada Bounded Context administra la información correspondiente a su responsabilidad, buscando reducir el acoplamiento entre las diferentes áreas del dominio.

- **Sistemas externos:** Kinemo 4D se integra con el **Sistema Externo de Boletería**, **Hardware 4D**, **Pasarela de Pagos**, **Servicio de Facturación Electrónica**, **Almacenamiento de Archivos** y **Servicio de Notificaciones**, según las necesidades de cada Bounded Context.

![Software Architecture Container Diagram - Kinemo 4D](Kinemo-report/assets/img/4_6_3-Software-architecture-container-diagrams/diagram-container.png)

La interacción principal con la solución se realiza mediante la **Web Application**, mientras que la **Landing Page B2B** funciona como la interfaz pública destinada a presentar la propuesta de valor, características y planes de Kinemo.

A nivel interno, los Bounded Contexts encapsulan las responsabilidades correspondientes a cada área del dominio. Las relaciones entre ellos se basan en las interacciones identificadas durante el **Design-Level EventStorming**, permitiendo coordinar las diferentes funcionalidades necesarias para la operación de una experiencia 4D.

Por ejemplo, el **BC01 — Movie & Sensory Content Management** permite gestionar una película 4D y su contenido sensorial, mientras que el **BC02 — Scheduling & Calendar** gestiona la programación de las funciones. Una función programada puede requerir posteriormente que el **BC03 — Room & Resource Readiness** compruebe la preparación de la sala.

De manera similar, el **BC04 — Ticketing Integration** proporciona información relacionada con la ocupación que puede ser utilizada por el **BC05 — Seat Allocation & Control**. Durante una función, el **BC06 — 4D Execution & Synchronization** se encarga de la ejecución y sincronización de los efectos, mientras que las incidencias relacionadas con los recursos son gestionadas por el **BC07 — Resource Testing & Maintenance**.

Los resultados operativos pueden ser utilizados por el **BC08 — Operational Analytics & Reporting** para presentar métricas y reportes. Finalmente, el **BC09 — Subscription & Service Management** gestiona los planes y suscripciones relacionados con el servicio.

De esta manera, el Container Diagram permite visualizar la distribución general de responsabilidades, las relaciones entre las principales partes de Kinemo 4D y las dependencias externas necesarias para soportar la solución.

#### 4.6.4. Software Architecture Components Diagrams

Para cada uno de los **9 Bounded Contexts** identificados se elaboró el **Component Diagram** correspondiente. Cada diagrama representa la descomposición interna del contexto y muestra los componentes responsables de recibir solicitudes, ejecutar la lógica de aplicación, aplicar las reglas del dominio, administrar la persistencia e interactuar con servicios externos cuando corresponde.

A continuación se presenta el detalle de los componentes definidos para cada Bounded Context.

##### BC01 — Movie & Sensory Content Management

El **MovieSensoryController** expone las operaciones relacionadas con la gestión de películas y contenido sensorial. El **MovieCommandService** gestiona las operaciones de registro, actualización y desactivación de películas, mientras que el **MovieQueryService** permite realizar consultas y búsquedas sobre el catálogo. El **SensoryContentService** gestiona la carga, vinculación, validación y habilitación del contenido sensorial. El **MovieSensoryDomainService** aplica las reglas de negocio relacionadas con las películas y el contenido sensorial, y el **MovieSensoryRepository** gestiona la persistencia y recuperación de la información.

![Component Diagram - BC01 Movie & Sensory Content Management](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_1.png)

##### BC02 — Scheduling & Calendar

El **SchedulingController** expone las operaciones relacionadas con la programación de funciones 4D. El **SchedulingCommandService** gestiona las operaciones de programación, reprogramación y cancelación de funciones, mientras que el **AvailabilityService** permite consultar la disponibilidad necesaria para la programación. El **SchedulingDomainService** aplica las reglas de negocio relacionadas con horarios y disponibilidad, y el **SchedulingRepository** gestiona la persistencia de las funciones programadas.

![Component Diagram - BC02 Scheduling & Calendar](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_2.png)

##### BC03 — Room & Resource Readiness

El **RoomReadinessController** expone las operaciones relacionadas con la preparación y disponibilidad de las salas. El **RoomPreparationService** gestiona las actividades necesarias para verificar la preparación de una sala, mientras que el **RoomBlockingService** permite bloquear una sala cuando no se encuentra disponible. El **RoomReleaseService** gestiona la liberación de las salas una vez finalizadas las restricciones correspondientes. El **RoomReadinessRepository** gestiona la persistencia de la información relacionada con el estado y preparación de las salas.

![Component Diagram - BC03 Room & Resource Readiness](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_3.png)

##### BC04 — Ticketing Integration

El **TicketingController** expone las operaciones relacionadas con la integración con el sistema externo de boletería. El **TicketingSyncService** gestiona la sincronización de la información proveniente del sistema de boletería, mientras que el **TicketingConnectionMonitor** permite supervisar el estado de la conexión con dicho sistema. El **OccupancyService** procesa la información relacionada con la ocupación de las salas y el **TicketingRepository** gestiona la persistencia de la información de integración.

Como dependencia externa, el **Sistema Externo de Boletería** proporciona la información necesaria para mantener actualizada la ocupación de las funciones.

![Component Diagram - BC04 Ticketing Integration](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_4.png)

##### BC05 — Seat Allocation & Control

El **SeatController** expone las operaciones relacionadas con la asignación y control de las butacas. El **SeatAllocationService** gestiona la asignación de butacas para las funciones, mientras que el **SeatActivationService** permite activar las butacas que corresponden a los boletos vendidos. El **SeatControlService** gestiona el estado operativo de las butacas y el **SeatRepository** administra la persistencia de la información relacionada con su asignación y estado.

![Component Diagram - BC05 Seat Allocation & Control](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_5.png)

##### BC06 — 4D Execution & Synchronization

El **ExecutionController** expone las operaciones relacionadas con la ejecución de las funciones 4D. El **ExecutionService** gestiona el inicio, pausa, reanudación y finalización de la ejecución, mientras que el **SynchronizationService** controla la sincronización entre la película y los efectos sensoriales. El **EmergencyExecutionService** gestiona las situaciones de emergencia que pueden interrumpir la ejecución. El **Hardware4DGateway** encapsula la comunicación con el hardware encargado de ejecutar los efectos físicos y el **ExecutionRepository** gestiona la persistencia de la información relacionada con la ejecución.

Como sistema externo, el **Hardware 4D** recibe las instrucciones necesarias para ejecutar los efectos sensoriales durante una función.

![Component Diagram - BC06 4D Execution & Synchronization](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_6.png)

##### BC07 — Resource Testing & Maintenance

El **MaintenanceController** expone las operaciones relacionadas con las pruebas, mantenimiento e incidencias de los recursos 4D. El **ChannelTestingService** gestiona las pruebas de los canales y componentes del sistema, mientras que el **IncidentService** permite registrar y gestionar las incidencias identificadas. El **MaintenanceService** gestiona las actividades de mantenimiento y el **EquipmentService** administra la información relacionada con los equipos. El **HardwareMaintenanceGateway** encapsula la comunicación con los recursos de hardware y el **MaintenanceRepository** gestiona la persistencia de las pruebas, incidencias y actividades de mantenimiento.

Como dependencia externa, el **Hardware 4D** permite realizar las pruebas y actividades técnicas necesarias sobre los recursos físicos.

![Component Diagram - BC07 Resource Testing & Maintenance](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_7.png)

##### BC08 — Operational Analytics & Reporting

El **AnalyticsController** expone las operaciones relacionadas con la consulta de información operativa y generación de reportes. El **OperationalMetricsService** gestiona el cálculo y consolidación de métricas relacionadas con la operación de las funciones y el mantenimiento. El **DashboardService** permite obtener la información necesaria para los dashboards, mientras que el **IncidentReportService** gestiona la información relacionada con las incidencias. El **DashboardExportService** permite generar y exportar reportes operativos y el **AnalyticsRepository** gestiona la persistencia y consulta de la información utilizada para los análisis.

![Component Diagram - BC08 Operational Analytics & Reporting](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_8.png)

##### BC09 — Subscription & Service Management

El **SubscriptionController** expone las operaciones relacionadas con la gestión de las suscripciones del servicio. El **SubscriptionPlanService** gestiona la información de los planes disponibles, mientras que el **SubscriptionService** administra la contratación, activación, renovación y cambio de plan. El **SubscriptionPaymentService** gestiona el procesamiento de los pagos asociados a las suscripciones. El **SubscriptionDomainService** aplica las reglas de negocio relacionadas con el ciclo de vida de las suscripciones y el **SubscriptionRepository** gestiona su persistencia.

Como dependencias externas, el **Payment Gateway Adapter** encapsula la comunicación con la **Pasarela de Pagos**, permitiendo procesar los pagos de las suscripciones. Asimismo, el contexto puede interactuar con el **Servicio de Facturación Electrónica** para gestionar los comprobantes correspondientes.

![Component Diagram - BC09 Subscription & Service Management](Kinemo-report/assets/img/4_6_4-Software-architecture-components-diagrams/Component_9.png)

En conjunto, los Component Diagrams permiten visualizar cómo cada Bounded Context se descompone internamente en componentes con responsabilidades específicas, manteniendo una separación clara entre la exposición de operaciones, la lógica de aplicación, las reglas del dominio, la persistencia y las integraciones externas. Esta descomposición contribuye a mantener la autonomía de cada contexto y facilita su evolución.
### 4.7 Software Object-Oriented Design

En esta sección se presenta el diseño orientado a objetos de Kinemo 4D mediante diagramas de clases UML. Estos diagramas permiten representar la estructura interna de los principales elementos del dominio, mostrando las clases, atributos, métodos y relaciones que intervienen en las funcionalidades de cada Bounded Context.

Para mantener consistencia con la arquitectura definida previamente, los diagramas de clases se organizan de acuerdo con los nueve Bounded Contexts identificados durante el diseño de la solución.

#### 4.7.1 Class Diagrams

A continuación, se presentan los diagramas de clases correspondientes a cada Bounded Context de Kinemo 4D.

##### BC01 — Movie & Sensory Content Management

Descripción:  Gestiona las películas disponibles en Kinemo y el contenido sensorial asociado a cada una. Permite registrar, modificar, activar o desactivar películas, clasificarlas por género, asociar contenido sensorial y administrar las pistas de efectos utilizadas durante las experiencias 4D.
Su responsabilidad reúne lo que anteriormente se encontraba separado en Movie Catalog Management y Sensory Content & Experience Management. En el proyecto original ambos procesos contemplaban películas, archivos sensoriales, pistas y configuraciones de efectos.

![Class Diagram - BC01 Movie & Sensory Content Management](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%201.png)

---

##### BC02 — Scheduling & Calendar

Descripción: Administra la programación de las funciones 4D. Permite crear, modificar, reprogramar y cancelar funciones, así como comprobar conflictos de horarios y la disponibilidad necesaria para ejecutar cada función.
El agregado principal es Show, ya que representa la función 4D y controla su ciclo de vida.

![Class Diagram - BC02 Scheduling & Calendar](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%202.png)

---

##### BC03 — Room & Resource Readiness

Descripción: Administra el estado operativo de las salas utilizadas para experiencias 4D. Permite inspeccionar una sala, determinar si se encuentra disponible, bloquearla temporalmente, liberarla después de una intervención y gestionar los recursos necesarios para una función. El agregado principal es Room.

![Class Diagram - BC03 Room & Resource Readiness](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%203.png)

---

##### BC04 — Ticketing Integration

Descripción: Administra la comunicación entre Kinemo y el sistema externo de boletería. Se encarga de establecer y supervisar la conexión, sincronizar información de ventas y ocupación, registrar fallas y reintentos de sincronización y mantener una representación interna de la ocupación de cada función.
En el diseño previo del proyecto, ticketing connections ya se encontraba definido como el agregado principal de este contexto.

![Class Diagram - BC04 Ticketing Integration](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%204.png)

---

##### BC05 — Seat Allocation & Control

Descripción: Administra las butacas que participarán en una función 4D. Utiliza los datos de ocupación provenientes de la boletería para determinar cuáles butacas fueron vendidas y deben habilitarse, cuáles deben permanecer inactivas y qué intervenciones manuales realiza el personal operativo.El agregado principal es SeatAllocation.
![Class Diagram - BC05 Seat Allocation & Control](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%205.png)

---

##### BC06 — 4D Execution & Synchronization

Descripción: administra la ejecución de una experiencia 4D durante una función. Controla el inicio, pausa, reanudación y finalización de la ejecución, así como la sincronización entre la película y los efectos sensoriales.
También incorpora la parada de emergencia, por lo que Emergency Management deja de existir como contexto separado y pasa a formar parte del ciclo de ejecución. El agregado principal es ShowExecution.

![Class Diagram - BC06 4D Execution & Synchronization](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%206.png)

---

##### BC07 — Resource Testing & Maintenance

Descripción: Gestiona el ciclo técnico de los equipos que intervienen en las experiencias 4D. Permite registrar equipos, probar canales de efectos, reportar incidencias, controlar su vida útil y gestionar órdenes de mantenimiento preventivo y correctivo.Aquí se consolidan los antiguos contextos Testing & Calibration y Maintenance & Incident Management.
![Class Diagram - BC07 Resource Testing & Maintenance](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%207.png)

---

##### BC08 — Operational Analytics & Reporting

Descripción: Concentra información proveniente de diferentes procesos operativos para proporcionar métricas, dashboard y reportes que ayuden al administrador a supervisar el funcionamiento de Kinemo.
Este contexto está principalmente orientado a Queries y Read Models, por lo que no es necesario inventar un Aggregate Root únicamente para cumplir una estructura. En el informe anterior ya estaba orientado a métricas, reportes y exportación.

![Class Diagram - BC08 Operational Analytics & Reporting](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%208.png)

---

##### BC09 — Subscription & Service Management

Descripción: Administra la relación comercial entre Kinemo y las cadenas de cine. Gestiona planes disponibles, contratación, pagos, activación, estado y límites de una suscripción, además de renovación y cambio a planes superiores.El agregado principal es Subscription.
El Statement menciona explícitamente Subscriptions and Payment Management como uno de los subdominios habituales en soluciones SaaS.

![Class Diagram - BC09 Subscription & Service Management](Kinemo-report/assets/img/4_7_1-Class-diagrams/diagrama%20de%20clase%209.png)

### 4.8 Database Design

El diseño de base de datos de **Kinemo 4D** representa la estructura utilizada para almacenar y organizar la información necesaria para las diferentes funcionalidades de la plataforma. La organización de los datos mantiene relación con los Bounded Contexts definidos previamente, permitiendo que cada área del dominio gestione la información correspondiente a sus responsabilidades.

Los diagramas permiten identificar las principales entidades de persistencia, sus atributos y las relaciones existentes entre ellas. De esta manera, el diseño de datos mantiene coherencia con el modelo de dominio y con la arquitectura planteada para la solución.

#### 4.8.1 Database Diagrams

A continuación, se presentan los diagramas de base de datos correspondientes a los diferentes Bounded Contexts de Kinemo 4D.

##### BC01 — Movie & Sensory Content Management

El diagrama de base de datos de este Bounded Context representa la persistencia de las películas 4D y del contenido sensorial asociado a cada una. La tabla movies almacena la información principal de cada película, mientras que sensory_contents mantiene la configuración sensorial vinculada. A su vez, sensory_tracks registra las pistas de efectos utilizadas durante la experiencia 4D y configuration_history conserva el historial de cambios realizados sobre la intensidad del contenido sensorial. Las relaciones permiten que una película posea contenido sensorial y que dicho contenido agrupe múltiples pistas e historial de configuración.

![Database Diagram - BC01 Movie & Sensory Content Management](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC01.png)

##### BC02 — Scheduling & Calendar

Este diagrama representa la persistencia de las funciones 4D programadas y de los conflictos de horario detectados durante el proceso de planificación. La tabla shows almacena la información correspondiente a cada función, incluyendo referencias a la película, sala, horario y estado. La tabla schedule_conflicts registra los conflictos identificados entre funciones y su estado de resolución. De esta forma, el contexto puede conservar el historial necesario para programar, reprogramar y controlar la disponibilidad de las funciones.

![Database Diagram - BC02 Scheduling & Calendar](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC02.png))

##### BC03 - Room & Resource Readiness

El diagrama de este contexto permite almacenar el estado operativo de las salas utilizadas para las experiencias 4D. La tabla rooms representa cada sala y mantiene información sobre su capacidad y estado actual. room_inspections registra las inspecciones realizadas para comprobar si una sala se encuentra preparada para operar, mientras que room_blocks almacena los periodos durante los cuales una sala permanece bloqueada, por ejemplo, debido a mantenimiento o indisponibilidad operativa. Estas relaciones permiten controlar la preparación, bloqueo y posterior liberación de cada sala.

![Database Diagram - BC03 Room & Resource Readiness](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC03.png)

##### BC04 - Ticketing Integration

Este diagrama representa los datos necesarios para soportar la integración entre Kinemo y el sistema externo de boletería. La tabla ticketing_integrations almacena la información principal de cada integración y su estado de conexión. sync_logs registra los resultados de los procesos de sincronización, incluyendo errores o intentos fallidos. Finalmente, show_occupancies mantiene la información de ocupación recibida para cada función. Esta estructura permite conservar el estado de sincronización y la información necesaria para actualizar la ocupación del sistema.

![Database Diagram - BC04 Ticketing Integration](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC04.png)

##### BC05 - Seat Allocation & Control

El diagrama de este Bounded Context almacena la información relacionada con la asignación y control de las butacas de una función 4D. La tabla seat_allocations representa la asignación general correspondiente a una función, mientras que show_seats mantiene el estado individual de cada butaca, indicando si fue vendida, habilitada o se encuentra fuera de servicio. Por su parte, manual_interventions registra las intervenciones realizadas por el personal operativo sobre una butaca. Con esta estructura se mantiene el control de las butacas que participan en cada experiencia.

![Database Diagram - BC05 Seat Allocation & Control](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC05.png)

##### BC06 - 4D Execution & Synchronization

Este diagrama representa la persistencia del ciclo de ejecución de una función 4D. show_executions almacena la información principal de cada ejecución y su estado. sensory_sequences mantiene el avance de las secuencias sensoriales utilizadas durante la función y synchronization_events registra los eventos relacionados con la sincronización entre la película y los efectos físicos. hardware_execution_logs permite conservar eventos y mensajes producidos por el hardware durante la ejecución. Finalmente, emergency_events registra las situaciones de emergencia ocurridas durante una función. De esta forma, la ejecución normal y la gestión de emergencias permanecen integradas dentro del mismo Bounded Context.

![Database Diagram - BC06 4D Execution & Synchronization](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC06.png)

##### BC07 - Resource Testing & Maintenance

El diagrama de este contexto representa la persistencia del ciclo técnico de los equipos 4D. La tabla equipment almacena la información principal de cada recurso físico, incluyendo su estado y vida útil. incidents registra las fallas o problemas detectados, mientras que maintenance_orders mantiene las órdenes de mantenimiento preventivo o correctivo asociadas a los equipos. Por otro lado, equipment_tests almacena las pruebas realizadas sobre cada equipo y channel_tests detalla los resultados obtenidos para los distintos canales de efectos. Esta estructura permite gestionar de manera conjunta las pruebas, incidencias y mantenimiento de los recursos.

![Database Diagram - BC07 Resource Testing & Maintenance](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC07.png)

##### BC08 - Operational Analytics & Reporting

Este diagrama almacena información consolidada utilizada para las consultas analíticas de Kinemo. La tabla dashboards representa los datos generados para una visualización operativa, mientras que operational_metrics mantiene las métricas calculadas durante un determinado periodo. room_performance almacena indicadores asociados al desempeño de las salas y incident_summaries consolida la información de incidencias según su nivel de severidad. Finalmente, operational_reports registra los reportes generados por el sistema. Esta estructura permite soportar las consultas y Read Models utilizados por el contexto de analítica.

![Database Diagram - BC08 Operational Analytics & Reporting](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC08.png)

##### BC09 - Subscription & Service Management

El diagrama de este Bounded Context representa la persistencia de la relación comercial entre Kinemo y las organizaciones clientes. subscription_plans mantiene la información de los planes disponibles, mientras que subscriptions almacena las suscripciones contratadas y su estado. payment_transactions registra las transacciones asociadas a cada suscripción y subscription_upgrades conserva las solicitudes y cambios realizados entre distintos planes. Las relaciones entre estas tablas permiten gestionar la contratación, activación, pagos, renovación y actualización de los planes del servicio.

![Database Diagram - BC09 Subscription & Service Management](Kinemo-report/assets/img/4_8_1-Database-diagrams/BC09.png)

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1 Software Configuration Management

#### 5.1.1 Software Development Environment Configuration


A continuación se detallan las herramientas y plataformas utilizadas por el equipo durante el ciclo de vida del proyecto, indicando su propósito, tipo de actividad y ruta de referencia.


A continuación se detallan las herramientas y plataformas utilizadas por el equipo durante el ciclo de vida del proyecto, indicando su propósito, tipo de actividad y ruta de referencia.

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
| Visual Studio Code | Entorno de desarrollo integrado (IDE) para Landing Page y Web Application | Software Development | https://code.visualstudio.com/ |
| Visual Studio 2022 | IDE para el desarrollo del RESTful API en ASP.NET Core | Software Development | https://visualstudio.microsoft.com/ |
| Node.js + npm | Entorno de ejecución y gestor de paquetes para el frontend (Vue) | Software Development | https://nodejs.org/ |
| Vue CLI / Vite | Herramienta de scaffolding y build del proyecto Vue | Software Development | https://cli.vuejs.org/ |
| PrimeVue | Biblioteca de componentes UI para la Web Application | Software Development | https://primevue.org/ |
| .NET SDK 8 | Framework para el desarrollo del RESTful API | Software Development | https://dotnet.microsoft.com/ |
| Swagger / OpenAPI | Documentación interactiva de los Endpoints del RESTful API | Documentation | https://swagger.io/ |
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
| RESTful API (Web Services) | Pendiente — se implementará en TB1 |
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

El despliegue de la Web Application (Vue + PrimeVue) y del RESTful API (ASP.NET Core) se realizará en la entrega TB1, utilizando un proveedor Cloud (Vercel/Netlify para el frontend y MonsterASP.NET o Azure para el backend).

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

![Code frequency - Landing Page](./assets/img/landing-code-frequency.png)

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

> _A completar a partir de la entrega AV2. Misma estructura que Sprint 1._

#### 5.2.4 Sprint 4 (TB2)

> _A completar a partir de la entrega TB2. Misma estructura que Sprint 1._

### 5.3 Validation Interviews

#### 5.3.1 Diseño de Entrevistas

> _Bloqueado — depende de tener un producto/prototipo validable (a partir de AV2)._

#### 5.3.2 Registro de Entrevistas

> _Bloqueado — depende de 5.3.1._

#### 5.3.3 Evaluaciones según heurísticas

> _Bloqueado — depende de 5.3.2. Usar el formato del Anexo D del enunciado._

### 5.4 Video About-the-Product

> _A completar a partir de AV2 (primera versión), versión final en TB2._

## Conclusiones

### Conclusiones y recomendaciones

> _Pendiente — sección acumulable, versión final en TB2._

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