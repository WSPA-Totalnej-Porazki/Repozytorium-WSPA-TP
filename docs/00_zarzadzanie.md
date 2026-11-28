# 00. Zarządzanie projektem

## Sposób pracy zespołu

- Kanał komunikacji: Discord (serwer zespołu „WSPA GIER”)
- Spotkania: robocze, asynchronicznie na Discordzie; ustalenia spisane w `docs/spotkania/`
- Tablica zadań: [GitHub Projects – WSPA GIER](https://github.com/orgs/WSPA-Totalnej-Porazki/projects/1)
- Notatki ze spotkań: [`spotkania/`](spotkania/), jeden plik na dokument: `spotkanie-NN-krotki-opis.md` (np. `spotkanie-01-start-projektu.md`) i `wywiad-z-klientem.md`; każdy plik ma na górze adnotację, że jest spotkaniem roboczym lub wywiadem symulowanym (ustalenia, zadania z linkami do Issues)
- Każda zmiana przez Pull Request z recenzją innej osoby; PR scala autor po zatwierdzeniu (zasady w [CONTRIBUTING.md](../CONTRIBUTING.md))

## Harmonogram semestru

| Kamień | Termin oddania (tag) | Odpowiedzialny | Uwagi |
|---|---|---|---|
| M1 | 06.11.2026 | Dawid Cichosz | 48 h przed 4. zjazdem (08.11.2026); wizja i zakres, słownik wstępny, ryzyka, pytania do wywiadu |
| M2 | 04.12.2026 | Dawid Cichosz | 48 h przed 6. zjazdem (06.12.2026); wymagania, historyjki, C4 kontekst, protokół wywiadu |
| M3 | 08.01.2027 | Dawid Cichosz | 48 h przed 8. zjazdem (10.01.2027); UC, model dziedziny, ERD, architektura, ADR, bezpieczeństwo |
| M4 | 17.01.2027 | Dawid Cichosz | 14 dni przed 10. zjazdem, 31.01.2027 (miejsce na recenzję krzyżową); UI, wdrożenie, testy, macierz |
| v1.0 | 29.01.2027 | Dawid Cichosz | 48 h przed 10. zjazdem (31.01.2027); wersja końcowa |

## Rejestr ryzyk

| ID | Ryzyko | P | W | P×W | Reakcja (unikanie / łagodzenie / akceptacja) | Właściciel | Status |
|---|---|---|---|---|---|---|---|
| RYZ-01 | Członek zespołu nie wywiązuje się z zadań | 2 | 3 | 6 | Łagodzenie: cotygodniowy przegląd tablicy przez PM, wczesna eskalacja do prowadzącego | Dawid Cichosz | otwarte |
| RYZ-02 | Zakres rozrasta się, bo Steam ma setki funkcji, a zespół chce je powtórzyć | 3 | 3 | 9 | Unikanie: jawna lista „poza zakresem” w 1.5, priorytety MoSCoW, każda nowa funkcja tylko przez decyzję w dzienniku | Dawid Cichosz | otwarte |
| RYZ-03 | Zwrot akcji na wywiadzie (zajęcia 2) zmienia wymagania lub dodaje system zewnętrzny | 3 | 2 | 6 | Łagodzenie: rezerwa czasu w M2, decyzja zapisana w dzienniku, aktualizacja 01 i 05 | Natalia Stopa | otwarte |
| RYZ-04 | Niespójne nazewnictwo (np. „Deweloper” i „Wydawca”) w różnych dokumentach | 2 | 2 | 4 | Łagodzenie: jedno pojęcie w słowniku, recenzent PR sprawdza zgodność ze słownikiem | Ewelina Pikul | otwarte |
| RYZ-05 | Konflikty w git lub commity niepodpięte do konta i utrata punktów za wkład | 2 | 2 | 4 | Unikanie: ochrona `main`, jedna osoba na plik naraz, sprawdzenie `user.email` u każdego | Kacper Graczyk | otwarte |
| RYZ-06 | Pominięcie wymagań prawnych: RODO i zwroty za treści cyfrowe | 2 | 3 | 6 | Łagodzenie: pytania do klienta w grupie E, sekcja 08 bezpieczeństwo, ograniczenia w 1.7 | Natalia Stopa | otwarte |
| RYZ-07 | Spiętrzenie pracy tuż przed terminem i spóźniony tag | 2 | 3 | 6 | Łagodzenie: wszystkie PR kamienia scalone 3 dni przed terminem, tag robi PM | Dawid Cichosz | otwarte |
| RYZ-08 | Odpowiedzi na kwestie otwarte z wywiadu (K-02…K-04) zmienią reguły biznesowe lub priorytety po napisaniu historyjek | 2 | 2 | 4 | Łagodzenie: pytania jako Issues `pytanie` od razu po wywiadzie, odwołania do U-xx w WF i RB ułatwiają poprawki | Ewelina Pikul | otwarte |
| RYZ-09 | Zmiany lub awaria Logowania zewnętrznego Google (zwrot akcji Z-01) | 1 | 2 | 2 | Łagodzenie: logowanie e-mailem i hasłem zawsze dostępne, standard OpenID Connect | Natalia Stopa | otwarte |

## Dziennik decyzji zespołu

| Kiedy | Decyzja | Kto podjął |
|---|---|---|
| M1, spotkanie robocze nr 1 | Platforma: GitHub (organizacja WSPA-Totalnej-Porazki, repozytorium publiczne). Uzasadnienie: darmowa ochrona gałęzi `main`, Issues i Projects w jednym miejscu, wszyscy mają konta. | cały zespół |
| M1, spotkanie robocze nr 1 | Makiety: Figma (plan edukacyjny). Uzasadnienie: bezpłatna, praca kilku osób jednocześnie, łatwy eksport do PNG/SVG. | cały zespół |
| M1, spotkanie robocze nr 1 | Diagramy: Mermaid w plikach Markdown. Uzasadnienie: renderuje się na GitHubie, zmiany widać w PR. | cały zespół |
| M1, spotkanie robocze nr 1 | Kanał komunikacji: Discord. Uzasadnienie: wszyscy z niego korzystają, kanały tematyczne i rozmowy głosowe na spotkania. | cały zespół |
| M1, spotkanie robocze nr 1 | Nazewnictwo: „Wydawca” zamiast „Deweloper” (w zarysie tematu są oba). Uzasadnienie: jedno pojęcie, jedna nazwa. | cały zespół |
| M1, spotkanie robocze nr 1 | Wywiad z klientem i spotkania zespołu w formie symulowanej (prowadzący nie odgrywa klienta): treść przygotowuje zespół na podstawie zarysu steam -0.2.pdf, każdy taki dokument ma na górze jawną adnotację. | cały zespół |
| 27.11.2026 | Struktura repozytorium przywrócona zgodnie z szablonem (`docs/`, `.github/`), PR #12. | Natalia Stopa |
| M2, wywiad symulowany | Zwrot akcji Z-01 (logowanie kontem Google): wchodzi do MVP jako WF-27 z priorytetem S, logowanie e-mailem i hasłem zostaje. Zmiany: 01 (1.5, 1.6, analiza luk), 02 (Logowanie zewnętrzne, Dostawca tożsamości), 03 (WF-27), 05 (C4), nowe ryzyko RYZ-09. | cały zespół |
| M2, spotkanie robocze nr 2 | Wymagania M2 (WF, RB, priorytety MoSCoW) na podstawie wywiadu symulowanego (odpowiedzi klienta przygotował zespół) i zarysu tematu zatwierdzonego przez prowadzącego; kwestie otwarte K-02…K-04 wyjaśniamy przez Issues `pytanie`. | cały zespół |
| M2, spotkanie robocze nr 2 | Kupić czy zbudować: płatności, e-mail i przechowywanie plików integrujemy z systemami zewnętrznymi, budujemy rdzeń (katalog, biblioteka, zamówienia, reklamacje, weryfikacja). Szczegóły w 01, analiza luk. | cały zespół |
| M2, spotkanie robocze nr 2 | Raporty sprzedaży i Lista życzeń z priorytetem W (poza MVP), żeby M nie przekraczało ok. 60% pracy. | cały zespół |
