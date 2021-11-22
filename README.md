# Selenium_project:
![portada](https://github.com/Lydia-Arocena/Selenium_project/blob/main/LOGO.png)
​
## Objetivo
Este proyecto tiene como objetivo verificar o rechazar las 5 hipótesis planteadas sobre los datos recabados de la página web Kenay Home a través de visualizaciones. 

Las hipótesis son las siguientes:
​
- **El precio de ningún artículo superaba los 3,000 euros antes de la rebaja:** FALSO --> 4 de ellos superan ese precio.
- **La mayoría de los artículos se entregan en el plazo de 7 días:** --> VERDADERO.
- **El 75% de los artículos están rebajados, al menos, en 900 euros:** FALSO --> Concretamente, la rebaja del 75% de los artículos es de, al menos, 651.42 €.
- **Hay el mismo número de butacas rebajadas en Kenay que de pufs:** FALSO --> Hay una butaca más.
- **Los precios de los sofás tras la rebaja rondan los 1,000 euros de media:** VERDADERO.



## Desarrollo:
En primer lugar,he escrapeado el apartado de Sofás con ofertas de "Black Friday" de la página web de Kenay Homes usando **Selenium**. Mediante esta técnica, he recabado los datos relativos a los nombres de los artículos, el precio original, el precio rebajado y el plazo previsto de entrega de los mismos.

Luego, con esos datos, he creado un dataframe, lo he limpiado transformando el tipo de algunos datos de string a float para poder así operar con ellos y creado algunas columnas nuevas a través del uso de funciones y también operando con las ya existentes.

Para todo ello, he utilizado la fuente de la página oficial de Kenay Homes ("https://kenayhome.com/es/")



## Estructura del proyecto:
​
La estructura del proyecto se compone de:
-  archivo Jupyter Notebook:en él he llevado a cabo el escrapeo usando Selenium, he creado mi df y mostrado mis cinco visualizaciones que prueban o desmienten mis hipótesis.
- Readme.
- Output: dataframe importado en formato csv como resultado del escrapeo y limpieza de los datos.


## Librerías:
- **Pandas** (https://pandas.pydata.org/)
- **re** (https://docs.python.org/3/library/re.html)
- **Selenium** (https://www.selenium.dev/es/documentation/)
- **Plotly.express** (https://plotly.com/python-api-reference/plotly.express.html)
- **Seaborn** (https://seaborn.pydata.org/)
- **Matplotli.pyplot** (https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
- **Selenium web driver** (https://www.selenium.dev/documentation/webdriver/)
- **matplotlib** (https://matplotlib.org/)
- **time** (https://www.programiz.com/python-programming/time)
 
