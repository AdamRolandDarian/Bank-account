# Bank-account

### ContBancar
Are urmatoarele atribute:numarCont(String);
suma(Float)

### Client
Are urmatoarele atribute: nume(String); adresa(String); contru(tablou de elemente de tip ContBancar: un client trebuie sa aiba cel putin un cont, dar nu mai mult de 5)

Conturile bancare pot fi de mai multe feluri: in LEI si in EURO. Conturile in euro si numai ele au o dobanda fixa, 0.3 euro pe zi, daca suma depaseste 500 euro sau 0 in caz contrar, deci acest tip de cont trebuie sa ofere serviciul public float getDobanda().

Pot exista transferuri intre contruile in lei si numai intre ele, in sensul ca un cont de acest tip trebuie sa ofere serviciul public void transfer(ContBanca contDestinatie, float suma).
