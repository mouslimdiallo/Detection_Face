# Detection_Face

1.	La détection du visage qui consiste à (localiser, délimiter, carré, cercle);
2.	L’alignement du visage qui consiste à (normaliser, la géométrie);
3.	L’extraction de caractéristiques (extraire les traits pour la reconnaissance du visage);
4.	Reconnaissance du visage à travers le modèle;



1.3	Détection du visage 

•	Pour que cela fonctionne, nous utiliserons un modèle de fichier en cascade haarcascade en XML avec 2 paramètres (scalFactor, minNeighbors);

•	Le modèle que nous allons utiliser est performant pour la détection des visages : MTCNN(Multi-task Cascaded Convolutional Networks
•	), il est multitâche, pré entraîné avec de la vitesse et une bonne précision;
•	
•	Utiliser keras et Python
•	
•	Créer le dataset avec une taille des images : 224 x 224 px ;
•	
•	Utiliser des boucles et des fonctions avec des paramètres;
•	
•	Pour la reconnaissance faciale, nous utiliserons un modèle performant pour la vérification : VGGFace2.

La méthode consiste d'abord à détecter les visages sur des photos, puis à vérifier les visages afin de les reconnaître ou de les identifier. Donc ici, nous sommes face à deux problématiques, la détection et l'identification des visages sur des photos ou des vidéos.

Nous utiliserons les techniques de vision par ordinateur avec l’apprentissage profond afin d'obtenir un modèle performant capable de résoudre cette problématique. 

