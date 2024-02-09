# backtracking-recursiv-assembly

Acest repository continte a doua tema din cadrul cursului de Arhitectura Sistemelor de Calcul.

In fisierul Tema2.pdf sunt explicate anumite concepte si este enuntata cerinta.

Cerinta este rezolvata in fisierul 143_Hutan_MihaiAlexandru.asm.

Pentru verificarea corectitudinii cerintei vom rula prima data:

as --32 143_Hutan_MihaiAlexandru.asm.asm -o 143_Hutan_MihaiAlexandru.asm.o

gcc -m32 143_Hutan_MihaiAlexandru.asm.o -o 143_Hutan_MihaiAlexandru.asm

Pentru a rula scriptul python vom folosi urmatoarele comenzi:

sudo apt install python2

wget https://bootstrap.pypa.io/pip/2.7/get-pip.py

sudo python2 get-pip.py

pip2 install pwn

pip2 install pathlib2

python2 script.py

# ATENTIE:

Pentru ca totul sa functioneze perfect va trebui sa fim sigur ca toate fisierele sunt regasite in fisierul in care deschidem terminalul unde rulam comenzile!
