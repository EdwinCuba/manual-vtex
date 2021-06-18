# VTEX

## Primeros pasos con Vtex
Para empezar a usar vtex debemos tener una cuenta, para ello debemos solicitarlo a nuestro a jefe de area.

Cuando ya tengamos una cuenta lista podremos empezar:

1. Empezaremos creando el directorio que almacenara nuestro desarrollo e ingresando a él.
2.  Ahora instalaremos vtex. Para ello es necesario tener instalado [yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable).
3. Instalaremos Vtex goblalmente.
	```
	$yarn global add vtex
	```
4. El siguiente paso sera loguearnos en vtex con el usuario que nos brinde nuestro jefe de area.
	```
	$vtex login <user>
	```
5. Si el logueo fue exitoso denera aparecernos una informacion de este estilo 
	![](https://i.ibb.co/JsKBgKT/vtex-login.png).
6.  Ahora debemos crear un workspace para no afectar a Master.
	```
	$vtex use <workspace>
	```
7. Procederemos a iniciar nuestro proyecto con vtex.
	```
	$vtex init
	```
8. De las opciones que nos aparezcan deberemos dar Enter sobre "Store".
8. Esto creará una nueva carpeta con un diseño base de vtex.
10. Accedemos a la carpeta creada y ejecutamo el comando para linkear nuestro desarrollo.
	```
	$vtex link
	```
