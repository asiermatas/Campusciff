

# Ejercicio Avanzado Clase Big Data Tool Kits

Lo rimero fue ir a ejecutar git y crear un fichero Readme_Avanzado.md para ir anotando lo que se ahce con este ejercicio.
Teclee:

	tocuch Readme_Avanzado.md

Y lo subí con los siguientes comandos una vez más:

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/SubidaRead1.jpg)


__Siguientes pasos del ejercicio__

##  Crear Rama

	git branch v0.2

entramos en la rama

	checkout v0.2

## Añadir fichero

Pues creamos el fichero

	touch 2.txt

Y lo subimos

	git add -A
	git commit -m 2.txt
	git push DIRECCION REPOSITORIO REMOTO (en mi caso git@github.com:asiermatas/Campusciff.git)

Esta ultima orden me da error, ya que no he defindo el repositorio remoto para esta rama. Y me pone:

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/errorpush.jpg)

Así que ejecuto:

	git push --set-upstream git@github.com:asiermatas/Campusciff.git v0.2

me sale este mensaje:

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/okpush.jpg)

Y subo todo.

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/subirrama.jpg)


Y me aparecerá:

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/ramav0.2jpg)


## Merge Directo

Vamos al master del git (para ello salimos de la rama v0.2)

	git checkout maste

__ATENCIÓN: si hemos hecho cambios en algun fichero no podremos salir de la rama. Primero tendremos que subir los ficheros cambiados.__


Y hacemos un merge

	git merge v0.2


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/mergejpg)


Con esto he compiado lo que habia en la rama v0.2 al master

# Merge con conflicto y Arreglar conflicto

El fichero 1.txt lo teniamos creado del ejercicio anterior. En este lo vamos a rellenar con un HOLA

Para ello simplemente uutilizaremos windowws: boton derecho abrir , escribi y guardar. 

Y hacemos el add+commit.

Despues vamos a la rama v0.2

	git checkout v0.2

Y editamos con windows el 1.txt que tenemos ahi.

Este ahora aprecera en blanco, porque dependiendo de en que rama o master enstemos en git bash, y si hemos hecho ya commit. 
Pues entonces tendremos un fichero distion con una visualización distinta.


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/generandoconflicto.jpg)


Ahora al hacer el merge, es decir copiar reciprocamente rama v0.2 y Master, deectará que hay valores distintos en commit en Master y Rama paara 1.txt

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/conflicto1txt2.jpg)

Para resolver el conflicto vamos a wndows abrimos el fichero 1txxt y nos aparecerá donde esta el conflicto.

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/conflicto1txt.jpg)

Yo me decido a dejar el Hola y borro el resto.



# Lista ramas con y sin merge

Ahora mismo mi rama v0.2 yaa esta con merge.

Me voy a crear una nuevva rama: 1.NoMerge

	get branch 1.NoMerge

Y despues salgo a la rama master 

	git checkout master

Y ejeccuto los código:

	git branch --merged
	git branch --no-merged

y me saldra:


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/listado.jpg)


y hago add + commit + push.


# borrar rama

Con el siguiente comando me borro la rama 1.NoMerge

	git branch -d 1.NoMerge

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/del1.jpg)


Con el siguiente comando pongo un tag a la rama v0.2 y después la borro

	git tag v0.2 
	git branch -d 1.NoMerge

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/del2.jpg)

# Listado cambios

Con el siguiente comando listaremos toooooddoooooos los cambios:

	git log

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/cambios1.jpg)


__Y ahora apor las organizaciones.__

Creamos organización

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/org.jpg)


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/org2.jpg)

E invitamos miembros


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/org3.jpg)


Y creamos equipos y añadimo miembros al equipo

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team1.jpg)


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team2.jpg)


Y gestionamos autorizaciones


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team3.jpg)


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team4.jpg)


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team5.jpg)


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team6.jpg)


Creamos un nuevo repositorio en la organizacion. campusciff-tunombredeusuariodegithub.github.io


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team7.jpg)


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team8.jpg)


![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/team9.jpg)