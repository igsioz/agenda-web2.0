# WordPress vs. desarrollo a medida

## Alcance y evidencia

AgendaWeb es una aplicación propia en PHP y MySQL. Su código permite registrar eventos con título, fecha, hora y categoría; consultar el calendario mensual; editar eventos y borrarlos. La tabla `eventos` se define en `db.sql`, y la conexión y ejecución están en los archivos PHP del proyecto.

La comparación de AgendaWeb se basa en ese código. En esta sesión se abrió el proceso de creación de WordPress.com, que solicita iniciar sesión o crear una cuenta. No había una sesión autorizada disponible, por lo que todavía no se creó ni publicó un sitio WordPress. No se inventan una URL, una captura ni tiempos de uso.

## Comparativo

| Criterio | WordPress.com | AgendaWeb (a medida) |
|---|---|---|
| Tiempo para publicar | Con textos e imágenes preparados, una página y una entrada sencillas suelen montarse en una sesión corta usando el editor y un tema. El tiempo real de esta práctica queda pendiente de medir al completar la publicación. | El código de la agenda ya está desarrollado. Para ponerlo en marcha hacen falta PHP, MySQL, crear la base con `db.sql` y configurar `conexion.php`; una instalación local no equivale por sí sola a publicarla en Internet. Partir desde cero y programar las funciones tomaría bastante más que configurar un sitio informativo en un CMS. |
| Control sobre el código | WordPress es software abierto, pero en WordPress.com el alojamiento y el plan condicionan el acceso a temas, plugins y personalización. El control no es idéntico al de una instalación propia de WordPress. | Control directo sobre PHP, CSS, consultas y esquema de MySQL. Se pueden modificar las reglas y la interfaz sin depender de un editor visual, aunque cada cambio requiere trabajo técnico. |
| Facilidad para no programadores | El editor de bloques y los temas permiten cambiar textos, páginas y publicaciones visualmente. Es adecuado para que una persona no técnica mantenga contenido habitual. | Una persona puede usar los formularios existentes para gestionar eventos, pero cambiar el diseño, los campos o las reglas exige editar código y comprender la aplicación y su base de datos. |
| Mantenimiento a futuro | En el servicio alojado, el proveedor administra la infraestructura; el alcance de funciones, copias, extensiones y controles depende del plan. Hay que mantener el contenido y revisar la compatibilidad de temas y extensiones disponibles. | El responsable debe mantener el alojamiento PHP/MySQL, actualizar y proteger la aplicación, cuidar las credenciales y realizar copias de seguridad de la base de datos. Hay menos dependencia de plugins, pero más responsabilidad técnica propia. |
| Adaptación a reglas propias | Las páginas, entradas y temas cubren necesidades comunes. Reglas específicas pueden requerir extensiones o desarrollo; las opciones dependen del plan y pueden añadir dependencias. | La agenda ya implementa un calendario mensual, categorías (trabajo, personal, estudio y ocio), fechas y horas, y operaciones CRUD. Sus reglas se pueden ajustar al flujo exacto del proyecto, a cambio de programarlas y probarlas. |

## Conclusión por escenario

Para un blog, una web de presentación o un sitio de contenidos que una persona no técnica necesite actualizar con frecuencia, elegiría WordPress.com porque ofrece editor visual, temas y alojamiento integrado, siempre verificando que el plan permita las funciones necesarias. Para una agenda interna con reglas particulares de eventos, categorías y calendario, elegiría desarrollo a medida como AgendaWeb porque el comportamiento se ajusta al flujo requerido y se controla el código; asumiría también el coste de desarrollo, alojamiento y mantenimiento.

## Evidencia de WordPress pendiente

- Crear o abrir una cuenta autorizada en WordPress.com.
- Crear el sitio y aplicar un tema.
- Publicar una página de inicio y una entrada.
- Completar aquí la URL pública del sitio: **pendiente**.
- Guardar y añadir al repositorio una captura del panel y otra del sitio publicado: **pendiente**.
- Sustituir en la tabla la estimación de tiempo por el tiempo observado durante la práctica.