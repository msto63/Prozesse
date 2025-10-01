# K03.03 Problem Management

**Zweck:** Das Ziel des Problem Managements ist die Minimierung der negativen Auswirkungen von Incidents auf den Geschäftsbetrieb, indem deren eigentliche Ursachen (Root Causes) identifiziert und dauerhaft beseitigt werden. Es agiert proaktiv, um das wiederholte Auftreten von Incidents zu verhindern.

**Geltungsbereich:** Der Prozess beschäftigt sich mit der Analyse von wiederkehrenden oder schwerwiegenden Incidents.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Services](../rollen/R10_Leiter_Services.md) |
| **Input** | `Analyse von Incident-Daten`, `Major Incidents`, `Hinweise vom Support-Team` |
| **Output** | `Identifizierte Problem-Ursache (Root Cause)`, `Known Error Record`, `Change Request zur Fehlerbehebung` |

---

## Prozessschritte

1.  **Problem-Identifikation**:
    -   Proaktive Analyse von [Ticket-Daten](../artefakte/A09_Ticket.md), um wiederkehrende Incidents zu identifizieren.
    -   Erstellung eines "Problem Records" nach einem schwerwiegenden Incident (Major Incident).
    -   Meldung eines potenziellen Problems durch einen [Service Desk Agenten](../rollen/R12_Service_Desk_Agent.md) oder [Teamleiter](../rollen/R13_Teamleiter_Service_Desk.md).
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md), [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md)

2.  **Problem-Protokollierung und -Kategorisierung**:
    -   Erstellung eines neuen Problem-Tickets im ITSM-Tool, das mit allen zugehörigen Incident-Tickets verknüpft wird.
    -   Kategorisierung und Priorisierung des Problems basierend auf den Auswirkungen auf den Kunden.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

3.  **Problem-Untersuchung und -Diagnose**:
    -   Systematische Ursachenanalyse (Root Cause Analysis), z.B. mittels "5 Whys" oder Ishikawa-Diagramm.
    -   Dies geschieht oft in Zusammenarbeit mit technischen Spezialisten (2nd/3rd Level).
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md), technische Spezialisten

4.  **Workaround-Identifikation**:
    -   Falls eine sofortige Behebung der Ursache nicht möglich ist, wird ein temporärer Workaround entwickelt und in der [Wissensdatenbank](../artefakte/A10_Wissensartikel.md) dokumentiert.
    -   Dieser Workaround hilft dem [Incident Management](./K03_01_Incident_Management.md), die Auswirkungen zukünftiger Incidents zu minimieren, bis die endgültige Lösung da ist.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

5.  **Erstellung eines "Known Error Records"**:
    -   Sobald die Ursache und ein Workaround bekannt sind, wird das Problem zu einem "bekannten Fehler" (Known Error).
    -   Dieser wird in einer "Known Error Database" (KEDB) dokumentiert, die oft Teil der allgemeinen Wissensdatenbank ist.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

6.  **Initiierung der Fehlerbehebung**:
    -   Um die Ursache endgültig zu beseitigen, ist oft eine Änderung am IT-System notwendig.
    -   Das Problem Management initiiert hierfür einen "Request for Change" (RFC), der dann im Change-Management-Prozess behandelt wird.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

7.  **Problem-Abschluss**:
    -   Nachdem die Ursache durch den Change erfolgreich beseitigt wurde, wird das Problem-Ticket geschlossen.
    -   Der Erfolg der Maßnahme wird überwacht, indem geprüft wird, ob die zugehörigen Incidents weiterhin auftreten.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)
    - [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md)
- **Artefakte**:
    - [Ticket](../artefakte/A09_Ticket.md)
    - [Wissensdatenbank-Artikel](../artefakte/A10_Wissensartikel.md)