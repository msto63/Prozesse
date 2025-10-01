# A09 Ticket

## Beschreibung

Ein Ticket ist ein Datensatz im ITSM-Tool, der einen einzelnen Fall (einen Incident oder einen Service Request) repräsentiert. Es dient der lückenlosen Dokumentation, Nachverfolgung und Steuerung der Bearbeitung von der Erstellung bis zur Schließung.

## Inhalt eines Tickets

Ein Ticket sollte mindestens die folgenden Felder enthalten:

-   **Eindeutige Ticket-ID**.
-   **Anwenderinformationen**: Name, Unternehmen, Kontaktdaten.
-   **Klassifizierung**: Art des Tickets (Incident, Service Request).
-   **Priorität**: Einstufung nach Dringlichkeit und Auswirkung.
-   **Status**: Aktueller Bearbeitungsstatus (z.B. Neu, In Bearbeitung, Gelöst, Geschlossen).
-   **Betreff/Titel**: Kurze, prägnante Beschreibung des Anliegens.
-   **Beschreibung**: Detaillierte Beschreibung des Problems oder der Anfrage.
-   **Bearbeitungshistorie (Journal)**: Chronologische Aufzeichnung aller durchgeführten Aktionen, Kommunikationen und Lösungsversuche.
-   **Lösungsbeschreibung**: Detaillierte Beschreibung der zur Lösung führenden Schritte.
-   **Zugewiesener Bearbeiter/Team**.
-   **Zeitstempel**: Erstellungs-, Lösungs- und Schließungszeitpunkt.

## Prozess-Verwendung

-   Das Ticket ist das zentrale Arbeitsobjekt in den Teilprozessen [Incident Management](../02_kernprozesse/K03_01_Incident_Management.md) und [Service Request Fulfillment](../02_kernprozesse/K03_02_Service_Request_Fulfillment.md).
-   Es wird vom [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md) erstellt und bearbeitet.

## Verantwortlich

-   Der jeweils zugewiesene [Service Desk Agent](../rollen/R12_Service_Desk_Agent.md) ist für die Qualität und Vollständigkeit der Dokumentation in seinem Ticket verantwortlich.
-   Der [Teamleiter Service Desk](../rollen/R13_Teamleiter_Service_Desk.md) überwacht die Ticketqualität im Team.