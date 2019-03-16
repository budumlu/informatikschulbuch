# HTML hat Kopf und Fuß

Eine vollständige Webseite sieht nämlich wie folgt aus:

```html
<!DOCTYPE html>
<html>
  <head>
	<meta charset="utf-8">
    <title>Titel der Webseite</title>
    <!-- weitere Kopfinformationen -->
    <!-- Kommentare werden im Browser nicht angezeigt. -->
  </head>
  <body>
	<!-- erst ab hier wird der Inhalt auch im Browser angezeigt. -->
    <p>Inhalt der Webseite</p>
  </body>
</html>
```

Um das zu verstehen, müssen wir unser gesamtes Wissen zusammennehmen und noch einiges Neue lernen:

Wir haben schon gelernt, dass es Rechtecke gibt, welche wir ineinanderschachteln können. Das ist auch hier der Fall. Es gibt ganz große Rechtecke, von denen wir bisher noch nichts wussten.

`html` - das Rechteck zeigt an, dass es eine HTML-Seite ist. Was du bisher als HTML kennst ist eine Art Dialekt einer größeren Sprache XML (welche wiederum ein Dialekt ist, dazu aber im Informatikstudium mehr)

`head` - dieses Rechteck wird **nicht** im Browserfenster angezeigt. Hier haben wir ganz spezielle Informationen für den Browser abgelegt.

`body` - dieses Rechteck wird im Browserfenster angezeigt und füllt dies vollständig aus.
