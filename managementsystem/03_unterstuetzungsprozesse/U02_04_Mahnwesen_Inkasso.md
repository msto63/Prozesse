# U02.04 Mahnwesen & Inkasso

**Zweck:** Dieser Teilprozess beschreibt das standardisierte Vorgehen bei Zahlungsverzug von Kunden. Er soll sicherstellen, dass offene Forderungen systematisch und konsequent verfolgt werden, um die Liquidität des Unternehmens zu sichern und Forderungsausfälle zu minimieren.

**Geltungsbereich:** Der Prozess beginnt, wenn eine Ausgangsrechnung nach Ablauf des Zahlungsziels nicht bezahlt wurde, und endet mit dem Zahlungseingang oder der Ausbuchung der Forderung.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md) |
| **Input** | `Überfällige offene Forderung` |
| **Output** | `Bezahlte Forderung`, `Einleitung eines gerichtlichen Mahnverfahrens`, `Ausgebuchte Forderung` |

---

## Prozessschritte

1.  **Offene Posten identifizieren**:
    -   Der [Buchhalter](../rollen/R19_Buchhalter.md) überprüft regelmäßig (z.B. wöchentlich) die Liste der offenen Posten auf überfällige Rechnungen.
    -   **Verantwortlich**: [Buchhalter](../rollen/R19_Buchhalter.md)

2.  **Kaufmännisches Mahnverfahren durchführen**:
    -   Ein mehrstufiger, meist automatisierter Mahnlauf wird gestartet:
        -   **Stufe 1**: Freundliche Zahlungserinnerung kurz nach Fälligkeit.
        -   **Stufe 2**: Erste Mahnung mit einer neuen Zahlungsfrist.
        -   **Stufe 3**: Zweite und letzte Mahnung mit Androhung weiterer rechtlicher Schritte.
    -   Vor dem Versand der letzten Mahnung wird oft der zuständige [Account Manager](../rollen/R04_Account_Manager.md) oder [Service Delivery Manager](../rollen/R11_Service_Delivery_Manager.md) informiert, um eventuelle Missverständnisse (z.B. eine unerkannte Reklamation) auszuschließen.
    -   **Verantwortlich**: [Buchhalter](../rollen/R19_Buchhalter.md)

3.  **Übergabe an Inkasso oder Rechtsanwalt**:
    -   Bleibt die Zahlung auch nach der letzten Mahnung aus, wird der Fall an einen externen Partner (Inkassobüro oder Rechtsanwalt) übergeben.
    -   Diese Entscheidung wird vom [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md) getroffen.
    -   **Verantwortlich**: [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md)

4.  **Gerichtliches Mahnverfahren**:
    -   Der externe Partner beantragt einen gerichtlichen Mahnbescheid.
    -   Widerspricht der Schuldner nicht, kann ein Vollstreckungsbescheid erwirkt werden.
    -   **Verantwortlich**: Externer Partner

5.  **Forderungsausfall buchen**:
    -   Ist die Forderung uneinbringlich (z.B. bei Insolvenz des Kunden), wird sie als Forderungsausfall ausgebucht.
    -   **Verantwortlich**: [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Buchhalter](../rollen/R19_Buchhalter.md)
    - [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md)
- **KPIs**:
    - [Days Sales Outstanding (DSO)](../kpis/KPI21_DSO.md)