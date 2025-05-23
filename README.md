# PROYECTO SINTESI IVAN Y ERIC

![image](https://github.com/user-attachments/assets/c45d1522-5a13-436a-a862-d847fc3b637c)

![image](https://github.com/user-attachments/assets/bfd4d821-666a-49aa-8a1b-cdbe692bbb5d)





## Memoria del proyecto de síntesis 2 🔝

Nine studios (marca de ropa personal con bases de datos MYSQL y pagina web dinámica)

 ### Introducción
Nine studios es, una marca de ropa la cual se dedica a vender ropa mediante una tienda online, para crear nuestra tienda online utilizaremos HTML, CSS, JavaScript, PHP y MySQL, todo este contenido sera posible de aprender y aplicar gracias a los profesores, que nos enseñaran a como hacerlo. 

Los objetivos que tenemos con este proyecto son, poder tener nuestra propia pagina web y poder crear nuestra propia marca de ropa. 

El público objetivo al que nos dirigimos, es a gente joven entre 14 años a 35 años, ya que nos queremos adaptar al mercado de la moda y actualizaros según los estándares de moda, tanto de la gente como de otras marcas que nos diferencian. 

#### Módulos de referencia
Los módulos de referencia del ciclo que necesitaremos para este proyecto son: 

Sistemas operativos en red (Maquinas virtuales linux...) 

Servicios de red (DNS y DHCP) 

Seguridad informática (Truenas, Firewall, Nginx) 

Aplicaciones web (HTML y CSS, JavaScript, PHP, MYSQL) 

Conocimientos extra (Pi hole). 

###  _contenido extra_
* [DHCP](https://www.redeszone.net/tutoriales/internet/que-es-protocolo-dhcp/) - EXPLICACION DHCP
* [DNS](https://www.isc.org/bind/) - EXPLICACION DNS
* [PHP](https://www.php.net/manual/es/intro-whatis.php) - EXPLICACION PHP
* [PI-HOLE](https://docs.pi-hole.net/main/basic-install) - EXPLICACION PI-HOLE
* [MySQL](https://www.hostinger.es/tutoriales/que-es-mysql) - EXPLICACION MySQL
* [HTML, CSS, JAVASCRIPT](https://dinahosting.com/blog/entendiendo-la-base-del-desarrollo-web-html-css-y-javascript/) - EXPLICACION DESARROLLO WEB
* [APACHE](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04-es#paso-5-configurar-hosts-virtuales-recomendado) - EXPLICACION SERVER WEB
* [RSYNC](https://www.hostinger.com/es/tutoriales/rsync-linux) - EXPLICACION RSYNC



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

**_Aprender HTML, CSS_**

**_Aprender JavaScript_**

**_Aprender XAMPP_**

**_Configurar los servers_**

**_Hacer la memoria cada día_**

**_Hacer pfSense_**

## Asignación de roles y responsabilidades del equipo ⭐

|           Iván                  |                 Eric                 | 
| ------------------------------- | -------------------------------------|
|Creación y gestión de sistemas  | Diseño web y gestor de bases de datos|
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

![image](https://github.com/user-attachments/assets/6396137a-5d39-4398-a0b9-516ccf5835b8)






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
> https:www.esedsl.com/blog/que-es-un-kernel-en-informatica-y-su-importancia-para-las-empresas
> 
> https://www.geeknetic.es/Kernel/que-es-y-para-que-sirve
> 

#### Pasos a seguir:
Paso 1
Comprobar la Version del kernel con **_uname -r_**

Paso 2
Actualizar los paquetes con **_sudo apt update && Sudo apt upgrade -y_**, despues reiniciar con **_reboot_** y comprobar la version nueva para verificar.

Paso 3
Instalar el kernel desde ubuntu mainline con **_sudo add-apt-repository ppa:cappelikan/ppa -y_**, despues **_sudo apt update y sudo apt install mainline -y_** y hacemos por ultimo un **_mainline --install-latest_**.

Paso 4 
Comprobar de que lo tenemos todo correcto con **_sudo reboot y uname -r_**



## DNS
DNS es un sistema que traduce nombres de dominio legibles por humanos (como www.google.com) en direcciones IP numéricas (como 142.250.190.46) que los ordenadores utilizan para identificar servidores en la red.

#### ¿Qué es?
DNS  es un sistema de nombres que traduce nombres de dominio en direcciones IP, el cual nos sirve para poder tener nuestro propio dominio web
#### ¿Por qué es necesario?
Es necesario, porque necesitamos de un dominio para nuestra pagina web y para que nuestro nombre de dominio, se transforme en la direccion ip que nosotros le pusimos a nuestro servidor a la hora de buscar por internet.

#### ¿Dónde hay información oficial? 
> **SOBRE DNS**:
> 
> https://www.isc.org/bind/
> 
> https://tools.ietf.org/html/rfc1034
> 

#### Instalación (DNS):
Instalaremos Dns des de pi-hole en una maquina virtual de ubuntu server, despues de instalar la maquina y el pi-hole, configuraremos este mismo para que pueda tener conectividad con el cliente

#### Detalles de la MV:

|     Material      |   Componentes    | sistema operativo     |
| :--- |     :---:        |    ---:  |
| 2 PC CLASE | Intel Core i7 11700, 1 TB de Memoria SSD, 16 GB RAM ddr4 UHD graphics 750 | Windows , Máquinas virtuales Ubuntu |
#### Pasos a seguir:
_Paso 1_

Creacion de la red nat:

Para crear la red nat lo que hay que hacer es, ir a las herramientas de virtualbox, ir a Redes NAT, Crear una red nat con una direccion ip la cual este en la misma red la cual este el servidor, despues tienes que ir al reenvio de puertos, crear uno nuevo, 

en la direccion anfitrion pones la ip de tu ordenador, en el puerto pones el puerto 80 y en la direccion invitado pones la direccion que tu quieras, pero que este en la misma red que la red nat y la maquina en cuestion.


_Paso 2_

Instalacion del Curl:

Para empezar, se actualizan los paquetes con sudo apt update y sudo apt upgrade, despues sudo apt install curl -y Para instalar el curl, despues hacemos un **_curl -sSL https://install.pi-hole.net | bash_** Para instalar Automaticamente el pi-hole, Esto abrira el

instalador interactivo, despues

Elige un servidor DNS: Puedes seleccionar Cloudflare (1.1.1.1), Google (8.8.8.8), Quad9, OpenDNS, etc. (selecciona google y cloudfare)

Selecciona las listas de bloqueo predeterminadas (Dejalo por defecto).

Configura una IP estática para evitar problemas en la red, por ejemplo la de tu servidor.

Habilita la interfaz web para gestionar Pi-hole desde el navegador.

y por ultimo si quieres cambiar la contraseña hazlo con **_pihole -a -p_**


_Paso 3_

configuracion de la web:

Para entrar a la web de pihole tienes que entrar poniendo tu ip anfitrion de la red nat /admin, ejemplo: (100.77.20.22/admin), entonces una vez entras en la web, de las a local dns y despues a dns records, en dns records tienes que poner el nombre de tu dominio y la ip 

de tu servidor.


## DHCP

#### ¿Qué es?
DHCP es un protocolo de red que asigna automáticamente direcciones IP y otros parámetros de configuración a los dispositivos dentro de una red.
#### ¿Por qué es necesario?
DHCP es necesario Porque el cliente necesita una ip que este en la misma red y proporcionada por el servidor ubuntu en nuestro caso, para saber si el servidor funciona

#### ¿Dónde hay información oficial? 

> **SOBRE DHCP**:
> 
> https://https://www.cisco.com/c/en/us/td/docs/iosxr/ncs5500/l2vpn/63x/b-l2vpn-cg/b-l2vpn-cg_chapter_010.html
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
 Apache es esencialmente necesario porque todo lo que hagamos en la web se almacenara en el server apache y tambien esto es importante para poder tener una web con personalidad propia a nivel de creatividad


#### ¿Dónde hay información oficial?
>
> https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04-es#paso-3-comprobar-su-servidor-web
>
>


### Instalacion Apache:
Para instalar poder instalar el apache necesitaremos de dos maquinas virtuales, un cliente y un servidor debian donde podamos guardar nuestro contenido web

#### recomendacion personal
Tener instalado ssh para copiar todo el codigo que en el futuro hagamos.

#### Detalles de la MV
Sistema operativo: Debian 12
Recursos recomendados:
Memoria RAM: 1-2 GB 
Disco SSD: 10-20 GB de almacenamiento para la instalación de Apache y los archivos web
Red: Conexión NAT para asegurar la comunicación interna de los servicios dentro de la máquina virtual

#### Pasos a seguir
Paso 1: instalar apache2
Para empezar a instalar apache2 hacemos un **_sudo apt install apache2_**, despues para poder comprobar que lo tenemos instalado hacemos un **_sudo sytemctl status apache2_**, tambien para que podamos comprobar de que el servidor esta instalado

Paso 2: comprobar que tenemos una web por defecto
Para comprobar que tenemos la web ya creada primeramente hacemos un **_curl -4 icanhazip.com_** para que nos de una ip publica para buscar por internet y que nos aparezca la web que hemos creado, despues ponemos la direccion ip por el buscador web y nos aparecera creada por defecto

Paso 3: configurar nuestra web
Para empezar, creamos un dominio web con **_sudo mkdir /var/www/your_domain_**.

Despues para darle permisdos de lectura y usuario hacemos un **_sudo chown -R $USER:$USER /var/www/your_domain_** y despues un **_sudo chmod -R 755 /var/www/your_domain_**.

Posteriormente para editar el archivo de nuestra web, hacemos un **_sudo nano /var/www/your_domain/index.html_**.

Antes de nada creamos el archivo.conf para que podamos hacer que nuestra web sea visible en el buscador, despues para editar el dominio (tiene que ser copiado del por defecto) hacemos un **_sudo nano /etc/apache2/sites-available/your_domain.conf_** añadiendo nuestro nombre de web personalizado.

despues para habilitar la web hacemos un **_sudo a2ensite your_domain.conf_** y para deshabilitar la web por defecto hacemos un **_sudo a2dissite 000-default.conf_**.

Por ultimo para comprobar que nuestra web funcione hacemos un **_sudo apache2ctl configtest_**, que cuando lo hagamos deberia de dar un **_syntax OK_** y despues reiniciamos el servidor apache con **_sudo systemctl restart apache2_**.

## Pfsense
#### ¿Qué es?

pfSense es un software de codigo abierto utilizado para gestionar y proteger redes. Funciona como un firewall  y router, permitiendo controlar el trafico de internet,proteger la red de ataques y intrusos,y crear VPN 

pf Sense Se basa en el sistema operatibo  FreeBSD, conocido por su seguridad y estabilidad.

#### Entre sus principales características están:
>
>Firewall avanzado: Reglas potentes para filtrar y controlar el tráfico de red.
>
>Enrutamiento: Funciones avanzadas para conectar redes.
>
>VPN: Soporta OpenVPN, entre otros.
>
>Interfaz gráfica: Web intuitiva para gestión y configuración.
>
#### ¿Por qué es necesario?
ofrece muchas funcionalidades avanzadas para gestionar y proteger redes, lo cual puede ser útil para nuestra tienda de ropa, tambien porque pfSense te da un firewall libre de uso y gratis.
#### ¿Dónde hay información oficial?
>
> https://www.pfsense.org/
>
> https://www.gugms.net/pfsense
>
#### Recomendacion personal

#### Detalles de la MV
ISO de pfsense

https://www.pfsense.org/download/

Disco Duro: 10 GB mínimo

Sistema base: BSD / FreeBSD (64-bit)

RAM: 2048 MB

red 1: Modo puente (WAN)

red 2: Adaptador interno o red host-only (LAN)
________________________________________


#### Pasos a seguir
Necesitramos una imagen ISO para la máquina virtual. La imagen ISO de pfSense se puede descargar desde la página oficial: https://www.pfsense.org/download/

- Cuando se haga la descarga, configuramos la red. 

- La configuración de red es importante para el firewall. Seleccionaremos la red y habilitaremos los adaptadores 1 y 2. Configurando el adaptador 1 en adaptodr puente . y el adaptador 2 en red nat.

- iniciamos la máquina virtual  y procederemos a instalar pfsense.

- le damos a instalar pfsense

- Seleccionamos la primera interfaz de la wan

- Este proceso de instalación tardará un tiempo.

- cuando este listo aceptamos y reiniciamos el sistema
![image](https://github.com/user-attachments/assets/5f6cf4dc-ff69-4337-b895-52b154042822)


- Después de reiniciar, es importante eliminar la iso, ya que si no lo haces el proceso de instalación y vuelve a generarse. Por lo tanto, lo que haremos primero es apagar la amquina virtual, y vamos a la configuracion , y eliminamos la ISO, luego la volvemos a iniciar.

- Y ya estaria lista la interfaz principal de pfsense.
 ![image](https://github.com/user-attachments/assets/aebdb669-af17-4c7e-9dac-fcb67c68f84c)

- Ahora, accederemos a la máquina Ubuntu y realizaremos el resto de la configuración.

**Ubuntu:**

nos aseguramos de que el adaptador del Ubuntu 1 esté conectado a la red interna.
Verificamos la dirección IP con el comando *ip a*
Abrimos el navegador y usamos la dirección IP del firewall de la LAN.
Inicie sesión en el sistema con el usuario por defecto de pfsense.

## OpenVPN en pfSense

OpenVPN es una software libre que permite levantar una VPN. este mismo permite crear certificados digitales de autenticación de clientes, así como autenticarnos con usuarios y contraseñas. 
Todo el tráfico es cifrado sin importar si la red es por cable o inalámbrica.

- Instalar el plugin OpenVPN client
Lo primero es descargar el paquete openvpn-client-export y para ello vamos a System - Package Manager - Available Packages y buscamos el paquete openvpn-client-export y pulsamos en Install.




### Crear la Autoridad Certificadora 
Una CA es una entidad confiable que se encarga de emitir y gestionar certificados digitales necesarios para realizar transacciones seguras y firmas electrónicas
Accedemos a la interfaz de pfSense y vamos a System - Certificate Manager, luego hacemos clic en Add.
Generamos el certificado dejando las configuraciones predeterminadas, pero asignando un nombre que pueda diferenciarse.

- Creamos el certificado manteniendo casi todas las opciones por defecto y asignando un nombre.
  
| opcion  | descripcion |
| ------------- | ------------- |
| Descriptive name  | OpenVPN_CA  |
| Common name | OpenVPN_CA  |


Una vez realizado los cambios y guardando nos aparecera nuestro certificado ya hecho.


### Crear el certificado para el servidor OpenVPN
En la sección System - Certificates, seleccionamos Add Certificate para crear uno nuevo.

| opcion  | descripcion |
| ------------- | ------------- |
| Method  | create an internal certificates  |
| Descriptive name | OpenVPN_Certificates  |
| Common Name | OpenVPN_Certificates  |
| Certificate type | Server certificate   |

Aquí nos tiene que aparecer nuestra CA ya creada


### Configuración del servidor OpenVPN

- Ahora, configuramos el servidor OpenVPN el cual los clientes se conectarán. Para ello, vamos a VPN - OpenVPN - Servers y hacemos clic en Add. Rellenamos los siguientes campos:


| opcion  | descripcion |
| ------------- | ------------- |
| Description | OPENVPN_Server  |
| Descriptive name | Remote Access (SSL/TLS + User Auth)  |
| Protocol | UDP on IPv4 only   |
| Interface | WAN   |
| Puerto | 5194 (cambiamos el puerto por defecto)  |
|Peer Certificate Authority | OpenVPN_CA (seleccionamos el nuestro) |
| Server certificate | OPENVPN_Certificate (Server: Yes, CA: OPENVPN_CA)   |

- En la sección de redes, seleccionamos la subred 10.4.44.0/24 (en este caso) para la conexión entre el cliente y pfSense. Además, configuramos las redes o IPs a las cuales los clientes tendrán acceso una vez conectados por VPN.

- A continuación, activamos la opción Redirect IPv4 Gateway: Force all client-generated IPv4 traffic through the tunnel, para asegurar que todo el tráfico pase por la VPN.

- También, podemos habilitar la opción Inter-client communication para permitir la comunicación entre clientes de la VPN y Duplicate connection para permitir múltiples conexiones del mismo cliente.
  
podemos asignar los servidores DNS que los clientes utilizaran:

- DNS Server 1: 1.1.1.1
- DNS Server 2: 8.8.8.8
  
Guardamos la configuración y ya estaria listo.

### Verificar el servicio
- Para comprobar que todo esta funcionando, vamos a Status - Services, donde podremos revisar los servicios activos, incluidos los recién habilitados

![image](https://github.com/user-attachments/assets/dc9fc701-0a32-415a-b6a5-73d3ccf68543)

### Configuración de reglas en el firewall
A continuación, debemos configurar una regla en el firewall para permitir el acceso a través del puerto de la VPN  Vamos a Firewall - Rules - WAN y hacemos clic en Add para crear la nueva regla.

![image](https://github.com/user-attachments/assets/5ca171b9-4ad3-42cc-b948-26f209f000f5)

| opcion  | descripcion |
| ------------- | ------------- |
| Action  | Pass  |
| Interface | WAN |
| Protocol | UDP  |
|Source | Any   |
| Destination | Any  |
|Destination port range | 5194 |
| Logs |Seleccionamos la opción de guardar |
| Description |OPENVPN:RULE|

- Una vez configurada  la regla deberia aparecer en la lista de reglas.


### Crear una regla para permitir todo el tráfico VPN
Ahora vamos a la pestaña de OpenVPN y creamos una regla para permitir todo el trafico entre clientes de la VPN. Seleccionamos todos los protocolos (ANY) y permitimos la comunicación entre cualquier origen y cualquier destino
Guardamos la configuración y la regla quedará creada.

### Exportar el archivo de configuracion para los clientes
Para crear un cliente de la VPN, primero necesitamos generar un usuario. Nos dirigimos a System - User Manager y creamos un nuevo usuario. Al crear el usuario, seleccionamos la opción Click to create a user certificate para generar el certificado del cliente.


- Una vez creado el usuario, vamos a VPN - OpenVPN - Client Export, donde veremos el usuario recién creado. Desde alli podremos exportar el archivo de configuración.

![image](https://github.com/user-attachments/assets/b09856b3-0798-4047-829a-3f403cd70378)


### Comprobar estado del servicio y de los clientes conectados
- Si queremos hacer una prueba  podemos descargar el certificado para Android o el de OpenVPN for android y nos lo mandamos por correo electronico.
- Cuando lo tengamos abriremos el archivo desde la aplicacion openVPN for andriod, y este Nos llevará a este apartado donde le daremos a ADD para importar el perfil. 
 
- Nos pedira que pongamos el usuario y contraseña, Y ya tendriamos el VPN activo.

Una vez conectados, podemos comprobar la conexion realizando pruebas, como acceder al firewall a través de un navegador para verificar que todo funciona correctamente
- Vamos al navegador y escribimos la IP
  
![image](https://github.com/user-attachments/assets/cf5b8421-124c-4659-ba0c-9e6b4e45f6cd)

Ya podemos comprobar la conexión al firewall. Esto mismo nos permitira en un futuro buscar nuestra web en el telefono y poder verla desde ahi gracias a nuestro servidor pfsense.












#### Incidencias


## Truenas
#### ¿Qué es?
TrueNAS es un sistema operativo basado en FreeBSD que da servicios de almacenamiento en red y proporciona copias de seguridad mediante rsync.

#### ¿Por qué es necesario?
TrueNAS es necesario para que nosotros podamos a nivel de empresa guardar toda nuestra informacion porque si sucede un accidente o nos roban toda nuestra informacion no podremos recuperar nuestra informacion, es por eso que usamos truenas, para que nuestra informacion este a salvo.

#### ¿Dónde hay información oficial?
>
> https://www.truenas.com
> 
> https://www.itelca.com.co/truenas-vs-freenas-y-por-que-deberia-actualizar/
>

#### Detalles de la MV

|     Material      |   Componentes    |
| :--- |     :---:        | 
| nº maquinas | 2 maquinas iguales |
| Redes | Red nat |
| Discos duros | 2 Raid 1 y 2 discos para el arranque de ambas maquinas |
| Memoria RAM | 4096 MB |
| Ip | Maquina 1: 192.168.1.76 |
| Ip | Maquina 2: 192.168.1.91 |

#### Pasos a seguir
Paso 1.

Instalas la iso de truenas que esta en esta web https://www.truenas.com/download-truenas-scale/, despues vas a virtualbox (con la iso instalada) y creas una maquina con freebsd 64 bits.

Paso 2.

Deberas de crear 2 discos vdi (con menos espacio que el primero que se crea por defecto), desde la configuracion en el apartado de almacenamiento, despues de esto vas al apartado de redes en la configuracion y pones una red nat (para comunicar con el resto de servidores) y un adaptador puente (para comunicar con el equipo real).

Paso 3.

Abre la maquina que has creado, para poder instalar el truenas desde la maquina, seleccionas la unidad de arranque, la contraseña y una vez hecho esto cierras la maquina, para poder quitarle la iso y asi ya poder acceder a la interfaz de truenas.

Paso 4.

Ahora clona la maquina para poder tener una maquina igual con la que poder comprobar la funcionalidad de esta misma con el servicio de rsync.

Paso 5.

 Ahora cuando intentes acceder a la interfaz de truenas, para acceder tienes que poner la direccion ip del truenas (ojo, tiene que estar en la misma red), una vez entras tienes que poner como usuario "root" y la contraseña que hayas generado.
 
Una vez en el truenas, buscas pools en storage, ahí te muestra una interfaz en donde puedes poner un nombre a la pool, en la parte del medio están los discos disponibles, dependiendo de cuantos tengas harás un raid 1 o un raid 5, y por la parte de abajo esta la capacidad estimada total de gigas que requiere para crear el pool.

Ahora en el apartado de users en el truenas hay que darle al apartado de add, entonces podrás ver una interfaz donde puedes poner el nombre de usuario que quieras y poner los directorios a los que quieres dirigir tu usuario y sus permisos, Esto mismo nos servira para que cuando hagamos el rsync los archivos se dirijan hacia ese usuario en especifico.

Despues configuraremos los servicios necesarios para poder hacer las copias de seguridad correspondientes

SMB: En el apartado de SMB lo que hay que editar es el "NetBIOS name" que es el nombre de la maquina virtual, y el "workgroup" que es el grupo que tu mismo creaste al hacer el usuario.

SSH: En el ssh para poder usarlo hay que habilitar simplemente el TCP portforwarding para poder hacerlo funcionar, el login por root y la autentificacion de la contraseña ya estan habilitados por defecto.

RSYNC:

![image](https://github.com/user-attachments/assets/508cf5e6-f39f-42f6-aa60-28edd5ae7114)

Para el Rsync lo que hay que hacer es, crear un rsync module, darle un nombre y direccion de archivos con el usuario ya creado, darle acceso de lectura y escritura, darle un numero maximo de conexiones y acceso al grupo y usuario donde quieres que se dirijan las copias de seguridad y con eso ya es suficiente


Paso 6

Rsync task: Para hacer el rsync task, vas al apartado de tasks donde esta el rsync task y una vez le des tendras la opcion de poder crear un rsync task

![image](https://github.com/user-attachments/assets/f5c91820-7e47-4b0f-b0c4-3350e77ff351)

Una vez aqui habra que hacer lo siguiente:

darle la misma direccion de archivos de usuario, pones el usuario correspondiente, en direction tienes la opcion de coger o dar archivos, en este caso como queremos dar archivos le damos a push, que es el equivalente a dar archivos, el horario en este caso ponemos que sea cada semana el domingo.
Para el remote host para que podamos comprobar que funciona el rsync task de momento usamos como prueba otro truenas clonado identico, el rsync module del remote host tiene que ser el que hayamos creado en la otra maquina identica, y con esto solo quedaria comprobarlo y ya lo tendriamos.


Paso 7

cronjob:

Ahora lo que haremos sera combrobar que todo esta correcto con el cronjob y el archivo backup.sh (archivo el cual sirve para dirijir la direccion de otro archivo a cronjob para hacer copias de seguridad).

Entonces comenzamos con el cronjob:

Para el cronjob en el truenas lo que hay que hacer es ir al apartado de tareas y darle a cronjob, una vez hecho esto os mostrara esto: 

![image](https://github.com/user-attachments/assets/ec759f9c-4d80-4fb8-80cd-f26012fc7e2c)

Una vez aqui lo que hay que hacer es mostrale al cronjob la direccion de archivo (de los servidores a hacer copias) para que el truenas lo lea y pueda hacer copias a este mismo, despues poner el usuario indicado, y tambien el horario el cual pondremos cada semana los domingos, entones una vez hecho esto ya podremos hacer las copias des de cronjob.

backup.sh:

Ahora por ultimo lo que haremos sera un backup.sh a cada maquina con la direccion de cada servicio que hemos hecho hasta ahora, un ejemplo de un backup.sh de cualquier servidor seria:

ECHO "INIT"

rsync -avzh nine.conf erick@100.77.20.22: /home/nine.conf/destino/

ECHO "FIN".

Y asi habria que hacer con todos los servidores (aunque con archivos diferentes) para poder tener copias de seguridad completas de lo que tenemos de ahi, asi no lo perdemos.


## Mockup y mapa del sitio

Este es nuestro mockup de como sera nuestra pagina web 


![image](https://github.com/user-attachments/assets/0b86f365-2191-478f-b126-ca625a3d88c5)

![image](https://github.com/user-attachments/assets/411ad80d-bb44-40fd-a6b2-be592b91a02e)

![image](https://github.com/user-attachments/assets/cf66201e-6b02-4f43-a450-d5cd71020b75)

![image](https://github.com/user-attachments/assets/57e047a9-b10b-45b6-b356-6f4eb6680b3c)

### Mapa del sitio

![image](https://github.com/user-attachments/assets/7ca5bfb0-d477-4070-be9d-702c11ee5ea6)

# HTML y CSS

¿Qué es HTML y CSS?
HTML: Es el lenguaje de marcado que estructura el contenido de las páginas web. Define elementos como títulos, párrafos, enlaces, imágenes, formularios, etc.
CSS: Es el lenguaje usado para estilizar el contenido HTML. Controla colores, fuentes, tamaños, diseño, y comportamiento visual de los elementos.
Ambos son la base de todo sitio web, junto con JavaScript.

Detalles del Entorno de Desarrollo
Requisitos mínimos:
Apache2: para alojar la web en el futuro
Editor de código: Visual Studio Code
Navegador: Google Chrome, para probar la web des de ahi.
Sistemas operativos que vamos a usar: Windows y Linux, windows para entorno real y para entorno de apache usaremos linux.

¿Por qué es necesario aprender HTML y CSS?
HTML y CSS son necesarios porque son el estándar para crear sitios web, al igual imprescindibles para cualquier desarrollo web, tambien Permiten crear interfaces visualmente bonitas, responsables y accesibles.


¿Dónde hay información oficial?
https://www.w3schools.com/
https://html.spec.whatwg.org/

Pasos para instalar y comenzar a usar HTML y CSS
1. Instalar Visual studio core
Descarga desde: https://code.visualstudio.com
se Instala como cualquier otro programa
2. Crear tu primer proyecto web
Crea una carpeta (por ejemplo: mi-sitio-web)
Ábrela con VS Code
Dentro, crea un archivo index.html y uno style.css
3. Código básico de ejemplo

#### html


![image](https://github.com/user-attachments/assets/fde6d3d9-604b-40b3-b268-3fdbe68f3534)

Esto es el ejemplo basico de html el cual nos servira para construir nuestro cuerpo de la web

#### css
![image](https://github.com/user-attachments/assets/a0fa3e5b-bba2-46a8-9352-4cfef45ff244)

Este otro es un ejemplo basico de decoracion de nuestro cuerpo web

4. Ver tu sitio en el navegador
Des del visual studio hay una opcion que se llama run, en esta misma puedes abrir debuggeando o sin debuggear, recomiendo usar la primera opcion. Esto nos ayudara para saber si la pagina esta bien hecha o no.


![image](https://github.com/user-attachments/assets/758f7f47-003b-4967-92de-40d6166e02af)
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

#### Desde el 11/03/25 hasta 18/03/25 ✅
Lo que hicimos durante esta semana ha sido acabar el pfsense con openvpn, terminar de probar este mismo y empezar a hacer el truenas con freebsd

## incidencias ❗❗❗
**Sudo nano /etc/netplan/00-installer-config.yaml** - El error que hay a la hora de hacer este comando es que no podemos por alguna razón ver el contenido del archivo (básicamente porque no pone nada) entonces estamos mirando de solucionarlo porque sino no podremos hacer el pi-hole. la solución al error es hacer un sudo apt install nano para instalar el servicio y poder editar el archivo

**PC18495** - Este pc nos ha estado dando problemas  a paso del tiempo, con el almacenamiento, el calentamiento del ordenador, con errores al iniciar maquinas de virtual box, incluso perdimos algunas porque se abortaron.

**web pi-Hole** - lo que nos sucedió fue que cuando instalamos el pi-hole con la actualización del kernel, miramos con la guía de acceder a la web de pi-hole pero con la dirección del servidor, pero se hace simplemente poniendo la ip anfitrión de la red nat con un /admin un ejemplo seria: (100.1.1.1/admin) 


# Esquema de ip de maquinas

Pi-hole
Apache


