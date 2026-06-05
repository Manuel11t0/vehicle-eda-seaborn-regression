# Vehicle EDA Seaborn Regression

Este proyecto realiza un análisis exploratorio de datos usando Python y Seaborn.  
Se trabajan dos archivos CSV relacionados con vehículos por entidad y datos mensuales de personal.

## Descripción del proyecto

El objetivo principal es explorar, visualizar y analizar la relación entre diferentes variables, principalmente:

- Automóviles
- Autobuses
- Camionetas
- Personal mensual

El proyecto utiliza gráficas estadísticas y un modelo de regresión lineal para observar patrones, relaciones y posibles comportamientos dentro de los datos.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Análisis realizado

Durante el proyecto se realizan los siguientes pasos:

1. Carga de archivos CSV.
2. Lectura de los datasets `reto.csv` y `reto3.csv`.
3. Revisión inicial de columnas y datos.
4. Boxplot para analizar la distribución de autobuses.
5. Cálculo de la mediana de autobuses.
6. Gráfica 3D entre automóviles, autobuses y camionetas.
7. Modelo de regresión lineal para estimar automóviles usando autobuses y camionetas.
8. Gráfica de residuos del modelo.
9. Cálculo de correlación entre automóviles y autobuses.
10. Gráfica de dispersión con recta de ajuste.
11. KDEplot para las primeras 6 entidades.
12. Histograma del personal de enero a junio.
13. Gráfica de barras del personal por mes.
14. Gráfica de pastel para la distribución de automóviles.
15. Visualización final de dispersión con ajuste lineal.

## Modelo utilizado

Se utiliza un modelo de regresión lineal con la siguiente idea:

```text
Automóvil ~ Autobús + Camioneta
