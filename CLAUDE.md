# Alltagshelfer – Projektdokumentation

## Zweck
Barrierefreie Sammelseite der vier Praxis-Werkzeuge, ohne E-Mail-Anmeldung. Gedacht für die bestehende Kongressliste (~2.000 Adressen), die man nicht erneut nach der E-Mail fragen muss. Kein Ersatz für die Lead-Generierungs-Seite `tinnituspraxis-seedorf.de/tinnitus-selbsthilfe`, die bleibt unverändert für organischen Traffic bestehen.

**Live-URL:** https://alltagshelfer.tinnituspraxis-seedorf.de
**GitHub-Repo:** https://github.com/Boris1900/alltagshelfer
**Projektordner:** C:\Users\Boris\Projekte\Alltagshelfer\

Bewusst NICHT im Menü der Hauptseite verlinkt und technisch komplett losgelöst von ihr (eigene Subdomain, eigenes Repo), damit sie nicht als Teil der offiziellen Praxisseite auffindbar/verwechselbar ist.

---

## Die vier Kacheln

| Werkzeug | Ziel-Link | Barriere |
|---|---|---|
| Tinnitus-Tester | `tester.tinnituspraxis-seedorf.de` | keine (war schon offen) |
| Tinnitus-Kompass | `tinnitus-kompass.pdf` (liegt im Repo) | keine (Original nur per E-Mail über Quentn erreichbar, hier direkt) |
| Tinnitus Tracker App | `app.tinnituspraxis-seedorf.de/download.html` | keine (führt NICHT auf die E-Mail-Landingpage `index.html` des Tracker-Projekts) |
| Ohreninsel | `ohreninsel.tinnituspraxis-seedorf.de/download` | keine (war schon offen) |

## Design
Übernommen von der bestehenden `/tinnitus-selbsthilfe`-Seite: Logo, vier Icons (als JPG/PNG heruntergeladen, liegen im Repo), Grün `#7ed957`, Hintergrund `#ece9e1`, Schrift Open Sans. Gleiches Kartenschema wie bei Tester/Tracker (weiße Card, abgerundet, Schatten).

## Bekannter offener Punkt: Kompass-Link beim Tester
Die CLAUDE.md des Tester-Projekts (`Tinnitustester Webseite`) behauptet, das Kompass-PDF liege dort öffentlich unter `tester.tinnituspraxis-seedorf.de/tinnitus-kompass.pdf`. Stimmt nicht (404, geprüft 27.07.2026), das PDF war nie im Tester-Repo. Hier bewusst umgangen, indem das PDF direkt in diesem Repo liegt. Der Fehler im Tester-Projekt selbst ist NICHT behoben, nur hier nicht relevant.

## Push-Workflow
Projektordner ist selbst das Git-Repo (`git status` direkt hier), kein Umweg über `repo-temp` nötig.

## Verknüpfte Projekte
- `Tinnitustester Webseite` – liefert Tester + (eigentlich) Kompass-PDF
- `TinnitusTracker` – liefert die App, `download.html` dort am 27.07.2026 von reinem APK-Download auf Android/iPhone-Auswahl umgestellt (Play Store dort noch in Prüfung)
- `Tinnitus_Pilotgruppe` (Google Drive) – dieser Landingpage-Link geht in Mail 1 der Intensivtage-Kampagne, siehe Protokoll dort, LOG-045ff.

## Session-Workflow
Neue Session starten mit: „Lies die CLAUDE.md im Ordner Alltagshelfer und sag mir kurz wo wir stehen."
