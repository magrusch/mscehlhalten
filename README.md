# Homepage für den MSC Ehlhalten e.V. im ADAC

Ein Gemeinschaftsprojekt der Jugendgruppe des MSC Ehlhalten.

Verschiedene Ziele werden mit diesem Projekt verfolgt:

- Ersatz für die bisherige Homepage, die nicht mehr gewartet wird
- Vermitteln von Programmier-Know-How an die Jugendlichen. Das im Informatikunterricht Gelernte kann sinnvoll vertieft und erweitert werden
- Gestaltungsfreiheit: Wir sind frei von irgendwelchen Vorgaben, es kann alles gebaut und ausprobiert werden. Was den anderen auch gefällt, geht live
- DevOps: Du baust es, du betreibst es, du fixt es, du entwickelst es weiter. So wird es bei großen Software Firmen auch gelebt.
- Wartung und Pflege der Seite durch die Jugendlichen selbst: Wissen wird auf die Art auf viele Schultern verteilt und jede(r) kann sich einbringen, soviel sie/er mag
- Erfahrene Ältere zeigen den Jugendlichen, wie man Software entwickeln kann. Mit der Zeit werden die Jugendlichen dann den Älteren hoffentlich zeigen, wie man es noch besser machen kann
- Das ganze soll eine Eigendynamik entwickeln und den Jugendlichen auch als Referenz dienen. Je ordentlicher und sorgfälltiger ihr Code und anderer Content geschrieben ist, desto eher können sie dies auch in einer Bewerbung vorzeigen bzw. als Arbeitsprobe darauf verweisen. Engagement und Kompetenz sind die besten Voraussetzungen für einen gutbezahlten Job, der auch noch Spass macht.

# Aufbau

Das ist unsere Startstruktur. Im Lauf der Zeit kann gerne alles umgekrempelt werden:

## Backend
Ein Webservice basierend auf Python Flask. Blogbeiträge werden in einer Datenbank gespeichert und werden über Rest API Calls erzeugt/abgefragt/bearbeitet.

## Frontend
HTML/CSS/Javascript, was die Backend Services konsumiert und darstellt.

# Ausblick
Wer Lust hat und sich dafür interessiert, kann auch eine App für Android/iOS bauen, die die Backend Services konsumiert. Wie cool wäre es denn, wenn der Verein seine eigene App hat, die die Jugendliche  selbst bauen?!

Alles kann, nichts muss!

# Generelle Basics

- Keine Zugangsdaten im Code speichern und nicht commiten! Das gehört in eine Config und die Config Dateien in .gitignore. Beispielconfig mit Dummy Werten gerne commiten.
- Entwicklung im eigenen Branch, Pull Request Richtung Main Branch für go live
- Commits sollten nur lauffähigen Code enthalten. Bugs sind völlig ok, Syntaxfehler sollten schon gefixt sein
- Lieber viele kleine Commits, als wenige große
- Angepasster Angular commit style: "feat:", "fix:", "doc:", "chore:"
