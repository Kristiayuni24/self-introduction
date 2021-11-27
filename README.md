# self-introduction
#include <ncurses\ncurses.h>
using namespace std;

int main()
{
	/* Nama  : Kristi Ayuni
	   NPM   : 2117051097
	   Kelas : B Ilmu Komputer
	*/
	
    initscr(); //start
    
    char a[500];//a=nama
	char b[500];//b=alamat
	char c[500];//c=hobi
	
	getstr (a);//input nama
	getstr (b);//input alamat
	getstr (c);//input hobi

	printw ("\nNama    :  ");
	printw (a);//output nama
	printw ("\nAlamat  :  ");
	printw (b);//output alamat
	printw ("\nHobi    :  ");
	printw (c);//output hobi

	getch();//menjeda tampilan sampai menekan tombol apapun

	endwin();//end 
	
}
