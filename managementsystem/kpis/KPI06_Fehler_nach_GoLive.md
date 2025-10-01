# KPI06: Anzahl kritischer Fehler nach Go-Live

## Beschreibung

Diese Kennzahl misst die Anzahl der kritischen Fehler (Bugs), die innerhalb eines definierten Zeitraums (z.B. die ersten 3 Monate) nach der produktiven Inbetriebnahme einer Lösung vom Kunden gemeldet werden. Ein kritischer Fehler verhindert die Nutzung wesentlicher Funktionen der Anwendung.

## Messung

-   **Formel**: Summe der als "kritisch" eingestuften Fehlermeldungen im definierten Zeitraum.
-   **Datenquelle**: Bug-Tracking-System, Service-Desk-Tool.
-   **Messfrequenz**: 3 Monate nach jedem Go-Live.

## Ziele

-   **Zielwert**: 0 kritische Fehler.
-   **Schwellenwert (Gelb)**: 1-2 kritische Fehler.
-   **Schwellenwert (Rot)**: > 2 kritische Fehler.

## Prozess-Verwendung

-   Dient zur Bewertung der Effektivität des [Qualitätssicherungs-Prozesses](../02_kernprozesse/K04_04_Qualitaetssicherung_Test.md) innerhalb der [Lösungsrealisierung](../02_kernprozesse/K04_Loesungsrealisierung.md).
-   Gibt Aufschluss über die Produktreife zum Zeitpunkt der Übergabe.

## Verantwortlich

-   **Datenerfassung**: [Projektleiter](../rollen/R06_Projektleiter.md) / [Kundenbetreuung](../02_kernprozesse/K05_Kundenbetreuung.md)
-   **Analyse & Reporting**: [Leiter Solutions](../rollen/R05_Leiter_Solutions.md)