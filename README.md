# GL02_project
-Assurez-vous d'avoir Node.js installé sur votre machine.
-Vérifiez votre version avec node -v et npm -v.
-Installation des dépendances
-Pour installer toutes les dépendances nécessaires d'un coup, exécutez la commande suivante dans le répertoire du projet :
	>>>>npm install
	
-Cette commande installe automatiquement les modules suivants :

cli-chart : Génère des graphiques dans la console.
express : Fournit un framework web rapide et minimaliste.
inquirer : Crée des interfaces interactives en ligne de commande.
plotly : Génère des graphiques interactifs.

-Si vous rencontrez un problème avec npm install, vous pouvez installer chaque dépendance individuellement :

	>>>>npm install <nom-du-module>
	
-Par exemple, pour installer inquirer uniquement :

	>>>>npm install inquirer

-Exécution du programme
-Utilisez la commande suivante pour exécuter le programme principal :

	>>>>node main.js

-Exécution des tests unitaires
-Assurez-vous d'avoir installé Jasmine pour exécuter les tests unitaires :

	>>>>npm install jasmine --save-dev

-Lancez les tests avec cette commande :

	>>>>npm test

-Si vous rencontrez des erreurs, vérifiez que toutes les dépendances nécessaires sont correctement installées.
