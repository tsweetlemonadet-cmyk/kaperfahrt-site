# Kaperfahrt Landing Page. Einrichtung

Statische One-Page-Site, keine Abhängigkeiten, kein Build-Schritt. Alles liegt in diesem Ordner.

## Vor dem Livegang ausfüllen

1. **Impressum.** In impressum.html die Platzhalter in eckigen Klammern ersetzen (Name, Anschrift, E-Mail). Das ist als Gewerbetreibender Pflicht. Hinweis, das ist eine Basis-Vorlage und keine Rechtsberatung.
2. **Presse-Adresse.** In index.html steht press@kaperfahrt.com als mailto. Entweder eine solche Adresse bei deinem Domain-Anbieter als Weiterleitung anlegen oder durch deine echte Adresse ersetzen.
3. **OG-Bild-Domain.** In index.html zeigt og:image auf https://kaperfahrt.com. Falls du eine andere Domain nimmst, die URL anpassen.

## Domain

Empfehlung. kaperfahrt.com als Hauptdomain sichern, kaperfahrt.de als Zweitsicherung mit Weiterleitung auf .com. Registrar nach Geschmack, zum Beispiel Cloudflare Registrar, INWX oder Netcup, Kosten je etwa 10 bis 15 Euro pro Jahr.

## Hosting über GitHub Pages (kostenlos)

1. Neues öffentliches Repository anlegen, zum Beispiel kaperfahrt-site, und den Inhalt dieses Ordners hineinpushen (index.html im Wurzelverzeichnis). Das kann Claude Code in einer Minute erledigen.
2. Im Repository unter Settings und Pages als Quelle den Branch main mit dem Wurzelverzeichnis wählen. Danach ist die Seite unter benutzername.github.io/kaperfahrt-site erreichbar.
3. Eigene Domain verbinden. Unter Settings und Pages die Domain kaperfahrt.com eintragen (GitHub legt dabei eine CNAME-Datei im Repo an). Beim Domain-Anbieter einen CNAME-Eintrag für www auf benutzername.github.io setzen und für die nackte Domain die vier A-Records von GitHub Pages eintragen (stehen in der GitHub-Pages-Doku). Danach in den Pages-Einstellungen Enforce HTTPS aktivieren.
4. DNS braucht manchmal ein bis zwei Stunden. Danach einmal alles im Inkognito-Fenster testen.

## Am Announcement-Tag

1. Trailer-Einbettung aktivieren. In index.html im Trailer-Abschnitt den Kommentar-Block gegen das iframe tauschen und die YouTube-Video-ID eintragen.
2. Einmal pushen, fertig. Die Seite braucht sonst keine Pflege.

## Messung

Alle Steam-Links tragen utm_source=website mit utm_content je Position (hero_wishlist, playtest_band, footer). Die Sonntags-Review sieht damit in Steamworks, wie viele Besucher über die Domain kommen und welche Stelle der Seite sie geklickt haben.

## Später erweiterbar

Screenshots-Galerie, Presse-Kit-Download und eine deutsche Sprachfassung lassen sich jederzeit ergänzen. Das Repo ist dafür der natürliche Ort, Claude Code kennt den Weg.
