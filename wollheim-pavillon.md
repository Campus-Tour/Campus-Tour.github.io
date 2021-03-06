# Wollheim Pavillon
<p class="aligncenter">
    <img src="Logo.png" alt="centered image" width="400" />
</p>
Falls dies deine erste Station der Campus Tour ist und Du noch nicht weißt, was dich erwartet und wie der Ablauf ist, dann kannst Du auf unserer [Startseite](https://campus-tour.github.io) alles Wichtige nachlesen! Falls Du dich allerdings schon auskennst, dann kannst Du hier direkt weitermachen, viel Spaß! <br/>

<img src="Wollheim_Bild1.jpg" width="600">
Hier siehst Du das Innere des Wollheim-Pavillons. Gehe doch gerne selbst hinein und schau dich um! Auf den Bildschirmen im Pavillion kannst Du vieles entdecken!

Lust auf ein [großes Kreuzworträtsel?](https://www.xwords-generator.de/de/solve/dshbk) (Alternativ kannst du auch ein [kleineres Kreuzworträtsel](https://www.xwords-generator.de/de/solve/7kqan) lösen). <img align="right" src="Pose3_1.svg" width="100"> 
Es verbindet Fragen zu Wollheim und allgemeine Fragen zum Holocaust, damit Du dein Wissen überprüfen kannst. Die teils dazu nötigen Informationen findest Du auf den Bildschirmen im Wollheim-Pavillon oder [online](http://www.wollheim-memorial.de/de/home). Am Ende erhältst Du ein Lösungswort, das du hier zur Prüfung eingeben kannst:
<form name="f4">
  Lösungswort für das große Rätsel (GROßBUCHSTABEN) <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers4()">

</form>

<form name="f3">
  Lösungswort für das kleine Rätsel (GROßBUCHSTABEN) <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers3()">

</form>

Weitere Information findest du auf der [Webseite des Wollheim Pavillons ](http://www.wollheim-memorial.de/de/home)und auf der Webseite des [Fritz Bauer Institutes](https://www.fritz-bauer-institut.de).

Zudem kannst Du [hier](https://campus-tour.github.io/HabilDumaVeronika_Kurztext.pdf) ein Exposé zum Habilitationsprojekt von Veronika Duma anschauen, welches sich mit dem Raub an der jüdischen Bevölkerung in Europa befasst. Durch ihre Arbeit erhältst Du einen Einblick in die aktuelle Forschung an der Goethe-Uni zur NS-Geschichte! 

### Wie heißen die Kinder? Finde es heraus, indem Du die Tafeln vor dem IG-Farbenhaus suchst und auf die Rückseite der Bildertafeln schaust.

<img src="Wollheim_Bild2.jpg" width="200">

<h3>Wer ist auf diesem Foto zusehen?</h3>
<form name="f1">
  Vorname Nachname: <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers1()">

</form>

<img src="Wollheim_Bild3.jpg" width="200">

<h3>Wer ist auf diesem Foto zusehen?</h3>
<form name="f2">
  Vorname Nachname: <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers2()">

</form>

Der Lösungsbuchstabe dieser Station ist der Anfangsbuchstabe des Vornamens des ersten Jungen!

### Nächste Station: _///fischte.erprobt.gelbes_   
Du kannst zudem [hier](https://campus-tour.github.io/ruw.html) klicken, um zur Seite der nächsten Station zu gelangen ;)

<img src="Pose2.svg" width="200">


<script>
function checkAnswers1() {
// document.$formName.$inputName
  Student_answer = document.f1.studentAnswer.value
  Teacher_answer = "Marcel Ginzig"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Bitte gebe den Vor- und Nachnamen ein. Achte dabei auf Groß- und Kleinschreibung.");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("Super! Deine Antwort ist korrekt!");
  } else {
    alert("Falsche Antwort. Bitte gebe den Vor- und Nachnamen ein. Achte dabei auf Groß- und Kleinschreibung.");
  }

}

function checkAnswers2() {
// document.$formName.$inputName
  Student_answer = document.f2.studentAnswer.value
  Teacher_answer = "Victor Perez"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Bitte gebe den Vor- und Nachnamen ein. Achte dabei auf Groß- und Kleinschreibung.");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("Super! Deine Antwort ist korrekt!");
  } else {
    alert("Falsche Antwort. Bitte gebe den Vor- und Nachnamen ein. Achte dabei auf Groß- und Kleinschreibung.");
  }

}
  

function checkAnswers3() {
// document.$formName.$inputName
  Student_answer = document.f3.studentAnswer.value
  Teacher_answer = "ERINNERN"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Leider keine Übereinstimmung.");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("Super! Du hast das Lösungswort gefunden!");
  } else {
    alert("Leider keine Übereinstimmung.");
  }

}
  
function checkAnswers4() {
// document.$formName.$inputName
  Student_answer = document.f4.studentAnswer.value
  Teacher_answer = "GEDENKEN"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Leider keine Übereinstimmung.");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("Super! Du hast das Lösungswort gefunden!");
  } else {
    alert("Leider keine Übereinstimmung.");
  }

}
</script>
