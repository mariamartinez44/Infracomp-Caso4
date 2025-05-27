# Infracomp-Caso4

Para realizar las pruebas, se conectaron las 2 ips proporcionadas (172.23.66.79 y 172.23.66.92) a conexionUniandes.sh siguiendo el tutorial de conexión proporcionado por el curso. Luego de esto, se generó un docker para la ip 172.23.66.79 y se hicieron las pruebas de verificación de conexión.

Con estos datos, se procedió a instalar jmeter y python en la instancia con ip 172.23.66.92. Ya con esto, se creó el archivo mock_data.txt, generando de forma random datos hasta conseguir un peso aproximado de 67KB.
Luego de haber creado mock_data.txt, se crearon los archivos de purbe usando jmeter.

Mediante la máquina local, se configuró el entorno de prueba con la IP 172.23.66.79 y el puerto 78080. Se usó un ramp-up de 100 segundos con threads desde los 1000 a los 6000 threads. 
Con la configuración definida, se corrieron las pruebas, modificando el archivo .jmx para cambiar el valor de threads y produciendo los resultados en archivos nombrados "resultsXXXX", donde XXXX representa el número de threads.

Debido a que estos arechivos son extensos, se optó por realizar el procesamiento de datos para obtención de resultados directamente en la instancia con ip 172.23.66.92, usando el código mostrado en 
