

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

# Merge con conflicto

El fichero 1.txt lo teniamos creado del ejercicio anterior. En este lo vamos a rellenar con un HOLA

Para ello simplemente uutilizaremos windowws: boton derecho abrir , escribi y guardar. 

Y hacemos el add+commit.













