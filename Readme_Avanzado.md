

# Ejercicio Avanzado Clase Big Data Tool Kits

Lo rimero fue ir a ejecutar git y crear un fichero Readme_Avanzado.md para ir anotando lo que se ahce con este ejercicio.
Teclee:

	tocuch Readme_Avanzado.md

Y lo sub� con los siguientes comandos una vez m�s:

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/SubidaRead1.jpg)


__Siguientes pasos del ejercicio__

##  Crear Rama

	git branch v0.2

entramos en la rama

	checkout v0.2

## A�adir fichero

Pues creamos el fichero

	touch 2.txt

Y lo subimos

	git add -A
	git commit -m 2.txt
	git push DIRECCION REPOSITORIO REMOTO (en mi caso git@github.com:asiermatas/Campusciff.git)

Esta ultima orden me da error, ya que no he defindo el repositorio remoto para esta rama. Y me pone:

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/errorpush.jpg)

As� que ejecuto:

	git push --set-upstream git@github.com:asiermatas/Campusciff.git v0.2

me sale este mensaje:

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/okpush.jpg)

Y subo todo.












