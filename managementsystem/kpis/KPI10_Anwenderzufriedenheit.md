# KPI10: Anwenderzufriedenheit

## Beschreibung

Diese Kennzahl misst die Zufriedenheit der Endanwender mit der erbrachten Service-Desk-Leistung. Sie ist ein direkter Indikator für die wahrgenommene Qualität der Interaktion und der Problemlösung.

## Messung

-   **Methode**: Die Messung erfolgt in der Regel durch kurze Umfragen, die dem Anwender nach der Schließung eines [Tickets](../artefakte/A09_Ticket.md) per E-Mail zugesendet werden.
-   **Skala**: Oft wird eine Skala von 1-5 (sehr unzufrieden bis sehr zufrieden) oder eine einfache Daumen-hoch/Daumen-runter-Bewertung verwendet.
-   **Formel**: (Summe der erhaltenen positiven Bewertungen / Summe aller erhaltenen Bewertungen) * 100% oder Durchschnittswert der Bewertungen.
-   **Datenquelle**: Umfrage-Tool, ITSM-Tool.
-   **Messfrequenz**: Kontinuierlich, Auswertung monatlich.

## Ziele

-   **Zielwert**: > 4,5 von 5 Sternen oder > 90% positive Bewertungen.
-   **Schwellenwert (Gelb)**: 4,0 - 4,5 Sterne oder 80% - 90%.
-   **Schwellenwert (Rot)**: < 4,0 Sterne oder < 80%.

## Prozess-Verwendung

-   Gibt Aufschluss über die "weiche" Qualität des [K03 Service Operation](../02_kernprozesse/K03_Service_Operation.md) Prozesses.
-   Dient als wichtige Ergänzung zu den "harten" [SLA-Kennzahlen](../kpis/KPI09_SLA_Erfuellung.md).
-   Ist Bestandteil des [Kunden-Reportings](../artefakte/A11_Kunden_Reporting.md) und dient zur Identifikation von Verbesserungspotenzialen (z.B. Schulungsbedarf für Agents).

## Verantwortlich

-   **Datenerfassung**: ITSM-Tool / Umfrage-Tool (automatisiert).
-   **Analyse & Reporting**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md).