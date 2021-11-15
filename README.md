# Título del Proyecto

Es un sitio web dedicada a la visualización del historial de reservas de un restaurante mediante la reserva y liberación de mesas en el mismo sitio.

Además permite la gestión del numero de comensales de un espacio en un tiempo conecreto con lo cual podemos visualizar que mesas o salas se han ocupado con mayor numero de comensales. 
Tambien se pueden generar y gestionar incidencias que puedan ocurrir en las mesas, que impidan la reserva de la misma.

## Comenzando 🚀
Para obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas, usaremos XAMPP para hacer la copia y probar. 
(En el siguiente paso explicaremos como instalar XAMPP). XAMPP nos genera localmente un sevridor LAMP fácil de gestionar para desarrollar comodamente.

Además usaremos GitHub como portal de Git y asi llevar un control de versiones de la aplicación web.
Para ello, es necesario crear una cuenta en GitHub y tener un conocimiento básico de gestion de ficheros en tu sistema operativo.


### Pre-requisitos 📋

Comenzaremos instalando XAMPP para desplegar el entorno de desarrollo. Lo descargaremos primero [Windows](https://www.apachefriends.org/xampp-files/8.0.12/xampp-windows-x64-8.0.12-0-VS16-installer.exe) o [MacOS](https://www.apachefriends.org/xampp-files/8.0.12/xampp-osx-8.0.12-0-vm.dmg)

Una vez lo tengamos instalado, hemos de arrancar los servicios desde el panel de control de XAMPP en el apartado Manage Servers si tenemos el software en inglés o Administrar servicios en español. ![img](https://i.gyazo.com/406d2e3c6268130f0c0b0f49dca9393f.png)

Desde este apartado podemos arrancar o parar servicios e incluso configurar las aplicaciones, modificando puertos o incluso ver los logs que dejan estas aplicaciones.

Igual de importante es instalar el controlador de versions Git, para luego combinar con GitHub. [Windows](https://git-scm.com/downloads#:~:text=macOS-,Windows,-Linux/Unix) o [MacOS](https://git-scm.com/download/mac)

### Instalación 🔧

Una vez tengamos los softwares instalados y con los servicios arrancados como explicado anteriormente, hemos de importar el proyecto a nuestro entorno de desarrollo local.

Para ello iremos al directorio htdocs hubicaod en la raiz de la aplicación XAMPP, una vez estemos posicionados desde el terminal de GIT en este directorio ejecutamos el siguiente comando

```
git clone https://github.com/100007217/PR01.git
```
Ahora deberemos implementar en nuestro servidor de BBDD de XAMPP la base de datos del proyecto. Dentro de la carpeta bd que acabmos de importar desde github se encuentran dos archivos. **bd_bar.sql**, nos permite generar la estructura de la base de datos y **bd_bar_inserts.sql** ejecuta los inserts en la bbdd creada.

Ahora solo irnos a [este enlace](http://localhost/phpmyadmin/) para administrar las bases de datos en XAMPP usando PhpMyAdmin.

En este momento podremos hacer la importacion de dos maneras, podemos copiar el contenido del archivo sql y pegarlo en el campo de texto de SQL o importar directamente el archivo SQL pulsando en la pestaña Importar.
![img](https://i.gyazo.com/9d4eaaf2409b16aa2b5161bf8f0e4274.png)


```
hasta finalizar
```

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_

## Ejecutando las pruebas ⚙️

_Explica como ejecutar las pruebas automatizadas para este sistema_

### Analice las pruebas end-to-end 🔩

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Despliegue 📦

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Andrés Villanueva** - *Trabajo Inicial* - [dannylarrea](https://github.com/dannylarrea)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](#fulanito-de-tal)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.
