# U03 Beschaffung

**Zweck:** Dieser Prozess regelt den Einkauf von Waren und Dienstleistungen, die für den Geschäftsbetrieb oder die Leistungserbringung an Kunden notwendig sind. Er soll eine bedarfsgerechte, wirtschaftliche und termingerechte Versorgung sicherstellen und dabei die Einhaltung von Budgets und Genehmigungsrichtlinien gewährleisten.

**Geltungsbereich:** Der Prozess umfasst den gesamten Beschaffungszyklus von der Bedarfsfeststellung bis zur Bezahlung der Rechnung.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md) |
| **Input** | `Bedarfsanforderung aus einem Fachbereich`, `Angebot eines Lieferanten` |
| **Output** | `Bestellung`, `Gelieferte Ware / Erbrachte Dienstleistung`, `Geprüfte [Rechnung](../artefakte/A21_Rechnung.md)` |

---

## Prozessschritte

Da der Beschaffungsprozess oft eine lineare Abfolge von Schritten ist, wird er hier direkt und nicht in separate Teilprozesse unterteilt.

1.  **Bedarf identifizieren und spezifizieren**:
    -   Ein Mitarbeiter oder ein Fachbereich stellt einen Bedarf fest (z.B. neue Software, Büromaterial, externe Beratung).
    -   Der Bedarf wird spezifiziert (Menge, Qualität, Anforderungen).
    -   **Verantwortlich**: Bedarfsträger (Mitarbeiter des Fachbereichs)

2.  **Angebotseinholung und Lieferantenauswahl**:
    -   Abhängig vom Bestellwert werden ein oder mehrere Angebote von potenziellen Lieferanten eingeholt.
    -   Die Angebote werden verglichen (Preis, Qualität, Lieferzeit).
    -   Der am besten geeignete Lieferant wird ausgewählt.
    -   **Verantwortlich**: Bedarfsträger, ggf. in Abstimmung mit der Fachbereichsleitung

3.  **Bestellung genehmigen**:
    -   Die geplante Bestellung wird zur Genehmigung vorgelegt. Der Genehmigungsworkflow ist nach dem Bestellwert gestaffelt:
        -   Bis X €: Genehmigung durch den direkten Vorgesetzten.
        -   Bis Y €: Zusätzliche Genehmigung durch den [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md).
        -   Über Y €: Zusätzliche Genehmigung durch die Geschäftsführung.
    -   Die Genehmigung prüft die sachliche Notwendigkeit und die Einhaltung des [Budgets](../artefakte/A23_Budgetplan.md).
    -   **Verantwortlich**: Zuständige Führungskraft / Management

4.  **Bestellung auslösen**:
    -   Nach der Genehmigung wird eine formale Bestellung an den Lieferanten gesendet.
    -   **Verantwortlich**: Bedarfsträger / Zentrale Einkaufsstelle

5.  **Wareneingang / Leistungserbringung prüfen**:
    -   Die gelieferte Ware oder erbrachte Dienstleistung wird vom Bedarfsträger auf Vollständigkeit und Qualität geprüft.
    -   Der Wareneingang oder die Leistungsabnahme wird dokumentiert.
    -   **Verantwortlich**: Bedarfsträger

6.  **Rechnungsprüfung und -freigabe**:
    -   Die eingehende [Rechnung](../artefakte/A21_Rechnung.md) des Lieferanten wird vom Bedarfsträger sachlich geprüft (stimmt die Rechnung mit der Lieferung/Leistung überein?).
    -   Mit der sachlichen Freigabe wird die Rechnung an die [Kreditorenbuchhaltung](./U02_01_Kreditoren_Debitoren.md) zur Bezahlung weitergeleitet.
    -   **Verantwortlich**: Bedarfsträger

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md)
    - [Buchhalter](../rollen/R19_Buchhalter.md)
    - Jede Führungskraft als Genehmigender
- **Artefakte**:
    - [Rechnung](../artefakte/A21_Rechnung.md)
    - [Budgetplan](../artefakte/A23_Budgetplan.md)