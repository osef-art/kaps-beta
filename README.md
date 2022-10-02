# KAPS. 💊

[TÉLÉCHARGER LE JEU](https://github.com/osef-art/play-kaps/raw/main/KAPS.apk)
📥👈🏾

yo, c'est adam.  
très fier de pouvoir vous montrer mon tout premier **jeu mobile** *"KAPS"*, que
j'ai codé et dessiné de A à Z avec [Unity](https://unity.com/). j'ai commencé à
taffer dessus fin juin 2022, depuis j'ai pas arrêté de poncer le truc, 7j/7,
comme si les gens allaient le télécharger tsais 🤡

**j'explique le principe:** c'est un jeu à la *'Dr. Mario'* pour ceux qui ont la
ref.pour ceux qui voient pas, disons que ça ressemble un peu à Tetris. des
pilules 💊 vont tomber dans une grille truffée de microbes 👾. le but est de
faire des combinaisons (des *matchs*) de la même couleur pour virer tous les
microbes de la grille façon Pfizer. ✨  
ça a l'air assez chill dit comme ça. sauf que les pilules **accélèrent** ⏳ au
fur et à mesure, les grilles deviennent de plus en plus **chargées** en
microbes, y'en a qui vont commencer à avoir des **pouvoir spéciaux** 💥, sans
parler des **sidekicks** 🤝 qui t'aideront à travers les niveaux et qui eux
aussi possèdent chacun leur propre **pouvoir** 🧪, je te cache pas que le
résultat est assez fun. bourré de bugs, mais fun.

[clip]

⚠ il s'agit d'une **version bêta** du jeu, c'est à dire qu'il y a pas mal de
trucs qui manquent, de trucs qui buggent un peu, de trucs temporaires qui vont
être remplacés par des truc mieux, du coup soyez pas surpris si parfois y'a des
comportements bizarres. 😬  
*(ah oui et ceux qui sont sur iOS.... bon au moins vous avez la santé* 🤡)

bon il est probable que je parle beaucoup, du coup je te propose un petit menu
avec toutes les infos sur le jeu dont j'aimerais faire part. clique sur celle(s)
qui t'intéresse

[📱 EH COMMENT ON TÉLÉCHARGE LE JEU ??](#lancer-le-jeu-)  
[🎮 EH COMMENT ON JOUE ??????](#comment-jouer-)  
[📜 EH C'EST QUOI LES RÈGLES (j'arrête)](#rgles-du-jeu-)  
~  
[🚨 DERNIÈRES UPDATES](#updates-)  
[👨🏾‍💻 CE SUR QUOI JE TAF EN CE MOMENT](#devlog-)  
[🎯 LES IDÉES / OBJECTIFS SUR CE PROJET](#objectifs-)  
[💀 BUGS CONNUS (donc venez pas me harceler)](#bugs-)  
~  
[🤝 LES SIDEKICKS](#sidekicks-)  
[👾 LES MICROBES](#microbes-)  
[💊 PILULES SPÉCIALES](#glules-spciales-)

## LANCER LE JEU 📱

Si tu es sur Android, clique vite
👉🏾 [ICI](https://github.com/osef-art/play-kaps/raw/main/KAPS.apk) 👈🏾 !!
Ca va direct télécharger une `.apk` te permettant d'installer le jeu sur ton
tel.  
Si tu es sur iPhone, tu pourras toujours regarder tes potes sur Android s'amuser
🙏🏾  
Si tu es sur un ordi, j'ai aucune idée de ce que tu fous là.

## COMMENT JOUER 🎮

*(si tu n'as pas lu l'intro ou [les règles](#rgles-du-jeu-), il est possible que
tu ne comprennes pas grand chose je t'avoue* 💀)  
Pour **bouger** les pilules, sélectionne-les avec ton doigt et déplace-les
librement dans la grille.  
Tu peux aussi les déplacer depuis n'importe quel endroit de l'écran avec le **
joystick**. Tu peux déplacer la pilule vers la **gauche** ⬅, la **droite** ➡, et
le bas ⬇.  
Pour faire **pivoter** une pilule, **tape** 👆 dessus, ou sur n'importe quel
endroit de l'écran.  
💨 MOVE STYLÉ: tu peux **swipe vers le bas** pour faire **tomber** la pilule
super vite. Ca rapporte des points supplémentaires donc hésite pas. 😏

Si le joystick ou le swipe te gênent, tu peux les désactiver à tout moment dans
les **paramètres**. Tu peux même changer le sens dans lequel tourne la pilule
par défaut. Si ça c'est pas magnifique.

Très important aussi, quand tu combines des pilules et qu'elles se cassent, tu
peux aussi bouger les
**fragments** des pilules. C'est un peu compliqué parce qu'elles sont assez
rapides, mais c'est archi rentable.

## RÈGLES DU JEU 📜

*(je vais bientôt rajouter un **tuto** dans le jeu détaillant tout ce que je
vais raconter ici, mais lis quand même on sait jamais.)*

Chaque niveau est une **grille** dont certaines cases sont occupées par des **
microbes** colorés.  
Au fur et à mesure, des **pilules** colorées vont tomber dans la grille et
s'empiler. Le gameplay consiste à réaliser des **combinaisons** de **4 objets**
de la **même couleur** pour détruire ces 4 objets. On appelle ça un **match-4**
. (on appelle pas du tout ça un match4 mais c'est moins long à écrire)

Quand les microbes se retrouvent dans des *matchs*, ils sont **éradiqués**. Le
niveau est complété lorsqu'on a viré **tous les microbes** de la grille.
J'aurais peut-être du appeler le jeu Astrazenekaps. Attends je l'ai dit à voix
haute ?

Le jeu aurait pu s'arrêter là, mais j'ai rajouté pas mal de **mécaniques**
rendant le concept plus
**challengeant** (je hais ce mot):

- Les [**MICROBES**](#microbes-) 👾 vont développer des **pouvoirs spéciaux**,
  y'en a qui pourront se **multiplient**, d'autres**supriment** des pilules de
  la grille, certains nécessiteront **plusieurs coups** pour être éradiqués.
  Plus il y aura de microbes spéciaux, plus il deviendra nécessaire d'élaborer
  des petites **stratégies**
  pour compléter un niveau, genre supprimer tels microbes en priorité, ne pas
  poser de pilules à proximité de certains, etc. Mais la vraie **force** du jeu
  réside dans une mécanique bien plus intéressante:
- Les [**SIDEKICKS**](#sidekciks) 🤝. Ce sont des *'principes actifs'* qui
  pourront t'aider en cours de partie. Chaque sidekick a sa propre **
  compétence**, qui pourra être déclenchée **plusieurs fois** pendant le
  niveau.  
  Certains **éradiquent** des microbes, d'autres suppriment des **lignes**,
  des **colonnes**
  et autres **motifs**, certains génèrent des **pilules spéciales**, etc. On
  peut en choisir jusqu'à
  **2** par partie, et certaines équipes possèdent une **synergie** unique.  
  Chaque sidekick possède une **jauge de mana**, vide au début de la partie.
  Lorsqu'<u>un objet de la couleur du sidekick</u> est détruit, il **remplit**
  sa jauge de 1. Quand la jauge est pleine, le sidekick est **prêt**, et sa
  compétence peut être **déclenchée** par le joueur. ⚡ La jauge se vide à chaque
  utilisation de la compétence.  
  Certains sidekicks sont **passifs** 🤖 et se déclenchent **automatiquement**
  après un certain nombre de
  **tours**.

❌ La partie est perdue quand la pile de pilules atteint <u>le haut de la
grille</u>.  
Attention, le jeu devient de plus en plus **rapide** au fur et à mesure de la
partie.

#### MÉCANIQUES AVANCÉES 🧠

- 📥 Le bouton **"HOLD"** sert à **conserver** une capsule dans l'inventaire
  pour pouvoir la
  **ressortir** au moment venu. Elle est échangée avec celle déjà présente dans
  la grille. Il y a des chances que la mécanique devienne payante, plus j'y
  réfléchit et plus je la trouve ultra cheatée.
- 🎊 Lorsque qu'une pilule se sépare ou tombe, on peut **la bouger** ou **bouger
  ses fragments** afin de les déposer ailleurs.  
  Ca peut être très utile pour perpétuer un combo ou juste réaménager la grille.
- 📛 On a vu qu'on pouvait swipe vers le bas pour faire **tomber** une pilule.  
  Ce move génère des **points supplémentaires** et a une faible chance de
  libérer de la **mana**.
- 🎆 Réaliser des ***match-5***, des ***match-6*** ou + génère de la mana et des
  points supplémentaires.  
  Aussi, ces *matchs* font plus de **dégâts** aux microbes qui ont une barre de
  vie.
- 🌡 Enchaîner plusieurs *matchs* d'affilée démarre un **combo**.  
  Plus il est élevé, plus il a de chances de générer de la mana supplémentaires
  à chaque match.
- ⏹ Il est possible de *matcher* des lignes et des colonnes, mais aussi des **
  carrés 3x3**.  
  C'est très chaud à réaliser, mais encore une fois, c'est particulièrement **
  récompensant** en terme de mana, de dégâts et de score.

---

# UPDATES 🚨

*(bientôt!)*

## DEVLOG 👨🏾‍💻

*(bientôt!)*

## OBJECTIFS 🎯

*(bientôt!)*

### BUGS 💀

*(bon ça pas besoin d'attendre)*

---

## SIDEKICKS 🤜‍🤛

| Nom | | Mana | Dégâts | Pouvoir |  
|---:|:---:|:---:|:---:|:---|   
| (✨nouv.!) **SHADOW**   | ![ SHADOW ](../Assets/Resources/Sprites/Sidekicks/shadow0.png "Shadow")     | 10 tours | 1 | Enlève toutes les gélules de sa propre couleur de la grille
| **SLICER**              | ![  JIM   ](../Assets/Resources/Sprites/Sidekicks/slicer1.png "Jim")        | 20       | 1 | Découpe un élément, et tous les autres sur la même ligne
| **SHOCKWAVE**           | ![  SEAN  ](../Assets/Resources/Sprites/Sidekicks/shockwave1.png "Sean")    | 20       | 2 | Frappe un élément, puis les cases adjacentes
| **BUTCHER**             | ![ ZYRAME ](../Assets/Resources/Sprites/Sidekicks/butcher1.png "Zyrame")    | 20       | 2 | Découpe deux bactéries aux hasard
| **PAINTER**             | ![ PAINT  ](../Assets/Resources/Sprites/Sidekicks/painter1.png "Paint")     | 10       |   | Repeins 8 gélules de la grille au hasard
| **UNI**                 | ![ COLOR  ](../Assets/Resources/Sprites/Sidekicks/uni1.png "Color")         | 4 tours  |   | Génère une gélules avec deux couleurs identiques
| (✨nouv.!) **CUTTER**   | ![ CUTTER ](../Assets/Resources/Sprites/Sidekicks/cutter0.png "Cutter")     | 18       | 2     | Découpe deux segments de 3 cases, verticaux et horizontaux
| **MIMAPS**              | ![ MIMAPS ](../Assets/Resources/Sprites/Sidekicks/mimaps0.png "Mimaps")     | 15       | 2 | Brûle 3 éléments de la grille au hasard
| **BOMBER**              | ![ BOMBER ](../Assets/Resources/Sprites/Sidekicks/bomber0.png "Bomber")     | 13 tours | 1 | Génère une gélules explosive
| (✨nouv.!) **SAMURAI**  | ![SAMURAI ](../Assets/Resources/Sprites/Sidekicks/samurai0.png "Samurai")   | 15       | 1 | Découpe une diagonale, dans un sens au pif
| **SNIPER**              | ![ SNIPER ](../Assets/Resources/Sprites/Sidekicks/sniper0.png "Sniper")     | 15       | 3 | Tire sur la bactérie qui a le plus de vie
| **MOSES**               | ![  RED   ](../Assets/Resources/Sprites/Sidekicks/moses0.png "Red")         | 25       | 2 | Découpe toute une colonne au hasard
| **MARKSMAN**            | ![ XERETH ](../Assets/Resources/Sprites/Sidekicks/marksman0.png "Xereth")   | 25       | 1 | Découpe deux diagonales
| (✨nouv.!) **SHUFFLER** | ![SHUFFLER](../Assets/Resources/Sprites/Sidekicks/shuffler0.png "Shuffler") | 8        |   | Repeint TOUTE la grille avec des couleurs au pif
| (✨nouv.!) **CROSS**    | ![ CROSS  ](../Assets/Resources/Sprites/Sidekicks/cross0.png "Cross")       | 12       |   | Peins un "+" autour de l'objet le plus entouré
| **???** | *(Coming soon !)* | 12       |   | Freeze définitivement une bactérie avec un cooldown
| **???** | *(Coming soon !)* | 15       | 3 | Frappe 4 cases au hasard dans la partie basse de la grille

## MICROBES 🦠

| Nom | | Cooldown | Pouvoir |  
|---:|:---:|:---:|:---|   
| **BASIC** | ![BASIC](../Assets/Resources/Sprites/Gridobj/skin14/germs/basic/idle_0.png "Basic") | - | "ah gros on est là hein"
| **WALL**  | ![WALL ](../Assets/Resources/Sprites/Gridobj/skin15/germs/wall/level4/idle_0.png "Wall")  | - | A besoin de plusieurs coups (4 max.) pour être détruit
| **VIRUS** | ![VIRUS](../Assets/Resources/Sprites/Gridobj/skin16/germs/virus/idle_0.png "Virus") | 8 | Transforme une gélule de la grille au hasard en virus
| **SPIKE** | ![SPIKE](../Assets/Resources/Sprites/Gridobj/skin4/germs/thorn/idle_0.png "Spike") | 5 | Détruit une gélule adjacente au hasard
| **???**   | *(Coming soon !)* | 6 | Peut soigner un WALL (de 1PV), ou transformer une bactérie BASIC en WALL
| **???**   | *(Coming soon !)* | 6 | Échange de place avec la gélule la plus proche
| **???**   | *(Coming soon !)* | 6 | Change sa propre couleur. comme ça.
| **???**   | *(Coming soon !)* | 10 | Émet de la fumée devant un élément, masquant sa couleur. (peut être dissipé au contact, ou si l'émetteur est détruit)
| **???**   | *(Coming soon !)* | - | Protège une bactérie, et doit être détruit pour que la bactérie devienne atteignable.
| **???**   | *(Coming soon !)* | - | Pareil qu'au dessus, mais fais en sorte de masquer la couleur de la bactérie protégée.

## GÉLULES SPÉCIALES ✨💊

| Nom | | Effet |  
|---:|:---:|:---|   
| **EXPLOSIVE** | ![EXPLOSIVE](../Assets/Resources/Sprites/Gridobj/skin7/caps/bomb/unlinked.png "Explosive") | Explose quand elle est détruite, brûlant toutes les cases autour
| **JOKER**     | *(Coming soon !)* | Peut être matchée avec n'importe quelle autre couleur
| **???**       | ? | (Coming soon !)

---
