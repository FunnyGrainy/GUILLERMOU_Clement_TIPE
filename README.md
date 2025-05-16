<h1>Première piste (actuelle) : Lotka Volterra</h1>

Correspond au thème de l'année par les simulations, les diagrammes de phases etc...

Code en Python du modèle classique fait assez facilement.

Pour rendre le travail + personnel, je me suis rappelé des battues réalisées à Port Cros concernant les sangliers -> j'ai donc décidé de partir sur un modèle modifié, pour y inclure des battues humaines sur les sangliers.

L'idée est de savoir si des évènements naturels peuvent être retranscrits sur le modèle Lotka Volterra, le but est de mettre en question sa fiabilité.

<h3>1ère problématique : "A quel point le modèle Lotka Volterra se rapproche-t-il de la réalité ?"</h3>

Cependant je me suis heurté aux problèmes suivants :
* Je n'ai pas de données concernant la natalité, mortalité ni même un nombre général de proies et prédateurs
* Les sangliers au départ étaient les proies, mais je n'ai aucune idée de qui est la proie n1 du sanglier.
* La manière dont j'implémente la battue me semble trop naïve dans son impact pour être la réalité : j'utilise un seuil qui fait baisser le nombre de sangliers si jamais le seuil est dépassé.

Avant les vacances d'Avril, mes pistes notables et points à mettre au clair : 
1. Obtenir une base de donnée fiable
2. S’intéresser à d’autres facteurs naturels (saisons, vieillesse,
sécheresse...)
3. Comparer un impact humain vs impact animal sur les
prédateurs
4. S’intéresser à d’autres modèles de proie-prédateur (Holling,
Kermack-McKendrick)
----------------------------------
Durant les vacances d'Avril j'ai pu avoir contact avec Bruno GIAMINARDI, Directeur de la Fédération des chasseurs du Var et Alison PESSON, Cheffe du bureau chasse, faune sauvage, pastoralisme.

Avec eux j'ai pu avoir des informations sur les méthodes de chasse, sur les sangliers en eux mêmes :
* Il existe un mode de chasse "classique" + en lien avec Lotka Volterra, présent dans le Var et un mode "destructif" où le but est qu'il n'y ait plus du tout de sangliers, mode utilisé à Port Cros.
* Les opérations se font principalement sur les plaintes relevées

10 à 15 sangliers tués +- 50 % en temps normal (prendre en compte le facteur météo genre pluie qui peut affaiblir le nombre battu (possibilité de repartir bredouille)

faire une variable plainte : la faire monter en fonction de :

- nombre de sangliers
- un cpt qui monte de 1 aléatoirement pour siginfier un dégat (le rendre + probable + y a de sanglier)
- un facteur estival (+ facilement montable en été car les sangliers sont en urbain manger des poubelles)

Parler de Port Cros particulièrement, avec que les hommes et les sangliers puis s'étendre dans le Var et, avec les loups, voir comment cela peut changer avec une 3ème espèce.
16 mai 2025 : j'ai envoyé un mail à l'OFB, l'ONF et le Museum du Var et au contact du mec de Port Cros que m'a donné Pesson

