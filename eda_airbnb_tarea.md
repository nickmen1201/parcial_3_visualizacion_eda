> **Instrucción para el desarrollo de la tarea**
>
> El docente pidió mínimo 5 visualizaciones distintas en el proceso de exploración, y anotaciones de lo que se ve en algunas visualizaciones y en otras no. Lo que se pide es precisamente una exploración: puntos de vista distintos que vayan arrojando información. Evitar guiones largos, emojis, comentarios muy estructurados o comentarios que realmente no reflejen lo que muestra una visualización. Que sea lo más humano posible, pero de buena calidad.

---

# Exploratory Data Analysis Task

**Objetivo:** Realizar una Exploración Visual de Datos utilizando Múltiples Perspectivas y Técnicas de Interacción.

## Descripción de los datos

Airbnb fue lanzada en 2009 por dos amigos que alquilaron su apartamento de San Francisco para una convención local, y ahora es uno de los mayores negocios hoteleros/de alquiler del mundo. En el tercer trimestre de 2022, Airbnb había reservado casi 100 millones de noches y experiencias (Airbnb, 2023). Airbnb utiliza una plataforma basada en comisiones que permite a los anfitriones alquilar una habitación o toda la vivienda de su hogar. El tipo de alquiler puede variar desde una habitación individual en Austin (Texas) hasta un ático entero en Manhattan (Nueva York).

Una de las características de la plataforma son los registros históricos de opiniones de clientes anteriores. Estos registros ayudan a los clientes potenciales a calibrar la popularidad de la propiedad. También ayuda a construir sobre la información de la propiedad que es proporcionada por el inquilino (Aznar et al, 2016). Según una encuesta de Goldman Sachs, la probabilidad de que una persona prefiera un hotel tradicional se reduce a la mitad si se ha alojado en una propiedad de alquiler de espacio compartido en los últimos cinco años (Clever Real Estate, 2021).

Airbnb ha perturbado considerablemente el sector hotelero tradicional. Según un estudio realizado por Clever a 1000 personas en 2019, el 82% afirmó que consideraría alquilar una parte de su casa para obtener ingresos extra (Clever Real Estate, 2021). Según una encuesta realizada por Earnest, de media, los anfitriones de Airbnb ganan más de 500 dólares al mes (6.000 dólares anuales) (Morris, 2021). Como parte del proceso de alquiler, Airbnb cobra una tarifa plana de servicio del 3% a cada anfitrión. Esta tarifa cubre servicios de Airbnb como atención al cliente, marketing y seguros (Airbnb, 2020).

A continuación se ofrece una definición de los tipos de datos.

| Nombre del Campo | Tipo de Campo | Descripción | Ejemplo |
|---|---|---|---|
| ID | Número | Identificador único del alquiler | 5136 |
| Name | Cadena | Nombre del alquiler | Castillo Feliz |
| HostId | Número | Identificador único de Airbnb | 5162530 |
| Host Name | Cadena | Nombre del anfitrión | Steve |
| Host Since | Fecha | La fecha en que el alquiler fue creado | 6/26/08 |
| Neighborhood | Cadena | Barrio donde queda el alquiler | Williamsburg |
| Neighborhood Group | Cadena | Distrito dentro de la ciudad de New York | Brooklyn |
| Latitude & Longitude | Número | Utiliza la proyección del Sistema Geodésico Mundial (WGS84) para la latitud y la longitud. | 40.764570,-73.955120 |
| Room Type | Cadena | Descripción del tipo de alquiler | Private room |
| Accommodates | Número | Máxima capacidad de personas | 4 |
| Bathrooms | Cadena | Número de baños | 1 bath |
| Bedrooms | Número | Número de dormitorios | 3 |
| Price | Número | Precio por día en dólares | 145 |
| Beds | Número | Cantidad de camas | 1 |
| Number of Reviews | Número | Número de comentarios. Hay un comentario por día alquilado. Por lo tanto este campo es el total de días alquilados entre Host Since y Last Review. | 171 |
| Last Review | Fecha | Fecha del último comentario, último día alquilado. | 11/21/2022 |

## Exploración de los datos

Tu trabajo consiste en analizar un conjunto de datos de alquileres de Airbnb de la ciudad de Nueva York. Utiliza el libro de Tableau `/data/Exploring Airbnb Rental Properties Starter.twbx` para que inicies la exploración.

Explora los datos construyendo visualizaciones de las diferentes relaciones cuantitativas que puedan existir. El proceso de explorar y analizar datos requiere un grado extremo de flexibilidad y fluidez de interacción: adiciona o elimina variables, selecciona, filtra u ordena la data no de maneras predefinidas, cambia de posición los gráficos en la pantalla, elimina y crea gráficos nuevos y diferentes, coloca los gráficos en vistas de múltiples perspectivas y aplica las técnicas de interacción aprendidas en clase para facilitar la comprensión de la interrelación de gráficos unos con otros.

## Evaluación

Haz una lista de al menos 7 cosas que aprendiste con esta data sobre los alquileres de Airbnb. Presenta en clase las visualizaciones que te ayudaron a responder esas preguntas. Utiliza múltiples perspectivas y técnicas de interacción si crees que te son útiles en la explicación.
