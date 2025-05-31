# Einführung in die Softwareentwicklung
# Übung 1
## UE01-A01 TicTacToe Ausgabe
TicTacToe <a href="https://de.wikipedia.org/wiki/Tic-Tac-Toe">(Siehe Link)</a>, auch bekannt als "Drei gewinnt" oder "Xs and Os", ist ein einfaches
strategisches Spiel für zwei Spieler*innen. Es wird auf einem 3x3-Raster gespielt, und das Ziel
ist es, drei der eigenen Symbole (traditionell "X" für den ersten Spieler*in und "O" für den
zweiten Spieler*in) in einer horizontalen, vertikalen oder diagonalen Linie zu platzieren. Die
Spieler*innen setzen abwechselnd ihre Symbole, bis einer von ihnen drei in einer Linie hat
oder alle neun Felder belegt sind und das Spiel unentschieden endet.

### 1. Spielfeld-Ausgabe
Erstellen Sie zunächst ein einfaches Java-Programm, welches ein leeres TicTacToe Spielfeld mit * als
Begrenzungszeichen in der Konsole ausgibt.  
  
Beispieldialog:  
  
+---+---+---+  

|   |   |   |  

+---+---+---+  

|   |   |   |  

+---+---+---+  

| | | |  

+---+---+---+  

### 2. Fortgeschrittene Spielfeld-Ausgabe mit Variablen

Refaktorisieren ("refactoring" = Umstrukturierung von Code, ohne dessen Funktionalität zu
verändern) Sie ihren Code aus der ersten Teilaufgabe so, dass dieser nun zwei String
Variablen nutzt zur Ausgabe des leeren Spielfeldes.  

Diese Aufgabe zielt auf die Wiederverwendbarkeit von Codeteilen ab. Anstatt die gleiche
Zeile immer wieder zu schreiben, können bereits existierende Variablen wiederverwendet
werden.  

Beispieldialog:  

+---+---+---+  

|   |   |   |  

+---+---+---+  

|   |   |   |  

+---+---+---+  

| | | |  

+---+---+---+  

### 3. Einlesen eines vollen Spielfeldstandes
Lesen Sie nun neun Benutzereingaben über die Konsole ein und geben Sie diese gemeinsam
mit dem Spielfeld auf der Konsole aus.  

Enter value for row 1 and col 1: X  

Enter value for row 1 and col 2: O  

Enter value for row 1 and col 3: X  

Enter value for row 2 and col 1: O  

Enter value for row 2 and col 2: X  

Enter value for row 2 and col 3: X  

Enter value for row 3 and col 1: O  

Enter value for row 3 and col 2: O  

Enter value for row 3 and col 3: X  

+---+---+---+  

| X | O | X |  

+---+---+---+  

| O | X | X |  

+---+---+---+  

| O | O | X |  

+---+---+---+  

## UE01-A02 Einfache Rechnungen
Erstellen Sie ein einfaches Java-Programm, welches diverse Berechnungen durchführt, siehe
Beispieldialog.  

• Lesen Sie dazu zwei ganze Zahlen (Datentyp int) vom Benutzer ein.  

• Geben Sie das Ergebnis der Addition dieser beiden Zahlen aus.  

• Dann lesen Sie eine weitere Zahl ein und subtrahieren diese Zahl von der vorherigen
Summe.  

• Das Ergebnis der Subtraktion multiplizieren Sie mit einer weiteren Zahl und ziehen sie 2 davon ab.  

• Dessen Ergebnis wiederum wird mit einer neuen Zahl dividiert.  

• Schließlich wird der Divisionsrest gebildet.  

Beispieldialog:  
  
Zahl eingeben: 33  

Zahl für Addition eingeben: 44  

Addition: 33 + 44 = 77  

Zahl für Subtraktion eingeben: 7  

Subtraktion: 77 - 7 = 70  

Zahl für Multiplikation eingeben: 5  

Multiplikation: 70 * 5 = 350  

Zahl für Division eingeben: 13  
 
Division: 350 / 13 = 26  

Zahl für Divisionsrest eingeben: 4  

Divisionsrest: 26 % 4 = 2  

## UE01-A03 Lohnberechnungen
Herr und Frau Moser arbeiten in einer Tischlerei. Herr Moser bekommt ein jährliches
Grundgehalt von 40.000 Euro minus 1000 Euro, Frau Moser erhält 42.000 Euro.
Dazu kommt eine Bonuszahlung am Ende des Jahres von 1.000 Euro für Herrn Moser und
eine von 1.500 Euro für Frau Moser. Zusätzlich bekommt jeder pro Montagetag 50 Euro.
Schreiben Sie ein Java-Programm, das das gemeinsame Einkommen von Herrn und Frau
Moser berechnet.  

Verwenden Sie Variablen für einzulesende Werte (Anzahl der Montagetage) und Konstante
für alle fixen Werte (Grundgehalt und Bonus).  

  
Hinweis: Mit String.format("%,10d", i) können Sie eine ganze Zahl mit Tausendertrennzeichen
(Komma oder Punkt, je nach Spracheinstellungen) rechtsbündig auf 10 Stellen formatieren.  

  
Beispieldialog:  
  
 Anzahl Montagetage von Herrn Moser: 33  
 
Anzahl Montagetage von Frau Moser: 28  

Gehaltsberechnung  

Frau Moser:
Grundgehalt: 42,000 Euro  

Bonus:   1,500 Euro  

Montage: 1,400 Euro (28*50)  

Gesamt: 44,900 Euro  

Herr Moser:  

Grundgehalt: 40,000 Euro  

Bonus: 1,000 Euro  

Montage: 1,650 Euro (33*50)  

Gesamt: 42,650 Euro  

Gemeinsames Einkommen: 87,550 Euro  
## UE01-A04 Betriebskostenrechner
Erstellen Sie ein einfaches Java-Programm, welches basierend auf der Anzahl der gefahrenen
Kilometer die Betriebskosten berechnet:  

• Lesen Sie dazu die gefahrenen Kilometer (Datentyp int), den Verbrauch des Wagens
pro 100km in Liter ein (Datentyp double), sowie die Benzinkosten in Euro pro Liter
(Datentyp double).  

• Die Wartungskosten des Fahrzeugs sind mit 4.20 Euro plus 20% Mehrwertsteuer pro 100km veranschlagt.  

Verwenden Sie dafür eine Konstante.  

• Berechnen Sie die Bezinkosten der Fahrt, die entsprechenden Wartungskosten, sowie
die Gesamtkosten der Fahrt und geben Sie diese aus.  

Hinweis: Mit String.format("%,.2f", d) können Sie eine Gleitkommavariable d mit zwei Stellen
hinter dem Komma und Tausendertrennzeichen formatieren.  

Mit String.format("%,20.2f", d) können Sie zusätzlich angeben, dass insgesamt 20 Stellen
verwendet werden sollen.  

Mit String.format("%,10d", i) können Sie eine ganze Zahl mit Tausendertrennzeichen
rechtsbündig auf 10 Stellen formatieren.  
  

Beispieldialog:  
Dateneingabe:  

 Gefahrene Kilometer: 1000  
 
 Verbrauch/100km: 7.5  
 
 Benzinkosten/Liter: 1.995  

   
Daten:  

 Distanz: 1,000 km  
 
 Treibstoffkosten/l: 2.00 Euro  
 
 Verbrauch (l/100km): 7.50 l  
 
 Wartung pro 100km: 4.20 Euro  

   
Fahrtkosten:  

 Treibstoffkosten: 149.63 Euro  
 
 Wartungskosten: 42.00 Euro  
 
 Gesamtkosten: 191.63 Euro
 ## UE01-A05 Angebotserstellung
 Eine Reinigungsfirma verrechnet für die Reinigung von Büroräumen folgende Tarife:  
 
• Boden:
Bodenreinigung wird pro m² abgerechnet. Ein Quadratmeter Bodenreinigung kostet
12,50 Euro plus 2 Euro Sonderzuschlag.  

• Arbeitsräume:
Für jeden Arbeitsraum (= Büroraum, Seminarraum, Labor, etc.) wird zusätzlich zum
Boden eine Pauschale verrechnet, die abhängig von der Größe des Raumes ist  

o bis 40 m²: 34,00 Euro  

o bis 80 m²: 123,00 Euro  

o über 80 m²: 210,50 Euro.  

• Mehrwertsteuer:
Auf den Endbetrag werden 20% Mwst. verrechnet.  

<b>Verwenden Sie Konstanten für folgende Werte:</b>  

• Kosten pro Quadratmeter  

• Pauschale für Arbeitsräume bis 40 m²  

• Pauschale für Arbeitsräume bis 80 m²  

• Pauschale für Arbeitsräume über 80 m²  

<b>Lesen Sie folgende Daten ein:</b>  

• Firma, Name und Anschrift des Kunden  

• m² Boden  

• Anzahl der Arbeitsräume bis 40 m²  

• Anzahl der Arbeitsräume bis 80 m²  

• Anzahl der Arbeitsräume über 80 m²  

<b>Berechnen Sie folgende Werte:</b>  

• Zwischensummen der Reinigungskosten für Böden  

• Zwischensummen der Reinigungskosten pro Raumgröße  

• Gesamtkosten Netto (ohne Steuer)  

• Gesamtkosten Brutto (inkl. 20% Mehrwertsteuer)  

<b>Geben Sie folgende Werte aus:</b>  

• Kundendaten  

• Bodenfläche, Basiskosten für Bodenfläche  

• pro Raumgröße: Anzahl und Zwischensumme der Reinigungskosten  

• Gesamtkosten Netto  

• Mehrwertsteuer  

• Gesamtkosten Brutto  
  
Berechnen Sie dazu die Kosten der einzelnen Posten und geben Sie diese in einer
übersichtlichen Form aus. Es sollen die Preise für die jeweiligen Posten, Gesamtnetto, MwSt.,
Gesamtbrutto ersichtlich sein, siehe Beispieldialog.  

Hinweis: Mit String.format("%,.2f", d) können Sie eine Gleitkommavariable d mit zwei Stellen
hinter dem Komma und Tausendertrennzeichen formatieren.  

Mit String.format("%,20.2f", d) können Sie zusätzlich angeben, dass insgesamt 20 Stellen
verwendet werden sollen.  
  
Beispieleingabe:  

Angebotserstellung  
Dateneingabe:  
Firma: JKU  
Name: Maria Moser  
Anschrift: Altenbergerstr. 69, 4040 Linz  
Bodenfläche in m²: 573.5  
Anzahl Räume bis 40 m²: 7  
Anzahl Räume bis 80 m²: 3  
Anzahl Räume über 80 m²: 2  
...  
Angebot  
Kunde: Maria Moser  
Firma: JKU  
Adresse: Altenbergerstr. 69, 4040 Linz  
...  
Kosten pro Quadratmeter: 12.50 Euro  
Aufpreis Räume bis 40m²: 34.00 Euro  
Aufpreis Räume bis 80m²: 123.00 Euro  
Aufpreis Räume über 80m²: 210.50 Euro  
...  
Grundpreis: 573.50 m² x 12.50 = 7,168.75 Euro  
7 Räume bis 40m²: 7 x 34.0 = 238.00 Euro  
3 Räume bis 80m²: 3 x 123.0 = 369.00 Euro  
2 Räume über 80m²: 2 x 210.5 = 421.00 Euro  
...  
Netto: 8,196.75 Euro  
20.0% MwSt.: 1,639.35 Euro  
Brutto: 9,836.10 Euro  
...  
## UE01-A06 Wechselgeld-Berechnung
Schreiben Sie ein Java-Programm, das einen beliebigen, vom Benutzer eingegebenen DollarBetrag in Scheine und Münzen zerlegt, sodass möglichst viele große Währungseinheiten
benutzt werden.  
Wir verwenden zum Wechseln folgende Scheine: $100, $50, $20, $10, $5, $2, $1, sowie folgende
Münzen: ¢25, ¢10, ¢5, ¢1.  
Der Dollar- und der Cent-Betrag werden jeweils als ganze Zahlen eingelesen.  
Hinweis: Wir gehen im Moment davon aus, dass der Benutzer nur gültige Werte eingibt, d.h.
keine negativen Zahlen und max. 99 Cents.  

Beispieldialog:  

Enter dollars: 983  
Enter cents: 93  
Amount: $983.93  
Franklins: 9 x $100  
Grants: 1 x $50  
Jacksons: 1 x $20  
Hamiltons: 1 x $10  
Lincolns: 0 x $5  
Bucks: 3 x $1  
Quarters: 3 x ¢25  
Dimes: 1 x ¢10  
Nickels: 1 x ¢05  
Pennies: 3 x ¢01  
9 x 100 + 1 x 50 + 1 x 20 + 1 x 10 + 0 x 5 + 3 x 1 +  
3 x 0.25 + 1 x 0.10 + 1 x 0.05 + 3 x 0.01 = 983.93  
