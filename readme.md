
# Repositorio Campus CIF

## 1. Crear un repositorio

_Este repositorio ya lo cree en clase_

De todas maneras se har� as�:

![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/Crear%20repositorio.jpg)


En el fichero reeadme, que veremos m�s adelante, para poner una imagens se utiliza este texto:


	![Imagen Subida](https://github.com/asiermatas/Campusciff/blob/master/Crear%20repositorio.jpg)


 (Al tabular en el readme un texto te aparec en gris y resaltado, tal y como he puesto yo los comandos)


# 2. Clonar campus ciff a local

Ponemos el git en la carpeta que vamos a utilizar. Para ello debemos utilizar:

cd .. --> para salir de la carpeta actuala a la superios

cd c --> para ir a C

Y cuando estamos en la carpeta que vamos a utilizar ponemos (esto es porque yo me cre� una carpeta nueva y para habilitar GIT en ella)

	git init

A continuaci�n vamos a apuntar esa carpeta o entorno de trabajo al repositorio Git Hub. Se hace mediante commando:

	git clone git@github.com:asiermatas/Campusciff.git

La direcci�n es la direcci�n internet de nuestro repositorio en github.

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/Dreccionrepositorio.jpg)

Sabremos que va bien porque nos pedir� la contrase�a de git hub.

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/git push.jpg)


# Crear Readme

Lo he creado con el boton derecho del raton en la carpeta en local de campus ciff. Tambi�n se puede con 

	echo "nombre archivo" > "nombre achivo..txt

o 

	touch nombre archivo


# commmit inicial

Voy a subir al staggin el readme.md  y la imagen  con  

	git add -A  

y despu�s al repositorio con un 

	git commit -m "Subir readme.md"  


# Push inicial

Voy a subir con el commando push la imagen y el readme.md

	git add -A                -------> hecho en el punto anterior
	git commit -m "Subir imagen"   --> hecho en el punto anterior

	git push git@github.com:asiermatas/Campusciff.git


# Ignore

## 1. Crear fichero privado

Eso lo hice con el bot�n derecho ;o)

## 2. Crear carpeta privada

Y esto tambi�n :oD

## 3 . Hacer que sea ignorado

Para eso pondre los siguientes pasos:

1. Estando en la carpeta nuestra de trabajo, creamos un ficheo .gitignore en la carpeta ejecutando el comando:
	touch .gitignore
2. Aparecer� un fichero .gitignore en nuestra carpeta (windows) y lo editamos con el bloc de notas. Ahi vamos a poner:
privada.txt   ---> esto es para que ignore el fichero privada.txt
privada/  ---> esto es para que ignore la carpeta privada

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/git ignore.jpg)

A partir de ahhora al subir a staging (git add -A) y hacer commit (git commit -m "subida X") no subira estos dos objetos.

Subo este readme hasta el git hub, ahora que lo acabo de actualizar.

	git add "Readme.md"
	commit -m "subir readme 3"


	push git@github.com:asiermatas/Campusciff.git



# Crear fichero 1.txt

Adivina.... :oP   (s�, lamento confesarme como fan de bill gates) 

y lo subo

	git add "1txt"
	commit -m "subir 1.txt 3"

# Crea tag

Al crer un tag lo que hacemos es asignar un tag al ultimo commit que hemmos hecho. en este caso el del fichero 1.txt. 
Por eso es importante haber subido ya el 1.txt a repositorio local. 

Una vez subido ejecutamos el commando:

	git tag v0.1

En caso de equivocarnos del tag se puede borrar con:

	git tag -d v01


# cuenta git hub

## poner foto

Pues me he puesto una foto para ello he ido a mi perfil:

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/your profile.jpg)

Y en edit profile he subbido una nueva foto

## doble autentificaci�n y clave publica

Tambi�n enn profile, en security se puede poner una dobe autentificaci�n pero como me pide el tel�fono, pues no lo he hecho.

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/doble.jpg)

La clave publica es en el profile en SSH y ya llo hicimos en clase:

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/SSH.jpg)


# Uso social del git hub

Para esto tuve que ir a la opci�n de explore 

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/explore.jpg)


Y buscar a los 

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/campus.jpg)

Y ah� ya reccurr� al advanced search para hacer una busqueda por dia de creaci�n etc..

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/campus2.jpg)

Y ya entre a sus repositorios  para ponerles estrella y usuarios para seguirlos

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/starred.jpg)


# Tabla

Dibujamos lo siguiente en el fichero readmer



	| Header | Header   | 
	| ------ | --------:| 
	| Nombre |< enlace >|
	| nombre |< enlace >| 


con los signos <> indicamos en el readme.md que es un en lace, y el enlace lo tomamos de la direcci�n web de su perfil

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/enlace.jpg)

As� nos queda:



| Nombre |    Perfil Git Hub                   | 
| ------ | -----------------------------------:| 
| Anna   |< https://github.com/juangarciaciff >|
| Juan   |< https://github.com/annalawrenc    >| 


# A�adir adolfo de colaborador

En el git hub, en nuestro repositorio, en el signo __+__ podemos a�adir un colaborador


![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/colaborador.jpg)


__Bueno y con esto ya...__

![Imagen direcci�n](https://github.com/asiermatas/Campusciff/blob/master/fin.jpg)



