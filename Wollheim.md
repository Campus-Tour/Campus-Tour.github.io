### Wollheim Pavillion

<img src="Wollheim_Bild1.jpg" width="600">

Hier: Exposé von Veronika Duma folgt ende Juni

Lust auf ein [Kreuzworträtsel?](https://www.xwords-generator.de/de/solve/dshbk)

Weitere Information findest du auf der [Webseite des Wollheim Pavillions ](http://www.wollheim-memorial.de/de/home)und auf der Webseite des [Fritz Bauer Institutes](https://www.fritz-bauer-institut.de).

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
<form name="f1">
  Vorname Nachname: <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers2()">

</form>



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
</script>

<script>
function checkAnswers2() {
// document.$formName.$inputName
  Student_answer = document.f1.studentAnswer.value
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
</script>
