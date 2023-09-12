### Proyecto Data Analytics Sobre Siniestros Viales

![](https://www.autopista.es/uploads/s1/56/95/38/2/article-se-debe-llamar-a-los-accidentes-de-trafico-siniestro-vial-101778-542913d2a7f82.jpeg)

En el siguiente proyecto, el objetivo principal es realizar un análisis basado en datos públicos obtenidos del Observatorio de Movilidad y Seguridad Vial de la Ciudad de Buenos Aires (OMSV). Estos datos contienen información sobre homicidios en siniestros viales que ocurrieron en la Ciudad de Buenos Aires durante el período 2016-2021.

Para llevar a cabo este proyecto, se utilizaron las siguientes tecnologías y herramientas:

**Lenguaje de Programación:** Python
**Editor de Código:** Visual Studio Code
**Librerías Python:**
+ Pandas
+ Numpy
+ Seaborn
+ Matplotlib

**Dashboard:**

**Herramienta:** Power BI

**Habilidades Aplicadas:**
+ Creación de diversos gráficos interactivos para el análisis de datos históricos.
+ Programación en lenguaje DAX para la creación de medidas que se emplearán en tarjetas de indicadores clave de rendimiento (KPIs).
+ Diseño interactivo del tablero, siguiendo un patrón Z, que hace un uso efectivo de colores, formas y tamaños.

El desarrollo del proyecto seguirá los siguientes pasos:

***1. Descripción del Problema*:** En esta sección, proporcionaremos una descripción detallada del problema que estamos abordando.

***2. Contexto y Entregables:*** Aquí, se presentará el contexto general en el que se encuentra el problema, y tabién incluiremos los entregables de este proyecto.

***3. EDA (Exploratory Data Analysis):*** Realizaremos un análisis exploratorio de datos para comprender mejor los patrones y tendencias relacionados con los homicidios en siniestros viales.

***4. Dashboard:*** Crearemos un panel de control interactivo que permitirá visualizar los resultados de nuestro análisis de manera más accesible.

***5. Conclusiones:*** Finalmente, resumiremos las conclusiones clave que hemos obtenido a partir de nuestro análisis de datos.

## 1. Descripción del Problema

La Organización Mundial de la Salud (OMS) define como siniestro vial a cualquier incidente de tráfico que involucre al menos un vehículo en movimiento y que tenga lugar en una vía pública o en una vía privada de acceso público, y que tenga como resultado al menos una persona herida o fallecida.

Estos siniestros viales son de gran importancia tanto para las autoridades como para el público en general, ya que pueden tener consecuencias graves, incluida la pérdida de vidas humanas. Por lo tanto, es fundamental abordar este problema y trabajar en su prevención de manera efectiva. Para lograrlo, es esencial contar con estrategias respaldadas por datos sólidos que permitan a las autoridades tomar medidas precisas y efectivas para reducir al máximo la ocurrencia de estos incidentes.

## 2. Contexto y Entregables

En Argentina, los accidentes de tránsito continúan siendo una grave preocupación, cobrando la vida de aproximadamente 4,000 personas cada año. A pesar de que varias provincias han logrado reducir la cantidad de siniestros viales, esta problemática aún persiste como la principal causa de muertes violentas en el país.

En este proyecto, nos enfocaremos en analizar los datos específicos de la Ciudad Autónoma de Buenos Aires. Nuestro objetivo es proporcionar insights y conclusiones basados en estos datos, y además, desarrollar un dashboard interactivo que pueda ser de utilidad para las autoridades locales. Este panel permitirá un seguimiento más efectivo de los incidentes y facilitará la aplicación de estrategias enfocadas en métricas precisas, con el propósito de reducir de manera significativa estos eventos.

## 3. EDA (Exploratory Data Analysis)

En esta sección, llevaremos a cabo un análisis exploratorio de datos con el objetivo de comprender mejor la información disponible sobre los homicidios en siniestros viales en la Ciudad de Buenos Aires durante el período 2016-2021. Nuestro análisis constará de los siguientes pasos los cuales se detallan en el archivo .ipynb que se encuentra en aquí:

1. Detección de Valores Faltantes
2. Transformaciones y tratamiento de variables redundantes
3. Tratamiento de Valores Faltantes
4. Estadística Descriptiva
5. Detección y Tratamiento de Valores Atípicos

El análisis realizado se centrará en obtener resultados que nos permitan responder a las siguientes preguntas clave:

¿Dónde ocurrió el evento?
¿Quién fue la víctima?
¿Quién fue el causante del evento?
Para abordar estas interrogantes, examinaremos los siguientes gráficos que nos ayudarán a obtener las respuestas que buscamos.

### ¿Dónde ocurrió el evento?

<span>![</span><span>Aquí la descripción de la imagen por si no carga</span><span>]</span><span>(</span><span>[https://raw.githubusercontent.com/parzibyte/WaterPy/master/assets/ImagenV1.png](https://github.com/ctorres2747/Proyecto-Data-Analytics-Siniestros-Viales/blob/main/Imagenes/Countplot_Cruce.png)</span><span>)</span>


Según el gráfico anterior podemos ver que el 75% de los eventos ocurrieron en un cruce o intersección vial entre avenidas calles o autopistas.
