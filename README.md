# Projects_Alexandru_Nicoara

*mentionez faptul ca proiectele prezentate mai jos sunt proiecte realizate in facultate si nu mai am o mare parte din soft/hard. Astfel, descrierile de mai jos pot fi cosiderate abstract-uri pentru proiectele respective.

1. Sistem de alarma si acces cu PIN si amprenta.
Sistemul realizat are la baza un MCU ATMega16. Componentele principale au constat dintr-un senzor de detectie a distantei HC-SR04, un keypad, un modul door lock, un senzor pentru citirea amprentei, un LCD 16x2, circuit de alimentare si buzzer.
Functionare: 
In cazul in care o persoana se apropie de usa la o distanta mai mica de 50cm, sistemul permite introducerea parolei sau a amprentei. Daca parola este introdusa gresit de mai mult de 3 ori, atunci se declanseaza o alarma sonora care poate fi oprita doar prin introducerea parolei corecte. La fel, daca amprenta nu are match de mai mult de 3 ori, se declanseaza o alarma care poate fi oprita doar prin introducerea parolei. In cazul in care parola este corecta, este actionat door lock-ul si este permis accesul.
Dupa setarea parolei initiale, parola poate fi schimbata doar pe baza parolei vechi. De asemenea, match-ul amprentei poate fi schimbat pe baza parolei sau a amprentei vechi.

Codul a fost scris in C si incarcat pe MCU cu ajutorul unui programmer pentru microcontrollere AVR.

2. Sistem de control pentru iluminat.
Sistemul are la baza un MCU ATMega328 si este un proiect relativ simplu. Prin intermediul acestui sistem se face comanda a 4 module de iluminat care functioneaza la 220V. Comanda se face prin intermediul MCU si a unor swich-uri aflate pe panoul de comanda. Dupa citirea starii swich-urilor, MCU schimba comanda releelor in functie de starea swich-urilor. 
Ulterior, la acest proiect am folosit si un modul bt HC-05 si am reusit realizarea comenzii releelor de pe telefonul mobil.
Codul a fost scris in C si incarcat pe MCU cu ajutorul unui programmer pentru microcontrollere AVR.

