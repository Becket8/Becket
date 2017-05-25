#include <iostream>
#include <cstdlib>
#include <ctime>
using namespace std;
int podejscie = 0;
int main()

{
    srand( time ( NULL ) );
    short cyfra;
    short losowa = ( (rand() % 1001) + 1 );

    do
    {


    cout << "Wpisz cyfre: ";
    cin.clear();
    cin.sync();
    cin >> cyfra;
    if( cin.good() == false || cyfra > 1000)
    cout << "Podano nieprawidlowa liczbe, sprobuj ponownie " << endl;
    podejscie ++;
    cout << "Podejscie: " << podejscie << endl;
    while( cin.good() == false && cyfra > 1000);

        if ( cin.good() && cyfra > losowa)
            cout << "Celuj nizej" << endl;
        if ( cin.good() && cyfra < losowa)
            cout << "Celuj wyzej" << endl;
        if ( cyfra == losowa && cin.good() == true && cyfra <= 1000 )
            cout << "Gratulacje! Udalo Ci sie wpisac to samo co wylosowal komputer!!" << endl << "Liczba to: " << losowa << endl << "Liczba prob: " << podejscie << endl;
    }while (1);

    return 0;

}
