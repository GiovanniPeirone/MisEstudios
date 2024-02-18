
display: grid; ------> Define que todo sea grid (Se puede ver Inspeccionando y seleccionando el                                        boton de gird)


Colubnas
----------------------------------------------------------------------------------------------


grid-template-columns: ; ----> Los valores que pones adentro define cuantas colubns van a haber                                                    ye el ancho

ej

grid-template-columns: 100px, 100px, 100px ;


Si en ves de un valor pones  AUTO  Se vaa ajustar autamaticamente para que ocupe todo el espacio

ej

grid-template-columns: auto auto auto ;


Fracciones
---------------------------------------------------------------------------------------------

 Fracciones En css grid existe una unidad llamada fraccion (fr) La cual se usa ma en ves de lo px o %


ej

grid-template-columns: 1fr 1fr 1fr ;

Lo que hace es dividir el espacio en fracciones


Filas
--------------------------------------------------------------------------------------------------------


grid-template-rows:  ; -----------> Define el tamaño en largo de las filas

Ej


grid-template-rows: 100px 100px 100px 100px ; 





Importante
--------------------------------------
Aunque no veas la cuadricula puede estar creada


Filas automatica
------------------------------------------------------------------------------------------


grid-auto-rows: 50px ; ------> Las auto rows definen una altura predeterminada de filas en caso de                                                  que no se especifiquen



Con esto se puede hacer lo sgiente:

grid-template-rows: 100px ; 
grid-auto-rows: 50px ;




Propiedad Repeat
----------------------------------------------------------------------------------------------


Con la propiedad repeat nos podemos ahorrar tiempo teniendo que escrivir lo mismo muchas veses 

eje:

En ves de :
grid-template-rows: 1fr 1fr 1fr;


Ponemos:
grid-template-rows: repeat(3, 1fr);



Cosas que se puede hacer
--------------------------------------------------------------------------------------------------
En ves de:
grid-template-rows: 25px 1fr 1fr 1fr);

Hacemos
grid-template-rows: 25px repeat(3, 1fr);


-----------------------

En ves de hacer:
grid-template-rows: 25px 50px 25px 50px 25px 50px;

Hacemos:
grid-template-rows: repeat(3, 25px 50px);



MinMax
-------------------------------------------------------------------------------------------------------------

Con mina max podemos dar un tamaño maximo y un tamaño minimo a las colubnas o a las filas 

grid-template-columns: minmax(100px, 1fr);


Esto dise que el tamanño maximo va a ser de 1fr pero el minimo va a ser de 100px



Column-Gap
-------------------------------------------------------------------------------------------------------------

Column-Gap hace que entre cada columna haya un espacio

ej;

grid-column-gap: 16px;


Row-Gap
-------------------------------------------------------------------------------------------------------------

Row-Gap es lo mismo que  Column-Gap pero para las filas

ej:

grid-row-gap: 16px;



Auto-Fill
-------------------------------------------------------------------------------------------------------------


    grid-template-columns: repeat(

        auto-fill,

        minmax(200px, 1fr)

    );

Auto-Fill hace que las colubnas se uviequen en lo ancho mientras que su ancho sea de 200 o
lo que pongas en em minmax

Auto-Fit
-------------------------------------------------------------------------------------------------------------


El Auto Fit hace lo mismo que auto-fill pero si tenes pocos elementos de todos modos va a ocupar todo el espacio



grid-column-star,end
-------------------------------------------------------------------------------------------------------------

grid-column-start: 1;
grid-column-end: 3;


Con esto se puede definir anta donde llega una cosa en los grids
en este caso en ancho


Atajo mas rapido

grid-column 1 / 3
si colocas las mismas cordenadas se sobreponen

grid-row-star,end
-------------------------------------------------------------------------------------------------------------

grid-row-start: 1;
grid-row-end: 3;

En este caso en largo

Atajo mas rapido

grid-row 1 / 3
si colocas las mismas cordenadas se sobreponen
grid-column-start: span 2;
-------------------------------------------------------------------------------------------------------------

Con span se pude directamente decir lo que ocupa
tamvien se puede usra con grid-row-start: span 2;
 









En caso de duda el video del caual se saco la info es este

https://youtu.be/iTjkiI8QQsM?si=maH3cvvpy0Lar9PQ