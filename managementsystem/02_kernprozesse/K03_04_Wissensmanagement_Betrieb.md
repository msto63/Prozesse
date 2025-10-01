# K03.04 Wissensmanagement im Betrieb

**Zweck:** Das Ziel dieses Prozesses ist die Sicherstellung, dass das für die Service-Erbringung notwendige Wissen den [Service Desk Agents](../rollen/R12_Service_Desk_Agent.md) in der richtigen Form und zur richtigen Zeit zur Verfügung steht. Er beschreibt den Lebenszyklus von [Wissensartikeln](../artefakte/A10_Wissensartikel.md).

**Geltungsbereich:** Der Prozess umfasst die Erstellung, Überprüfung, Veröffentlichung und Archivierung von Wissensartikeln.

| | |
| :--- | :--- |
| **Prozesseigner** | [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md) |
| **Input** | `Gelöstes Ticket mit neuer Lösung`, `Identifizierter Workaround aus dem Problem Management` |
| **Output** | `Neuer oder aktualisierter Wissensartikel` ([Artefakt A10](../artefakte/A10_Wissensartikel.md)), `Gepflegte Wissensdatenbank` |

---

## Prozessschritte

1.  **Wissensbedarf identifizieren**:
    -   Ein [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md) löst ein [Ticket](../artefakte/A09_Ticket.md) auf eine neue Art und Weise, für die es noch keinen Artikel gibt.
    -   Im [Problem Management](./K03_03_Problem_Management.md) wird ein Workaround für ein wiederkehrendes Problem identifiziert.
    -   Analyse von Ticket-Daten zeigt häufige Anfragen, die standardisiert werden könnten.
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md), [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

2.  **Artikel entwerfen**:
    -   Der [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md) oder ein Fachexperte erstellt einen Entwurf für einen neuen Wissensartikel.
    -   Der Entwurf wird gemäß der Vorlage für [Wissensartikel](../artefakte/A10_Wissensartikel.md) strukturiert und formuliert.
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

3.  **Review und Freigabe**:
    -   Der erstellte Entwurf wird von einem zweiten Mitarbeiter (z.B. einem erfahrenen Kollegen oder dem [Teamleiter](../rollen/R13_Teamleiter_Service_Desk.md)) auf technische Korrektheit, Verständlichkeit und Vollständigkeit geprüft.
    -   Nach erfolgreichem Review wird der Artikel zur Veröffentlichung freigegeben.
    -   **Verantwortlich**: [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md)

4.  **Veröffentlichung**:
    -   Der freigegebene Artikel wird in der Wissensdatenbank publiziert und steht somit allen relevanten Mitarbeitern zur Verfügung.
    -   **Verantwortlich**: [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md)

5.  **Wissensnutzung**:
    -   Die [Service Desk Agents](../rollen/R12_Service_Desk_Agent.md) nutzen die Wissensdatenbank aktiv bei jedem Ticket, um die [Erstlösungsrate](../kpis/KPI07_Erstloesungsrate.md) zu erhöhen und eine konsistente Servicequalität sicherzustellen.

6.  **Regelmäßige Pflege**:
    -   Wissensartikel werden bei Nutzung auf Aktualität geprüft. Veraltete Artikel werden markiert oder aktualisiert.
    -   Es finden regelmäßige Reviews statt, um die Qualität der Wissensdatenbank sicherzustellen.
    -   **Verantwortlich**: Alle [Service Desk Agents](../rollen/R12_Service_Desk_Agent.md) (laufende Aktualisierung), [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md) (geplante Reviews)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)
    - [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md)
- **Artefakte**:
    - [Wissensdatenbank-Artikel](../artefakte/A10_Wissensartikel.md)