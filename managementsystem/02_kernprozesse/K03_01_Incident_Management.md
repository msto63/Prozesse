# K03.01 Incident Management

**Zweck:** Das Ziel des Incident Managements ist die schnellstmögliche Wiederherstellung des normalen Servicebetriebs und die Minimierung der negativen Auswirkungen von Störungen (Incidents) auf das Geschäft des Kunden.

**Geltungsbereich:** Der Prozess beginnt mit der Meldung einer Störung und endet mit der Bestätigung der Lösung durch den Anwender.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Services](../rollen/R10_Leiter_Services.md) |
| **Input** | `Meldung einer Störung (Anruf, E-Mail etc.)` |
| **Output** | `Gelöster Incident`, `Wiederhergestellter Service`, `Aktualisiertes [Ticket](../artefakte/A09_Ticket.md)` |

---

## Prozessschritte

1.  **Incident-Erfassung & Protokollierung**:
    -   Annahme der Störungsmeldung über einen beliebigen Kanal.
    -   Erstellung eines neuen [Tickets](../artefakte/A09_Ticket.md) im ITSM-Tool mit allen relevanten Informationen (Anwender, Symptome, betroffenes System).
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

2.  **Incident-Klassifizierung & Priorisierung**:
    -   Kategorisierung des Incidents (z.B. Hardware, Software, Netzwerk).
    -   Einstufung der Priorität basierend auf der im [SLA](../artefakte/A08_SLA.md) definierten Matrix aus Auswirkung (Anzahl betroffener User) und Dringlichkeit (wie kritisch ist der Service).
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

3.  **Erstlösungsversuch (First-Level-Support)**:
    -   Abgleich der Symptome mit der [Wissensdatenbank](../artefakte/A10_Wissensartikel.md).
    -   Versuch, den Incident mit bekannten Lösungen oder standardisierten Prozeduren direkt zu beheben.
    -   Bei Erfolg wird der Incident gelöst und der Anwender informiert.
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

4.  **Incident-Eskalation (falls Erstlösung scheitert)**:
    -   Wenn keine Erstlösung möglich ist, wird der Incident an eine definierte, spezialisierte Support-Gruppe (2nd/3rd Level) weitergeleitet.
    -   Die Eskalation erfolgt inklusive aller bisher gesammelten Informationen im Ticket.
    -   **Funktionale Eskalation**: Weitergabe an ein Team mit mehr technischem Spezialwissen.
    -   **Hierarchische Eskalation**: Hinzuziehen eines Vorgesetzten ([Teamleiter](../rollen/R13_Teamleiter_Service_Desk.md), [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)), z.B. bei drohender SLA-Verletzung.
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

5.  **Untersuchung & Diagnose (im 2nd/3rd Level)**:
    -   Tiefgehende Analyse des Incidents durch die Spezialisten.
    -   Entwicklung einer Lösung oder eines Workarounds.
    -   **Verantwortlich**: Spezialisierte Support-Teams

6.  **Lösung & Wiederherstellung**:
    -   Implementierung der Lösung.
    -   Überprüfung, ob der Service wieder normal funktioniert.
    -   Dokumentation der Lösung im Ticket.
    -   **Verantwortlich**: Zuständiger Bearbeiter (1st, 2nd oder 3rd Level)

7.  **Incident-Abschluss**:
    -   Bestätigung durch den Anwender, dass die Störung behoben wurde.
    -   Formale Schließung des Tickets im ITSM-Tool.
    -   **Verantwortlich**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)
    - [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md)
- **Artefakte**:
    - [Ticket](../artefakte/A09_Ticket.md)
    - [SLA](../artefakte/A08_SLA.md)
    - [Wissensdatenbank-Artikel](../artefakte/A10_Wissensartikel.md)
- **KPIs**:
    - [Erstlösungsrate](../kpis/KPI07_Erstloesungsrate.md)
    - [Durchschnittliche Lösungszeit](../kpis/KPI08_Loesungszeit_Incidents.md)
    - [SLA-Erfüllungsgrad](../kpis/KPI09_SLA_Erfuellung.md)