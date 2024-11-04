El repositorio "tarea_2" contiene el codigo desarrollado para una página web de “Clínica Chillán”, presentando las vistas de las secciones:
• Home: pantalla de inicio del sitio web, en el se encuentra una sección de bienvenida a los usuarios y se da a conocer la visión y misión de la clínica, sus principales servicios y algunos testimonios de usuarios dando a conocer su experiencia. • Equipment: en esta sección de la pagina web, se presenta el compromiso de la clínica con la excelencia profesional y se presenta a parte de su equipo médico. • Contact: en esta sección de la página web, se presenta un formulario para que los usuarios envíen sus consultas, dudas u sugerencias y puedan ser atendidos por los funcionarios administrativo, además, se presenta un mapa con su ubicación de la clínica.
Para el desarrollo de este proyecto se han utilizado los lenguajes HTML y SASS y algunos recursos extras como iconos de Bootstrap.
En este repositorio, se encuentra todo el contenido de la página web, y encontraras los siguientes carpetas y archivos:
• contact.html: archivo html, que presenta la estructura del contenido de la sección contacto de la página web. 
• home.html: archivo html, que presenta la estructura del contenido de la sección home, página principal del sitio. 
• equipment.html: archivo html, que presenta la estructura del contenido de la sección equipo de la página web. 
• shared: en esta carpeta se encuentran todos los recursos gráficos utilizados en la página web, en este caso en particular, se encuentran las carpetas img que contiene las mágenes asociadas al logo de la clínica y equipo médico y que contiene el archivo styles que contiene las carpetas y archivos asociados a la implementación de estilos.
 En esta ocasión, se utilizo sass y la metodología de carpetas 7-1, la cual se distribuye de la siguiente manera:
•	abstract: carpeta que contiene 2 archivos asociados a las variables creadas mediante sass y mixims
•	base: carpeta que contine archivo asociada a la tipografía general asociada a la página web.
•	components: carpeta que contine código sass asociado a 3 componentes desarrollados buttons, card, map.
•	layout: carpeta que contiene archivos sass asociados a os estilos de header, footer, navegación, formularios, lista y main.
•	pages: estilos específicos asociadas a las paginas principales del sitio web home, equipment y contact.
•	themes: estilos asociados a temas claro y oscuro
•	vendors: carpeta que contiene archivos asociados a librerías externas.
•	main.scss: archivo encargado de importar todos los ficheros sass descritos anteriormente.
Otro de los puntos destacados a mencionar, del sitio web, es la responsidad, el sitio se adapta a cualquier tamaño de pantalla, sin inconvenientes, para ello se utilizaron media queries, los puntos de ruptura seleccionados, fueron los siguientes: 
@media (max-width: 575.98px) 
@media (max-width: 767.98px) 
@media (max-width: 991.98px) 

Para visualizar este proyecto en tu navegador puedes descargar este repositorio en formato zip, y descomprimir su contenido, es recomendable que utilices un editor como Visual Studio Code para visualizar el código de cada archivo de una forma adecuada e instalar dos extensiones, la primera Live Server, esta extensión permite abrir una pestaña en tu navegador predeterminado y podrás visualizar todo el contenido de la página web y la segunda Live Sass Server, esta extensión, permitirá al seleccionarla que se compila el código sass incluido y ver los estilos creados en la página web. Si ya cuentas con manejo de Git, puedes clonar este repositorio mediante los métodos provistos por GitHub.
