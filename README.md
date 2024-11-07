El repositorio "tarea_2" contiene el codigo desarrollado para una página web de “Clínica Chillán”, presentando las vistas de las secciones:

- Home: pantalla de inicio del sitio web, en el se encuentra una sección de bienvenida a los usuarios y se da a conocer la visión y misión de la clínica, sus principales servicios y algunos testimonios de usuarios dando a conocer su experiencia.
- Equipment: en esta sección de la pagina web, se presenta el compromiso de la clínica con la excelencia profesional y se presenta a parte de su equipo médico.
- Contact: en esta sección de la página web, se presenta un formulario para que los usuarios envíen sus consultas, dudas u sugerencias y puedan ser atendidos por los funcionarios administrativo, además, se presenta un mapa con su ubicación de la clínica.

Para el desarrollo de este proyecto se han utilizado los lenguajes HTML, el preprocesador SASS y algunos recursos extras como iconos de Bootstrap.

En este repositorio, se encuentra todo el contenido de la página web, sus carpetas y archivo se encuentran estructurados de la siguiente manera:
- contact.html: archivo html, que presenta la estructura del contenido de la sección contacto de la página web. 
- home.html: archivo html, que presenta la estructura del contenido de la sección home, página principal del sitio. 
- equipment.html: archivo html, que presenta la estructura del contenido de la sección equipo de la página web. 
- assets: archivo que contiene recursos graficos dentro del se encuentra la carpeta img, que contiene todas las imagenes utilizadas en el sitio como el logo y el equipo medico y la carpeta styles la cual agrupa los estilos scss utilizados en el proyecto, esta carpeta esta creada bajo la metodología de carpetas 7-1, la cual se distribuye de la siguiente manera:
  - abstract: carpeta que contiene 2 archivos asociados a las variables creadas mediante sass y mixims
  - base: carpeta que contine archivo asociada a la tipografía general asociada a la página web.
  - components: carpeta que contine código sass asociado a 3 componentes desarrollados buttons, card, map.
  - layout: carpeta que contiene archivos sass asociados a os estilos de header, footer, navegación, formularios, lista y main.
  - pages: estilos específicos asociadas a las paginas principales del sitio web home, equipment y contact.
  - themes: estilos asociados a temas claro y oscuro
  - vendors: carpeta que contiene archivos asociados a librerías externas, en esta ocación, la carpeta se encuentra vacia, ya que no se han utilizado librerias extras.
  - main.scss: archivo encargado de importar todos los ficheros sass descritos anteriormente.


Otro de los puntos destacados a mencionar, del sitio web, es la responsividad, el sitio se adapta a cualquier tamaño de pantalla, sin inconvenientes, para ello se utilizaron media queries, los puntos de ruptura seleccionados, fueron los siguientes: 
- @media (max-width: 575.98px) 
- @media (max-width: 767.98px) 
- @media (max-width: 991.98px) 

Para visualizar este proyecto en tu navegador puedes descargar este repositorio en formato zip, y descomprimir su contenido, es recomendable que utilices un editor como Visual Studio Code para visualizar el código de cada archivo de una forma adecuada, para ello, es necesario contar con dos extensiones, las cuales pueden instalar escribiendo su nombre en la seccion extensiones de visual studio y presionar la opcion install, la primera es Live Server, la cual, una vez instalada aparecera una opcion en la esquina inferior derecha  de visual studio code titulada como "Go live" la cual debes presionar, esto permitira abrir una pestaña en tu navegador predeterminado y podrás visualizar todo el contenido de la página web. la segunda extension que debes instalar es Live Sass Server, esta extensión, una vez instalada, dara la opcion "watch Sass" en la esquina inferior derecha la cual al seleccionarla permitira que se compile el código sass incluido y ver los estilos creados en la página web. cabe destacar, que ambas opciones deben ser seleccionadas para visualizar correctamente el sitio web de la clinica.

Si ya cuentas con manejo de Git, puedes clonar este repositorio mediante el comando 
```bash
git clone https://github.com/lorenasotosanmartin/tarea_2
```
e instalar y trabajar con las extensiones de la forma antes señalada.
