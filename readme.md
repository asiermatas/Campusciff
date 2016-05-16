
# Repositorio Campus CIF

## 1. Crear un repositorio

_Este repositorio ya lo cree en clase_

De todas maneras se hará así: (Al tabular en el readme te aparecce lo tabulado en gris y resaltado)

	![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/Crear%20repositorio.jpg)

Y saldrá asi

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/Crear%20repositorio.jpg)


# 2. Clonar campus ciff a local

Ponemos el git en la carpeta que vamos a utilizar. Para ello debemos utilizar:

cd .. --> para salir de la carpeta actuala a la superios

cd c --> para ir a C

Y cuando estamos en la carpeta que vamos a utilizar ponemos:

git init

A continuación vamos a apuntar esa carpeta o entorno de trabajo al repositorio Git Hub. Se hace mediante commando:

	git clone git@github.com:asiermatas/Campusciff.git

La dirección es la dirección internet de nuestro repositorio en github.

![Imagen dirección](https://github.com/asiermatas/Campusciff/blob/master/Dreccionrepositorio.jpg)

Sabremos que va bien porque nos pedirá la contraseña de git hub.


# Crear Readme

Lo he creado con el boton derecho del raton en la carpeta en local de campus ciff. También se puede con echo o touch 


# commmit inicial

Voy a subir el readme al staggin el readme.md  y la imagen  con  

	git add -A  

y después al repositorio con un 

	git commit -m "Subir readme.md"  


# Push inicial

Voy a subir con el commando push la imagen y el readme.md

	git add -A                -------> hecho en el punto anterior
	git commit -m "Subir imagen"   --> hecho en el punto anterior

	git push git@github.com:asiermatas/Campusciff.git


# Ignore

## 1. Crear fichero privado

Eso lo hare con el botón derecho ;o)

## 2. Crear carpeta privada

Y esto también :oD

## 3 . Hacer que sea ignorado

Para eso pondre los siguientes pasos:

1. Estando en la carpeta nuestra de trabajo, creamos un ficheo .gitignore en la carpeta ejecutando el comando:
	touch .gitignore
2. Aparecerá un fichero .gitignore en nuestra carpeta (windows) y lo editamos con el bloc de notas. Ahi vamos a poner:
privada.txt   ---> esto es para que ignore el fichero privada.txt
privada/  ---> esto es para que ignore la carpeta privada

A partir de ahhora al subir a staging (git add -A) y hacer commit (git commit -m "subida X") no subira estos dos objetos.

Subo este readme hasta el git hub, ahora que lo acabo de actualizar.

	git add "Readme.md"
	commit -m "subir readme 3"


	push git@github.com:asiermatas/Campusciff.git



# Crear fichero 1.txt

Adivina.... :oP   (sí, lamento confesarme como fan de bill gates) 

y lo subo

	git add "1txt"
	commit -m "subir 1.txt 3"

# Crea tag

Al crer un tag lo que hacemos es asignar un tag al ultimo commit que hemmos hecho. en este caso el del fichero 1.txt. 
Por eso es importante haber subido ya el 1.txt a repositorio local. 

Una ve sudido ejecutamos el commando:

	git tag v0.1

En caso de equivocarnos del tag se puede borrar con:

	git tag -d v01





