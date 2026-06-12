# Política de Privacidad de Yumidark

**Bot de Discord de Pen Testing y Ciberseguridad**

*Última actualización: 12 de junio de 2026*

## 1. Introducción

Yumidark es un bot de Discord especializado en pruebas de penetración (pen testing) y ciberseguridad. Esta Política de Privacidad explica qué datos personales recopilamos, cómo los utilizamos, almacenamos y protegemos cuando interactúas con el bot.

## 2. Datos que Recopilamos y Procesamos

Como bot de Discord, recopilamos y procesamos los siguientes datos:

- **Datos de Discord**: ID de usuario de Discord, nombre de usuario, discriminador (si aplica), avatar, ID del servidor (guild ID), ID del canal y el contenido de los mensajes/comandos que envías al bot.
- **Datos de uso y comandos**: Registro de comandos ejecutados, parámetros usados (como targets de escaneo, puertos, etc.), timestamp y servidor donde se usó. Esto se utiliza para logs de auditoría y prevención de abuso.
- **Datos de pruebas temporales**: Cuando ejecutas comandos de escaneo o pen testing, procesamos temporalmente la información de los objetivos (IPs, dominios, puertos). **Estos datos se procesan en memoria o de forma temporal y no se almacenan de forma persistente** una vez finalizado el comando.
- **Datos técnicos**: Logs de errores, información del host donde se ejecuta el bot (para fines de hosting y seguridad).

**No recopilamos**:
- Contraseñas, tokens de Discord, datos de pago ni información sensible de cuentas.
- Datos de otros usuarios del servidor que no interactúen directamente con el bot.
- Resultados completos de escaneos de forma permanente.

## 3. Cómo Usamos los Datos

Utilizamos los datos para:
- Proporcionar y ejecutar las funcionalidades del bot (comandos de pen testing y ciberseguridad).
- Prevenir, detectar y responder a usos abusivos o maliciosos del bot.
- Mejorar el rendimiento, seguridad y características del bot.
- Cumplir con obligaciones legales (por ejemplo, cooperar con autoridades si se detecta actividad ilegal).
- Generar estadísticas anonimizadas de uso.

## 4. Almacenamiento, Retención y Seguridad

- Los datos se almacenan de forma segura siguiendo las mejores prácticas de ciberseguridad (encriptación en tránsito, controles de acceso estrictos, zero-trust principles).
- Logs de comandos y uso: se retienen temporalmente (máximo 30 días) y luego se eliminan o anonimizan.
- Datos de escaneos: se descartan inmediatamente después de generar la respuesta al usuario.
- El código del bot es open source y está sujeto a revisiones de seguridad continuas.
- Recomendamos a los administradores de servidores limitar los permisos del bot (solo roles de confianza para comandos de pen testing).

## 5. Compartir o Divulgar Datos

No vendemos, alquilamos ni compartimos tus datos personales con terceros con fines comerciales.

Solo podemos compartir datos en estos casos:
- Cuando sea requerido por ley o por orden de autoridad competente.
- Para proteger la seguridad del bot, los usuarios o para prevenir fraude/abuso.
- En caso de fusión o venta del proyecto (con notificación previa).

Los datos de tus objetivos de escaneo **nunca** se comparten con nadie.

## 6. Tus Derechos según el RGPD y Leyes de Privacidad

Tienes derecho a:
- Acceder a los datos que tenemos sobre ti.
- Solicitar la rectificación o eliminación de tus datos.
- Oponerte al procesamiento o solicitar limitación.
- Retirar tu consentimiento (aunque el bot requiere ciertos datos para funcionar).

Para ejercer estos derechos, contacta a Ari (ver sección Contacto). Responderemos en el plazo legal.

## 7. Cookies y Tecnologías Similares

El bot Yumidark no utiliza cookies ni tecnologías de seguimiento en el navegador. Toda la interacción ocurre a través de la API de Discord.

## 8. Cambios en esta Política de Privacidad

Podemos actualizar esta política cuando sea necesario. Los cambios se publicarán en el repositorio GitHub Yumidark y se anunciarán en el bot cuando sea posible. Te recomendamos revisar esta página periódicamente.

## 9. Contacto para Privacidad y Seguridad

Para cualquier consulta relacionada con privacidad, eliminación de datos o reportes de incidentes de seguridad:

- GitHub: https://github.com/aariidev/Yumidark
- Contacta directamente a Ari (aariidev)

**Yumidark está comprometido con la privacidad, la seguridad y el uso ético de la ciberseguridad. Pen testing responsable siempre.**