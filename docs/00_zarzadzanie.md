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
| M1 | «TERMIN_M1» | Dawid Cichosz | 48 h przed zajęciami 2; wizja i zakres, słownik wstępny, ryzyka, pytania do wywiadu |
| M2 | «TERMIN_M2» | Dawid Cichosz | 48 h przed zajęciami 3; wymagania, historyjki, C4 kontekst, protokół wywiadu |
| M3 | «TERMIN_M3» | Dawid Cichosz | 48 h przed zajęciami 4; UC, model dziedziny, ERD, architektura, ADR, bezpieczeństwo |
| M4 | «TERMIN_M4» | Dawid Cichosz | 14 dni przed zajęciami 5 (miejsce na recenzję krzyżową); UI, wdrożenie, testy, macierz |
| v1.0 | «TERMIN_V1» | Dawid Cichosz | 48 h przed zajęciami 5; wersja końcowa |

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
