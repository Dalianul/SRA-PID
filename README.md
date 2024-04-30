# SRA-PID

LISTA COMPONENTE PROIECT: 
  Logica:
1x Arduino Nano sau Uno (compatibil)
  Senzori:
1x Senzor temperatura LM35
  Interfata:
1x Display LCD 16x2 
4x Buton Tactil 6X6X5MM
~10x Rezistor 1k Ohm sau 10k Ohm pentru pull-ups butoane
sau:
1x Arduino LCD 16x2 cu Tastatura (LCD 1602 cu Keypad)
Control sursa caldura:
1x Tranzistor putere TIP31C sau echivalent + rezistori baza
sau
1x Modul tranzistor de putere IRF520
sau
1x Punte H driver motor DC
  Sursa caldura:
1x Bec 5V-12V  minim 5W 
1x Sursa alimentare compatibila cu sursa de caldura aleasa (ie. 5V min. 1A sau 12V min. 0.5A pentru 5W) 
+Conectori

  TEMATICA PROIECTULUI:
Sistem de conducere pe bază de microcontroller care va efectua următoarele funcţii:
● Încălzirea sistemului până la o temperatura setată TSET într-un timp t incalzire
● Menţinerea acestei temperaturi pentru o perioada de timp tmentinere
● Răcirea sistemului treptat într-o perioadă de timp t racire Interfaţa cu utilizatorul
● Sistemul va dispune de un LCD 16x2 pe care va fi afişat meniul, iar în timpul rulării se vor afişa temperatura setată, temperatura curentă şi timpul rămas din etapa actuală (t incalzire, t mentinere,t racire).
● Meniul sistemului va permite modificarea următorilor parametri: TSET, t incalzire, t mentinere, t racire, KP, KI, KD
● Parametrii vor fi salvaţi în memoria nevolatilă. Repornirea sistemului nu va afecta parametrii salvaţi.
● Navigarea prin meniul echipamentului se va face prin patru butoane: “OK”, “Cancel”, “+”, “-”.
● Opţional, se poate crea o interfaţă pe PC pentru afişarea unui grafic al temperaturii.

  Reglarea temperaturii
● Controlul temperaturii va fi asigurat de un regulator de tip PID
● Senzorul de temperatură folosit va fi unul de tip LM35 sau echivalent.
● Elementul de execuţie al sistemului ce va asigura încălzirea senzorului va fi un bec incandescent c.c. de putere >= 5W ce va putea ajunge la o temperatura de minim 50°C
● Se va folosi un releu sau un tranzistor pentru a comanda pornirea/oprirea alimentării acestui bec de către microcontroller.
