# Filmweb User Statistics Analysis

Analiza statystyk filmów obejrzanych przez użytkownika portalu Filmweb wykonana w języku R przy użyciu Markdown i Quarto.

## Opis projektu

Projekt ma na celu kompleksową analizę preferencji filmowych użytkownika Filmweb. Analiza obejmuje:

- Statystyki ilościowe (liczba filmów, godzin oglądania)
- Rozkład ocen i porównanie ze średnimi ocenami społeczności
- Analizę gatunków, reżyserów i krajów produkcji
- Trendy ocen w różnych dekadach produkcji
- Wizualizacje danych w formie interaktywnych wykresów i tabel

## Wymagania

- R (wersja 4.0+)
- RStudio (zalecane)
- Pakiety R: `tidyverse`, `DT`, `plotly`, `leaflet`, `rnaturalearth`, `sf`, `rvest`, `rio`, `RSelenium`

## Jak uruchomić

1. Sklonuj repozytorium:
   ```bash
    git clone https://github.com/twoja_nazwa/filmweb-analysis.git
   ```
2. Otwórz plik filmweb_analisys.html w przeglądarce, aby zobaczyć gotowy raport
3. Aby modyfikować analizę:
   - Otwórz filmweb_analisys.qmd w RStudio
   - Zainstaluj wymagane pakiety
   - Wykonaj kompilację (Knit)

## Główne funkcjonalności
- Interaktywne tabele z możliwością sortowania i wyszukiwania
- Wykresy porównawcze ocen użytkownika vs średniej społeczności
- Trendy w różnych dekadach
- Mapa geograficzna krajów produkcji filmów
- Statystyki szczegółowe dla reżyserów i gatunków

## Hipotezy badawcze
Projekt weryfikuje 5 głównych hipotez dotyczących preferencji filmowych użytkownika, w tym preferencje dla starszych dekad, wpływ selektywnego oglądania oraz dominację kina amerykańskiego.

## Live demo
https://arraxus.github.io/filmweb-analisys/
