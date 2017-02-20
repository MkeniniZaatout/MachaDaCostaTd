# MachaDaCostaTd  
## Repot pour déposer les tds Android

#### Interface Utilisateur Native
Présentation du projet TD2  

Le sujet du td à realiser  :  http://www.machada.fr/lpidse/android_td2.pdf  


#### Structure du projet
```
/TD2-master
  |- app/
	|- src/
		|- androidTest
			|- java.com.example.rl633611.tp2
				ExampleInstrumentedTest.java
		ExampleInstrumentedTest.java
		|- main
			|- java
			|- ..., GalleryGridView.java, ImageAdapter.java , MainActivity.java , NavDrawer.java, NumberPickerView.java
			|- res
			 AndroidManifest.xml
		|- test
			|- java.com.example.rl633611.tp2
				ExampleUnitTest.java
  |- gradle/
	|- wrapper
  
```

##### Observation :  

##Elements manquants : 
-number picker  
-Toolbar  

##### Layout principal
![Github](https://github.com/GregoryVesic/InterfaceUtilisateurNative/blob/master/images-td2/main.png)

* Ils ont bien respectés les consignes du premier layout, le submit est bien à droit en dessous du EditText et l'image au dessus.

##### Layout NumberPicker
![Github](https://github.com/GregoryVesic/InterfaceUtilisateurNative/blob/master/images-td2/age.png)

* Ajout de l'objet NumberPicker se situant bien entre 10 et 20
* Ajout du bouton Next pour aller vers le GridView

##### Layout GridView
![Github](https://github.com/GregoryVesic/InterfaceUtilisateurNative/blob/master/images-td2/gallery.png)
* La gallery correspond bien aux attentes du tp2 il  y a bien 2 colonnes, et autant de lignes qu'il y a d'images. De plus il y a bien du menu avec les (...) qui affiche ensuite le choix entre 'TD2', 'Settings' et 'TD2 Developed by MEYER PONZO'.
