# Macierz śledzenia wymagań

Każde wymaganie funkcjonalne z priorytetem M ma co najmniej jedną historyjkę. Kolumny UC/PB, Ekrany, Tabele, API i Testy uzupełniamy w M3 i M4 (puste pole = jeszcze nie opracowane).

| Wymaganie | Priorytet | Historyjki | UC / PB | Ekrany | Tabele / encje | Endpointy API | Testy | Uwagi |
|---|---|---|---|---|---|---|---|---|
| WF-01 | M | US-01 | | | | | | |
| WF-02 | M | US-02 | | | | | | |
| WF-04 | M | US-03 | | | | | | |
| WF-05 | M | US-04 | | | | | | |
| WF-06 | M | US-05 | | | | | | |
| WF-07 | M | US-06 | | | | | | |
| WF-08 | M | US-07 | | | | | | |
| WF-12 | M | US-09 | | | | | | |
| WF-13 | M | US-10 | | | | | | |
| WF-16 | M | US-11 | | | | | | |
| WF-17 | M | US-12 | | | | | | |
| WF-21 | M | US-15 | | | | | | |
| WNF-01 | M | — | | | | | | test obciążeniowy (np. k6 / JMeter) w środowisku testowym |
| WNF-03 | M | — | | | | | | przegląd kodu + test automatyczny logowania |
| WNF-04 | M | — | | | | | | skan konfiguracji TLS (np. SSL Labs, ocena ≥ A) + przegląd bazy danych |
| WNF-05 | M | — | | | | | | monitoring dostępności + test odtworzenia kopii zapasowej |
| WNF-07 | M | — | | | | | | przegląd z listą kontrolną z 08_bezpieczenstwo |
| WNF-08 | M | — | | | | | | test z 5 Graczami, którzy nie znają platformy |
| WNF-11 | M | — | | | | | | testy integracyjne w środowisku testowym (sandbox) operatora |
