# S8---ZUBER
Impacto del clima en la preferencia de los pasajeros para una empresa de viajes en taxi. 
Extracción de infomación de sitios web HTML y uso de comandos SQL.

## Descripción
Zuber, una nueva empresa de viajes compartidos que se está lanzando en Chicago, le interesa comprender las preferencias de los pasajeros y el impacto de los factores externos en los viajes, como el clima y los competidores.

Hipótesis a comprobar : "La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos".

## Herramientas utilizadas
![Python](https://img.shields.io/badge/:Python-024A86?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)</br>
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/seaborn-%233F4F75.svg?style=for-the-badge&logo=seaborn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![Datetime](https://img.shields.io/badge/datetime-%233F4F75.svg?style=for-the-badge&logo=datetime&logoColor=white)

![MySQL](https://img.shields.io/badge/:MySQL-E36B26?style=for-the-badge&logo=mysql&logoColor=white&labelColor=101010)</br>
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![DBeaver](https://img.shields.io/badge/dbeaver-382923?style=for-the-badge&logo=dbeaver&logoColor=white)


![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)


## Conclusiones 
Se concluye que ciertamente cambia la duración promedio de los viajes los sabados lluviosos.

Se pudo corroborar con los gráficos de bigotes en los que la media de la duración de los viajes en sabados lluviosos es de 2427 segundos, mientras que la de los demás días es menor a 1999 segundos.

## Profundización técnica

* Extracción de información de sitios web con librería - requests.get(url='')
* Trabajo de tablas HTML con librería BeautifulSoup
--
*  Extracción de información mediante comandos SQL.
--
*  Análisis exploratorio en Python:
*  * Importar archivos
   * Explorar columnas, tipos de datos, nulos...
   * Ordenar por valores en columna - df.sort_values(by='col',ascending='False/True')
   * Graficas - df.plot(x='col1',y='col2', title=, kind= , color=, xlabel='' , ylabel='',figsize=(,), rot=) ,plt.show()
   * Trabajo con fechas - df['col']= pd.to_datetime(df['col'],  format= '%Y-%m-%d  %H:%M:%S'), value.day()/weekday()/month()....
   * Graficos de caja bigotes (sns.boxplot(s),plt.show()) y valores estadísticos (s.describe())
   * Prueba de hipótesis entre dos poblaciones, de dos colas con prueba de Taylor - si results.pvalue < alpha se rechaza hipótesis nula (=)
