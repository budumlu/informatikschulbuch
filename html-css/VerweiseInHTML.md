# Verweise & Links

## Verweisarten

### absolute Verweise

Gibst du in deinen Browser einen Verweis, musst du immer die vollständige Adresse eingeben, damit dein Rechner weiß, wo er die Webseite herbekommen kann. Dadurch ist es egal, auf welcher Seite du vorher warst. Du kommst immer auf der neuen Adresse an. Das ist ähnlich einer Postanschrift. Hier ist es auch ganz egal, in welchen Briefkasten ich den Brief einwerfe.					

```
https://apps.wi-wissen.de/html-css-js-editor/img/bird.jpg
```

### relative Verweise

Manchmal ist es unpraktisch immer die ganze Adresse anzugeben. Etwa wenn du vorhast den Domainnamen deiner Webseite zu ändern, dann müsstest du auch alle Links anpassen. Dies funktioniert nur, wenn du schon auf einer ganz speziellen Webseite im Internet bist. Das ist wie eine Wegbeschreibung "*200m geradeaus und dann scharf links, dann bist du gegen den Laternenpfahl gelaufen.*. Du rennst nur gegen den Laternenpfahl, wenn du dich an einer speziellen Position befindest.					

```
img/bird.jpg
```

Du siehst, dieser relative Verweis ist auch viel kürzer und erspart ein wenig Schreibarbeit. Um zu der Datei zu gelangen, soll der Browser zuerst in den Ordner `img` gehen und anschließend das Bild `bird.jpg` abrufen.

i> Der Ordner `..` weist den Browser an einen Ordner über den aktuellen Ordner zu gehen. und mit `/` geht es ganz nach oben in das Wurzelverzeichnis oder hier bekannt als Domainname mit Domainendung.


## Links

```
<a href="https://buch.lernraumzeit.de/">Lernraumzeit.de</a>
```

Hier haben wir etwas Neues. Bisher kannten wir nur `<a>Lernraumzeit</a>`. Nun steht im Startelement noch zusätzlich `href="https://wi-wissen.de/"`. Hierdurch wird das Textelement Link genauer für den Webbrowser beschrieben, was aber so nicht unmittelbar angezeigt wird.

Da es den Link genauer beschreibt, sagt man auch, `href` ist eine Eigenschaft des Links. Bei HTML heißt Eigenschaft Attribut. `"https://buch.lernraumzeit.de/"` ist der Wert des Attributes (Attributwert), welcher in Anführungszeichen geschrieben wird.


## Bilder

Das Einbinden eines Bildes funktioniert ähnlich eines Links, nur dass hier nicht auf das Bild verwiesen wird, sondern es direkt in der HTML-Webseite angezeigt wird:

```html
<img src="img/dog.jpg" alt="Dog" />
```
