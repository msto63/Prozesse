# K04.03 Entwicklung & Implementierung

**Zweck:** Dieser Teilprozess beschreibt die eigentliche Erstellung der Softwarelösung. Hier werden die im Lösungsdesign spezifizierten Komponenten und Funktionen programmiert und konfiguriert.

**Geltungsbereich:** Der Prozess beginnt nach der Freigabe des Lösungsdesigns und endet, wenn die entwickelte Software für die Qualitätssicherung bereitgestellt wird.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Solutions](../rollen/R05_Leiter_Solutions.md) |
| **Input** | `Freigegebenes Lösungsdesign` ([Artefakt A05](../artefakte/A05_Technische_Doku.md)), `Pflichtenheft` ([Artefakt A06](../artefakte/A06_Pflichtenheft.md)) |
| **Output** | `Entwickelte Software (Source Code)`, `Kompilierte Anwendung`, `Durchgeführte Unit-Tests` |

---

## Prozessschritte

1.  **Einrichtung der Entwicklungsumgebung**:
    -   Aufsetzen der notwendigen Tools, wie Versionskontrollsystem (z.B. Git), IDEs und Build-Systeme.
    -   Bereitstellung der erforderlichen Bibliotheken und Abhängigkeiten.
    -   **Verantwortlich**: [Entwickler](../rollen/R08_Entwickler.md)

2.  **Implementierung der Komponenten**:
    -   Programmierung der einzelnen Softwaremodule, Klassen und Funktionen gemäß den Designvorgaben und Programmierrichtlinien.
    -   Regelmäßiges Einchecken des Codes in das Versionskontrollsystem.
    -   **Verantwortlich**: [Entwickler](../rollen/R08_Entwickler.md)

3.  **Durchführung von Unit-Tests**:
    -   Erstellung und Durchführung von automatisierten Tests für einzelne Code-Einheiten (Methoden, Klassen), um deren korrekte Funktionsweise isoliert sicherzustellen.
    -   Code-Coverage-Analysen zur Bewertung der Testabdeckung.
    -   **Verantwortlich**: [Entwickler](../rollen/R08_Entwickler.md)

4.  **Code-Reviews**:
    -   Gegenseitige Überprüfung des geschriebenen Codes durch andere Entwickler (Peer-Review), um die Code-Qualität zu verbessern, Fehler frühzeitig zu finden und Wissen zu teilen.
    -   Der [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md) prüft stichprobenartig die Einhaltung der Architekturvorgaben.
    -   **Verantwortlich**: [Entwickler](../rollen/R08_Entwickler.md), [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)

5.  **Integration und Build**:
    -   Zusammenfügen der einzelnen entwickelten Komponenten zu einem lauffähigen Gesamtsystem (Build).
    -   Idealerweise erfolgt dies automatisiert über einen Continuous-Integration-(CI)-Server.
    -   **Verantwortlich**: [Entwickler](../rollen/R08_Entwickler.md)

6.  **Bereitstellung für die Qualitätssicherung**:
    -   Installation der lauffähigen Anwendung auf einer dedizierten Testumgebung für den nächsten Prozessschritt.
    -   **Verantwortlich**: [Entwickler](../rollen/R08_Entwickler.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Entwickler](../rollen/R08_Entwickler.md)
    - [Softwarearchitekt](../rollen/R07_Softwarearchitekt.md)
- **Artefakte**:
    - [Technische Dokumentation](../artefakte/A05_Technische_Doku.md) (wird aktualisiert)
- **Systeme**:
    - Versionskontrollsystem (z.B. Git)
    - Bug-Tracking-System
    - CI/CD-Server