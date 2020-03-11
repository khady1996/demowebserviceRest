# demowebserviceRest
Génération du fichier WAR:
A la racine du projet demorestfullrs exécute la commande suivante dans l'invite de commande:
$ mvn package
Une fois que l'invité de commande affiche "BUILD SUCCESS", vous pouvez aller dans le dossier "target" et récuperer le fichier WAR « demorestfullrs.war ».
Deplacer le fichier demorestfullrs.war  dans le dossier webapps de Tomcat
Pour tester, veuillez démarrer votre serveur Tomcat et taper sur votre navigateur : http://localhost:8080/demorestfullrs/rest/hello/ « entrer votre paramètre » 
http://localhost:8080/demorestfullrs/rest/hello/ => sans paramètre
