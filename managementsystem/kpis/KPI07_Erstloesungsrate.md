# KPI07: Erstlösungsrate (First Contact Resolution - FCR)

## Beschreibung

Diese Kennzahl misst den prozentualen Anteil der Anfragen (Incidents und Service Requests), die vom [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md) direkt beim ersten Kontakt mit dem Anwender gelöst werden können, ohne dass eine Eskalation an eine nachgelagerte Support-Einheit oder ein erneuter Kontakt durch den Anwender notwendig ist.

## Messung

-   **Formel**: (Anzahl der im Erstkontakt gelösten Tickets / Anzahl aller erfassten Tickets) * 100%
-   **Datenquelle**: ITSM-Tool ([Ticket-Daten](../artefakte/A09_Ticket.md)). Die Messung erfolgt oft durch ein spezielles Feld "Im Erstkontakt gelöst?", das vom Agenten gesetzt wird.
-   **Messfrequenz**: Monatlich.

## Ziele

-   **Zielwert**: > 70% (kann je nach Komplexität des Services variieren).
-   **Schwellenwert (Gelb)**: 60% - 70%.
-   **Schwellenwert (Rot)**: < 60%.

## Prozess-Verwendung

-   Zentrale Kennzahl zur Messung der Effizienz des [Incident Managements](../02_kernprozesse/K03_01_Incident_Management.md) und [Service Request Fulfillments](../02_kernprozesse/K03_02_Service_Request_Fulfillment.md).
-   Ein hoher FCR-Wert korreliert oft mit einer hohen [Anwenderzufriedenheit](../kpis/KPI10_Anwenderzufriedenheit.md).
-   Ist Teil des [Kunden-Reportings](../artefakte/A11_Kunden_Reporting.md).

## Verantwortlich

-   **Datenerfassung**: [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md) (durch korrekte Ticket-Dokumentation).
-   **Analyse & Reporting**: [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md), [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md).