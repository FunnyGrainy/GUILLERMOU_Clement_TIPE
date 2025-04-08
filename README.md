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
    Ce modèle permet de s'instaurer dans le thème de cette année (par exemple la représentation rond des boucles, on passe d'une boucle à l'autre), possède une formule mathématique d'équa diff et permet de facilement le modéliser via code.
    <br>
Le modèle prend en compte le fait que la population est composée d'une même espèce x 10000, ça prend pas en compte l'age de la population, en reprennant Wikipédia :
    <br>
    "The Lotka–Volterra predator-prey model makes a number of assumptions about the environment and biology of the predator and prey populations:
    <ul><li>The prey population finds ample food at all times.</li>
    <li>The food supply of the predator population depends entirely on the size of the prey population.</li>
    <li>The rate of change of population is proportional to its size.</li>
    <li>During the process, the environment does not change in favour of one species, and genetic adaptation is inconsequential.</li>
    <li>Predators have limitless appetite.</li>
    <li>Both populations can be described by a single variable. This amounts to assuming that the populations do not have a spatial or age distribution that contributes to the dynamics."</li></ul>
Donc qu'est ce qu'il se passerait si y a pas de nourriture, si on touche à une de ces assumptions ? si c'était une population naturelle ?

C'est sur l'aspect naturel que je souhaite me pencher, en prenant le cas des sangliers à Port Cros. L'idée est de savoir si des évènements naturels peuvent être retranscrits sur le modèle Lotka Volterra, le but est de mettre en question sa fiabilité.

Pour l'instant, à ce modèle a été rajoutée une battue, qui reduit la taille des prédateurs lorsque ces derniers dépassent un certain seuil.

OBJECTIFS :

- URGENT : Trouver une base de données pour connaître le nombre de sangliers, de proies, quand est ce que ce sont réalisées les battues, combien de sangliers sont tués par battues -> permettra d'avoir des paramètres fiables pour la suite
- Téléphoner à un institut de chasse pour demander :
  <ul><li>la chasse à porc croc des sangliers, qu'on chasse à certains moments, comprendre pourquoi ils font ça à ce moment là
</li> <li>quel modèle ils utilisent et pourquoi, demander à des instituts de chasse, pourquoi ils font ça, combien et à quel moment, si c'est empirique ou s'ils se basent sur un modèle scientifique ou pas, savoir s'ils tuent en fonction de combien j'en veux l'année prochaine, alors combien j'en tue cette année (parce que quand on fait la battue, on perd des proies, et on passe dans le cycle d'en dessous, et on aura encore + de biches l'année pro)</li>
</ul>
- Ajouter d'autres paramètres au modèle (que ce soit dans le bidouillage des paramètres, ou dans l'ajout d'un aléa (comme des loups qui mangnent les sangliers)

  Base donnée potentiellement intéressante actuellement : <ul> https://www.researchgate.net/publication/343583211_Colonisation_des_iles_d%27Hyeres_Var_sud_de_la_France_par_le_sanglier_Sus_scrofa_Colonization_of_the_islands_of_Hyeres_Var_south_of_France_by_the_wild_boar_Sus_scrofa#pf7
  Regarder autre part que les sangliers (facilement remplaçables), voir du côté des espèces sous marines ou des oiseaux (ALPO, protection des oiseaux)


-------------------------------------------------------------------
    
Notes fourre tout :
    Pistes : <ul><li>- Lotka Voltera avec 3 ou 4 espèces, dynamique des populations (voir la cyclique ?), la chaîne YT de Primer
    avec ses simulations, l'hotel d'Hilbert, la proba que 2 personnes aient le même anniversaire
    check aussi les 2 vidéos de squeezie sur les sites de psycho "ca a l'air nul mais intéressant"
    Rappel de comment présenter ma recherche :</li><li> présenter des formules avec les unités, des bases de données, les calculs et schémas de référence (avec des légendes
    (figure (x) - blabla)) expliquer les différents phénomène et utilisations des formules(avec des schémas)</li>
    <li> parler des l'évaluation de l'erreur, la qualité de la simulation faire une MAE, Mean absolute error
    tableau de résultat finaux : moyenne et écart type de l'erreur</li><li>- conclusion : bullet point de ce qu'on a réussi et pas réussi à faire dans nos expériences</li>
    <li>mettre les ref biblio, les codes (SAVOIR EXPLIQUER CE QU ILS FONT) </li></ul>

Notes appels :

    
    
    
    
    
  </p>
</body>

</html>
