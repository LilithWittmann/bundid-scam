# BundID Scam

Die BundID ist ein zentrales Konto zur Identifizierung für alle Online-Anträge des Bundes. Sie wird auch von vielen Bundesländern und Kommunen eingesetzt.

## Wie funktioniert die BundID?
Die BundID nutzt den SAML-Standard, um die Identität des Nutzers zu bestätigen. Dazu leitet z.B. die Webseite der Stadt [Lingen](https://openrathaus.lingen.de/auth?redirect=https://openrathaus.lingen.de/) den Nutzer auf die BundID-Seite weiter. Dort kann sich der Nutzer mit seiner BundID anmelden und die Stadt Lingen erhält die Bestätigung, dass der Nutzer sich erfolgreich angemeldet hat.

Jede Webseite, die die BundID nutzt, muss sich bei der BundID registrieren und muss bei jeder Anfrage auch auf Basis einer kryptographischen Signatur bestätigen, dass sie die BundID nutzen darf.

Wenn es nun eine Sicherheitslücke in einer der Webseiten gibt, die die BundID offiziell nutzen, kann ein Angreifer die BundID missbrauchen, um einem Nutzer vorzugaukeln, dass er sich auf einer offiziellen Webseite befindet.
