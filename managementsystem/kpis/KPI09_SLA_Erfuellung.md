# KPI09: SLA-Erfüllungsgrad

## Beschreibung

Diese Kennzahl misst den prozentualen Anteil der Tickets (insbesondere Incidents), bei denen die im [Service Level Agreement (SLA)](../artefakte/A08_SLA.md) definierten Reaktions- und Lösungszeiten eingehalten wurden.

## Messung

-   **Formel**: (Anzahl der Tickets, bei denen alle SLA-Ziele eingehalten wurden / Anzahl aller SLA-relevanten Tickets) * 100%
-   Die Messung erfolgt oft getrennt für Reaktionszeit-SLAs und Lösungszeit-SLAs.
-   **Datenquelle**: ITSM-Tool ([Ticket-Daten](../artefakte/A09_Ticket.md)).
-   **Messfrequenz**: Monatlich.

## Ziele

-   **Zielwert**: > 95% (oder gemäß kundenspezifischem [SLA](../artefakte/A08_SLA.md)).
-   **Schwellenwert (Gelb)**: 90% - 95%.
-   **Schwellenwert (Rot)**: < 90%.

## Prozess-Verwendung

-   Wichtigste Kennzahl zur Überprüfung der vertraglichen Leistung im [K03 Service Operation](../02_kernprozesse/K03_Service_Operation.md) Prozess.
-   Ist der zentrale Bestandteil des [Kunden-Reportings](../artefakte/A11_Kunden_Reporting.md) und der Service-Review-Meetings.
-   Nichteinhaltung kann zu Pönalen führen.

## Verantwortlich

-   **Datenerfassung**: ITSM-Tool (automatisch).
-   **Analyse & Reporting**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md).