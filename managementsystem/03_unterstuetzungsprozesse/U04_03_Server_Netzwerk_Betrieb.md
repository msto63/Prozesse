# U04.03 Server- & Netzwerk-Betrieb

**Zweck:** Dieser Teilprozess stellt den stabilen, performanten und sicheren Betrieb der zentralen IT-Infrastruktur des Unternehmens sicher. Er umfasst alle Aktivitäten, die notwendig sind, um die Verfügbarkeit der Backend-Systeme zu gewährleisten.

**Geltungsbereich:** Der Prozess umfasst alle Server (physisch und virtuell), Netzwerkkomponenten (Switches, Router, Firewalls, WLAN), Speichersysteme und Rechenzentrumsdienste.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter IT](../rollen/R16_Leiter_IT.md) |
| **Input** | `Anforderungen aus Projekten`, `Monitoring-Alarme`, `Sicherheitswarnungen` |
| **Output** | `Verfügbare und performante IT-Infrastruktur`, `Durchgeführte Backups`, `Installierte Updates` |

---

## Prozessschritte

1.  **System-Monitoring**:
    -   Kontinuierliche, automatisierte Überwachung der Systemgesundheit, Auslastung und Verfügbarkeit aller kritischen Infrastrukturkomponenten.
    -   Automatische Alarmierung bei Schwellenwertüberschreitungen oder Ausfällen.
    -   **Verantwortlich**: [IT-Administrator](../rollen/R17_IT_Administrator.md)

2.  **Regelmäßige Wartung**:
    -   Planung und Durchführung regelmäßiger Wartungsarbeiten (oft in Wartungsfenstern außerhalb der Geschäftszeiten).
    -   Dazu gehört das Einspielen von Firmware-Updates und Sicherheitspatches (Patch-Management).
    -   **Verantwortlich**: [IT-Administrator](../rollen/R17_IT_Administrator.md)

3.  **Backup und Recovery**:
    -   Tägliche Durchführung und Überprüfung der Datensicherungen (Backups) aller relevanten Systeme.
    -   Regelmäßige Durchführung von Wiederherstellungstests, um die Funktionsfähigkeit der Backups sicherzustellen.
    -   **Verantwortlich**: [IT-Administrator](../rollen/R17_IT_Administrator.md)

4.  **Kapazitätsmanagement**:
    -   Überwachung der Auslastung von Ressourcen wie CPU, Arbeitsspeicher, Speicherplatz und Netzwerkbandbreite.
    -   Proaktive Planung von Erweiterungen, um zukünftige Engpässe zu vermeiden.
    -   **Verantwortlich**: [Leiter IT](../rollen/R16_Leiter_IT.md), [IT-Administrator](../rollen/R17_IT_Administrator.md)

5.  **Störungsbehebung (3rd Level)**:
    -   Analyse und Behebung von komplexen Störungen an der Infrastruktur, die vom [internen IT-Support](./U04_02_Interner_IT_Support.md) eskaliert wurden.
    -   Im Notfall wird nach dem [IT-Notfallhandbuch](../artefakte/A20_IT_Notfallhandbuch.md) vorgegangen.
    -   **Verantwortlich**: [IT-Administrator](../rollen/R17_IT_Administrator.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [IT-Administrator](../rollen/R17_IT_Administrator.md)
    - [Leiter IT](../rollen/R16_Leiter_IT.md)
- **Artefakte**:
    - [IT-Notfallhandbuch](../artefakte/A20_IT_Notfallhandbuch.md)
- **KPIs**:
    - [Verfügbarkeit interner Kernsysteme](../kpis/KPI19_Verfuegbarkeit_Systeme.md)