# Laborator-ASC

Acest repository continte prima tema din cadrul cursului de Arhitectura Sistemelor de Calcul.

In fisierul Tema1.pdf sunt explicate anumite concepte si sunt enuntatate cele patru cerinte.

Fiecare cerinta este rezolvata in codurile cerintax.asm (x = 1,4).

Pentru verificarea corectitudinii cerintei vom rula prima data:

as --32 cerintax.asm -o cerintax.o

gcc -m32 cerintax.o -o cerintax

pentru fiecare din cele patru cerinte.

Pentru a rula scriptul python vom folosi urmatoarele comenzi:

sudo apt install python2

wget https://bootstrap.pypa.io/pip/2.7/get-pip.py

sudo python2 get-pip.py

pip2 install pwn

pip2 install pathlib2

python2 script.py

Pentru o verificare mai amanuntita cu inputuri mai mari putem inlocui in script.py inputul si outputul dand copy paste din fisierul script_final_notare.

# ATENTIE:

Pentru ca totul sa functioneze perfect va trebui sa fim sigur ca toate fisierele sunt regasite in fisierul in care deschidem terminalul unde rulam comenzile!
