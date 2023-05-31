![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | JS Grundlagen der Algorithmen

Willkommen zur ersten Übung im Bootcamp bei Ironhack!

Das Ziel dieser Übung besteht darin, dass du dich mit den primitiven Datenstrukturen in JavaScript vertraut machst, die wir gerade im Unterricht behandelt haben. Du kannst gerne auf die Lernmaterialien zurückgreifen und dich nicht einschränken, sondern neugierig sein und Google verwenden, um mehrere Lösungen zu erkunden.

Bereit?

![qrjeCm](https://user-images.githubusercontent.com/76580/167263489-bd345c02-6c3b-425e-9a9c-96390dea9ba6.gif)

## Einführung

Bei dieser **Pair-Programming**-Aktivität arbeiten beide Personen im Paar in ihren eigenen Repositories. Am Ende der Übung sollten beide Schüler identischen Code in ihren jeweiligen Repositories haben.

Bereit, um loszulegen?


## Anforderungen

- Fork dieses Repositories
- Clone das Repository
- Gib folgendes im _File Tab_ (linker Bereich) ein:

 ```javascript    
 console.log("I'm ready!");    
 ```  
- Speichern
- Öffne ein Terminal und navigiere zu dem Verzeichnis, in dem sich die Skriptdatei befindet, und gib dann den folgenden Befehl ein: `node js/index.js`
- Wenn du die Nachricht im Terminalpanel (unten) sehen kannst, bist du wirklich bereit!

-   __Nach der ersten Iteration, später zu jedem Zeitpunkt oder wenn du fertig bist, befolge die Schritte zur Einreichung.__

## Abgabe

Nach Abschluss der Übung führe die folgenden Befehle aus:

```shell 
git add .
git commit -m "done"
git push origin master 
```   
Erstelle einen Pull-Request, damit deine TAs deine Arbeit überprüfen können.

_Du solltest einen Pull-Request (PR) erstellen, sobald du eine bedeutende Änderung vorgenommen hast. Du musst nicht warten, bis du mit dieser oder einer anderen Übung fertig bist, um den PR zu erstellen. Nach dem ersten PR wird jede Änderung, die du hochlädst (nach den vorherigen drei Schritten), automatisch im PR angezeigt, und deine TAs werden sie überprüfen können._

<!-- ## Abgabe -->    

<!-- Wenn du fertig bist und überprüft hast, dass alles einwandfrei funktioniert, klicke auf die Schaltfläche **Share** und kopiere den Link aus dem Feld *Share Link*. Sende diesen Link an deine TAs, damit sie deine Arbeit überprüfen können. 
![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_b2aa98f91affe5d4c5f12f216b069184.png) -->  

## Anweisungen

### Iteration 1: Namen und Eingabe

1.1 Erstelle eine Variable `hacker1` mit dem Namen des Fahrers.  
1.2 Gib aus: `"The driver's name is XXXX"` (`"Der Name des Fahrers ist XXXX"`).  
1.3 Erstelle eine Variable `hacker2` mit dem Namen des Navigators.  
1.4 Gib aus: `"The navigator's name is YYYY"` (`"Der Name des Navigators ist YYYY"`).

### Iteration 2: Bedingungen

2.1. Abhängig davon, welcher Name [länger](https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Global_Objects/String/length) ist, gib aus:    
<br>

- `The driver has the longest name, it has XX characters`  (`Der Fahrer hat den längsten Namen, er hat XX Zeichen.`) oder <br>
- `It seems that the navigator has the longest name, it has XX characters.` (`Es scheint, dass der Navigator den längsten Namen hat, er hat XX Zeichen.`) oder <br>
- `Wow, you both have equally long names, XX characters!` (`Wow, ihr habt beide Namen mit gleicher Länge, XX Zeichen!`).


### Iteration 3: Schleifen

3.1 Gib alle Zeichen des Fahrernamens aus, durch Leerzeichen getrennt und [in Großbuchstaben](https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase) z.B. `"J O H N"` 3.2 Gib alle Zeichen des Navigator-Namens in umgekehrter Reihenfolge aus.    
z.B. `"nhoJ"` 3.3 Abhängig von der [lexikografischen Ordnung](https://de.wikipedia.org/wiki/Lexikographische_Ordnung) der Zeichenketten gib aus: <br>
- `The driver's name goes first.` (`Der Name des Fahrers kommt zuerst.`) <br>
- `Yo, the navigator goes first, definitely.` (`Hey, der Navigator kommt zuerst.`) <br>
- `What?! You both have the same name?` (`Wow, ihr habt beide denselben Namen?`)

### Bonuszeit!

#### Bonus 1:

Gehe zur [Lorem Ipsum Generator](http://www.lipsum.com/) Webseite und:

- Generiere 3 Absätze. Speichere den Text in einer Variablen als Zeichenkette.
- Zähle die Anzahl der Wörter in der Zeichenkette mithilfe deines Programms.
- Zähle die Anzahl der Vorkommnisse des lateinischen Wortes [`et`](https://de.wiktionary.org/wiki/et#Latein) in der Zeichenkette.

#### Bonus 2:

Erstelle eine neue Variable `phraseToCheck` und weise ihr einen Wert vom Typ String zu. Schreibe einen Code, der überprüft, ob der Wert, den wir dieser Variable zugewiesen haben, ein [Palindrom](https://de.wikipedia.org/wiki/Palindrom) ist. Hier sind einige Beispiele für Palindrome:

- "A man, a plan, a canal, Panama!"
- "Amor, Roma"
- "race car"
- "stack cats"
- "step on no pets"
- "taco cat"
- "put it up"
- "Was it a car or a cat I saw?" und "No 'x' in Nixon".

**Hinweis**: Wenn Du Google zur Hilfe nimmst, um eine Lösung für diese Iteration zu finden, wirst Du möglicherweise auf Lösungen stoßen, die fortgeschrittene String- oder Array-Methoden verwenden (wie z.B. _join()_, _reverse()_, usw.). Versuche jedoch, das Wissen, das Du derzeit hast, anzuwenden, da Du eine ziemlich gute Lösung nur mit einer `for`-Schleife, `if-else`-Anweisungen und einigen `break`- und `continue`-Anweisungen erstellen kannst... Nur so als Tipp :smiley:

## Zusätzliche Ressourcen

- [String - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
- [if - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
- [while - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
- [for - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)


__Viel Spaß beim Coden!!__ :heart: