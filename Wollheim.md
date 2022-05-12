### Wollheim Pavillion

<img src="Wollheim_Bild1.jpg" width="600">

Hier: Exposé von Veronika Duma folgt ende Juni

Lust auf ein [Kreuzworträtsel?](https://www.xwords-generator.de/de/solve/dshbk)

Weitere Information findest du auf der [Webseite des Wollheim Pavillions ](http://www.wollheim-memorial.de/de/home)und auf der Webseite des [Fritz Bauer Institutes](https://www.fritz-bauer-institut.de).

<img src="Wollheim_Bild2.jpg" width="200">

<h3>Wer ist auf diesem Bild zu sehen?</h3>
<br>
<form name="f1">
  Name: <input type="password" name="studentAnswer" size="20">
  <br>
  <input type="button" value="Check" onClick="checkAnswers()">
</form>

<img src="Wollheim_Bild3.jpg" width="200">


<script>
function checkAnswers() {
// document.$formName.$inputName
  Student_answer = document.f1.studentAnswer.value
  Teacher_answer = "Hallo"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Gebe den Namen ein.");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("Super! Deine Antwort ist korrekt!);
  } else {
    alert("Falsch, versuche es noch einmal");
    //NOTE: here the button must be disabled
  }

}
  
</script>
