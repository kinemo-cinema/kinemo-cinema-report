# Informe de Trabajo Final — Kinemo

## Carátula

![Logo UPC](assets/img/logo-upc.png)

| Campo | Valor                                           |
|---|-------------------------------------------------|
| Universidad | Universidad Peruana de Ciencias Aplicadas (UPC) |
| Carrera | Ingeniería de Software                          |
| Ciclo | 2026-20                                         |
| Código y Nombre del Curso | 1ASI0730 – Aplicaciones Web                     |
| NRC | 8155                                            |
| Profesor | Angel Augusto Velasquez Nuñez                   |
| Nombre del Startup | VonNeuman New Men                               |
| Nombre del Producto | Kinemo                                          |
| año | 2026                                            |

**Integrantes**

| Código      | Apellidos y Nombres                  |
|-------------|--------------------------------------|
| u202319398  | Llamozas Diaz, Edson Diego           |
| u202212327  | Flores Chavez, Fabricio              |
| u20241b932  | Huamanchumo Chicchon, Felipe Marcelo |
| u202318865  | Trigoso Garrido, Cristian Joseph     |
| u202412041  | Correa Rodriguez, Andrea Khristina   |

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

### 1.1 Startup Profile

#### 1.1.1 Descripción de la Startup

Kinemo es una startup de tecnología para entretenimiento cinematográfico que provee a cadenas de cine pequeñas y medianas una solución integral de experiencias inmersivas: butacas con movimiento y efectos físicos sincronizados (viento, vibración, entre otros), servicio de mantenimiento especializado y un software propio de gestión operativa.

Kinemo nace para cerrar la brecha entre las grandes cadenas de cine —que ya cuentan con tecnología inmersiva propietaria como 4DX o D-BOX— y las cadenas pequeñas y medianas, que hoy no pueden competir en experiencia de usuario debido al alto costo de inversión y a la falta de conocimiento técnico especializado para operar y mantener este tipo de tecnología por cuenta propia.

Tagline: "Cine que se siente."

Misión: Democratizar el acceso a experiencias cinematográficas inmersivas, permitiendo que cadenas de cine de cualquier tamaño ofrezcan a sus espectadores sensaciones físicas sincronizadas con el contenido, a través de una solución accesible de hardware, mantenimiento y software de gestión.

#### 1.1.2 Perfiles de integrantes del equipo

> _Pendiente — completar en `feature/startup-profile` (foto, nombres, código, carrera, conocimientos técnicos por integrante)._

### 1.2 Solution Profile

#### 1.2.1 Antecedentes y problemática

Análisis 5W2H

Who (¿Quién?): cadenas de cine pequeñas y medianas —operadas de forma independiente o familiar, con un número reducido de complejos— y su personal operativo/técnico, que hoy no cuentan con tecnología de entretenimiento inmersivo en sus salas.
What (¿Qué?): la imposibilidad de ofrecer experiencias de cine inmersivo (butacas con movimiento, efectos físicos sincronizados) comparables a las de las grandes cadenas, debido al alto costo de inversión y a la falta de conocimiento técnico especializado para operar y mantener este tipo de tecnología por cuenta propia.
Where (¿Dónde?): mercados donde conviven pocas cadenas dominantes de gran escala con varias cadenas regionales más pequeñas; inicialmente el proyecto se enfoca en el mercado peruano, con potencial de expansión a otros países de Latinoamérica.
When (¿Cuándo?): el problema se ha intensificado en los últimos años, conforme las cadenas líderes han adoptado formatos inmersivos propietarios (4DX, D-BOX) como diferenciador frente a la competencia, ampliando la brecha de experiencia frente a las cadenas más pequeñas.
Why (¿Por qué?): porque los proveedores actuales de tecnología inmersiva dirigen su modelo comercial principalmente a cadenas de gran escala, exigiendo una inversión de capital y una infraestructura técnica que las cadenas pequeñas y medianas no pueden asumir por sí solas.
How (¿Cómo?): actualmente estas cadenas continúan operando salas convencionales sin posibilidad de diferenciarse en experiencia, lo que las expone a perder espectadores frente a cadenas más grandes o a otras formas de entretenimiento en el hogar.
How Much (¿Cuánto?): el mercado de exhibición cinematográfica peruano está altamente concentrado en dos cadenas líderes, mientras que un conjunto de cadenas más pequeñas —como UVK Multicines (5 complejos a nivel nacional), Cinerama, Cine Star y Movie Time— compiten por una porción menor del mercado; dimensionar con precisión el impacto económico de esta brecha requiere profundizar con fuentes primarias (entrevistas) además de las fuentes secundarias consultadas.

**Enunciado del problema**

Las cadenas de cine pequeñas y medianas no pueden ofrecer experiencias de entretenimiento inmersivo comparables a las de las grandes cadenas, debido al alto costo de la tecnología propietaria existente en el mercado, a la falta de conocimiento técnico especializado para operarla y mantenerla, y a la ausencia de un software de gestión adecuado para su operación diaria. Esto las deja en desventaja competitiva frente a cadenas líderes que ya ofrecen este tipo de experiencia como diferenciador.

**Puntos más importantes que debe resolver la solución propuesta**

Reducir la barrera de inversión de capital necesaria para adoptar tecnología de entretenimiento inmersivo.
Suplir la falta de conocimiento técnico especializado del personal operativo mediante software de gestión simple y soporte de mantenimiento incluido.
Permitir que el personal operativo programe funciones y perfiles de efectos sin fricción, integrando esta gestión con la operación diaria de la sala.
Comunicar de forma clara la propuesta de valor a los tomadores de decisión de las cadenas de cine (Landing Page) y facilitar el paso de la evaluación a la contratación.

**Objetivos del proyecto**

Diseñar y desarrollar una solución de software (Landing Page, Web Application y RESTful API) que dé soporte al modelo de negocio de Kinemo, permitiendo gestionar la programación de funciones, la sincronización de efectos y el mantenimiento de las salas.
Validar la propuesta de valor y los Assumptions del modelo de negocio mediante entrevistas con gerentes/propietarios de cadenas de cine y con su personal operativo.
Desplegar progresivamente versiones funcionales del producto digital a lo largo del ciclo académico, cumpliendo con los hitos AV1, TB1, AV2 y TB2.

**Restricciones que delimitan el alcance del proyecto**

El alcance académico del proyecto se limita al desarrollo del software (Landing Page, Web Application, RESTful API); la fabricación física de butacas y actuadores de efectos se trata como un supuesto de negocio (Business Assumption), no como un entregable de ingeniería de software.
El desarrollo se realiza dentro del calendario académico del ciclo 2026-20 (15 semanas).
El backend debe implementarse en C# sobre ASP.NET Core, y el frontend en Vue, conforme a los lineamientos tecnológicos del curso.
Las entrevistas y validaciones se limitan a 3–5 participantes por segmento objetivo, dado el carácter académico del proyecto.

#### 1.2.2 Lean UX Process

#### 1.2.2 Lean UX Process

Para abordar el dominio del problema se aplicó el Lean UX Process, cuyo objetivo es validar de forma temprana y económica las creencias del equipo sobre el negocio, los usuarios y la solución antes de invertir en su construcción completa. A continuación se presenta el Problem Statement consolidado del proyecto, los Assumptions identificados por categoría, los Hypothesis Statements derivados de los Feature Assumptions, y finalmente el Lean UX Canvas que resume el proceso.

##### 1.2.2.1 Lean UX Problem Statements

El estado actual del dominio de **entretenimiento cinematográfico inmersivo** se ha enfocado principalmente en **cadenas de cine grandes**, que cuentan con el capital suficiente para adquirir tecnología propietaria de efectos sincronizados (butacas con movimiento, viento, aromas, entre otros), dejando de lado a las **cadenas de cine pequeñas y medianas**, cuyos puntos de dolor son la imposibilidad de competir en experiencia de usuario frente a las grandes cadenas, la falta de conocimiento técnico especializado para operar y mantener este tipo de tecnología, y flujos de trabajo de programación de funciones y mantenimiento de sala que siguen siendo manuales y desarticulados.

Lo que los productos y proveedores existentes de tecnología inmersiva (por ejemplo, soluciones propietarias de efectos 4D) no logran abordar es una **oferta integral y accesible** dirigida específicamente a cadenas pequeñas y medianas, que combine el hardware (butacas motorizadas y actuadores de efectos), el mantenimiento especializado y un software de gestión, bajo un modelo que no exija una inversión de capital equivalente a la de una gran cadena.

Nuestro producto/servicio abordará esta brecha ofreciendo una **solución llave en mano de entretenimiento inmersivo** —butacas con movimiento y efectos físicos sincronizados (viento, vibración, entre otros), servicio de mantenimiento y un software de gestión propio— bajo un modelo comercial más accesible que el de los proveedores tradicionales, permitiendo a cines pequeños y medianos ofrecer experiencias comparables a las de las grandes cadenas.

Nuestro enfoque inicial será las **cadenas de cine pequeñas y medianas que actualmente no cuentan con salas de experiencia inmersiva**, junto con el personal operativo/técnico de dichas salas, responsable de la programación de funciones y del mantenimiento del equipamiento.

Sabremos que somos exitosos cuando veamos que estas cadenas de cine **contratan el servicio, programan funciones de forma recurrente en las salas inmersivas instaladas, renuevan sus contratos de mantenimiento, y reportan un incremento medible en la venta de entradas premium** en las salas equipadas con nuestra solución.

##### 1.2.2.2 Lean UX Assumptions

**Business Assumptions**
- Creemos que el mercado de cadenas de cine pequeñas y medianas en la región representa una oportunidad desatendida por los proveedores actuales de tecnología de entretenimiento inmersivo.
- Creemos que un modelo de servicio (hardware + mantenimiento + software, en lugar de venta directa de equipos) reduce la barrera de inversión de capital para este segmento.
- Creemos que podemos generar ingresos recurrentes mediante contratos de mantenimiento y actualizaciones periódicas del software de gestión.
- Creemos que las cadenas de cine estarán dispuestas a firmar contratos de mediano/largo plazo a cambio de condiciones comerciales preferenciales.
- Creemos que contamos con la capacidad organizativa para fabricar o ensamblar el hardware de las butacas y ofrecer soporte técnico continuo a múltiples salas simultáneamente.

**Business Outcome Assumptions**
- Incremento en el número de contratos firmados con cadenas de cine (por ejemplo, de 0 a un número determinado de cadenas contratadas en un periodo de tiempo definido).
- Reducción del tiempo promedio de instalación y puesta en marcha de una sala inmersiva.
- Incremento en la tasa de renovación de los contratos de mantenimiento.
- Reducción del costo de adquisición de clientes mediante referidos de cadenas que ya cuentan con la solución instalada.
- Incremento del ingreso promedio por sala instalada gracias a servicios adicionales del software de gestión.

**User Assumptions**
- Gerentes de operaciones y/o propietarios de cadenas de cine pequeñas y medianas, con poder de decisión sobre inversión en tecnología para sus salas.
- Personal técnico/operativo de las salas de cine, responsable de configurar, programar y dar mantenimiento a las butacas y efectos.
- Espectadores finales de las salas de cine, que asisten buscando una experiencia audiovisual más dinámica.

**User Outcome and Benefit Assumptions**
- Los gerentes de cadenas de cine desean diferenciar su oferta frente a cadenas más grandes sin realizar una inversión de capital prohibitiva.
- El personal operativo desea contar con una herramienta simple para programar funciones y asignar perfiles de efectos sin requerir conocimiento técnico avanzado.
- El personal operativo desea poder reportar y dar seguimiento a incidencias de mantenimiento de forma centralizada.
- Los espectadores finales desean sentir que forman parte de la película mediante movimiento de butacas, viento y otras sensaciones físicas sincronizadas con el contenido.

**Feature Assumptions**
- Un panel de administración web que permita programar funciones y asignar perfiles de efectos a cada película.
- Un motor de sincronización entre el contenido audiovisual y los efectos físicos (movimiento de butacas, viento, entre otros).
- Un módulo de gestión de mantenimiento preventivo y correctivo del hardware instalado en cada sala.
- Un dashboard de analítica sobre el uso, desempeño y estado de las salas instaladas.
- Un Landing Page dirigido a cadenas de cine que comunique la propuesta de valor del negocio y permita solicitar una demostración o cotización.

##### 1.2.2.3 Lean UX Hypothesis Statements

**H1**
Creemos que lograremos incrementar el número de contratos firmados con cadenas de cine si los gerentes de operaciones de cadenas pequeñas y medianas logran evaluar y contratar el servicio de forma clara y rápida, con un panel de administración web que les permita programar funciones y asignar perfiles de efectos a cada película.

**H2**
Creemos que lograremos incrementar la retención de clientes y la venta de entradas premium si los espectadores finales logran sentir que forman parte de la película, mediante un motor de sincronización entre el contenido audiovisual y los efectos físicos de las butacas.

**H3**
Creemos que lograremos incrementar la tasa de renovación de los contratos de mantenimiento si el personal operativo de las salas logra reportar y resolver incidencias de forma centralizada, con un módulo de gestión de mantenimiento preventivo y correctivo.

**H4**
Creemos que lograremos incrementar el ingreso promedio por sala instalada si los gerentes de operaciones logran monitorear el desempeño de sus salas, con un dashboard de analítica sobre uso, desempeño y estado del hardware instalado.

**H5**
Creemos que lograremos reducir el costo de adquisición de clientes si los gerentes de cadenas de cine logran conocer la propuesta de valor del negocio y solicitar una demostración de forma sencilla, con un Landing Page claro y orientado a su segmento.

##### 1.2.2.4 Lean UX Canvas

| Bloque | Contenido |
|---|---|
| **1. Business Problem** | Las cadenas de cine pequeñas y medianas no pueden ofrecer experiencias de entretenimiento inmersivo comparables a las de las grandes cadenas, debido al alto costo de la tecnología propietaria, la falta de conocimiento técnico especializado y la ausencia de un software de gestión adecuado. |
| **2. Business Outcomes** | Incremento en el número de cadenas de cine contratadas; incremento en el ingreso promedio por sala instalada; incremento en la tasa de renovación de contratos de mantenimiento; reducción del costo de adquisición de clientes. |
| **3. Users** | Gerentes de operaciones/propietarios de cadenas de cine pequeñas y medianas; personal técnico/operativo de las salas de cine; espectadores finales de las salas de cine. |
| **4. User Outcomes & Benefits** | Diferenciación competitiva sin alta inversión de capital (gerentes); simplicidad operativa en la programación y mantenimiento de salas (personal operativo); mayor inmersión y disfrute de la experiencia (espectadores finales). |
| **5. Solutions** | Butacas con movimiento y efectos físicos sincronizados; servicio de mantenimiento especializado; software de gestión (panel de programación de funciones, motor de sincronización, módulo de mantenimiento, dashboard de analítica); Landing Page y Web Application. |
| **6. Hypotheses** | H1 a H5 (ver sección 1.2.2.3), priorizadas según su impacto en los Business Outcomes definidos. |
| **7. What's the most important thing we need to learn first?** | Si los gerentes de cadenas de cine pequeñas y medianas perciben la solución integral (hardware + mantenimiento + software) como suficientemente accesible y valiosa como para justificar la contratación frente a no invertir en tecnología inmersiva. |
| **8. What's the least amount of work we need to do to learn the next most important thing?** | Realizar entrevistas de validación con gerentes de cadenas de cine pequeñas/medianas presentando el concepto de la solución y un prototipo de baja fidelidad del panel de administración y del Landing Page, para medir su nivel de interés y disposición a contratar. |

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

Al recopilar la información de los segmentos objetivo a través de las entrevistas, se procedió a sintetizar y analizar los hallazgos mediante la construcción de User Personas, User Task Matrix, User Journey Mapping y Empathy Mapping.

#### 2.3.1 User Personas

**User Persona 1: Carlos Torres**  
La imagen ilustra el perfil de Carlos Torres, enfocado en el mantenimiento técnico y la operación de las salas. Destaca sus metas de mantener el 100% de operatividad en horas de alta afluencia y sus frustraciones ligadas a la ausencia de un sistema centralizado para dar seguimiento a fallas mecánicas e interfaces complejas.

<img src="assets/img/Carlos%20Torres.png" alt="Carlos Torres">

**User Persona 2: Pepe Castillo**  
La imagen sintetiza el perfil del tomador de decisiones comerciales. Refleja sus objetivos de diferenciar la oferta de sus cines e incrementar la venta de entradas premium, equilibrado con su temor a realizar inversiones en tecnología propietaria costosa sin soporte local asegurado.

<img src="assets/img/Pepe%20Castillo.png" alt="Pepe Castillo">

Link de UXPressia: https://uxpressia.com/w/v8FzI/p/CvSDi?tagId=9BZKW

#### 2.3.2 User Task Matrix

La imagen presenta la matriz de tareas construida a partir de las necesidades de nuestros dos User Personas. En ella se relacionan las actividades principales diferenciando la frecuencia de ejecución y el nivel de importancia/prioridad para el Gerente de Operaciones y el Técnico de Mantenimiento.

<img src="assets/img/User%20Task%20Matrix.png" alt="Task Matrix">

Link del Task Matrix: https://uxpressia.com/w/v8FzI/p/HWL53

#### 2.3.3 User Journey Mapping

**Segmento objetivo #1: Gerentes/Propietarios de cadenas de cine pequeñas y medianas**  
Este user persona presenta el recorrido actual de Pepe Castillo. El mapa ilustra su experiencia completa desde que identifica la necesidad de modernizar sus salas para competir contra las grandes cadenas de cine, pasando por la búsqueda de opciones en el mercado y la evaluación de costos, hasta la toma de decisión y el seguimiento del impacto comercial en su negocio.

<img src="assets/img/User%20Journey%20Map%20-%20Pepe%20Castillo.png" alt="User Journey Map - Pepe Castillo">

**Segmento objetivo #2: Personal operativo/técnico de las salas de cine**  
Este User Journey Map representa el recorrido actual de Carlos Torres. El mapa ilustra su experiencia completa desde que recibe la programación diaria de funciones y realiza la inspección de las salas, pasando por el intento de configurar y sincronizar equipos o atender incidencias mecánicas/técnicas a mano, hasta el reporte de fallas y el cierre de jornada.

<img src="assets/img/User%20Journey%20Map%20-%20Carlos%20Torres.png" alt="User Journey Map - Carlos Torres">

Link del User Journey Mapping - Pepe Castillo: https://uxpressia.com/w/v8FzI/m/52UwW?tagId=9BZKW  
Link del User Journey Mapping - Carlos Torres: https://uxpressia.com/w/v8FzI/m/9xtmS?tagId=9BZKW

#### 2.3.4 Empathy Mapping

**Pepe Castillo:**  
La imagen resume los hallazgos sobre lo que piensa, siente, ve, escucha, dice y hace el Gerente de Operaciones. Refleja su preocupación por la pérdida de competitividad frente a grandes cadenas y su deseo de adoptar un modelo de software y tecnología accesible con ROI predecible.

<img src="assets/img/Empathy%20map-Pepe%20Castillo.png" alt="Empathy Map - Pepe Castillo">

**Carlos Torres:**  
La imagen sintetiza la vivencia diaria del técnico de sala. Destaca la presión por resolver fallas repentinas antes de las funciones y la oportunidad de contar con un sistema automatizado e intuitivo para reportes y calibración de equipos.

<img src="assets/img/Empathy%20map-Carlos%20Torres.png" alt="Empathy Map - Carlos Torres">

### 2.4 Big Picture EventStorming

> _Pendiente — completar en `feature/event-storming-big-picture`._

### 2.5 Ubiquitous Language

> _Pendiente — completar en `feature/ubiquitous-language`._

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

#### 4.6.1 Design-Level EventStorming

> _Pendiente — completar en `feature/domain-driven-architecture`._

#### 4.6.2 Software Architecture Context Diagram

> _Pendiente — completar en `feature/domain-driven-architecture`._

#### 4.6.3 Software Architecture Container Diagrams

> _Pendiente — completar en `feature/domain-driven-architecture`._

#### 4.6.4 Software Architecture Component Diagrams

> _Pendiente — completar en `feature/domain-driven-architecture`._

### 4.7 Software Object-Oriented Design

#### 4.7.1 Class Diagrams

> _Pendiente — completar en `feature/class-diagrams`._

### 4.8 Database Design

#### 4.8.1 Database Diagrams

> _Pendiente — completar en `feature/database-design`._

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
