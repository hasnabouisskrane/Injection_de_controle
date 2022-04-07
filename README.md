Part 2: Mise en oeuvre de l'injection des dépendances.


Cette screenshot montre l'injection des dépendances en utilisant le framework Spring avec la version XML.


![image](https://user-images.githubusercontent.com/61788817/162300045-e96e31ed-5bf2-49b7-8da8-60acda08e98c.png)

La figure suivante illustre l'injection des dépendances en utilisant le framework Spring avec la version annotations.

![image](https://user-images.githubusercontent.com/61788817/162301254-b3c79ca1-5213-4d7d-afbb-b57d4c3909e1.png)


Par la suite on utilise Apache Maven qui est un outil de gestion et d'automatisation de production des projets logiciels Java en général et Java EE en particulier. Il est utilisé pour automatiser l'intégration continue lors d'un développement de logiciel.

mvn compile : Cette commande permet de compiler le code source du projet.

![image](https://user-images.githubusercontent.com/61788817/162304495-718d51ec-410c-4278-ad4d-44e19fe36a59.png)

mvn test : avec cette commande, on peut exécuter les étapes de test du projet.

![image](https://user-images.githubusercontent.com/61788817/162306120-11d87beb-a6b3-40d9-a12a-0c78c1674966.png)

mvn package : avec cette commande de cycle de vie Maven, on empaquete ou crée un fichier WAR ou JAR de projet pour pouvoir utiliser un format distribuable.

![image](https://user-images.githubusercontent.com/61788817/162306578-e4f279e8-af80-4c49-9e7e-6b872e4f8904.png)

![image](https://user-images.githubusercontent.com/61788817/162308599-b2657096-2e2e-40df-a781-5c2a1f11ccb6.png)

mvn install : cette commande permet de déployer les fichiers WAR/JAR empaquetés en les stockant sous forme de classes dans le référentiel local.

![image](https://user-images.githubusercontent.com/61788817/162311152-b41e3700-e730-40ae-9cc2-82419c9de470.png)

mvn clean : ici, le projet est nettoyé pour supprimer tous les fichiers de génération précédente générés.


![image](https://user-images.githubusercontent.com/61788817/162311659-1d90994a-0900-4866-80d5-643f8295a966.png)









