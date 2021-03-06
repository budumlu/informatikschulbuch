# Verschachtelungen in HTML

Bisher konnten wir einen Text nur fett oder kursiv machen. Aber geht auch beides? 					

Probiere folgendes Beispiel aus:

```html
<b><i>Text :)</i></b>
```

Wie funktioniert das? Du kannst dir vorstellen, dass jedes Element, was wir schreiben, eine Art Rechteck innerhalb der Webseite ist. In diesem Rechteck gelten ganz spezielle Regeln. Wie etwa in `<b></b>`,  dass Text fettgeschrieben werden muss. Ergänze ich nun innerhalb des `<b></b>`-Bereiches noch den `<i></i>`; Bereich, so gelten innerhalb diesen Bereiches zusätzlich noch die Regeln des `<b></b>`-Bereiches.


t> Erstelle einen Text im [Editor](https://apps.wi-wissen.de/html-css-js-editor/), welcher sowohl kursiv als auch fett ist.

t> Erstelle einen Text im [Editor](https://apps.wi-wissen.de/html-css-js-editor/), welcher sowohl fett als auch unterstrichen ist.

t> Erstelle einen Text im [Editor](https://apps.wi-wissen.de/html-css-js-editor/), welcher unterstrichen, kursiv und eine Überschrift der 2. Ordnung ist.

## div-Element

Bisher waren von allen Elementen die Regeln schon klar festgelegt. So war etwa das `<b></b>`-Element klar mit fettgeschriebenem Text. Das `<div></div>`; Element ist nur ein Rechteck, welches so keine Regeln hat. Diese werden alle erst mit CSS festgelegt.

```html
<div>Anarchie!</div>
```

t> In dem vorbereiteten [Beispiel](https://apps.wi-wissen.de/html-css-js-editor/0u6AD) wurden die Farben der Rechtecke festgelegt. Notiere, wie sich Regeln zueinander verhalten.
