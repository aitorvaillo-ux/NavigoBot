# Política de Privacidad de Navigo

Última actualización: 29 de agosto de 2026

## 1. Información general
Esta Política de Privacidad describe cómo Navigo recopila, procesa, almacena y protege la información cuando interactúa con sus usuarios. Al utilizar Navigo en tu servidor de Discord, aceptas las prácticas descritas en este documento. Si no estás de acuerdo con estos términos, debes remover el Bot o deshabilitar las funciones.

## 2. Datos que recopilamos
Navigo opera bajo el principio de minimización de datos: solo procesa la información estrictamente necesaria para cumplir sus funciones de administración, moderación automática, seguridad y utilidad.

### A. Datos almacenados en base de datos (Persistentes)
- **Identificadores únicos.** IDs de servidores, canales, roles y de usuarios.

- **Casos de moderación.** Sanciones aplicadas, motivos, ID del moderador e ID del usuario sancionado.

- **AFK.** Mensaje de ausencia y marcas de tiempo cuando un usuario activa el comando de ausencia.

- **Respuestas Automáticas.** Claves de activación y respuestas personalizadas configuradas.

### B. Datos procesados en memoria (No persistentes)
- **Contenido de mensajes.** El texto de los mensajes enviados es analizado en tiempo real por el motor de AutoMod para detectar menciones no autorizadas, filtrar enlaces/invitaciones de Discord, y analizar la similitud entre mensajes para la prevención de spam y mensajes duplicados. Para ello, Navigo conserva temporalmente en memoria RAM una matriz con los últimos 5 mensajes enviados por usuario. Este historial nunca se guarda en la base de datos, y se elimina automáticamente.

## 3. Uso de los datos
Los datos recopilados se utilizan exclusivamente para:
- Proveer las funcionalidades operativas del Bot en los servidores autorizados.
- Mantener la seguridad de las comunidades mediante filtrado automático de contenido malicioso.
- Permitir a los administradores llevar un registro histórico de sanciones.
- Navigo NO vende, alquila, comercializa ni comparte ningún tipo de datos con terceros, anunciantes o redes de telemetría.

## 4. Almacenamiento y seguridad
- Los datos persistentes se almacenan de forma segura en bases de datos protegidas mediante credenciales de acceso restringidas y cifrado en tránsito.

- Eliminamos los ajustes de un servidor automáticamente si el Bot es expulsado del servidor.

- Los datos en la memoria RAM son volátiles y desaparecen al superar la ventana de uso.

## 5. Derechos del usuario y eliminación de datos
- Cualquier usuario o administrador de un servidor puede solicitar la eliminación completa de los datos asociados a su ID enviando una solicitud formal a través del servidor de soporte.

- Al eliminar el Bot de un servidor, la configuración asociada al servidor puede ser purgada previa petición o tras los ciclos de mantenimiento del sistema.

## 6. Cumplimiento con los Términos de Discord
Navigo cumple estrictamente con los Términos de Servicio para Desarrolladores de Discord y la Política de Privacidad de Discord. El uso del Message Content Intent está limitado exclusivamente al funcionamiento del motor de administración y moderación.

## 7. Cambios en esta Política
Nos reservamos el derecho de actualizar esta Política de Privacidad en cualquier momento para reflejar cambios técnicos en el Bot o requisitos legales de la plataforma. La fecha de la última revisión se actualizará en la parte superior de este documento.
