# 02. Słownik pojęć dziedziny

| Pojęcie | Nazwa ang. (dla kodu) | Definicja | Synonimy (niezalecane) | Przykład | Powiązane pojęcia |
|---|---|---|---|---|---|
| Administrator | Administrator | Pracownik platformy z najwyższymi uprawnieniami. Moderuje Recenzje i Gry, zarządza Kontami i Katalogiem gier, nadzoruje działanie systemu. | moderator, admin | Administrator blokuje Konto, które publikuje obraźliwe Recenzje | Konto, Zgłoszenie naruszenia |
| Agent wsparcia | SupportAgent | Pracownik działu obsługi, który rozpatruje Reklamacje i odpowiada Graczom. Widzi historię Zamówień i czas gry Gracza. | konsultant, support | Agent wsparcia uznaje Reklamację i zleca Zwrot | Reklamacja, Zwrot, Gracz |
| Biblioteka gier | Library | Zbiór wszystkich Gier, do których Gracz ma Licencję. Z Biblioteki gier Gracz pobiera i uruchamia Gry. | półka | Biblioteka gier Gracza zawiera 42 Gry | Gracz, Licencja, Gra |
| Gatunek | Genre | Kategoria Gry według jej rodzaju rozgrywki, służąca do filtrowania Katalogu gier. Gra może mieć kilka Gatunków. | tag | RPG, Strategia, Wyścigi | Gra, Katalog gier |
| Gra | Game | Produkt cyfrowy opublikowany przez Wydawcę, który Gracz może kupić, pobrać i uruchomić. Gra ma cenę, opis, Gatunki i Status gry. | tytuł, produkt | „Kosmiczna Farma 2”, cena 59,99 zł | Wydawca, Wersja gry, Gatunek, Status gry |
| Gracz | Player | Osoba z Kontem, która przegląda Katalog gier, kupuje Gry, gra w nie i wystawia Oceny oraz Recenzje. | użytkownik, kupujący | Gracz „nick_123” kupuje Grę w Promocji | Konto, Biblioteka gier, Zamówienie |
| Katalog gier | Catalog | Wszystkie Gry o Statusie gry OPUBLIKOWANA, które Gracz może przeglądać, wyszukiwać i filtrować. | sklep, oferta | Katalog gier filtrowany po Gatunku „Strategia” | Gra, Gatunek, Promocja |
| Konto | Account | Zarejestrowany dostęp osoby do platformy (login, e-mail, hasło). Konto ma rolę: Gracz, Wydawca, Agent wsparcia lub Administrator. | profil, użytkownik | Konto z e-mailem jan@example.com i rolą Gracz | Gracz, Wydawca, Rola konta |
| Licencja | License | Prawo Gracza do korzystania z konkretnej Gry, nadawane po opłaceniu Zamówienia. Licencja trafia do Biblioteki gier i może zostać cofnięta po Zwrocie. | klucz, prawo do gry | Licencja Gracza na Grę „Kosmiczna Farma 2” | Biblioteka gier, Zamówienie, Zwrot |
| Ocena | Rating | Liczbowa ocena Gry wystawiona przez Gracza posiadającego Licencję, w skali 1–5. | gwiazdki, nota | Ocena 4/5 | Recenzja, Gra, Gracz |
| Płatność | Payment | Przekazanie pieniędzy za Zamówienie przez zewnętrzny System płatności. Płatność ma status (autoryzowana, odrzucona, zwrócona). | transakcja, przelew | Płatność 59,99 zł kartą, autoryzowana | Zamówienie, System płatności, Zwrot |
| Promocja | Promotion | Obniżka ceny Gry ustalona przez Wydawcę na określony czas. | wyprzedaż, rabat, zniżka | −30% na Grę od 01.12 do 07.12 | Gra, Wydawca |
| Recenzja | Review | Tekstowa opinia Gracza o Grze, którą posiada. Recenzję może usunąć Administrator. | opinia, komentarz | „Świetna fabuła, słaba optymalizacja” | Ocena, Gra, Administrator |
| Reklamacja | Complaint | Wniosek Gracza o zwrot pieniędzy za Grę, rozpatrywany przez Agenta wsparcia. Reklamacja ma Status reklamacji. | zgłoszenie, ticket, wniosek o zwrot | Reklamacja: Gra nie uruchamia się | Agent wsparcia, Zwrot, Zamówienie |
| System płatności | PaymentProvider | Zewnętrzny system banku lub operatora, który autoryzuje Płatności i wykonuje Zwroty. | bank, bramka płatności | Operator płatności kartą/BLIK | Płatność, Zwrot |
| Wersja gry | GameVersion | Konkretne wydanie plików Gry wgrane przez Wydawcę. Nowa Wersja gry to aktualizacja. | aktualizacja, patch, build | Wersja 1.2.0 z poprawkami błędów | Gra, Wydawca |
| Wydawca | Publisher | Firma lub osoba z Kontem deweloperskim, która publikuje Gry, ustala ceny i Promocje oraz wgrywa Wersje gry. | deweloper, twórca, studio | Niezależne studio „Pixel Lublin” | Gra, Promocja, Wersja gry |
| Zamówienie | Order | Zakup jednej lub kilku Gier przez Gracza. Po opłaceniu Zamówienia Gracz otrzymuje Licencje. | transakcja, koszyk | Zamówienie nr 1024 na 2 Gry, 89,98 zł | Gracz, Płatność, Licencja |
| Zgłoszenie naruszenia | ViolationReport | Informacja od Gracza, że Gra lub Recenzja narusza regulamin, rozpatrywana przez Administratora. | raport, skarga | Zgłoszenie: Recenzja zawiera wulgaryzmy | Administrator, Gra, Recenzja |
| Zwrot | Refund | Oddanie Graczowi pieniędzy za Grę po uznaniu Reklamacji, wykonywane przez System płatności. Po Zwrocie Licencja zostaje cofnięta. | refundacja | Zwrot 59,99 zł na kartę Gracza | Reklamacja, Płatność, Licencja |

## Wartości wyliczeniowe

### Status gry

| Wartość | Znaczenie |
|---|---|
| SZKIC | Wydawca przygotowuje Grę, nie jest widoczna w Katalogu gier |
| W_WERYFIKACJI | Gra czeka na sprawdzenie przez Administratora |
| OPUBLIKOWANA | Gra jest widoczna w Katalogu gier i można ją kupić |
| ZABLOKOWANA | Administrator wstrzymał sprzedaż, np. po Zgłoszeniu naruszenia |
| WYCOFANA | Wydawca zakończył sprzedaż; Gracze z Licencją nadal mają Grę w Bibliotece gier |

### Status zamówienia

| Wartość | Znaczenie |
|---|---|
| NOWE | Zamówienie utworzone, czeka na Płatność |
| OPŁACONE | Płatność potwierdzona, Licencje nadane |
| ANULOWANE | Płatność nie doszła do skutku lub Gracz zrezygnował |
| ZWRÓCONE | Po uznanej Reklamacji wykonano Zwrot |

### Status reklamacji

| Wartość | Znaczenie |
|---|---|
| ZŁOŻONA | Gracz złożył Reklamację |
| W_TOKU | Agent wsparcia rozpatruje Reklamację |
| UZNANA | Reklamacja zasadna, zlecono Zwrot |
| ODRZUCONA | Reklamacja niezasadna, Gracz otrzymał uzasadnienie |

### Rola konta

| Wartość | Znaczenie |
|---|---|
| GRACZ | Kupuje Gry i korzysta z Biblioteki gier |
| WYDAWCA | Publikuje Gry i zarządza nimi |
| AGENT_WSPARCIA | Rozpatruje Reklamacje |
| ADMINISTRATOR | Moderuje i zarządza platformą |
