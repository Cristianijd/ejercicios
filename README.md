1---------

#include <iostream>

using namespace std;

int main()
{
    cout << "Calcular la tension en Resistensia,donde tiene dos Resistensias en serie"<< endl;
    int R1,R2,V,T,T2;

    cout << "Ingrese el valor de Resistensia1"<<endl;
        cin>> R1;

        cout <<"Ingrese el valor de Resisitencia2"<<endl;
        cin>> R2;

        cout<<"Ingrese el valor del Voltaje"<<endl;
        cin>>V;

        T=R1 /R1+R2;
        T2=T*V;
        cout<<"La tension es de : "<<T2<<endl;

    return 0;
}

2----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "Calcular la Corriente que pasa a traves del Resistor" << endl;

     float I,V,R;

    cout<<"Ingrese el valor del Voltaje"<< endl;
    cin>>V;
     cout<<"Ingrese el valor del Resistensia"<< endl;
    cin>>R;

   I=V/R;

    if(R>0){

        cout<<"El valor de la Corriente es : "<<I<<endl;

        }
       else {
        cout<<"ERROR ingrese bien el valor de la Resistensia";

        }

    return 0;
}

3-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "Cual es la Potencia Disipada " << endl;

    float P,I,R;
    cout<<"Ingrese el valor de Corriente"<<endl;
    cin>>I;
    cout<<"Ingrese el valor de la Resistensia"<<endl;
    cin>>R;

    if(R>0){
        P=I*I*R;
        cout<<"El valor de la Potencia Disipada es :" <<P<<endl;
    } else{
        cout<<"ERROR el valor de resistencia no es valido"<<endl;
    }
    return 0;
}

4---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "Capacidad total del Circuito" << endl;

    float C1,C2,CT,Ctotal ;

    cout<<"Ingrese el valor del Circuito 1:"<<endl;
    cin>>C1;

    if(C1>0){
        cout<<"Ingrese el valor del Circuito 2:"<<endl;
        cin>> C2;

        if(C2>0){
            CT=1/C1+1/C2;
            Ctotal=1/CT;
            cout<<"El total del circuito es : " <<Ctotal<< "Faradios" <<endl;

        }else{cout<<"ERROR Ingrese el valor correcto del Circuito "<<endl;
        }
    }else{cout<<"ERROR Ingrese el valor correcto del Circuito "<<endl;
    }

    return 0;
}


5---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "Cual es la tension de salida" << endl;
    float V,T,GV;

    cout<<"Ingrese el valor de voltaje:"<<endl;
    cin>>V;

    cout<<"Ingrese el valor de GV:"<<endl;
    cin>>GV;

    T=V*GV;

    cout<<"El valor de la tension de salida es :"<<T<<endl;


    return 0;
}


6---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "Cual es la Corriente que fluye por el Circuito" << endl;
    float R1,R2,V,I,Rtotal;

    cout<<"Ingrese el valor de la Resisitensia 1 :"<<endl;
    cin>>R1;

    if(R1>0){
        cout<<"Ingrese el valor de la Resistencia 2 :"<<endl;
        cin>>R2;
        if(R2>0){
            Rtotal=R1+R2;
            cout<<"El Corriente es : "<<Rtotal<<endl;
        }else{cout<<"ERROR Ingrese Correctamente el Valor de la Resisistencia"<<endl;
        }
    }else{cout<<"ERROR Ingrese Correctamente el Valor de la Resisistencia"<<endl;
    }
    return 0;
}

7---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "Calcular la Potensia Disipada por el Resistidor" << endl;
    float P,V,R;

    cout<<"Ingrese el valor de Voltios:"<<endl;
    cin>>V;

    cout<<"Ingrese el valor de la Resistensia :"<<endl;
    cin>>R;

    if(R>0){
        P=V*V/R;
        cout<<"El valor de la Potensia Disipada es :"<<P<<endl;

    }else{cout<<"ERROR el valor de la Resistencia es 0"<<endl;
    }
    return 0;
}

8---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "Calcular la Tension en la Resistencia conectada" << endl;

    float V1,V2,VR;

    cout<<"Ingrese el valor de Voltio 1 :"<<endl;
    cin>>V1;

    cout<<"Ingrese el valor de Voltio 2 :"<<endl;
    cin>>V2;

    if(V2>V1){
        VR=V2-V1;
        cout<<"La tension en la Resistensia es :"<<VR<<endl;

    }else{cout<<"ERROR no se puede calcular por los valores"<<endl;
    }
    return 0;
}

9---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "Calcular cual es la Corriente" << endl;
    float V,I;
    int R;

    R=250;
    cout<<"Ingrese el valor de Voltios"<<endl;
    cin>>V;

    I=V/R;
    cout<<"La corriente es :"<<I<<endl;



    return 0;
}

10---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include <iostream>

using namespace std;

int main()
{
    cout << "se cumple la ley de Kichhoff" << endl;

    float A1,A2,Suma;

    cout<<"Ingrese el valor de Variable 1"<<endl;
    cin>>A1;

    cout<<"Ingrese el valor de Variable 2"<<endl;
    cin>>A2;

    Suma=A1+A2;

    if(A1+A2>0){
        cout<<"La ley no se cumple";

    }else{cout<<"La ley  se cumple";
    }

    return 0;
}








