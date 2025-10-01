# K03 Service Operation

**Zweck:** Dieser Prozess beschreibt die effiziente und effektive Erbringung der vertraglich vereinbarten IT-Service-Desk-Leistungen für unsere Kunden. Er stellt sicher, dass Störungen schnellstmöglich behoben, Serviceanfragen zeitnah bearbeitet und die vereinbarten Service Level eingehalten werden.

**Geltungsbereich:** Der Prozess umfasst alle Aktivitäten des täglichen Betriebs nach der erfolgreichen [Service Transition (K02)](./K02_Service_Transition.md). Er endet, wenn ein Ticket (Incident oder Service Request) zur Zufriedenheit des Anwenders gelöst wurde.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Services](../rollen/R10_Leiter_Services.md) |
| **Input** | `Eingehendes Ticket (Anruf, E-Mail, Portal)`, `Service Level Agreement (SLA)` ([Artefakt A08](../artefakte/A08_SLA.md)), `Wissensdatenbank` |
| **Output** | `Gelöstes Ticket`, `Zufriedener Anwender`, `Erfülltes SLA`, `Aktualisierter Wissensartikel` |

---

## Teilprozesse

Der Prozess "Service Operation" gliedert sich in die folgenden, an ITIL angelehnten Teilprozesse:

| ID | Teilprozess | Beschreibung |
| :--- | :--- | :--- |
| K03.01 | [Incident Management](./K03_01_Incident_Management.md) | Schnellstmögliche Wiederherstellung des normalen Servicebetriebs bei Störungen (Incidents), um die negativen Auswirkungen auf das Geschäft des Kunden zu minimieren. |
| K03.02 | [Service Request Fulfillment](./K03_02_Service_Request_Fulfillment.md) | Bearbeitung von Standardanfragen der Anwender, wie z.B. Passwort-Resets, Informationsanfragen oder die Bestellung von Standard-Hardware. |
| K03.03 | [Problem Management (proaktiv)](./K03_03_Problem_Management.md) | Analyse der Ursachen von wiederkehrenden Störungen, um zukünftige Incidents zu verhindern. |
| K03.04 | [Wissensmanagement im Betrieb](./K03_04_Wissensmanagement_Betrieb.md) | Pflege und Nutzung der Wissensdatenbank zur Steigerung der Effizienz und Lösungsqualität im Service Desk. |

## Prozess-KPIs

- **[KPI07: Erstlösungsrate (First Contact Resolution)](../kpis/KPI07_Erstloesungsrate.md)**
- **[KPI08: Durchschnittliche Lösungszeit von Incidents](../kpis/KPI08_Loesungszeit_Incidents.md)**
- **[KPI09: SLA-Erfüllungsgrad](../kpis/KPI09_SLA_Erfuellung.md)**
- **[KPI10: Anwenderzufriedenheit](../kpis/KPI10_Anwenderzufriedenheit.md)**

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)
    - [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md)
    - [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md)
- **Artefakte**:
    - [Ticket](../artefakte/A09_Ticket.md)
    - [Wissensdatenbank-Artikel](../artefakte/A10_Wissensartikel.md)
    - [Kunden-Reporting](../artefakte/A11_Kunden_Reporting.md)