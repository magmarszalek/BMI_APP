# BMI Calculator

## Opis projektu
Ten projekt to prosty kalkulator BMI (Body Mass Index) napisany w Pythonie z wykorzystaniem biblioteki CustomTkinter. Aplikacja pozwala na dynamiczne obliczanie BMI na podstawie podanego wzrostu i wagi użytkownika.

## Wymagania
Aby uruchomić aplikację, należy zainstalować następujące zależności:

- Python 3.x
- CustomTkinter

Można je zainstalować za pomocą polecenia:
```sh
pip install customtkinter
```

## Funkcjonalności
- Dynamiczne obliczanie BMI na podstawie podanego wzrostu i wagi.
- Regulacja wagi za pomocą przycisków zwiększania i zmniejszania wartości.
- Regulacja wzrostu za pomocą suwaka.
- Automatyczna aktualizacja wyniku BMI w interfejsie użytkownika.
- Atrakcyjny graficznie interfejs użytkownika w technologii CustomTkinter.

## Struktura kodu
### Główne klasy:
- `App` – główna klasa aplikacji, definiująca okno oraz interakcje między komponentami.
- `ResultText` – etykieta wyświetlająca aktualną wartość BMI.
- `WeightInput` – panel z przyciskami do regulacji wagi użytkownika.
- `HeighInput` – suwak pozwalający na ustawienie wzrostu użytkownika.
- `Text_BIM` – etykieta wyświetlająca napis "BMI".

### Metody:
- `update_bmi(self, *args)` – oblicza BMI na podstawie wartości wprowadzonych przez użytkownika.
- `change_title_bar_color(self)` – zmienia kolor paska tytułu okna.
- `update_weight(self, info = None)` – aktualizuje wartość wagi w interfejsie.
- `update_text(self, amount)` – aktualizuje wartość wzrostu w interfejsie.

## Uruchomienie aplikacji
Aby uruchomić aplikację, należy wykonać polecenie:
```sh
python bmi.py
```


## Autor
Projekt został opracowany jako narzędzie do prostego i szybkiego obliczania BMI z wykorzystaniem graficznego interfejsu użytkownika.


