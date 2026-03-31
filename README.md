<div align="center">

# FIZYKA
**System Analityczny Wspomagania Nauki i Pomiaru Czasu Pracy**

</div>

<hr />

## OPIS SYSTEMU
System V13 PRO to dedykowane narzędzie typu Single-File Application zaprojektowane do monitorowania postępów w nauce. Pozwala na precyzyjne mierzenie czasu poświęconego na poszczególne zadania oraz automatyczne generowanie statystyk i wykresów wydajności.

## GŁÓWNE MODUŁY
1. **Chronometr milisekundowy**: Precyzyjny stoper z funkcją inteligentnej inkrementacji ID zadań.
2. **Interaktywny Wykres Timeline**: Wizualizacja czasu nauki w czasie rzeczywistym z obsługą High-DPI.
3. **Analiza Rozdziałów**: Automatyczne grupowanie zadań w bloki tematyczne na podstawie prefiksów numerycznych.
4. **Sparklines**: Miniaturowe wykresy trendów czasowych dla każdego aktywnego rozdziału.

## SKRÓTY KLAWIATUROWE
| Klawisz | Akcja |
| :--- | :--- |
| **SPACE** | Start / Stop stopera (poza polem tekstowym) |
| **CTRL + ENTER** | Zapisanie sesji i przejście do kolejnego ID |
| **ESCAPE** | Resetowanie bieżącego licznika czasu |

## SPECYFIKACJA TECHNICZNA
*   **Silnik graficzny**: Native Canvas API (Spline Curve Interpolation).
*   **Magazyn danych**: Browser Local Storage (Klucz: `f_v12`).
*   **Format zapisu**: JSON.
*   **Obsługa stref czasowych**: Mechanizm normalizacji daty uwzględniający przesunięcia letnie/zimowe (DST Fix).

## ZARZĄDZANIE DANYMI
System oferuje pełną kontrolę nad bazą danych rekordów:
*   **Eksport**: Zapis bazy do pliku `.json`.
*   **Import**: Przywracanie danych z kopii zapasowej.
*   **Migracja**: Kompatybilność wsteczna z bazami danych wersji V7.

## INSTRUKCJA INSTALACJI
Aplikacja nie wymaga instalacji ani zewnętrznych bibliotek.
1. Pobierz plik `.html`.
2. Otwórz go w dowolnej nowoczesnej przeglądarce (Chrome, Edge, Firefox).
3. System automatycznie zainicjuje bazę danych w pamięci lokalnej przeglądarki.

<hr />

<div align="center">
    <strong>WERSJA: V13_PRO_CHART | DOKUMENTACJA TECHNICZNA | 2026</strong>
</div>
