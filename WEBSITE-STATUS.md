# WEBSITE-STATUS Kaperfahrt Landing Page

Stand 3. August 2026 abends, eingerichtet über Cowork. Diese Datei ist die Übergabe an Claude Code für die Weiterarbeit an der Website.

## Eingerichtet

1. Statische Site in diesem Repo, index.html im Wurzelverzeichnis. Seiten sind index.html, press.html, games-like-sid-meiers-pirates.html und impressum.html, dazu robots.txt, sitemap.xml, CNAME und der Ordner assets.
2. Impressum ausgefüllt, keine Platzhalter mehr in eckigen Klammern.
3. GitHub-Repo github.com/tsweetlemonadet-cmyk/kaperfahrt-site, öffentlich, Branch main. GitHub Pages baut von main aus dem Wurzelverzeichnis.
4. Domain kleinodgames.com bei INWX registriert (Laufzeit bis 3.8.2027) und als Custom Domain in Pages eingetragen, DNS-Check bestanden, Enforce HTTPS aktiv. Die Seite läuft unter https://kleinodgames.com und die github.io-Adresse leitet dorthin um. kaperfahrt.com und kaperfahrt.de waren bereits vergeben, deshalb die Studio-Domain.
5. DNS bei INWX. Vier A-Records auf die GitHub-Pages-Adressen, www als CNAME auf tsweetlemonadet-cmyk.github.io, Wildcard als Weiterleitung auf die Hauptdomain, dazu der Google-TXT-Eintrag für die Search Console (nicht löschen). kleinodgames.de ist komplett als Weiterleitung auf kleinodgames.com eingerichtet.
6. Alle Canonical-, OG-, robots- und sitemap-URLs zeigen auf kleinodgames.com. Presse-Kontakt in press.html ist kleinodgames@gmail.com, denn kaperfahrt.com gehört einem Dritten und die alte press-Adresse dort war nicht nutzbar.
7. Search Console. Domain-Property kleinodgames.com per DNS-TXT bestätigt, sitemap.xml eingereicht. Der Erstabruf durch Google stand beim Einrichten noch aus.
8. Live-Check bestanden. Startseite, Presse-Kit und Vergleichsartikel laden, Bilder erscheinen.
9. Lokale Arbeitskopie mit Git in Desktop/GameDev/kaperfahrt-site. Der GitHub-Stand entstand über Web-Uploads, die lokale Historie ist inhaltsgleich aber eigenständig. Vor der ersten Push-Weiterarbeit einmal frisch von origin klonen oder auf origin/main resetten.
10. Neues Layout aus Claude Design am 3.8.2026 abends in index.html eingebaut. SEO-Kopf (Canonical, OG, Schema mit sameAs, Preload), UTM-Links, Social-Links und Artikel-Link im Footer wurden dabei übernommen. Die Zitate-Sektion aus dem Entwurf steckt als Kommentar vor dem Footer und wird nach Playtest-Welle 1 mit echten Stimmen einkommentiert. YouTube- und TikTok-Profil verlinken auf die Website, die TikTok-Bio nennt kleinodgames.com.
11. Search Console. Startseite ist im Google-Index, Artikel und Presse-Kit sind zur Indexierung beantragt (3.8.2026).

## Offen

1. Trailer-Video-ID am Announcement-Tag eintragen. In index.html im Trailer-Abschnitt den Platzhalter-Div gegen das vorbereitete iframe aus dem Kommentar tauschen und die YouTube-ID einsetzen.
2. Zitate-Sektion nach Playtest-Welle 1 einkommentieren und die Platzhalter durch echte Playtester-Stimmen ersetzen (Kommentar-Block vor dem Footer in index.html).
3. Screenshot-Zip fürs Presse-Kit ergänzen. Der Download-Link in press.html ist als Kommentar vorbereitet, Ziel assets/press-screenshots.zip.
4. Optional press@kleinodgames.com als Mail-Weiterleitung einrichten, bis dahin bleibt kleinodgames@gmail.com der Presse-Kontakt.
5. Sitemap-Status in der Search Console gelegentlich prüfen. Frische Domains brauchen für die ersten Google-Treffer erfahrungsgemäß einige Tage bis Wochen, Links von Steam, TikTok und YouTube auf die Domain beschleunigen das.
