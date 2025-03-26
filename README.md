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
