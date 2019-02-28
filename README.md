# KalmanSensys
Einführung in die g-h-Filter, Statistik und Kalmanfilter zur Sensorsignalverarbeitung

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/StefanMack/KalmanSensys/master)

Dieses Repository befindet sich noch im Aufbau. Es wird am dem Sommersemester 2019 in der Vorlesung Sensorsyteme und im dazugehörigen Projekt Verwendung finden.

### Übersicht der einzelnen Jupyter-Notebooks:
1. Der g-h-Filter am Beispiel eines Abstandssensors.
2. Beispiele zum g-h-Filter
3. Der diskrete Bayes-Filter zum Tracken eines Roboterfahrzeugs, Teil 1
4. Der diskrete Bayes-Filter zum Tracken eines Roboterfahrzeugs, Teil 2 
5. Grundlagen der Wahrscheinlichkeitsrechnung
6. Der eindimensionale Kalmanfilter, Teil 1 Grundlagen
5. Der eindimensionale Kalmanfilter, Teil 2 Simulationen

> Hinweis: Wenn Sie oben im File Explorer auf eine der beiden Jupyter Notebooks (Endung ".ipnyb") klicken, dann wird lediglich ein Viewer geöffnet, in dem Sie das Notebook nur anschauen können. Dieser Viewer funktioniert nicht immer zuverlässig.  
Daher verwenden Sie zum Anschauen der Notebooks besser den Viewer "nbviewer" [über diesen Link](https://nbviewer.jupyter.org/github/StefanMack/KalmanSensys/tree/master/).  
Möchten Sie die Codebeispiele darin einzeln ausführen und ändern, dann klicken Sie bitte für das jeweils geöffnete Notebook *im nbviewer* rechts oben auf das Menüitem "Execute on Binder" (Icon mit drei Ringen). Dadurch wird für dieses Notebook der Webservice Binder gestartet.  
Alternativ können Sie auch auf den schwarzroten Button "launch|binder" oben auf dieser Seite klicken. Damit gelangen Sie ebenfalls zu diesem Webserver, können anschließend aber unter den verschiedenen Notebooks auswählen.  
**Das Starten des Webservice binder kann bis zu einer Minute dauern.**



License
-----
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title"> Most contents of this book are based an the book "Kalman and Bayesian Filters in Python"</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/StefanMack/KalmanSensys" property="cc:attributionName" rel="cc:attributionURL">Roger R. Labbe</a> which is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Bemerkung: Um dieses Notebook lokal auf einem Rechner innerhalb Python 3.6 auszuführen sind die Bibliothekten numpy, matplotlib, scipy, collections, time und copy nötig. Für das Ausführen unter binder sind in der Datei ``requirements.txt`` jedoch nur die Bibliotheken numpy, matplotlib und scipy ohne Versionsnummern angegeben. Die Bibliotheken collections, time und copy fhren bei binder zu einem Fehler beim Starten - keine Ahnung wieso, liegt vermutlich an Python 3.7, welches bei binder verwendet wird.
