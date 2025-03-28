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

## Análisis de Gráfico de Evolución Temporal de Premios Nobel

![Screenshot from 2025-03-27 15-16-06](https://github.com/user-attachments/assets/ab3a510f-e9c2-4fdd-b42b-646f44a30576)

Descripción del Gráfico

El gráfico muestra la evolución anual de premios Nobel desde 1901 hasta el año 2023. 

Hallazgos clave:

1. Tendencia general ascendente

    Se observa un aumento progresivo en el número de premios concedidos por año con picos notables como en 2001, donde se registró la mayor cantidad de galardonados (15). Aumentos de categorías que podrían corresponder a premios compartidos o categorías especiales, avances científicos significativos o a la acumulación de méritos en períodos anteriores, especialmente a partir de 1950. En 1969 punto de inflexión visible con la introducción del Premio en Ciencias Económicas. 

  Promedio histórico:
    
    - 1901-1940: 5 premios/año.
    - 1914-1918 (Primera Guerra Mundial): hubo una disminución en la concesión de premios, especialmente en categorías como Paz y Literatura.
    - 1939-1945 (Segunda Guerra Mundial): Caída más pronunciada y eventos como la Guerra Fría también afectaron.
    - 1950-2000: 10 premios/año.
    - 2001-presente: 12-15 premios/año.

2. Edad de los Galardonados

   La media de edad, a lo largo de los años (1901-2023), es de 60 años. Se observan edades que van desde los 17 años, destacando a Malala Yousafzai, la más joven en recibir el Premio Nobel de la Paz en 2014, hasta los 97 años, con el caso del profesor John Goodenough, quien ganó el Premio Nobel de Química en 2019 por su contribución al desarrollo de las baterías de iones de litio, una labor que ha dedicado décadas de trabajo y sigue siendo activo en la actualidad.

Tendencias por disciplina:

    Ciencias (Física, Química, Medicina): Los premiados suelen ser mayores (50-70 años), ya que sus contribuciones requieren años de estudio.

    Paz y Literatura: Edades más variadas, incluyendo galardonados jóvenes con impacto inmediato (activistas).

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
![image](https://github.com/user-attachments/assets/286e14a9-e3dc-4571-9b9c-528addffd7c7)


Estudio desde 1901-2023

Gráfica de quesitos:

·Porcentaje total de premios otorgados a hombres y mujeres. Se aprecia predominio masculino.

Gráfica de barras:

·A pesar de que hay una gran disparidad en todas las categorías, curiosamente, las que están relacionadas con la Paz y la Literatura son las categorías donde las mujeres tienen una mayor representación y visión. Por el contrario, Economía es la que menos mujeres premiadas tiene, no obstante, su entrega de premios es menor que el resto, por lo que su casi ausencia es comprensible si comparamos las barras.

Gráfica lineal:

·Una comparativa a lo largo de los años entre hombres y mujeres premiados. Aquí se puede apreciar que la línea de hombres crece de forma constante y pronunciada mientras que la de mujeres se mantiene baja y casi sin cambios. Sin embargo, entre 1960 y 1990 se aprecia la primera subida significante que, aun manteniendo la gran disparidad con hombres, es un dato crucial para saber sobre qué años empezaron a recibir muchos más premios. De ahí en adelante, su incremento ha sido exponencial, pero no similar a los premiados masculinos.

## APORTACION POR JB!! LEER Y REVISAR/MODIFICAR

1. Casos de Mujeres No Reconocidas en los Premios Nobel
A lo largo de la historia, varias mujeres han sido ignoradas o desplazadas en favor de hombres (maridos, colegas o superiores). Algunos casos conocidos:

A. Rosalind Franklin (Química, 1962)
Contribución: Descubrió la estructura del ADN mediante cristalografía de rayos X (Fotografía 51).

Premio dado a: James Watson, Francis Crick y Maurice Wilkins (1962, Fisiología/Medicina).

Razón: Murió antes de la nominación (1958), y su trabajo fue usado sin reconocimiento explícito.

B. Lise Meitner (Física, 1944)
Contribución: Descubrió la fisión nuclear junto a Otto Hahn.

Premio dado a: Solo Otto Hahn (1944, Química).

Razón: Exclusión por ser mujer y judía en la Alemania nazi.

C. Jocelyn Bell Burnell (Física, 1974)
Contribución: Descubrió los púlsares (estrellas de neutrones).

Premio dado a: Su supervisor, Antony Hewish (1974, Física).

Razón: Era estudiante de doctorado y no fue considerada "suficientemente senior".

D. Esther Lederberg (Medicina, 1958)
Contribución: Descubrió el virus bacteriófago lambda y técnicas clave en genética.

Premio dado a: Su marido, Joshua Lederberg (1958, Medicina).

Razón: Su trabajo fue atribuido a él por jerarquía de género en la ciencia.

E. Chien-Shiung Wu (Física, 1957)
Contribución: Demostró la violación de la paridad en física nuclear (experimento Wu).

Premio dado a: Tsung-Dao Lee y Chen Ning Yang (1957, Física).

Razón: Exclusión sistemática de mujeres en física teórica.

## Representación geográfica entre países o regiones
![image](https://github.com/user-attachments/assets/35ccc9fc-6c34-4700-a5a7-10b9e3f62093)

## Recomendaciones para mejorar la diversidad y representación

-- Reformas en el proceso de nominación:
	Establecer metas de paridad en nominaciones (como el Nobel de Literatura 2018, pospuesto por falta de diversidad).

	Incluir más mujeres y expertos de países no occidentales en las academias suecas y noruegas.

-- Reconocimiento Póstumo y revisión histórica:
	
	Crear un informe oficial sobre científicas excluidas. Como Lise Meitner (Física, 1944) por ser mujer y judía en la Alemania nazi, Esther Lederberg (Medicina, 1958) atribuido a su marido por jerarquía de género en la ciencia, etc..
	
	Otorgar distinciones especiales a contribuciones ignoradas, como el "Nobel Paralelo" de Derechos Humanos.Se entrega a individuos o grupos que hayan destacado en la lucha por los derechos fundamentales, la justicia social y la paz, en situaciones donde el Nobel de la Paz tradicional no ha reconocido.

-- Visibilización de Mujeres en Ciencia:
	Incluir en libros de texto a figuras femeninas como Jocelyn Bell Burnell o Esther Lederberg, etc..

	Producir contenido sobre científicas no reconocidas. Película "Photograph 51" sobre Franklin: se centra en la vida de Rosalind Franklin, una científica británica que jugó un papel clave en el descubrimiento de la estructura del ADN y murió antes de la nominación (1958). Su trabajo fue usado sin reconocimiento explícito.

-- Políticas Institucionales Contra el Sesgo:
	Publicar listas de candidatos/as previos para evitar "robo de autoría".

	Evitar que el premio se otorgue solo al "jefe de laboratorio" y no a quienes hicieron el trabajo clave.

	Conectar a jóvenes científicas con galardonadas, como "Nobel Women’s Initiative", organización de defensa internacional con sede en Ottawa, Canadá. Creado en 2006 por seis mujeres ganadoras del Premio Nobel de la Paz para apoyar a grupos de mujeres de todo el mundo. 

## Organización de presentación

![Screenshot from 2025-03-28 12-51-15](https://github.com/user-attachments/assets/af1e0748-33fd-41b0-9563-6a00529955a1)

## Problemas y soluciones:

Ecnontramos una columna que daba problemas, la de 'Year'. Estaba como texto y lo converti a años para que lo identificara como DATE.
Y para crear la columna 'award-winning age' tuve que extraer el año de a columna 'Born' convertirla en numero para restar al año del premio y asi sacar la edad cuando recibieron el galardón.
