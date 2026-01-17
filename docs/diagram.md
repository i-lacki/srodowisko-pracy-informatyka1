# Diagram Flowchart

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
