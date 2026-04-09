# P2_2_Motylki
Jak zmieniała się liczebność zaobserwowanych motyli w Kalifornii w latach 2000-2016 na podstawie danych monitoringowych?

## Cel projektu
Celem projektu jest analiza zmian liczebności motyli w Kalifornii w latach 2000–2016 na podstawie danych monitoringowych.

## Opis danych
Dane zawierają informacje o liczbie zaobserwowanych motyli w poszczególnych latach oraz dla różnych gatunków.

Kolumny:
- `year` – rok obserwacji
- `genus_species` – nazwa gatunku motyla
- `count` – liczba zaobserwowanych osobników

## Metody analizy
W projekcie wykorzystano:
- Python
- bibliotekę pandas (analiza danych)
- bibliotekę matplotlib (wizualizacja)

Wykonane analizy:
- agregacja danych rocznych
- analiza trendu liczebności
- obliczenie zmiany procentowej
- analiza 5 najczęściej występujących gatunków

## Struktura projektu
P2_2_Motylki/
│
├── README.md # opis projektu
├── main.py # główny kod analizy
├── raport.pdf # raport końcowy
├── requirements.txt # wymagane biblioteki
│
├── data/
│ └── data1.csv # dane wejściowe
│
├── src/
│ ├── script1.py # dodatkowy skrypt
│ └── notebook1.ipynb # analiza w Jupyter Notebook
│
└── outputs/
├── plot1.png # wykres wynikowy
└── data1.csv # dane po przetworzeniu
