// Bunga Laelatul Muna
// 21102010

#include <iostream>

using namespace std;

int main() {

    int data[10];
    int *poindat;
    int *poinrubah;
    int rubah, norubah, pilihan;
    char kembali;


    cout << endl;
    cout << "====================================" << endl;
    cout << "PROGRAM TINGGI BADAN MAHASISWA IF " << endl;
    cout << "====================================" << endl << endl;

    for (int i = 0; i < 10; ++i) {
        cout << "Data ke- " << i+1<< endl;
        cout << "Masukan Tinggi badan: ";
        cin >> *(data + i) ;

    }

    cout << endl;
    cout << "====================================" << endl;
    cout << "    MENU TINGGI BADAN MAHASISWA     " << endl;
    cout << "====================================" << endl << endl;
    cout << " 1. Menampilkan Nilai TB Mahasiswa " << endl;
    cout << " 2. Menampilkan Alamat TB Mahasiswa " << endl;
    cout << " 3. Merubah TB Mahasiswa " << endl;

    cout << "Masukan menu: " ;
    cin  >> pilihan;

    switch (pilihan) {
    case 1:
    cout << endl;
    cout << "====================================" << endl;
    cout << "TAMPILAN TINGGI BADAN MAHASISWA IF " << endl;
    cout << "====================================" << endl << endl;
    for (int i = 0; i < 10; ++i) {
            poindat=&data[i];
        cout << "Tinggi badan: "<< *poindat << " cm" << endl ;
    }

     break;

    case 2:
    cout << endl;
    cout << "====================================" << endl;
    cout << "TAMPILAN ALAMAT TB MAHASISWA IF " << endl;
    cout << "====================================" << endl << endl;
    for (int i = 0; i < 10; ++i) {
        poindat=&data[i];
        cout << "Alamat TB ke- " << i+1<< ": " << poindat<< endl ;
    }
    break;

    case 3:
    cout << endl;
    cout << "====================================" << endl;
    cout << "DATA TB MAHASISWA YG DIRUBAH " << endl;
    cout << "====================================" << endl << endl;


for (int i=0; i<5; i++){
     cout << "Rubah data indeks : ";
     cin  >> norubah;
     cout << "TB ubah menjadi: ";
     cin  >> rubah;
     poinrubah = &data[rubah];
    *poinrubah = rubah;
    if (norubah<10 ){
     cout << "TB dari " << norubah[data]  << " menjadi: " << data[rubah] << " cm" << endl << endl;
    } else {
        cout << "indeks tidak ditemukan" << endl;
    }
}

 break;
    }
    return 0;
}
