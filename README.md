# KalmanSensys
Einführung in die g-h-Filter, Statistik und Kalmanfilter zur Sensorsignalverarbeitung

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/StefanMack/KalmanSensys/master)

Dieses Repository ist nun in der ersten Version fertig. Es findet seit dem Sommersemester 2019 in der Vorlesung Sensorsysteme und im dazugehörigen Projekt Verwendung.

### Übersicht der einzelnen Jupyter-Notebooks:
1. Der g-h-Filter am Beispiel eines Abstandssensors.
2. Beispiele zum g-h-Filter
3. Der diskrete Bayes-Filter zum Tracken eines Roboterfahrzeugs, Teil 1
4. Der diskrete Bayes-Filter zum Tracken eines Roboterfahrzeugs, Teil 2 
5. Grundlagen der Wahrscheinlichkeitsrechnung
6. Der eindimensionale Kalmanfilter, Teil 1 Grundlagen
5. Der eindimensionale Kalmanfilter, Teil 2 Simulationen
6. Mehrdimensionale Gaußverteilungen
7. Der mehrdimensionale Kalman-Filter, Teil 1 Grundlagen
8. Der mehrdimensionale Kalman-Filter, Teil 2 Simulationen

> Hinweis: Wenn Sie oben im File Explorer auf eine der beiden Jupyter Notebooks (Endung ".ipnyb") klicken, dann wird lediglich ein Viewer geöffnet, in dem Sie das Notebook nur anschauen können. Dieser Viewer funktioniert nicht immer zuverlässig.  
Daher verwenden Sie zum Anschauen der Notebooks besser den Viewer "nbviewer" [über diesen Link](https://nbviewer.jupyter.org/github/StefanMack/KalmanSensys/tree/master/).  
Möchten Sie die Codebeispiele darin einzeln ausführen und ändern, dann klicken Sie bitte für das jeweils geöffnete Notebook *im nbviewer* rechts oben auf das Menüitem "Execute on Binder" (Icon mit drei Ringen). Dadurch wird für dieses Notebook der Webservice Binder gestartet.  
Alternativ können Sie auch auf den schwarzroten Button "launch|binder" oben auf dieser Seite klicken. Damit gelangen Sie ebenfalls zu diesem Webserver, können anschließend aber unter den verschiedenen Notebooks auswählen.  
**Das Starten des Webservice binder kann bis zu einer Minute dauern.**



License
-----
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>. Most contents of this book are based an the book "Kalman and Bayesian Filters in Python"</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python" property="cc:attributionName" rel="cc:attributionURL">Roger R. Labbe</a> which is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

*Bemerkung*: Um dieses Notebook lokal auf einem Rechner innerhalb Python 3.6 auszuführen, sind die Bibliotheken numpy, matplotlib, scipy, collections, time und copy nötig. Für das Ausführen unter binder sind in der Datei ``requirements.txt`` jedoch nur die Bibliotheken numpy, matplotlib und scipy ohne Versionsnummern aufgeführt. Die Bibliotheken collections, time und copy führen bei binder zu einem Fehler beim Starten des Webservice - keine Ahnung wieso, liegt vermutlich an Python 3.7, welches bei binder verwendet wird.
