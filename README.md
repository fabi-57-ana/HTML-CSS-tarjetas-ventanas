Proyecto de Práctica Web: Ventanas Modales y Tarjetas

Descripción General

Este proyecto contiene cuatro archivos HTML diseñados para practicar conceptos de desarrollo web, centrándose en ventanas modales y diseños de tarjetas. Cada archivo demuestra diferentes técnicas de HTML y CSS, como el uso del elemento <dialog>, diseños con Flexbox y componentes de tarjetas estilizadas. El proyecto tiene fines educativos para ayudar a los desarrolladores a comprender e implementar estos patrones de diseño web.

Estructura del Proyecto

El proyecto está organizado en un solo directorio con los siguientes archivos y carpetas:

index.html: Muestra una ventana modal utilizando el elemento <dialog> de HTML con un botón de cierre basado en un formulario y un efecto de desenfoque en el fondo.

tarjeta.html: Presenta tres componentes de tarjetas con diferentes estilos (predeterminado, rojo y verde) para mostrar+ mostrar variaciones de clases CSS.

holy_grail.html: Implementa el diseño "Holy Grail" usando Flexbox, incluyendo un encabezado, navegación, contenido principal, barra lateral y pie de página.

card_presentacion.html: Muestra un único componente de tarjeta con una imagen, título, subtítulo y contenido de texto, similar a una tarjeta de perfil.

css/stylos.css: La hoja de estilos que contiene todas las reglas CSS para los archivos HTML (se asume que existe, ya que se referencia en los archivos HTML).

img/: Directorio que contiene las imágenes usadas en los componentes de tarjetas (por ejemplo, imagen_tarjeta.png).

Requisitos Previos

Para ejecutar este proyecto, necesitas:

Un navegador web (por ejemplo, Chrome, Firefox, Edge).

Un editor de texto (por ejemplo, VS Code) si deseas modificar los archivos.

Un servidor local (opcional) para servir los archivos, ya que algunas funcionalidades (como la carga de imágenes) pueden no funcionar al abrir los archivos HTML directamente desde el sistema de archivos. Puedes usar herramientas como Live Server en VS Code o un servidor HTTP simple como http.server de Python.

Instrucciones de Configuración

Clona o descarga el proyecto en tu máquina local.

Asegúrate de que el directorio del proyecto contenga los archivos HTML, el archivo css/stylos.css y el directorio img/ con las imágenes requeridas.

Abre los archivos HTML en un navegador web:

Para una visualización simple, haz doble clic en los archivos HTML para abrirlos en tu navegador predeterminado.

Para un funcionamiento correcto (por ejemplo, para cargar imágenes o probar CSS), sirve los archivos usando un servidor local:

python -m http.server 8000

Luego, navega a http://localhost:8000 en tu navegador.

Explora cada archivo HTML para ver las características implementadas:

index.html: Haz clic en el botón "X" para cerrar la ventana modal (nota: la ventana modal está configurada como open por defecto).

tarjeta.html: Observa las tres tarjetas con diferentes estilos.

holy_grail.html: Examina el diseño basado en Flexbox con navegación y secciones de contenido.

card_presentacion.html: Revisa el diseño de una única tarjeta.

Características

Ventana Modal (index.html):

Utiliza el elemento <dialog> con el atributo open para una ventana emergente modal.

Incluye un formulario con method="dialog" para cerrar la ventana automáticamente al hacer clic en el botón.

Aplica un efecto de desenfoque al contenido de fondo.

Diseños de Tarjetas (tarjeta.html, card_presentacion.html):

Muestra componentes de tarjetas con imágenes, títulos, subtítulos y texto.

tarjeta.html incluye tres tarjetas con diferentes esquemas de color (predeterminado, rojo y verde) para demostrar variaciones de clases CSS.

card_presentacion.html se centra en un diseño de tarjeta único y pulido.

Diseño Holy Grail (holy_grail.html):

Implementa un diseño responsive usando Flexbox.

Incluye un encabezado con navegación, un área de contenido principal, dos barras laterales (una para navegación secundaria) y un pie de página.

Notas

El archivo CSS (stylos.css) se referencia en todos los archivos HTML, pero no se proporcionó en la entrada. Asegúrate de que exista y contenga los estilos necesarios para clases como modal__content, card, red-card, green-card, main-wrapper, etc.

El archivo de imagen (imagen_tarjeta.png) se referencia en los archivos HTML de tarjetas. Reemplázalo con una imagen real o actualiza el atributo src para que apunte a una ruta de imagen válida.

El código JavaScript comentado en index.html no es necesario, ya que method="dialog" maneja la funcionalidad de cierre de la ventana modal. Puedes eliminarlo o descoméntarlo si prefieres un enfoque basado en JavaScript.

El proyecto está principalmente en español (por ejemplo, títulos como "VENTANA MODAL" y "DESARROLLADOR WEB"), pero algunos archivos usan inglés (lang="en"). Considera estandarizar el atributo de idioma para mayor consistencia.

Mejoras Futuras

Agregar el archivo stylos.css faltante para garantizar un estilo consistente en todos los archivos HTML.

Implementar un diseño responsive para que los diseños sean compatibles con dispositivos móviles.

Mejorar la ventana modal con JavaScript para alternar la visibilidad dinámicamente sin el atributo open.

Añadir interactividad a los enlaces de navegación en holy_grail.html.

Incluir un proceso de compilación o un preprocesador de CSS (por ejemplo, SASS) para una mejor gestión de estilos.

Licencia

Este proyecto es para fines educativos y no incluye una licencia específica. Siéntete libre de usarlo y modificarlo para aprendizaje personal.
