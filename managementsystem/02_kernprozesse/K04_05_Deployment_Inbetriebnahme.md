# K04.05 Deployment & Inbetriebnahme

**Zweck:** Dieser Teilprozess beschreibt die Überführung der getesteten und freigegebenen Software in die produktive Zielumgebung des Kunden. Ziel ist eine reibungslose Inbetriebnahme mit minimaler Störung des Geschäftsbetriebs.

**Geltungsbereich:** Der Prozess beginnt nach der Testfreigabe und endet, wenn die Software in der Produktivumgebung lauffähig ist und für die Abnahme bereitsteht.

| | |
| :--- | :--- |
| **Prozesseigner** | [Projektleiter](../rollen/R06_Projektleiter.md) |
| **Input** | `Freigegebene Software`, `Installationsanleitung` (aus [A05](../artefakte/A05_Technische_Doku.md)), `Betriebskonzept` |
| **Output** | `Lauffähige Software in Produktivumgebung`, `Durchgeführter Deployment-Plan` |

---

## Prozessschritte

1.  **Deployment-Planung**:
    -   Erstellung eines detaillierten Plans für die Inbetriebnahme (Deployment Plan), der alle technischen Schritte, den Zeitplan (oft außerhalb der Geschäftszeiten), die Verantwortlichkeiten und einen Rollback-Plan enthält.
    -   Abstimmung des Plans mit dem Kunden und dessen IT-Abteilung.
    -   **Verantwortlich**: [Projektleiter](../rollen/R06_Projektleiter.md), [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)

2.  **Vorbereitung der Zielumgebung**:
    -   Sicherstellung, dass die Produktivumgebung des Kunden alle technischen Voraussetzungen erfüllt (Hardware, Software, Berechtigungen).
    -   Erstellung eines Backups des bestehenden Systems vor dem Deployment.
    -   **Verantwortlich**: [Entwickler](../rollen/R08_Entwickler.md) / IT-Betrieb des Kunden

3.  **Durchführung des Deployments**:
    -   Installation der Softwarekomponenten in der Produktivumgebung gemäß dem Deployment-Plan.
    -   Konfiguration der Anwendung und der angebundenen Systeme.
    -   Gegebenenfalls Migration von Daten aus einem Altsystem.
    -   **Verantwortlich**: [Entwickler](../rollen/R08_Entwickler.md)

4.  **Funktionstest (Smoke Test)**:
    -   Durchführung eines kurzen, oberflächlichen Tests in der Produktivumgebung, um die grundlegende Funktionsfähigkeit der installierten Anwendung zu überprüfen.
    -   **Verantwortlich**: [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md), [Entwickler](../rollen/R08_Entwickler.md)

5.  **Rollback (falls erforderlich)**:
    -   Falls der Smoke Test fehlschlägt oder schwerwiegende Probleme auftreten, wird der im Deployment-Plan definierte Rollback-Prozess ausgeführt, um das Altsystem wiederherzustellen.
    -   **Verantwortlich**: [Projektleiter](../rollen/R06_Projektleiter.md), [Entwickler](../rollen/R08_Entwickler.md)

6.  **Kommunikation der Inbetriebnahme**:
    -   Information an alle Stakeholder (insbesondere den Kunden und die zukünftigen Anwender) über die erfolgreiche Inbetriebnahme der neuen Software.
    -   **Verantwortlich**: [Projektleiter](../rollen/R06_Projektleiter.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Projektleiter](../rollen/R06_Projektleiter.md)
    - [Entwickler](../rollen/R08_Entwickler.md)
    - [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)
    - [Qualitätssicherungsingenieur](../rollen/R09_QS_Ingenieur.md)
- **Artefakte**:
    - [Technische Dokumentation](../artefakte/A05_Technische_Doku.md)