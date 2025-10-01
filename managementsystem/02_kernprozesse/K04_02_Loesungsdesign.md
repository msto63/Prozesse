# K04.02 Lösungsdesign & -konzeption

**Zweck:** Dieser Teilprozess dient dazu, auf Basis der freigegebenen Anforderungen ein detailliertes technisches Design und eine robuste Systemarchitektur zu entwickeln. Das Ergebnis ist die technische Blaupause für die Implementierung.

**Geltungsbereich:** Der Prozess beginnt nach der Freigabe des [Pflichtenhefts](../artefakte/A06_Pflichtenheft.md) und endet mit der Freigabe des Lösungsdesigns.

| | |
| :--- | :--- |
| **Prozesseigner** | [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md) |
| **Input** | `Freigegebenes Pflichtenheft` ([Artefakt A06](../artefakte/A06_Pflichtenheft.md)) |
| **Output** | `Lösungsdesign-Dokument`, `Technische Architektur-Spezifikation` (Teil von [A05](../artefakte/A05_Technische_Doku.md)) |

---

## Prozessschritte

1.  **Architekturentwurf (High-Level-Design)**:
    -   Definition der groben Systemstruktur und der Hauptkomponenten.
    -   Auswahl von geeigneten Architekturmustern (z.B. Microservices, Client-Server).
    -   Entscheidung über die Kerntechnologien, Frameworks und Plattformen.
    -   Berücksichtigung der nicht-funktionalen Anforderungen wie Skalierbarkeit, Sicherheit und Performance.
    -   **Verantwortlich**: [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)

2.  **Schnittstellendesign**:
    -   Spezifikation der internen und externen Schnittstellen (APIs) des Systems.
    -   Definition der Datenformate und Kommunikationsprotokolle.
    -   **Verantwortlich**: [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)

3.  **Datenbankdesign**:
    -   Entwurf des Datenmodells und des Datenbankschemas.
    -   Definition der Tabellen, Beziehungen und Datentypen.
    -   **Verantwortlich**: [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)

4.  **Detaildesign (Low-Level-Design)**:
    -   Detaillierte Ausarbeitung des Designs der einzelnen Komponenten und Module.
    -   Erstellung von Diagrammen (z.B. UML-Klassendiagramme, Sequenzdiagramme), um die Logik zu visualisieren.
    -   **Verantwortlich**: [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md), [Entwickler](../rollen/R08_Entwickler.md)

5.  **Design-Review und Freigabe**:
    -   Prüfung des erstellten Lösungsdesigns durch das Projektteam (Peer-Review), um die technische Stimmigkeit und Machbarkeit zu gewährleisten.
    -   Formale Freigabe des Designs durch den [Projektleiter](../rollen/R06_Projektleiter.md) und den [Softwarearchitekten](../rollen/R07_Softwarearchitekt.md).
    -   **Verantwortlich**: [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md), [Projektleiter](../rollen/R06_Projektleiter.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)
    - [Entwickler](../rollen/R08_Entwickler.md)
    - [Projektleiter](../rollen/R06_Projektleiter.md)
- **Artefakte**:
    - [Technische Dokumentation](../artefakte/A05_Technische_Doku.md)