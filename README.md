5. # PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT
    1. ## 5.1 Software Configuration Management.
        1. ### 5.1.1 Software Development Environment Configuration
            A continuación, daremos a conocer los productos de software que hemos utilizado para el desarrollo de nuestro proyecto.
            **Project Management**				

            - **Whatsapp:** [https://web.whatsapp.com/](https://web.whatsapp.com/)
                La plataforma de Whatsapp se empleó para realizar la organización de tareas para el equipo, así como también para poder ayudarnos entre nosotros ante cualquier duda que se tuviera en el trabajo.
            - **Discord:** [https://discord.com/](https://discord.com/)
                La plataforma Discord se empleó para poder realizar las reuniones de forma virtual, en dichas reuniones dábamos un reporte sobre el avance de las tareas que se nos habían asignado, así como también se usó para la elaboración de idea de negocio.

            **Product UX/UI Design**

            - **Miro:** [https://www.miro.com](https://www.miro.com)

                La plataforma Miro se empleó para el desarrollo del Lean ux canvas, Análisis de competidores, As-is Scenario mapping, To-be Scenery mapping
            - **Uxpresia:** [https://uxpressia.com/](https://uxpressia.com/)
            
                La plataforma Uxpresia se empleó para la elaboración del User Persona, Empathy maps, Journey Maps e Impact maps.
            - **Figma:** [https://www.figma.com/](https://www.figma.com/)

                La plataforma figma se empleó para el desarrollo wireframes y mock up del landing page, y para los wireframes, mock up y prototyping del web applications 

            **Software Development**

            - **Landing Page**

                Para el desarrollo de nuestro landing page se usará  HTML5, CSS y Javascript.
            - **Frontend Web Application**

                Se ha utilizado a Vue como framework de Javascript. En adición, para la implementación de componentes reutilizables y accesibles se usó Prime Vuel como biblioteca de componentes UI. 

            **Software Testing**
            
            Para la realización de pruebas de testeo de software  que se ha utilizado para el landing page y  la aplicación web hemos empleado las herramientas de desarrollador de los siguientes navegadores web: Google Chrome (<https://www.google.com/chrome/>), Microsoft Edge (<https://www.microsoft.com/en-us/edge>) y Mozilla Firefox (<https://www.mozilla.org/en-US/firefox/browsers/>). Asimismo, dichos navegadores cuentan con aplicaciones desktop y móviles las cuales son totalmente gratuitas y por consiguientes accesible para todas las personas.

            **IDE's de desarrollo**

            - **Webstorm:** [https://www.jetbrains.com/webstorm/](https://www.jetbrains.com/webstorm/)

                Webstorm es un IDE enfocado al desarrollo de frontend y posee una gran cantidad de herramientas que pueden agilizar el proceso de desarrollo. Para poder usar Webstorm es necesario tener una licencia

            **Software Deployment**

            - **Github Pages:** [https://pages.github.com/?(null)](https://pages.github.com/?\(null\))
                
                La plataforma Github pages se empleó para el deployment del landing page, para ello fue necesario vincular el repositorio de github con github pages. De esta manera, Github Pages se encargará automáticamente del deploy de la página.

            **Software Documentation**

            - **Google Drive:** [https://www.google.com/intl/es-419_pe/drive/](https://www.google.com/intl/es-419_pe/drive/)

                La plataforma Google Drive se empleó para la creación de archivos de documento (Google Docs) y presentación. Se optó por esta plataforma ya que permite el desarrollo colaborativo.
            - **Github: https:** [https://github.com/](https://github.com/)

                La plataforma Github se empleó para la creación de documentación de nuestro proyecto, así como del landing page. Se optó por esta plataforma porque permite el desarrollo colaborativo entre desarrolladores. La evidencia de commits demuestra la participación que ha tenido cada uno de los integrantes en el desarrollo del proyecto.
            - **Structurizr:** [https://structurizr.com/](https://structurizr.com/)

                La plataforma Structurizr se empleó para la creación de los diagramas C4 de nuestro proyecto, para la elaboración de los diagramas se necesita emplear una sintaxis similar a un lenguaje de programación.
            - **Vertabelo:** [https://vertabelo.com/](https://vertabelo.com/)

                La plataforma Vertabelo es una aplicación web colaborativa la cual ha sido empleada para la elaboración del diseño de base de datos.
        2. ### 5.1.2 Source Code Management.
        3. ### 5.1.3 Source Code Style Guide & Conventions.
            **HTML:** [https://www.w3schools.com/html/html5_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)

            **Index.html:**
            Es la página por defecto dentro de los directorios de los servidores de cualquier sitio web que se carga siempre que se solicita un dominio y no se especifica el nombre de un archivo en específico. Y en la mayoría de los casos el propio servidor web es el que se encarga de buscar el archivo index.

            **Convenciones de HTML:**

            - Se debe declarar el tipo de documento en la primera línea: < !DOCTYPE html >
            - Se recomienda usar minúsculas en las etiquetas y estructuras: < body > < p >
            - Se recomienda cerrar todas las etiquetas y estructuras: < p >This is a paragraph. < /p >
            - Se recomienda usar minúsculas en los atributos: < a href="https://www.google.com/html/" >
            - Se recomienda usar comillas en los valores de atributo: < table class="striped" >
            - Se debe especificar el alt, ancho y alto de las imágenes: < img src="html5.gif" alt="HTML5" style="width:128px; height:128px" >
            - Se recomienda no usar espacios a la hora de usar el signo “=”: < link rel="stylesheet" href="styles.css" >
            - Solo se debe usar líneas en blaco para facilitar la lectura de bloques de códigos grandes o lógicos
            - No se debe omitir el elemento < title > ya que es vital para el motor de búsqueda, así como también se recomienda que el contenido de los < title > sea preciso y significativo: < title >HTML Style Guide and Coding Conventions< /title >
            - No se recomienda omitir las etiquetas < html > y < body > ya que puede producir errores en navegadores antiguos y puede bloquear el software DOM y XML.
            - Se debe usar el atributo lang para declarar el idioma de la página web: < html lang="en-us" >
            - Se debe utilizar el atributo meta para una interpretación adecuada e indexación correcta en los motores de búsqueda: < meta charset="UTF-8" >

            **CSS:** [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)

            **Style.css:**
            El estilo de cascada (CSS) se puede usar para estilos de texto, por ejemplo, cambiar de color y el tamaño de los encabezados, enlaces, entre otras cosas.

            **Convenciones de CSS**

            - Utilizar el protocolo HTTPS para imágenes y otros archivos multimedia: @import 'https://fonts.googleapis.com/css?family=Open+Sans’; Todo el código debe estar en minúsculas como nombres de elementos HTML, atributos, valores de atributo, entre otros: color: #e5e5e5;
            - El nombre de una clase debe transmitir lo que hace de la forma más breve posible ya que de esta manera se apoya la comprensibilidad y eficiencia del código: navegación {}. autor {} Se debe separar los nombres de las clases con un guion (“-”): navegación {}. autor {}
            - Se recomienda usar propiedades abreviadas cuando sea posible: border - top: 0;
            - Se recomienda usar la notación hexadecimal de 3 caracteres en colores que lo permitan: color: #ebc;
            - Se recomienda ordenar las declaraciones de propiedades y características en orden alfabético
            - Se debe usar un “;” después de cada declaración: pantalla: bloque;
            - Se debe usar un espacio después de los “:” de cada nombre de la propiedad: font – weight-bold;
            - Se debe usar un espacio entre el último sector y la llave “ { “que comienza el bloque de declaración: vídeo {…}
            - Se debe usar las comillas simples (‘ ‘) para los atributos y valores de propiedad: familia de fuentes : ' open sans', arial, sans - serif ;

            **Gherkin:** [https://cucumber.io/docs/gherkin/reference/](https://cucumber.io/docs/gherkin/reference/)

            **< usertStoryID >.featrue:**

            En este archivo de formato feature estarán las historias de usuario como características de la aplicación. Asimismo, se pueden encontrar los criterios de aceptación para las diversas situaciones. 
            **Convenciones de Gherkin:**

            - Se utiliza la palabra Feature para introducir una descripción de alto nivel de una función de software y agruparlos en escenarios relacionados
            - Example o Scenario sirven para plantear una situación
            - Se utiliza Given para describir el contexto inicial, When para describir un evento y Then para describir un resultado esperado y And para adicionar información. Given,When,Then y And se usan para describir un escenario
            - El carácter “|” sirve para formar una tabla datos, las cuales son útiles para pasar una lista de valores a una definición de paso.

            **JavaScript:** [https://google.github.io/styleguide/jsguide.html](https://google.github.io/styleguide/jsguide.html). 
            **Convenciones de JavaScript:**

            - Se debe usar Camelcase para los nombres de variables y funciones.
            - Se debe usar Pascalcase para los nombres de constructores o clases.
            - Se debe usar mayúsculas y guiones bajos para los nombres de las constantes, por ejemplo UPPER_CASE_WITH_UNDERSCORES.
            - Se debe usar let y const para definir las variables, var debe evitarse.
            - Para los comentarios de una sola línea debe usar “ // ” y para bloques de comentario se debe usar  “ /* */ ”.
            - Se debe incluir un punto y coma al final de cada instrucción.

            **C#:** [https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)

            **Convenciones de C#:**

            - Se debe usar PascalCase para los nombres de clases, tipos y métodos. Por ejemplo: MiClase, MiTipo, MiMetodo().
            - Se debe usar CamelCase para los nombres de variables locales y parámetros.Por ejemplo:miVariable, miParametro.
            - Se debe usar mayúsculas para los nombres de variables constantes, por ejemplo: MI_CONSTANTE.
            - Para los comentarios de una sola línea debe usar “ // ” y para bloques de comentario se debe usar  “ /* */ ”.
            - Se debe especificar el modo acceso para las clases, métodos y propiedades como lo son:  public y  private
            - Se debe usar “\_” para nombres de instancias privadas, por ejemplo: private int _miCampoPrivado.

            **ASP.NET Core:** [https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#coding-guidelines](https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#coding-guidelines)

            **Convenciones de ASP.NET Core:**

            - Se debe usar PascalCase para los nombres de clases y métodos. Por ejemplo: MiClase, MiMetodo().
            - Se debe definir los atributos de ruta para definir las rutas del controlador. Por ejemplo: [Route("api/[controller]" ) ].
            - Se debe usar verbos HTTP como prefijos en los métodos de acción, así como también se debe especificar el nombre de la acción, por ejemplo:GetUsuario(), PostUsuario().
            - Se debe emplear espaciado después de usar comas y operadores.

            **Vue.js:** [https://v2.vuejs.org/v2/style-guide/?redirect=true](https://v2.vuejs.org/v2/style-guide/?redirect=true)

            **Convenciones de Vue.js:**

            - Se debe usar Pascalcase para los nombres de los componentes, por ejemplo: MiComponente.
            - Se debe usar kebab-case para los nombres de archivos y eventos personalizados en los componentes, por ejemplo: mi-componente.vue, mi-evento.
            - Se debe usar el prefijo “ v- “al usar directivas en las plantillas como: v-if, v-for .
            - Se debe usar camelCase para los nombres de método y propiedades en los componentes: miPropiedad, miMetodo.
            - Se debe evitar combinar v-if con v-for en un mismo scope.
            - Se recomienda usar prefijos para evitar conflictos con los nombres de clases de estilos.
        4. ### 5.1.4 Software Deployment Configuration

            
