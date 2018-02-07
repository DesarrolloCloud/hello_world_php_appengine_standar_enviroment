# HELLO WORLD PHP APP ENGINE STANDART ENVIROMENT

Aplicativo inicial en PHP para Google App Engine 
Standart Enviroment

### Requerimientos

**Toda la configuracion se a realizardo para linux - ubuntu 16.04**

1. Instalar google cloud sdk. [Page Oficial Intalacion] (https://cloud.google.com/sdk/docs/?hl=es)
2. Instalar app-engine-php con el comando:
	**gcloud components install app-engine-php**
3. Instalar php5.6-cgi con el comando:
	**sudo apt install php5.6-cgi**
   Talves necesites [instalar php5.6]( http://www.ingdiaz.org/cambiar-version-php-7-0-php-5-6-ubuntu-16-04/)
  
### Ejecucion del aplicativo en desarrollo

1. Dirigirte a la carpeta donde has clonado el codigo de la aplicacion
2. Ejecutar el comando:
	**dev_appserver.py --php_executable_path=/usr/bin/php-cgi5.6 --port=8099 app.yaml**
3.-Colocar en el browser http://localhost:8099.

### Ejecucion del aplicativo en GCP App Engine
1.- Dirigirte a la carpeta donde has clonado el codigo de la aplicación
2.- gcloud init (para configurar el proyecto al que vas a subir el aplicativo)
3.- gcloud app deploy (subes el aplicativo a app engine)
4.- gcloud browse (para que obtengas la URL de internet del aplicativo)

### Consultas y Asesorias

**Contactate conmigo escribiendome a wilsonnm22@gmail.com**

