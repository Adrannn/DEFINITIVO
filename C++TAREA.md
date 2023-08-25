#include<iostream>

using namespace std;

int main(){
	
	
	int opc,centi;
	cout<<"Conversor de centimetros"<<endl;
	cout<<"Seleccione 1 para convertir a metros"<<endl;
	cout<<"Seleccione 2 para convertir a yardas"<<endl;
	cout<<"Seleccione 3 para convertir a varas"<<endl;
	cout<<"Seleccione 4 para convertir a pies"<<endl;
	cout<<"Seleccione 5 para convertir a pulgadas"<<endl;
	cin>>opc;
	
	switch(opc){
		case 1: cout<<"Selecciono de centimetros a metros"<<endl;
		cout<<"ingrese la cantidad de centimetros"<<endl;
		cin>>centi;
		if (centi<=0 ){
			cout<<"numero no valido";
				}
			else {
				cout<<"los centimetros ingresados son " << centi << " equivalen a " << centi/100 << " metros "<<endl;
			}break;
			
			
		case 2: cout<<"selecciono de centimetros a yardas"<<endl;
		cout<<"ingrese la cantidad de centimetros"<<endl;
		cin>>centi;
		if(centi<=0){
			cout<<"numero no valido";
		}
		else {
			cout<<"los centimetros ingresados son " << centi << " equivalen a "<< centi/91.44 << " yardas "<<endl;
		}break;
		
		
		case 3: cout<<"selecciono de centimetros a varas"<<endl;
		cout<<"ingrese la cantidad de centimetros"<<endl;
		cin>>centi;
		if(centi<=0){
			cout<<"numero no valido";
		} 
		else {
			cout<<"los centimetros ingresados son "<< centi << " equivalen a " << centi/83.8235 << " varas "<<endl;
			
		}break;
		
		
		case 4: cout<<"selecciono de centimetros a  pies"<<endl;
		cout<<"ingrese la cantidad de centimetros"<<endl;
		cin>>centi;
		if(centi<=0){
		cout<<"numero no valido";
		
		}else {
		cout<<"los centimetros ingresados son "<< centi<< " equivalen a "<< centi/30.48 << " pies "<< endl;
		
		}break;
	
		case 5: cout<<"selecciono de centimetros a pulgadas"<<endl;
		cout<<"ingrese la cantidad de centimetros"<<endl;
		cin>>centi;
		if(centi<=0){
			cout<<"numero no valido";
		}else { 
			cout<<"los centimetros ingresados son "<< centi << " equivalen a " << centi/2.54 << " pulgadas "<< endl;
		}break;
	 default:
	 	cout<<"Ingrese una opcion valida, por favor"<< endl;




	}

	
	
	
	
	
	
	
	return 0;
	
	
}
