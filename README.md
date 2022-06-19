Name des Projekts:	K Means Clustering
Link zum MyBinder: 	https://github.com/HuseyinBgn/3KMeansClustering

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in dem K_Means_Clustering.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!


1. Libraries installieren & importieren: 
- Hier werden die Librairies für die Datenverarbeitung und -visualisierung installiert und anschließend importiert

2. Die Daten:
- College_Data.csv Datei wird gelesen
- College_Data Daten werden überprüft ob sie richtig gelesen wurden, ob die Darstellung korrekt übernommen wurde, usw.

3. Explorative Daten Analyse:
- Ein Scatterplot von "Grad.Rate" und "Room.Board", bei dem die Punkte nach "Private" Spalte gefärbt sind.
- Erneut ein Scatterplot, diesmal von "F.Undergrad" und "Outstate".
- Histogramm der "Out of State Tuition" nach "Private" geteilt.
- Gleiches Histogramm mit "Grad.Rate".
- Nach Universitaeten filtern, die einen "Grad.Rate" von mehr als 100% haben.
- Anpassung der Datei von der jeweiligen Universitaet, da es kein Sinn ergibt.
- Erneutes Ueberpruefen nach mehr als 100% "Grad.Rate".
- Histogramm erneut darstellen.

4. K Means Cluster erstellen:
- Erstellen des K Means Clusters

5. Auswertung:
- Anpassung der Tabelle durch Hinzufügen der neuen Spalte "Cluster". Es soll Oeffentliche Unis als 0 und Private als 1 darstellen.
- Ausgabe der Ergebnisse und der Konfusionsmatrix von K Means Clustering Modell.