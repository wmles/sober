# Die ultimative Diskussions-Software
 -- boost your arguments to a new level --

### Anleitung zur Installation
1. Voraussetzungen
  - installiere git (autocsrf einstellen) python3, virtualenv
  - Kommandozeile, `cd` zum parent-Ordner für das kommende Projekt
2. Diese repository clonen:
  `git clone https://github.com/wmles/scholarium.git`
3. Eine virtual environment erstellen + aktivieren
  `virtualenv venv --python=python3`
  `source venv/bin/activate` (unter Windows anders -> google)
die Folgenden Installationen passieren in der virtualenv, die globale python-Installation wird nicht beeinflusst.
4. Alles einrichten
  `pip install -r requirements.txt`
  um neue DB zu erstellen: `python manage.py migrate`
  `python manage.py createsuperuser` -> dem prompt folgen
5. Lokalen Server starten
  `python manage.py runserver`
  im Browser 127.0.0.1:8000 aufrufen

