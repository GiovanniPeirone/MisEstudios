


Local ---> Lo que definas va a ser solo de ese repositorio

Global ---> Para todos los repositorios de un usuario

System ---> Toda la computadora


Modificar Nombre del usuario
--------------------------------------------------------------------------------------

$ git config --global user.name "Giovanni"



Modificar email
-----------------------------------------------

$ git config --gloabal user.email "mgperione@gmail.com"



Para que todas las configuraciones que se puede hacer
----------------------------------------------------------------------------------------------------

$ git config --list

Aparece:
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.name=Giovanni Peirone
user.email=mgpeirone@escuelasproa.edu.ar

si pones git config --global --list Solo se ve las configuraciones globales que hiciste es lo mismo con local y system




Definir el editor de codigo
------------------------------


$ git config --global core.edito "code --wait"

	core.edito ----> Dice que queres definir e editor de codigo
	 code      ----> Es la palabra reserbada reserbada de visual studio code cada editor                       tiene su palabra reserbada 
	 --wait    ----> hace que cuando agrgas un cambio se suba cuando seras el editor de                        codigo 




Poner color
---------------------------------------------------------------------------------------------

$ git config --global color.ui true



Salto de línea 
-----------------------------------------------------------------------------------------------------


$ git config --global  core.autocrlf true












