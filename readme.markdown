# Jose Luis Pérez Portfolio

Este portfolio está basado en la plantilla "Timeline" para Jekyll, puedes encontrar más información para esta plantilla en la página: 

https://github.com/kirbyt/timeline-jekyll-theme 

## Estructura de directorios

El portfolio hereda la estructura de la plantilla con ciertas modificaciones. Este resultado se ordena en una serie de directorios y ficheros los cuales cumplen la siguiente estructura:

	joluper.github.io/
	├── about.html				- ocumento que almacena una breve descripción personal.
	├── career.html				- documento utilizado para el timeline (simplemente se declara el timeline).
	├── _config.yml				- fichero de configuración de jekyll.
	├── contact.html			- documento que almacena los datos de contacto.
	├── css 					- directorio en el que se almacenan los ficheros '.css' utilizados.
	│   ├── bootstrap.css		- fichero de estilos básico.
	│   ├── bootstrap.min.css	- fichero de estilos básico reducido.
	│   ├── grayscale.css		- fichero de estilos para los colores del tema.
	│   └── timeline.css		- fichero de estilos para el timeline.
	├── font-awesome			- directorio donde se almacena la fuente utilizada principalmente.
	│   ├── css					- ficheros de estilos para font-awesome.
	│   │   └── [...]			
	│   ├── fonts				- ficheros de fuentes para font-awesome.
	│   │   └── [...]
	│   ├── less				- ficheros less para font-awesome.
	│   │   └── [...]
	│   └── scss				- ficheros de estilo scsss para font-awesome.
	│       └── [...]
	├── fonts					- directorio donde se almacena otras fuentes utilizadas.
	│   └── [...]
	├── img						- directorio donde se almacenan las imágenes utilizadas.
	│   ├── [...]
	│   └── timeline			- directorio donde se almacenan las imágenes utilizadas en el timeline.
	│       └── [...]
	├── _includes				- directorio donde se almacenan los ficheros '.html' principales.
	│   ├── footer.html			- fichero que contiene el pie de página utilizado en la web.
	│   ├── header.html			- fichero que contiene la cabecera de página utilizada.
	│   ├── head.html			- fichero que contiene el principio de fichero de las páginas.
	│   ├── js.html				- fichero que contiene código html referente a javascript utilizado.
	│   └── navigation.html		- fichero que contiene la barra de navegación de la web.
	├── index.html				- fichero html principal que carga el resto de ficheros.
	├── js						- directorio donde se almacenan los ficheros javascript utilizados.
	│   └── [...]
	├── _layouts				- directorio donde se almacenan las plantillas de estructuración de una página.
	│   └── default.html		- plantilla principal de estructuración de una página.
	├── less					- directorio de almacenamiento de ficheros less necesarios.
	│   └── [...]
	├── LICENSE					- documento de licencia.
	├── _posts					- directorio de posts interpretados como entradas del timeline.
	│   └── [...]
	└── readme.markdown			- fichero que estás leyendo ahora mismo.

En este caso, los posts son interpretados como entradas en el timeline y los ficheros ".html" como páginas de la web.

Tanto los posts como las páginas deben empezar con una cabecera del siguiente estilo, de este modo pueden ser identificadas y tratadas por jekyll.

	---
	layout: null
	section-type: default
	title: nombre
	---

Cualquier modificación de estilo debe ser realizada en los ficheros '.css' hubicados en el directorio /css/.
