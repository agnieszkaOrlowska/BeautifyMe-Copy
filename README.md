# BeautifyMe

#### Tytuł aplikacji: BeautifyMe
Link do projektu interfejsu aplikacji:
https://www.figma.com/file/QtjEubLqRExxCAqHM0VqQz/BAI-Aplikacja?type=design&node-id=0%3A1&mode=design&t=JPsobhqlvsLXWL3f-1

## Opis aplikacji:
BeautifyMe to aplikacja umożliwiająca rezerwację wizyt kosmetycznych i fryzjerskich. Użytkownicy mogą łatwo umawiać się na spotkania z profesjonalistami branży urody.

## Szczegółowy opis funkcjonalności:
#### 1. Ekran startowy "O nas"
Na tym ekranie użytkownik może uzyskać informacje na temat BeautifyMe oraz skontaktować się z obsługą.

Funkcjonalności:

- Wyświetlenie informacji o aplikacji BeautifyMe.
- Prezentacja danych kontaktowych.
- Dostęp do górnej zakładki zawierającej "Home", "Rezerwacja", "O nas".

#### 2. Ekran logowania
Na tym ekranie użytkownik może zalogować się do swojego konta lub utworzyć nowe konto, jeśli jeszcze go nie posiada.

Funkcjonalności:

- Wyświetlenie pól do wprowadzenia danych logowania: adresu e-mail.
- Możliwość zalogowania się za pomocą istniejącego konta.
- Przypomnienie hasła - opcja umożliwiająca użytkownikowi odzyskanie hasła poprzez podanie adresu e-mail i wysłanie linku resetującego.
- Przejście do ekranu rejestracji - jeśli użytkownik nie posiada konta, może przejść do ekranu rejestracji, aby je utworzyć.
- Obsługa błędów - informowanie użytkownika o błędnie wprowadzonych danych logowania oraz komunikaty o problemach z połączeniem.
- Opcja zalogowania za pomocą konta Google - umożliwienie użytkownikowi szybkiego logowania za pomocą konta Google lub Facebook (opcjonalnie).
- Link do odwołania się do polityki prywatności oraz warunków użytkowania aplikacji.
- Dostęp do przycisku "Zaloguj się" lub "Zarejestruj się", w zależności od wybranej operacji.

#### 3. Ekran startowy aplikacji
Na tym ekranie użytkownik jest witany i zachęcany do sprawdzenia dostępych usług.

Funkcjonalności:

- Wyświetlenie powitalnego komunikatu: "Welcome to BeautifyMe!"

#### 4. Ekran rezerwacji 
Na tym ekranie użytkownik dokonuje rezerwacji wizyty, wybierając preferowany rodzaj usługi.

- Prezentacja opcji wyboru rodzaju usługi (kosmetyczne, fryzjerskie).
- Możliwość wyszukiwania usługi w wyszukiwarce.
- Dostęp do górnej zakładki zawierającej "Home", "Rezerwacja", "O nas".

#### 5. Szczegóły usługi
Na tym ekranie użytkownik przechodzi do dalszej części rezerwacji wizyty, wybierając preferowanego specjalistę, usługę oraz potwierdzając termin.

Funkcjonalności:

- Możliwość wyboru daty i godziny wizyty.
- Wyświetlenie dostępnych terminów wizyt.
- Możliwość wyboru preferowanego specjalisty.
- Wybór usługi (np. manicure, strzyżenie).
- Potwierdzenie rezerwacji poprzez przycisk "pay".

#### 6. Ekran metody płatności
Na tym ekranie użytkownik może wybrać preferowaną metodę płatności za usługę.

Funkcjonalności:

- Wyświetlenie listy dostępnych metod płatności: karta kredytowa, BLIK, Google Pay, PayPal.
- Możliwość wprowadzenia danych karty kredytowej:
Numer karty
Data ważności
Kod CVV
Imię i nazwisko posiadacza karty
- Obsługa płatności za pomocą BLIK:
- Możliwość wprowadzenia kodu BLIK
- Potwierdzenie transakcji za pomocą aplikacji bankowej
- Integracja z Google Pay:
Umożliwienie użytkownikowi skorzystania z opcji płatności za pomocą zapisanych kart w Google Pay.
- Opcja płatności za pomocą PayPal:
- Przekierowanie użytkownika do systemu PayPal w celu zalogowania się i autoryzacji transakcji.
- Obsługa błędów:
Informowanie użytkownika o błędach przy wprowadzaniu danych płatności (np. nieprawidłowy numer karty, data ważności, itp.).
- Komunikaty o problemach z połączeniem lub autoryzacją płatności.
- Potwierdzenie dokonania płatności:
Wyświetlenie potwierdzenia transakcji po jej pomyślnym zakończeniu.
- Przejście do ekranu podsumowania zamówienia po dokonaniu płatności.

## Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).
