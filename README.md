# Cyfrowa Wizytówka

Prosty i responsywny projekt wizytówki internetowej stworzony w czystym kodzie **HTML5** oraz **CSS3**. Projekt przedstawia profil fikcyjnego programisty i został zbudowany z wykorzystaniem nowoczesnego środowiska deweloperskiego **Vite**.

Projekt realizuje klasyczne zadanie zorientowane na naukę układów pudełkowych (Box Model) oraz nowoczesnego pozycjonowania elementów w CSS.

---

## Funkcjonalności i efekty wizualne

* **Układ Flexbox:** Cała struktura karty wykorzystuje `display: flex` z odpowiednim wyrównaniem (`justify-content: space-around`), co zapewnia symetryczne rozłożenie zdjęcia oraz tekstu.
* **Interaktywne efekty Hover:** Zdjęcie profilowe (avatar) posiada płynną mikrointerakcję po najechaniu myszką (`:hover`). Wykorzystuje właściwości `scale(1.1)` (delikatne powiększenie) oraz `rotate(10deg)` (lekkie obrócenie) połączone z płynnym przejściem czasowym `transition: all .5s`.
* **Personalizowany Box Model:** Karta posiada estetyczne, asymetryczne obramowanie (`border-bottom` oraz `border-right`) nadające jej efekt głębi, dopełnione delikatnym zaokrągleniem rogów (`border-radius`) oraz cieniem (`box-shadow`) pod avatarem.

---

## Zastosowane technologie

* **HTML5** – semantyczna struktura dokumentu (`<div>`, `<img>`, nagłówki `<h3>`/`<h4>`).
* **CSS3** – zaawansowane stylowanie, Flexbox, pseudoklasy interaktywne (`:hover`) oraz transformacje i animacje płynne (`scale`, `rotate`, `transition`).
* **Vite** – superszybkie środowisko uruchomieniowe i bundler dla frontendu.
