# Biblioteka Gier "WSPA GIER"

> Projekt zespołowy systemu informatycznego, cz. 1 (dokumentacja), semestr zimowy 2026/27, studia niestacjonarne.
> **Temat własny** (zaakceptowany przez prowadzącego): System informatyczny zarządzania biblioteką gier komputerowych (platforma dystrybucji gier)

## O systemie

WSPA GIER to platforma dystrybucji gier komputerowych, alternatywa dla Steam. Gracz przegląda Katalog gier, kupuje Gry, pobiera je z Biblioteki gier oraz wystawia Oceny i Recenzje. Wydawca samodzielnie publikuje Gry i ustala ich ceny, a dział obsługi rozpatruje Reklamacje i moderuje treści w jednym miejscu.

## Zespół

| Osoba | Login GitHub/GitLab | Rola główna | Role dodatkowe |
|---|---|---|---|
| Dawid Cichosz | @Derpuu | Kierownik projektu | — |
| Ewelina Pikul | @ewelinapikul345 | Analityk wymagań | — |
| Natalia Stopa | @nataliastopa | Architekt / projektant BD | — |
| Olga Mróz | @olgamroz | Projektant UX/UI | — |
| Kacper Graczyk | @kacpergraczyk | QA / wdrożenie | — |

### Macierz odpowiedzialności (RACI)

R = wykonuje, A = odpowiada (tylko jedna osoba), C = konsultowany, I = informowany

| Sekcja dokumentacji | Dawid (PM) | Ewelina (Analityk) | Natalia (Architekt) | Olga (UX/UI) | Kacper (QA) |
|---|---|---|---|---|---|
| 00 Zarządzanie projektem | A | C | C | C | R |
| 01 Wizja i zakres | A | R | C | C | I |
| 02 Słownik | C | A | R | C | I |
| 03 Wymagania | C | A | C | R | R |
| 04 Procesy i UC | I | A | R | C | C |
| 05 Architektura | C | C | A | I | R |
| 06 Model danych | I | C | A | I | C |
| 07 Interfejs | C | R | I | A | C |
| 08 Bezpieczeństwo | C | C | A | C | R |
| 09 Wdrożenie | I | I | C | I | A |
| 10 Testy | C | R | C | C | A |
| 11 Plan realizacji | A | C | R | R | R |
| Macierz śledzenia | C | R | C | C | A |

## Dokumentacja

| Nr | Dokument | Właściciel | Status |
|---|---|---|---|
| 00 | [Zarządzanie projektem](docs/00_zarzadzanie.md) | Dawid Cichosz | 🟩 |
| 01 | [Wizja i zakres](docs/01_wizja_i_zakres.md) | Dawid Cichosz | 🟩 |
| 02 | [Słownik pojęć](docs/02_slownik.md) | Ewelina Pikul | 🟩 |
| 03 | [Wymagania](docs/03_wymagania.md) | Ewelina Pikul | ⬜ |
| 04 | [Procesy i przypadki użycia](docs/04_procesy_i_przypadki_uzycia.md) | Ewelina Pikul | ⬜ |
| 05 | [Architektura](docs/05_architektura.md) + [ADR](docs/adr/) | Natalia Stopa | ⬜ |
| 06 | [Model danych](docs/06_model_danych.md) | Natalia Stopa | ⬜ |
| 07 | [Interfejs użytkownika](docs/07_interfejs_uzytkownika.md) + [makiety](docs/makiety/) | Olga Mróz | ⬜ |
| 08 | [Bezpieczeństwo](docs/08_bezpieczenstwo.md) | Natalia Stopa | ⬜ |
| 09 | [Wdrożenie](docs/09_wdrozenie.md) | Kacper Graczyk | ⬜ |
| 10 | [Testy i jakość](docs/10_testy_i_jakosc.md) | Kacper Graczyk | ⬜ |
| 11 | [Plan realizacji cz. 2](docs/11_plan_realizacji.md) | Dawid Cichosz | ⬜ |
| — | [Macierz śledzenia wymagań](docs/macierz_sledzenia.md) | Kacper Graczyk | ⬜ |

Statusy: ⬜ nie rozpoczęto · 🟨 w trakcie · 🟩 gotowe do recenzji · ✅ zatwierdzone

## Kamienie milowe

| Tag | Zawartość | Termin | Oddano |
|---|---|---|---|
| `m1` | repozytorium i tablica zadań, zespół i RACI, wizja i zakres, interesariusze, rejestr ryzyk, wstępny słownik, ćwiczenie git, pytania do wywiadu | 06.11.2026 | 28.11.2026 |
| `m2` | słownik, wymagania WF/WNF z MoSCoW, reguły biznesowe, historyjki z kryteriami akceptacji, C4 kontekst, protokół wywiadu, aktualizacja zakresu | 04.12.2026 | |
| `m3` | UC, procesy, model dziedziny, ERD, architektura, ADR, bezpieczeństwo | 08.01.2027 | |
| `m4` | UI, wdrożenie, testy, plan realizacji, macierz śledzenia | 17.01.2027 | |
| `v1.0` | wersja końcowa | 29.01.2027 | |

## Konwencje

Zasady pracy z repozytorium opisuje [CONTRIBUTING.md](CONTRIBUTING.md).

### Identyfikatory artefaktów

| Prefiks | Artefakt | Przykład |
|---|---|---|
| `CEL-` | cel biznesowy | CEL-01 |
| `INT-` | interesariusz | INT-01 Recepcjonistka |
| `RB-` | reguła biznesowa | RB-01 |
| `WF-` | wymaganie funkcjonalne | WF-07 |
| `WNF-` | wymaganie niefunkcjonalne | WNF-03 |
| `US-` | historyjka użytkownika | US-12 |
| `PB-` | proces biznesowy | PB-02 |
| `UC-` | przypadek użycia | UC-05 |
| `EKR-` | ekran / makieta | EKR-04 |
| `ADR-` | decyzja architektoniczna | ADR-0003 |
| `TC-` | przypadek testowy | TC-21 |
| `RYZ-` | ryzyko | RYZ-02 |

Identyfikatora raz nadanego **nie zmienia się i nie używa ponownie**. Usunięte wymaganie oznacza się jako ~~wycofane~~.
