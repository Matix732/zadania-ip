*README wygenerowane przez Gemini by Google*
# 🌐 Sieciowe Narzędzia IP: Kalkulator & Trenażer VLSM

Wielofunkcyjna aplikacja webowa (Single Page Application) stworzona z myślą o inżynierach sieciowych, studentach informatyki oraz osobach przygotowujących się do certyfikacji branżowych (Cisco CCNA, CompTIA Network+) oraz egzaminów państwowych (INF.02 / EE.08). 

Projekt łączy w sobie potężny kalkulator adresacji IPv4 z interaktywnymi trenażerami, które generują w locie nieskończoną liczbę scenariuszy do ćwiczeń.

👉 **[ZOBACZ APLIKACJĘ NA ŻYWO (Live Demo)](TUTAJ WPISZ LINK DO GITHUB PAGES)**

## ✨ Dostępne Moduły

Aplikacja składa się z 4 niezależnych zakładek:

1. **🧮 Kalkulator Podsieci (CIDR Calculator):** Błyskawicznie wylicza adres sieci, adres rozgłoszeniowy (broadcast), użyteczny zakres hostów oraz pojemność podsieci na podstawie adresu IP i maski.
2. **🔎 Trenażer: Szukanie IP:** Moduł losujący adresy hostów i maski (od /10 do /29). Zadaniem użytkownika jest obliczenie granic sieci. Aplikacja na bieżąco waliduje poprawność wprowadzonych danych.
3. **🧩 Trenażer: Podział VLSM (Variable Length Subnet Mask):** Zaawansowany silnik alokacji, który generuje realistyczne zapotrzebowanie na hosty dla fikcyjnych działów firmy. Zmusza użytkownika do poprawnego sortowania sieci i bezkolizyjnego przydzielania bloków adresowych.
4. **📦 Trenażer: Agregacja Tras (Supernetting):** Generuje zestawy przyległych podsieci, wymagając od użytkownika wyliczenia najmniejszej możliwej maski agregującej (supernetu).

## 🚀 Cechy projektu

* **100% Client-Side:** Cała matematyka sieciowa opiera się na wydajnych operacjach bitowych w czystym języku JavaScript (Vanilla JS).
* **Brak zależności:** Aplikacja to tylko 1 plik `index.html`. Brak frameworków (React/Angular), brak zewnętrznych bibliotek. Działa offline i wczytuje się błyskawicznie.
* **Dark Mode:** Nowoczesny, nienarzucający się dla oczu interfejs oparty o paletę Dracula Theme.
* **Responsywność:** Aplikacja działa płynnie zarówno na komputerach, jak i na ekranach smartfonów.

## 🎯 Dla kogo jest ten projekt?
* Dla osób uczących się do egzaminu **Cisco CCNA (200-301)**.
* Dla uczniów techników informatycznych (kwalifikacja **INF.02** / dawniej EE.08 / E.13).
* Dla administratorów sieci, którzy chcą odświeżyć mechanikę adresacji bez wspomagania się kalkulatorami.

## 💻 Uruchomienie lokalne
Aby uruchomić aplikację lokalnie, nie potrzebujesz żadnego serwera. Wystarczy, że:
1. Pobierzesz plik `index.html`.
2. Otworzysz go w dowolnej nowoczesnej przeglądarce internetowej (Chrome, Firefox, Edge, Safari).

## 🛠️ Technologie
* HTML5
* CSS3 (Zmienne CSS, Flexbox)
* JavaScript (ES6+, Operatory Bitowe, Manipulacja DOM)

---
*Jeśli to narzędzie pomogło Ci zrozumieć sieci lub zdać egzamin - zostaw ⭐️ (gwiazdkę) w tym repozytorium!*
