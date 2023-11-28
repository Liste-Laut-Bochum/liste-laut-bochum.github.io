# Guidelines zum Mitarbeiten an der Website

Du willst helfen? Super! Bitte beachte dabei folgendes:

1. Posts und ähnliches werden nur von Mitgliedern der Liste verfasst. Pull Requests welche neue Posts erstellen und nicht von Listenmitgliedern sind werden abgelehnt.
2. Bitte schreibe deine Commit-Nachrichten auf Englisch.
3. Jedes Pull-Request sollte einen Titel beginnend mit "nit:" (für kleine Änderungen wie Rechtschreibfehler), "tech:" (für technische Änderungen an der Seite), "post:" (für neue Posts/größere Änderungen an posts) oder "other:" (für alles andere) haben.
    - Der Titel selbst sollte auf Englisch sein.
4. Wenn nicht direkt offensichtlich ist, was dein Pull-Request erreichen möchte, schreibe eine kurze Beschreibung.
    - Die Beschreibung sollte auf Englisch sein.
5. Labele deine Pull-Requests.
6. Nutze "Squash-and-merge" zum mergen von Pull-Requests.

Die Website ist mit [jekyll](https://jekyllrb.com/) und dem [minimal-mistakes-Theme](https://mmistakes.github.io/minimal-mistakes/) gebaut. Außerdem nutzen wir [rtx](https://github.com/jdx/rtx) zum einfachen verwalten von Ruby-Abhängigkeiten und Bibliotheken. Du kannst die Website lokal anzeigen lassen mit dem Befehl `bundle exec jekyll serve --incremental`.

## WICHTIG

Falls du eine Schwachstelle oder ein Sicherheitsrisiko gefunden hast, schau [hier](SECURITY.md) nach um zu wissen wie du vorgehen sollst. 
