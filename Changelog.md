# Navigo 1.3.0 Community Update

## Nuevas características
- **Navigo Pro.** Nuevo plan de suscripción por servidor con herramientas avanzadas, activación instantánea tras la compra y beneficios para los servidores del equipo de Navigo. Incluye Aegis AI, reglas personalizadas, criptomonedas, sincronización de baneos y más. Configúralo con `/pro`.
- **Aegis AI**. La moderación de Navigo ahora entiende las normas de tu servidor y analiza los mensajes con IA, avisando o actuando según lo configures. Configúralo con una suscripción Pro y `/aegis`.
- **Sincronización de baneos.** Puedes enlazar servidores para compartir listas de baneos y mantener limpia la comunidad de forma conjunta.
- **Criptomonedas.** Consulta precios en tiempo real y programa actualizaciones automáticas en tus canales con `/crypto` y `/cryptotimer`.
- **Niveles con recompensas.** Sistema completo de progreso por servidor con roles que se entregan automáticamente al subir de nivel.
- **Filtro de ingresos sospechosos.** Cuando entra un miembro, Aegis evalúa su cuenta (antigüedad, avatar, nombre y listas externas) y avisa en el canal configurado si el riesgo es alto.
- **Perfil de usuario.** `/profile` reúne niveles, economía, rachas, tiempos de espera y actividad en llamadas.
- **Estadísticas de moderación.** `/modstats` con resumen por meses, tipos de sanción y actividad de Aegis.
- **Recompensas por votar.** Votar en top.gg otorga recompensas exclusivas cada 12 horas.
- **Rachas diarias.** `/daily` ahora premia la constancia con bonificaciones crecientes.
- **Llamadas anónimas:** `/phone` añade modo anónimo y registra la duración total de cada llamada.
- **Excepciones de enlaces.** `/automod` permite gestionar enlaces permitidos y configurar el canal de avisos de Aegis.

## Cambios
- **Nuevo diseño visual.** embeds más limpios y minimalistas, sin campos y con la información en líneas claras.
- **Configuración con botones y modales.** Los módulos, registros, casos, roles y respuestas automáticas se gestionan ahora con botones y formularios, sin comandos largos.
- **Edición de casos.** los casos de moderación pueden editarse (motivo y pruebas adjuntas) directamente desde su tarjeta.
- **Gestión de invitaciones.** Puedes eliminar una invitación desde su propia tarjeta de información.
- **Leveling rediseñado.** /setlevel y /unsetlevel se integran en /leveling set|unset.
- **Traducciones.** Inglés y español revisados y ampliados, con mensajes más claros en todos los módulos.
- **Comandos contextuales.** Se han movido las acciones Hug, Kiss, Pat, Poke y Slap a comandos de menú contextual sobre usuarios.

## Errores solucionados
- **Mensajes privados.** Arreglada la entrega de avisos al sancionar o recompensar a un usuario.
- **Teléfono:** Ya no se producen errores si alguien escribe mientras espera a que la otra persona se conecte.
- **Baneos y aislamientos.** Si la duración indicada no es válida, Navigo lo avisa en lugar de aplicar una sanción distinta a la esperada.
