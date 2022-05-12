### Wollheim Pavillion

<img src="Wollheim_Bild1.jpg" width="600">

Hier: Exposé von Veronika Duma folgt ende Juni

Lust auf ein [Kreuzworträtsel?](https://www.xwords-generator.de/de/solve/dshbk)

Weitere Information findest du auf der [Webseite des Wollheim Pavillions ](http://www.wollheim-memorial.de/de/home)und auf der Webseite des [Fritz Bauer Institutes](https://www.fritz-bauer-institut.de).

<img src="Wollheim_Bild2.jpg" width="200">


<input pattern="Hallo" type="text" name="" value="">

<img src="Wollheim_Bild3.jpg" width="200">

<h3>Write here your answer...</h3>
<br>
<form name="f1">
  Your answer: <input type="password" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers()">

</form>

function checkAnswers() {
// document.$formName.$inputName
  Student_answer = document.f1.studentAnswer.value
  Teacher_answer = "abc"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("You must enter an answer to continue...");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("CONGRATULATIONS! Your answer is correct! You have advanced to the next level");
    //<button onclick="window.location.href = 'https://www.google.com';">Next Riddle</button>
    //NOTE: here is where the button should be activated and click on it to advance to an hyperlink 
  } else {
    alert("Worng answer, please, keep trying...<br />");
    //NOTE: here the button must be disabled
  }

}
