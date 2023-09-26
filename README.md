4. # Chapter IV: PRODUCT DESIGN

    1. ## 4.1 Style Guidelines

        1. ### 4.1.1 General Style Guidelines

            #### Branding
            El logo principal está conformado por las letras iniciales de las palabras del nombre de la aplicación ¨S¨ y ¨K¨. 

            #### Typography
            La tipografia que utiizaremos será Monserrat con sus variantes Regular, Medium, Semibold y Bold. El tamaño de la letra varía entre 1 rem (16px), 15 rem (24px), 2 rem (32xp) y 3 rem (48px).

            #### Colors
            El color principal que se utilizará es un tono azul (#3066BE) y los colores secundarios son un tono verde (#00C9A7) y un tono blanco para contrastes más claros (#F5F9FF).

            #### Spacing
            El spacing mantiene

            * Botones: pading de 1 rem (16px) vertical y 2 rem (32px) horizontal.
            * Margin entre texto 1 rem (16px).
            * Margin entre elemntos 1,5 rem (24px).
            * Margin entre secciones 6 rem (72 px).

            #### Dimensión 
            La orientación a seguir para el diseño sería mantener un tono formal pero entusiasta. Para ello, podemos utilizar colores profesionales como el azul y, al mismo tiempo, incorporar un toque de entusiasmo mediante el uso de tonos verdes. En cuanto al diseño de los iconos y las formas, deberíamos optar por diseños que resulten amigables para el usuario, lo que implicaría utilizar principalmente bordes curvos.

        2. ### 4.1.2 Web Style Guidelines

            Se ha empleado la tendencia de diseño web de minimalismo funcional, donde el color blanco predomina en el fondo de la mayoría de las secciones con el objetivo de proporcionar una visualización limpia y destacar el contraste entre los elementos.

            Por otro lado, se han incorporado de manera moderada iconos coloridos en algunas secciones con el fin de diversificar la paleta de colores sin comprometer el estilo minimalista de la página web.

    2. ## 4.2 Information Architecture 

        1. ### 4.2.1 Organization Systems
            En lo que respecta a la organización visual del contenido, en primer lugar, se ha seguido el patrón de jerarquía visual para estructurar la información en las secciones. La importancia de las frases varía en función del tamaño de la fuente, siendo una oración de 48px (3 rem) la más destacada, seguida de 32px (2 rem), 24px (1,5 rem) y finalmente 16px (1 rem).

            Además, se ha optado por la organización matricial ordenada para la presentación de las características del producto y los planes de pago.

            Por otro lado, en cuanto a los esquemas de categorización, se ha implementado una categorización basada en la audiencia, ya que se dirige a dos segmentos objetivos: colegios y padres de familia. Cada uno de estos segmentos contará con secciones y funciones específicas.

            Asimismo, se ha empleado la categorización cronológica para el registro de entradas cuando un usuario consulte la base de datos que contenga fechas. El orden de presentación será descendente, de modo que las entradas más recientes aparezcan al principio.

        2. ### 4.2.2 Labeling Systems
            En la página de inicio (landing page), se ha buscado reducir al mínimo el uso de iconos representativos para los enlaces y se ha dado prioridad al uso de texto con botones que destacan. De esta manera, se mantiene el estilo minimalista de la página de inicio. Además, se han utilizado iconos en color para representar las características de la aplicación y los enlaces a las redes sociales.

            En cuanto a la aplicación web, se emplearán los iconos de la biblioteca de Prime Vue al trabajar con el framework de Vue ([https://primevue.org/icons](https://primevue.org/icons)).

        3. ### 4.2.3 SEO Tags and Meta Tags

            #### Landing Page
            ```html
            <meta charset="UTF-8"> 
            <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
            <meta name="viewport" content= width-device width, initial-scale=1.0><meta name="robots" content="index, follow">
            <link rel="shortcut icon" href=" /images/favicon png" type-"image/x-icon" /> <title>JobSync</title>
            <meta name="keywords* content-'jobysnc, human resources, recruitment process software, software for HR, software for hiring"» ‹meta name="description' content-"Recruit top talent with JobSync's highly rated software. Intuitive platform saves time and helps you hire faster. Start today.">
            ```

            #### Web Aplication

        4. ### 4.2.4 Searching Systems
            En lo que respecta a los sistemas de búsqueda, se planea implementar un sistema de filtros para el registro de notas por alumno. Además, se habilitarán filtros por tablas en las siguientes situaciones:

            * Cuando los padres de familia busquen las notas de los exámenes de sus hijos.
            * Cuando los profesores necesiten revisar y, en ciertos casos, corregir las notas de sus alumnos.
        
        5. ### 4.2.5 Navigation Systems
            En landing page, en la parte superior se situará la barra de navegación junto con un botón que permitirá a los usuarios acceder directamente a la página de inicio de sesión de la aplicación. Una vez que el usuario haya iniciado sesión, también dispondrá de accesos directos a todas las funciones principales en la parte superior, además de contar con un ashboard debajo que mostrará información relevante, como el estado de un proceso y notificaciones importantes.
        
    3. ## 4.3 Landing Page UI Design 
        En esta sección se presentará la propuesta del landing page, así como algunas vistas previas del prototipo de la aplicación web. Comenzaremos mostrando los wireframes y luego el prototipo, tanto en su versión web como en la móvil. Además, los diseños reflejarán las pautas de diseño web mencionadas anteriormente. Para la creación de estos diseños, hemos utilizado Figma, una aplicación que permite la colaboración en tiempo real con el equipo de forma remota.

        1. ### 4.3.1 Landing Page Wireframe 
            |**Links Figma Landing Page Wireframe**||
            | - | :- |
            |Web|Móvil|
            |<https://www.figma.com/proto/aFkdd9BboBQAtj7VyPdAfA/SkillGrade-Landing-Page?type=design&node-id=34-707&t=H8P6ucfedV7S16fN-1&scaling=min-zoom&page-id=0%3A1&mode=design>|<https://www.figma.com/proto/aFkdd9BboBQAtj7VyPdAfA/SkillGrade-Landing-Page?type=design&node-id=65-2216&t=PTohzeE0pn2XXj8K-1&scaling=min-zoom&page-id=0%3A1&mode=design>|

            <br>

            ![](https://imgur.com/2D903my.png)

        2. ### 4.3.2 Landing Page Mock-ups
            |**Links Figma Landing Page Mock-up**||
            | :- | :- |
            |Web|Móvil|
            |<https://www.figma.com/proto/aFkdd9BboBQAtj7VyPdAfA/SkillGrade-Landing-Page?type=design&node-id=3-868&t=hRTKTOQoRFsR1p1x-1&scaling=min-zoom&page-id=0%3A1&mode=design>|<https://www.figma.com/proto/aFkdd9BboBQAtj7VyPdAfA/SkillGrade-Landing-Page?type=design&node-id=39-1610&t=awHZBru57UstRleD-1&scaling=min-zoom&page-id=0%3A1&mode=design>|

            <br>

            ![](https://imgur.com/VbAzOMa.png)

    4. ## 4.4 Web Application UX/UI Design

        1. ### 4.4.1 Web Application Wireframes
            **Link Figma Web Application Wireframes**
            <https://www.figma.com/file/UdRCvE9pI4GtamivoTeiGx/Web-Application---Wireframe?type=design&node-id=0%3A1&mode=design&t=WvIfI5K1Dg2uQu4L-1>

            <br>

            **Registro de cuentas:**

            ![](https://i.imgur.com/7Rzbmdp.png)

            **Iniciar sesion:**

            ![](https://i.imgur.com/tCmd8ie.png)

            **Solicitar cambio de contraseña:**

            ![](https://i.imgur.com/A5h4U3F.png)

            **Cambio de contraseña:**

            ![](https://i.imgur.com/DJYu2vV.png)

            **Aplicación para padres de familia:**

            ![](https://i.imgur.com/q7blh8v.png)

            ![](https://i.imgur.com/M1JMnJW.png)

            ![](https://i.imgur.com/mUJvAu5.png)

            ![](https://i.imgur.com/w2w6q6z.png)

            **Aplicación para profesores:**

            ![](https://i.imgur.com/Bh6peum.png)

            ![](https://i.imgur.com/D1s15O9.png)

            ![](https://i.imgur.com/F9S25I3.png)

        2. ### 4.4.2 Web Application Wireflow Diagrams

             **User goal: Usuario se registra, recupera contraseña o inicia sesión a la aplicación con credenciales**

            ![](https://i.imgur.com/Qd2oZ8J.png)

            Descripción:
Cuando el usuario abre la aplicación, se encuentra en la página de inicio de sesión, donde tiene tres alternativas: iniciar sesión con sus datos correctos, registrarse haciendo clic en la sección de registros, o recuperar su contraseña para recibir un enlace de restablecimiento. Una vez que el usuario inicia sesión con las credenciales correctas, accederá a su panel correspondiente, dependiendo de si es un reclutador o un candidato.

             **User goal: Usuario desea ver las notas de sus hijos en una determinada asignatura o competencia.**

            ![](https://i.imgur.com/YyPyyOA.png)

            Descripción:
Cuando el usuario abre la aplicación, se encuentra con una o más opciones dependiendo de cuantos hijos tenga matriculados en escuelas afiliadas. Al escoger uno de sus hijos el usuario puede ver las notas por cursos o ver que tal va el nivel de su hijo en cada competencia.

             **User goal: Usuario desea editar o añadir nuevas calificaciones a un alumno**

            **User goal: Usuario desea editar o añadir nuevos comentarios sobre las actividades de un alumno.**

            **User goal: Usuario desea editar o añadir nuevas puntuaciones de nivel según la competencia de cada alumno.**

            ![](https://i.imgur.com/5FWVcoG.png)

            Descripción:
Cuando el usuario abre la aplicación, se encuentra con uno o más salones en los que es docente. El usuario hace clic en “join” para ingresar a un aula. Al ingresar al aula el usuario se encontrará con la lista de todos los alumnos que están en esa sección. El usuario puede editar o agregar, comentarios, actividades, notas y niveles de competencias.




        3. ### 4.4.3 Web Application Mock-ups

    5. ## 4.5 Web Application Prototyping

    6. ## 4.6 Domain-Driven Software Architecture

        1. ### 4.6.1 Software Architecture Context Diagram

        2. ### 4.6.2 Software Architecture Container Diagrams

        3. ### 4.6.3 Software Architecture Components Diagrams
    
    7. ## 4.7 Software Object-Oriented Design

        1. ### 4.7.1 Class Diagrams

        2. ### 4.7.2 Class Dictionary

    8. ## 4.8 Database Design 

        1. ### 4.8.1 Database Diagram

            
