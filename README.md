# Project---Nobel-Prizes
![Screenshot from 2025-03-24 10-31-37](https://github.com/user-attachments/assets/a8f7c0c4-11b7-4c47-a018-3084c53769ed)

El Comité Nobel desea evaluar los patrones históricos en la concesión de los Premios Nobel. Para ello, se ha recopilado información detallada sobre los galardonados, incluyendo su nacionalidad, género, disciplina y año de entrega, con el fin de entender mejor la evolución y diversidad en la historia de los premios.

Guión Premios Nobel
👨💼 SOLICITUD DEL CLIENTE
“Queremos identificar posibles patrones, cambios o sesgos históricos en la entrega de los
Premios Nobel, con el fin de fomentar una mayor equidad y representatividad.”

● Identificar patrones históricos: distribución por género, país y disciplina a lo largo del
tiempo.

● Evaluar la representación de género en las distintas categorías.

● Analizar la evolución temporal de la concesión de premios.

● Comparar la representación geográfica entre países o regiones.

● Proponer recomendaciones para mejorar la diversidad y representación futura.

-------------------------------------------------
Día 1. Visualización general de registros.
-----------------------------------------

Análisis previo al EDA.

-No se detectan registros duplicados.

-Se detectan IDs repetidos y NULL.

-Fecha nacimiento o muerte NULL.

-Born Country con valor NULL o ??.

-Overall motivation mayor parte NULL.

-Hay lugares de muerte NULL.

-Nombre de organizaciones NULL.


Día 2. Análisis de datos con gráficos:
-----------------------------------------

![Screenshot from 2025-03-25 10-45-33](https://github.com/user-attachments/assets/a7f2cba2-dba9-4e8f-91f5-6ee9d4a58677)

![Screenshot from 2025-03-25 11-42-52](https://github.com/user-attachments/assets/a0809694-f74b-48f1-b29d-20cabf0e1ac3)

![Screenshot from 2025-03-25 15-09-16](https://github.com/user-attachments/assets/05b6761b-de58-4367-b4b9-8e3d3fe5f30f)

-Descubrimiento de coordenadas. (Deben cambiarse a formato GEO en LookerStudio)

![Screenshot_from_2025-03-25_15-07-52](https://github.com/user-attachments/assets/43942fe5-711f-45be-8d71-1118c7adb067) 
![Screenshot_from_2025-03-25_15-08-13](https://github.com/user-attachments/assets/4aa585c3-5c2d-4868-a204-02fbf5614ebd)

GOOGLE LOOKER STUDIO:
-----------------------

Análisis de Gráfico de Evolución Temporal de Premios Nobel

![Screenshot from 2025-03-26 11-10-54](https://github.com/user-attachments/assets/0cc98f02-fe8a-4cf4-afd6-4a0823916e8c)


Descripción del Gráfico

El gráfico muestra la evolución anual en la concesión de premios Nobel desde 1901 hasta el año 2023. Hallazgos clave:

1. Tendencia general ascendente

    Crecimiento notable: Se observa un aumento progresivo en el número de premios concedidos por año, especialmente a partir de 1950.

  Promedio histórico:
    
    - 1901-1940: 5 premios/año
    
    - 1950-2000: 10 premios/año
    
    - 2001-presente: 12-15 premios/año

2. Eventos históricos visibles

    Impacto de guerras mundiales:
      - Notable disminución 1914-1918 (Primera Guerra Mundial)
      - Caída más pronunciada 1939-1945 (Segunda Guerra Mundial)
    Años sin premiados: Algunos años muestran cero premios en ciertas categorías durante periodos bélicos.

3. Cambios institucionales

    1969: Punto de inflexión visible con la introducción del Premio en Ciencias Económicas.

    Aumento de categorías: Algunos años muestran "picos" que podrían corresponder a premios compartidos o categorías especiales.


    Segmentar por categorías para identificar patrones específicos

    Añadir anotaciones para eventos históricos relevantes

    Analizar correlación con indicadores de inversión en investigación mundial

    Crear vista por décadas para identificar tendencias de más largo plazo

Este análisis revela que la concesión de premios Nobel funciona como termómetro del desarrollo científico global, reflejando eventos históricos y cambios en la geopolítica de la investigación.


## Nobel Prizes by Discipline Over Time
![Screenshot from 2025-03-26 15-51-22](https://github.com/user-attachments/assets/bc3f51ae-1108-45bb-b45e-fe1709b380bf)

Esta gráfica de líneas muestra el número de premios Nobel otorgados en seis categorías diferentes (Medicina, Física, Química, Paz, Literatura y Economía) a lo largo del tiempo, desde 1901 hasta 2022.

Descripción de la gráfica:

Eje X (Horizontal): Representa los años, con marcas cada 11 años desde 1901 hasta 2022.
Eje Y (Vertical): Representa el recuento de premios Nobel otorgados en un año determinado, con valores que van de 0 a 4.
Líneas de colores: Cada línea representa una categoría diferente del Premio Nobel, con una leyenda en la parte superior para identificar cada color.
Puntos de datos: Cada punto en una línea representa el número de premios Nobel otorgados en esa categoría en un año específico.
Conclusiones que se pueden obtener de la gráfica:

Tendencia general al aumento: Se observa una tendencia general al aumento en el número de premios Nobel otorgados por año en todas las categorías a lo largo del tiempo. Esto podría reflejar el crecimiento de la investigación científica y el reconocimiento de logros en diversas áreas.
Variaciones por categoría: El número de premios Nobel otorgados varía significativamente entre las diferentes categorías. Por ejemplo, Medicina y Física tienden a tener un mayor número de premios otorgados en comparación con Literatura y Economía.

Picos y valles: Se pueden observar picos y valles en el número de premios otorgados en algunas categorías en ciertos años. Estos picos y valles podrían estar relacionados con eventos históricos específicos, como guerras o crisis económicas, que podrían haber afectado la investigación y el reconocimiento en ciertas áreas.
Estabilidad en algunas categorías: Algunas categorías, como Economía, muestran una mayor estabilidad en el número de premios otorgados por año en comparación con otras categorías.
Aumento en el siglo XXI: Se observa un aumento notable en el número de premios Nobel otorgados en todas las categorías a partir del siglo XXI. Esto podría reflejar un mayor énfasis en la investigación y el desarrollo en diversas áreas en los últimos años.

En general, esta gráfica proporciona una visión general interesante de la distribución de los premios Nobel a lo largo del tiempo y destaca algunas tendencias y variaciones importantes entre las diferentes categorías.

## Nobel Prizes by Country Over Time
![Screenshot from 2025-03-26 15-53-25](https://github.com/user-attachments/assets/d3b88741-e2c9-4297-a196-1fed18522cea)

La gráfica de líneas muestra el número de premios Nobel otorgados por país de afiliación del laureado a lo largo del tiempo, desde 1901 hasta 2022.

Descripción de la gráfica:

Eje X (Horizontal): Representa los años, con marcas cada 11 años desde 1901 hasta 2022.
Eje Y (Vertical): Representa el recuento de premios Nobel otorgados a personas afiliadas a instituciones en un país determinado en un año específico, con valores que van de 0 a 10.
Líneas de colores: Cada línea representa un país diferente, con una leyenda en la parte superior para identificar cada color. Se incluyen países como Estados Unidos, Reino Unido, Alemania, Francia, Suiza, Suecia, Japón, Rusia y los Países Bajos, además de una categoría para "Sin afiliación".
Puntos de datos: Cada punto en una línea representa el número de premios Nobel otorgados a personas afiliadas a instituciones en ese país en un año específico.
Conclusiones que se pueden obtener de la gráfica:

Dominio de Estados Unidos: Se observa un claro dominio de Estados Unidos en el número de premios Nobel otorgados a lo largo del tiempo, especialmente a partir de la segunda mitad del siglo XX.
Importancia histórica de países europeos: Reino Unido, Alemania y Francia también han tenido una contribución significativa al número de premios Nobel, especialmente en las primeras décadas.
Aumento general en el tiempo: Al igual que en la gráfica anterior, se aprecia una tendencia general al aumento en el número de premios Nobel otorgados por año, incluso al considerar la afiliación por país.
Variaciones y picos: Se pueden observar variaciones anuales y picos en el número de premios otorgados a cada país, lo que podría reflejar eventos históricos, inversiones en investigación o el surgimiento de investigadores destacados.
Contribuciones de otros países: Aunque en menor medida, países como Suecia, Japón, Rusia y los Países Bajos también han tenido laureados con premios Nobel a lo largo del tiempo.
Categoría "Sin afiliación": La categoría "Sin afiliación" indica premios otorgados a individuos que no estaban afiliados a ninguna institución en el momento de recibir el premio. Estos casos son menos frecuentes.

En resumen, esta gráfica destaca la notable contribución de Estados Unidos a la investigación y los logros reconocidos por los premios Nobel, a la vez que muestra la importancia histórica de varios países europeos y las contribuciones de otras naciones a lo largo del siglo XX y principios del XXI.


## Estadísticas de premios Nobel por género.
-
![Screenshot from 2025-03-26 15-52-00](https://github.com/user-attachments/assets/19ed3761-4631-4e14-a500-0ad2f7f4e04e)

Estudio desde 1901-2023

Gráfica de quesitos:

·Porcentaje total de premios otorgados a hombres y mujeres. Se aprecia predominio masculino.

Gráfica de barras:

·A pesar de que hay una gran disparidad en todas las categorías, curiosamente, las que están relacionadas con la Paz y la Literatura son las categorías donde las mujeres tienen una mayor representación y visión. Por el contrario, Economía es la que menos mujeres premiadas tiene, no obstante, su entrega de premios es menor que el resto, por lo que su casi ausencia es comprensible si comparamos las barras.

Gráfica lineal:

·Una comparativa a lo largo de los años entre hombres y mujeres premiados. Aquí se puede apreciar que la línea de hombres crece de forma constante y pronunciada mientras que la de mujeres se mantiene baja y casi sin cambios. Sin embargo, entre 1960 y 1990 se aprecia la primera subida significante que, aun manteniendo la gran disparidad con hombres, es un dato crucial para saber sobre qué años empezaron a recibir muchos más premios. De ahí en adelante, su incremento ha sido exponencial, pero no similar a los premiados masculinos.

## Representación geográfica entre países o regiones
![image](https://github.com/user-attachments/assets/38ef3b19-13fe-4f7f-98d2-2655e34d5491)
