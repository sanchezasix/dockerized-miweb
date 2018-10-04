# Dockerized Miweb

Este fichero contiene los archivos necesarios para utilizarlos en un servidor LAMP para que sirva paginas web, están los archivos de configuración necesarios para ser utilizado con doker,
añade una Pagina web de una empresa de ordenadores.
  
 ### Directorios del repositorio. 
 ```
  dockerized-lamp/
  ├── docker-compose.yml
  └── DocumentRoot
       └── index.php
       └── Pagina_Web
```


## Para que sirve docker:
    
    Docker permite meter en un contenedor todas aquellas cosas que una aplicación necesita para ser ejecutada 
    y la aplicación. Utiliza los recursos del kernel del sistema para ejecutar los contenedores, la ventaja 
    de esto es que no se necesita un sistema operativo para ejecutar un contenedor, el contenedor se ejecuta 
    con los mismos recursos del sistema que ya tenemos instalado.
   
   
   ### Utilidades de los Contenedores:
   
    
     Su utilidad básicamente es para guardar los archivos necesarios para ser ejecutada una aplicación en 
     cualquier equipo sin tener que preocuparse por la versión que tiene instalada, y de si tiene los elementos 
     necesarios para ser ejecutado, así es mas fácil de utilizar una aplicación y de utilizarla en mas equipos. 
        
     Se utilizan menos recursos para utilizar una aplicación en concreto así te olvidas de instalar una maquina 
     para tener aplicaciones concretas.
     
     
   ### Diferencia entre Imagen y Contenedor:
    
    
      Imagen: contiene básicamente la base de la aplicación/servicio que va a ejecutar, el código, 
      el entorno de ejecución, ficheros de configuración..., es una imagen estática no se modifica.
    
      Contenedor: es una instancia de una imagen en ejecución, contiene todo los archivos modificados 
      o añadidos de la imagen.

   ### Que se ha echo:
   
      Instalación de docker.
      Instalación del conjunto de imagenes para poner en marcha un servidor LAMP.
      Configuración de los diferentes ficheros para que funcione correctamente el servidor LAMP.
      Añadir una pagina web al servidor LAMP, en concreto la pagina web echa anteriormente para un trabajo.
      Puesta en marcha del servidor LAMP.
