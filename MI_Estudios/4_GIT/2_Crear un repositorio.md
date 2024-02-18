

Crear repositorio
-----------------------------------------------------------------------------------
$ git init


Subir archivo al repositorio
------------------------------------------------------------------------------------





Ver Archivos que hay dentro de un carpeta
----------------------------------------------------------------------------------------

$ ls

$ ls -a ----> te deja ver las carpetas ocultas ejemplo .git


Accedear a una carpeta
--------------------------------------------------------------------------------------

$ cd e:

	e: ---> hace referencia al disco 
	
Si pones cd podes abrir cualquier carpeta

$ cd ../
vuelve a hacia atras


Crear  y borrar carpetas
---------------------------------------------------------------------------


$ mkdir repo ----> crear carpeta

	mk ---> make
	 dir ---> Directorio
	 repo ---> nombre de la carpeta

$ rmdir  repo ----> remober carpetas

	rm ---> remove


Ver la ruta en la que estas
-------------------------------------------------------------------------------------------
$ pwd



Ver info entre nuestro directorio de trabajo y el area de preparacion
-------------------------------------------------------------------------------------------------
Esto nos va a mostrar lo que se va a subir cuando agámos un cómit
$ git status

con  $ git rm --cached <file> se puede remover de los archivos que vas a comitear

con $ git add <file>                se puede agregar a los archivos que se van a comitear


Se pueden poner varios archivos ej:  $ git rm --cached <file> <file>





Comitear
------------------------------------------------


$ git commit -m "Agregando archivo" 









