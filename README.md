# software_craftmanship
Formateur : François devos
Participants : 
	- Yves
	- Mostapha
	- Saidi
	- Gérard
	
L'attendu de la formation : Découvrir la notion CraftmanShip 

CraftmanShip est lié à la notion de l'agilité et le but est de rapporter une qualité logiciel meilleure. 

Cycle de vie d'un projet "classique"
	1. Métier  Kickoff : 
	2. Définition du besoin
	3. IT : Analyse et chiffrage 
	4. Réalisation 
	5. Tests d'acceptation (recette)
	6. Corrections
	7. Go en production 

Les points clés : 
Besoin défini exhaustivement 
Engagement sur ce périmètre 
Réalisation 

Manifeste Agile 
Les individus et leurs interactions plus que les processus et les outils. 
Des logiciels opérationnels plus qu'une documentation exhaustive. 
La collaboration avec les clients plus que la négociation contractuelle. 
L'adaptation au changement plus que le suivi d'un plan. 
Réf. http://agile.manifesto.org 

Agile : 
	- Pilotage par la valeur métier
	- Collaboration des acteurs projets 
	- Engagement des acteurs
	- Test et qualité 
	- Industrialisation du delivery 

Introduction à l'eXtreme Programming (XP) 
XP se focalise sur comment réaliser le code. 
Ci-dessus les principes de base de XP : 
	- Revue de code par un binôme 
	- Tests 
	- Conception (Refactoring) 
	- Simplicité 
	- Compréhensions
	- Intégration
	- Cycle de développement très rapide pour nous adapter au changement. 

Les valeurs : 
	- Simplicité, 
	- Communication,
	- Courage,
	- Respect
	
Une architecture émergente : Travaille de manière itérative en se focalisant sur le besoin d'aujourd'hui pour trouver une solution simplicité. 

Refactoring : Le code doit être refactoré tout le temps pour améliorer la lisibilité. 

Gerrit : https://gerrit-review.googlesource.com/ 

Test unitaire : 
Tester et re-tester mon application avant chaque livraison. 
Test : il doit effectivement tester quelque choses (capacité à passer au rouge). 
Unitaire : une seule classe testée, avec un minimum de dépendances.
Rapide : moins d'une seconde d'exécution.
Déterministe : Répondre la même chose sans dépendre d'un paramètre extérieur. 
Simple : facile à comprendre et à adapter. 

Avant le TU, le code testable 
Ecrire un TU n'est  vraiment possible que si le code est testable 
	- Nécessite une architecture pensée dès le départ 
	- Penser injection de dépendance 
	- Programmation orientée interface (attention à ne pas tomber dans l'excès) 
Architecture pensée dès le départ 
	- Comment simuler les interfaces externes ? (base de données, appels réseaux)
	- Quels frameworks utiliser pour les mocks ?
	- Comment gérer les jeux de données fakes?
Injection de dépendance 
	- Graphe d'objets différents lors des TU que lors de l'exécution en production
	- Permet de sortir cette complexité du code, d'être plus flexible
Programmation orienté interface 
	- Pré-requis pour que l'injection de dépendance soit utilisable 

Fizzbizz test: Programme pour apprendre les tests => http://wiki.c2.com/?FizzBuzzTest 
