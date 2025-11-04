int main (){
    int pilihan; 
    cout << "1. cocacola\n2. fanta\n3. burger\n4. KFC \npilih menu: ";
    cin >> pilihan;
    
    switch (pilihan){
        case 1: 
        cout << "cocacola";
        break;
        case 2: 
        cout << "fanta";
        break;
        case 3:
        cout << "burger";
        break;
        case 4:
        cout << "KFC";
        break;
        default: 
        cout << "Menu tidak tersedia";
    }
}
