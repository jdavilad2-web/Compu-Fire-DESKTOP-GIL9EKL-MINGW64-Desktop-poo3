# Compu-Fire-DESKTOP-GIL9EKL-MINGW64-Desktop-poo3
#include <iostream>
using namespace std;
class Persona{
	// atributos
	protected : string nombres,apellidos,direccion;
				int telefono;
	// costructor
	protected : 
		Persona(){
		}
		Persona(string nom,string ape,string dir,int tel){
			nombres = nom;
			apellidos = ape;
			direccion = dir;
			telefono = tel;
		}
	
	// metodos
	void mostrar();
	
};
