# Überschrift der ersten Ebene

Dies ist ein gewöhnlicher Absatz nach der Überschrift der ersten Ebene. In Markdown werden gewöhnliche Absätze jeweils durch eine Blindzeile voneinander getrennt.

Hier beginnt nun also der zweite Absatz. Ein einfacher Zeilenumbruch wird erreicht indem zwei oder mehr Leerzeichen am Ende der Zeile eingegeben werden und eine neue Zeile begonnen wird,  
… so wie diese hier. \
Im iA Writer funktioniert aber auch Shift Return.

Ein oder mehrere Wörter können zwischen je einem Sternzeichen (`*`) oder Unterstrich (`_`) gesetzt werden um diese/s *kursiv* auszuzeichnen.

Ein oder mehrere Wörter können zwischen je zwei Sternzeichen (`**`) oder Unterstrich (`__`) gesetzt werden um diese/s **fett** auszuzeichnen.

Beim FirIA Template wurde versucht die Satzbreite,<span style="color:red;"> also die Anzahl Zeic</span>hen einer Zeile, ungefähr im Bereich von 50 bis 70 Zeichen zu halten. 

Verkleinere und vergrössere doch einmal die Fenste<span style="color:red;">rbreite. Anhand des </span>rot markierten Textes, kannst du die bevorzugte Satzbreite ablesen.

## Überschrift der zweiten Ebene

Ein gewöhnlicher Absatz, welcher zwischen einer Überschrift der zweiten Ebene und der Überschrift einer dritten Ebene befindet.

### Überschrift der dritten Ebene

Ein gewöhnlicher Absatz, welcher zwischen einer Überschrift der dritten Ebene und einer Überschrift der vierten Ebene befindet.

#### Überschrift der vierten Ebene

Ein gewöhnlicher Absatz, welcher zwischen einer Überschrift der vierten Ebene und einer Überschrift der fünften Ebene befindet.

##### Überschrift der fünften Ebene

Ein gewöhnlicher Absatz, welcher zwischen einer Überschrift der fünften Ebene und einer Überschrift der sechsten Ebene befindet.

###### Überschrift der sechsten Ebene

Ein gewöhnlicher Absatz, welcher zwischen einer Überschrift der sechsten Ebene und einer Überschrift der ersten Ebene befindet.

# Listen

## Nummerierte Listen

Um nummerierte Listen zu erzeugen, tippe einfach die Zahl 1 gefolgt von einem Punkt und einem Leerzeichen hinzu (1. ) und beginne mit dem Inhalt des ersten Listenpunkts. 

Theoretisch kann irgendeine Zahl als Nummerierung benutzt werden. Markdown wandelt dies jedoch immer in eine nummerierte Liste um, welche mit der Nummer 1 beginnt und sich jeweils um eine Zahl erhöht.

1. Zutat Eins
2. Zutat Zwei
3. Zutat Drei, welche eine etwas längere Beschreibung benötigt um zu demonstrieren wie der Einzug eines Listenpunkts aussieht, wenn dieser über mehrere Zeile läuft.
4. Zutat Vier
5. Zutat Fünf, welche noch eine Unterliste mit Aufzählungszeichen enthält:
	- Füge vor die Aufzählungszeichen der Unterliste 4 Leerzeichen oder ein Tabulator ein, damit sie als Unterliste erkannt wird.
	- nächster Listenpunkt
	- letzter Listenpunkt der Unterliste
6. Zutat Sechs
7. Zutat Sieben
8. Zutat Acht
9. Zutat Neun
10. Zutat Zehn

## Ungeordnete Listen (mit Aufzählungszeichen)

Um Listen mit Aufzählungszeichen zu erzeugen, können in Markdown folgende Zeichen zu Beginn eines Listenpunkts verwendet werden:

- `-` (Bindestrich),
- `*` (Sternzeichen) oder 
- `+` (Pluszeichen) verwendet werden.

Hier eine Musterliste:

- Zutat Eins
- Zutat Zwei, welche noch eine Unterliste mit Aufzählungszeichen enthält:
	- Füge vor die Aufzählungszeichen der Unterliste 4 Leerzeichen oder ein Tabulator ein, damit sie als Unterliste erkannt wird.
	- nächster Listenpunkt
	- letzter Listenpunkt der Unterliste
- Zutat Drei
- Zutat Vier, welche eine etwas längere Beschreibung benötigt um zu demonstrieren wie der Einzug eines Listenpunkts aussieht, wenn dieser über mehrere Zeile läuft.
- Zutat Fünf

## Aufgabenliste

- [ ] Aufgabe 1, welche eine etwas längere Beschreibung benötigt um zu demonstrieren wie der Einzug eines Listenpunkts aussieht, wenn dieser über mehrere Zeile läuft.
- [x] Aufgabe 2, welche erledigt ist.
- [ ] Aufgabe 3, welche noch nicht erledigt ist.

Es ist auch möglich Aufgabenlisten zu nummerieren:

1. [ ] Aufgabe 1, welche eine etwas längere Beschreibung benötigt um zu demonstrieren wie der Einzug eines Listenpunkts aussieht, wenn dieser über mehrere Zeile läuft.
2. [x] Aufgabe 2, welche erledigt ist.
3. [ ] Aufgabe 3, welche noch nicht erledigt ist.

# Blockquote

Mit Markdown kann man auch Inhalte zitieren. Es geht also um Texte, die nicht von mir selbst, sondern von jemand anderem geschrieben wurde. Man nennt diese Auszeichnung *Blockquote.*

> Um einen gewöhnlichen Absatz als *Blockquote* zu verwenden, wird am Anfang ein Grösser-als-Zeichen (>) gefolgt von einem Leerzeichen gesetzt.

Es ist auch möglich weitere Auszeichnungen innerhalb von Blockquotes zu verwenden, z.B. nummerierte Listen:

> 1. Zitierte nummerierte Liste; Punkt 1
> 2. Zitierte nummerierte Liste; Punkt 2
> 3. Zitierte nummerierte Liste; Punkt 3

… oder Listen mit Aufzählungszeichen:

> - Liste mit Aufzählungszeichen; Punkt 1 
> - Liste mit Aufzählungszeichen; Punkt 2  
> mit einem Zeilenumbruch
> - Liste mit Aufzählungszeichen; Punkt 3

# Horizontale Linie

Eine horizontale Linie kann verwendet werden um Inhalte visuell voneinander zu trennen.

***

In Markdown wird eine horizontale Linie indem **drei** Sternzeichen (`*`), Bindestriche (`-`) oder Unterstriche (`_`) auf einer eigenen Zeile eingegeben wird.

# Tabelle

Tabellen waren in der ersten Markdown Syntax noch nicht vorhanden. Diese können unter anderem mit der *GitHub Flavored Markdown* Syntax genutzt werden, siehe dazu auch den Beitrag auf [markdown-syntax.de](http://markdown-syntax.de/Syntax-GFM/Tabellen/).

Der iA Writer unterstützt diese Schreibweisung und enthält auch einen praktischen Dialog zur Erstellung des Grundgerüsts.

| Überschriftszelle, die links ausgerichtet ist | Überschriftszelle, die zentriert ausgerichtet ist | Überschriftszelle, die rechts ausgerichtet ist | 
| :--- | :---: | ---: |
| Datenzelle, die links ausgerichtet ist | Datenzelle, die zentriert ausgerichtet ist | Datenzelle, die rechts ausgerichtet ist | 
| Datenzelle, die links ausgerichtet ist | Datenzelle, die zentriert ausgerichtet ist | Datenzelle, die rechts ausgerichtet ist |
| Datenzelle, die links ausgerichtet ist | Datenzelle, die zentriert ausgerichtet ist | Datenzelle, die rechts ausgerichtet ist | 
[Beschreibung][table-example]

# Fussnoten

Auch Fussnoten gehören zur erweiterten Markdown Syntax.[^1] 

[^1]: Die Referenznummer wurde im Text mit `[^1]` gesetzt. Die Fussnote kann irgendwo im Dokument in einem eigenen Absatz gesetzt werden und beginnt so: `[^1]:`. 

Wird ein PDF aus Markdown erstellt, stellt man fest, dass es eigentlich Endnoten sind, da sie am Ende des Dokuments stehen.[^Fussnoten können auch *inline*, also direkt im entsprechenden Absatz, gesetzt werden. Die Syntax dafür sieht so aus: `[^Fussnoten können … sieht so aus:]`].

# Code

Programmcode oder Ähnliches kann entweder in *inline*, also innerhalb eines Absatzes, z.B. so: `<div class="test">`, oder als separaten Block, z.B. so:

    <html>
      <head>
      </head>
    </html>

*Inline* wird der entsprechende Text zwischen Backtick-Zeichen (‌`) gesetzt 

Ein Codeblock wird als solchen ausgezeichnet, der ganze Block mindestens ein Tab eingerückt wird.

# Links

Hyperlinks verweisen auf eine Website und werden wie folgt erstellt: 

	[Linktext](Linkadresse)

Demnach ergibt 

	[Google](https://google.com)

den Hyperlink

[Google](https://google.com)

# Bilder

Ähnlich wie Hyperlinks werden Bilder integriert.

	![Beschreibungstext](Adresse-des-Bildes)

Demnach wird mit

	![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/2880px-Markdown-mark.svg.png)

das Bild

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/2880px-Markdown-mark.svg.png)

hinzugefügt.