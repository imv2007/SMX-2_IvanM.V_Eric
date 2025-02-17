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
En el diagrama de red lo que hay es un router conectado a firewall(sophos) y a un DHCP que se usara cuando todos los servidores esten configurados porque el reparto de ips en firewall hace que despues no sea tan dificil de configurar. el propio firewall esta conectado a un switch ficticio que permite conectarse a todos los servidores y a los pcs fisicos, la razon la cual hemos conectado el switch con los pcs reales es porque en los pcs reales es donde se crean los servidores y el firewall. los servidores dns y dhcp nos permite tener direcciones ip para todos los servidores y un dominio para nuestra web, la razon por la cual ponemos dhcp ahora es para que los servidores tengan ip para que a futuro se pueda conectar con el DHCP de firewall. el Truenas nos permitira con rsync tener copias de seguridad de nuestra informacion. el servidor  web (nginx) nos permitira guardar nuestro codigo y poder buscarlo en web. y el servidor MySQL nos servira para tener bases de datos en nuestra web._

![image](https://github.com/user-attachments/assets/518b5c70-3ba5-487b-90fa-ec89dccd82ba)



## El hardware a utilizar 🎮



|     Material      |   Componentes    | Caracteristicas       |
| :--- |     :---:        |    ---:  |
| 2 PC CLASE | Intel Core i7 11700, 1 TB de Memoria SSD, 16 GB RAM ddr4 UHD graphics 750 | Windows , Máquinas virtuales Ubuntu |
| PC Iván | Intel Core i5 9400 500 GB de Memoria SSD 16 GB de Memoria RAM ddr4 Nvidia GeForce GTX 960 | Windows, Maquinas virtuales Ubuntu |
| PC Eric | Procesador i5 13400F 32 GB de Memoria RAM 500GB Memoria SSD Nvidia GeForce GTX 1060 |Windows, Maquinas virtuales Ubuntu|


 *El uso de los ordenadores de clase es para poder virtualizar los servidores y guardar el contenido de la web*

_El uso de los ordenadores de casa de los dos es por si no acabamos en clase los contenidos correspodientes en clase_


  ## Los sistemas operativos a utilizar
  
  
Linux: Utilizaremos Linux como servidores DNS y DHCP porque pensamos que se nos da mejor y terminaremos mas rápido.

Windows: Utilizaremos Windows como sistema operativo Core de nuestro proyecto porque ahí haremos las máquinas virtuales de Linux, el truenas y todo lo que tiene que ver con la web

Truenas: Utilizaremos truenas como servidor de copias de seguridad, porque pensamos que seria buena idea tener guardada nuestra información de forma segura, sin posibilidad de perderla.




## Diagrama de Gantt Nine studios 


![image](https://github.com/user-attachments/assets/a8f3e368-dafa-439d-a2c6-27c5111c4191)


# Guias de uso


## kernel

#### ¿Qué es?


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
Para empezar, se actualizan los paquetes con sudo apt update y sudo apt upgrade, despues sudo apt install curl -y Para instalar el curl, despues hacemos un curl -sSL https://install.pi-hole.net | bash Para instalar Automaticamente el pi-hole

## DHCP

#### ¿Qué es?
DHCP es un protocolo de administración de red que automatiza el proceso de asignación de direcciones IP a dispositivos en una red.

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





# Diario semanal


#### Desde el 13/01/25 hasta 21/01/25 ✅

Hemos estado haciendo las ideas de nuestro proyecto y las hemos plasmado en una presentación introductoria, también hemos hecho nuestro esquema de red y de proyecto en general, esto nos ha servido para organizarnos para saber por donde tirar en el proyecto, después hemos pensado en usar Pi-Hole como servidor dns y dhcp, pero eso se vera en el futuro a ver como sale.

#### Desde el 22/01/25 hasta 29/01/25 ✅

Lo que hemos hecho ha sido organizar nuestras tareas, especificar nuestros objetivos, especificar nuestras funcionalidades, organizar el proyecto a nivel tanto de recursos de hardware como de software, hacer un diagrama de gantt sobre los tiempos que necesitamos para hacer nuestro proyecto y documentarlo en github

                                
#### Desde el 03/02/25 hasta 10/02/25 ✅

lo que hemos estado haciendo esta semana ha sido empezar y terminar la arquitectura del sistema y empezar con los servidores DNS y DHCP. todavia no hemos terminado por diversos problemas con las maquinas anteriores, uno de estos problemas es que no nos detectaba el nano o que el archivo.yaml estaba vacio y no podiamos hacer nada, entonces solo nos quedaria solventar el problema y terminar el pi hole

#### 11/02/25 
Hoy intentamos avanzar con los servidores de dns y dhcp pero tuvimos distintos problemas con los pcs de clase porque el estabamos ejecutando la maquina desde el disco duro, entonces acabaremos las maquinas en casa

#### 12/02/25
El dia anterior lo que hice en casa fue instalar el pi-hole con todo el procedimiento necesario, y hoy en clase lo que hemos hecho ha sido terminar de instalarlo, configurarlo y probarlo en un equipo cliente 


## incidencias
**Sudo nano /etc/netplan/00-installer-config.yaml** - El error que hay a la hora de hacer este comando es que no podemos por alguna razón ver el contenido del archivo (básicamente porque no pone nada) entonces estamos mirando de solucionarlo porque sino no podremos hacer el pi-hole. la solución al error es hacer un sudo apt install nano para instalar el servicio y poder editar el archivo

**PC18495** - Este pc nos ha estado dando problemas  a paso del tiempo, con el almacenamiento, el calentamiento del ordenador, con errores al iniciar maquinas de virtual box, incluso perdimos algunas porque se abortaron.

**web pi-Hole** - lo que nos sucedió fue que cuando instalamos el pi-hole con la actualización del kernel, miramos con la guía de acceder a la web de pi-hole pero con la dirección del servidor, pero se hace simplemente poniendo la ip anfitrión de la red nat con un /admin un ejemplo seria: (100.1.1.1/admin) 


