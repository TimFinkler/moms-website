EXPAT FAMILY LIFE – Website
============================

Struktur
--------
index.html        -> die Website (eine Seite)
images/           -> Fotos (Buch, Autorin, Banner)
fonts/            -> Schriftarten (lokal, kein Google)

Alles ist self-contained und ohne externe Dienste – kein Google Fonts,
keine Cookies, kein Tracking.

Hochladen bei domainfactory (per SFTP)
--------------------------------------
1. FTP/SFTP-Zugang im df-Kundenmenue unter "FTP-Accounts" bereitlegen.
2. Mit FileZilla verbinden: Servertyp "SFTP - SSH File Transfer Protocol",
   Host = deine Domain, Port 22, Benutzer/Passwort aus dem Kundenmenue.
3. Den KOMPLETTEN Inhalt dieses Ordners (index.html + images/ + fonts/)
   in das Webroot der Domain hochladen (oft der Ordner, in dem die Domain
   liegt – bei df meist der Domain-/htdocs-Ordner).
4. Im df-Kundenmenue unter Domain > SSL-Zertifikate das kostenlose
   Zertifikat aktivieren und HTTPS-Weiterleitung einschalten.

Fertig – die Seite ist unter https://deine-domain.de erreichbar.

Noch anzupassen (Inhalt)
------------------------
- Termine gibt es aktuell keine (Bereich ist ausgeblendet).
- Impressum/Datenschutz sind hinterlegt; Datenschutz von Fachperson
  pruefen lassen, bevor es live geht.

Aenderungen
-----------
Texte stehen direkt in index.html. Fotos in images/ einfach durch
gleichnamige Dateien ersetzen. Kein Build-Schritt noetig.
