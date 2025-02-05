### PROYECTO SINTESI IVAN Y ERIC


![image](https://github.com/user-attachments/assets/95c53d50-c4dd-42cc-9314-8967deddd513)




# Memoria del proyecto de síntesis 2 🔝

Nine studios (marca de ropa personal con bases de datos MYSQL y pagina web dinámica)

 ### Introduccion
#### Briefing
 Hemos decidido hacer una marca de ropa personal porque pensamos que con los conocimientos que nos brindan los profesores de el ciclo, podremos llevar a cabo esta idea, también ellos pueden ayudarnos para que esta idea sea posible. 

Los objetivos que tenemos con este proyecto son, poder tener nuestra propia pagina web y poder crear nuestra propia marca de ropa. 

El publico objetivo al que nos dirigimos, es a gente joven entre 14 años a 35 años, ya que nos queremos adaptar al mercado de la moda y actualizaros según los estándares de moda, tanto de la gente como de otras marcas que nos diferencian. 

#### Modulos de referencia
los módulos de referencia del ciclo que necesitaremos para este proyecto son: 

Sistemas operativos en red (Maquinas virtuales linux...) 

Servicios de red (DNS y DHCP) 

Seguridad informática (Truenas, Firewall, Nginx) 

Aplicaciones web (HTML y CSS, JavaScript, PHP, MYSQL) 

Conocimientos extra (Pi hole). 

#### Recursos extra


 https://www.php.net/manual/es/intro-whatis.php

https://docs.pi-hole.net/main/basic-install

# Objetivos del proyecto ⭐  

_Los objetivos que tenemos con este proyecto son, poder tener nuestra propia página web, poder crear nuestra propia marca de ropa y cumplir con las expectativas de la gente que visualice nuestra idea_

### Listado de tareas 📋
-Especificar listado de tareas

-Aprender HTML, css

-Aprender JavaScript 

-Aprender PHP, MYSQL 

-Aprender XAMPP 

-Configurar los servers 

-Hacer la memoria cada día 

-Aprender todo lo relacionado con Carmen 

-Aprender pi hole








### Asignación de roles y responsabilidades del equipo ⭐

|           Iván                  |                 Eric                 | 
| ------------------------------- | -------------------------------------|
| Creación y gestión de sistemas  | Diseño web y gestor de bases de datos|
|Organización, GitHub, trello, Aprender contents anteriormente especificados estar pendiente de trello y GitHub cuando este ausente (cuestiones médicas)| GitHub, trello, ayudar a poner al día a Iván cuando este ausente (cuestiones medicas)|


## Funcionalidades del equipo

Ivan: 

Eric:

## Diagrama de la red 📡
En el diagrama de red lo que hay es un router conectado a firewall(sophos) y a un DHCP que se usara cuando todos los servidores esten configurados porque el reparto de ips en firewall hace que despues no sea tan dificil de configurar. el propio firewall esta conectado a un switch ficticio que permite conectarse a todos los servidores y a los pcs fisicos, la razon la cual hemos conectado el switch con los pcs reales es porque en los pcs reales es donde se crean los servidores y el firewall. los servidores dns y dhcp nos permite tener direcciones ip para todos los servidores y un dominio para nuestra web, la razon por la cual ponemos dhcp ahora es para que los servidores tengan ip para que a futuro se pueda conectar con el DHCP de firewall. el Truenas nos permitira con rsync tener copias de seguridad de nuestra informacion. el servidor  web (nginx) nos permitira guardar nuestro codigo y poder buscarlo en web. y el servidor MySQL nos servira para tener bases de datos en nuestra web._
![image](https://github.com/user-attachments/assets/6bca9822-9952-4e72-982c-208604c7e697)




## Las tecnologías a implementar 📲

Las tecnologías por utilizar en nuestro proyecto serían: Ubuntu, Truenas, Pi-Hole, PHP, MySQL. Podemos justificar el uso de estas mismas porque:
-	Ubuntu:  Ubuntu es un sistema operativo que de funciona como Windows , es gratuito y esta basado en Linux , es interesante porque es fácil de usar y seguro además de tener muchas herramientas para programar.

-	Truenas: truenas es un So (sistema operativo) basado en FreeBSD y Linux que permite configurar almacenamiento en red.
Truenas es útil para poder hacer copias de seguridad de nuestra información con el servicio de RSYNC, esto mismo es interesante porque la posibilidad de que nuestra información no se pierda con un sistema propio de copias de seguridad.

-	Pi-Hole: Pi-hole : es como un escudo para tu red que bloquea los anuncios para la red que bloquea los anuncios que molestan antes de que lleguen a la pantalla, Es genial porque hace que la navegación sea más rápida limpia y privada

-	PHP: Es una herramienta que da vida a las páginas web, permitiéndoles hacer cosas dinámicas y interactivas, Es útil porque es fácil de aprender y funciona perfectamente con bases de datos como MySQL 

-	MySQL :Es como un archivador gigante pero digital un sistema de base de datos a herramienta básica para manejar información en páginas web y aplicaciones, Es útil porque permite organizar, buscar, y usar datos de forma eficiente 




## El hardware a utilizar 🎮

-	2 ordenadores de clase

Intel Core i7 11700

16 GB RAM ddr4

UHD graphics 750

So: Windows

Máquinas virtuales: Ubuntu


-	1 ordenador (casa Iván:)
  

Intel Core i5 9400

16 GB RAM ddr4

Nvidia GeForce GTX 960

So: Windows

Maquinas virtuales: Ubuntu


- 1 ordenador (casa Eric:)
  

Procesador i5 13400F

32 GB RAM 

500GB SSD

Nvidia GeForce GTX 1060 

So: Windows 10

Maquinas virtuales: Ubuntu




  ## Los sistemas operativos a utilizar
  
  
Linux: Utilizaremos Linux como servidores DNS y DHCP porque pensamos que se nos da mejor y terminaremos mas rápido.

Windows: Utilizaremos Windows como sistema operativo Core de nuestro proyecto porque ahí haremos las máquinas virtuales de Linux, el truenas y todo lo que tiene que ver con la web

Truenas: Utilizaremos truenas como servidor de copias de seguridad, porque pensamos que seria buena idea tener guardada nuestra información de forma segura, sin posibilidad de perderla.






## diagrama de Gantt Nine studios 


![image](https://github.com/user-attachments/assets/a8f3e368-dafa-439d-a2c6-27c5111c4191)


# Diario semanal


## Desde el 13/01/25 hasta 21/01/25 ✅

Hemos estado haciendo las ideas de nuestro proyecto y las hemos plasmado en una presentación introductoria, también hemos hecho nuestro esquema de red y de proyecto en general, esto nos ha servido para organizarnos para saber por donde tirar en el proyecto, después hemos pensado en usar Pi-Hole como servidor dns y dhcp, pero eso se vera en el futuro a ver como sale.

## Desde el 22/01/25 hasta 29/01/25 ✅

Lo que hemos hecho ha sido organizar nuestras tareas, especificar nuestros objetivos, especificar nuestras funcionalidades, organizar el proyecto a nivel tanto de recursos de hardware como de software, hacer un diagrama de gantt sobre los tiempos que necesitamos para hacer nuestro proyecto y documentarlo en github

### 03/02/25 

Hoy lo que hemos hecho ha sido crear nuestra arquitectura de sistema, aun no se ha acabado pero tendremos mas dias para hacerlo

### 05/02/25

Hoy lo que hemos hecho ha sido arreglar un poco el github para que los contenidos esten correctamente, empezar a hacer el server dns y dhcp y arreglar un poco el diagrama de la red

                                

