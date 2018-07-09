

De acuerdo a lo conversado, adjuntamos los queries para obtener la información preliminar  y preparar una propuesta para el servicio de optimización y mejora de performance del servidor de base de datos.

 

Por favor, es importante que cuando ejecuten los queries tengan en cuenta las siguientes instrucciones básicas:

 
1.El archivo "1.2 QueriesGetInfo.sql" contiene 64 queries preparados para correr bajo SQL Server 2008 R2, ejecutar uno por uno con resultados en grid a través del SQL Server Management Studio. Los queries no son intrusivos pueden ser ejecutados en business hours de preferencia, el usuario que los ejecuta debe tener derechos de sysadmin sobre la instancia SQL. 
2.Después de ejecutar cada query, deben hacer click en el recuadro superior izquierdo de los resultados en grid para seleccionar todos los resultados, luego right-click y seleccionar “Copy with Headers” para copiar todos los resultados, incluyendo las cabeceras de las columnas.
3.Luego pegar los resultados copiados a cada hoja que se ha preparado en el archivo excel "1.3 Resultados Queries.xlsx", así el resultado del "Query 1" debe ser copiado a la hoja "Query 1" en el excel, y así sucesivamente.
4.A partir del query 40, deben cambiar el contexto a la base de datos de Laboratorio que es la que tiene los problemas de performance segun nos comentaron, en la sentencia USE <nombre_db> reeplazar el <nombre_db> con el nombre real de la db en la que tienen problemas. Los queries 53 y 60 estan comentados, no ejecutarlos.
5.Ejecutar el query del archivo "1.4 PrepPart2.sql". Solo se recibirá un mensaje de ejecución satisfactoria.
6.Ejecutar el query del archivo "1.5 QueriesGetDetails.sql". Una vez finalizado deben hacer click en el recuadro superior izquierdo de los resultados en grid para seleccionar todos los resultados, luego right right-click y seleccionar “Copy with Headers” para copiar todos los resultados, incluyendo las cabeceras de las columnas en un nuevo archivo excel.
7.Ejecutar el query del archivo "1.6 Clean.sql"

  


Por favor enviar los 2 excel para analizar los resultados y determinar si con eso es suficiente para poder preparar la propuesta. De ser necesario y de acuerdo a los resultados se estaría coordinando una reunion y revision para levantar más informacion, podria ser remoto. Esperemos los resultados.

 

Gracias,
