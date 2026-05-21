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


Oppsummering
I denne brukerveiledningen lærte vi:
hvordan åpne terminal
hvordan gå til prosjektmappe
hvordan lage virtual environment
hvordan installere Python-pakker
hvordan starte Python-programmer
hvordan feilsøke vanlige problemer
 
