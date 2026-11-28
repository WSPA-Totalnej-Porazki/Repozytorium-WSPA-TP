# Wywiad z klientem – przygotowanie

> **Wywiad symulowany przygotowany przez zespół na podstawie zarysu steam -0.2.pdf.** Prowadzący nie odgrywa klienta, dlatego odpowiedzi klienta (INT-01) opracował zespół. To nie jest zapis rozmowy z prawdziwym klientem.

## Cel wywiadu

Poznać potrzeby właściciela platformy WSPA GIER (INT-01; w wywiadzie symulowanym jego odpowiedzi przygotowuje zespół), potwierdzić zakres MVP z sekcji 1.5 i założenia z sekcji 1.7, poznać wartości bazowe celów CEL-01…CEL-03 oraz zebrać informacje potrzebne do wymagań w M2.

## Role w wywiadzie symulowanym

| Osoba | Zadanie |
|---|---|
| Olga Mróz | przygotowuje odpowiedzi klienta (właściciel platformy, INT-01) i zwrot akcji Z-01 |
| Ewelina Pikul | przygotowuje przebieg rozmowy i parafrazę ustaleń |
| Dawid Cichosz | spisuje protokół: liczby i nazwy dosłownie, zwrot akcji |
| Kacper Graczyk | sprawdza sprzeczności, mierniki i kryteria odbioru |
| Natalia Stopa | przygotowuje szczegóły: dane, systemy zewnętrzne, skala |

## Założenia do potwierdzenia

Z sekcji 1.7:
1. Gracz korzysta z platformy przez przeglądarkę na komputerze lub telefonie.
2. Płatności obsługuje zewnętrzny System płatności, platforma nie przechowuje danych kart.
3. Wydawca dostarcza gotowe pliki Gry, Administrator sprawdza Grę przed publikacją.
4. Gracz pobiera Grę i uruchamia ją na swoim urządzeniu, bez własnego launchera.
5. W MVP język polski i ceny w PLN.
6. Administrator i Agent wsparcia to pracownicy operatora platformy.

Wartości bazowe celów z sekcji 1.2 (pytamy, jak jest dziś):
- CEL-01: ile dziś trwa znalezienie i zakup Gry przez nowego Gracza?
- CEL-02: ilu niezależnych Wydawców klient chce pozyskać i w jakim czasie?
- CEL-03: ile dziś trwa rozpatrzenie Reklamacji?

## Pytania

### A. Kontekst i problem

1. Dlaczego chcą Państwo stworzyć własną platformę, skoro na rynku jest Steam i Epic Games Store?
2. Proszę opisać sytuację, w której obecne platformy zawiodły Gracza albo Wydawcę. Co się wtedy stało?
3. Po czym za rok poznają Państwo, że platforma odniosła sukces?

### B. Użytkownicy i ich praca

1. Kim są Gracze, do których chcą Państwo dotrzeć w pierwszej kolejności, i jak dziś kupują Gry?
2. Na jakich urządzeniach i w jakich sytuacjach Gracz najczęściej przegląda Katalog gier i kupuje Gry?
3. Jak wygląda dzień pracy osoby z działu obsługi, która rozpatruje Reklamacje?

### C. Procesy i przypadki szczególne

1. Proszę opisać krok po kroku, jak Wydawca ma dodać nową Grę, od założenia Konta do momentu, gdy Gracz może ją kupić.
2. Co powinno się stać, gdy Płatność za Zamówienie nie dojdzie do skutku albo zostanie przerwana?
3. W jakich sytuacjach Gracz może otrzymać Zwrot za Grę i kto o tym decyduje?
4. Co dzieje się z Grami w Bibliotece gier Gracza, gdy Wydawca wycofa Grę albo Administrator ją zablokuje?

### D. Dane, raporty, systemy zewnętrzne

1. Z jakim operatorem płatności lub bankiem już Państwo współpracują i jakie metody płatności są potrzebne?
2. Ile Gier, Graczy i Zamówień dziennie spodziewają się Państwo na starcie i po roku?
3. Jakie raporty i zestawienia są potrzebne właścicielowi platformy i Wydawcom (np. sprzedaż, Zwroty)?

### E. Jakość, bezpieczeństwo, ograniczenia

1. Jakie dane osobowe Graczy i Wydawców platforma musi przechowywać i jak długo?
2. Jak długo platforma może być niedostępna, zanim stanie się to poważnym problemem dla Państwa?
3. Jakie przepisy lub umowy (np. prawa konsumenta przy zwrotach treści cyfrowych) musimy uwzględnić?

### F. Priorytety i kryteria odbioru

1. Gdyby pierwsza wersja mogła mieć tylko trzy funkcje, które by to były?
2. Z czego mogą Państwo zrezygnować w pierwszej wersji, jeśli zabraknie czasu?
3. Na podstawie czego odbiorą Państwo system jako gotowy?

## Protokół z wywiadu symulowanego

> **Wywiad symulowany przygotowany przez zespół na podstawie zarysu steam -0.2.pdf.** Ustalenia U-xx to odpowiedzi klienta przygotowane przez zespół, nie zapis rozmowy z prawdziwym klientem.

- **Klient:** rola właściciela platformy WSPA GIER (INT-01); odpowiedzi przygotowała Olga Mróz na podstawie zarysu steam -0.2.pdf
- **Opracowanie:** Ewelina Pikul (przebieg i parafraza), Dawid Cichosz (protokół), Kacper Graczyk (sprzeczności), Natalia Stopa (szczegóły)
- **Cel wywiadu:** potwierdzenie wizji, kluczowe procesy, wyjątki, liczby, ograniczenia

### Ustalenia

| # | Ustalenie (odpowiedź klienta w symulacji) | Typ (WF/WNF/RB/zakres/słownik) | Gdzie trafia |
|---|---|---|---|
| U-01 | Platforma ma być prostszą alternatywą dla Steam, przede wszystkim dla nowych Graczy i małych Wydawców | zakres | 01: 1.1, CEL-01, CEL-02 |
| U-02 | Na start ok. 2 000 Gier i 50 000 Kont Graczy, po roku ok. 10 000 Gier; w szczycie do 500 Graczy jednocześnie | WNF | WNF-01, WNF-02 |
| U-03 | Płatności kartą i BLIK przez jednego zewnętrznego operatora płatności | WF / zakres | WF-06, 01: 1.6, 05: C4 |
| U-04 | Reklamację można złożyć do 14 dni od zakupu, jeśli Czas gry jest krótszy niż 2 h | RB | RB-02, WF-12 |
| U-05 | Reklamacja ma być rozpatrzona w ciągu 3 dni roboczych | RB | RB-03, CEL-03, WF-13 |
| U-06 | Każdą nową Grę sprawdza Administrator przed publikacją, najdłużej 5 dni roboczych | RB | RB-07, WF-21 |
| U-07 | Promocja: obniżka 5–90%, najwyżej 30 dni, co najmniej 14 dni przerwy między Promocjami tej samej Gry | RB | RB-05, WF-19 |
| U-08 | Platforma działa 24/7; przerwa dłuższa niż kilka godzin jest poważnym problemem | WNF | WNF-05 |
| U-09 | Gracze korzystają z komputerów i telefonów, przez przeglądarkę | WNF | WNF-10 |
| U-10 | Raporty sprzedaży dla Wydawców nie są potrzebne na start | zakres | WF-25 (W), 01: 1.5 |
| U-11 | Oceny i Recenzje mogą wystawiać tylko osoby, które kupiły Grę | RB | RB-01, WF-10, WF-11 |
| U-12 | Wydawca rejestruje Konto deweloperskie z nazwą studia i NIP | WF | WF-16, US-11 |

### Nowe pojęcia i doprecyzowane znaczenia

- **Czas gry**: klient bierze go pod uwagę przy Reklamacji (U-04) → 02
- **Weryfikacja gry**: sprawdzenie Gry przez Administratora przed publikacją (U-06) → 02
- **Konto deweloperskie**: konto Wydawcy (U-12) → 02
- **Logowanie zewnętrzne**: logowanie kontem Google (Z-01) → 02

### Liczby podane przez klienta (w symulacji)

- 2 000 Gier na start, 10 000 po roku; 50 000 Kont Graczy na start; 500 Graczy jednocześnie w szczycie
- Reklamacja: 14 dni, Czas gry < 2 h, rozpatrzenie w 3 dni robocze
- Weryfikacja gry: najwyżej 5 dni roboczych
- Promocja: 5–90%, najwyżej 30 dni, przerwa min. 14 dni

### Sprzeczności i kwestie otwarte

| # | Kwestia | Dalsze kroki (Issue „pytanie”) |
|---|---|---|
| K-01 | Klient najpierw chciał, żeby Gry „od razu były w sklepie”, potem że „każdą trzeba sprawdzić”. Ustalono Weryfikację gry przed publikacją (U-06). | rozstrzygnięte w wywiadzie (U-06) |
| K-02 | Czy oprócz karty i BLIK potrzebne są inne metody płatności (np. przelew, PayPal)? | Issue `pytanie` |
| K-03 | Czy Wydawca płaci za publikację Gry? | Issue `pytanie` |
| K-04 | Lista życzeń: klient powiedział, że „kiedyś by się przydała”. Zespół proponuje W. | Issue `pytanie` |

### Zwrot akcji

- **Karta:** Z-01 „Gracze nie chcą zakładać kolejnego hasła. Platforma musi pozwalać logować się kontem Google.” (zwrot akcji przygotowany przez zespół w roli klienta)
- **Decyzja zespołu:** logowanie kontem Google wchodzi do MVP z priorytetem S, a logowanie e-mailem i hasłem zostaje. Wpis w dzienniku decyzji, [00_zarzadzanie.md](../00_zarzadzanie.md), i nowe ryzyko RYZ-09.
- **Zmienione dokumenty:** 01 (1.5 MVP, 1.6 nowy system zewnętrzny, analiza luk), 02 (Logowanie zewnętrzne), 03 (WF-27), 05 (C4: Dostawca tożsamości Google)

### Zadania (Issues)

- #26 słownik, #27–#31 wymagania i historyjki, #32 C4 kontekst, #34 pytania do klienta (K-02…K-04), #24 dziennik decyzji (Z-01)
