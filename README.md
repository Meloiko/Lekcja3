# NIP rent

Aplikacja do rozliczania najmowanych mieszkań.

## Getting started

- Używając *Python3.12* utwórz *venv* i zainstaluj zależności

```sh
python3.12 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# Projekt: System Rozliczeń Mieszkań
Aplikacja służy do zarządzania rozliczeniami najmu. Pozwala na automatyczne wyliczanie salda najemnców.

## Co już zrobiliśmy:
* Stworzyliśmy model **ApartmentSettlement** do sumowania rachunków za całe mieszkanie.
* Stworzyliśmy model **TenantSettlement**, który oblicza saldo każdego lokatora (wpłaty minus koszta).

## Współautorzy
* **Oliwia Wichlaj** - Lider, Dokumentacja
* **Marta Taras** - Wyświetlanie danych
