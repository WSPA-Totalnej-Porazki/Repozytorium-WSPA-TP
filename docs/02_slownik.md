# 02. Słownik pojęć dziedziny

| Pojęcie | Nazwa ang. (dla kodu) | Definicja | Synonimy (niezalecane) | Przykład | Powiązane pojęcia |
|---|---|---|---|---|---|
| Administrator | Administrator | Pracownik platformy z najwyższymi uprawnieniami. Moderuje Recenzje i Gry, zarządza Kontami i Katalogiem gier, nadzoruje działanie systemu. | moderator, admin | Administrator blokuje Konto, które publikuje obraźliwe Recenzje | Konto, Zgłoszenie naruszenia |
| Agent wsparcia | SupportAgent | Pracownik działu obsługi, który rozpatruje Reklamacje i odpowiada Graczom. Widzi historię Zamówień i czas gry Gracza. | konsultant, support | Agent wsparcia uznaje Reklamację i zleca Zwrot | Reklamacja, Zwrot, Gracz |
| Biblioteka gier | Library | Zbiór wszystkich Gier, do których Gracz ma Licencję. Z Biblioteki gier Gracz pobiera i uruchamia Gry. | półka | Biblioteka gier Gracza zawiera 42 Gry | Gracz, Licencja, Gra |
| Cena | Price | Kwota w złotych, za którą Gracz może kupić Grę. Cenę ustala Wydawca. W czasie Promocji obowiązuje cena obniżona. | koszt, opłata | 59,99 zł, w Promocji 41,99 zł | Gra, Promocja, Wydawca |
| Czas gry | Playtime | Łączny czas, przez który Gracz miał uruchomioną Grę. Agent wsparcia bierze go pod uwagę przy Reklamacji. | czas rozgrywki | 1 h 25 min | Gracz, Gra, Reklamacja |
| Dostawca tożsamości | IdentityProvider | Zewnętrzny system (Google), który potwierdza tożsamość osoby przy Logowaniu zewnętrznym. | Google, OAuth | Google potwierdza, że anna.k@gmail.com to właścicielka konta | Logowanie zewnętrzne, Konto |
| Gatunek | Genre | Kategoria Gry według jej rodzaju rozgrywki, służąca do filtrowania Katalogu gier. Gra może mieć kilka Gatunków. | tag | RPG, Strategia, Wyścigi | Gra, Katalog gier |
| Gra | Game | Produkt cyfrowy opublikowany przez Wydawcę, który Gracz może kupić, pobrać i uruchomić. Gra ma cenę, opis, Gatunki i Status gry. | tytuł, produkt | „Kosmiczna Farma 2”, cena 59,99 zł | Wydawca, Wersja gry, Gatunek, Status gry |
| Gracz | Player | Osoba z Kontem, która przegląda Katalog gier, kupuje Gry, gra w nie i wystawia Oceny oraz Recenzje. | użytkownik, kupujący | Gracz „nick_123” kupuje Grę w Promocji | Konto, Biblioteka gier, Zamówienie |
| Katalog gier | Catalog | Wszystkie Gry o Statusie gry OPUBLIKOWANA, które Gracz może przeglądać, wyszukiwać i filtrować. | sklep, oferta | Katalog gier filtrowany po Gatunku „Strategia” | Gra, Gatunek, Promocja |
| Konto | Account | Zarejestrowany dostęp osoby do platformy (login, e-mail, hasło). Konto ma rolę: Gracz, Wydawca, Agent wsparcia lub Administrator. | użytkownik | Konto z e-mailem jan@example.com i rolą Gracz | Gracz, Wydawca, Logowanie zewnętrzne, Rola konta |
| Konto deweloperskie | PublisherAccount | Konto z rolą WYDAWCA, które pozwala publikować Gry, wgrywać Wersje gry i ustalać ceny oraz Promocje. | panel dewelopera, konto wydawcy | Konto deweloperskie studia „Pixel Lublin” | Konto, Wydawca, Gra |
| Licencja | License | Prawo Gracza do korzystania z konkretnej Gry, nadawane po opłaceniu Zamówienia. Licencja trafia do Biblioteki gier i może zostać cofnięta po Zwrocie. | klucz, prawo do gry | Licencja Gracza na Grę „Kosmiczna Farma 2” | Biblioteka gier, Zamówienie, Zwrot |
| Lista życzeń | Wishlist | Lista Gier, które Gracz chce kupić w przyszłości. Poza MVP. | ulubione, obserwowane | 3 Gry na Liście życzeń Gracza | Gracz, Gra, Promocja |
| Logowanie zewnętrzne | ExternalLogin | Zalogowanie się do Konta kontem Google zamiast e-mailem i hasłem. Logowanie e-mailem i hasłem pozostaje dostępne. | logowanie Google, SSO | Gracz loguje się kontem anna.k@gmail.com | Konto, Gracz, Dostawca tożsamości |
| Ocena | Rating | Liczbowa ocena Gry wystawiona przez Gracza posiadającego Licencję, w skali 1–5. | gwiazdki, nota | Ocena 4/5 | Recenzja, Gra, Gracz |
| Płatność | Payment | Przekazanie pieniędzy za Zamówienie przez zewnętrzny System płatności. Płatność ma status (autoryzowana, odrzucona, zwrócona). | transakcja, przelew | Płatność 59,99 zł kartą, autoryzowana | Zamówienie, System płatności, Zwrot |
| Pobranie | Download | Skopiowanie plików aktualnej Wersji gry z platformy na urządzenie Gracza. Możliwe tylko dla Gry, na którą Gracz ma Licencję. | ściągnięcie, instalacja | Pobranie Wersji gry 1.2.0 (4,3 GB) | Biblioteka gier, Licencja, Wersja gry |
| Profil | Profile | Publiczne informacje o Graczu widoczne przy jego Recenzjach: nazwa wyświetlana i awatar. | strona gracza | Profil „nick_123” z awatarem | Gracz, Konto, Recenzja |
| Promocja | Promotion | Obniżka ceny Gry ustalona przez Wydawcę na określony czas. | wyprzedaż, rabat, zniżka | −30% na Grę od 01.12 do 07.12 | Gra, Wydawca |
| Recenzja | Review | Tekstowa opinia Gracza o Grze, którą posiada. Recenzję może usunąć Administrator. | opinia, komentarz | „Świetna fabuła, słaba optymalizacja” | Ocena, Gra, Administrator |
| Reklamacja | Complaint | Wniosek Gracza o zwrot pieniędzy za Grę, rozpatrywany przez Agenta wsparcia. Reklamacja ma Status reklamacji. | zgłoszenie, ticket, wniosek o zwrot | Reklamacja: Gra nie uruchamia się | Agent wsparcia, Zwrot, Zamówienie |
| Serwer e-mail | EmailService | Zewnętrzny system, który wysyła wiadomości e-mail do Graczy i Wydawców (np. potwierdzenie Zamówienia). | poczta, mailer | Wiadomość „Potwierdzenie Zamówienia nr 1024” | Gracz, Wydawca, Zamówienie |
| System płatności | PaymentProvider | Zewnętrzny system banku lub operatora, który autoryzuje Płatności i wykonuje Zwroty. | bank, bramka płatności | Operator płatności kartą/BLIK | Płatność, Zwrot |
| Usługa przechowywania plików | FileStorage | Zewnętrzny system, który przechowuje pliki Wersji gry i udostępnia je do Pobrania. | chmura, serwer plików, CDN | Pliki Wersji gry 1.2.0 (4,3 GB) | Wersja gry, Pobranie, Wydawca |
| Wersja gry | GameVersion | Konkretne wydanie plików Gry wgrane przez Wydawcę. Nowa Wersja gry to aktualizacja. | aktualizacja, patch, build | Wersja 1.2.0 z poprawkami błędów | Gra, Wydawca |
| Weryfikacja gry | GameVerification | Sprawdzenie przez Administratora, czy Gra przesłana przez Wydawcę spełnia regulamin, zanim zostanie opublikowana. Kończy się publikacją albo odrzuceniem z uzasadnieniem. | moderacja gry, akceptacja | Weryfikacja Gry „Kosmiczna Farma 2” zakończona publikacją | Gra, Administrator, Status gry |
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
