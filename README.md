<h1>Première piste (actuelle) : Lotka Volterra</h1>

Correspond au thème de l'année par les simulations, les diagrammes de phases etc...

Code en Python du modèle classique fait assez facilement.
Pour rendre le travail + personnel, je me suis rappelé des battues réalisées à Port Cros concernant les sangliers -> j'ai donc décidé de partir sur un modèle modifié, pour y inclure des battues humaines sur les sangliers.
L'idée est de savoir si des évènements naturels peuvent être retranscrits sur le modèle Lotka Volterra, le but est de mettre en question sa fiabilité.
1ère problématique : "A quel point le modèle Lotka Volterra se rapproche-t-il de la réalité ?"
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
