# DIU23
Prácticas Diseño Interfaces de Usuario 2022-23 (Tema: Turirmos ) 

Grupo: DIU1_0Ahora-o-nunca.  Curso: 2022/23 
Updated: 02/05/2023

Proyecto: **NazaLine**

**NazaLine** representa la línea de las artesanías nazaríes, un camino que queremos recorrer junto a una comunidad entusiasta que quiere compartir y mantener las Artesanías Nazaríes. 

Descripción: 

Queremos fomentar el sentimiento de comunidad por ello proponemos expandir ese concepto y solventar además un problema. Los usuarios normalmente quieren información acerca de los talleres, si les va a gustar, saber experiencias de otros usuarios etc. Queremos dar la posibilidad a los usuarios de expresar sus vivencias en los talleres, crearemos un entorno donde los usuarios puedan postear sus obras y opinar sobre los talleres y las artesanías que hagan. Además de crear grupos abiertos de talleres donde los usuarios de la comunidad puedan participar, conocerse y también abaratar el coste de los talleres.

Logotipo: 
<p align="center">
    <img src="./P3/img/logo.svg#center">
</p>


Miembros
 * :bust_in_silhouette:   [Manuel Hidalgo Carmona](https://github.com/venrra)     :octocat:     
 * :bust_in_silhouette:  [Maria Forencio](https://github.com/mariafd412)     :octocat:

----- 


# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

El tema del analisis se centra en proyectos enfocados al __Turismo__. Hemos elegido Teller de arteseania al pertenecer al grupo 3. Se va a acomparar con las otras ofertas turisticas Free Tour y Tablao

![Método UX](P1/img/Competitor_Analysis.jpg)

![Método UX](img/Persona.png) 1.b Persona
-----

Hemos elegido dos personas jovenes que encajan con nuestro entorno estudiantil mas carcano. Estas dos personas son fisticias inspiradas en personas reales, Sara y Marta.

![Método UX](P1/img/Persona1.png)

![Método UX](P1/img/Persona2_Sara.png)

![Método UX](img/JourneyMap.png) 1.c User Journey Map
----

Hemos modelado una situción distinta para cada usuario que consideramos posibles y reales para un publico mas joven.

![Método UX](P1/img/User_journey1.png)

![Método UX](P1/img/User_journey2.png)

![Método UX](img/usabilityReview.png) 1.d Usability Review
----
- [Enlace al documento](./P1/Usability-review.xlsx)
- Valoración final: __38 Poor__

### BRIEFING

__Problemas de diseño y navegación. Confusión sobre el propósito de la web. Necesita mejoras en el proceso de compra.__

## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid / POV
----

Obtenemos los objetivos e ideas que queremos desarrollar a través de la malla receptora de ideas.

Utilizamos esta herramienta 


### - Malla receptora de información

![ScopeCanvas](./P2/sgv/MallaReceptora.svg)

### - Punto de vista

Como complemento y para obtener mas información hacemos uso de los usuarios para ver su punto de vista y que necesitan.

![ScopeCanvas](./P2/sgv/PointOfView.svg)


![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
----

Utilizamos esta herramienta porque nos ofrece una **visión  general** de los problemas que podemos resolver del sitio y nuevas ideas que podemos desarrollar.
Vemos que uno de los problemas es que no podemos ver las valoraciones de los talleres y con ese problema obtenemos la idea de crear una **TimeLine o comunidad** donde podamos solucionar ese problema. Además fomenta que se comparta el taller y la artesania nazari.

También sacamos algunos defecto de diseños que mejoraremos en las siguientes etapas.

**En conclusión** la propuesta se basa en crear una **comunidad**  un sitio donde los usuarios puedan **postear** sus obras y **valorar** los talleres y las obras de los demás. Además con esta comunidad se podrá asistir a talleres abiertos para todos.

![ScopeCanvas](./P2/img/Propuesta_de_valor_scope_canvas.png)


![Método UX](img/Sitemap.png) 2.b Tasks analysis 
-----

Análisis de las tareas mas realizadas dentro de los 3 grupos de usuarios que vamos a definir:
- **Contratan talleres**: Usuarios que ya han contratado un taller o tienen la intención de hacerlo y forman parte de la comunidad
- **Curiosos por artesanía**: Usuarios que buscan información por artesanía como estudiantes, profesores, artesanos.
- **Curiosos por el taller**: usuarios que nunca han reservado un taller.

|     **_Usuario\ <br>Tareas_**    	| **Contratan talleres** 	| **Curiosos por artesanía** 	| **Curiosos por el teller** 	|
|:--------------------------------------------	|:----------------------:	|:--------------------------:	|:--------------------------:	|
|              **iniciar sesión**             	|            H           	|              L             	|              L             	|
|    **Busca información <br>de artesanía**   	|            H           	|              H             	|              M             	|
|      **Busca información <br>de taller**     	|            H           	|              M             	|              H             	|
|               **Busca ofertas**              	|            H           	|              L             	|              H             	|
|         **Busca <br>colaboraciones**         	|            M           	|              M             	|              M             	|
|          **Publicar su experiencia**         	|            M           	|              L             	|              L             	|
| **Revisar la experiencia de otros usuarios** 	|            H           	|              L             	|              H             	|
|              **Reservar taller**             	|            H           	|              L             	|              H             	|
|              **Cancelar Taller**             	|            M           	|             NA             	|              L             	|
|             **Modificar Taller**             	|            H           	|             NA             	|              L             	|


![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
----

### Site Map

Gracias al análisis de tareas podemos expresar el siguiente site map

![ScopeCanvas](./P2/img/Site_Map.png)

### Labelling

| **_Labeling_**            | **_Descripción_**     |
|------------------------   |-------------------    |
| **Inicio**                | Portada y entrada al sitio. |
| **Sobre nosostros**       | Explicación de taller a nivel profesional y explicación de organización empresarial. |
| **Maestros Artesanos**    | Explicación sobre métodos, herramientas y maestros artesanos dentro del taller y dentro de la organización. |
| **Colaboraciones**        | Exposición de colaboraciones y trabajos hechos desde el taller. Los trabajos realizados a otras empresas e identidades. |
| **Contacto**              | Formularios y datos de contacto. |
| **Nuestro trabajo**       | Los trabajos realizados dentro de la organización.  |
| **Materiales**            | Mas información acerca de los materiales. |
| **Galería**               | Todos los complementos de videos y fotos. |
| **Artesanías**            | Mas información acerca de las artesanías. |
| **Talleres**              | Explicación sobre los talleres. |
| **Ofertas**               | Dentro de los talleres que ofertas se ofrecen. |
| **Reservar taller**       | Punto de reserva y gestión de los talleres. |
| **Comunidad**             | Portal donde se pueden ver todas las publicaciones y comentarios de los usuarios. |
| **Tienda**                | Enlace de la aplicación de artesanías nazaríes. |
| **Iniciar sesión**        | inicio de sesión y gestión de usuarios. |



![Método UX](img/Wireframes.png) 2.d Wireframes
-----

Hemos creado 4 vistas de la página de inicio y comunidad en web y móvil.

- **Inicio**: hemos creado una barra de navegación sencilla compuesta por los puntos destacados en el site map. Para representar la llamada a la acción hemos apartado el acceso al login y a reserva de talleres en dos botones resaltando su importancia. También tenemos un carrusel con información relevante de los distintos sitios de la web que recogemos todos los videos y documentos que antes estaban dispersos.

- **Comunidad**: en la vista de comunidad vemos todos los pos que se han hecho por parte de los usuarios. Cada post tiene una parte de imágenes, otra de descripción. En la parte inferior del post vemos comentarios y valoraciones y acciones (compartir, comentar) por parte de otros usuarios


- Inicio

![inicio](./P2/sgv/Prototipo_LoFi/Inicio.svg)

- Comunidad

![comunidad](./P2/sgv/Prototipo_LoFi/Comunidad.svg)

- Inicio (smartphone)

<p align="center">
    <img src="./P2/sgv/Prototipo_LoFi/movili-inicio.svg">
</p>

- comunidad (smartphone)

<p align="center">
    <img src="./P2/sgv/Prototipo_LoFi/movil-comunidad.svg">
</p>



## Paso 3. Mi UX-Case Study (diseño)


![Método UX](img/moodboard.png) 3.a Moodboard
-----

### __LOGO__

<p align="center">
    <img src="./P3/img/logo.svg#center">
</p>

### __MoodBoard__

<p align="center">
    <img src="./P3/img/moodboard.png#center">
</p>


![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Landing Page](./P3/img/Landing.png)

![Método UX](img/guidelines.png) 3.c Guidelines
----

Patrón de diseño de la rejilla: La web se ha estructurado utilizando un patrón de rejilla para lograr una disposición organizada y equilibrada de los elementos. Esta elección representa la atención meticulosa y el cuidado que los artesanos ponen en cada una de sus creaciones. Al igual que una rejilla proporciona una estructura estable para construir sobre ella, la rejilla en la web brinda una sensación de orden y armonía.

Patrón de diseño de tarjetas: Las tarjetas se han utilizado para presentar las diferentes creaciones y productos artesanales en la web. Estas tarjetas permiten una presentación visual clara y concisa de cada artículo, mostrando una imagen representativa y una breve descripción. Además, las tarjetas facilitan la navegación y la comparación de productos, brindando a los usuarios una experiencia intuitiva y cómoda al explorar las opciones disponibles.

Patrón de diseño de scroll parallax: Al desplazarse por la página, se ha implementado un efecto de scroll parallax en ciertos elementos, como imágenes de fondo o secciones destacadas. Este efecto agrega una sensación de profundidad y dinamismo a la página, creando una experiencia visualmente atractiva y envolvente. Además, el scroll parallax resalta la atención al detalle y la artesanía meticulosa que se refleja en cada obra.

Estos patrones de diseño han sido seleccionados para realzar la experiencia del usuario y transmitir los valores de artesanía, claridad y pureza presentes en la web https://artesanianazari.es/. Cada patrón ha sido adaptado estratégicamente para lograr una presentación visual armoniosa y una navegación intuitiva, lo que mejora la interacción de los usuarios y la apreciación de las creaciones artesanales.

![Método UX](img/mockup.png)  3.d Mockup
----

![Landing Page](./P3/img/Wireframe.png)

### Vista Inicio iPhone
<p align="center">
    <img src="./P3/img/iPhone14-1.png#center">
</p>

### Vista Cominuidad iPhone
<p align="center">
    <img src="./P3/img/iPhone14-2.png#center">
</p>


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----

El rediseño del sitio web https://artesanianazari.es/ se ha centrado en transmitir los conceptos de artesanía, claridad y pureza. Para lograr esto, se han implementado varios elementos y decisiones de diseño.

En cuanto a la paleta de colores, se ha elegido una combinación de gris, terracota y beige. Estos colores se seleccionaron por su neutralidad y pureza. El beige y el terracota hacen referencia a la cerámica y al barro, elementos tradicionales de la artesanía. El gris oscuro, casi negro, se ha utilizado para representar la elegancia del negro, pero de una manera más suavizada.

Los iconos utilizados en el sitio web provienen de la librería de material. Estos iconos son lineales y sencillos, lo que los hace coherentes con el resto de los elementos de diseño. Esta elección contribuye a la claridad y la simplicidad visual del sitio.

Una característica destacada del rediseño es la inclusión de un timeline para crear comunidad. Este timeline permite a los alumnos y usuarios del sitio web publicar sus creaciones y dar feedback a otros compañeros. Esta funcionalidad fomenta la interacción y la participación de la comunidad, fortaleciendo así la conexión entre los usuarios y la artesanía.

## Paso 4. Evaluación 

![Método UX](./img/ABtesting.png) 4.a Caso asignado
----

Projecto asignado: [DIU2.Dumblendor](https://github.com/VictorPB/DIU)

Es una un espacio donde los propios usuarios pueden crear y añadir rutas para que otros usuarios las hagan. Además cada ruta puede tener variantes. Estas variantes tienen una estructura similar a la ruta original pero con alguna otra parada. Se pueden buscar rutas a través de la ubicación o a través del inicio y el fin.

<p align="center">
    <img src="./P4/img/logo.jpg">
</p>

<p align="center">
    <img src="./P4/img/LandingPage.png">
</p>


Antes que nada destacar que es un proyecto completo y que cumple con todos los objetivos propuestos.

Destacamos los siguientes puntos negativos que pueden implicar problemas de usabilidad:

La cantidad de elementos y texto hacen complicado centrar la acción. resulta confuso tanta información en un mismo espacio.
- La elección de colores no nos ha resultado del todo amigable.
- Hay algunas incongruencias en el estilo en algunos elementos. Hay varios elementos como cajas que no mantienen un mismo estilo.
- A título personal la fuente no nos parece la más adecuada para un diseño moderno.
Por otro parte puntos fuertes a destacar:
- Un buen diseño de logo.
- Cumple con todos los requisitos de navegación. En todo momento se entiende dónde estás y a dónde vas.
- La propuesta resulta muy interesante.


![Método UX](./img/usability-testing.png) 4.b User Testing
----

### 1 Usuario: Martín López -  
Sexo/Edad: Masculino, 35 años
Ocupación: Oficinista con movilidad reducida
Experiencia en Internet: Promedio
Plataforma: Aplicación móvil
Perfil cubierto: Prototipo A (2 valoraciones)
- Martín, debido a su movilidad reducida, necesita una aplicación que sea accesible y fácil de usar.
- Le gustaría poder planificar y organizar encuentros con amigos de manera sencilla, considerando sus limitaciones de movilidad.
- Martín se siente asqueado por las aplicaciones que no tienen en cuenta las necesidades de las personas con discapacidades físicas. Espera que el prototipo A sea inclusivo y tenga características diseñadas pensando en usuarios como él.


### 2 Usuario: Clara Rodríguez - 
Sexo/Edad: Femenino, 28 años
Ocupación: Estudiante y hippie del Albaicín
Experiencia en Internet: Alta
Plataforma: Aplicación móvil
Perfil cubierto: Prototipo B (2 usuarios)
Necesidades con respecto al prototipo B:
- Clara es una apasionada del senderismo y necesita una aplicación que le proporcione rutas y guías para sus excursiones.
- Como hippie, valora mucho la sostenibilidad y la protección del medio ambiente. Espera que el prototipo B promueva actividades al aire libre de manera responsable y respetuosa con la naturaleza.
- Clara se encuentra enfadada con las aplicaciones que no se comprometen con la preservación del entorno y espera que el prototipo B sea consciente de esta preocupación.

### 3 Usuario: Laura Gómez -
Sexo/Edad: Femenino, 45 años
Ocupación: Empresaria en el ámbito de la fotografía
Experiencia en Internet: Alta
Plataforma: Aplicación web
Perfil cubierto: Prototipo A (2 valoraciones)
Necesidades con respecto al prototipo A:
- Laura tiene un trabajo muy demandante y necesita una aplicación que le permita organizar reuniones y eventos de manera eficiente.
- Como empresaria, tiene miedo de no poder cumplir con todas sus responsabilidades y necesita una herramienta que le ayude a gestionar su agenda y tareas de manera efectiva.
- Laura espera que el prototipo A sea intuitivo y le brinde la tranquilidad de que no se le escapará ningún detalle importante en su vida profesional y personal.

### 4 Usuario: Carlos Fernández -
Sexo/Edad: Masculino, 40 años
Ocupación: Monitor de pilates
Experiencia en Internet: Media
Plataforma: Aplicación web
Perfil cubierto: Prototipo B (2 usuarios)
Necesidades con respecto al prototipo B:
- Carlos es monitor de pilates y le gustaría tener una aplicación que le permita compartir rutinas y ejercicios con sus alumnos.
- Como alguien que disfruta salir y estar activo, busca una aplicación que ofrezca recomendaciones sobre lugares y eventos relacionados con el fitness y el bienestar.
- Carlos se sentiría sorprendido y entusiasmado si el prototipo B le ofrece nuevas ideas y recursos para enriquecer sus clases de pilates y brinda opciones interesantes para su vida social activa.

 

| Usuarios | Sexo/Edad     | Ocupación       | Experiencia internet | Plataforma | TestA/B
| ------------- | -------- | -----------     | -----------  | ---------- | ----
| Martín López  | H/35   | Estudiante        | Promedio    | movil         | A 
| Clara Díaz  | M/28   | Estudiante          | Alta       | Web           | B 
| Laura Gómez  | M/45   | Abogado                     | Alta       |web            | A 
| Carlos Pérez  | H/40   | Monitor de pilates       | Media/ baja  |movil  | B 


![Método UX](./img/Survey.png). 4.c Cuestionario SUS
----

Test Clara

<p align="center">
    <img src="./P4/img/TestClara.png">
</p>

Test Carlos

<p align="center">
    <img src="./P4/img/TestCarlos.png">
</p>

Excel

<p align="center">
    <img src="./P4/img/TodosTest.png">
</p>


![Método UX](./img/usability-report.png) 4.d Usability Report
----

En el siguiente enlace encontramos el [Reporte de usabilidad B](./P4/P4_UsabReport_B_doneby_DIU2_Dumblendor.pdf) para Dumblendor.

En el siguiente enlace encontramos el [UXCaseStudy-review](./P4/UXCasescores.pdf) __SCORE 81__

En resumen, el diseño web actualmente presenta un cumplimiento satisfactorio de sus promesas, pero aún existen áreas que requieren atención para lograr una experiencia aún mejor. Es recomendable enfocarse en mejorar la distribución de la información, ya que esto permitiría una presentación más clara y accesible para los usuarios. Además, sería beneficioso explorar la posibilidad de utilizar una paleta de colores más ligera y armoniosa, lo cual podría generar una sensación visual más agradable y coherente en el sitio. Al trabajar en la coherencia de los componentes visuales, se podría lograr una apariencia más cohesionada y profesional en general. Sin embargo, a pesar de estas áreas de mejora, la propuesta en sí resulta interesante y evidencia un potencial considerable para ofrecer una experiencia web atractiva y efectiva.

## Paso 5. Evaluación mediante Eye Tracking

![Método UX](img/eye-tracking.png)  5.a Eye Tracking method 

Para realizar el experimento, utilizamos la herramienta [Gaze Recorder](https://gazerecorder.com/). Generamos imágenes del diseño a partir de los archivos de Figma del equipo Dumblendor, que inicialmente no estaban disponibles. El uso de una cuenta estándar dificultó la utilización de la herramienta.

En cuanto a la selección de los usuarios participantes, contamos con la participación tanto de nosotros mismos, como usuarios expertos, como de nuestros compañeros de piso y amigos, quienes siguieron detalladamente las instrucciones que les proporcionamos.

Al diseñar el experimento, nos centramos en las características del diseño web y en la intención del equipo Dumblendor.

5.a) Diseño del experimento 
----

Para llevar a cabo el experimento, seguimos las siguientes pautas:

- Al comenzar el experimento, se explicó a cada usuario cuál sería su motivación al acceder al sitio, en este caso, buscar y planificar una actividad turística de senderismo.

- Se solicitó a cada usuario que identificara los servicios ofrecidos por el sitio web.

- Se pidió a los usuarios que localizaran y reconocieran elementos específicos, como la función de búsqueda de rutas.

- Se solicitó a los usuarios que identificaran la estructura de la información presentada en el sitio.

- Se les pidió a los usuarios que intentaran determinar su ubicación (en el sitio web) en cada momento durante la navegación del sitio web.

- Se les explicó cómo funcionaba la aplicación Gaze Recorder y se inició el experimento con la calibración inicial.

La intención era permitir que cada usuario navegara libremente con un par de objetivos y observar cómo se desenvolvían al recorrer cada vista con la mirada.

Suponíamos que el entorno de experimentación estaba operativo y que las imágenes estaban cargadas en el mismo orden para todos los usuarios.

5.b) Resultados y valoración 

Debido al agotamiento de cretidos de la aplicación no hemos podido realizar tantos experimentos con usuarios como queriamos. Hemos sufrigo agotamiento de creditos y no nos dejaba crear mas pruebas.

__Inicio__

<p align="center">
    <img src="./P5/zonasInteres/inicio.jpg">
</p>


__Cuenta__

<p align="center">
    <img src="./P5/zonasInteres/cuenta.jpg">
</p>

En el caso de la pantalla de la cuenta personal, se logró un resultado satisfactorio en cuanto a las áreas de interés. Sin embargo, se podrían realizar mejoras en el diseño del menú del perfil para resaltar las opciones disponibles y otorgarles la relevancia necesaria. Se sugiere utilizar colores distintos y una disposición que permita destacar las opciones de manera efectiva. 


__Buscador personalizado__

<p align="center">
    <img src="./P5/zonasInteres/buscadorP.jpg">
</p>

La información no está correctamente estructurada. Pese a que se está dando información detallada de una ruta completa en la parte superior, el usuario ha pasado la mayor parte del tiempo observando el cuadro marrón, que a priori, contiene información complementaria o secundaria.


## Conclusión final / Valoración de las prácticas

En base a nuestro análisis del diseño web, podemos concluir que este presenta deficiencias en la dirección de la atención del usuario. En lugar de guiar de manera efectiva la mirada del usuario, el diseño se convierte en un conjunto abrumador de información que puede resultar confuso y dificultar la comprensión.

Además, la falta de una jerarquía visual clara puede generar una sensación de desorden y dificultar la identificación de la información más relevante. Esto puede llevar a una experiencia negativa para el usuario, quien puede sentirse abrumado por la cantidad de elementos presentes en la interfaz.

El enfoque principal se encuentra en las imágenes, las cuales captan principalmente la atención del usuario. Por lo tanto, es recomendable utilizar las imágenes de manera eficiente para respaldar y complementar el diseño de manera efectiva.

Por lo tanto, es recomendable revisar y optimizar el diseño para mejorar la usabilidad y facilitar la comprensión de la información por parte de los usuarios. Esto implica considerar la implementación de una estructura visual coherente y una jerarquía clara que guíe la atención del usuario de manera intuitiva y efectiva.