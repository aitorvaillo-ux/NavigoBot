![](https://i.imgur.com/ghO869t.png$0)

¡La Social Update aún no ha terminado! Volvemos a actualizarla para ofrecerte las últimas novedades y correcciones de Navigo.

## Nuevas características
- **Invite tracker.** Ahora puedes saber qué invitación ha usado un usuario al entrar a tu servidor, revisar estadísticas y recompensar a tus miembros con leaderboards. Puedes configurarlo en `/trackinvites` y revisar el leaderboard en `/leaderboard invites`. Se pueden reestablecer todas las estadísticas usando el comando `/trackinvites reset`.
- `/serverinfo`. Revisa la información del servidor en el que te encuentras.
- `/userinfo`. Revisa la información de un usuario del servidor.
- Se añade una nueva opción a `/afk <status> <temporary>`. Si selecciones `temporary`, el modo AFK se desactivará una vez envies un mensaje.

## Cambios
- La cantidad de XP por mensaje pasa de un máximo de 7 y mínimo de 5 a un máximo de 3 y mínimo de 1.
- Hemos actualizado el mensaje que reciben los dueños de los servidores que invitan a Navigo.
- `/case view <case>` ahora muestra un botón directo para revocar la sanción.
- `/balance` ahora te permite ver tu saldo sin tener que automencionarte.
- `/ban info` ahora muestra la información del baneo en un embed.
- Los usuarios que has bloqueado ahora pueden robarte con `/rob`.
- El embed de `/case all` se amplía de 10 casos por página a 15.
- Ahora en `/phone`, puedes identificar al equipo de moderadores de Navigo por su insignia característica.
- Se han rediseñado los comandos `/github user`, `/github org` y `/github repo`.
- Se ha centralizado la búsqueda de usuarios en caché y en la API de Discord para hacer más rápidas las búsquedas de varios comandos.
- Los cooldowns de los comandos de economía, el cooldown general y las fechas de `/github` han sido mudados al sistema de tiempo de Discord.

## Errores solucionados
- Hemos arreglado el comando `/starboard off`, que lanzaba un error inesperado cuando un usuario quería desactivar el starboard.
- Hemos solucionado el sistema de leveling global, que en ciertos supuestos causaba un aumento exponencial de la XP del usuario.
- El AFK ya no responde si es el propio usuario quien se menciona a sí mismo.
- Se han solucionado problemas con la traducción de comandos, tanto en el comando `/help` como en la interfaz de Discord.
- Se han reescrito parcialmente algunos comandos para mejorar su tiempo de respuesta.
- Se ha solucionado un bug en `/ban` que no te permitía banear si no establecías una duración.
- Se ha arreglado un error en `/ban remove` que no te permitía ejecutarlo.
- El comando `/case view` ya busca correctamente a los usuarios.
- El comando `/invite` ahora acepta la invitación sin que sea el enlace completo.
- Se han corregido algunos errores en Anchor que hacían que no se emitieran correctamente los logs de canal creado.
- La starboard ya borra mensajes si bajan del límite de estrellas y edita los mensajes actualizando el número de estrellas.
- Si transfieres tan pocas monedas que tras impuestos se queda en 0, ahora `/transfer` te informa de que no puedes transferirlo.
- Los logs de usuario baneado/desbaneado ahora reflejan bien si el usuario es un bot o no.
