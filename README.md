Świat Zwierząt - Blog

Linki do projektu
Strona (GitHub Pages): https://tereqsynka.github.io/Swiat-Zwierzat/
Repozytorium kodu (GitHub): https://github.com/TereqSynka/Swiat-Zwierzat.git

O projekcie:

Świat Zwierząt to nowoczesny, w pełni responsywny portal blogowy poświęcony różnorodnym gatunkom zwierząt domowych i egzotycznych (psy, koty, gryzonie, gady, ptaki).

Kluczowe moduły strony:
-Sekcja Hero: Baner powitalny z płynnym przyciskiem akcji kierującym do eksploracji portalu.
-O nas: Krótkie wprowadzenie do portalu
-Interaktywny Katalog Gatunków: Dynamiczna siatka kart przedstawiająca poszczególne zwierzęta wraz ze szczegółowymi parametrami (średnia waga, wzrost, cechy charakterystyczne). Sekcja umożliwia filtrowanie według -kategorii (np. psy, koty, gryzonie, ptaki, gady).
-Slider Zdjęć: Płynny, interaktywny slider prezentujący fotografie zwierząt z możliwością nawigacji przyciskami.
-Ciekawostki: Sekcja z ciekawostkami
-Formularz Kontaktowy i Stopka: Nawigacja pomocnicza, linki do mediów społecznościowych oraz formularz kontaktowy.

Wykorzystane technologie i rozwiązania

1. HTML
Semantyczna struktura dokumentu (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
Zastosowanie dobrych praktyk dostępności (dostępne etykiety `aria-label`, odpowiednie opisy alternatywne `alt` dla obrazów).
Dbałość o strukturę nagłówków (`<h1>`-`<h3>`)

2. CSS
Struktura i układy: Wykorzystanie modułów CSS Grid (dla kart zwierząt) oraz Flexbox (dla nawigacji i układu elementów).
Responsywność (RWD): Zastosowanie reguł `@media` dopasowujących wygląd strony do urządzeń mobilnych, tabletów i ekranów stacjonarnych.
Stylizacja i Zmienne CSS: Spójna paleta kolorystyczna oparta na zmiennych CSS (`:root`)

3. JavaScript (Vanilla JS)
Filtrowanie kategorii: Logika odpowiedzialna za pokazywanie/ukrywanie kart zwierząt w zależności od wybranego filtru.
Interaktywny Slider: Obsługa przejść slajdów, automatycznego lub manualnego przełączania zdjęć.
Efekty Interaktywne: Płynne przewijanie do sekcji (`smooth scroll`) oraz efekty wizualne przy interakcji użytkownika.


