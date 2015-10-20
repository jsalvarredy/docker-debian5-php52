# docker-debian5-php52

Contenedor que esta en basado en un Debian 5 que tiene instalado php 5.2.6 con los modulos de mysql y postgres.
Además tiene un servidor de correo postfix para el envio de mail.

## Uso
```
	docker run -d -e MAIL_DOMAIN=ejemplo.com.ar \
	-e USER_ID=`id -u`-v `pwd`:/var/www \
	jsalvarredy/debian5-php52
```
