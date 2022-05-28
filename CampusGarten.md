# Campus Garten
<p class="aligncenter">
    <img src="Logo.png" alt="centered image" width="400" />
</p>

## Schön, dass du den Campus-Garten gefunden hast!

<img src="CampusGarten2.jpg" width="170"> <img src="Campusgarten1.jpg" width="170"> 
<br>
Hier bauen Studierende und Anwohner:innen gemeinsam nach den Prinzipien der Permakultur Gemüse an.
<br>
Im Interview hat uns David Delto von Goethes Green Office unter anderem erzählt, was es dort alles zu entdecken gibt.
<br>
<br>

<figure>
    <figcaption>Interview mit David Delto zum Campus Garten:</figcaption>
    <audio
        controls
        src="CampusGarten.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>
_Interview durchgeführt von Hanna Barner_

Hier siehst du den Campus Garten von oben. Wir haben 5 Buchstaben darin versteckt, die die erste Hälfte des Lösungswortes ergeben. Findest du sie?
<img src="CampusGarten3.jpg" width="400">

Die Bildchen unten zeigen alle ein Teekesselchen. Das sind Wörter, die zwei verschiedene Bedeutungen haben. Eine Bedeutung ist auf dem Bild dargestellt, die andere bezieht sich auf Dinge, die man in einem Garten finden kann. Die roten Buchstaben geben dann den zweiten Teil vom Lösungswort. 

<img src="Campusgarten4.png" width="400">

<form name="f1">
 Lösungswort: <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers1()">

</form>

Hier findest du weitere Informationen zu den am Garten beteiligten Gruppen: 
[www.goethesgreenoffice.de](http://www.goethesgreenoffice.de/2021/10/13/permakultur-campus-gaerten-uni-frankfurt/)
[www.gemueseheldinnen-frankfurt.de](https://gemueseheldinnen-frankfurt.de/permakulturinseln/).

Du hast Lust, selber einen Permakultur garten anzulegen? 
Hier gibt es 9 praktische Tipps dazu: [www.wurzelwerk.net](https://www.wurzelwerk.net/2020/10/28/permakultur-garten/). 
Und auch in der Unibibliothek findest du ein Ebook dazu: [Handbuch Permakultur : Klug planen und nachhaltig gärtnern / Ulrike Windsperger](https://ubffm.hds.hebis.de/Record/HEB486052583)

### Nächste Station: _WORT//WORT//WORT_   
<img src="Pose2.svg" width="200">

### Quellen der Cliparts:
1) Aha-Soft/ Shutterstock.com
2) Word Clipart
3) Oakview Studios/ Shutterstock.com
4) Word Clipart
5) AVIcon/ Shutterstock.com

<script>
function checkAnswers1() {
// document.$formName.$inputName
  Student_answer = document.f1.studentAnswer.value
  Teacher_answer = "Hügelbeete"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Bitte gebe das Lösungswort ein. Achte dabei auf Groß- und Kleinschreibung.");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("Super! Deine Antwort ist korrekt!");
  } else {
    alert("Falsche Antwort. Achte auf Groß- und Kleinschreibung.");
  }

}
</script>
