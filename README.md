# PROYECTO SINTESI IVAN Y ERIC


![image](https://github.com/user-attachments/assets/95c53d50-c4dd-42cc-9314-8967deddd513)




## Memoria del proyecto de síntesis 2 🔝

Nine studios (marca de ropa personal con bases de datos MYSQL y pagina web dinámica)

 ### Introduccion
Nine studios es, una marca de ropa la cual se dedica a vender ropa mediante una tienda online, para crear nuestra tienda online utilizaremos HTML, CSS, JavaScript, PHP y MySQL, todo este contenido sera posible de aprender y aplicar gracias a los profesores, que nos enseñaran a como hacerlo. 

Los objetivos que tenemos con este proyecto son, poder tener nuestra propia pagina web y poder crear nuestra propia marca de ropa. 

El publico objetivo al que nos dirigimos, es a gente joven entre 14 años a 35 años, ya que nos queremos adaptar al mercado de la moda y actualizaros según los estándares de moda, tanto de la gente como de otras marcas que nos diferencian. 

#### Modulos de referencia
los módulos de referencia del ciclo que necesitaremos para este proyecto son: 

Sistemas operativos en red (Maquinas virtuales linux...) 

Servicios de red (DNS y DHCP) 

Seguridad informática (Truenas, Firewall, Nginx) 

Aplicaciones web (HTML y CSS, JavaScript, PHP, MYSQL) 

Conocimientos extra (Pi hole). 

###  _contenido extra_
* [DHCP](https://www.redeszone.net/tutoriales/internet/que-es-protocolo-dhcp/) - EXPLICACION DHCP
* [DNS](https://www.ibm.com/es-es/topics/dns-protocol) - EXPLICACION DNS
* [PHP](https://www.php.net/manual/es/intro-whatis.php) - EXPLICACION PHP
* [PI-HOLE](https://docs.pi-hole.net/main/basic-install) - EXPLICACION PI-HOLE
* [MySQL](https://www.hostinger.es/tutoriales/que-es-mysql) - EXPLICACION MySQL
* [HTML, CSS, JAVASCRIPT](https://dinahosting.com/blog/entendiendo-la-base-del-desarrollo-web-html-css-y-javascript/) - EXPLICACION DESARROLLO WEB




## Objetivos del proyecto ⭐  

_Los objetivos que tenemos con este proyecto son, poder tener nuestra propia página web, poder crear nuestra propia marca de ropa y cumplir con las expectativas de la gente que visualize nuestra idea_

## Las tecnologías a implementar 📲

Las tecnologías por utilizar en nuestro proyecto serían: Ubuntu, Truenas, Pi-Hole, PHP, MySQL. Podemos justificar el uso de estas mismas porque:
-	Ubuntu:  Ubuntu es un sistema operativo que de funciona como Windows , es gratuito y esta basado en Linux , es interesante porque es fácil de usar y seguro además de tener muchas herramientas para programar.

-	Truenas: truenas es un So (sistema operativo) basado en FreeBSD y Linux que permite configurar almacenamiento en red.
Truenas es útil para poder hacer copias de seguridad de nuestra información con el servicio de RSYNC, esto mismo es interesante porque la posibilidad de que nuestra información no se pierda con un sistema propio de copias de seguridad.

-	Pi-Hole: Pi-hole : es como un escudo para tu red que bloquea los anuncios para la red que bloquea los anuncios que molestan antes de que lleguen a la pantalla, Es genial porque hace que la navegación sea más rápida limpia y privada

-	PHP: Es una herramienta que da vida a las páginas web, permitiéndoles hacer cosas dinámicas y interactivas, Es útil porque es fácil de aprender y funciona perfectamente con bases de datos como MySQL 

- MySQL :Es como un archivador gigante pero digital un sistema de base de datos a herramienta básica para manejar información en páginas web y aplicaciones, Es útil porque permite organizar, buscar, y usar datos de forma eficiente 


## Listado de tareas 📋
**_Especificar listado de tareas_**

**_Aprender HTML, CSS_**

**_Aprender JavaScript_**

**_Aprender PHP, MYSQL_**

**_Aprender XAMPP_**

**_Configurar los servers_**

**_Hacer la memoria cada día_**

**_Aprender pi hole_**



## Asignación de roles y responsabilidades del equipo ⭐

|           Iván                  |                 Eric                 | 
| ------------------------------- | -------------------------------------|
| Creación y gestión de sistemas  | Diseño web y gestor de bases de datos|
|Organización, GitHub, trello, Aprender contents anteriormente especificados estar pendiente de trello y GitHub cuando este ausente | GitHub, trello, ayudar a poner al día a Iván cuando este ausente |


## Funcionalidades del equipo
**Iván**:
* Configuración y gestión de sistemas (Linux, DNS, DHCP)
* Copias de seguridad (Truenas)
* Apoyo en desarrollo web (PHP, MySQL)
  
**Eric**:  
* Seguridad (firewall, red)
* Diseño y desarrollo web (HTML, CSS, JavaScript)
* Gestión de bases de datos (MySQL)
*Coordinación de GitHub y Trello

## Diagrama de la red 📡
En el diagrama de red lo que hay es un router conectado a firewall(Pfsense) conectado a la par con un switch ficticio el cual da con todos los servidores, estos mismos son los que van a hecer que mi web funcione.
El primer server es el de dns y dhcp, que lo hemos hecho con pi-hole para que el dhcp no se nos complique a la hora de funcionar, asi matamos dos pajaros de un tiro.
El segundo server es es el de truenas, este servidor nos servira en el futuro para poder hacer copias de seguridad de nuestra informacion.
El tercer server es el de apache, este server nos servira para poder almacenar nuestro contenido html que hagamos en el futuro.
El cuarto server y ultimo sera el de MySQL, Este server nos servira para poder tener bases de datos en nuestra pagina web

![image](https://github.com/user-attachments/assets/42e7eaad-e452-447a-95de-e87dad336c20)




## El hardware a utilizar 🎮



|     Material      |   Componentes    | Caracteristicas       |
| :--- |     :---:        |    ---:  |
| 2 PC CLASE | Intel Core i7 11700, 1 TB de Memoria SSD, 16 GB RAM ddr4 UHD graphics 750 | Windows , Máquinas virtuales Ubuntu |
| PC Iván | Intel Core i5 9400 500 GB de Memoria SSD 16 GB de Memoria RAM ddr4 Nvidia GeForce GTX 960 | Windows, Maquinas virtuales Ubuntu |
| PC Eric | Procesador i5 13400F 32 GB de Memoria RAM 500GB Memoria SSD Nvidia GeForce GTX 1060 |Windows, Maquinas virtuales Ubuntu|


 *El uso de los ordenadores de clase es para poder virtualizar los servidores y guardar el contenido de la web*

_El uso de los ordenadores de casa de los dos es por si no acabamos en clase los contenidos correspodientes en clase_


  ## Los sistemas operativos a utilizar 🌐
  
  
Linux: Utilizaremos Linux como servidores DNS y DHCP porque pensamos que se nos da mejor y terminaremos mas rápido.

Windows: Utilizaremos Windows como sistema operativo Core de nuestro proyecto porque ahí haremos las máquinas virtuales de Linux, el truenas y todo lo que tiene que ver con la web

Truenas: Utilizaremos truenas como servidor de copias de seguridad, porque pensamos que seria buena idea tener guardada nuestra información de forma segura, sin posibilidad de perderla.




## Diagrama de Gantt Nine studios  📃


![image](https://github.com/user-attachments/assets/a8f3e368-dafa-439d-a2c6-27c5111c4191)


# Guias de uso 📃


## kernel

#### ¿Qué es?
El kernel es el núcleo del sistema operativo, responsable de gestionar los recursos del hardware y permitir que el software interactúe con él. Es la parte fundamental que se encarga de tareas como la administración de memoria, la gestión de procesos y la comunicación con los dispositivos del sistema.

#### ¿Por qué es necesario?
Kernel es necesario porque para poder instalar pi-hole necesitamos de actualizar el kernel que tiene la Imagen ISO de ubuntu server

#### ¿Dónde hay información oficial? 
> **SOBRE Kernel**:
> 
> https://es.wikipedia.org/wiki/N%C3%BAcleo_(inform%C3%A1tica)
> 
> https://www.geeknetic.es/Kernel/que-es-y-para-que-sirve
> 

#### Pasos a seguir:
Paso 1
Comprobar la Version del kernel con uname -r

Paso 2
Actualizar los paquetes con sudo apt update && Sudo apt upgrade -y, despues reiniciar con un reboot y comprobar la version nueva para verificar.

Paso 3
Instalar el kernel desde ubuntu mainline con sudo add-apt-repository ppa:cappelikan/ppa -y, despues sudo apt update y sudo apt install mainline -y y hacemos por ultimo un mainline --install-latest.

Paso 4 
Comprobar de que lo tenemos todo correcto con sudo reboot y uname -r



## DNS
DNS es un sistema que traduce nombres de dominio legibles por humanos (como www.google.com) en direcciones IP numéricas (como 142.250.190.46) que los ordenadores utilizan para identificar servidores en la red.

#### ¿Qué es?
DNS  es un sistema de nombres que traduce nombres de dominio en direcciones IP, el cual nos sirve para poder tener nuestro propio dominio web
#### ¿Por qué es necesario?
Es necesario, porque necesitamos de un dominio para nuestra pagina web y para que nuestro nombre de dominio, se transforme en la direccion ip que nosotros le pusimos a nuestro servidor a la hora de buscar por internet.

#### ¿Dónde hay información oficial? 
> **SOBRE DNS**:
> 
> https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio
> 
> https://tools.ietf.org/html/rfc1034
> 

#### Instalación (DNS):
Instalaremos Dns des de pi-hole en una maquina virtual de ubuntu server, despues de instalar la maquina y el pi-hole, configuraremos este mismo para que pueda tener conectividad con el cliente

#### Detalles de la MV:
4096 Mb de ram
3 Procesadores
25 GB de Memoria SSD
Red NAT: NatNST 192.168.1.0
#### Pasos a seguir:
Paso 1
Creacion de la red nat:
Para crear la red nat lo que hay que hacer es, ir a las herramientas de virtualbox, ir a Redes NAT, Crear una red nat con una direccion ip la cual este en la misma red la cual este el servidor, despues tienes que ir al reenvio de puertos, crear uno nuevo, en la direccion anfitrion pones la ip de tu ordenador, en el puerto pones el puerto 80 y en la direccion invitado pones la direccion que tu quieras, pero que este en la misma red que la red nat y la maquina en cuestion.

Paso 2
Instalacion del Curl:
Para empezar, se actualizan los paquetes con sudo apt update y sudo apt upgrade, despues sudo apt install curl -y Para instalar el curl, despues hacemos un curl -sSL https://install.pi-hole.net | bash Para instalar Automaticamente el pi-hole, Esto abrira el instalador interactivo, despues
Elige un servidor DNS: Puedes seleccionar Cloudflare (1.1.1.1), Google (8.8.8.8), Quad9, OpenDNS, etc. (selecciona google y cloudfare)
Selecciona las listas de bloqueo predeterminadas (Dejalo por defecto).
Configura una IP estática para evitar problemas en la red, por ejemplo la de tu servidor.
Habilita la interfaz web para gestionar Pi-hole desde el navegador.
y por ultimo si quieres cambiar la contraseña hazlo con pihole -a -p

Paso 3
configuracion de la web:
Para entrar a la web de pihole tienes que entrar poniendo tu ip anfitrion de la red nat /admin, ejemplo: (100.77.20.22/admin), entonces una vez entras en la web, de las a local dns y despues a dns records, en dns records tienes que poner el nombre de tu dominio y la ip de tu servidor.


## DHCP

#### ¿Qué es?
DHCP es un protocolo de red que asigna automáticamente direcciones IP y otros parámetros de configuración a los dispositivos dentro de una red.
#### ¿Por qué es necesario?
DHCP es necesario Porque el cliente necesita una ip que este en la misma red y proporcionada por el servidor ubuntu en nuestro caso, para saber si el servidor funciona

#### ¿Dónde hay información oficial? 

> **SOBRE DHCP**:
> 
> https://es.wikipedia.org/wiki/DHCP
>
> https://www.digitalocean.com/community/tutorials/what-is-dhcp
>
> https://tools.ietf.org/html/rfc2131


### Configuracion (DHCP):
Para configurar el dhcp necesitamos de haber instalado previamente el ubuntu server con dns y pi-hole, para entonces configurarlo des de pi-hole.

#### Pasos a seguir:
Paso 1
Configuracion pihole:
Con el pihole configurado anteriormente ahora toca configurar el dhcp que tiene pihole. Para configurar el dhcp de pi-hole para empezar dale al apartado de settings, en este apartado le das a DHCP, este mismo te llevara a la configuracion de rangos de ip y de gateway, el rango puedes poner lo que quieras (que este en la misma red) y el gateway pones la 1.1.

Paso 2
Comprobacion mediante cliente:
una vez hecho todo lo anterior, hacemos un ubuntu cliente que configuramos con la misma red nat, habilitamos en la red del ubuntu solo el dns y ya tenemos direccion proporcionada por nuestro servidor.

## Apache

Introducción al servicio 
#### ¿Qué es?
Apache es un servidor web de código abierto que permite alojar sitios web y aplicaciones. Es uno de los servidores web más populares y ampliamente utilizados en la web debido a su fiabilidad, flexibilidad y capacidad para manejar tráfico elevado. Apache puede servir tanto páginas estáticas (HTML) como dinámicas (PHP, Python, etc.).
#### ¿Por qué es necesario?
Apache es necesario porque es la herramienta que permitirá a tu proyecto Nine Studios ofrecer su página web de manera accesible en línea. Actúa como el servidor que gestionará las solicitudes de los usuarios a la tienda online y mostrará el contenido, como los productos y las páginas interactivas de la tienda. 
Además, Apache permite la configuración de archivos .htaccess para mejorar la seguridad, redirección y control de tráfico, lo que facilita la administración de la web.


#### ¿Dónde hay información oficial?
>
> https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04-es#paso-3-comprobar-su-servidor-web
>
>


### Instalacion Apache:
Para instalar poder instalar el apache necesitaremos de dos maquinas virtuales, un cliente y un servidor debian donde podamos guardar nuestro contenido web

#### recomendacion personal
tener instalado ssh para copiar todo el codigo que en el futuro hagamos.

#### Detalles de la MV
Sistema operativo: Debian 12
Recursos recomendados:
Memoria RAM: 1-2 GB 
Disco SSD: 10-20 GB de almacenamiento para la instalación de Apache y los archivos web
Red: Conexión NAT para asegurar la comunicación interna de los servicios dentro de la máquina virtual

#### Pasos a seguir
Paso 1: instalar apache2
Para empezar a instalar apache2 hacemos un sudo apt install apache2, despues para poder comprobar que lo tenemos instalado hacemos un sudo sytemctl status apache2, tambien para que podamos comprobar de que el servidor esta instalado

Paso 2: comprobar que tenemos una web por defecto
Para comprobar que tenemos la web ya creada primeramente hacemos un curl -4 icanhazip.com para que nos de una ip publica para buscar por internet y que nos aparezca la web que hemos creado, despues ponemos la direccion ip por el buscador web y nos aparecera creada por defecto

Paso 3: configurar nuestra web
Para empezar, creamos un dominio web con sudo mkdir /var/www/your_domain.

Despues para darle permisdos de lectura y usuario hacemos un sudo chown -R $USER:$USER /var/www/your_domain y despues un sudo chmod -R 755 /var/www/your_domain.

Posteriormente para editar el archivo de nuestra web, hacemos un sudo nano /var/www/your_domain/index.html.

Antes de nada creamos el archivo.conf para que podamos hacer que nuestra web sea visible en el buscador, despues para editar el dominio (tiene que ser copiado del por defecto) hacemos un sudo nano /etc/apache2/sites-available/your_domain.conf añadiendo nuestro nombre de web personalizado.

despues para habilitar la web hacemos un sudo a2ensite your_domain.conf y para deshabilitar la web por defecto hacemos un sudo a2dissite 000-default.conf.

Por ultimo para comprobar que nuestra web funcione hacemos un sudo apache2ctl configtest, que cuando lo hagamos deberia de dar un syntax OK y despues reiniciamos el servidor apache con sudo systemctl restart apache2.

#### Incidencias

https://www.digitalocean.com/community/tutorials/como-instalar-el-servidor-web-de-apache-en-debian-9-es
Tenemos que saltarnos el paso 2 de la web a la hora de explicarlo




# Diario semanal 📆


#### Desde el 13/01/25 hasta 21/01/25 ✅

Hemos estado haciendo las ideas de nuestro proyecto y las hemos plasmado en una presentación introductoria, también hemos hecho nuestro esquema de red y de proyecto en general, esto nos ha servido para organizarnos para saber por donde tirar en el proyecto, después hemos pensado en usar Pi-Hole como servidor dns y dhcp, pero eso se vera en el futuro a ver como sale.

#### Desde el 22/01/25 hasta 29/01/25 ✅

Lo que hemos hecho ha sido organizar nuestras tareas, especificar nuestros objetivos, especificar nuestras funcionalidades, organizar el proyecto a nivel tanto de recursos de hardware como de software, hacer un diagrama de gantt sobre los tiempos que necesitamos para hacer nuestro proyecto y documentarlo en github

                                
#### Desde el 03/02/25 hasta 10/02/25 ✅

lo que hemos estado haciendo esta semana ha sido empezar y terminar la arquitectura del sistema y empezar con los servidores DNS y DHCP. todavia no hemos terminado por diversos problemas con las maquinas anteriores, uno de estos problemas es que no nos detectaba el nano o que el archivo.yaml estaba vacio y no podiamos hacer nada, entonces solo nos quedaria solventar el problema y terminar el pi hole

#### Desde el 11/02/25 hasta el 17/02/25 ✅
Lo que hicimos durante esta semana fue instalar el pi-hole con servicio tanto de dns como de dhcp, tuvimos un monton de problemas con las maquinas reales, ya que daban mucha guerra y se calentaban mucho y tuvimos que acabarlas en casa, ya despues en la web de pi-hole editamos todo sobre el dns y dhcp del server.

#### Desde el 17/02/25 hasta 24/02/25 ✅
Lo que hemos hecho durante la semana ha sido instalar apache2 y configurarlo para que salga nuestro dominio web con las cosas que nosotros hemos editado, el problema que tuvimos fue, que nos costo un poco entender la estructura del apache y los archivos de este mismo pero pudimos conseguirlo, tan solo quedandonos el php.

## incidencias ❗❗❗
**Sudo nano /etc/netplan/00-installer-config.yaml** - El error que hay a la hora de hacer este comando es que no podemos por alguna razón ver el contenido del archivo (básicamente porque no pone nada) entonces estamos mirando de solucionarlo porque sino no podremos hacer el pi-hole. la solución al error es hacer un sudo apt install nano para instalar el servicio y poder editar el archivo

**PC18495** - Este pc nos ha estado dando problemas  a paso del tiempo, con el almacenamiento, el calentamiento del ordenador, con errores al iniciar maquinas de virtual box, incluso perdimos algunas porque se abortaron.

**web pi-Hole** - lo que nos sucedió fue que cuando instalamos el pi-hole con la actualización del kernel, miramos con la guía de acceder a la web de pi-hole pero con la dirección del servidor, pero se hace simplemente poniendo la ip anfitrión de la red nat con un /admin un ejemplo seria: (100.1.1.1/admin) 


