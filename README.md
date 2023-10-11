Proyecto de Análisis de Accidentes de Aereos

Este proyecto se centra en el análisis de datos relacionados con accidentes de aviones. 

Se aborda la limpieza y preparación de datos, seguido de un análisis exploratorio detallado que incluye visualizaciones y hallazgos importantes. 

Se exploran aspectos como la cantidad de personas a bordo, fallecimientos, tipos de aeronaves involucradas y más. Además, se investigan posibles causas de los accidentes basándose en las descripciones proporcionadas.

Contenido

1.	Introducción

2.	Tecnologías y Herramientas Utilizadas

3.	Metodología

4.	Proceso de ETL

5.	Análisis Exploratorio de Datos (EDA)

6.	Análisis de Causas de Accidentes

7.	Resumen por Décadas

Introducción

El objetivo de este proyecto es realizar un análisis completo de datos relacionados con accidentes de aviones. Se comienza por cargar y preparar los datos, seguido de un análisis exhaustivo para extraer información relevante. Además, se exploran posibles causas de los accidentes a través del análisis de descripciones proporcionadas.
Tecnologías y Herramientas Utilizadas

•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
Metodología

El proyecto sigue una metodología estructurada que consta de los siguientes pasos:

1.	ETL (Extracción, Transformación y Carga): Se extraen los datos desde un archivo CSV, se realizan transformaciones para limpiar y preparar los datos, y luego se carga en un DataFrame para su análisis.

2.	Análisis Exploratorio de Datos (EDA): Se exploran los datos, se identifican patrones, se visualizan distribuciones y se obtienen estadísticas descriptivas para comprender mejor la naturaleza de los accidentes.

3.	Análisis de Causas de Accidentes: Se analizan las descripciones de los accidentes en busca de posibles palabras clave que puedan indicar causas subyacentes.

4.	Resumen por Décadas: Se agrupan los datos por décadas para proporcionar un resumen cuantitativo de los accidentes en cada período.
Proceso de ETL.

El proceso ETL (Extracción, Transformación y Carga) incluye las siguientes etapas:

1.	Extracción de datos desde el archivo CSV.

2.	Transformación de datos, incluyendo limpieza, manipulación de columnas y eliminación de filas no deseadas.

3.	Carga de datos limpios en un DataFrame listo para su análisis.

Análisis Exploratorio de Datos (EDA)

Este análisis implica:

•	Visualización de la distribución de variables relevantes.

•	Identificación de valores atípicos.

•	Análisis de accidentes por década.

•	Análisis de accidentes por ruta y tipo de aeronave.

Análisis de Causas de Accidentes

Se realizan análisis de las descripciones de los accidentes en busca de palabras clave relacionadas con posibles causas. Estas palabras clave incluyen aspectos técnicos, condiciones climáticas, errores humanos y más.

Resumen por Décadas

Se agrupan los datos por décadas para obtener un resumen cuantitativo de los accidentes en cada período. Esto incluye información sobre personas a bordo, fallecimientos y cantidad de accidentes.

El KPI propuesto se realiza sobre una serie de operaciones en un DataFrame  que contiene información sobre accidentes.

Se definen las décadas de interés (1990 y 2000).

Se  calcula la tasa de fatalidad de la tripulación para  las decadas (1990 y 2000).

Se calculan las tasas de fatalidad para cada década y se almacenan en una lista.

Se calcula la disminución porcentual de la tasa de fatalidad entre la última década y la década anterior.

Se crea un gráfico de barras que muestra la tasa de fatalidad de la tripulación para cada década. 

Con las líneas punteadas se indica la tasa de la última década y la década anterior y se evidencia la disminucion porcentual en la tasa de fatalidad.

 La disminución de la tasa de fatalidad en la última década respecto a la década anterior es del -11.73%.cercana al 10% que se planteaba.

Los KPI,s  se realizan bajo el parametro de un índice de supervivencia para aviones Douglas en las décadas de 1940 y 1950, basado en el número de personas a bordo y el número de fallecidos, vemos que la accidentalidad disminuyo en la decada de los 50 vs los 40 y el indice de supervivencia se incremento.

Se Calcula el índice de supervivencia para cada avión Douglas utilizando la fórmula mencionada.

Se imprime los resultados del índice de supervivencia para los aviones Douglas en las décadas de 1940 y 1950.

El índice de supervivencia promedio para los aviones Douglas en la década de 1940 fue aproximadamente del 12.91%. Esto indica que, en promedio, alrededor del 12.91% de las personas a bordo de estos aviones sobrevivieron en situaciones evaluadas o de accidente.

En la década de 1950, el índice de supervivencia promedio para los aviones Douglas fue de aproximadamente el 21.77%. Esto sugiere una mejora en la tasa de supervivencia en comparación con la década anterior, indicando un desempeño relativamente mejor en términos de seguridad para los pasajeros en esta década.

En resumen, el índice de supervivencia es un indicador importante que muestra la proporción de personas que sobrevivieron en situaciones relacionadas con la seguridad en los aviones Douglas durante las décadas de 1940 y 1950. Un índice más alto implica una mayor tasa de supervivencia y, por lo tanto, un mejor desempeño en términos de seguridad para los pasajeros.

Conclusiones : Los accidentes aereos a lo largo de los años han disminuido y se debe a diferentes factores, mayor capacitacion, incremento en los mantenimientos tanto preventivos como correctivos, disminucion de conflictos belicos, estudio de condiciones climaticas, reduccion en los errores humanos y aumento en los sistemas de seguridad con los que cuentan las aeronaves actualmente, es importante seguir trabajando en el decrecimiento de las tasas de fatalidad de accidentes aereos y es un trabajo riguroso que se debe llevar acabo por entes privados y publicos en todas las naciones, si bien hay factores que no se pueden preveer, como los ataques terroristas, fuego cruzado y condiciones climaticas extremas, se pueden reducir considerablemente las muertes ocasionadas por estos accidentes, generando mayor seguridad y proteccion en las aeronaves, cuando el accidente es inminente, esto necesita de investigacion e inversion a largo plazo para continuar por el camino correcto.
________________________________________
Este README.md proporciona una visión general detallada del proyecto, desde la metodología hasta los análisis realizados. Cada sección está diseñada para facilitar la comprensión del proyecto y fomentar la replicación y expansión del análisis.


Se quiere aclarar y remarcar que el fin de los proyectos propuestos son exclusivamente pedagógicos, con el objetivo de realizar proyectos que simulen un entorno laboral, en el cual se trabajen diversas temáticas ajustadas a la realidad. No reflejan necesariamente la filosofía y valores de la organización. Además, Henry no alienta ni tampoco recomienda a los alumnos y/o cualquier persona que lea los repositorios (y entregas de proyectos) que tomen acciones en base a los datos que pudieran o no haber recabado. Toda la información expuesta y resultados obtenidos en los proyectos nunca deben ser tomados en cuenta para la toma real de decisiones (especialmente en la temática de finanzas, salud, política, etc.).


