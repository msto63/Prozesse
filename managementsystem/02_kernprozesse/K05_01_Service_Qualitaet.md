# K05.01 Service-Qualität überwachen und berichten

**Zweck:** Dieser Teilprozess stellt eine kontinuierliche Überwachung der vereinbarten Service-Leistungen und eine transparente Kommunikation der Ergebnisse an den Kunden sicher. Er ist die operative Basis für eine vertrauensvolle Kundenbeziehung im "Services"-Geschäft.

**Geltungsbereich:** Dieser Prozess läuft kontinuierlich während der gesamten Vertragslaufzeit für Kunden des Geschäftsbereichs "Services".

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Services](../rollen/R10_Leiter_Services.md) |
| **Input** | `Laufender Service-Betrieb` ([K03](./K03_Service_Operation.md)), `SLA` ([Artefakt A08](../artefakte/A08_SLA.md)) |
| **Output** | `Erstelltes und präsentiertes Kunden-Reporting` ([Artefakt A11](../artefakte/A11_Kunden_Reporting.md)), `Protokoll des Service-Review-Meetings` |

---

## Prozessschritte

1.  **Leistungsdaten kontinuierlich überwachen**:
    -   Der [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md) überwacht laufend die Einhaltung der [SLA-Ziele](../kpis/KPI09_SLA_Erfuellung.md) und anderer relevanter KPIs im ITSM-Tool.
    -   Bei drohenden SLA-Verletzungen werden proaktiv Gegenmaßnahmen eingeleitet.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

2.  **Kunden-Reporting erstellen**:
    -   Am Ende jeder Berichtsperiode (z.B. monatlich) werden die Leistungsdaten aus den Systemen exportiert.
    -   Der [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md) erstellt auf Basis der Vorlage das [Kunden-Reporting](../artefakte/A11_Kunden_Reporting.md), analysiert die Daten und bereitet Kommentare und Handlungsempfehlungen vor.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

3.  **Service-Review-Meeting durchführen**:
    -   Regelmäßige, terminierte Meetings mit dem Kunden, um das Reporting zu präsentieren und die Service-Qualität der letzten Periode zu besprechen.
    -   Weitere Themen: besondere Vorkommnisse, laufende und geplante Verbesserungsmaßnahmen, Feedback des Kunden.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

4.  **Maßnahmen vereinbaren und nachverfolgen**:
    -   Im Meeting identifizierte Probleme oder Verbesserungspotenziale werden als Maßnahmen mit Verantwortlichkeiten und Fristen protokolliert.
    -   Der [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md) ist für die Nachverfolgung dieser Maßnahmen verantwortlich.
    -   **Verantwortlich**: [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md)
- **Artefakte**:
    - [Kunden-Reporting](../artefakte/A11_Kunden_Reporting.md)
    - [SLA](../artefakte/A08_SLA.md)