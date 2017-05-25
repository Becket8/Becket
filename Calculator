#include <iostream>
using namespace std;
int wczytajliczbe1()
{
    int liczba1;
do
{
cout << "Wprowadz liczbe 1: ";
cin.clear();
cin.sync();
cin >> liczba1;
if ( cin.good() == false )
cout << "Podano bleda liczbe sprobuj ponownie" << endl;
else
return liczba1;
}while ( cin.good() == false );
}

int wczytajliczbe2()
{
   int liczba2;
 do
    {
    cout << "Wprowadz liczbe 2: ";
    cin.clear();
    cin.sync();
    cin >> liczba2;
    if (cin.good() == false)
    cout << "Podano nieprawidlowa liczbe, sprobuj ponownie" << endl;
    else
        return liczba2;
    }while (cin.good() == false);
}

int main()
{

    {
        int dzialanie;
        int jeden = wczytajliczbe1();
        int dwa = wczytajliczbe2();


            do
                {cout << "Wybierz jedno z dzialan: " << endl << "[1] Dodawanie " << endl << "[2] Odejmowanie " << endl << "[3] Mnozenie " << endl << "[4] Dzielenie " << endl << "[5] Rezygnuj " << endl;
                cout << "Wybrano operacje: ";


    cin.clear();
    cin.sync();
    cin >> dzialanie;
    if (cin.good() == false)
    cout << "Podano nieprawidlowa liczbe, prosimy sprobowac ponownie" << endl;
                }while (cin.good() == false);
    switch (dzialanie)
                    {
        case 1:
            cout << "Wynik to: " << jeden + dwa << endl;
            break;
        case 2:
            cout << "Wynik to: " << jeden - dwa << endl;
            break;
        case 3:
            cout << "Wynik to: " << jeden * dwa << endl;
            break;
        case 4:
            if(jeden && dwa != 0)
            cout << "Wynik to: " << jeden / dwa << endl;
            else
            cout << "Nie mozna dzielic przez 0 " << endl;
            break;
        case 5:
            cout << "Dziekujemy za skorzystanie z naszego kalkulatora" << endl;
            return 0;
        default:
            cout << "Zadna operacja nie zostala wybrana " << endl;

                    }
    } while (1);


return 0;
}
