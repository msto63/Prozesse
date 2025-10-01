# K03.02 Service Request Fulfillment

**Zweck:** Das Ziel dieses Prozesses ist die effiziente und benutzerfreundliche Bearbeitung von Serviceanfragen (Service Requests). Service Requests sind standardisierte, vorab genehmigte Anfragen von Anwendern, z.B. nach Informationen, Beratung, einem Passwort-Reset oder Standard-Software.

**Geltungsbereich:** Der Prozess umfasst den gesamten Lebenszyklus einer Serviceanfrage von der Meldung bis zur Erfüllung.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Services](../rollen/R10_Leiter_Services.md) |
| **Input** | `Serviceanfrage eines Anwenders` |
| **Output** | `Erfüllte Serviceanfrage`, `Informierter Anwender`, `Aktualisiertes [Ticket](../artefakte/A09_Ticket.md)` |

---

## Prozessschritte

1.  **Anfrage-Erfassung & Protokollierung**:
    -   Annahme der Serviceanfrage über einen beliebigen Kanal (ein Self-Service-Portal mit einem Servicekatalog ist hier ideal).
    -   Erstellung eines neuen [Tickets](../artefakte/A09_Ticket.md) vom Typ "Service Request".
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

2.  **Validierung & Genehmigung**:
    -   Prüfung, ob es sich um eine valide Standardanfrage handelt und ob der Anwender berechtigt ist, diese zu stellen.
    -   Einholung eventuell erforderlicher Genehmigungen (z.B. vom Vorgesetzten des Anwenders bei Hardware-Bestellungen). Viele einfache Anfragen (wie Passwort-Resets) benötigen keine Genehmigung.
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

3.  **Ausführung des Requests**:
    -   Die eigentliche Erfüllung der Anfrage gemäß einer definierten Prozedur, die oft in der [Wissensdatenbank](../artefakte/A10_Wissensartikel.md) dokumentiert ist.
    -   Dies kann durch den [Service Desk Agenten](../rollen/R12_Service_Desk_Agent.md) selbst geschehen (z.B. Passwort-Reset) oder die Beauftragung einer anderen Abteilung beinhalten (z.B. die Beschaffung, um eine neue Maus zu versenden).
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md) oder beauftragte Stelle.

4.  **Abschluss und Bestätigung**:
    -   Information des Anwenders über die Erfüllung seiner Anfrage.
    -   Einholung einer Bestätigung, dass die Anfrage zu seiner Zufriedenheit erledigt wurde.
    -   Formale Schließung des Tickets.
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)
- **Artefakte**:
    - [Ticket](../artefakte/A09_Ticket.md)
    - [Wissensdatenbank-Artikel](../artefakte/A10_Wissensartikel.md)
- **KPIs**:
    - [SLA-Erfüllungsgrad](../kpis/KPI09_SLA_Erfuellung.md) (auch für Service Requests können Zielzeiten definiert sein)
    - [Anwenderzufriedenheit](../kpis/KPI10_Anwenderzufriedenheit.md)