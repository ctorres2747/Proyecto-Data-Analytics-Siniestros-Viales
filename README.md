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

![Image text](https://github.com/ctorres2747/Proyecto-Data-Analytics-Siniestros-Viales/blob/main/Imagenes/Countplot_Cruce.png)

Según el gráfico anterior podemos ver que el 75% de los eventos ocurrieron en un cruce o intersección vial entre avenidas, calles o autopistas.

![Image text](https://github.com/ctorres2747/Proyecto-Data-Analytics-Siniestros-Viales/blob/main/Imagenes/Countplot_TIPO_DE_CALLE.png)

Adicionalmente, el 61% de los eventos ocurrieron sobre una Avenida

### ¿Quien fue la Victima?

![Image text](https://github.com/ctorres2747/Proyecto-Data-Analytics-Siniestros-Viales/blob/main/Imagenes/Countplot_Victima.png)

El 79% de las victimas fueron actores viales en moto y peatones en primer y segundo lugar respectivamente

![Image text](https://github.com/ctorres2747/Proyecto-Data-Analytics-Siniestros-Viales/blob/main/Imagenes/Countplot_sexo_victima.png)

El 76% de las victimas fueron de género masculino.

![Image text](https://github.com/ctorres2747/Proyecto-Data-Analytics-Siniestros-Viales/blob/main/Imagenes/Histograma.jpg)

En la gráfica anterior vemos una concentración de las edades de las victimas donde el 50 % de las edades se encuentran entre 28 y 55 años de edad

### ¿Quien fue el Acusado?

![Image text](https://github.com/ctorres2747/Proyecto-Data-Analytics-Siniestros-Viales/blob/main/Imagenes/Countplot_Acusado.png)

En el gráfico anterior, podemos ver que los principales acusados fueron actores viales en Auto y vehículos de pasajeros con un 52% de eventos causados.

### Conclusiones EDA

Basándonos en los datos proporcionados por las gráficas y el análisis realizado, podemos llegar a las siguientes conclusiones:

***Ubicación de los Eventos:*** La mayoría de los eventos de siniestros viales ocurrieron en cruces o intersecciones viales, lo que sugiere que estas áreas pueden ser críticas en términos de seguridad vial. Además, un porcentaje significativo de eventos ocurrió en avenidas, lo que podría indicar la importancia de abordar la seguridad en estas vías específicas.

***Perfiles de las Víctimas:*** Las principales víctimas de siniestros viales fueron motoristas y peatones, con una notable predominancia de género masculino. La concentración de edades entre 28 y 55 años indica que este grupo demográfico está particularmente en riesgo.

***Perfiles de los Acusados:*** Los actores viales en automóviles y vehículos de pasajeros fueron los principales acusados en la ocurrencia de estos eventos. Esto sugiere la necesidad de medidas específicas para mejorar la conducta y la seguridad de los conductores de estos vehículos.

En resumen, estos hallazgos destacan la importancia de enfocar los esfuerzos de seguridad vial en áreas de cruce e intersecciones viales, así como en avenidas. Además, se debe prestar una atención especial a los motociclistas y peatones, y se debe concienciar a los conductores de automóviles y vehículos de pasajeros sobre la responsabilidad y el cumplimiento de las normas de tránsito. 

## 4. Dashboard

![Image text](https://github.com/ctorres2747/Proyecto-Data-Analytics-Siniestros-Viales/blob/main/Imagenes/Dashboard.png)

En el diseño del dashboard se tuvieron en cuenta los principios de visualización de datos para captar el interés en la información y, al mismo tiempo, transmitir la información adecuada para llegar a conclusiones. Asimismo, se seleccionaron los gráficos apropiados para representar la información de manera precisa, lo que facilita la obtención de conclusiones de manera más sencilla. Las herramientas utilizadas para la creación del dashboard fueron las siguientes:

1. Tarjetas de categorías con filtros para variables numéricas.
2. Tarjetas de KPI para mostrar gráficamente el cumplimiento de los indicadores propuestos, utilizando código DAX para su formulación y cálculo.
3. Gráfico de barras horizontales apiladas para representar dos variables categóricas junto con una variable numérica, permitiendo además filtrar por los cinco mejores resultados.
4. Gráfico de líneas para mostrar la tendencia de una variable numérica en el tiempo.
5. Filtros de tiempo que permiten seleccionar un rango de fechas para realizar las visualizaciones.
6. Gráfico Treemap para representar la dimensión de una variable categórica, contando variables numéricas relacionadas.
7. Un mapa de coordenadas geográficas para representar la ubicación de los eventos y contabilizar las víctimas que se presentan en áreas específicas.

En el dashboard se abordan 3 KPI(s) que representan objetivos clave orientados a reducir las víctimas mortales en eventos viales, los cuales se describen a continuación:

**Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior**. Definimos la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000.

**Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año en CABA, en comparación con el año anterior.** Definimos la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un período de tiempo determinado. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100.

**Reducir en un 10% la cantidad total de eventos que ocurrieron en cruces viales en el último año en CABA, en comparación con el año anterior.** Definimos la cantidad total de eventos como el número absoluto total de eventos registrados que ocurrieron en cruces viales. Su fórmula es: (Número de eventos ocurridos en cruces viales del año anterior - Número de eventos ocurridos en cruces viales del año actual) / (Número de eventos ocurridos en cruces viales del año anterior) * 100.

Es importante mencionar que el diseño del tablero se realizó pensando en responder las preguntas clave analizadas en el EDA anteriormente (¿Dónde ocurrió el evento? ¿Quién fue la víctima? ¿Quién fue el causante del evento?) y se agregaron otros datos y métricas importantes para completar la información.

## 5. Conclusiones

Basandonos en los análisis realizados en este estudio, podemos llegar a las siguientes concusiones:

1. Los cruces viales con avenidas son los puntos mas críticos donde ocurren los eventos fatales cuyas victimas son principalmente motorizados y peatones siendo causados principalmente por automóviles y vehículos de pasajeros.
2. El grupo demográfico de personas que tienen edades entre los 28 y 55 años son los principales victimas de homicidios en CABA. Dicho grupo demográfico, es más propenso a estar activo en la comunidad, lo que las hace más vulnerables a los eventos viales.
3. Los indicadores, KPI(s) métricas y gráficos que genera el dashboard da información precisa del comportamiento de los eventos a lo largo del tiempo y muestra la situación actual en el cumplimiento de los objetivos plateados por la organización. Esta información puede utilizarse para identificar áreas donde se necesitan mejoras y tomar medidas para corregirlas.
