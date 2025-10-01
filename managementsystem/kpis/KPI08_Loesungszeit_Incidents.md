# KPI08: Durchschnittliche Lösungszeit von Incidents

## Beschreibung

Diese Kennzahl misst die durchschnittliche Zeit, die vom Erfassen eines Incidents bis zu seiner endgültigen Lösung vergeht. Sie wird oft getrennt nach Prioritätsstufen betrachtet und ist ein direktes Maß für die Geschwindigkeit und Effektivität des Störungsbeseitigungsprozesses.

## Messung

-   **Formel**: Summe der Lösungszeiten aller Incidents einer Periode / Anzahl der gelösten Incidents in dieser Periode.
-   Die Lösungszeit pro Incident ist der `Zeitstempel (Lösung) - Zeitstempel (Erstellung)`.
-   Servicezeiten (gemäß [SLA](../artefakte/A08_SLA.md)) müssen bei der Berechnung berücksichtigt werden (d.h. die "Uhr" wird außerhalb der Servicezeiten angehalten).
-   **Datenquelle**: ITSM-Tool ([Ticket-Daten](../artefakte/A09_Ticket.md)).
-   **Messfrequenz**: Monatlich.

## Ziele

-   **Zielwerte**: Werden im [SLA](../artefakte/A08_SLA.md) pro Prioritätsstufe festgelegt (z.B. Kritisch: 4h, Hoch: 8h).
-   Die Zielerreichung wird im [SLA-Erfüllungsgrad](../kpis/KPI09_SLA_Erfuellung.md) gemessen. Diese KPI hier betrachtet den Durchschnittswert.

## Prozess-Verwendung

-   Zentrale Kennzahl zur Bewertung des [Incident Management](../02_kernprozesse/K03_01_Incident_Management.md) Prozesses.
-   Wichtiger Bestandteil des [Kunden-Reportings](../artefakte/A11_Kunden_Reporting.md).

## Verantwortlich

-   **Datenerfassung**: ITSM-Tool (automatisch durch Ticket-Bearbeitung).
-   **Analyse & Reporting**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md).