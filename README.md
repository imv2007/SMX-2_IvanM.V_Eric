# PROYECTO SINTESI IVAN Y ERIC


![image](https://github.com/user-attachments/assets/95c53d50-c4dd-42cc-9314-8967deddd513)




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
>VPN: Soporta OpenVPN, IPSec, PPTP, entre otros.
>
>Proxy y filtrado web: Control y supervisión de acceso a Internet 
>
>Balanceo de carga y redundancia: Distribuye el tráfico y asegura redundancia en conexiones.
>
>Seguridad: IPS, filtrado de contenido, protección contra ataques DoS.
>
>Interfaz gráfica: Web intuitiva para gestión y configuración.
>
#### ¿Por qué es necesario?
ofrece muchas funcionalidades avanzadas para gestionar y proteger redes, lo cual puede ser útil para nuestra tienda de ropa.
#### ¿Dónde hay información oficial?
>
> https://www.pfsense.org/
>
> https://www.gugms.net/pfsense
>
#### Recomendacion personal

#### Detalles de la MV

#### Pasos a seguir
Necesitramos una imagen ISO para la máquina virtual. La imagen ISO de pfSense se puede descargar desde la página oficial: https://www.pfsense.org/download/
- Seleccionaremos AMD64 ISO.
![image](https://github.com/user-attachments/assets/384da588-b892-494c-883b-e1caa2c6119c)
- Cuando se complete la descarga, abriremos la maquina virtual y haremos clic en nuevo
- Asignaremos un nombre para la máquina virtual, y pondremos la imagen ISO que descargamos, el tipo pondremos BSD y la versión FreeBSD de 64 bits.
- la asignación de recursos, como la memoria base y el disco duro, debe hacerse según los requisitos.
Luego de asignar, al final  haremos click en "Finalizar"

![image](https://github.com/user-attachments/assets/126769ed-32d1-431a-9f48-0a2e76d2595d)


![image](https://github.com/user-attachments/assets/45a17fde-23fb-4029-9aa6-fc94a1cbdda8)

- cuando le demos a finalizar le  hacemos clic en Configuración. 
- La configuración de red es importante para el firewall. Seleccionaremos la red y habilitaremos los adaptadores 1 y 2. Configurando el adaptador 1 en adaptodr puente . y el adaptador 2 en red nat.
  
![image](https://github.com/user-attachments/assets/b2543bb7-8814-4a7d-b11b-0be4044b6bde)

![image](https://github.com/user-attachments/assets/0fefe6d2-580c-4188-a292-25a2f498ff49)

- iniciamos la máquina virtual  y procederemos a instalar pfsense.
  
![image](https://github.com/user-attachments/assets/77258cd9-ac39-4085-b2fd-0bec1e11eb3b)

- clicamos en instalar pfsense
  
![image](https://github.com/user-attachments/assets/271e62a3-45a6-4258-83af-7d3717638287)

- Configurando la configuración de red. Haga clic en ok y continamos
![image](https://github.com/user-attachments/assets/042d6f56-b8a0-451e-bc31-29cb6c489795)
- Hacemos clic en Instalar CE

![image](https://github.com/user-attachments/assets/00e034e2-f977-4457-978b-ba018a2cc43c)


- Seleccionamos el disco para la instalación.
![image](https://github.com/user-attachments/assets/40434bdc-264a-4fdd-8bba-0101135ec94c)

- Seleccionamos la versión actual de pfSense CE, luego haremos clic en Aceptar y contiuar
![image](https://github.com/user-attachments/assets/fbc2aa27-3a56-4be5-afa0-12ffeb86373a)

- Este proceso de instalación tardará un tiempo.

- cuando este listo aceptamos y reiniciamos el sistema
![image](https://github.com/user-attachments/assets/5f6cf4dc-ff69-4337-b895-52b154042822)

![image](https://github.com/user-attachments/assets/ec5f7c21-38dc-46a9-b749-4a965b4c53a8)

- Después de reiniciar, es importante eliminar la imagen adjunta, ya que revierte el proceso de instalación y vuelve a generar la misma pregunta. Por lo tanto, lo que haremos primero es apagar la amquina virtual, y vamos a la configuracion , y eliminamos  la imagen ISO 
luego la volvemos a iniciar.

- Reiniciamos la máquina virtual.

- Y ya estaria listo, La IP está configurada.
 ![image](https://github.com/user-attachments/assets/aebdb669-af17-4c7e-9dac-fcb67c68f84c)

- Ahora, accederemos a la máquina Ubuntu y realizaremos el resto de la configuración.

**Ubuntu:**

nos aseguramos de que el adaptador del Ubuntu 1 esté conectado a la red interna.
Verificamos la dirección IP con el comando *ip a*
Abrimos el navegador y usamos la dirección IP del firewall de la LAN.
Inicie sesión en el sistema con las credenciales predeterminadas de pfsense.

## OpenVPN en pfSense

OpenVPN es una software libre que permite levantar una red privada virtual (VPN). Está basado en SSL/TLS, por lo tanto, permite crear certificados digitales de autenticación de clientes, así como autenticarnos con usuarios y contraseñas. 
Todo el tráfico es cifrado sin importar si la red es cableada (Ethernet) o inalámbrica (802.11), con cifrado WEP/WPA/WPA2 o sin cifrar.

- Instalar el plugin OpenVPN client
Lo primero es descargar el paquete openvpn-client-export y para ello vamos a System - Package Manager - Available Packages y buscamos el paquete openvpn-client-export y pulsamos en Install.

![image](https://github.com/user-attachments/assets/d361c2d4-f9fa-4471-931f-0b9cadf2e76a)


#### Crear la Autoridad Certificadora (CA)
Una CA (Autoridad de Certificación) es una entidad confiable que se encarga de emitir y gestionar certificados digitales necesarios para realizar transacciones seguras y firmas electrónicas
Accedemos a la interfaz de pfSense y vamos a System - Certificate Manager, luego hacemos clic en Add.
Generamos el certificado dejando las configuraciones predeterminadas, pero asignando un nombre distintivo.

- Creamos el certificado manteniendo casi todas las opciones por defecto y asignando un nombre.
  
| opcion  | descripcion |
| ------------- | ------------- |
| Descriptive name  | OpenVPN_CA  |
| Common name | OpenVPN_CA  |


Una vez realizado los cambios y guardando nos aparece nuestro certificado:
![image](https://github.com/user-attachments/assets/675148c9-498e-44eb-a13f-ddc4e96b24b6)

#### Crear el certificado para el servidor OpenVPN
En la sección System - Certificates, seleccionamos Add Certificate para crear uno nuevo.

| opcion  | descripcion |
| ------------- | ------------- |
| Method  | create an internal certificates  |
| Descriptive name | OpenVPN_Certificates  |
| Common Name | OpenVPN_Certificates  |
| Certificate type | Server certificate   |

Aquí nos tiene que aparecer nuestra CA previamente creada

![image](https://github.com/user-attachments/assets/b56cb520-0d2e-4c8b-9f41-39fa09480a3a)

#### Configuración del servidor OpenVPN

Ahora, configuramos el servidor OpenVPN el cual los clientes se conectarán. Para ello, vamos a VPN - OpenVPN - Servers y hacemos clic en Add. Rellenamos los siguientes campos:


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
  
![image](https://github.com/user-attachments/assets/8a4fc4c4-b8a8-4c03-b1a8-375614afcc3d)

podemos asignar los servidores DNS que los clientes utilizaran:

- DNS Server 1: 1.1.1.1
- DNS Server 2: 8.8.8.8
  
Guardamos la configuración y ya estaria listo.

![image](https://github.com/user-attachments/assets/d0bbe730-1bfd-476e-9499-6ed4e833d592)

#### Verificar el servicio
Para comprobar que todo esta funcionando, vamos a Status - Services, donde podremos revisar los servicios activos, incluidos los recién habilitados

![image](https://github.com/user-attachments/assets/dc9fc701-0a32-415a-b6a5-73d3ccf68543)

#### Configuración de reglas en el firewall
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

- Una vez configurada  la regla deberia aparecer en la lista de reglas

![image](https://github.com/user-attachments/assets/366275f5-5c44-496f-8c63-b4c23f6f3c4e)

#### crear una regla para permitir todo el tráfico VPN
Ahora vamos a la pestaña de OpenVPN y creamos una regla para permitir todo el trafico entre clientes de la VPN. Seleccionamos todos los protocolos (ANY) y permitimos la comunicación entre cualquier origen y cualquier destino
Guardamos la configuración y la regla quedará creada.
![image](https://github.com/user-attachments/assets/c719a238-5288-4566-9dff-55a2ea4677a6)






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

## PHP
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


