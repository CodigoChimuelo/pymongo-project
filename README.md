# pymongo-project - Readme 


COMPANY UBICATION PROJECT

1. Con Mongo he filtrado por aquellas compañías que tenían un capital mayor de 1M, aquellas que se han fundado en los últimos 10 años, para buscar empresas "nuevas" y que no haya nulos en la columna oficinas, además he filtrado para que sean empresas tecnológicas filtrando por category_code.

2. Con la función geopoint he modificado la columna office para filtrarlo en MongoDB Compass.

3. Obteniendo las columnas que quería para posteriormente deje filtrar y hacer el geonear en Tableau por los siguientes campos, City, latitude y longitude. 

4. Una vez que ya lo tengo con el formato deseado, he pasado a tableau para mostrar un mapa mundial y saber en que lugar hay más aglomeración de empresas como la que quiero ubicar. En este caso la aglomeración se centra en EEUU, seguido por Europa. Localizamos que la costa oeste del continente Americano tiene la mayor concentración de compañías con tendencias y posibles áreas de negocio/colaboración a la compañía que queremos ubicar, por tanto podemos aprovechar el know how de esas empresas al ubicar sus oficinas y centrarnos en trabajar felizmente.





![Possible Ubications World Map](https://raw.githubusercontent.com/CodigoChimuelo/pymongo-project/master/assets/ub_world_map.png)