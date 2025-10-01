# K02 Service Transition

**Zweck:** Dieser Prozess stellt sicher, dass neue oder geänderte Services für Kunden geplant, entworfen, aufgebaut, getestet und reibungslos in den Live-Betrieb ([K03 Service Operation](./K03_Service_Operation.md)) überführt werden. Er gewährleistet, dass der Service Desk vom ersten Tag an in der Lage ist, die vereinbarte Leistung in der geforderten Qualität zu erbringen.

**Geltungsbereich:** Der Prozess beginnt nach der Unterzeichnung eines neuen oder geänderten Service-Vertrags und endet mit der formellen Übergabe des Services an das operative Service-Desk-Team.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Services](../rollen/R10_Leiter_Services.md) |
| **Input** | `Unterzeichneter Vertrag` ([Artefakt A01](../artefakte/A01_Vertrag.md)), `Service Level Agreement (SLA)` ([Artefakt A08](../artefakte/A08_SLA.md)) |
| **Output** | `Betriebsbereiter Service`, `Geschultes Service-Desk-Team`, `Erstelltes Service-Handbuch` ([Artefakt A12](../artefakte/A12_Service_Handbuch.md)), `Go-Live-Freigabe` |

---

## Teilprozesse

Der Prozess "Service Transition" gliedert sich in die folgenden Teilprozesse:

| ID | Teilprozess | Beschreibung |
| :--- | :--- | :--- |
| K02.01 | [Transition-Planung und Kick-off](./K02_01_Transition_Planung.md) | Detaillierte Planung des Onboarding-Projekts und Durchführung eines Kick-off-Meetings mit dem Kunden und dem internen Team. |
| K02.02 | [Service-Setup und Konfiguration](./K02_02_Service_Setup.md) | Aufbau der technischen und prozessualen Infrastruktur, die für die Service-Erbringung notwendig ist (z.B. ITSM-Tool, Wissensdatenbank). |
| K02.03 | [Team-Onboarding und Schulung](./K02_03_Team_Onboarding.md) | Schulung des zugewiesenen [Service Desk Teams](../rollen/R12_Service_Desk_Agent.md) auf die spezifischen Anforderungen und Prozesse des neuen Kunden. |
| K02.04 | [Go-Live und Hypercare-Phase](./K02_04_Go_Live_Hypercare.md) | Die eigentliche Inbetriebnahme des Services und eine Phase intensiver Betreuung (Hypercare) direkt nach dem Go-Live. |

## Prozess-KPIs

- **[KPI11: Time-to-Onboard](../kpis/KPI11_Time_to_Onboard.md)**
- **[KPI12: Transition-Budgettreue](../kpis/KPI12_Transition_Budgettreue.md)**

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md) (agiert oft als Transition Manager)
    - [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md)
- **Artefakte**:
    - [Transition-Plan](../artefakte/A13_Transition_Plan.md)