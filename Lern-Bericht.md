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

Bild1:
![image](https://github.com/TigerL06/LA1600/assets/110893121/8afa37f0-30e9-4bd8-8205-2faa9fe4aa8a)


Bild2:
![image](https://github.com/TigerL06/LA1600/assets/110893121/f9b22231-d7d5-4cd2-9180-d667a5e89525)


HTML Code:
```html
<!DOCTYPE html>
<html>

<head>
    <title>Willkommensseite</title>
    <link href="./style.css" rel="stylesheet" type="text/css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
    <div class="container">
        <div class="flex-item">Element 1</div>
        <div class="flex-item">Element 2</div>
        <div class="flex-item">Element 3</div>
    </div>
</body>


</html>
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

👍Alle haben seriös ihren Aufträge erledigt. 

👍Wir haben uns gut koordiniert und eine hohe Leistungsbereitschaft gezeigt. 

👍Online-Besprechungsorte wurden immer eingehalten.

👍Alle waren motiviert ein gutes Projekt umzusetzen.



 👎Es gab Missverständnisse, welche unsere Effizient beinträchtigt haben und wir nicht so schnell vorankamen wie wir wollten. 


**VBV**: 
Um die Kommunikation zu verbessern, müssen wir klare Anforderungen festlegen, regelmäßige Updates und Feedback geben und eine offene Kommunikation fördern. Dadurch können Missverständnisse vermieden und ein besseres gemeinsames Verständnis erreicht werden.
