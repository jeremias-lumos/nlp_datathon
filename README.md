# NLP Datathon

Hallo liebe Datathon Teilnehmer, 

freu mich, dass ihr dabei seid. Unten findet ihr eine kurze Beschreibung des Repositories:

## Dataset

Der Datensatz dieser Challenge basiert auf dem [OMQ datensatz](http://www.dfki.de/~neumann/resources/omqdata.html) welche aus deutschsprachigen Interaktions und Email Anfragen an ein Softwareunternehmen besteht

Ihr findet die Daten unter `data/train.csv` als CSV File (seperator: ','). Die Test-Daten findet ihr unter `data/test.csv` wobei hier nur die E-Mail Texte drinnen sind, aber nicht die richtigen Klassen, sodass ihr diese nur mit dem trainierten Modell herausfinden müsst.

## Helper Functionality

Zusätzlich stellen wir euch die Grundfunktionen bereit, damit ihr mit einem GMail Account interagieren können:

- Ungelesene EMails abfragen
- EMails senden

Diese Funktionen  sind im `GMail-API.ipynb` notebook zu finden und zusätzlich auch kurze Beispiele, wie die Funktionen verwendet werden können. 

Ihr solltet bereits eine E-Mail bekommen haben, welche die Credentials zu eurem Gruppen E-Mail Account als pickle-token `token.pickle` angehängt hat. Diesen Token einfach in den selben Folder wie das Notebook legen (oder den Pfad im Notebook ändern) und ihr solltet Zugriff auf euren E-Mail Account haben. (Testweise könnt ihr euch gerne E-Mail an den Account schicken bzw E-Mail von diesem Account abschicken. 


## Git-Hub

Ich empfehle euch dieses Repository einfach zu forken und direkt in dem geforkten Repository weiterzuarbeiten, damit ihr gleich losstarten könnt. Natürlich ist es euch frei überlassen das auf alle möglichen anderen arten zu lösen. 


Bei Fragen einfach an fabian.traxler@lumos-consulting.at melden :) 
