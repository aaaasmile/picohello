# Hello Pico
Ho provato un piccolo programma con Tinygo e Raspberry pico.
L'installazione do Tinygo l'ho eseguita in powershell con scoop.
scoop install tinygo
Poi in visula code ho installato l'estensione TinyGo e scelto il target pico.
Una volta scritto il programma in go, pico va collegato al laptop in modalità boot.
Per questa procedura basta premere il tasto boot e collegare il cavo usb.
Ora basta lanciare in terminal il seguente comando:
tinygo flash -target=pico main.go

## Link
Ho seguito le istruzioni di questo video:
https://www.youtube.com/watch?v=Fl5eFIYU1Xg&ab_channel=PatricioWhittingslow