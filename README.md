# gamecsv

# 📊 Analisis del sector de los videojuegos: Exploración y Modelado de Datos

## 2. Introducción

Hemos descargado una base de datos en formato .csv el cual constaba de diferentes columnas y mas de 2.000 lineas que hemos utilizado para realizar un análisis visual de los datos.

**-Rank:** Valores únicos.  
**-Name:** Nombre del videojuego  
**-Platform:** Plataforma  
**-Year:** Año  
**-Genre:** Género del videojuego  
**-Publisher:** Distribuidora  

NA=USA  
EU=Europa  
JP= Japón  
Other= Otras regiones  
Global Sales= Total Ventas  

Link directo:  
<https://www.kaggle.com/datasets/gregorut/videogamesales>  

## 3. Descripción del Proyecto y pasos
Hemos empezado exportando el archivo en formato .csv. Hemos decidido trabajar con todas las columnas sin eliminar ninguna. El objetivo es analizar las ventas centrandonos  
 mayoritariamente por el género. Para ello podreos ver la evolución de la venta por genero dependiendo de diferentes variables.  
En la parte del analisis analizaos las ventas a nivel global y despues analizamos las ventas por genero pero incluyendo otras variables (plataforma, distirbuidora..)  

Para la limpieza y transformación:  

Hemos revisado y elimiinado los duplicados  
Hemos visto que hay algunas combinaciones o celdas blank, pero valoramos dejar los ceros, ya que son juegos que quizásen una región no se han vendido pero en otras si.  
Hemos Garantizado que en las columnas de Ranking, name y genero no dentamos vacíos.  
Hemos eliminado aquellos juegos que no tienen un año indicado. No eran muchas lineas(realtivo poco impacto) y no eran utiles para nuestro análisis.  

Sabemos como realizar un analisis perfecto, pero para esta base de datos en cuestión,  
No hemos sacado media, mediana o percentiles ya que solo tenemos datos cualitativos y no encontro el sentido de sacar la media de ventas por plataforma o genero…  
Ademas desconocemos si tenemos para cada año la totalidad de las ventas o solo una parte representativa (sospechamos que solo e suna representación)  

Las ventas se representan en millones de dolares y hemos decidido simplemente en la zona del dashbboard y analisis dejar la palabra M para que se tenga constancia  



Menciona brevemente el contexto del análisis y qué problema estás
resolviendo.
Incluye qué técnicas o enfoques se usaron para llevar a cabo el análisis.
Ejemplo: 📖 Descripción
Este proyecto realiza un análisis exploratorio y predictivo de las ventas de una
empresa minorista. El objetivo es identificar tendencias, patrones y realizar
predicciones basadas en datos históricos usando técnicas de modelado
estadístico.

## 4. Estructura del Proyecto

🗂 Estructura del Proyecto
├── videogameanalysis.xlsx # Excel file
├── README.md # Descripción del proyecto

## 5. Instalación y Requisitos
Nada es necesario, simplemente acceso y cuenta de Microsoft para Excel.

## 6. Resultados y Conclusiones

Presenta un resumen de los hallazgos más importantes.
Puedes incluir gráficos o tablas relevantes que apoyen las conclusiones.
Explica cómo los resultados pueden ser útiles para los usuarios o
tomadores de decisiones.
Ejemplo:
📊 Resultados y Conclusiones
📝 Guía para Escribir un Buen README en Nuestros Proyectos 3
- Identificamos un aumento estacional en las ventas durante los meses de
noviembre y diciembre.
- El modelo predictivo alcanzó un 85% de precisión en la estimación de ventas
futuras.
- El análisis sugiere que los descuentos y promociones tienen un impacto
directo en el comportamiento de compra de los clientes.
6. Próximos Pasos
Si el proyecto sigue en desarrollo, menciona qué queda por hacer o
mejorar.
También puedes mencionar ideas para futuros análisis o expansiones del
proyecto.
Ejemplo:
🔄 Próximos Pasos
- Refinar el modelo predictivo usando más datos históricos.
- Implementar técnicas avanzadas de feature engineering para mejorar la
precisión.
- Explorar el impacto de factores externos como cam
