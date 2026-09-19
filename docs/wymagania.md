# Wymagania

## Wymagania funkcjonalne

Na podstawie diagramu przypadków użycia.

### Uczeń (Gość)
- Przeglądanie bazy zadań i działów
- Wyszukiwanie zadań po kryteriach
- Wrzucenie własnego zadania (upload)
- Rejestracja i logowanie (z podaniem daty urodzenia)

### Zalogowany Uczeń
- Dodawanie komentarza do rozwiązania
- Ocenianie rozwiązania
- Edycja/usunięcie własnego zgłoszonego zadania
- Przeglądanie własnego profilu i historii
- Wylogowanie

### Autor / Moderator
- Dodawanie nowych zadań i rozwiązań do bazy
- Zarządzanie bazą pytań i działów
- Zarządzanie kontami użytkowników

### Automatyzacja / integracje zewnętrzne
- Automatyczna kategoryzacja zgłoszonego zadania przy pomocy modelu LLM
- Dopasowanie rozwiązań z bazy na podstawie kategoryzacji
- Wykonywanie obliczeń przez kalkulator oparty o Wolfram Alpha API

### Reguły biznesowe
- Jeden użytkownik może wystawić tylko jedną ocenę dla danego rozwiązania.
- Zadanie zgłoszone przez ucznia ma status `OCZEKUJĄCE` do czasu decyzji moderatora
  (`ZATWIERDZONE` / `ODRZUCONE`) — założenie przyjęte przy diagramie klas i sekwencji,
  wymaga potwierdzenia.

## Wymagania niefunkcjonalne
<!-- TBD — do uzupełnienia po wyborze stacku technologicznego -->
- Wydajność:
- Bezpieczeństwo (hasła, dane osobowe uczniów):
- Dostępność / responsywność (urządzenia mobilne):
- Skalowalność bazy zadań:
