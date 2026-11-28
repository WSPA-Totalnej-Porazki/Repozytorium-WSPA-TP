# 03. Wymagania

## 3.1. Wymagania funkcjonalne

Priorytet MoSCoW: M (Must), S (Should), C (Could), W (Won't – tym razem nie). Źródła: interesariusze INT-xx, zarys tematu zatwierdzony przez prowadzącego, ustalenia U-xx i zwrot akcji Z-01 z wywiadu symulowanego ([protokół](spotkania/wywiad-z-klientem.md)). Priorytety ustalone na wywiadzie; kwestie otwarte K-xx wyjaśniamy przez Issues `pytanie`.

| ID | Wymaganie (System musi/powinien…) | Aktor | Priorytet | Źródło | Historyjki |
|---|---|---|---|---|---|
| WF-01 | System musi umożliwiać Graczowi rejestrację Konta przez podanie adresu e-mail, nazwy wyświetlanej i hasła. | Gracz | M | INT-02, zarys tematu, rozdz. 3 | US-01 |
| WF-02 | System musi umożliwiać Graczowi i Wydawcy zalogowanie się i wylogowanie z Konta. | Gracz, Wydawca | M | INT-02, INT-03, zarys tematu, rozdz. 3 | US-02 |
| WF-03 | System powinien umożliwiać Graczowi zmianę hasła i ustawienie nowego hasła przez link wysłany e-mailem. | Gracz | S | INT-02, zarys tematu, rozdz. 5 | — |
| WF-04 | System musi umożliwiać Graczowi przeglądanie Katalogu gier z filtrowaniem po Gatunku i Cenie. | Gracz | M | INT-02, zarys tematu, rozdz. 3 | US-03 |
| WF-05 | System musi umożliwiać Graczowi wyszukanie Gry w Katalogu gier po nazwie. | Gracz | M | INT-02, zarys tematu, rozdz. 3 | US-04 |
| WF-06 | System musi umożliwiać Graczowi złożenie Zamówienia na Grę i opłacenie go przez System płatności. | Gracz | M | INT-01, INT-02, INT-05, zarys tematu, rozdz. 3, U-03 | US-05 |
| WF-07 | System musi po opłaceniu Zamówienia nadać Graczowi Licencję i dodać Grę do jego Biblioteki gier. | Gracz | M | INT-02, zarys tematu, rozdz. 3 | US-06 |
| WF-08 | System musi umożliwiać Graczowi Pobranie aktualnej Wersji gry, na którą ma Licencję. | Gracz | M | INT-02, zarys tematu, rozdz. 3 | US-07 |
| WF-09 | System powinien umożliwiać Graczowi ukrycie Gry w Bibliotece gier. | Gracz | C | zarys tematu, rozdz. 5 | — |
| WF-10 | System powinien umożliwiać Graczowi z Licencją wystawienie Oceny Gry w skali 1–5. | Gracz | S | INT-02, zarys tematu, rozdz. 3, U-11 | US-08 |
| WF-11 | System powinien umożliwiać Graczowi z Licencją napisanie Recenzji Gry. | Gracz | S | INT-02, zarys tematu, rozdz. 3 | US-08 |
| WF-12 | System musi umożliwiać Graczowi złożenie Reklamacji dotyczącej kupionej Gry. | Gracz | M | INT-02, INT-04, zarys tematu, rozdz. 3, U-04 | US-09 |
| WF-13 | System musi umożliwiać Agentowi wsparcia uznanie albo odrzucenie Reklamacji, a po uznaniu zlecenie Zwrotu w Systemie płatności. | Agent wsparcia | M | INT-04, INT-05, zarys tematu, rozdz. 2, U-05 | US-10 |
| WF-14 | System powinien umożliwiać Graczowi wysłanie Zgłoszenia naruszenia dotyczącego Gry lub Recenzji. | Gracz | C | INT-02, zarys tematu, rozdz. 3 | — |
| WF-15 | System powinien umożliwiać Graczowi usunięcie Konta. | Gracz | S | INT-06 (RODO), zarys tematu, rozdz. 5 | — |
| WF-16 | System musi umożliwiać Wydawcy rejestrację Konta deweloperskiego. | Wydawca | M | INT-03, zarys tematu, rozdz. 3, U-12 | US-11 |
| WF-17 | System musi umożliwiać Wydawcy dodanie Gry z opisem, Gatunkami, Ceną i plikami pierwszej Wersji gry oraz przesłanie jej do Weryfikacji gry. | Wydawca | M | INT-03, zarys tematu, rozdz. 3 | US-12 |
| WF-18 | System powinien umożliwiać Wydawcy wgranie nowej Wersji gry dla opublikowanej Gry. | Wydawca | S | INT-03, zarys tematu, rozdz. 3 | US-13 |
| WF-19 | System powinien umożliwiać Wydawcy ustalenie Promocji dla swojej Gry. | Wydawca | S | INT-03, zarys tematu, rozdz. 3, U-07 | US-14 |
| WF-20 | System powinien umożliwiać Wydawcy wycofanie Gry ze sprzedaży. | Wydawca | S | INT-03, zarys tematu, rozdz. 5 | — |
| WF-21 | System musi umożliwiać Administratorowi przeprowadzenie Weryfikacji gry zakończonej publikacją albo odrzuceniem z uzasadnieniem. | Administrator | M | INT-01, INT-04, zarys tematu, rozdz. 2, U-06 | US-15 |
| WF-22 | System powinien umożliwiać Administratorowi rozpatrzenie Zgłoszenia naruszenia i usunięcie Recenzji. | Administrator | S | INT-04, zarys tematu, rozdz. 3 | — |
| WF-23 | System powinien umożliwiać Administratorowi zablokowanie Konta naruszającego regulamin. | Administrator | S | INT-04, zarys tematu, rozdz. 3 | — |
| WF-24 | System powinien wysyłać Graczowi e-mail z potwierdzeniem opłaconego Zamówienia. | Gracz | S | INT-02, sekcja 1.6 | — |
| WF-25 | System nie będzie w MVP generował raportów sprzedaży dla Wydawców. | Wydawca | W | INT-03, U-10 | — |
| WF-26 | System nie będzie w MVP udostępniał Listy życzeń. | Gracz | W | sekcja 1.5 (rozszerzenia), K-04 | — |
| WF-27 | System powinien umożliwiać Graczowi rejestrację i zalogowanie się przez Logowanie zewnętrzne kontem Google. | Gracz | S | Z-01, wywiad symulowany | — |

## 3.2. Wymagania niefunkcjonalne

Kategorie jakości wg ISO/IEC 25010:2023 (w nawiasie nazwa angielska).

| ID | Kategoria | Wymaganie | Miara / sposób weryfikacji | Priorytet |
|---|---|---|---|---|
| WNF-01 | Efektywność wydajnościowa (performance efficiency) | Strona Katalogu gier z 24 Grami ładuje się w czasie ≤ 2 s dla 95% żądań przy 500 równoczesnych Graczach (U-02). | test obciążeniowy (np. k6 / JMeter) w środowisku testowym | M |
| WNF-02 | Efektywność wydajnościowa (performance efficiency) | Wyszukanie Gry po nazwie zwraca wyniki w czasie ≤ 1 s dla 95% żądań przy 500 równoczesnych Graczach i 10 000 Gier w Katalogu gier. | test obciążeniowy | S |
| WNF-03 | Bezpieczeństwo (security) | Hasła są przechowywane wyłącznie jako skrót Argon2id lub bcrypt; po 5 nieudanych logowaniach Konto jest blokowane na 15 min (RB-08). | przegląd kodu + test automatyczny logowania | M |
| WNF-04 | Bezpieczeństwo (security) | Cała komunikacja odbywa się przez HTTPS (TLS 1.2 lub nowszy). System nie przechowuje danych kart płatniczych; dane karty wpisuje się tylko na stronie Systemu płatności. | skan konfiguracji TLS (np. SSL Labs, ocena ≥ A) + przegląd bazy danych | M |
| WNF-05 | Niezawodność (reliability) | Dostępność (availability) platformy ≥ 99,5% w miesiącu, 24/7 (U-08); utrata danych (RPO) ≤ 24 h, czas przywrócenia (RTO) ≤ 4 h. | monitoring dostępności + test odtworzenia kopii zapasowej | M |
| WNF-06 | Łatwość utrzymania (maintainability) | Pokrycie testami jednostkowymi logiki reguł biznesowych RB-01…RB-10 ≥ 80%; brak błędów krytycznych w analizie statycznej kodu. | raport pokrycia testów + raport analizy statycznej w każdym PR | S |
| WNF-07 | Ograniczenie prawne (poza ISO 25010) | System przetwarza dane osobowe Graczy i Wydawców zgodnie z RODO; po usunięciu Konta dane osobowe są usuwane lub anonimizowane w ciągu 30 dni. | przegląd z listą kontrolną z 08_bezpieczenstwo | M |
| WNF-08 | Zdolność interakcji (interaction capability / usability) | Nowy Gracz bez instruktażu znajduje i kupuje wskazaną Grę w czasie ≤ 3 min w co najmniej 4 z 5 prób (CEL-01). | test z 5 Graczami, którzy nie znają platformy | M |
| WNF-09 | Zdolność interakcji: inkluzywność (dostępność, accessibility) | Interfejs spełnia WCAG 2.2 na poziomie AA. | audyt narzędziem (axe / Lighthouse ≥ 90 w kategorii Accessibility) + ręczna lista kontrolna WCAG | S |
| WNF-10 | Elastyczność (flexibility / portability) | Wszystkie ekrany Gracza działają bez przewijania poziomego od szerokości 360 px w dwóch ostatnich wersjach Chrome, Firefox, Safari i Edge (U-09). | test ręczny na liście przeglądarek i szerokości ekranu | S |
| WNF-11 | Kompatybilność (compatibility) | Integracja z Systemem płatności przez jego API: 100% scenariuszy testowych operatora (płatność udana, odrzucona, Zwrot) kończy się poprawnym Statusem płatności; jedna Płatność nigdy nie obciąża Gracza dwukrotnie. | testy integracyjne w środowisku testowym (sandbox) operatora | M |

## 3.3. Historyjki użytkownika

Format: Jako <aktor> chcę <cel>, aby <korzyść>. Kryteria akceptacji w formacie Given/When/Then (Zakładając/Gdy/Wtedy), min. 2 scenariusze, w tym błędny. Szacunek: S (≤ 3 pkt), M (5 pkt), L (8 pkt).

### US-01: Rejestracja Konta Gracza

**Jako** Gracz **chcę** założyć Konto podając e-mail i hasło, **aby** móc kupować Gry i mieć je w jednej Bibliotece gier.

- Wymaganie: WF-01 · Priorytet: M · Szacunek: S

**Kryteria akceptacji:**

```gherkin
Scenariusz: Udana rejestracja
  Zakładając że nie mam Konta
  Gdy podam e-mail anna.k@example.com, nazwę wyświetlaną „AnnaK” i hasło „Gry2026#bezp”
  Wtedy Konto otrzyma Status konta AKTYWNE i Rolę konta GRACZ
  I otrzymam e-mail z potwierdzeniem rejestracji

Scenariusz: E-mail jest już zajęty
  Zakładając że istnieje Konto z e-mailem anna.k@example.com
  Gdy spróbuję zarejestrować Konto z tym samym e-mailem
  Wtedy zobaczę komunikat „Konto z tym adresem e-mail już istnieje”
  I nowe Konto nie zostanie utworzone
```

### US-02: Logowanie do Konta

**Jako** Gracz **chcę** zalogować się e-mailem i hasłem, **aby** mieć dostęp do swojej Biblioteki gier i Zamówień.

- Wymaganie: WF-02 · Priorytet: M · Szacunek: S

**Kryteria akceptacji:**

```gherkin
Scenariusz: Udane logowanie
  Zakładając że mam Konto AKTYWNE z e-mailem anna.k@example.com
  Gdy podam poprawne hasło
  Wtedy zostanę zalogowana i zobaczę swoją Bibliotekę gier

Scenariusz: Blokada po 5 nieudanych próbach (RB-08)
  Zakładając że 4 razy z rzędu podałam błędne hasło
  Gdy po raz piąty podam błędne hasło
  Wtedy Konto otrzyma Status konta ZABLOKOWANE_CZASOWO na 15 minut
  I zobaczę komunikat „Zbyt wiele prób. Spróbuj ponownie za 15 minut”
```

### US-03: Przeglądanie Katalogu gier z filtrami

**Jako** Gracz **chcę** filtrować Katalog gier po Gatunku i Cenie, **aby** szybko znaleźć Grę, która mnie interesuje i na którą mnie stać.

- Wymaganie: WF-04 · Priorytet: M · Szacunek: M

**Kryteria akceptacji:**

```gherkin
Scenariusz: Filtrowanie po Gatunku i Cenie
  Zakładając że w Katalogu gier są 3 Gry z Gatunku „Strategia”, z czego 2 kosztują do 50 zł
  Gdy wybiorę Gatunek „Strategia” i Cenę „do 50 zł”
  Wtedy zobaczę dokładnie 2 Gry z okładką, nazwą i Ceną

Scenariusz: Brak Gier spełniających filtry
  Zakładając że w Katalogu gier nie ma Gier z Gatunku „Wyścigi” do 10 zł
  Gdy wybiorę te filtry
  Wtedy zobaczę komunikat „Brak Gier spełniających kryteria” i przycisk „Wyczyść filtry”
```

### US-04: Wyszukiwanie Gry po nazwie

**Jako** Gracz **chcę** wpisać nazwę Gry w wyszukiwarkę, **aby** od razu przejść do Gry, którą już znam.

- Wymaganie: WF-05 · Priorytet: M · Szacunek: S

**Kryteria akceptacji:**

```gherkin
Scenariusz: Gra znaleziona
  Zakładając że w Katalogu gier jest Gra „Kosmiczna Farma 2” o Statusie gry OPUBLIKOWANA
  Gdy wpiszę „kosmiczna”
  Wtedy na liście wyników zobaczę Grę „Kosmiczna Farma 2”

Scenariusz: Gra niedostępna nie pojawia się w wynikach
  Zakładając że Gra „Mroczny Las” ma Status gry ZABLOKOWANA
  Gdy wpiszę „mroczny las”
  Wtedy zobaczę komunikat „Nie znaleziono Gier”
  I Gra „Mroczny Las” nie pojawi się w wynikach
```

### US-05: Zakup Gry

**Jako** Gracz **chcę** kupić Grę i zapłacić za nią kartą lub BLIK-iem, **aby** od razu móc ją pobrać.

- Wymaganie: WF-06 · Priorytet: M · Szacunek: M

**Kryteria akceptacji:**

```gherkin
Scenariusz: Udany zakup
  Zakładając że jestem zalogowanym Graczem bez Licencji na Grę „Kosmiczna Farma 2” za 59,99 zł
  Gdy złożę Zamówienie i System płatności autoryzuje Płatność 59,99 zł
  Wtedy Zamówienie otrzyma status OPŁACONE
  I Gra pojawi się w mojej Bibliotece gier (WF-07)

Scenariusz: Płatność odrzucona
  Zakładając że złożyłam Zamówienie na Grę za 59,99 zł
  Gdy System płatności odrzuci Płatność z powodu braku środków
  Wtedy Płatność otrzyma Status płatności ODRZUCONA, a Zamówienie pozostanie NOWE
  I zobaczę komunikat „Płatność odrzucona. Spróbuj inną metodą płatności”

Scenariusz: Gra już kupiona (RB-06)
  Zakładając że mam Licencję na Grę „Kosmiczna Farma 2”
  Gdy otworzę stronę tej Gry
  Wtedy zamiast przycisku „Kup” zobaczę „W Bibliotece gier”
```

### US-06: Biblioteka gier

**Jako** Gracz **chcę** zobaczyć listę wszystkich moich Gier w jednym miejscu, **aby** łatwo wybrać Grę do pobrania.

- Wymaganie: WF-07 · Priorytet: M · Szacunek: S

**Kryteria akceptacji:**

```gherkin
Scenariusz: Lista kupionych Gier
  Zakładając że mam Licencje na 3 Gry
  Gdy otworzę Bibliotekę gier
  Wtedy zobaczę 3 Gry z okładką i przyciskiem „Pobierz”

Scenariusz: Pusta Biblioteka gier
  Zakładając że nie mam żadnej Licencji
  Gdy otworzę Bibliotekę gier
  Wtedy zobaczę komunikat „Nie masz jeszcze Gier” i link do Katalogu gier
```

### US-07: Pobranie Gry

**Jako** Gracz **chcę** pobrać aktualną Wersję gry z Biblioteki gier, **aby** zainstalować Grę na swoim komputerze.

- Wymaganie: WF-08 · Priorytet: M · Szacunek: M

**Kryteria akceptacji:**

```gherkin
Scenariusz: Pobranie aktualnej Wersji gry
  Zakładając że mam Licencję na Grę „Kosmiczna Farma 2”, której aktualna Wersja gry to 1.2.0
  Gdy kliknę „Pobierz” w Bibliotece gier
  Wtedy rozpocznie się Pobranie plików Wersji gry 1.2.0

Scenariusz: Brak Licencji
  Zakładając że nie mam Licencji na Grę „Mroczny Las”
  Gdy spróbuję otworzyć link do Pobrania tej Gry
  Wtedy zobaczę komunikat „Nie masz dostępu do tej Gry”
  I Pobranie się nie rozpocznie
```

### US-08: Ocena i Recenzja Gry

**Jako** Gracz **chcę** ocenić Grę w skali 1–5 i napisać Recenzję, **aby** pomóc innym Graczom w wyborze.

- Wymaganie: WF-10, WF-11 · Priorytet: S · Szacunek: M

**Kryteria akceptacji:**

```gherkin
Scenariusz: Wystawienie Oceny i Recenzji
  Zakładając że mam Licencję na Grę „Kosmiczna Farma 2”
  Gdy wystawię Ocenę 4 i napiszę Recenzję „Świetna fabuła, słaba optymalizacja”
  Wtedy Ocena i Recenzja będą widoczne na stronie Gry z moim Profilem

Scenariusz: Brak Licencji (RB-01)
  Zakładając że nie mam Licencji na Grę „Mroczny Las”
  Gdy otworzę stronę tej Gry
  Wtedy nie zobaczę formularza Oceny i Recenzji, tylko informację „Ocenić Grę mogą tylko jej posiadacze”
```

### US-09: Złożenie Reklamacji

**Jako** Gracz **chcę** złożyć Reklamację na Grę, która nie działa, **aby** odzyskać pieniądze.

- Wymaganie: WF-12 · Priorytet: M · Szacunek: S

**Kryteria akceptacji:**

```gherkin
Scenariusz: Reklamacja w terminie (RB-02)
  Zakładając że 3 dni temu opłaciłam Zamówienie na Grę „Kosmiczna Farma 2”, a mój Czas gry to 40 min
  Gdy złożę Reklamację z opisem „Gra nie uruchamia się po instalacji”
  Wtedy Reklamacja otrzyma Status reklamacji ZŁOŻONA
  I otrzymam e-mail z numerem Reklamacji

Scenariusz: Reklamacja po terminie (RB-02)
  Zakładając że 20 dni temu opłaciłam Zamówienie na Grę „Kosmiczna Farma 2”
  Gdy spróbuję złożyć Reklamację
  Wtedy zobaczę komunikat „Minął 14-dniowy termin na Reklamację”
  I Reklamacja nie zostanie utworzona
```

### US-10: Rozpatrzenie Reklamacji

**Jako** Agent wsparcia **chcę** uznać lub odrzucić Reklamację, widząc historię Zamówień i Czas gry Gracza, **aby** szybko i sprawiedliwie podjąć decyzję.

- Wymaganie: WF-13 · Priorytet: M · Szacunek: M

**Kryteria akceptacji:**

```gherkin
Scenariusz: Uznanie Reklamacji (RB-04)
  Zakładając że Reklamacja na Grę za 59,99 zł ma Status reklamacji W_TOKU
  Gdy uznam Reklamację
  Wtedy Reklamacja otrzyma status UZNANA, a System płatności wykona Zwrot 59,99 zł
  I Licencja Gracza na tę Grę zostanie cofnięta

Scenariusz: Odrzucenie bez uzasadnienia
  Zakładając że Reklamacja ma Status reklamacji W_TOKU
  Gdy spróbuję ją odrzucić bez wpisania uzasadnienia
  Wtedy zobaczę komunikat „Podaj uzasadnienie odrzucenia”
  I Status reklamacji się nie zmieni
```

### US-11: Rejestracja Konta deweloperskiego

**Jako** Wydawca **chcę** założyć Konto deweloperskie dla mojego studia, **aby** publikować i sprzedawać swoje Gry.

- Wymaganie: WF-16 · Priorytet: M · Szacunek: S

**Kryteria akceptacji:**

```gherkin
Scenariusz: Udana rejestracja
  Zakładając że studio „Pixel Lublin” nie ma Konta deweloperskiego
  Gdy podam nazwę studia, e-mail kontakt@pixellublin.example i NIP 9462712345
  Wtedy powstanie Konto z Rolą konta WYDAWCA
  I będę mógł dodać pierwszą Grę

Scenariusz: Niepoprawny NIP
  Zakładając że rejestruję Konto deweloperskie
  Gdy podam NIP „123”
  Wtedy zobaczę komunikat „NIP musi mieć 10 cyfr”
  I Konto nie zostanie utworzone
```

### US-12: Dodanie Gry

**Jako** Wydawca **chcę** dodać Grę z opisem, Gatunkami, Ceną i plikami, **aby** udostępnić ją Graczom po Weryfikacji gry.

- Wymaganie: WF-17 · Priorytet: M · Szacunek: L

**Kryteria akceptacji:**

```gherkin
Scenariusz: Przesłanie Gry do Weryfikacji gry (RB-07)
  Zakładając że jestem zalogowanym Wydawcą
  Gdy dodam Grę „Kosmiczna Farma 2” z Gatunkiem „Symulacja”, Ceną 59,99 zł i plikiem Wersji gry 1.0.0
  Wtedy Gra otrzyma Status gry W_WERYFIKACJI
  I nie będzie jeszcze widoczna w Katalogu gier

Scenariusz: Brak plików Wersji gry
  Zakładając że wypełniłem opis i Cenę Gry
  Gdy spróbuję przesłać Grę do Weryfikacji gry bez pliku Wersji gry
  Wtedy zobaczę komunikat „Dodaj pliki Gry”
  I Gra pozostanie w Statusie gry SZKIC
```

### US-13: Nowa Wersja gry

**Jako** Wydawca **chcę** wgrać nową Wersję gry z poprawkami, **aby** Gracze pobierali zawsze najnowszą wersję.

- Wymaganie: WF-18 · Priorytet: S · Szacunek: M

**Kryteria akceptacji:**

```gherkin
Scenariusz: Wgranie nowej Wersji gry
  Zakładając że Gra „Kosmiczna Farma 2” ma Status gry OPUBLIKOWANA i aktualną Wersję gry 1.2.0
  Gdy wgram Wersję gry 1.2.1
  Wtedy Gracze z Licencją przy kolejnym Pobraniu dostaną Wersję gry 1.2.1

Scenariusz: Numer wersji już istnieje
  Zakładając że Gra ma Wersję gry 1.2.0
  Gdy spróbuję wgrać plik z numerem 1.2.0
  Wtedy zobaczę komunikat „Ta Wersja gry już istnieje”
```

### US-14: Ustalenie Promocji

**Jako** Wydawca **chcę** ustawić obniżkę Ceny mojej Gry na kilka dni, **aby** zwiększyć sprzedaż.

- Wymaganie: WF-19 · Priorytet: S · Szacunek: S

**Kryteria akceptacji:**

```gherkin
Scenariusz: Poprawna Promocja (RB-05)
  Zakładając że Gra „Kosmiczna Farma 2” kosztuje 59,99 zł i nie miała Promocji przez ostatnie 14 dni
  Gdy ustawię Promocję −30% od 01.12.2026 do 07.12.2026
  Wtedy w tym czasie Cena w Katalogu gier wyniesie 41,99 zł

Scenariusz: Zbyt duża obniżka (RB-05)
  Zakładając że ustalam Promocję dla tej Gry
  Gdy podam obniżkę 95%
  Wtedy zobaczę komunikat „Obniżka musi wynosić od 5% do 90%”
  I Promocja nie zostanie zapisana
```

### US-15: Weryfikacja gry

**Jako** Administrator **chcę** sprawdzić przesłaną Grę i ją opublikować albo odrzucić, **aby** w Katalogu gier były tylko Gry zgodne z regulaminem.

- Wymaganie: WF-21 · Priorytet: M · Szacunek: M

**Kryteria akceptacji:**

```gherkin
Scenariusz: Publikacja Gry
  Zakładając że Gra „Kosmiczna Farma 2” ma Status gry W_WERYFIKACJI
  Gdy zatwierdzę Weryfikację gry
  Wtedy Gra otrzyma Status gry OPUBLIKOWANA i pojawi się w Katalogu gier
  I Wydawca otrzyma e-mail o publikacji

Scenariusz: Odrzucenie bez uzasadnienia (RB-07)
  Zakładając że Gra ma Status gry W_WERYFIKACJI
  Gdy spróbuję ją odrzucić bez uzasadnienia
  Wtedy zobaczę komunikat „Podaj uzasadnienie odrzucenia”
  I Status gry się nie zmieni
```

## 3.4. Reguły biznesowe

| ID | Reguła |
|---|---|
| RB-01 | Ocenę i Recenzję Gry może wystawić tylko Gracz, który ma Licencję na tę Grę (U-11). Gracz ma najwyżej jedną Ocenę i jedną Recenzję na Grę i może je zmienić. |
| RB-02 | Reklamację można złożyć najpóźniej 14 dni po opłaceniu Zamówienia i tylko wtedy, gdy Czas gry tej Gry jest krótszy niż 2 h (U-04). |
| RB-03 | Agent wsparcia rozpatruje Reklamację w ciągu 3 dni roboczych od jej złożenia (U-05, CEL-03). |
| RB-04 | Po uznaniu Reklamacji wykonuje się Zwrot całej zapłaconej kwoty, a Licencja na Grę zostaje cofnięta i Gra znika z Biblioteki gier. |
| RB-05 | Promocja obniża Cenę o 5–90% i trwa od 1 do 30 dni. Między końcem jednej Promocji a początkiem następnej dla tej samej Gry musi minąć co najmniej 14 dni (U-07). |
| RB-06 | Kupić można tylko Grę o Statusie gry OPUBLIKOWANA. Gracz nie może kupić Gry, na którą ma już Licencję. |
| RB-07 | Nowa Gra trafia do Katalogu gier dopiero po pozytywnej Weryfikacji gry przez Administratora, przeprowadzonej w ciągu 5 dni roboczych od przesłania. Odrzucenie wymaga uzasadnienia (U-06). |
| RB-08 | Po 5 nieudanych próbach logowania z rzędu Konto jest blokowane na 15 minut. |
| RB-09 | Zamówienie nieopłacone w ciągu 30 minut od utworzenia otrzymuje status ANULOWANE. |
| RB-10 | Gra o Statusie gry WYCOFANA pozostaje w Bibliotece gier Graczy, którzy mają na nią Licencję, ale nie można jej kupić. |
