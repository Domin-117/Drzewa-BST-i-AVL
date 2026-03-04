# AiSD — Projekt 2: Drzewa przeszukiwań binarnych BST i drzewa samobalansujące AVL

Ten projekt implementuje struktury danych drzew binarnych przeszukiwań (BST) oraz zrównoważonych drzew AVL w języku Python. Zawiera interaktywny program do manipulacji drzewami oraz skrypt do porównania wydajności obu struktur.

## Funkcjonalności

### Program.py
- Implementacja klas BST i AVL z podstawowymi operacjami:
  - Wstawianie elementów
  - Usuwanie elementów
  - Przechodzenie drzewa (in-order, pre-order, post-order)
  - Znajdowanie minimum i maksimum
  - Rebalansowanie drzewa BST za pomocą algorytmu DSW
  - Eksport drzewa do formatu LaTeX (TikZ)
- Interaktywny interfejs tekstowy do obsługi drzew

### benchmark.py
- Skrypt do mierzenia czasów wykonania operacji:
  - Tworzenie drzew BST i AVL
  - Znajdowanie min/max
  - Przechodzenie in-order
  - Balansowanie BST
- Zapis wyników do plików CSV w folderze `Sprawozdanie/results/`

## Jak uruchomić

### Program
```bash
python3 Program.py
```

Postępuj zgodnie z instrukcjami w terminalu:
1. Wybierz typ drzewa (BST/AVL)
2. Opcjonalnie załaduj dane z pliku lub wprowadź ręcznie
3. Używaj komend takich jak:
   - `help` - wyświetla dostępne komendy
   - `print` - drukuje drzewo w różnych porządkach
   - `min_max` - pokazuje minimum i maksimum
   - `remove` - usuwa elementy
   - `export` - eksportuje drzewo do LaTeX
   - `rebalance` - rebalansuje drzewo BST
   - `exit` - wychodzi z programu

### Benchmark
```bash
python3 benchmark.py
```

Skrypt automatycznie wykona benchmarki dla różnych rozmiarów danych (od 2^11 do 2^19 elementów) i zapisze wyniki w plikach CSV.

Autorzy 
Projekt i sprawozdanie: Dominik Fischer, Oliwer Miller