RECONNAISSANCE DES PERSONNES POUR ENVOI AUTOMATISE DE FEUILLES D'EMARGEMENT

Dépendances:
-commons-math3-3.6.1.jar
-opencv-2413.jar
-OpenCV 2.4.13 (https://github.com/opencv/opencv/releases/tag/2.4.13)

Installation Eclipse:

1.Importer le projet FeatureExtractionApplication sur votre Eclipse
2. Dans les propriétes des libraires du projet (Clic droit FeatureExtractionApplication -> Properties -> Add External JAR),
ajoutez les deux libraries commons-math3-3.6.1.jar et opencv-2413.jar
3. Allez dans Run -> Run Configurations -> Arguments, et ajoutez dans VM arguments:
-Djava.library.path=<Chemin de opencv-2413.dll>

Exemple:
-Djava.library.path=C:\Users\Guest\opencv\build\java\x64

Lancez MainGui avec cette configuration.
Pour plus de détails sur l'application, veuillez consulter le guide utilisateur.


**Des erreurs peuvent survenir avec le chemin de opencv-2413.dll
