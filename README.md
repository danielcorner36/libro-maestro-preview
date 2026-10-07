# Libro Maestro — Taller editorial

Primera versión funcional, en español, de un espacio local para acompañar el desarrollo de libros de ficción y no ficción.

## Cómo abrir

1. Descarga y descomprime el paquete completo; conserva `index.html` y `fflate.js` juntos en la misma carpeta.
2. Abre `index.html` con un navegador actualizado (Safari, Chrome o Edge).
3. Crea la ficha de tu proyecto y avanza por las etapas del menú.
4. Usa **Respaldo** para descargar el proyecto completo en JSON y consérvalo en un lugar seguro.

## Qué incluye esta versión

- Ficha de proyecto: título, autor, género, lector y promesa.
- Ruta editorial en nueve etapas: concepto, investigación, arquitectura, manuscrito, edición de fondo, estilo, integridad, producción y publicación. Inicio con siguiente paso sugerido según datos guardados y la ruta completa desplegable; no es un juicio de IA.
- Biblioteca local de varios proyectos, mapa editable de capítulos y borradores con conteo de palabras.
- Biblia narrativa por proyecto: personajes, motivaciones, arcos, relaciones, cronología y reporte literal de presencia por capítulo.
- Perfil de voz y muestra autorizada por proyecto, incluidos en encargos editoriales que decides copiar a Zapia.
- Importación local de Markdown/TXT y extracción de texto/encabezados desde DOCX/EPUB (máximo 20 MB), con opción segura de añadir o reemplazar capítulos. No conserva la maquetación, imágenes, comentarios ni notas al pie. Los ZIP se leen en el navegador con fflate, licencia MIT (ver LICENSE.fflate).
- Dieciséis plantillas editables para preliminares y secciones finales; se exportan con el manuscrito en Markdown.
- Registro de fuentes con localizadores, cita textual, paráfrasis de trabajo, afirmación respaldada y vínculo manual con los capítulos donde se utilizan.
- Mapa manual de afirmaciones por capítulo: fragmento, fuente asociada, localizador, pasaje de evidencia, nota y estado («por comprobar», «contrastada por mí» o «sin respaldo encontrado»). La sugerencia local marca algunos patrones de cifras, fechas o atribuciones; el autor decide qué registrar. Puede fallar y no detecta plagio ni revisa semánticamente el manuscrito.
- La auditoría de fichas copia solo los registros manuales; otra opción permite copiar el borrador completo de un capítulo elegido junto con las fichas, tras mostrar un aviso de privacidad. Nada se envía automáticamente; el contenido solo se comparte si el autor lo pega en otro servicio.
- Listas de control, evaluación orientativa de impacto potencial y maqueta tipográfica simple de cubierta.
- Alertas preliminares de longitud de oraciones, repeticiones inmediatas y marcadores pendientes.
- Encargos editoriales que se copian para trabajar después con Zapia en el chat; cada capítulo permite guardar retroalimentación, acciones y decisiones sin mezclarlas con el manuscrito.
- Registro por capítulo del origen de ideas/materiales, el aporte del autor y el uso de IA o colaboradores; incluye exportación de un informe de trazabilidad en Markdown. Son anotaciones manuales, no una certificación de autoría.
- Exportación a Markdown y DOCX/EPUB básicos; al descargar DOCX/EPUB se comprueban internamente sus paquetes ZIP/XML y la presencia del texto. La apariencia aún debe revisarse en Word/lector; la vista para PDF depende de imprimir en el navegador. Respaldo/restauración JSON.
- Pantalla «Alcance completo» con todos los requisitos de las imágenes, estados honestos de avance, dependencias y fases recomendadas.
- Especificación del producto en `ESPECIFICACION_PRODUCTO.md`, con funciones, privacidad, dependencias y criterios para considerarlo listo.

## Límites que no deben confundirse con una versión profesional final

- Los datos se guardan en el almacenamiento local del navegador; no hay cuentas, nube ni sincronización entre dispositivos. Exporta respaldos con frecuencia.
- No hay conexión interna a un modelo de IA. Los botones preparan encargos para revisar el material con Zapia en el chat; el contenido no se envía automáticamente.
- No es un detector de plagio ni de IA: no consulta bases de similitud, no determina autoría y no certifica originalidad. La procedencia, los aportes y el uso de herramientas se registran manualmente; ayudan a ordenar la revisión, pero no prueban quién escribió un texto. Verifica las fuentes y permisos; las coincidencias externas requieren revisión humana.
- Las alertas de gramática y estilo son simples heurísticas, no una corrección ortotipográfica completa.
- La maqueta de cubierta es conceptual; no genera archivos de imprenta.
- El checklist de publicación no certifica aceptación ni sustituye las instrucciones oficiales vigentes del canal, la revisión legal, fiscal o de derechos.
- El porcentaje de preparación mide casillas marcadas; no predice ventas ni garantiza un bestseller.

Esta entrega es un MVP de escritorio/navegador para probar el flujo editorial. Para una plataforma multiusuario con nube, IA integrada, revisión de similitud, DOCX/EPUB profesional y requisitos de publicación actualizados se necesita una segunda fase técnica, credenciales/servicios adecuados y pruebas antes de considerarla lista para producción.
