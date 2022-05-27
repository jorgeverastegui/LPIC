# Localización e Internacionalización
## Áreas claves de conocimiento
* Configurar los ajustes locales, y las variables de entorno.
* Configurar los ajustes de zonas horarias, y las variables de entorno.

## Lista parcial de archivos, términos y utilidades  usadas.
* /etc/timezone
* /etc/localtime
* LC*
* LC_ALL
* LANG
* TZ
* /usr/bin/locale
* tzselect
* timedatectl
* date
* UTF-8
* ISO-8859

## Zona Horaria
En los sistemas Linux puedes utilizar los comandos ***date*** y ***cal*** para conocer  la fecha y el calendario respectivamente. 
El formato de ***date*** se puede especificar con un mascara, pero por defecto nos especifica la sona horaria relativa a la hora UTC (Coordinated Universal Time) 
```
date 
vie may 27 13:38:55 -04 2022
```  
En los sistemas modernos tenemos un comando especifico para manejo del hora y la fecha de nuestro sistema.
```
[user@virtual01 /]$ timedatectl 
      Local time: vie 2022-05-27 13:41:22 -04
  Universal time: vie 2022-05-27 17:41:22 UTC
        RTC time: vie 2022-05-27 17:41:22
       Time zone: America/La_Paz (-04, -0400)
     NTP enabled: yes
NTP synchronized: yes
 RTC in local TZ: no
      DST active: n/a
``` 
