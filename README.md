Construcción del proyecto
===================


A continuación vamos a explicar cómo construir y ejecutar el proyecto con 'jetty', como servidor embebido y como obtener el fichero **WAR**

----------


Build
-------------

En primer lugar, ejecutamos el comando mvn compile **dentro de la raiz del proyecto**

    $mvn compile

Después tenemos que ejecutar:

    $mvn package

Con esto obtendremos la carpeta */target*, que contendrá dentro el **.war**
Para iniciar el servidor jetty, ejecutaremos dentro del raiz el siguiente comando:

    mvn jetty:run
    
El servidor quedará abierto en segundo plano en la shell, y ya podremos a través del browser probarlo y lanzar peticiones al servidor.

    http://localhost:9999/

