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

### 1.3 Segmentos objetivo


El mercado de exhibición cinematográfica en Perú está altamente concentrado: dos cadenas líderes —Cineplanet y Cinemark— capturan en conjunto más de dos tercios de la cuota de mercado, mientras que un grupo de cadenas más pequeñas (UVK Multicines, Cinerama, Cine Star, Movie Time, entre otras) se reparten el resto. Kinemo se enfoca en este segundo grupo, que compite en un mercado dominado por actores de mayor escala sin contar con presupuesto propio para adoptar tecnología inmersiva por su cuenta.

**Segmento 1: Gerentes de Operaciones / Propietarios de cadenas de cine pequeñas y medianas**

**Perfil firmográfico**
- Cadenas peruanas independientes o familiares con entre 1 y 10 complejos a nivel nacional (ejemplo de referencia: UVK Multicines, con 5 complejos a nivel nacional).
- Cuota de mercado individual minoritaria frente a los líderes del sector, generalmente concentradas en Lima con posible presencia en provincias.
- Sin tecnología de entretenimiento inmersivo instalada actualmente en ninguno de sus complejos.

**Perfil demográfico del tomador de decisión**
- Edad aproximada: 35–55 años.
- Rol: Gerente General, Gerente de Operaciones o Propietario/Socio de la cadena.
- Nivel educativo: superior universitario, frecuentemente con formación en administración o gestión de negocios.
- Ubicación: principalmente Lima Metropolitana, con posibilidad de gerencias regionales en otras ciudades.

> Las motivaciones y frustraciones de este segmento se plantean como Assumptions en la sección 1.2.2.2 y se validarán con datos reales al construir el User Persona correspondiente en la sección 2.3.1, una vez realizadas las entrevistas.

**Segmento 2: Personal Operativo / Técnico de las salas de cine**

**Perfil demográfico**
- Edad aproximada: 20–40 años.
- Rol: Jefe de sala, coordinador de operaciones, técnico de mantenimiento o proyeccionista.
- Nivel educativo: variable, desde educación técnica hasta universitaria; no necesariamente con formación en tecnología.
- Ubicación: en el mismo complejo de cine donde trabaja, dentro del área de influencia de la cadena.



**Segmento 2: Personal Operativo / Técnico de las salas de cine**



## Capítulo II: Requirements Elicitation & Analysis

### 2.1 Competidores

Para el análisis de competencia se identificaron tres competidores indirectos con ofertas parcialmente similares a nuestro modelo de negocio. Se consideran indirectos porque, si bien ofrecen tecnología de entretenimiento inmersivo para salas de cine (motion seats y efectos físicos sincronizados), su modelo comercial está orientado principalmente a grandes cadenas internacionales, y no ofrecen de forma explícita un paquete integral accesible pensado para cadenas pequeñas y medianas como el que propone nuestra startup.

- **Competidor 1: 4DX (CJ 4DPLEX)** — Tecnología 4D desarrollada por CJ 4DPLEX, subsidiaria de la cadena surcoreana CJ CGV, que opera cientos de salas 4DX alrededor del mundo mediante alianzas con grandes cadenas (Cinépolis, Cineworld/Regal, AMC, Kinepolis, entre otras).
- **Competidor 2: D-BOX Technologies** — Empresa canadiense pionera en butacas con retroalimentación háptica (motion, vibración y textura), con despliegues masivos en cadenas grandes de Norteamérica como Cinemark.
- **Competidor 3: MediaMation (MX4D)** — Empresa estadounidense integradora de sistemas de butacas con efectos EFX (movimiento, viento, agua, aromas), que ofrece paquetes de teatro completos (butacas, audio, proyección, pantallas, instalación y mantenimiento) y que declara contar con un modelo de negocio más flexible, lo que le ha permitido trabajar también con cadenas familiares de tamaño medio en Estados Unidos.


#### 2.1.1 Análisis competitivo

**Competitive Analysis Landscape**

**¿Por qué llevar a cabo este análisis?** Buscamos comprender cómo los proveedores actuales de tecnología de entretenimiento inmersivo para cines abordan (o dejan de abordar) al segmento de cadenas pequeñas y medianas, para identificar la brecha de mercado que nuestra startup puede ocupar.

| | **Nuestra Startup** | **Competidor 1: 4DX (CJ 4DPLEX)** | **Competidor 2: D-BOX Technologies** | **Competidor 3: MediaMation (MX4D)** |
|---|---|---|---|---|
| **Overview** | Startup que ofrece una solución integral (butacas con movimiento, efectos físicos sincronizados, mantenimiento y software de gestión) dirigida específicamente a cadenas de cine pequeñas y medianas. | Formato de cine 4D con motion seats, viento, luces estroboscópicas, nieve simulada y aromas, operado bajo licencia en alianza con grandes cadenas internacionales. | Butacas con tecnología háptica patentada (movimiento, vibración, textura), reconocida por la precisión de su sincronización, con despliegues masivos en cadenas grandes de Norteamérica. | Integrador de sistemas de efectos EFX en butacas (movimiento, viento, agua, aromas), con paquetes de teatro completos y un modelo de negocio que declara ser flexible para distintos tamaños de cadena. |
| **Ventaja competitiva** | Enfoque exclusivo en el segmento desatendido de cadenas pequeñas/medianas, con menor barrera de inversión y soporte técnico especializado incluido. | Marca globalmente reconocida, respaldo de un conglomerado de medios (CJ Group) y alianzas con las cadenas más grandes del mundo. | Tecnología háptica de alta precisión, validada incluso fuera de la industria del cine (licenciada para simulación en automovilismo). | Flexibilidad de su modelo comercial y experiencia como integrador de sistemas completos (hardware + software + instalación). |
| **¿Qué valor ofrece a los clientes?** | Capacidad de ofrecer experiencias inmersivas comparables a las grandes cadenas, sin necesitar una inversión de capital ni un equipo técnico propio especializado. | Incremento comprobado en ingresos por entradas premium y diferenciación de marca a nivel global. | Incremento de asistencia y satisfacción del cliente, con la posibilidad de equipar solo algunas filas de un auditorio en lugar de la sala completa. | Paquete llave en mano adaptable al tamaño del auditorio, con mantenimiento simplificado gracias a su sistema neumático de bajo mantenimiento. |
| **Mercado objetivo** | Cadenas de cine pequeñas y medianas sin presencia de salas inmersivas, en mercados regionales desatendidos. | Grandes cadenas y multiplexes internacionales con alto volumen de espectadores. | Grandes cadenas norteamericanas y multiplexes con alta capacidad de inversión. | Cadenas de cine de diverso tamaño en Estados Unidos y mercados internacionales, incluyendo algunas cadenas familiares de tamaño medio. |
| **Estrategias de marketing** | Marketing directo B2B hacia gerentes de cadenas pequeñas/medianas, mostrando el retorno de inversión y la accesibilidad del modelo de servicio. | Marketing de marca a través de alianzas de alto perfil con cadenas líderes y campañas ligadas al estreno de blockbusters. | Testimonios de cadenas líderes y casos de éxito de incremento de ingresos por butaca instalada. | Casos de éxito con cadenas medianas/familiares, resaltando la adaptabilidad del sistema a distintos formatos de sala. |
| **Productos & Servicios** | Butacas con movimiento, efectos físicos sincronizados, mantenimiento especializado y software propio de gestión (programación, sincronización, mantenimiento, analítica). | Salas 4DX completas licenciadas, con catálogo de películas codificadas para el formato. | Butacas de movimiento háptico (por fila o auditorio completo) y catálogo de títulos codificados. | Paquetes de teatro EFX (butacas, audio, proyección, pantallas), software propietario de sincronización de contenido (ShowFlow/Vidshow). |
| **Precios & Costos** | Modelo de servicio con menor inversión inicial frente a la competencia; información exacta pendiente de definir en el modelo financiero del proyecto. | Recargo aproximado de USD 8 adicionales por entrada en mercados como Estados Unidos; inversión de instalación negociada directamente por sala/cadena, no pública. | Recargo histórico de aproximadamente USD 8 por entrada; costos de instalación negociados directamente con cada cadena, no públicos. | Costos de paquete negociados directamente con cada cadena; no se dispone de tarifas públicas. |
| **Canales de distribución (Web y/o Móvil)** | Landing Page B2B con solicitud de demo/cotización, integrado a una Web Application de gestión para el personal operativo de las salas contratantes. | Sitio web corporativo institucional (CJ 4DPLEX) y sitios de cada cadena aliada donde se promociona la cartelera 4DX. | Sitio web corporativo con blog informativo y sección de "ultimate guide"; presencia en sitios de cadenas aliadas. | Sitio web corporativo con información de producto por segmento (cines, atracciones, eSports). |


**Análisis SWOT**

**Nuestra Startup**
- Fortalezas: enfoque exclusivo en un segmento desatendido; propuesta integral (hardware + mantenimiento + software) en un solo proveedor; modelo de servicio con menor barrera de inversión.
- Debilidades: marca nueva sin trayectoria ni casos de éxito comprobados; escala de producción y soporte técnico aún por construir; menor músculo financiero frente a competidores establecidos.
- Oportunidades: mercado de cadenas pequeñas/medianas desatendido por los líderes actuales; posibilidad de posicionarse como el proveedor de referencia regional antes que los grandes jugadores globales lleguen a ese segmento.
- Amenazas: que un competidor grande (4DX, D-BOX o MediaMation) decida bajar su barrera de entrada y dirigirse también a cadenas pequeñas/medianas; posibles barreras regulatorias o de importación de hardware.

**Competidor 1: 4DX (CJ 4DPLEX)**
- Fortalezas: reconocimiento de marca global; respaldo financiero de un conglomerado; alianzas con las cadenas más grandes del mundo.
- Debilidades: modelo orientado a grandes volúmenes, lo que implica alta inversión de capital difícil de justificar para una cadena pequeña/mediana.
- Oportunidades: expansión hacia mercados emergentes donde aún no tiene presencia.
- Amenazas: proveedores más ágiles y accesibles que capturen al segmento de cadenas pequeñas/medianas antes que ellos.

**Competidor 2: D-BOX Technologies**
- Fortalezas: tecnología háptica de alta precisión, validada incluso en otras industrias; flexibilidad de instalar solo algunas filas.
- Debilidades: fuerte dependencia de cadenas grandes de Norteamérica como cliente principal; menor presencia en mercados de cadenas pequeñas/medianas fuera de esa región.
- Oportunidades: diversificar su cartera de clientes hacia cadenas más pequeñas mediante instalaciones parciales.
- Amenazas: nuevos proveedores que ofrezcan una propuesta de mantenimiento y gestión más completa (no solo hardware) dirigida a cadenas medianas.

**Competidor 3: MediaMation (MX4D)**
- Fortalezas: modelo de negocio flexible que ya ha demostrado funcionar con cadenas familiares de tamaño medio; oferta de paquete completo con mantenimiento simplificado.
- Debilidades: sigue estando enfocado principalmente en el mercado estadounidense; no ofrece explícitamente un software de gestión integral para el día a día operativo de la cadena (más allá de la sincronización de contenido).
- Oportunidades: expandirse hacia mercados de Latinoamérica con su modelo flexible.
- Amenazas: que un competidor regional (como nuestra startup) capture el mercado de cadenas pequeñas/medianas en Latinoamérica antes de que ellos expandan su presencia ahí.



#### 2.1.2 Estrategias y tácticas frente a competidores

- **Frente a la fortaleza de marca y respaldo financiero de 4DX**: en lugar de competir en reconocimiento global, la startup se posicionará como el proveedor especializado y cercano para cadenas pequeñas/medianas en el mercado regional, ofreciendo atención directa y personalizada que un proveedor global no prioriza para clientes de menor escala.
- **Frente a la precisión tecnológica de D-BOX**: la startup destacará que su propuesta no es solo hardware, sino una solución integral que incluye software de gestión y mantenimiento continuo, cubriendo una necesidad que D-BOX no resuelve directamente (la gestión operativa diaria de la sala).
- **Frente al modelo flexible de MediaMation**: dado que es el competidor más cercano en enfoque, la táctica principal será acelerar la presencia en el mercado regional/local antes de que MediaMation decida expandir su modelo flexible hacia esta región, y diferenciarse ofreciendo un dashboard de analítica y un módulo de mantenimiento como parte nativa del software, no como un servicio adicional.
- **Táctica general de precios**: aprovechar la debilidad compartida por los tres competidores (falta de un modelo de precios accesible y transparente para cadenas pequeñas/medianas) ofreciendo un modelo de servicio por suscripción/contrato que reduce la inversión inicial de capital.
- **Táctica de canal digital**: mientras los competidores mantienen sitios web mayormente institucionales, la startup usará su Landing Page como canal de conversión directo (solicitud de demo/cotización) enlazado a la Web Application, acortando el ciclo de ventas B2B.


### 2.2 Entrevistas

#### 2.2.1 Diseño de entrevistas

> _Pendiente — completar en `feature/interview-design`._

#### 2.2.2 Registro de entrevistas

> _Bloqueado — depende de realizar las entrevistas reales a ambos segmentos objetivo._

#### 2.2.3 Análisis de entrevistas

> _Bloqueado — depende de 2.2.2._

### 2.3 Needfinding

#### 2.3.1 User Personas

> _Pendiente — completar en `feature/user-personas`._

#### 2.3.2 User Task Matrix

> _Pendiente — completar en `feature/user-task-matrix`._

#### 2.3.3 User Journey Mapping

> _Pendiente — completar en `feature/journey-maps`._

#### 2.3.4 Empathy Mapping

> _Pendiente — completar en `feature/empathy-maps`._

### 2.4 Big Picture EventStorming

> _Pendiente — completar en `feature/event-storming-big-picture`._

### 2.5 Ubiquitous Language

> _Pendiente — completar en `feature/ubiquitous-language`._

## Capítulo III: Requirements Specification

### 3.1 User Stories

> _Pendiente — completar en `feature/user-stories`._

### 3.2 Impact Mapping

> _Pendiente — completar en `feature/impact-mapping`._

### 3.3 Product Backlog

> _Pendiente — completar en `feature/product-backlog`._

## Capítulo IV: Product Design

### 4.1 Style Guidelines

#### 4.1.1 General Style Guidelines

> _Pendiente — completar en `feature/style-guidelines`._

#### 4.1.2 Web Style Guidelines

> _Pendiente — completar en `feature/style-guidelines`._

### 4.2 Information Architecture

#### 4.2.1 Organization Systems

> _Pendiente — completar en `feature/information-architecture`._

#### 4.2.2 Labeling Systems

> _Pendiente — completar en `feature/information-architecture`._

#### 4.2.3 SEO Tags and Meta Tags

> _Pendiente — completar en `feature/information-architecture`._

#### 4.2.4 Searching Systems

> _Pendiente — completar en `feature/information-architecture`._

#### 4.2.5 Navigation Systems

> _Pendiente — completar en `feature/information-architecture`._

### 4.3 Landing Page UI Design

#### 4.3.1 Landing Page Wireframe

> _Pendiente — completar en `feature/landing-page-ui`._

#### 4.3.2 Landing Page Mock-up

> _Pendiente — completar en `feature/landing-page-ui`._

### 4.4 Web Applications UX/UI Design

#### 4.4.1 Web Applications Wireframes

> _Pendiente — completar en `feature/web-app-ux`._

#### 4.4.2 Web Applications Wireflow Diagrams

> _Pendiente — completar en `feature/web-app-ux`._

#### 4.4.3 Web Applications Mock-ups

> _Pendiente — completar en `feature/web-app-ux`._

#### 4.4.4 Web Applications User Flow Diagrams

> _Pendiente — completar en `feature/web-app-ux`._

### 4.5 Web Applications Prototyping

> _Pendiente — completar en `feature/web-app-prototyping`._

### 4.6 Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming

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

![Design-Level EventStorming](Kinemo-report/assets/img/eventstorming.jpg)

#### 4.6.2. Software Architecture Context Diagram

El **Context Diagram** representa a **Kinemo 4D** como un único sistema central, mostrando los actores que interactúan con la solución y los sistemas externos con los que se integra. Este diagrama se elaboró aplicando la notación **C4 Model**, permitiendo visualizar el alcance de Kinemo 4D y sus principales relaciones con el entorno, sin mostrar todavía la estructura interna de la solución.

Los actores identificados son:

- **Gerente**: responsable de administrar la operación de Kinemo 4D, incluyendo la gestión de películas y contenido sensorial, programación de funciones, consulta de información operativa y gestión del servicio.
- **Técnico**: responsable de las actividades técnicas relacionadas con la preparación, pruebas, mantenimiento y atención de incidencias de los recursos 4D.

Asimismo, Kinemo 4D mantiene integración con los siguientes sistemas externos:

- **Sistema Externo de Boletería**: proporciona información relacionada con las funciones, ventas y ocupación de las salas.
- **Hardware 4D**: ejecuta los efectos sensoriales y las acciones físicas asociadas a las funciones 4D.
- **Pasarela de Pagos**: procesa los pagos asociados a las suscripciones del servicio.
- **Servicio de Facturación Electrónica**: permite gestionar la emisión de comprobantes relacionados con las suscripciones.
- **Almacenamiento de Archivos**: permite almacenar los archivos multimedia y contenido sensorial utilizados por las películas 4D.
- **Servicio de Notificaciones**: permite enviar alertas y notificaciones relacionadas con la operación, mantenimiento y suscripciones.

![Context Diagram de Kinemo 4D](Kinemo-report/assets/img/diagram-context.png)

Como se observa en el diagrama, **Kinemo 4D centraliza la interacción entre el Gerente y el Técnico y los servicios externos necesarios para soportar la operación de la plataforma**. Esta vista permite identificar claramente el límite del sistema y sus principales dependencias externas, sin entrar todavía en el detalle de los Containers o Bounded Contexts que conforman la solución.#### 4.6.3. Software Architecture Container Diagrams

El **Container Diagram** detalla los elementos de alto nivel que conforman la arquitectura de software de Kinemo 4D, las principales responsabilidades de cada container, las decisiones tecnológicas adoptadas y la manera en que estos containers se comunican entre sí. Cada container representa una unidad de despliegue independiente dentro de la solución.

La solución está compuesta por:

- **Landing Page B2B**: sitio de presentación de Kinemo 4D que comunica la propuesta de valor del servicio y permite consultar los planes de suscripción disponibles. Constituye el punto de entrada para el Gerente y el Técnico.

- **Web Application**: aplicación web utilizada por el Gerente y el Técnico para acceder a las funcionalidades de gestión y operación de Kinemo 4D, según las responsabilidades de cada actor.

- **RESTful API**: punto de entrada para las solicitudes provenientes de la aplicación web. Centraliza el acceso a las funcionalidades del sistema y dirige las solicitudes hacia el Bounded Context correspondiente.

- **9 Bounded Contexts** como containers independientes, cada uno encargado de un área específica del dominio de Kinemo 4D:
  **BC01 — Movie & Sensory Content Management**, **BC02 — Scheduling & Calendar**, **BC03 — Room & Resource Readiness**, **BC04 — Ticketing Integration**, **BC05 — Seat Allocation & Control**, **BC06 — 4D Execution & Synchronization**, **BC07 — Resource Testing & Maintenance**, **BC08 — Operational Analytics & Reporting** y **BC09 — Subscription & Service Management**.

  Cada Bounded Context mantiene su propia base de datos, siguiendo el patrón **Database per Service**, con el objetivo de mantener la autonomía de datos y reducir el acoplamiento entre los diferentes contextos del dominio.

- **Sistemas externos**: Kinemo 4D se integra con el **Sistema Externo de Boletería**, **Hardware 4D**, **Pasarela de Pagos**, **Servicio de Facturación Electrónica**, **Almacenamiento de Archivos** y **Servicio de Notificaciones**, según las necesidades de cada Bounded Context.

![Container Diagram de Kinemo 4D](Kinemo-report/assets/img/diagram-container.png)

La comunicación entre los actores y la solución se inicia desde el **Landing Page B2B**, desde donde el **Gerente** y el **Técnico** acceden a la plataforma. El Landing Page se comunica con la **Web Application**, y esta utiliza la **RESTful API** como punto de entrada hacia los diferentes Bounded Contexts.

A nivel interno, cada Bounded Context encapsula las responsabilidades de un área específica del dominio y mantiene su propia persistencia. Las relaciones entre los contextos se basan en las interacciones identificadas durante el **Design-Level EventStorming**, permitiendo que los eventos producidos en un contexto puedan desencadenar acciones en otro cuando existe una dependencia funcional.

Por ejemplo, el **BC01 — Movie & Sensory Content Management** permite registrar una película 4D y su contenido sensorial, lo que permite al **BC02 — Scheduling & Calendar** iniciar la programación de una función. Asimismo, una función programada permite al **BC03 — Room & Resource Readiness** verificar la preparación de la sala.

De manera similar, el **BC04 — Ticketing Integration** proporciona información de ocupación que permite al **BC05 — Seat Allocation & Control** gestionar el estado de las butacas vendidas. Durante la ejecución, el **BC06 — 4D Execution & Synchronization** interactúa con el **BC07 — Resource Testing & Maintenance** cuando se presentan incidencias relacionadas con los recursos 4D. Finalmente, los resultados de la ejecución y del mantenimiento pueden ser utilizados por el **BC08 — Operational Analytics & Reporting** para generar métricas y reportes operativos.

El **BC09 — Subscription & Service Management** gestiona la suscripción del servicio y se relaciona con los demás contextos para habilitar las funcionalidades correspondientes según el estado de la suscripción.

De esta manera, el Container Diagram permite visualizar la distribución de responsabilidades, las principales decisiones tecnológicas, las relaciones entre los Bounded Contexts y las dependencias con los sistemas externos que forman parte del ecosistema de Kinemo 4D.

#### 4.6.4. Software Architecture Components Diagrams

Para cada uno de los **9 Bounded Contexts** identificados como containers, se elaboró el **Component Diagram** correspondiente. Cada diagrama muestra la descomposición interna del Bounded Context en componentes responsables de exponer las operaciones, ejecutar la lógica de aplicación, aplicar las reglas del dominio y gestionar la persistencia de información.

De acuerdo con las responsabilidades de cada contexto, se identificaron componentes como **Controllers**, **Application Services**, **Domain Services**, **Repositories** y **External Services**, según las necesidades de interacción con otros Bounded Contexts o sistemas externos.

A continuación se presenta el detalle de los componentes definidos para cada Bounded Context.

#### BC01 — Movie & Sensory Content Management

El **MovieSensoryController** expone las operaciones relacionadas con la gestión de películas y contenido sensorial. El **MovieCommandService** gestiona las operaciones de registro, actualización y desactivación de películas, mientras que el **MovieQueryService** permite realizar consultas y búsquedas sobre el catálogo. El **SensoryContentService** gestiona la carga, vinculación, validación y habilitación del contenido sensorial. El **MovieSensoryDomainService** aplica las reglas de negocio relacionadas con las películas y el contenido sensorial, y el **MovieSensoryRepository** gestiona la persistencia y recuperación de la información.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_1.png)

#### BC02 — Scheduling & Calendar

El **SchedulingController** expone las operaciones relacionadas con la programación de funciones 4D. El **SchedulingCommandService** gestiona las operaciones de programación, reprogramación y cancelación de funciones, mientras que el **AvailabilityService** permite consultar la disponibilidad necesaria para la programación. El **SchedulingDomainService** aplica las reglas de negocio relacionadas con horarios y disponibilidad, y el **SchedulingRepository** gestiona la persistencia de las funciones programadas.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_2.png)

#### BC03 — Room & Resource Readiness

El **RoomReadinessController** expone las operaciones relacionadas con la preparación y disponibilidad de las salas. El **RoomPreparationService** gestiona las actividades necesarias para verificar la preparación de una sala, mientras que el **RoomBlockingService** permite bloquear una sala cuando no se encuentra disponible. El **RoomReleaseService** gestiona la liberación de las salas una vez finalizadas las restricciones correspondientes. El **RoomReadinessRepository** gestiona la persistencia de la información relacionada con el estado y preparación de las salas.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_3.png)
#### BC04 — Ticketing Integration

El **TicketingController** expone las operaciones relacionadas con la integración con el sistema externo de boletería. El **TicketingSyncService** gestiona la sincronización de la información proveniente del sistema de boletería, mientras que el **TicketingConnectionMonitor** permite supervisar el estado de la conexión con dicho sistema. El **OccupancyService** procesa la información relacionada con la ocupación de las salas y el **TicketingRepository** gestiona la persistencia de la información de integración.

Como dependencia externa, el **Sistema Externo de Boletería** proporciona la información necesaria para mantener actualizada la ocupación de las funciones.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_4.png)

#### BC05 — Seat Allocation & Control

El **SeatController** expone las operaciones relacionadas con la asignación y control de las butacas. El **SeatAllocationService** gestiona la asignación de butacas para las funciones, mientras que el **SeatActivationService** permite activar las butacas que corresponden a los boletos vendidos. El **SeatControlService** gestiona el estado operativo de las butacas y el **SeatRepository** administra la persistencia de la información relacionada con su asignación y estado.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_5.png)

#### BC06 — 4D Execution & Synchronization

El **ExecutionController** expone las operaciones relacionadas con la ejecución de las funciones 4D. El **ExecutionService** gestiona el inicio, pausa, reanudación y finalización de la ejecución, mientras que el **SynchronizationService** controla la sincronización entre la película y los efectos sensoriales. El **EmergencyExecutionService** gestiona las situaciones de emergencia que pueden interrumpir la ejecución. El **Hardware4DGateway** encapsula la comunicación con el hardware encargado de ejecutar los efectos físicos y el **ExecutionRepository** gestiona la persistencia de la información relacionada con la ejecución.

Como sistema externo, el **Hardware 4D** recibe las instrucciones necesarias para ejecutar los efectos sensoriales durante una función.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_6.png)

#### BC07 — Resource Testing & Maintenance

El **MaintenanceController** expone las operaciones relacionadas con las pruebas, mantenimiento e incidencias de los recursos 4D. El **ChannelTestingService** gestiona las pruebas de los canales y componentes del sistema, mientras que el **IncidentService** permite registrar y gestionar las incidencias identificadas. El **MaintenanceService** gestiona las actividades de mantenimiento y el **EquipmentService** administra la información relacionada con los equipos. El **HardwareMaintenanceGateway** encapsula la comunicación con los recursos de hardware y el **MaintenanceRepository** gestiona la persistencia de las pruebas, incidencias y actividades de mantenimiento.

Como dependencia externa, el **Hardware 4D** permite realizar las pruebas y actividades técnicas necesarias sobre los recursos físicos.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_7.png)

#### BC08 — Operational Analytics & Reporting

El **AnalyticsController** expone las operaciones relacionadas con la consulta de información operativa y generación de reportes. El **OperationalMetricsService** gestiona el cálculo y consolidación de métricas relacionadas con la operación de las funciones y el mantenimiento. El **DashboardService** permite obtener la información necesaria para los dashboards, mientras que el **IncidentReportService** gestiona la información relacionada con las incidencias. El **DashboardExportService** permite generar y exportar reportes operativos y el **AnalyticsRepository** gestiona la persistencia y consulta de la información utilizada para los análisis.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_8.png)

#### BC09 — Subscription & Service Management

El **SubscriptionController** expone las operaciones relacionadas con la gestión de las suscripciones del servicio. El **SubscriptionPlanService** gestiona la información de los planes disponibles, mientras que el **SubscriptionService** administra la contratación, activación, renovación y cambio de plan. El **SubscriptionPaymentService** gestiona el procesamiento de los pagos asociados a las suscripciones. El **SubscriptionDomainService** aplica las reglas de negocio relacionadas con el ciclo de vida de las suscripciones y el **SubscriptionRepository** gestiona su persistencia.

Como dependencias externas, el **Payment Gateway Adapter** encapsula la comunicación con la **Pasarela de Pagos**, permitiendo procesar los pagos de las suscripciones. Asimismo, el contexto puede interactuar con el **Servicio de Facturación Electrónica** para gestionar los comprobantes correspondientes.

![Component Diagram de Kinemo 4D](Kinemo-report/assets/img/Component_9.png)

En conjunto, los Component Diagrams permiten visualizar cómo cada Bounded Context se descompone internamente en componentes con responsabilidades específicas, manteniendo una separación clara entre la exposición de operaciones, la lógica de aplicación, las reglas del dominio, la persistencia y las integraciones externas. Esta descomposición contribuye a mantener la autonomía de cada contexto y facilita su evolución y despliegue independiente.

### 4.7 Software Object-Oriented Design

#### 4.7.1 Class Diagrams

> _Pendiente — completar en `feature/class-diagrams`._

### 4.8 Database Design

#### 4.8.1 Database Diagrams

![Diagrama de Movie Catalog Management](Kinemo-report/assets/img/BC01-Movie Catalog Managment.png)

## 1. Movie Catalog Management

La base de datos del módulo **Movie Catalog Management** se encuentra estructurada alrededor del agregado principal `movies`, el cual representa y centraliza la información base de las películas 4D registradas en el sistema.

Este agregado almacena atributos fundamentales como `title` y `duration_minutes`, y utiliza el Value Object `status` para gestionar la transición de estados del flujo de *Desactivación de Contenido*, permitiendo clasificar la disponibilidad del recurso en estados como *Activo*, *Inactivo* o *Bloqueado para Programación*.

Para dar soporte a la operativa estructurada del catálogo, el modelo incorpora características y entidades complementarias:

*   **Trazabilidad Autorreferencial:** El agregado `movies` implementa una relación recursiva mediante el atributo `original_movie_id`. Esta estructura da soporte directo al flujo de *Duplicación de Configuración*, permitiendo registrar y modificar copias de una cinta manteniendo intacta la trazabilidad histórica hacia la película de origen.
*   **Entidad `genres`:** Funciona como una entidad de soporte que normaliza la clasificación del contenido. Al separar los géneros en su propia estructura relacional, se elimina la redundancia de datos y se agiliza significativamente la ejecución del flujo de *Búsqueda de Película* mediante filtros estructurados.

> Las relaciones establecidas a través de las claves foráneas (`genre_id`, `original_movie_id`) garantizan la integridad referencial del esquema, asegurando que este Bounded Context administre su propia fuente de verdad de manera normalizada y desacoplada del resto de los módulos del sistema.


![Diagrama de Sensory Content & Experience Management](Kinemo-report/assets/img/BC02-Sensory Content and Experience Managment.png)

## 2. Sensory Content & Experience Management

La base de datos del módulo **Sensory Content & Experience Management** se encuentra estructurada alrededor del agregado principal `sensory_files`, el cual gestiona de manera centralizada la subida y administración del "Archivo de Efectos 4D".

Esta entidad utiliza el Value Object `validation_status` para administrar la transición de estados correspondiente al flujo de *Carga de Archivo de Efectos*, controlando etapas críticas como *Cargado*, *Rechazado* o *Vinculado*. Asimismo, integra el atributo `movie_id`, el cual actúa como clave foránea para establecer una conexión referencial con el catálogo de películas.

A partir de este agregado raíz, el modelo se expande en entidades especializadas para soportar el nivel granular de la experiencia sensorial:

*   **Entidad `sensory_tracks`:** Representa la "Pista Sensorial" individual, permitiendo que un mismo archivo agrupe múltiples pistas (ej. viento, movimiento, agua). Esta entidad emplea el atributo `track_status` para dirigir el ciclo de vida en el flujo de *Validación de Pista Sensorial* (*Validada*, *Rechazada*, *Habilitada para Ejecución*). Por su parte, el campo `intensity_level` da soporte directo al flujo de *Asignación de Intensidad*, almacenando el parámetro operativo validado por el técnico.
*   **Entidad `configuration_history`:** Funciona como una tabla de soporte y auditoría para el flujo de *Restablecimiento de Configuración*. Al almacenar un registro histórico de los cambios aplicados en los niveles de intensidad (`previous_intensity_level`), esta entidad provee al sistema la capacidad de emitir recomendaciones basadas en el uso y permite al técnico de mantenimiento revertir o restablecer la configuración a un estado anterior validado.

> Finalmente, las relaciones establecidas mediante las claves foráneas (`movie_id`, `sensory_file_id`, `sensory_track_id`) garantizan la estricta integridad referencial del modelo, asegurando un diseño normalizado que mantiene el desacoplamiento estructural frente a otros Bounded Contexts del sistema.

---

![Diagrama de Scheduling & Calendar](Kinemo-report/assets/img/BC03-Scheduling and Calendar.png) 


## Capítulo V: Product Implementation, Validation & Deployment

### 5.1 Software Configuration Management

#### 5.1.1 Software Development Environment Configuration

> _Pendiente — completar en `feature/software-configuration-management` (urgente para AV1)._

#### 5.1.2 Source Code Management

> _Pendiente — agregar URLs de los 4 repositorios, explicación de GitFlow, convenciones de branches y Conventional Commits. Completar en `feature/software-configuration-management` (urgente para AV1)._

#### 5.1.3 Source Code Style Guide & Coding Conventions

> _Pendiente — completar en `feature/software-configuration-management`._

#### 5.1.4 Software Deployment Configuration

> _Pendiente — completar en `feature/software-configuration-management`._

### 5.2 Landing Page, Services & Applications Implementation

#### 5.2.1 Sprint 1 (AV1)

##### 5.2.1.1 Sprint Planning 1
> _Pendiente._
##### 5.2.1.2 Aspect Leaders and Collaborators
> _Pendiente._
##### 5.2.1.3 Sprint Backlog 1
> _Pendiente._
##### 5.2.1.4 Development Evidence for Sprint Review
> _Pendiente._
##### 5.2.1.5 Execution Evidence for Sprint Review
> _Pendiente._
##### 5.2.1.6 Services Documentation Evidence for Sprint Review
> _Pendiente._
##### 5.2.1.7 Software Deployment Evidence for Sprint Review
> _Pendiente._
##### 5.2.1.8 Team Collaboration Insights during Sprint
> _Pendiente._

#### 5.2.2 Sprint 2 (TB1)

> _A completar a partir de la entrega TB1. Misma estructura que Sprint 1 (Planning, Aspect Leaders, Backlog, Development/Execution/Services/Deployment Evidence, Team Collaboration Insights)._

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
