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
Avancée du projet : APPEL AVEC LE DIRECTEUR DE LA FEDERATION DE CHASSE DU VAR LUNDI 14 à 14H <br/>
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
<h2>Appel du 8 avril</h2>
Les modèles de chasse, il y en a plein et sont liés aux biotopes
La chasse aux sangliers dépend de leur densité -> actualisation du modèle qui ne va plus se baser sur un seuil, mais sur une proportion : + il y a de sangliers, + il y a de chasse pour une battue, et + il y aura de sangliers tués.

<h2>Appel Bruno Giaminardi (Directeur Fédération des chasseurs du Var) : bruno.giaminardi@gdf83.com</h2>

Le parc national de port cros a sa propre structure, on est sur des prélèvements hors cadre :

à l’intérieur du parc national de port cros, il y a 3 îles :
- porquerolles : la chasse est autorisée, elle est encadrée avec une convention, organisée avec une société de chasse, c’est l’arrêté préfectoral qui s’applique (arrếté de 1986), elle est régit par des règles qui amènent une forme d’étique dans le cadre du prélèvement des animaux (par exemple la chasse de nuit, lunette thermique n’est pas autorisée).
- sur port cros et l’ile du levant : regime de « destruction » qui est régit par un autre cadre et sous la responsabilité du Prefet, et ici tout est permis, l’objectif est de détruire, de retirer les animaux qui posent problème. On ne regarde plus ni la période, ni le jour/nuit, ni les moyens.

Grosse nuance entre chasse classique et regime de destruction

Y a eu une grande prolifération sur le continent depuis 5 ans environ, en venant par la mer, en se faisant emporter par le courant.
1ère ile colonisée : porquerolles (+ proche du continent), les sociétés de chasses ont géré l’espèce, et l’ont fait se développer et s’est peuplée à Port Cros, là où cependant il n’y a pas de société de chasse (zone coeur du parc), c’est là qu’intervient la DDTM qui organise avec le bras armé du prefet (« lieutenants de louveterie »), c’est eux qui remplacent sur le terrain le prefet.
Ils interviennent dans le cadre de certaines espèces protégées (le loup par exemple), quand les animaux à préveler sont dans des endroits où il est difficile de pratiquer la chasse (zone urbaines) et sur les espèces qui peuvent être chassables, si elles provoquent des dégats le prefet a la possibilité de lancer des prélèvements sur celles ci.

Sangliers : l’impact, notamment sur des espèces protégées d’importances fortes ont amené le prefet à réagir, pas par la chasse car il n’y a pas de société de chasse mais par ces lieutenants et avec les agents du parc qui tentent de les piéger (sans trop de succès car les sangliers sont malins, 1 ou 2 peuvent se faire piéger mais les prochains ne tomberont pas dans le panneau)

Dans l’organisation d’execution, c’est comme une organisation de chasse : des gens sont postés à des endroits stratégiques avec des chiens pour aider à les prélever + facilement.

Espèce protégée impactée par les sangliers :
- petit pingouins dans le secteur
- toutes les espèces d’oiseaux (dites marines) qui font des nids à terre, les sangliers ont un odorat très développé qui ratisse tout sur son passage

LES OPERATIONS DE DESTRUCTION SONT REALISES SOUS L’ORDRE DU PREFET QUI AMENE SES BRAS ARMES QUAND UN IMPACT TROP IMPORTANT DES SANGLIERS EST REALISE SUR DES ESPECES
C’EST PAS EN LIEN AVEC LEUR DENSITE EN PREMIER LIEU (après par la suite, évidement en très grand nombre, ils finissent par dégrader le milieu de vie de toute manière)

il est connu qu’il y a des échanges entre les différentes îles, donc il est important que les société de chasse de porquerolle, que les battues à port cros soient bien menées pour enrayer le phénomène.

Ce qu’il reste à voir :
la quantification des chiffres, du nombre de prélèvement depuis plusieurs années (DDTM)
côté environemental : impact que ça a et pourquoi finalement dans ce parc national (zone sanctuaire, coeur du parc), on est tout de même obligé d’intervenir et de chasser


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

    
    
    
    
    
  </p>
</body>

</html>
