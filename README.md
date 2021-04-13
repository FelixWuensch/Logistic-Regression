# Logistic-Regression
Prüfungsaufgabe 1 - Erster Teil

Um dieses Projekt zu starten, folgen Sie dem Binder Badge:      [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FelixWuensch/Logistic-Regression/main)

# Ausführung der Übungsaufgabe

!!! Alle Befehle werden ausgeführt in dem die Zeile ausgewählt wurde und anschließend mit Shift (Großschreibtaste) und Enter gestartet wird !!!

1. Im ersten Schritt müssen alle benötigten Libraries installiert und importiert, so dass im Folgenden alle Befehle erfolgreich Ausgeführt werden können.
2. Danach werden unsere Daten im CSV Format eingelesen.
3. Daraufhin werden die Daten erst einmal begutachtet. Zunächst die ersten fünf Zeilen des Datensatzes (.head()), dann die Datentypen des Datensatzes (.info()) und zu guter letzt noch einmal die ersten Statistiken der Daten (.describe()).
4. Dann gehen wir über und untersuchen die Daten. Dazu erstellen wir zunächst ein Histogramm, welches die Altersverteilung in diesem Datensatz zeigt.
5. Im fünften Schritt wird ein Jointplot erstellt, welches das Alter (X-Ache) und das Area Income (Y-Achse) gegenüberstellt. Daraus lässt sich ablesen, wie viel jeder Kunde abhängig von seinem Alter verdient.
6. Beim nächsten Jointplot wird über das Alter (X-Achse) und die Daily Time Spent on Site (Y-Achse) aufgezeigt, welche Personen Gruppen abhängig vom Alter wie viel Zeit auf der Seite verbringen. Dies ist diesmal nicht in Punkten sondern in Regionen aufgezeigt. Die innersten Kreise zeigen die intensivste Nutzung.
7. Als nächstes wir dann wieder in einem Jointplot die Daily Time on Site (X-Achse) und die Daily Internet Usage (Y-Achse) betrachtet. Daraus lässt sich dann ablesen, wie viel Zeit die Personen auf der Internetseite verbringen in Relation zu ihrer gesamten Internetnutzungszeit.
8. Zu guter letzt wird noch mit einem Pairplot, anhand aller Kriterien in Relation zu einander gesetzt, gezeigt wer auf die Werbung geklickt hat und wer nicht. Damit endet dann auch die Explorative Datenanalyse.
9. Dann geht es über zur Logistischen Regression. Hierbei wird zunächst die SKLearn Library importiert. Danach werden die Daten in X-Daten und Y-Daten aufgeteilt. Im Folgenden werden dann die X-Daten wiederum aufgeteilt in Test- und Trainingsdaten, ebenso passiert das gleiche mit den Y-Daten.
10. Damit kann dann das trainieren und fitten der logistischen Regression beginnen. Dazu wird die Logistic Regression aus der SKLearn Bibliothek importiert und ein Regressionsmodell angelegt. Danach wird das Modell mit den X- und Y-Trainingsdaten gefittet.
11. Nun kann mit der Vorhersage und Auswertung begonnen werden. Dafür wird eine Vorhersage mit dem zuvor trainierten Modell ausgeführt, auf Basis der X-Testdaten. Um das ganze zu überprüfen wird von der SKLearn Bibliothek der Classification-Report importiert und auch direkt angewandt mit den Y-Testdaten und der zuvor generierten Vorhersage. Daraus erhält man dann eine Tabellarische Auflistung wie genau die Vorhersagen sind. Umso näher diese bei 1 liegen umso genauer ist die Vorhersage. In diesem Fall sind die Vorhersagen sehr gut, da wir eine Präzision von 0.86 bzw. 0.96 haben.

Damit ist das Kapitel der Logistischen Regression abgeschlossen. Wir haben uns dafür die Daten genauer angeschaut mit der Explorativen Datenanalyse um eine gute Aufteilung der Daten treffen zu können. Dann haben wir die Aufteilung vorgenommen, das Model erstellt, trainiert und eine Vorhersage treffen lassen. Zu guter letzt haben wir die Vorhersage auf seine Genauigkeit untersucht und dabei war alles in Ordnung. Somit gehen wir weiter zum Thema K Nearest Neighbors. 
