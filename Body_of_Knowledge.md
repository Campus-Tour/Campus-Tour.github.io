## Body of Knowledge

Eindrucksvoll, oder? Vor die siehst Du den __Body of Knowledge__ des spanischen Künstlers Jaume Plensa. 
Ganze 8 Meter ist der Body of Knowledge hoch und setzt sich zusammen aus einzelnen Buchstaben acht verschiedener Sprachen. 

Ein Zitat des Künstlers selbst beschreibt sehr gut, was der Body of Knowledge und die Universität ausmacht: 

_„Unser Körper ist der Sitz des Geistes. Die Universität ist eine Ausweitung unseres Körpers. 
Ein Versammlungsort, an dem sich Menschen und Ideen, Tradition und Zukunft zu Zwiegesprächen treffen und das Netz menschlichen Wissens weben.“_ 
Jaume Plensa [(Quelle)](https://www.kunst-im-oeffentlichen-raum-frankfurt.de/de/page28.html?id=433)

Weitere Skulpturen von Jaume Plensa findest Du [Hier.](https://jaumeplensa.com/works-and-projects/sculpture)

{% include Body_of_Knowledge_youtubePlayer.html id="f-ESeIvn5ZU?start=1290" %}

Eine Reihe von Bildern und Zeichen, deren Wortlaut durch Aneinanderfügung und Abstraktion einen oder mehrere neue Begriffe ergeben, die mit den Bildern in keinem sachlichen Zusammenhang stehen. Eine Reihe von Bildern und Zeichen, deren Wortlaut durch Aneinanderfügung und Abstraktion einen oder mehrere neue Begriffe ergeben, die mit den Bildern in keinem sachlichen Zusammenhang stehen. Dabei kann der Austausch, der Wegfall oder die Hinzufügung einzelner Buchstaben verfügt werden.

Lust auf ein kleines Bilderrätsel? Ein Rebus besteht aus mehreren Bildern oder Zeichen (hier Emojis). Die Wörter, die durch die Emojis repräsentiert werden, müssen aneinandergefügt werden, dabei müssen Buchstaben ausgetauscht, entfernt oder hinzugefügt werden. Auf diesem Weg entsteht einer neuer Begriff. 
Nutze die Hinweise und überprüfe Deine Antwort indem Du sie in den zugehörigen Kasten eingibst. 

<img src="Body_of_Knowledge_rebus.svg" width="600">

<form name="f1">
  Wort 1: <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers1()">

</form>

<form name="f2">
  Wort 2: <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers1()">

</form>

<form name="f3">
  Wort 3: <input type="text" name="studentAnswer" size="20">
  <br>
  <br>
  <input type="button" value="Check" onClick="checkAnswers1()">

</form>

Hast Du Lust,auch einen Rubus zu erstellen? [Hier findest du einen kostenlosen Rebus-Generator.](https://rebus.club/de)

<script>
function checkAnswers1() {
// document.$formName.$inputName
  Student_answer = document.f1.studentAnswer.value
  Teacher_answer = "Alphabet"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Bitte gebe das gesuchte Wort ein. Achte dabei auf Groß- und Kleinschreibung.");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("Super! Deine Antwort ist korrekt!");
  } else {
    alert("Falsche Antwort. Bitte gebe das gesuchte Wort ein. Achte dabei auf Groß- und Kleinschreibung.");
  }

}

function checkAnswers2() {
// document.$formName.$inputName
  Student_answer = document.f2.studentAnswer.value
  Teacher_answer = "Universität"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Bitte gebe das gesuchte Wort ein. Achte dabei auf Groß- und Kleinschreibung.");
    return false;
  }

  if (Student_answer == Teacher_answer) {
    alert("Super! Deine Antwort ist korrekt!");
  } else {
    alert("Falsche Antwort. Bitte gebe das gesuchte Wort ein. Achte dabei auf Groß- und Kleinschreibung.");
  }

}
  
function checkAnswers3() {
// document.$formName.$inputName
  Student_answer = document.f3.studentAnswer.value
  Teacher_answer = "Wissen"

  if (Student_answer.length == 0 || Teacher_answer.length == 0) {
    alert("Bitte gebe das gesuchte Wort ein. Achte dabei auf Groß- und Kleinschreibung.");
    return false;
  }
  if (Student_answer == Teacher_answer) {
    alert("Super! Deine Antwort ist korrekt!");
  } else {
    alert("Falsche Antwort. Bitte gebe das gesuchte Wort ein. Achte dabei auf Groß- und Kleinschreibung.");
  }

}
</script>


