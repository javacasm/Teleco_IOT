# Redes

##  IPs, Redes y subredes

Cualquier máquina que quiera establecer una conexión a través de Internet  o en una red local debe de tener una dirección IP, que no es más que un identificador inequívoco de la máquina  en la red.

Está formado por 4 números que pueden estar comprendido entre 0 y 255, 32 bits que permiten 4.294.967.296 direcciones distintas

Los primeros 3 números identifican la red y el último al ordenador dentro de ésta

![Esquema red](./images/Esquema_red.png)

Podemos pensar que la red de la izquierda es la 192.168.1.x y la de la derecha 192.168.0.x

Así los ordenadore de cada una serían....

Algunos números se reservan como el 0, el 1 y el 255

Las direcciones de red pueden ser:
* Estáticas: se mantienen en el tiempo
* Dinámicas: cambian de vez en cuando

### Conociendo nuesta red

* En windows: ipconfig

* En Linux: ifconfig

###  Detección de dispositivos en una red, herramientas

Para ver los equipos que hay conectados a una red

(En linux)

        nmap -sP 192.168.1.*

(En Windows)

[http://www.advanced-ip-scanner.com/es/](http://www.advanced-ip-scanner.com/es/)

## Tipos de Dispositivos
  * Router
  * Bridge
  * AP
## Configuración de routers
  * NAT
  * DMZ
## Hosting
