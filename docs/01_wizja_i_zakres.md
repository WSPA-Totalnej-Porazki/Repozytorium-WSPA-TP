# 01. Wizja i zakres systemu

## 1.1. Opis problemu

| | |
|---|---|
| **Problem** | Rynek cyfrowej dystrybucji gier komputerowych jest zdominowany przez jedną platformę (Steam), której rozbudowany interfejs utrudnia nowym Graczom znalezienie i kupienie Gry, a małym Wydawcom dotarcie do Graczy. |
| **dotyczy** | Graczy (zwłaszcza nowych i amatorskich), małych i niezależnych Wydawców oraz pracowników obsługi, którzy rozpatrują Reklamacje. |
| **skutkiem jest** | Gracze tracą czas na szukanie Gier i rezygnują z zakupu, mali Wydawcy giną w ogromnej ofercie, a brak konkurencji ogranicza wybór usług na rynku. |
| **dobre rozwiązanie** | Gracz szybko znajduje i kupuje Grę i ma wszystkie Gry w jednej Bibliotece gier, Wydawca samodzielnie publikuje Grę i ustala jej cenę, a Reklamacje są rozpatrywane w jednym miejscu. |

## 1.2. Cel biznesowy i mierniki sukcesu

| ID | Cel | Miernik | Wartość docelowa |
|---|---|---|---|
| CEL-01 | Skrócić czas, w którym nowy Gracz znajduje i kupuje Grę | Mediana czasu od pierwszego wyszukania Gry do opłacenia Zamówienia (test z 10 nowymi Graczami) | ≤ 3 min w teście przed uruchomieniem platformy |
| CEL-02 | Umożliwić małym Wydawcom samodzielną publikację Gier | Liczba Gier o Statusie gry OPUBLIKOWANA dodanych przez niezależnych Wydawców | ≥ 20 Gier w ciągu 6 miesięcy od uruchomienia |
| CEL-03 | Rozpatrywać Reklamacje szybko i w jednym miejscu | Odsetek Reklamacji o Statusie reklamacji UZNANA lub ODRZUCONA w ciągu 3 dni roboczych od złożenia | ≥ 90% Reklamacji w każdym miesiącu od uruchomienia |

## 1.3. Interesariusze

| ID | Interesariusz | Opis / rola | Oczekiwania wobec systemu | Wpływ (W/Ś/N) | Zainteresowanie (W/Ś/N) |
|---|---|---|---|---|---|
| INT-01 | | | | | |

## 1.4. Użytkownicy systemu (aktorzy)

| Aktor | Kim jest | Jak często korzysta | Kompetencje cyfrowe |
|---|---|---|---|
| | | | |

## 1.5. Zakres systemu

### W zakresie (MVP — realizacja w cz. 2)

- Konto: rejestracja, logowanie, wylogowanie, zmiana hasła, usunięcie Konta, profil Gracza
- Katalog gier: przeglądanie, wyszukiwanie po nazwie, filtrowanie po Gatunku i cenie, strona Gry
- Zamówienie i Płatność: zakup Gry przez zewnętrzny System płatności, nadanie Licencji
- Biblioteka gier: lista Gier Gracza, pobieranie aktualnej Wersji gry, ukrycie Gry
- Oceny i Recenzje Gier wystawiane przez Graczy z Licencją
- Panel Wydawcy: Konto deweloperskie, dodawanie Gry i Wersji gry, ustalanie ceny i Promocji, lista własnych Gier
- Reklamacje i Zwroty: złożenie Reklamacji, rozpatrzenie przez Agenta wsparcia, Zwrot przez System płatności
- Moderacja: weryfikacja Gier przed publikacją, usuwanie Recenzji, Zgłoszenia naruszenia, blokowanie Kont (Administrator)

### Poza zakresem (świadomie wyłączone)

- Własny program do uruchamiania Gier (launcher) i automatyczne pobieranie nowych Wersji gry na urządzenie Gracza
- Funkcje społecznościowe poza Ocenami i Recenzjami: znajomi, czat, grupy, fora
- Natywna aplikacja mobilna (platforma działa w przeglądarce, także na telefonie)
- Handel przedmiotami z Gier między Graczami i portfel środków na platformie
- Wiele walut i języków (MVP: PLN, język polski)

### Możliwe rozszerzenia (po MVP)

- Lista życzeń i powiadomienia o Promocjach
- Rekomendacje Gier dopasowane do Gracza
- Własne kolekcje i ulubione Gry w Bibliotece gier
- Osiągnięcia i statystyki czasu gry
- Logowanie przez konta zewnętrzne (Google)
- Wersja anglojęzyczna i inne waluty

## 1.6. Kontekst i systemy zewnętrzne

## 1.7. Założenia i ograniczenia

| Typ | Opis |
|---|---|
| Założenie | np. użytkownicy mają dostęp do Internetu i przeglądarki |
| Ograniczenie | np. budżet: wyłącznie darmowe/otwarte technologie; realizacja w 1 semestr przez zespół N-osobowy |

## 1.8. Rozwiązania konkurencyjne / analiza istniejących narzędzi

| Rozwiązanie | Co robi dobrze | Czego brakuje | Wniosek dla naszego projektu |
|---|---|---|---|
| | | | |
