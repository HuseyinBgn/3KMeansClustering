Name des Projekts:	K Means Clustering

Link zum MyBinder: 	[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HuseyinBgn/3KMeansClustering/HEAD)

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in dem K_Means_Clustering.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!

Zum Ausführen der einzelnen Code-Zeilen "STRG" + "Enter" Tasten drücken.
Beachten Sie keine der Zeilen zu überspringen, denn sonst kann es zu Fehlerhaften Ausführung führen.

1. Libraries installieren & importieren: 
- Librairies für die Datenverarbeitung und -visualisierung werden installiert und anschließend importiert.

2. Die Daten:
- College_Data.csv Datei wird gelesen.
- Mit head(), info() und describe() Methoden wird auf die Korrektheit und Darstellung der Tabelle überprüft.

3. Explorative Datenanalyse:
- Ein Scatterplot von "Grad.Rate" und "Room.Board", bei dem die Punkte nach "Private" Spalte gefärbt sind.
- Erneut ein Scatterplot, diesmal von "F.Undergrad" und "Outstate".
- Histogramm der "Out of State Tuition" nach "Private" geteilt.
- Gleiches Histogramm mit "Grad.Rate".
- Nach Universitaeten filtern, die einen "Grad.Rate" von mehr als 100% haben.
- Anpassung der Datei von der jeweiligen Universitaet, da es kein Sinn ergibt. Man kann nicht mehr als 100% Abschlussrate haben.
- Erneutes Ueberpruefen nach mehr als 100% "Grad.Rate". Kein Ergebnis, also alles wieder im grünen Bereich.
- Histogramm erneut darstellen.

4. K Means Cluster erstellen:
- Erstellen des K Means Clusters. Anzahl der Cluster wird auf 2 festgelegt.
- Trainieren des K Means Cluster Modells mit Hilfe fit() Methode ohne Spalte "Private".

5. Auswertung:
- Anpassung der Tabelle durch Hinzufügen der neuen Spalte "Cluster". Es soll Oeffentliche Unis als 0 und Private als 1 darstellen.
- Ausgabe der Ergebnisse und der Konfusionsmatrix von K Means Clustering Modell.