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