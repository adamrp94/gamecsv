
# 📊🎮Analisis del sector de los videojuegos: Exploración y Modelado de Datos

## 2. Introducción 📄 

Hemos descargado una base de datos en formato .csv del link indicado más abajo, el cual constaba de diferentes columnas y mas de 2.000 lineas que hemos utilizado para realizar un análisis visual de los datos. No es la mejor base de datos que pudiesemos utilizar debido a que hay muchos datos cualitativos (caracteristicas, descripciones...) que no cuantitativos (medibles y númericos) pero he considerado interesante igual ver como sería posible visualizar los datos y sacar algunas conclusiones solamente con lo existente.

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

## 3. Descripción del Proyecto y pasos 📖

Este proyecto realiza un análisis exploratorio de las ventas en el sector de los videojuegos. El objetivo es identificar patrones o cuales son los generos mas exitosos.  

Hemos empezado exportando el archivo en formato .csv. 
Hemos decidido trabajar con todas las columnas sin eliminar ninguna. El objetivo es analizar las ventas centrandonos mayoritariamente por el género. 
Para ello podremos ver la evolución de la venta por género dependiendo de diferentes variables.  
En la parte del análisis, analizamos las ventas a nivel global y despues analizamos las ventas por género pero incluyendo otras variables (plataforma, distribuidora...)  

<u>Para la limpieza y transformación:<u>  

-Hemos revisado y eliminado los duplicados.
-Hemos visto que hay algunas combinaciones o celdas "blank", pero valoramos dejar los ceros, ya que son juegos que quizás en en una región no se han vendido pero en otras si.  
-Hemos garantizado que en las columnas de Ranking, name y género no tengamos vacíos.  
-Hemos eliminado aquellos juegos que no tienen un año indicado >> No eran muchas lineas (relativo poco impacto) y no eran útiles para nuestro análisis.  

Sabemos como realizar un análisis perfecto, pero para esta base de datos en cuestión,  
-No hemos sacado media, mediana o percentiles ya que praticamente solo tenemos datos cualitativos y no encuentro el sentido de sacar la media de ventas por plataforma o género y uno de los motivos es porque desconocemos si tenemos para cada año la totalidad de las ventas o solo una parte representativa (sospechamos que solo es una representación ya que en la base original no había datos por ejemplo para el año 2018)  

-Las ventas se representan en millones de dolares y hemos decidido simplemente en la zona del dashbboard y análisis dejar la palabra M para que se tenga constancia.     

-En la Base de datos inicial, los datos llegan hasta el 2020 pero hemos detectado que desde el 2010 no está bien actualizada o mantenida ya que no hay datos para determinados años (lo cual es imposible). Es por eso que hemos decidido hacer el analisis hasta el 2010 y así tener 3 decadas.  

-Hemos representado los datos:  
Ventas por región (USA, EU y Japón las mas importantes, lo restante para resto de regiones)  
Ventas por género.  
Ventas por género y plataforma.  
Juegos mas vendidos.  
Ventas por año (de lo que tenemos).  
Zona top 5 para hacer mas visual las ventas por Género, Plataforma y Distribuidora.

Filtros para regiones y años.  

## 4. Estructura del Proyecto 📝 

🗂 Estructura del Proyecto  
├── videogameanalysis.xlsx # Excel file mostrando lo necesario
├── video game sales.csv # Archivo original
├── README.md # Descripción del proyecto  

## 5. Instalación y Requisitos 🔧
Ningún complemento o programa es necesario. Simplemente acceso y cuenta de Microsoft para Excel.  

## 6. Resultados y Conclusiones🔍


➡️En todas las regiones el género mas vendido es el de "acción" salvo para el conjunto de otras regiones que es el "role play".  
Sin embargo Other regions sin filtros aplicados demuestra que es la zona del planeta con menos ventas comparativamente hablando respecto los grandes mercados de Estados Unidos, Japón y Europa, por lo cual es un dato importante saber que el género de acción es el mas importante donde mas ventas se producen.   
Conclusión: las probabilidades de tener más exito si distribuimos un juego de acción en los mercados es más alta respecto al resto.

- El análisis sugiere que el género tienen un impacto directo en el comportamiento de compra de los clientes.    

➡️🔝En Estados Unidos y Europa el juego con más exito ha sido Wii Sports. Para Japón: Pokemón y para el resto de regiones Gran Thef Auto: San Andreas.    

➡️La Plataforma con más éxito ha sido la Play Station 2 (PS2).    

➡️La distribuidora con más éxito ha sido Nintendo.      

➡️💰Las ventas no han dejado de ascender desde el dato que tenemos de 1980, con importantes picos en el 1996 y 2006. Posibles motivos:  

Año 1996: Transición a las 3D y títulos icónicos.  
Lanzamiento de la Nintendo 64: Introdujo gráficos tridimensionales avanzados y juegos innovadores como Super Mario 64, que redefinieron la experiencia de juego.  ​
Éxito de la PlayStation: Con títulos como Resident Evil, Crash Bandicoot y Tomb Raider, Sony consolidó su posición en el mercado, atrayendo a una amplia audiencia.​  
Introducción de franquicias duraderas: El debut de Pokémon en Japón marcó el inicio de una de las series más exitosas en la historia de los videojuegos.  

Año 2006: Nueva generación de consolas y expansión del mercado caracterizado por:​  

Lanzamiento de consolas de nueva generación:  
Nintendo Wii: Con su innovador control de movimiento, atrajo a un público más amplio, incluyendo a jugadores casuales y familias.  
PlayStation 3 y Xbox 360: Ofrecieron mejoras gráficas y funciones en línea, elevando la experiencia de juego.​  
Ventas récord: las ventas en EE. UU. alcanzaron los $12.5 mil millones, un aumento del 19% respecto al año anterior.  

➡️Se observa lógicamente como para los primeros años las plataformas con más exito eran Atari y Activision. Las cuales en la actualidad han pérdido cuota de mercado.

➡️📈A lo largo de los años el mercado siempre con mas ventas siempre ha sido USA!

Próximos pasos: Se podría añadir datos fiables para los siguientes años de fuentes oficiales si existiesen.
