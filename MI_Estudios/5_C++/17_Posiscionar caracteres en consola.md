
Posiscionar caracteres en cordendas de la consola




#include<stdio.h>
#include<windows.h>


int main() {
	HANDLE hCon; //Define variable cono handle
	hCon = GetStdHandle(STD_OUTPUT_HANDLE); // hace que pueda acceder la salida de la consola
	COORD dwPos; //Define faviable con coord
	dwPos.X = 4; //Define cordenadas en x
	dwPos.Y = 5; //Define cordenadas en y


	SetConsoleCursorPosition(hCon, dwPos); // DEfine donde se van a pocicionar los caracteres
	printf("+"); 
	return 0;
}