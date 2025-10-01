# KPI19: Verfügbarkeit interner Kernsysteme

## Beschreibung

Diese Kennzahl misst die prozentuale Zeit, in der die als kritisch eingestuften internen IT-Systeme (z.B. E-Mail-Server, ERP-System, zentrales Filesharing) während der definierten Servicezeiten verfügbar und funktionsfähig sind.

## Messung

-   **Formel**: ( (Vereinbarte Servicezeit - Summe der Ausfallzeiten) / Vereinbarte Servicezeit ) * 100%
-   **Datenquelle**: Monitoring-Systeme, die die Erreichbarkeit der Systeme permanent überprüfen.
-   **Messfrequenz**: Monatlich.

## Ziele

-   **Zielwert**: > 99,8%
-   **Schwellenwert (Gelb)**: 99,5% - 99,8%
-   **Schwellenwert (Rot)**: < 99,5%

## Prozess-Verwendung

-   Zentrale Kennzahl zur Bewertung der Effektivität des Teilprozesses [U04.03 Server- & Netzwerk-Betrieb](../03_unterstuetzungsprozesse/U04_03_Server_Netzwerk_Betrieb.md).
-   Ein Nichterreichen der Ziele löst eine Analyse im Rahmen des [IT-Sicherheitsmanagements](../03_unterstuetzungsprozesse/U04_04_IT_Sicherheitsmanagement.md) oder des internen Problem Managements aus.

## Verantwortlich

-   **Datenerfassung**: Monitoring-System (automatisiert).
-   **Analyse & Reporting**: [Leiter IT](../rollen/R16_Leiter_IT.md).