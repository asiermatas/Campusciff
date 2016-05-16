
# Repositorio Campus CIF

## 1. Crear un repositorio

_Este repositorio ya lo cree en clase_

De todas maneras se hará así:

	![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/Crear%20repositorio.jpg)


# 2. Clonar campus ciff a local

Ponemos el git en la carpeta que vamos a utilizar. Para ello nos utilizamos:

cd .. --> para salir de la carpeta actuala a la superios

cd c --> para ir a C

Y cuando estamos en la carpeta que vamos a utilizar ponemos:

git init

A continuación vamos a apuntar esa carpeta o entorno de trabajo al repositorio Git Hub. Se hace mediante commando:

	git clone git@github.com:asiermatas/Campusciff.git

La dirección es la dirección internet de nuestro repositorio en github.


# Crear Readme

Lo he creado con el boton derecho del raton en la carpeta en local de campus ciff. También se puede con echo o touch 


# commmit inicial

Voy a subir el readme al staggin con  git add -A  readme.md  y la imagen y después al repositorio con un git commit -m "Subir readme.md"  

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






