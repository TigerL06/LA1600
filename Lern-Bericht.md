# Lern-Bericht
Pineapple: Koch, Grigioni, Hitz

## Einleitung
In diesem Projekt haben wir eine Webseite über Festivals in der Schweiz erstellt.

## Was habe ich gelernt?

Wir haben gelernt wie man die Funktion display flex in Css verwendet.

## Beschreibung
Die Funktion Responsiv Flex (Flexbox) ist eine CSS-Technik, dazu da ist, um eine Webseite zu strukturieren. Man kann mit dieser Funktion Elemente in einem Containers platzieren und so ihnen einen fixen Platz zuweisen. Um die Funktion Responsiv Flex anzuwenden, muss man zuerst den Befehl "display: felx; " in den Container schreiben, wo sich die Elemente befinden sollen, die einen bestimmten Platz haben sollen. Es gibt dann verschiedene Befehle, mit denen man die Positionierung und Ausrichtung der Elemente in einem Responsiv Flex steuern kann. Ich werde jetzt einige von den wichtigsten erklären.

"flex-direction": Diese Funktion definiert die Richtung, in der die Elemente in einem Container angeordnet werden sollen. 

"justify-content": Mit dieser Funktion kann die horizontale Ausrichtung der Elemente in einem Container gesteuert. 

"align-items": Diese Funktion steuert die vertikale Ausrichtung der Elemente im flexiblen Container. Sie macht es möglich, dass man das Element zentrieren werden können oder es am Anfang oder am Ende platziert werden.

"flex-wrap": Mit dieser Funktion sagt man, ob die Elemente in einer Zeile bleiben sollen oder ob sie auf mehrere Zeilen aufgeteilt werden sollen. 

"flex": Mit dieser Funktion kann man Elementen den verbleibenden Platz in einem container zuweisen. Zum Beispiel sagt, "flex: 1;" sagt, dass der Platz gleichmässig auf alle Elemente im Container verteilt wird. "flex: 2;" sagt, dass das angesprochen Element doppelt so viel Platz wie die anderen Elemente einnimmt und "flex: 0.5;" macht gerade das umgekehrte, es weisst einem Element den halben Platz von dem noch verfügbaren Platz zu.


HTML Code:
```html
<div class="container">
<div class="flex-item">Element 1</div>
<div class="flex-item">Element 2</div>
<div class="flex-item">Element 3</div>
</div>
```
Css Code:
```css
.container {
  display: flex; /* Aktiviert Flexbox für den Container */
  flex-direction: row; /* Legt die Richtung der Elemente fest (horizontal) */
  justify-content: center; /* Zentriert die Elemente horizontal */
  align-items: center; /* Zentriert die Elemente vertikal */
}


.flex-item {
  flex: 1; /* Bestimmt das Verhältnis des Elements zum Rest der Elemente */
  margin: 10px; /* Fügt einen Abstand um das Element hinzu */
}
```
## Verifikation

Code HTML und CSS: In dem Code wird gezeigt wie die Funktion Responsiv Flex in einem Code verwendt wird. 
Bild1: Im Bild sieht man wie die Webseite mit Responsiv Flex aussieht.
Bild2: Im Bild sieht man wie die Webseite ohne Responsiv Flex aussieht.
Text: Im Text wird die Funktion Responsiv Flex erklärt.

# Reflexion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
