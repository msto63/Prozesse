# U02.01 Kreditoren- & Debitorenbuchhaltung

**Zweck:** Dieser Teilprozess beschreibt die Verwaltung aller Forderungen (Debitoren) und Verbindlichkeiten (Kreditoren) des Unternehmens. Er stellt sicher, dass Rechnungen korrekt erstellt, versendet, bezahlt und verbucht werden.

**Geltungsbereich:** Der Prozess umfasst den gesamten Lebenszyklus von Eingangs- und Ausgangsrechnungen.

| | |
| :--- | :--- |
| **Prozesseigner** | [Leiter Finanzen & Controlling](../rollen/R18_Leiter_Finanzen.md) |
| **Input** | `Zu erstellende Ausgangsrechnung`, `Eingegangene Lieferantenrechnung` |
| **Output** | `Gebuchte und bezahlte Eingangsrechnung`, `Gebuchte und (hoffentlich) bezahlte Ausgangsrechnung` |

---

## Prozessschritte (Kreditorenbuchhaltung - Lieferanten)

1.  **Rechnungseingang und -prüfung**:
    -   Eingehende Lieferantenrechnungen werden zentral erfasst.
    -   Der [Buchhalter](../rollen/R19_Buchhalter.md) prüft die Rechnung auf formale Korrektheit (gemäß UStG).
    -   Die Rechnung wird zur sachlichen Prüfung und Freigabe an den zuständigen Fachbereich weitergeleitet.
    -   **Verantwortlich**: [Buchhalter](../rollen/R19_Buchhalter.md), Fachbereich

2.  **Buchung und Zahlung**:
    -   Nach der Freigabe wird die Rechnung vom [Buchhalter](../rollen/R19_Buchhalter.md) im Buchhaltungssystem erfasst (gebucht).
    -   Die Zahlung wird unter Berücksichtigung von Skontofristen termingerecht veranlasst.
    -   **Verantwortlich**: [Buchhalter](../rollen/R19_Buchhalter.md)

## Prozessschritte (Debitorenbuchhaltung - Kunden)

1.  **Rechnungserstellung**:
    -   Auf Basis von Vertragsdaten, Lieferscheinen oder Stundennachweisen wird die Ausgangsrechnung erstellt.
    -   **Verantwortlich**: Fachbereich, [Buchhalter](../rollen/R19_Buchhalter.md)

2.  **Rechnungsversand und Buchung**:
    -   Die erstellte Rechnung wird an den Kunden versendet.
    -   Die Forderung wird im Buchhaltungssystem erfasst.
    -   **Verantwortlich**: [Buchhalter](../rollen/R19_Buchhalter.md)

3.  **Zahlungseingangsüberwachung**:
    -   Die eingehenden Zahlungen auf den Bankkonten werden täglich überwacht.
    -   Eingehende Zahlungen werden mit den offenen Forderungen abgeglichen und ausgebucht.
    -   **Verantwortlich**: [Buchhalter](../rollen/R19_Buchhalter.md)

4.  **Mahnwesen anstoßen**:
    -   Wird eine Rechnung nicht innerhalb des Zahlungsziels bezahlt, wird der Prozess [U02.04 Mahnwesen & Inkasso](./U02_04_Mahnwesen_Inkasso.md) angestoßen.
    -   **Verantwortlich**: [Buchhalter](../rollen/R19_Buchhalter.md)

## Zugehörige Dokumente und Rollen

- **Rollen**:
    - [Buchhalter](../rollen/R19_Buchhalter.md)
- **Artefakte**:
    - [Rechnung](../artefakte/A21_Rechnung.md)
- **KPIs**:
    - [Days Sales Outstanding (DSO)](../kpis/KPI21_DSO.md)
    - [Einhaltung der Zahlungsziele](../kpis/KPI22_Einhaltung_Zahlungsziele.md)