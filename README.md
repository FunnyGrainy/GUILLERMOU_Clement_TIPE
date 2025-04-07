<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
  GUILLERMOU Clément MP2I
  <div style="text-align: center;">
    <h1>
      Journal de bord de TIPE
    </h1>
  </div>
  <br>
  <p>
Avancée du projet :
    Après quelques séances de recherches, et grâce à la recommandation de Mme Courrèges, je compte pour l'instant centrer mon TIPE sur le modèle Lotka Volterra classique.
    Ce modèle permet de s'instaurer dans le thème de cette année, possède une formule mathématique d'équa diff et permet de facilement le modéliser via code.

    Seule base donnée potentiellement intéressante : https://www.researchgate.net/publication/343583211_Colonisation_des_iles_d%27Hyeres_Var_sud_de_la_France_par_le_sanglier_Sus_scrofa_Colonization_of_the_islands_of_Hyeres_Var_south_of_France_by_the_wild_boar_Sus_scrofa#pf7



    -------------------------------------------------------------------
    
Notes fourre tout :
    Pistes : Lotka Voltera avec 3 ou 4 espèces, dynamique des populations (voir la cyclique ?), la chaîne YT de Primer
    avec ses simulations, l'hotel d'Hilbert, la proba que 2 personnes aient le même anniversaire
    check aussi les 2 vidéos de squeezie sur les sites de psycho "ca a l'air nul mais intéressant"
    Rappel de comment présenter ma recherche :
    - présenter des formules avec les unités, des bases de données, les calculs et schémas de référence (avec des légendes
    (figure (x) - blabla)) expliquer les différents phénomène et utilisations des formules(avec des schémas)
    - parler des l'évaluation de l'erreur, la qualité de la simulation faire une MAE, Mean absolute error
    tableau de résultat finaux : moyenne et écart type de l'erreur
    - conclusion : bullet point de ce qu'on a réussi et pas réussi à faire dans nos expériences
    - mettre les ref biblio, les codes (SAVOIR EXPLIQUER CE QU ILS FONT) 

    lotka voltera : faire le cas de base avec 1 proie 1 prédateur, faire le code, les cycles etc...

    le modèle prend en compte le fait que la population est composée d'une même espèce x 10000, ça prend pas en compte l'age de la population :

    The Lotka–Volterra predator-prey model makes a number of assumptions about the environment and biology of the predator and prey populations:

    The prey population finds ample food at all times.
    The food supply of the predator population depends entirely on the size of the prey population.
    The rate of change of population is proportional to its size.
    During the process, the environment does not change in favour of one species, and genetic adaptation is inconsequential.
    Predators have limitless appetite.
    Both populations can be described by a single variable. This amounts to assuming that the populations do not have a spatial or age distribution that contributes to the dynamics.

    donc qu'est ce qu'il se passerait si y a pas de nourriture, si on touche à une de ces assumptions ? si c'était une pop naturelle ?

    trouver des données l'institut des forets, données de chasses

    la chasse à porc croc des sangliers, qu'on chasse à certains moments, comprendre pourquoi ils font ça à ce moment là

    quel modèle ils utilisent et pourquoi, demander à des instituts de chasse, pourquoi ils font ça, combien et à quel moment, si c'est empirique ou s'ils se basent sur un modèle scientifique ou pas

    et trouver comment l'homme peut intervenir et influecer)
    quand les hommes 
    faire une battue numérique
    if nb biche>x -> battue
    en fonction de combien j'en veux l'année prochaine, combien j'en tue cette année
    le cycle rond des boucles, on passe d'une boucle à l'autre
    quand on fait la battue, on perd des proies, et on passe dans le cycle d'en dessous, et on aura encore + de biches l'année pro

  </p>
</body>

</html>
