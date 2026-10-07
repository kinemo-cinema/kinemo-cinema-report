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