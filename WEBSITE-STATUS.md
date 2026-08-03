# WEBSITE-STATUS Kaperfahrt Landing Page

Stand 3. August 2026, eingerichtet über Cowork. Diese Datei ist die Übergabe an Claude Code für die Weiterarbeit an der Website.

## Eingerichtet

1. Statische Site liegt in diesem Repo, index.html im Wurzelverzeichnis. Seiten sind index.html, press.html, games-like-sid-meiers-pirates.html und impressum.html, dazu robots.txt, sitemap.xml und der Ordner assets.
2. Impressum ist ausgefüllt, keine Platzhalter mehr in eckigen Klammern.
3. GitHub-Repo github.com/tsweetlemonadet-cmyk/kaperfahrt-site, öffentlich, Branch main.
4. GitHub Pages aktiv, Quelle Branch main mit Wurzelverzeichnis. Live unter tsweetlemonadet-cmyk.github.io/kaperfahrt-site
5. Live-Check bestanden am 3.8.2026. Startseite, Presse-Kit und Vergleichsartikel laden mit Status 200, Hero und Logo erscheinen, keine 404-Anfragen.
6. Lokale Arbeitskopie mit Git-Repo liegt unter Desktop/GameDev/kaperfahrt-site. Hinweis, der GitHub-Stand entstand über Web-Upload in zwei Commits, die lokale Historie ist ein eigener Initial-Commit mit identischem Inhalt. Vor der ersten Weiterarbeit mit Push daher einmal frisch von origin klonen oder git fetch und reset auf origin/main machen.

## Offen

1. Design-Entwurf aus Claude Design einbauen. Liegt lokal als Kaperfahrt Steam Landing Page.zip unter Desktop/GameDev/Trader and Pirates/Website. Achtung, dessen index.html enthält keine OG-, Schema- und Canonical-Tags, die SEO-Teile aus der aktuellen index.html beim Einbau übernehmen.
2. Trailer-Video-ID am Announcement-Tag eintragen. In index.html im Trailer-Abschnitt den Kommentar-Block gegen das iframe tauschen und die YouTube-ID einsetzen.
3. Screenshot-Zip fürs Presse-Kit ergänzen. In press.html ist der Download-Link als Kommentar vorbereitet, Ziel assets/press-screenshots.zip.
4. Search-Console-Anmeldung nach dem Livegang unter der finalen Domain.
5. Domain ist noch nicht gekauft, Empfehlung laut README kaperfahrt.com plus kaperfahrt.de als Weiterleitung. Nach dem Kauf die Custom Domain in den Pages-Einstellungen eintragen, DNS-Einträge nach GitHub-Pages-Doku setzen, Enforce HTTPS aktivieren. Canonical, OG-Bild, robots.txt und sitemap.xml zeigen bereits auf kaperfahrt.com und passen dann automatisch.
6. Presse-Adresse klären. In press.html steht press@kaperfahrt.com als Kontakt, die Adresse existiert erst nach dem Domain-Kauf mit Mail-Weiterleitung, alternativ vorher auf kleinodgames@gmail.com umstellen.
