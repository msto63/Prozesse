# K04.04 Qualitätssicherung & Test

**Zweck:** Dieser Teilprozess beschreibt die systematische Überprüfung der entwickelten Software, um Fehler zu finden und sicherzustellen, dass alle im [Pflichtenheft](../artefakte/A06_Pflichtenheft.md) definierten Anforderungen erfüllt sind.

**Geltungsbereich:** Der Prozess beginnt mit der Bereitstellung einer testbaren Softwareversion und endet mit der Freigabe der Software für das Deployment.

| | |
| :--- | :--- |
| **Prozesseigner** | [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md) |
| **Input** | `Testbereite Software`, `Pflichtenheft` ([Artefakt A06](../artefakte/A06_Pflichtenheft.md)), `Testplan & Testfälle` ([Artefakt A07](../artefakte/A07_Testplan.md)) |
| **Output** | `Getestete Software`, `Testprotokoll`, `Fehlerreports`, `Freigabe für Deployment` |

---

## Prozessschritte

1.  **Testplanung und -vorbereitung**:
    -   Erstellung und Abstimmung des [Testplans](../artefakte/A07_Testplan.md), der die Strategie, den Umfang und den Zeitplan festlegt.
    -   Erstellung der detaillierten Testfälle auf Basis der Anforderungen.
    -   Aufbau der Testumgebung und Vorbereitung der Testdaten.
    -   **Verantwortlich**: [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md)

2.  **Testdurchführung**:
    -   Ausführung der definierten Testfälle (manuell oder automatisiert).
    -   Dies umfasst verschiedene Teststufen wie Integrationstests (Zusammenspiel der Komponenten) und Systemtests (Gesamtsystem gegen Anforderungen).
    -   Durchführung von nicht-funktionalen Tests (z.B. Last- und Performancetests).
    -   **Verantwortlich**: [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md)

3.  **Fehlermanagement**:
    -   Detaillierte Dokumentation aller gefundenen Abweichungen und Fehler (Bugs) in einem Bug-Tracking-System.
    -   Zuweisung der Fehler an die [Entwickler](../rollen/R08_Entwickler.md) zur Behebung.
    -   Priorisierung der Fehler in Absprache mit dem [Projektleiter](../rollen/R06_Projektleiter.md).
    -   **Verantwortlich**: [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md)

4.  **Retest und Regressionstest**:
    -   Nach der Behebung eines Fehlers wird gezielt nachgetestet, ob der Fehler behoben ist (Retest).
    -   Durchführung von Regressionstests, um sicherzustellen, dass durch die Fehlerbehebung keine neuen Fehler in bereits funktionierenden Teilen der Software entstanden sind.
    -   **Verantwortlich**: [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md)

5.  **Testabschluss und -reporting**:
    -   Erstellung eines finalen Testreports, der die durchgeführten Tests, die Ergebnisse und die verbleibenden bekannten Fehler zusammenfasst.
    -   Formale Testfreigabe, wenn die im Testplan definierten Endkriterien erfüllt sind.
    -   **Verantwortlich**: [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md), [Projektleiter](../rollen/R06_Projektleiter.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md)
    - [Entwickler](../rollen/R08_Entwickler.md)
    - [Projektleiter](../rollen/R06_Projektleiter.md)
- **Artefakte**:
    - [Testplan & Testfälle](../artefakte/A07_Testplan.md)
- **Systeme**:
    - Bug-Tracking-System
    - Testmanagement-Tool