---
layout: default
---

[volver](./)

* [Bloqueos DNS y censura en la red](#bloqueos-dns-y-censura-en-la-red)
* [Fundació puntCAT: El organismo que regula los nombres de dominio](#fundació-puntcat-el-organismo-que-regula-los-nombres-de-dominio)
* [Enlaces externos](#enlaces-externos)

# Bloqueos DNS y censura en la red

![](images/manual_mesas_electorales.PNG)

La primera web del referéndum [referendum.cat](http://referendum.cat/) (dirección IP de red 2.22.126.197) fue cerrada por orden judicial el 13 de Septiembre, sólo seis días después de su publicación, sólo hay que ver el aspecto que sigue ofreciendo hoy en día (por cierto, necesitan un diseñador Web de forma urgente):

![](images/referendum_cat_blocked.png)

Esta Web tenía como propósito informar sobre la consulta, la orden de bloqueo de la Web proviene del juzgado de instrucción número 13 a petición de la GC (parece que la empresa que aloja la Web es [10dencehispahard S.L. (CDmon.com)](https://www.cdmon.com/es/)) y Akamai Technologies.

![](images/referendum_cat_whois.PNG)

**Como era de predecir (para todxs excepto lxs informáticxs del gobierno de Madrid parece) surgen clones de la Web original**, la medida judicial solo alimenta una respuesta más virulenta casi imposible de detener ya. Es imposible ponerle puertas al campo. 

![](images/tweets_gobern_nueva_ref1oct_cat.PNG)

Inmediatamente se hicieron  públicas **dos direcciones alternativas**.

**[ref1oct.eu](https://www.ref1oct.eu/)**  (IP 35.201.78.139) con dominio de la unión europea (EU=European Union) esta registrada por la empresa [EuroDNS S.A](https://www.eurodns.com/) con sede en Luxemburgo ([Google maps](https://goo.gl/maps/kKnoa9WJq4R2)). Actualmente esta Web esta inaccesible.  	 

![](images/ref1oct_eu_404.png)

Una consulta [Whois](https://whois.net/) muestra algunos datos sobre la empresa que registra el nombre, [Xabier Buck](https://www.linkedin.com/in/xavierbuck/) solo es un directivo de la empresa EuroDNS que ofrece servicios de alojamiento a miles de otras Webs.  

![](images/eurodns_whois.png)

La segunda Web espejo es **[ref1oct.cat](https://www.ref1oct.cat/)** (IP 2.20.44.196) y se encuentra intervenida por autoridad judicial como la original. Se pueden obtener más datos del registrante del nombre ref1oct.cat realizando una [consulta Whois en fundacio.cat](http://fundacio.cat/es/whois).

![](images/ref1oct_cat_whois.PNG)

![](images/jamestuber_domains.PNG)

Parece que el señor jamestuber@gmail.com de GB aparece como el nombre del registrante 


**Se presume que desde Madrid se ordena a ISPs (Internet Service Provider o proveedores de acceso a Internet) que bloqueen el acceso a sitios específicos, sospechamos que se produce un bloqueos DNS.**

[referendum1oct.cat](http://referendum1oct.cat/) Otra de las Webs clonadas.
 

## Fundació puntCAT: El organismo que regula los nombres de dominio

[Fundació puntCAT](http://fundacio.cat/) ([@puntcat](https://twitter.com/puntcat)) es el organismo que de alguna manera regula los nombres de las Webs acabadas con .cat como la citada arriba referendum.cat. Actualmente tiene registrados 112.984 sitios Web con esta terminación ([servidores DNS púbicos](http://servidordenoms.cat/)). 

![](images/fundacion_puntcat_web.png)

puntCAT solo regula los dominios .cat pero tiene un hermano mayor que los regula a nivel mundial y se llama [ICANN](https://www.icann.org/es) (La Corporación de Internet para la Asignación de Nombres y Números con origen en EEUU). puntCAT escribe una misiva al ICANN el 17 de Septiembre [[PDF]](https://www.icann.org/en/system/files/correspondence/lineros-to-marby-17sep17-en.pdf) dirigida a [Göran Marby](https://www.icann.org/profiles/goran-marby) (presidente y CEO de ICANN, hay es nada) informando que el 15 de Septiembre las autoridades judiciales Españolas ordenan bloquear cualquier Web .cat que contenga cualquier información referente al 1 de Octubre. Tachan las prácticas de censura y ataque a la libertad de expresión, la carta está firmada a su vez por [Eduard Martin Lineros](http://fundacio.cat/es/noticias/eduard-martin-lineros-nuevo-director-general-de-la-fundacio-puntcat) CEO y fundador de puntCAT.

![](images/lineros-to-marby-17sep17-en-page-001.jpg)

## ¿Que son los servidores DNS?

De manera algo sencilla, cuando introducimos [referendum.cat](http://referendum.cat/) sólo es un nombre para facilitarnos a los simples mortales recordar un sitio Web, realmente detrás de ese nombre existe una máquina identificada con un número único en Internet (simplificando mucho), como una especie de matricula, en este caso referendum.cat se traduce como “92.122.241.124” Todo ese proceso de conversión de nombre a esa serie de bloques de números separados por puntos lo hacen otras máquinas en Internet llamadas servidores **DNS** (**D**omain **N**ame **S**ystem o Sistema de Nombres de Dominio).

Es muy habitual que nuestro **ISP** (*I*nternet *S*ervice *P*rovider o Proveedor de Servicios de Internet) nos proporcione esos números de los servidores **DNS** que se suelen configurar en nuestra computadora de casa.

## Precedentes en el mundo

![](images/turkey_dns_google.png)

Tristemente la medida no es original y es algo muy predecible por otro lado. En el 2014 el gobierno Turco trata de silenciar la oposición política y toma la misma medida (que escandaloso resulta para algunos cuando esto pasa en Turquía) aplicando el bloqueo DNS.


## Enlaces externos

* [El TSJC pide a empresas documentación sobre la gestión de los ordenadores del 9N](http://www.catalunyapress.es/texto-diario/mostrar/371930/tsjc-pide-empresas-documentacion-sobre-gestion-ordenadores-9n)
* [What is a DNS block and 3 ways to get around it](http://blogjunkie.net/2011/06/get-around-dns-block-filter/)
* [It Took Us Less Than Five Seconds To Get Past The Government's Anti-Piracy Site Blocks](https://www.gizmodo.com.au/2017/02/it-took-us-less-than-five-seconds-to-get-past-the-governments-anti-piracy-site-blocks/)
* [How To Bypass ISP Blocking Of The Pirate Bay And Other Torrent Sites For Free](https://www.lifehacker.com.au/2016/12/how-to-bypass-isp-blocking-of-the-pirate-bay-and-other-torrent-sites-for-free/)
* [DNS Filtering is Essential to the Internet](http://hightechforum.org/dns-filtering-is-essential-to-the-internet/)
* [El Govern abre otra web del referéndum tras el cierre ordenado por un juez](http://www.elmundo.es/cataluna/2017/09/13/59b96a0d22601da7268b45f8.html).
* [Correos ordena no entregar ninguna carta referente al 1-O](http://www.larazon.es/espana/correos-ordena-no-entregar-ninguna-carta-referente-al-1-o-HF15983631?sky=Sky-Septiembre-2017#Ttt1FVU3Frj0kCjH).


[volver](./)