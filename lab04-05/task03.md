# Zadanie 3: Realizacja pracy zespołowej
> 1. Temat pracy zespołowej 
> 2. Cele pracy (4 zdania)
> 3. Założenia pracy (systemu do realizacji)
> 4. Wymagania funkcjonalne i niefunkcjonalne
> 5. Dokumentowanie przypadków użycia
> 6. Przypisanie aktorów i nadanie im działan i powiązań
> 7. Budowa diagramu
> 8. Omówienie założeń diagramu

<br><br>

# Temat pracy zespołowej:
Kairo Habit App
Aplikacja mobilna do monitorowania i utrwalania nawyków z elementami grywalizacji i społeczności.

# Cele pracy
Celem pracy jest stworzenie funkcjonalnej aplikacji mobilnej umożliwiającej użytkownikom monitorowanie własnych nawyków oraz obserwowanie postępów znajomych. Projekt ma angażować użytkowników poprzez gamifikacje: system punktów, osiągnięć i rankingów. Dążymy do promowania zdrowych i produktywnych zachowań oraz budowania społeczności motywujących się nawzajem. Ostatecznym celem jest dostarczenie estetycznej, intuicyjnej i wydajnej aplikacji dostępnej dla systemów Android i iOS.

# Założenia pracy
- System ma być aplikacją mobilną (Android/iOS), wykonaną z użyciem frameworka wieloplatformowego - React Native

- Użytkownicy tworzą konta i definiują swoje nawyki (np. czytanie, ćwiczenia, nauka).

- Aplikacja śledzi postępy użytkownika, generuje statystyki (streak, wykresy, oś czasu).

- System wspiera funkcje społecznościowe: dodawanie znajomych, przeglądanie ich aktywności, wysyłanie powiadomień („pingów”).

- Backend oparty na REST API  + baza danych - PHP

# Wymagania funkcjonalne i niefunkcjonalne
## Wymagania funkcjonalne
- Rejestracja i logowanie użytkownika.

- Dodawanie, edycja i usuwanie nawyków (CRUD).

- Przegląd własnych postępów (streak, wykresy, oś czasu).

- Dodawanie znajomych i podgląd ich aktywności.

- System osiągnięć i powiadomień.

- Tryb skupienia i możliwość „zamrożenia” streaka.

- Możliwość pingowania znajomych.

- Dodawanie powiadomień do kalendarza.

- Personalizacja motywu aplikacji.

## Wymagania niefunkcjonalne
- Intuicyjny i estetyczny interfejs użytkownika (UI/UX).

- Wysoka dostępność i stabilność aplikacji.

- Bezpieczeństwo danych (szyfrowanie, uwierzytelnianie).

- Responsywność (działanie na różnych rozdzielczościach ekranów)

- Skalowalność backendu.

- Czas reakcji interfejsu < 1 sekunda.

- Zgodność z wytycznymi platform Android i iOS.

# Dokumentowanie przypadków użycia

| ID | Nazwa przypadku użycia| Aktor | Opis | Warunek początkowy | Wynik końcowy |
|---:|:---------------------:|:-----:|:-----|:-------------------|:--------------|
| **UC1** | Rejestracja użytkownika | Użytkownik | Użytkownik wypełnia formularz rejestracji i zakłada konto. | Brak konta | Konto utworzone i zapisane w bazie. |
| **UC2** | Dodanie nowego nawyku | Użytkownik | Użytkownik dodaje nowy nawyk do śledzenia. | Użytkownik zalogowany | Nawyk zapisany w systemie. |
| **UC3** | Przegląd postępów | Użytkownik | Użytkownik przegląda wykres i streak swoich aktywności. | Użytkownik posiada zapisane dane | Wyświetlenie statystyk. |
| **UC4** | Dodanie znajomego | Użytkownik | Użytkownik wysyła zaproszenie do znajomego. | Obaj użytkownicy posiadają konta | Znajomość zapisana w systemie. |
| **UC5** | Pingowanie znajomego | Użytkownik | Użytkownik motywuje znajomego do działania. | Obaj użytkownicy są znajomymi | Znajomy otrzymuje powiadomienie. |

<br>

# Przypisanie aktorów i nadanie im działan i powiązań
| Aktor | Opis roli | Powiązane przypadki użycia |
|:-----:|:----------|:---------------------------|
| **Użytkownik** | Główny aktor systemu. Rejestruje się, zarządza nawykami, przegląda statystyki. | UC1, UC2, UC3, UC4, UC5 |
| **System** | Przechowuje dane, generuje statystyki, obsługuje powiadomienia. | UC2, UC3, UC4 |
| **Znajomy** | Interaktywny element społeczny – odbiera powiadomienia i motywuje użytkownika. | UC4, UC5 |
| **Administrator** *(opcjonalny)* | Zarządza kontami i monitoruje poprawność działania aplikacji. | UC1–UC5 |


# Budowa diagramu
placeholder
![placeholder-for-diagram-or-text](resources/placeholder)

# Omówienie założeń diagramu
placeholder

