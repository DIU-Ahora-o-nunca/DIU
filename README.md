# DIU23
Prácticas Diseño Interfaces de Usuario 2022-23 (Tema: Turirmos ) 

Grupo: DIU1_0Ahora-o-nunca.  Curso: 2022/23 
Updated: 02/05/2023

Proyecto: **NazaLine**

**NazaLine** representa la línea de las artesanías nazaríes, un camino que queremos recorrer junto a una comunidad entusiasta que quiere compartir y mantener las Artesanías Nazaríes. 

Descripción: 

Queremos fomentar el sentimiento de comunidad por ello proponemos expandir ese concepto y solventar además un problema. Los usuarios normalmente quieren información acerca de los talleres, si les va a gustar, saber experiencias de otros usuarios etc. Queremos dar la posibilidad a los usuarios de expresar sus vivencias en los talleres, crearemos un entorno donde los usuarios puedan postear sus obras y opinar sobre los talleres y las artesanías que hagan. Además de crear grupos abiertos de talleres donde los usuarios de la comunidad puedan participar, conocerse y también abaratar el coste de los talleres.

Logotipo: 
>>> Opcionalmente si diseña un logotipo para su producto en la práctica 3 pongalo aqui

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


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo
>>> Si diseña un logotipo, explique la herramienta utilizada y la resolución empleada. ¿Puede usar esta imagen como cabecera de Twitter, por ejemplo, o necesita otra?


![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 
>>> Tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----


>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto en forma de video de 90 segundos aprox


## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----


>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione 4 personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Asigne dos a Caso A y 2 al caso B
 

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)



>>> Valoración personal 


>>> ## Paso 5. Evaluación de Accesibilidad  (no necesaria)


>>> ![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report 
>>>> ----

>>> Indica qué pretendes evaluar (de accesibilidad) sobre qué APP y qué resultados has obtenido 

>>> 5.a) Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 
>>> 5.b) Uso de simuladores de accesibilidad 

>>> (uso de tabla de datos, indicar herramientas usadas) 

>>> 5.c Breve resumen del estudio de accesibilidad (de práctica 1) y puntos fuertes y de mejora de los criterios de accesibilidad de tu diseño propuesto en Práctica 4.



## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













