Brukerveiledning – Hvordan laste ned Python-pakker i Linux (Ubuntu/WSL)
Hva er en Python-pakke?
Python-pakker er ekstra funksjoner og verktøy man kan installere til Python.

Eksempler:

Flask → brukes til nettsider/webapplikasjoner

MariaDB → kobling mot database


⸻

1. Åpne terminal
Åpne Ubuntu/WSL-terminalen.


⸻

2. Gå til prosjektmappen
Bruk cd for å gå til prosjektet.

Eksempel:
cd /mnt/c/Users/Mohammad1/Documents/plannlegging
 
3. Lag virtual environment
Et virtual environment gjør at pakkene installeres kun til prosjektet.

python3 -m venv .venv

4. Aktiver virtual environment

source .venv/bin/activate

Vis det fungerer vil man se:

(.venv)
forna navnet i terminalen

5. Installere Python-pakker
bruk pip for å installere pakker

Installere flask
pip install flask

Installere mariadb

pip install mariadb

6. kontrollere at pakken fungerer
man kan teste av å starte progrannet

Eksempel:
python3 app.py eller python3 db.py

7. Vanlige feil
Feil: No module named flask
Betyr at Flask ikke er installert.

Løsning:
pip install flask

Feil: Port 5000 is in use
Betyr at Flask allerede kjører.

Løsning:
trykk: CTRL + C
I terminalen som kjører flask.

Feil: No such file or directory

Betyr ofte at man er i feil mappe.

Bruk: ls for å se filene i mappen

8. Installere MariaDB-pakker i Linux/WSL

Hvis man får feil som:

OSError: mariadb_config not found

må man installere MariaDB development-pakker.

Kjør:

sudo apt update

sudo apt install libmariadb-dev

Deretter kan man installere Python-pakken:

pip install mariadb
 


Oppsummering
I denne brukerveiledningen lærte vi:
hvordan åpne terminal
hvordan gå til prosjektmappe
hvordan lage virtual environment
hvordan installere Python-pakker
hvordan starte Python-programmer
hvordan feilsøke vanlige problemer


<img width="1156" height="299" alt="Skjermbilde 2026-05-22 001822" src="https://github.com/user-attachments/assets/a0a35f42-7137-4389-85fc-5965c8b27d7c" />

<img width="1347" height="241" alt="Skjermbilde 2026-05-22 001912" src="https://github.com/user-attachments/assets/e7a27cf1-9354-4b37-82ed-15cd18a947b2" />

<img width="1255" height="413" alt="Skjermbilde 2026-05-22 002044" src="https://github.com/user-attachments/assets/618efadf-e67e-43e2-ae6d-b9217349300e" />


<img width="1616" height="384" alt="Skjermbilde 2026-05-22 002306" src="https://github.com/user-attachments/assets/f7f68a91-6f0d-4392-89b5-9a82f4a0a318" />



<img width="941" height="389" alt="image" src="https://github.com/user-attachments/assets/87f34209-5aae-4da9-a215-423d6b2f099b" />


<img width="928" height="222" alt="image" src="https://github.com/user-attachments/assets/3f56fbc9-b64b-43d8-9fc1-fa80cbd935fb" />

<img width="845" height="295" alt="image" src="https://github.com/user-attachments/assets/3a5db5d5-1b6a-43d8-a145-d174ed220e06" />


<img width="1870" height="481" alt="image" src="https://github.com/user-attachments/assets/e8362759-3a62-4731-9b1c-214259293d26" />


<img width="1743" height="272" alt="Skjermbilde 2026-05-22 005358" src="https://github.com/user-attachments/assets/5796a353-6ec6-4070-8b8b-61edbbe8010e" />




 
