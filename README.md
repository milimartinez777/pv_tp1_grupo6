# pv_tp1_grupo6 
                        PROGRAMACIÓN VISUAL
                        TRABAJO PRÁCTICO Nº 1 GRUPAL 
            |GRUPO 6|
1. CRUZ Jonatan Anibal
https://github.com/Jonatan27C
2. JUAREZ David
https://github.com/davidjuharez
3. MARTINEZ Milagro Soledad
https://github.com/milimartinez777
4. RODRIGUEZ María Lourdes
https://github.com/lzmar
5. VENENCIA Shashiquen Brenda Mailén
https://github.com/shashiquen-b-m-venencia

Nuestro repositorio: (https://github.com/milimartinez777/pv_tp1_grupo6)

LAYOUT BASE de una plataforma de "Gestión de Proyectos". Un SITIO ESTÁTICO por el momento
                        HTML
    Dentro de la carpeta raíz deben ir los  siguientes archivos:
            1.index.html
                Dashboard Principal
                Para el inicio del sitio, diseñé un Dashboard Académico utilizando etiquetas semánticas para organizar la información. La estructura principal cuenta con un <header> que integra el logo y el menú de navegación, un <main> para el contenido dinámico y una <section> informativa sobre el ecosistema de la carrera.Dividí el contenido central en tres áreas funcionales:Estadísticas: Tarjetas creadas con <section> para visualizar datos rápidos como proyectos activos y mensajes.Novedades: Una lista ordenada (<ol>) que registra cronológicamente las últimas acciones del sistema.Barra Lateral: Un <aside> con accesos directos a proyectos destacados mediante mini-tarjetas.Descripción de Estilos (CSS) En lo visual, implementé un diseño moderno basado en CSS Grid para la estructura general y Flexbox para alinear los componentes internos. Utilicé variables globales (:root) para asegurar la consistencia de colores y tipografías en toda la página.Apliqué efectos de interactividad como el escalado (scale) y sombras dinámicas en el logo y los enlaces mediante los estados :hover y :active. Además, incorporé fondos con imágenes y gradientes para dar profundidad visual a las secciones, logrando una interfaz atractiva y profesional.
            2.proyectos.html
                Explorador de Proyectos
                Construcción de la página de Proyectos (HTML)
                Para organizar esta sección, empezamos con un header que contiene el título principal y un menú de navegación creado con una lista desordenada (<ul>), lo que permite moverse fácilmente entre las distintas páginas del sitio.
                El contenido central se agrupó en una etiqueta main, la cual dividimos en dos partes funcionales: un lateral (<aside>) donde colocamos los filtros de búsqueda mediante etiquetas (select) y (option) para elegir categorías o años, y una zona principal (<section>) destinada a mostrar todos los trabajos académicos de forma ordenada.
                Dentro de la galería, cada trabajo se representó con la etiqueta (<article>), funcionando como una tarjeta independiente que contiene toda la información del proyecto. 
                Usamos etiquetas (<h3>) para los nombres de los proyectos, (<img>) para las capturas de pantalla y (<p>) para las descripciones y categorías.
                También incluimos etiquetas (<a>) para crear los botones de acceso a los detalles y saltos de línea (<br>) para generar espacios visuales.
                Finalmente, cerramos la estructura con un (<footer>) que identifica nuestra carrera y el año actual, logrando un código semántico y fácil de entender.
                 


            3.detalle.html
                Detalles del Sistema de Gestión de una biblioteca escoolar
                DESCRIPCION DE DETALLE HTML
                El Encabezado:  Se muestra el titulo Gestión de Biblioteca, los autores y tiene los botones para moverse a otras partes de nuestra web.
                En el cuerpo/body: Dos párrafos que cuentan por qué es importante el sistema: sirve para que los libros no se pierdan, para saber quién los tiene y para que los alumnos encuentren lo que buscan más rápido.
                Una lista con enlaces directos a docs importantes, como el plano del sistema y el manual de uso.
                Un pequeño cuadro donde se reconoce quién es la coordinadora y quién se encarga de la investigación.

                DESCRIPCION DE DETALLE EN STYLE
                En la cabecera: tenemos una caja con bordes redondeados y mucho espacio alrededor para que el título no quede "apretado".

                El cuadro de texto: El párrafo de descripción ahora está dentro de una "cajita" blanca (o de un color claro) con bordes gruesos y redondeados, permitiendo que destaque.

                Luego tenemos efectos de flotado, cambio de colores y zoom haciendo que sea atractivo para el lector
            
              4.perfil.html
                Información Personal del usuario
                
                Para la maquetación de la página web solicitada nos dijeron que usaramos el lenguaje HTML (para la estructura  y su contenido) seguido de estilos mediante CSS para la parte visual .
                Para el perfil de usuario nos da como punto de partida su imagen, nombre y rol el cual tambien vamos a tener en cuenta a la hora de crear un perfil de usuario para ello tuvimos en cuenta:

                *Uso de semántica correcta con etiquetas de ...
                *Bloque: header, main, nav, footer, aside.
                *Contenido:section, article, table, form, h1-h6, ul, li,p.
                *Navegación:etiquetas a. 
                *Uso de estilos  con atributo y elemento style además de un archivo con su respetiva carpeta css y con la implementación del grid y flexbox con una variable global "root".
                Contamos con dos secciones divididas como Perfiles, en donde se ubican perfiles ya existentes con una imagen que define su sexo y otra sección Nuevo Perfil que cuenta con un formulario para ingreso de datos.   
