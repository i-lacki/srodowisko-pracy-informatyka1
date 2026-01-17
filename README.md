# Opis Projektu: Aplikacja do zarządzania roślinami

## Cel projektu
Projekt dotyczy aplikacji pomagającej w **zarządzaniu domową roślinnością**. Rozwiązuje problem zapominania o podlewaniu i nawożeniu kwiatów.

## Grupa docelowa
* Hobbyści-ogrodnicy.
* Osoby początkujące (tzw. "zabójcy paprotek").

## Kluczowe funkcje
1. Baza posiadanych roślin.
2. **System powiadomień** o podlewaniu.
3. Dziennik wzrostu rośliny.



```mermaid
graph TD
    A[Start] --> B{Logowanie}
    B --> C[Lista Roślin]
    C --> D[Dodaj nową roślinę]
    D --> E[Zapis w bazie]
    C --> F[Szczegóły rośliny]
    F --> G[Akcja: Podlej]
    G --> H[Koniec]
    E --> C
