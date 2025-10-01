# K04 Lösungsrealisierung

**Zweck:** Dieser Prozess beschreibt die strukturierte Konzeption, Entwicklung, Prüfung und Implementierung von Digitalisierungslösungen. Er stellt sicher, dass die für den Kunden entwickelte Lösung dessen Anforderungen erfüllt, im vereinbarten Zeit- und Budgetrahmen geliefert wird und eine hohe Qualität aufweist.

**Geltungsbereich:** Der Prozess beginnt nach der Vertragsunterzeichnung ([K01](./K01_Marketing_Vertrieb.md)) und endet mit der erfolgreichen Übergabe der Lösung an den Kunden und den internen Support.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Solutions](../rollen/R05_Leiter_Solutions.md) |
| **Input** | `Unterzeichneter Vertrag` ([Artefakt A01](../artefakte/A01_Vertrag.md)), `Kundenanforderungen`, `Angebot` |
| **Output** | `Implementierte Lösung`, `Technische Dokumentation` ([Artefakt A05](../artefakte/A05_Technische_Doku.md)), `Abnahmeprotokoll` ([Artefakt A04](../artefakte/A04_Abnahmeprotokoll.md)), `Betriebshandbuch` |

---

## Teilprozesse

Der Prozess "Lösungsrealisierung" gliedert sich in die folgenden Teilprozesse:

| ID | Teilprozess | Beschreibung |
| :--- | :--- | :--- |
| K04.01 | [Anforderungsanalyse & Spezifikation](./K04_01_Anforderungsspezifikation.md) | Detaillierte Erhebung, Analyse und Dokumentation der funktionalen und nicht-funktionalen Anforderungen des Kunden. |
| K04.02 | [Lösungsdesign & -konzeption](./K04_02_Loesungsdesign.md) | Erarbeitung der technischen Architektur und des detaillierten Designs der Lösung auf Basis der spezifizierten Anforderungen. |
| K04.03 | [Entwicklung & Implementierung](./K04_03_Entwicklung_Implementierung.md) | Programmierung der Software, Konfiguration der Standardkomponenten und Aufbau der Systemlandschaft. |
| K04.04 | [Qualitätssicherung & Test](./K04_04_Qualitaetssicherung_Test.md) | Systematisches Testen der entwickelten Lösung gegen die Anforderungen, um Fehler zu identifizieren und die Qualität sicherzustellen. |
| K04.05 | [Deployment & Inbetriebnahme](./K04_05_Deployment_Inbetriebnahme.md) | Installation der Lösung in der Zielumgebung des Kunden und Vorbereitung auf den produktiven Betrieb. |
| K04.06 | [Abnahme & Übergabe](./K04_06_Abnahme_Uebergabe.md) | Formale Abnahme der Lösung durch den Kunden und Übergabe an den Betrieb oder die Kundenbetreuung ([K05](./K05_Kundenbetreuung.md)). |

## Prozess-KPIs

- **[KPI04: Termintreue (Meilensteine)](../kpis/KPI04_Termintreue.md)**
- **[KPI05: Budgettreue](../kpis/KPI05_Budgettreue.md)**
- **[KPI06: Anzahl kritischer Fehler nach Go-Live](../kpis/KPI06_Fehler_nach_GoLive.md)**

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Projektleiter](../rollen/R06_Projektleiter.md)
    - [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)
    - [Entwickler](../rollen/R08_Entwickler.md)
    - [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md)
- **Artefakte**:
    - [Lastenheft/Pflichtenheft](../artefakte/A06_Pflichtenheft.md)
    - [Testplan & Testfälle](../artefakte/A07_Testplan.md)