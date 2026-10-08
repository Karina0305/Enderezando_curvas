# Enderezando Curvas

Corrección final del inicio: se ajustaron proporciones y posiciones con la referencia de 1512 × 4130, incluyendo encabezado, curva del banner, composición del texto y comunidad, tarjetas de servicios, seis testimonios, adornos y pie de página. Alianza utiliza el retrato transparente del colaborador, la X y los fondos originales. El video empieza pausado en un fotograma cercano a la referencia y dispone de control de reproducción al pasar el cursor o enfocar con teclado. Las fotos, textos y controles continúan siendo elementos independientes y navegables. La página reorganiza el contenido en pantallas pequeñas.

Abre `dist/index.html` en tu navegador. No requiere instalación.

- `index.html`: inicio, menús y ventana de Alianza.
- `casos.html`: caso de Victoria, evolución e historia.
- `donacion.html`: formulario de demostración.
- `contacto.html`: formulario de colaboración con validación local, sin envío de correos.
- `pacientes.html`: tarjetas y búsqueda por nombre, con datos de ejemplo de las capturas.
- `postularse.html`: formulario de tres pasos: datos del paciente/tutor, diagnóstico/documentos y confirmación de prueba. Los botones Postularse de todas las páginas lo abren.
- `especialistas.html`: cuatro especialistas con retratos, iconos y fondo originales, accesible desde Conoce nuestros especialistas.

Actualización de Especialistas y recursos: Sofía, Lucas y Ana utilizan sus PNG individuales. Las dos doctoras siguen la correspondencia de la referencia; las dos fotos masculinas se colocaron en el orden de las tarjetas (José Antonio: foto con lentes; Antonio: foto con portapapeles), pendiente de confirmar si se desea intercambiar. Las ondas blancas originales se aplicaron a los encabezados correspondientes. El video `assets/clips/astronauta.mp4` está incluido y se comprobó que carga (55 segundos), pendiente de confirmar su página y asociación antes de mostrarlo como historia de una persona.

Postularse conserva los datos al volver al paso anterior, valida campos y acepta PDF/JPG/PNG de hasta 20 MB por archivo. Los archivos solo se seleccionan en el navegador; no se suben, transmiten ni persisten. La confirmación muestra un folio DEMO, la fecha actual de Ciudad de México y el correo del tutor; no afirma que se haya enviado un caso real. Nueva postulación limpia todos los campos y archivos.

Entra a Pacientes desde el menú Pacientes & Familias. Entra a Contacto desde Nosotros o desde Más Información en Alianza. Las seis tarjetas de pacientes repiten tres personas, tal como en la referencia; los contadores resumen esas tres personas. Las páginas individuales de estos pacientes siguen pendientes.

Se reemplazaron con los archivos originales las seis fotos de los testimonios del inicio, la imagen de la comunidad, el retrato de Victoria en Casos y la niña de Donación. Se usan elementos de imagen independientes que se adaptan al tamaño de pantalla.

Actualización de la primera pantalla: la comunidad utiliza ahora el PNG suministrado; los tres iconos son los SVG originales (columna, postulación y donación). La cabecera utiliza la niña suministrada en JPG y conserva su fondo blanco. Las seis fotos de testimonios mantienen su correspondencia con los nombres de la plantilla. Esta actualización se limita a la página de inicio.

Corrección de Donación: se sustituyó el JPG de la niña por el PNG transparente y se reconstruyó el fondo con la textura azul, la cinta original y los vectores suministrados. Los corazones del panel se muestran desde el SVG proporcionado. Ya no se utilizan recortes de la captura para el fondo ni los corazones de esta pantalla. El formulario sigue siendo una demostración.

Corrección de Casos y Pacientes: las radiografías Antes/Después y el abrazo se muestran desde sus PNG originales. La cabecera amarilla, estrellas, corazones, signo de admiración y rayos utilizan los SVG suministrados. Pacientes utiliza la textura azul y los iconos originales del resumen. Los fondos de Casos/Pacientes y Contacto se reconstruyeron con los vectores recibidos. Las fotos de Sofía, Lucas y Ana y la portada del video siguen usando las capturas, pendientes de sus archivos individuales.

Los siguientes elementos siguen usando las capturas porque sus archivos independientes no se encontraron en las carpetas recibidas: logo, niña del encabezado principal, hombre de Alianza, abrazo de Casos, radiografías, portada del video de Victoria, fotos de Sofía/Lucas/Ana, iconos y corazones decorativos. La niña de Donación se conserva con el fondo blanco de su JPG original.

Los ocho archivos exportados están en `assets/originales`. Las tres fotos adicionales están en `assets/nuevas-fotos` y los cuatro videos están en `assets/clips`, sin asignarlos todavía a pacientes específicos.

Clips revisados:
- `Primer_pla_4150_0`: mano escribiendo en un hospital (4 s).
- `The_boy_si_3714_0`: niño dibujando en un hospital (10 s).
- `zoom_in_on_4226_0`: acercamiento a un dibujo de agradecimiento (4 s).
- `zoom_out_o_4278_0`: plano abierto del dibujo en el hospital (4 s).

Ninguno coincide con el video de Victoria mostrado en la plantilla. Por eso no se presenta como su historia.

Los montos de donación son propuestas provisionales porque las tarjetas de la referencia no incluyen importes. No hay procesamiento de pagos, transmisión de formularios ni almacenamiento de datos. Los campos de tarjeta están deshabilitados. El video requiere el archivo o enlace original; su botón informa que está pendiente.

La pantalla principal indica 12 años para Victoria y la nueva referencia indica 13 años. Cada página conserva por ahora su referencia, pendiente de confirmar en las correcciones.
El video astronauta.mp4 se identificó visualmente como el encabezado del inicio y se integró allí con reproducción silenciosa, botón de pausa y respeto de la preferencia de reducir movimiento. No se utiliza como testimonio de Victoria.
El encabezado del inicio reproduce automáticamente el video, sin sonido y en bucle. La curva se muestra completa y más abajo para dejar visible una mayor parte del video.
