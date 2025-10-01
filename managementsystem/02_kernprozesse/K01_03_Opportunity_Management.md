# K01.03 Opportunity-Management

**Zweck:** Dieser Teilprozess beschreibt die systematische Bearbeitung von qualifizierten Verkaufschancen (Opportunities), von der ersten Analyse bis zum Vertragsabschluss oder dem Verlust der Opportunity. Ziel ist es, die Abschlusswahrscheinlichkeit zu maximieren.

**Geltungsbereich:** Der Prozess beginnt mit der Annahme eines "Sales Qualified Leads" (SQL) aus dem [Lead-Management](./K01_02_Lead_Management.md) und endet mit der Unterzeichnung des Vertrags oder der Entscheidung, die Verkaufschance nicht weiter zu verfolgen.

| | |
| :--- | :--- |
| **Prozesseigner** | [Sales Manager](../rollen/R03_Sales_Manager.md) |
| **Input** | `Sales Qualified Lead (SQL)`, `Kundenanforderungen` |
| **Output** | `Gewonnener Auftrag (Vertrag)`, `Verlorene Opportunity mit Begründung`, `Angebot` |

---

## Prozessschritte

1.  **Opportunity-Analyse und -Qualifizierung**:
    -   Der übernommene SQL wird vom zuständigen Vertriebsmitarbeiter detailliert analysiert.
    -   Es wird geprüft, ob die Kundenanforderungen mit dem Lösungsportfolio der RDS übereinstimmen und ob ein realistisches Budget und ein Zeitplan vorhanden sind.
    -   Die Opportunity wird im [CRM-System](../artefakte/A03_CRM_Leitfaden.md) angelegt und bewertet (z.B. nach Umsatzpotenzial, strategischer Relevanz).
    -   **Verantwortlich**: [Sales Manager](../rollen/R03_Sales_Manager.md) / [Account Manager](../rollen/R04_Account_Manager.md)

2.  **Lösungserarbeitung und Präsentation**:
    -   In Zusammenarbeit mit den Fachexperten aus "Services" oder "Solutions" wird eine passende Lösung für die Kundenanforderung konzipiert.
    -   Die erarbeitete Lösung wird dem Kunden präsentiert.
    -   **Verantwortlich**: [Sales Manager](../rollen/R03_Sales_Manager.md) / [Account Manager](../rollen/R04_Account_Manager.md)

3.  **Angebotserstellung**:
    -   Basierend auf der konzipierten Lösung wird ein formales Angebot erstellt.
    -   Dieser Schritt folgt dem Teilprozess [Angebots- und Vertragserstellung](./K01_04_Angebot_Vertrag.md).
    -   **Verantwortlich**: [Sales Manager](../rollen/R03_Sales_Manager.md) / [Account Manager](../rollen/R04_Account_Manager.md)

4.  **Verhandlung und Abschluss**:
    -   Das Angebot wird mit dem Kunden verhandelt (Preise, Konditionen, Leistungsumfang).
    -   Ziel ist die Erzielung einer Einigung und die Unterzeichnung des Vertrags.
    -   **Verantwortlich**: [Sales Manager](../rollen/R03_Sales_Manager.md) / [Account Manager](../rollen/R04_Account_Manager.md)

5.  **Opportunity-Abschluss (Won/Lost)**:
    -   Der Status der Opportunity wird im CRM-System auf "Gewonnen" oder "Verloren" gesetzt.
    -   Bei "Verloren" wird der Grund für die Entscheidung dokumentiert, um daraus für die Zukunft zu lernen.
    -   Bei "Gewonnen" wird der Auftrag an die relevanten Folgeprozesse übergeben (z.B. [K02 Service Transition](./K02_Service_Transition.md) oder [K04 Lösungsrealisierung](./K04_Loesungsrealisierung.md)).
    -   **Verantwortlich**: [Sales Manager](../rollen/R03_Sales_Manager.md) / [Account Manager](../rollen/R04_Account_Manager.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Sales Manager](../rollen/R03_Sales_Manager.md)
    - [Account Manager](../rollen/R04_Account_Manager.md)
    - [Geschäftsführer Vertrieb](../rollen/R01_Geschaeftsfuehrer_Vertrieb.md)
- **Artefakte**:
    - [Angebot Vorlage](../artefakte/A02_Angebot_Vorlage.md)
    - [Vertrag](../artefakte/A01_Vertrag.md)
- **KPIs**:
    - [KPI03: Auftragseingang (in €)](../kpis/KPI03_Auftragseingang.md)
- **Systeme**:
    - [CRM-System](../artefakte/A03_CRM_Leitfaden.md)