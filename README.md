# albedo.github.io
 **ALBEDO**
 Membres du projet :
 - Louis
 - Asmar
 - Kairui



Notre projet:

L'albedo terrestre

Descriptif du projet :

Notre étude se porte sur l'albedo et l'augmenté de celle-ci en fonction de la température et inversement, on va définir l'albedo comme la réflexion des surfaces, et on va se demander si l'albedo a un impact sur l’environnement et si elle est a un impact comment cet impact peut-elle infecté la vie qu'on mènera dans le futur.

Questions qu'on peut se poser par rapport à notre sujet:

Avec un thème aussi vaste, on peut se demander si la température a-t-elle un réel impact sur les surfaces de la planète ? On peut aussi se demander si on n'applique pas les recommandations du GIEC, comment la température va-t-elle augmentée. Puis si notre température moyen était de 14 degrée Celcius telle qui l'est actuellement, comment la situation peut-elle évoluée. Enfin on peut se demander si tout ceci n'est pas en faite relier à un effet boule de neige qui impact notre environnement et notre futur si on n'applique pas les recommandations du GIEC.

Description de notre modèle:

Tout d'abord, nous avons initialisé la proportion et l'albedo de différentes surface de la planète al_ice étant la moyenne de l'albedo de la neige tassée, fraîche et de la glace et al_others une estimation de la moyenne de l'albedo des autres surfaces de la planète. ini_world est une fonction qui initialise une liste représantant un monde (ici la planète Terre), lui donnant comme élément les différentes proportions de surface spécifié au début du programme. Puis La fonction albedo_wd renvoie l'albedo moyen du monde mis en paramètre (la Terre à un albedo moyen de 0.3). equi_temp renvoie la température d'équilibre en Kelvin d'une planète selon son albedo, donc nous avons créé une fonction permettant de convertir la température mis en paramètre de Kelvin à Celcius. Ensuite nous avons créé une fonction qui modifie la proportion de glace et d'eau dans notre monde en fonction de la température. On considère qu'un appel à cet fonction équivaut à une année passé dans le monde. Enfin, nous avons La fonction étude enregistre et affiches les différentes modifications réalisé dans le monde dans un intervalle de n années à partir d'une température initiale choisie (température d'équilibre par défaut).

Descritpion des résultats:

 On a fait une l'étude a été initilisé à -19°C (température d'équilibre). On peut voire qu'au court de ces années la température s'est réduite, causant une augmentation importante de la proportion de glace dans la planète. Cette augmentation fait monter l'albedo d'environ 7%. Pour la la température initialisé à 14°C (environ la température moyenne atuelle de la planète). On remarque que ces données montre des résultats contraire par rapport à l'étude précédente. On voit par exemple qu'au bout de 50 ans, la température augmente de 50°C (Ces études ne prennent pas en compte l'effet de serre) réduisant notablement la proportion de glace et augmenatant celle de l'océan. On voit que cela réduit l'albedo moyen jusqu'à 0.275 à la fin de cette période(graphique dans le fichier ipynb). Ensuite on a initialisé la température à 20°C. Malgré la similarité avec les résultats précedents on peut voir que l'augmentation de température est plus important (allant jusqu'à presque 24°C) et que dans ce cas-là on perds 10% de glace à chaque décennie.



Problèmes rencontrés:

On a rencontré plusieurs problèmes lors de la mise en oeuvre de notre étude, car on a rencontré des difficultés pour les utilisé les formules qu'on a trouvé lors de notre recherche documentaire, elle était très complexe et très dur à utlisé, par conséquent on a décide de simplifier les formules en utlisant des formules générales telle que la formule de la température d'équilibre, pour l'Océa on a voulu faire une fonction qui permetait de calculer la surface terestre et celle de l'Océan en fonction de la taille de l'Océan. Il y aussi le fait que le sujet soit très vaste et est très compliqué à étudier, car il y a beaucoup de paramètres on peut prendre par exemple les marées, car avec la marées basse il y a moins de surface d'eau donc moins d'albedo; on peut prendre aussi le cas de la nuit où il y a peu d'albedo sur un côté de la terre et sur l'autre les rayons sont renvoyés. On peut ainsi dire que les problèmes rencontrés ont été énorme et que notre étude a été simplifié pour le faire et pour le montrer plus facilement.

Conclusion:

Ainsi on remarque une certaine corrélation entre l'albedo et la température, comme on a pu le voir plus l'albedo est élevé plus la température diminue et la glace augmente, cependant lorsque la température est haute on remarque que l'Océan augmente et l'albedo diminue, dans notre modèle on a décide le modélisé ainsi mais si on voulait faire un projet plus complet on aurait une fonction saison qui va calculer la température en fonction des saisons ce qui manque à notre modèle mais on peut voir déjà avec notre modèle que si on ne fait rien, les glaciers vont fondre et il y aura plus d'eau. On a rencontré énormément de problème, mais on a su se diriger vers un objectif assez simple qui est de montrer que notre étude simplifier montre que d'après du GIEC la température moyenne va causer un changement climatique, il y aura moins de glacier et il y aura plus de surface d'eau et moins de surface terestre. Pour conclure on remarque que notre sujet qui était vu comme vaste et en faite relié et qu'il y a un effet boule de neige sur le réchauffement climatique, donc on peut se demander si agir maintenant pourra-t-il changer l'impact que nous avons fait dans 1000 ans et est-ce que dans le futur il y aura une énergie naturelle non polluante qui va permettre à l'humanité à un stade imaginable ?



Semaine 10 mars :
- Définition détaillée de la problématique : Comment la température peut-elle évoluer en fonction de l'albedo et pk c'est un effet rétroactif?
- Recherche documentaire sur les modèles existants :
  - ref 1 : https://doi.org/10.1215/22011919-9320266 source bien mais court.
  - ref 2 : https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2014RG000449 (bonne source) mais moins bien que la 3.
  - ref 3 : https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2007GL031480  (formule)(bonne source) albedo.github.io albedo.github.io albedo.github.io

semaine du 17 mars:
- liens :
  - https://www.sciencedirect.com/topics/earth-and-planetary-sciences/albedo
  - https://www-sciencedirect-com.accesdistant.sorbonne-universite.fr/topics/earth-and-planetary-sciences/interfacial-energy
  - https://reader.elsevier.com/reader/sd/pii/B9780124095489103719?token=ED1EBD3BAE3E1BA50BFC8195BF8326E4C3BCCEA7FD1F99C1AEEA14D3C57203ECCA64AF90E488A754D8EBD6F73408210E&originRegion=eu-west-1&originCreation=20230317082452
  - https://curry.eas.gatech.edu/Courses/6140/ency/Chapter9/Ency_Atmos/Reflectance_Albedo_Surface.pdf

- idéeeeees du programme: 
  - création d'un monde(environnement) de taille 3\*3;
  - initialisation du monde avec full -1;
  - la fonction aura pour paramètres des surfaces, 3 pour l'instant;
  - on changera a surface du monde par les surfaces qu'on aura mis en paramètres, exemple :
     - glace = 1,
     - eau = 2,
     - surface à faible albdeo = 3;
  - création d'une nouvelle fonction qui modifie le monde en fonction de l'albedo et de la chaleur(paramètres : monde, fonction albedo,...);
  - on a commencé le programme et créer le monde.

semaine du 25 mars :
- https://www-sciencedirect-com.accesdistant.sorbonne-universite.fr/science/article/pii/B9780080454054006030
- https://tc.copernicus.org/articles/14/1651/2020/

- on a trouvé la formule pour la chaleur;
- on a trouvé un article qui prouve que le Soleil c'est chaud et ça fait sécher ou fondre la glace. 

semaine du 31 mars:
- On a fini notre carnet de bord, on reprend le programme qu'on a laissé en standby et puis on a trouvé un artcile intéréssant qui parlait de la symétrie de l'albedo terrestre.
-Pour le programme on compte utiliser les formules trouvé puis faire des graphiques au début, puis on a une idée de comment créer la fonction de la température pour étudier la conséquence de celle ci et l'effet boule de neige. 

semaine du 7 avril:

- On a changé tout ce qu'on avait fait avant, on a changé les paramètres et les données de base.
- On reprend notre programme, au lieu de faire un monde en 3D on a décidé d'opter pour un monde linéaire, car créer un monde en 3D n'affecte pas notre sujet et la recherche qu'on va faire.
- On a décidé de faire un tableau de dimension 1 avec les tailles surface au lieu de le représenter par un chiffre, car nous allons faire une fonction reflet qui va calculer l'albedo de notre monde, et donc on va utiliser les pourcentages de surface de la Terre c'est-à-dire qu'on va prendre 70 unités d'eau 10 unité de glace et 20 unités d'autres albédo moins fort. Au total il y aura 100 unités pour le monde. (Mais on peut faire des tests avec 80 unités de surface de glace, on pourra s'intéresser au autre cas pour observer comment juste changer les unités d'une surface peut changer le monde (effet boule de neige))
- Ensuite après avoir fait cette fonction nous avons commencé la fonction température qui permet de calculer la température du monde avec une température de base, puis elle va permettre aussi de calculer le réchauffement de la terre et si température trop haute fonte des glaces et réchauffement de l'eau avec l'augmentation du pH (mais cela n'est pas notre étude). Quand la glace va fondre l'eau va augmenter d'une unité par unité de glace fondu et à partir de 5 unités d'eau augmenté, la surface others sera réduit de 1 et on augmentera l'eau de 1.
- On a une idée de créer la fonction 'fonte' on ne connaît pas encore le nom, qui va se consacrer à faire chauffer ou réduire la température qui va permettre de soit faire fondre la glace ou d'augmenter la surface de glace.
- On va ensuite créer une fonction moyenne température qui permettre de renouveler la température de base de notre monde et puis on peut faire une boucle à l'intérieur de cette fonction qui va permettre de calculer la température au bout de x temps (qu'on va mettre en paramètre).
- on s'est arrêté à la fonction température.

semaine du 14 avril:

- On reprend où on s'est arrêté, on essaye de finir la fonction température (on va mettre en paramètre le température moyenne avant de lancer la fonction, puis le monde, et le nombre de jours) On va utiliser la formule de la température equilibre. On a créer une fonction temp_equilibre qui va être la fonction qui sera utilisé pour la fonction température pour nous aider à calculer la température. 
- fonction qui convertie les K en C, car la température d'équilibre est en K.
- fonction ice_level qui va calculer la glace qui va soit faire fondre la glace soit glacer l'océan. On va faire a fait que à 0 degré Celcius la glace ne fond pas, sinon elle augmente si la température est négatif si elle est positif, on augmente ou diminue la glace de 0.05*temp et de même pour l'eau sauf que pour celle ci on la rend opposé à la glace, c'est-à-dire si la glace fond l'Océan est augmenté sinon l'Océan diminue et la glace augmente.
- on a ensuite fait une fonction pour calculer le niveau de l'océan qui va être codé comme ceci on va garder la fonction en haut et on va faire rajouter le fait que lorsqu'on atteint 5 unité d'eau supplémentaire, on va diminuer la surface others de 1 et l'eau va augmenté de 1 en rapport à la montée de l'Océan qui prend petit à petit les surfaces.
- Puis on a fait une fonction year qui calcule une année de cela
- Enfin on a fini par la fonction Étude qui va calculer les surfaces et la température en fonction des années qu'on met en paramètres
- On a fini notre diapo et on commence à rédiger le texte pour le rapport.
