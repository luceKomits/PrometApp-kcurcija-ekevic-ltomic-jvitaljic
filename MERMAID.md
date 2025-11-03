```mermaid
flowchart TD
    A[Otvaranje aplikacije] --> B{Je li korisnik ulogiran?}
    B -- Ne --> C[Pregled vremena polazaka i stanica]
    B -- Da --> D[Pristup dodatnim opcijama profila]
    C --> E[Planiranje putovanja]
    D --> E
    E --> F{Kupovina karte/pokaza}
    F -- Dnevna karta --> G[Dodavanje novca u e-Novčanik]
    F -- Mjesečna/Godišnja karta --> H[Kupnja pokaza]
    G --> I[Aktivacija karte -> skeniranje QR koda]
    H --> I
    I --> J[Skeniranje karte prilikom ulaska u autobus]
    J --> K[Vožnja]
    K --> L[Pregled stanica u realnom vremenu]
    L --> M[Pomoć i korisnička podrška]
