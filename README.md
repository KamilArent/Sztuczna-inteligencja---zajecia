# Opis aplikacji
## 1. Wymagania
- python 3.10+
- django min.5.0
- paczka Pillow
- silnik bazy sqlite3

## 2. Uruchomienie projektu
Wykonanie polecenia

Dla windows
```sh
python -m venv venv
```

Dla Unix
```sh
python3 -m venv venv
```

Uruchomienie wirtualnej zmiennej środowiskowej

Dla windows
```sh
PowerShell
.\venv\Scrits\activate

GIT bash
source venv/Scripts/activate
```

Instalacja Django
```sh
pip install django
```

Instalacja Pillow
```sh
pip install Pillow
```

(Opcjonalnie jeżeli jest pusta baza)
```sh
python manage.py migrate
```
oraz stworzenie superusera
```sh
python manage.py createsuperuser
```

W przypadku używania silnikia sqlite3 z repo dane do logowania
```sh
login: kamil
password: 123
```

Uruchomienie serwera
```sh
python manage.py runserver
```