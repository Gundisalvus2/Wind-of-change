# Wind-of-change


### Problema
Hoy en día, debido a diversos factores tales como el sedentarismo, los malos hábitos alimenticios o las redes sociales, una gran parte de la población desarrollan problemas de salud relacionados con la ingesta de comida. En 2020, alrededor del 40% de la población mundial sufría sobrepeso, y un 13% eran obesos. Entre el 5 y el 10% de la población con edades comprendidas entre los 12 y los 25 años sufren algún tipo de TCA tales como bulimia o la anorexia.

Ya sea por desgana, desconocimiento o por imposibilidad, la mayoría de la gente no lleva una alimentación saludable. Por ello, se pretende crear una aplicación en la nube que sea accesible para todo el mundo y que facilite estos hábitos.

### Posibles Usuarios
Toda aquella persona que desee llevar una vida más saludable y que esté interesado en mejorar su alimentación.

### Descripción de la aplicación
Creación de una aplicación desplegada en la nube que genere una dieta en función de una serie de cálculos y parámetros que se explican a continuación:

Inicialmente se pedirá al usuario que introduzca su peso, altura y con qué frecuencia realiza actividad física a la semana. A partir de esta información, la aplicación calculará la Tasa Metabólica Basal (**BMR** en inglés) para ver la cantidad de calorías que debería de consumir el usuario si estuviese 24h en reposo y luego obtendrá, aplicando la fórmula de *Harris-Benedict*, una estimación de las calorías que debe de consumir teniendo en cuenta el BMR y lo que se quema haciendo esa cantidad de ejercicio.

A continuación, se procede a la creación de una dieta saludable. Para ello, el usuario podrá indicar a qué tipo de alimentos es alérgico, cuáles prefiere no comer o cuántas ingestas puede realizar, entre otras opciones y la aplicación tratará de crear una dieta saludable adaptada a las calorías anteriormente calculadas con la fórmula de *Harris-Benedict* y teniendo en cuenta las preferencias. Esto se hará filtrando y buscando alimentos en una base de datos según lo indicado y aplicando algoritmos de maximización o minimización sobre los macronutrientes dependiendo de si sufre enfermedades concretas o no. 

**Todos los datos** de los alimentos se obtendrán de bancos de datos, como por ejemplo el del [Departamento de Agricultura de los EE.UU. ](https://fdc.nal.usda.gov/download-datasets.html)

### Configuración para el objetivo 0
[Documento con imágenes de configuración](Configuraciones/Images.md)
