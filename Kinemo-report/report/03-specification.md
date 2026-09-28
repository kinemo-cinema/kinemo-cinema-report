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

> _Pendiente — completar en `feature/product-backlog`
