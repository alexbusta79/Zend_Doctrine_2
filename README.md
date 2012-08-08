Italiano: 
Questo è una prova semplice di uso di Doctrine 2.0 usando Zend-Framework 
L'applicativo usa un databases in memoria come SQLite, per cui non abbiamo bisogno 
di fare un databases stilo Mysql per farlo funzionare. 
Poi si vuoi usargli in tuoi proggeti soltanto si deve modificare il  archivio 
"config.ini" che sta nell PATH: "PATH/aplication/config/"
poi modificare le righe 18 e 19, inserendo le coordinate della nostra database  
resources.doctrine.connection.driver = "pdo_sqlite"
resources.doctrine.connection.path = APPLICATION_PATH "/../data/db/database.db"
Per provare la aplicazione si deve avere la diretiva: extension=php_apc.dll
attiva sul archivio php.ini. Anche si deve avere il archivio .dll compilato
nella cartella "ext" del nostro php. 
Per fare delle prova possiamo andare al indirizzo 
http://ip/section   oppure http://localhost/section 

Espanol: 
Esta es una prueba simple de uso de Doctrine 2.0 usando Zend-Framework 
La aplicacion usa un databases en memoria como SQLite, por lo tanto no tienes
que hacer una base de datos para que funcione. 
Si despues lo quieres implementar en tus proyectos solo debes modificar el 
archivo "config.ini" que esta en la ruta "PATH/aplication/config/"
y cambiar las lineas 18 y 19 respectivamente, colocando las coordenadas de nuestra 
base de datos, asi como la conexion a ella. 
resources.doctrine.connection.driver = "pdo_sqlite"
resources.doctrine.connection.path = APPLICATION_PATH "/../data/db/database.db"

Para provar la aplicacion debemos tener la directiva: extension=php_apc.dll
activada en nuestro archivo de configuracion php.ini. Debemos tener tambien 
nuestro archivo .dll de esta directiva compilado en la carpeta "ext" de 
nuestro php. 
Para probarlo podemos ingresar en un browser:  
http://ip/section  o tambien   http://localhost/section 