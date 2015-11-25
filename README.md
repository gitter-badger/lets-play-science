﻿lets-play-science, à la recherche de la sagesse des foules
----------------------------------------------------------

**Un petit repo** pour agréger les suggestions sur l'épisode 3 de **Lets Play Science** !  
**C'est un document collaboratif** où chacun peut intégrer sa proposition de manière organisée.
- Ce n'est **pas** un projet de développement ( [pas pour l'instant du moins, mais vous pouvez tous soumettre des idées](#IV) )  

**Problématique** :  **"Comment collaborer à 5000 cerveaux sur la même question ?".**  
- Les commentaires les plus pertinents ne sont pas forcément les plus likés
- Aller à la recherche des commentaires pertinents est une tâche laborieuse!
- Cette *navigation en eaux troubles* limite la circulation des idées, et cause de nombreux doublons

Pourquoi github?
----------------------------------------------------------
Au même titre qu'un wiki, cette application permet de faire des **révisions avec validation [des responsables](https://github.com/sveinburne/lets-play-science/issues/1)** d'un document collaboratif.
- L'idée est que chacun puisse éditer ce document en apportant des propositions (commentaires youtube) qui n'on pas encore été référencées dans la synthèse. Se rendre à la section [I. Participer](#I).
- Pour suivre le projet et être notifié des mises à jour et interventions sur [le forum associé](https://github.com/sveinburne/lets-play-science/issues), cliquez sur le bouton ![Watch](img/watch.png) en haut à droite.
- **Pour ne voir que les ajouts récents, et pas se refarcir tout le document à chaque fois**, faites un tour [du côté des *commits*](https://github.com/sveinburne/lets-play-science/commits/master)

Sommaire
----------------------------------------------------------

I. [Participer](#I)
  1.  [Ouvrir une issue](#I.1)
  2.  [Faire une requête](#I.2)

II. [Synthèse des commentaires Youtube](#II)
  1. [Espace de discussion (60% des propositions)](#II.1)
  2. [Espace Q&A / sondage (20%)](#II.2)
  3. [Espace d'écriture collaborative (15%)](#II.3)
  4. [Espace de T'chat (5%)](#II.4)

III. [Agrégation des propositions de fonctionnalités pour une plateforme collaborative](#III)
  1. [Espace de discussion (commentaires, forum...)](#III.1)
    1. [Un choix entre différents types de likes](#III.1.1)
    2. [Une forme de modération](#III.1.2)
    3. [Une association sémantique des posts](#III.1.3)
    4. [La possibilité de marquer un post comme "évalué"](#III.1.4)
    5. [Une interface qui favorise l'évaluation entre pairs](#III.1.5)
    6. [L'édition collaborative des posts](#III.1.6)
    7. [L'organisation une comunauté qui prémache le filtrage](#III.1.7)
  2. [Espace Q&A](#III.2)
  3. [Espace d'écriture collaborative](#III.3)

IV. [On est des fous et on code le truc open source!](#IV)  

<a name="I"></a>
## I. Participer
**Pour faire une proposition d'édition**, deux options

<a name="I.1"></a>
#### 1. Ouvrir une issue
- [Créez un compte github](https://github.com/join)
- Ouvrez une issue avec **le point concerné** (ex [II.2.b] : influence sur l'algorithme de tri), en vous rendant [à cette adresse](https://github.com/sveinburne/lets-play-science/issues) puis en cliquant sur ![New Issue](img/new_issue.png)

<a name="I.2"></a>
#### 2. Faire une requête

- [Créez un compte github](https://github.com/join)
- Sélectionnez le fichier [README.md](README.md)
- appuyez sur ![le symbole en forme de stylo *edit*](img/edit.png)
- faites vos modifications
- en bas de la page, section **Propose file change** :
  - renseignez une phrase qui décrit la modification
  - appuyez sur ![Propose file change](img/propose.png)
- Une *Pull Request* apparait alors [dans le forum](https://github.com/sveinburne/lets-play-science/pulls?utf8=%E2%9C%93&q=is%3Apr+) et **les gens peuvent commenter cette proposition**
- L'[équipe de validation](https://github.com/sveinburne/lets-play-science/issues/1) confirme l'édition.

**Si vous ne savez pas écrire en markdown, c'est un language de mise en forme très simple, [on l'apprend en cinq minutes](http://www.remarq.io/articles/five-minutes-to-markdown-mastery/)**  

<a name="help"></a>
**Si d'autres veulent me prêter la main pour la validation, [laissez un message ici](https://github.com/sveinburne/lets-play-science/issues/1)!**



<a name="II"></a>
## II. Synthèse des commentaires Youtube

<a name="II.1"></a>
### 1. Espace de discussion (60% des propositions)

#### 1.1 Forum souverain (75% des propositions du 1.)

Beaucoup partent du constat que les fonctionnalités offertes par le système de commentaires Youtube est bien trop limité, ne serait-ce que par rapport à un forum classique.

**Fonctionnalités qui reviennent le plus souvent :**
  1. Hashtags sur les posts, les fils
  2. Structuration du forum par défi / sous-défi / etc. (+ parfois mind mapping)
  3. Votes par catégorie
  4. Former un groupe de modos / contributeurs "reconnus"

**Plateformes existantes évoquées** : Reddit (très souvent), Discourse.

#### 1.2 Commentaires Youtube (25%)

**Ceux qui se "contenteraient" de Youtube, proposent le plus souvent :**
  1. De noter les commentaires (en réponse aux commentaires)
  2. De structurer l'arborescence de commentaires (par type de message : réaction à la vidéo ou réflexion sur le défi suivant, par défi/sous-défi...)
  3. De faire de l'analyse syntaxique pour dégager les principaux mots clés, tendances

<a name="II.2"></a>
### 2. Espace Q&A / sondage (20% des propositions)

**Fonctionnalité particulière souvent proposée :**
* Eviter l'effet "mouton" en masquant les votes, en ordonnant aléatoirement les propositions (pendant un temps limité ou non), etc.

**Outils existants évoqués** (par ordre de fréquence décroissante) : StackOverflow/StackExchange, Quora, république-numérique.fr, jepolitique.fr, laprimaire.org, projet "Reboot la France", Tricider, straw poll divers

Permettrait à moindre coût de faire ressortir facilement les grandes tendances se dégageant d'un groupe d'individus.

Des comparaisons reviennent souvent avec des citoyens votant aux élections, des neurones / groupes de neurones "collaborant".

Proposition qui revient souvent chez des personnes qui se présentent comme informaticiens / développeurs.

<a name="II.3"></a>
### 3. Espace d'écriture collaborative (15%)

Ce qui ressort de la plupart de ces propositions, serait qu'un groupe d'internautes motivé ferait le travail de synthèse des commentaires Youtube sur une plateforme d'écriture collaborative.

Dans une moindre mesure, l'idée de faire collaborer les internautes directement sur l'espace d'écriture a également été exprimée.

**Outils existants évoqués** : Wikipedia/Wikis, authorea.com, GoogleDoc, workflowy

<a name="II.4"></a>
### 4. Espace de T'Chat (5%)

Propositions de participants qui utilisent régulièrement IRC ou Twitch.




<a name="III"></a>
## III. Agrégation des propositions de fonctionnalités pour une plateforme collaborative

**Un nombre très majoritaire de contributeurs s'accordent sur la nécessité de déplacer la discussion sur une plateforme 'augmentée' qui améliorerait de façon drastique la circulation des idées et favoriserait l'évaluation des propositions peu exposées**

**[Voter pour les outils et fonctionnalités générales prioritaires](http://www.tricider.com/brainstorming/2vvPwC7VeKt)** [(lien admin)](https://www.tricider.com/admin/2vvPwC7VeKt/2wRDRxsHv8f)

<a name="III.1"></a>
#### 1. Espace de discussion (commentaires, forum...)

**[Voter pour les fonctionnalités prioritaires pour l'espace de discussion](http://www.tricider.com/brainstorming/34O75F4FgG7)** [(lien admin)](https://www.tricider.com/admin/34O75F4FgG7/CN8kK1IcbOt)

<a name="III.1.1"></a>
##### 1. Un choix entre différents types de likes pour les posts
*proposé par [koukaloukaki](https://www.youtube.com/user/koukaloukaki)*  

L'idée est de faire du filtrage collaboratif en catégorisant subjectivement l'intérêt

- pouce vert ça veut dire "bonne blague"
- pouce bleu ça veut dire "pas con"
- pouce rouge ça veut dire "nul" ou "spam"

... + d'autres catégories éventuellement, cf :
- l'intervention de [Gaspard Garry-Gendre](https://www.youtube.com/channel/UCYEMyvlHvpJcYypXJZzF9zA)
> "troll" "pas con" "petit breton" "brillant" "genie ou stupide ?" "big up" "hater" "critique" "eloge" "random"

- l'intervention de [bebertii](https://www.youtube.com/user/bebertii)
> - first, content, pas content, utile, futile

Ainsi on peut basculer entre différentes vues suivant notre approche, "érudite" ou "détente" !

<a name="III.1.2"></a>
##### 2. Une forme de modération
*proposé par une vaste majorité*  

- **a** Gestion du trolling et des contenus sans valeur ajoutée
- **b** Influence sur l'algorithme de tri. Un modérateur peut marquer
  - houleux (il ne sera plus favorisé dans l'algorithme de tri)
  - exceptionnel (il sera mis en avant dans l'algorithme de tri)

**Remarque** Certains comme [PhilocrateV](https://www.youtube.com/user/PhilocrateV) émettent des réserves à la **2.b**, qui favorisait un "système de castes". Je trouve au contraire que le droit de modérer est acquis par mérite, par les contributeurs qui s'investissent le plus.

<a name="III.1.3"></a>
##### 3. Une association sémantique des posts

**[Voter pour les différentes options](http://www.tricider.com/brainstorming/2wLfQJ6DBuN)** [(lien admin)](https://www.tricider.com/admin/2wLfQJ6DBuN/20cLRM1Jdav)

*proposé par [Gaspard Garry-Gendre](https://www.youtube.com/channel/UCYEMyvlHvpJcYypXJZzF9zA),
 [bebertii](https://www.youtube.com/user/bebertii), [Panda Terroriste](https://www.youtube.com/channel/UCOSyst_PWE8-gwCxQmZBoUw), et d'autres...!*  
- **a** Par des `#hashtags` : Permet de filtrer rapidement le contenu, et d'avoir un accès facile aux posts relatifs
  - [Panda Terroriste](https://www.youtube.com/channel/UCOSyst_PWE8-gwCxQmZBoUw) suggère qu'on devrait avoir accès à tous les hashtags en cours pour éviter une profusion de tags sémantiquement proches.

*proposé par [Seki Onudric](https://www.youtube.com/channel/UCJhOnkpjRbdL04tkfr46JhA)*
- **b** Via une structure d'arbre :

>Le système de commentaire / mail / hashtag / etc c'est bien pour une conversation. Pas pour organiser des idées.
Organiser les idées sous une forme d'arbre permettrait d'accroître la finesse de chaque argument. Puisqu'ainsi, chaque personne peut voir facilement et lisiblement la liste des arguments et entrer dans chaque branche pour apporter sa pierre à l'édifice.
Comment transporter l'humanité dans l'espace ?  
├── Ascenceurs spatiaux  
│   ├── Ascenseur  
│   ├── Skyhook  
│   └── …  
├── Propulsion  
│   ├── Capsules à explosions nucléaire  
│   ├── Fusées  
│   │   ├── Explosion  
│   │   ├── Hydrogène  
│   │   └── …  
│   └── …  
└── …  

*proposé par [Jules Randolph](https://www.youtube.com/user/theswanted)*
- **c** Fusion de **a** et **b** : un hashtag avec domaine de noms, séparés par des `:`
  - Exemple : `#Ascenceurs Spaciaux:Skyhook`


*[proposé par Fjellfrass ](https://www.youtube.com/user/Fjellfrass), [ Sebastien Huet](https://www.youtube.com/user/huetse), [heyhoo yoo](https://www.youtube.com/channel/UCfKFZIdjzeti_fbmDH4uIvg)*
- **d** Par une analyse syntaxique des posts (computationnellement très couteux !)

*[proposé par fsamin ](https://github.com/fsamin)*
- **e** Par l'organisation des posts sous la forme d'un carte mentale i.e. [mind-mapping](https://fr.wikipedia.org/wiki/Carte_heuristique). Pour permettre au modérateur d'organiser, regrouper et visualier les contributions.
![CC BY-SA 3.0 Graham Burnett](https://upload.wikimedia.org/wikipedia/commons/4/42/Mindmap.gif)

*proposé par [Monnet Julien](https://github.com/Roxtarmy)*
- **f** Extension de **b**. Au moment de valider son commentaire, on peut choisir si on **pour** ou **contre** (ou bien **neutre** par défaut) vis-à-vis de l'hypothèse à laquelle on répond : si je commente dans la section *Propulsion* pour dire que ça ne marchera jamais, je me rangerais du coté **contre**.
Le but à terme est de voir instantanément les commentaires qui ont des arguements favorables ou défavorables au sein de chaque catégorie. L'affichage serait semblable à une discussion sms : les commentaires **pour** l'hypothèse de la propulsion alignés à gauche, et ceux **contre** à droite (et les **neutre** au milieu).
On pourrait également proposer un filtre sur ce nouveau critère.

<a name="III.1.4"></a>
##### 4. La possibilité de marquer un post comme "évalué"
*proposé par [Jules Randolph](https://github.com/sveinburne/)*  
Extension de la proposition **3** :
Si on a ni liké, ni jugé le contenu extraordinaire, ni merdique, on peut le marquer comme **"évalué"**, cf la proposition **5.a**. L'objectif est de favoriser la navigation entre ce qui a été lu / pas lu.

<a name="III.1.5"></a>
##### 5. Une interface qui favorise l'évaluation entre pairs

**[Voter pour les différentes options](http://www.tricider.com/brainstorming/3QOMxjuDJBZ)** [(lien admin)](https://www.tricider.com/admin/3QOMxjuDJBZ/3mqN5RRaZa7)

*Inspiré de la proposition de [koukaloukaki](https://www.youtube.com/user/koukaloukaki), proposé par [Jules Randolph](https://www.youtube.com/user/theswanted)*  
- **a** Proposer à l'utilisateur un mode "évalutation" ou son travail est d'évaluer des posts qu'il n'a pas encore évalué. Grosso modo, ça lui permet de s'y retrouver facilement !  
Dans ce mode, **seuls les contenus non marqués (comme "vu", "pas con", "spam" ou "drôle") seront visibles**.  

*Proposé par [Yrtiop](https://www.youtube.com/user/Yrtiop)*
- **b** Provoquer la sérendipité et limiter le copinage en obligeant les gens à commenter (évaluer) des solutions tirées au hasard

*Proposé par [Takator LK](https://www.youtube.com/channel/UCKFNN9-FFfaN53BQc_ZF5Mw)*
- **c** Obliger l'évaluation d'autres propositions avant de publier la sienne. Bien évidemment, cette obligation ne s'applique pas aux premiers posts.

<h6 name="#clusters" id="#clusters"></h6>
*Insipiré de la proposition de [Takator LK](https://www.youtube.com/channel/UCKFNN9-FFfaN53BQc_ZF5Mw), proposé par [Jules Randolph](https://www.youtube.com/user/theswanted)*
- **d** En accord avec **a**, **b** et **c**, et en référence à la **sagesse des foules**, créer des "clusters" d'évaluateurs, ou comment créer des posts collaboratifs de qualité. Bon c'est un peu barré ce machin :
  - Vocabulaire :
    - **post** : une réponse directe au problème posé, distinct des
     **commentaires**
    - **cluster** : un groupe restreint de contributeurs participants à un **run**
    - **run** : phase d'évaluation collective
    - **commentaire** : un commentaire à un **post**
  - Dans chaque cluster, une équipe réduite de, par exemple, 50 personnes interagit, sans visibilité directe sur les autres clusters. **Ça permet à chacun d'avoir une quantité limitée d'évaluations à réaliser.**
  - Celà présuppose un processus itératif et séquentiel de l'évaluation :
    - **Phase de pre run** : On propose un lien aux collaborateurs qui veulent s'inscrire dans le **run**
      - Les inscrits *peuvent* commencer à rédiger des posts, mais ils ne sont pas visibles pour les autres, à moins d'être sémantiquement proches (cf **3.c**)! L'auteur doit proposer au moins 3 tags / post
      - Les inscrits ont accès à l'arbre de tags (cf **3.c**)
    - **Phase de run** sur X jours : des clusters (groupes) **isolés** les uns des autres élaborent des posts. L'isolation n'est pas stricte car **les posts sémantiquement proches (cf 3) sont visibles entre clusters et peuvent être fusionnés (cf 6.b).**. De plus, **les hashtag avec nom de domaine (3.c) sont visibles de tous.**
    Ainsi les clusters fusionnent progressivement les idées redondantes, et créent des révisions (cf **6.b**). Pendant ce temps, l'équipe de modération se charge d'éditer l'arbre de tags pour le rendre cohérent. Elle s'assure aussi que des clusters avec une trop grande proportion de gens inactifs fusionnent. Le **run** tourne jusqu'à ce qu'une des trois conditions soient vérifiée :
      - le jour X (échéance) est atteint
      - tous les posts ont été évalués par au moins **10** personnes (arbitraire) dans chaque cluster
      - l'équipe de modération décide d'arrêter le run
    - **Phase de publication** :
      - tous les posts sont visibles, mais leur poids est normalisé suivant leur nombre d'évaluations.
      - quiconque peut créer un post, mais **à condition d'avoir soumis au moins 3 évaluations** (cf **b** et **c**). Il a accès à l'arbre de tag, et doit fournir 3 tags à son post!
      - les contributeurs sont incités à évaluer les nouveaux posts
      - les posts sont toujours révisionnables et fusionnables. Seul l'auteur peut autoriser des demandes de fusion / révision
      -  un **run** peut être relancé n'importe quand par l'équipe de modération ou par un vote de volontaires pour trier les nouveaux posts peu visibles (vues < 10 )
  - Le nombre de vues n'a qu'une influence marginale sur l'évaluation de qualité d'un post. On peut imaginer une fonction racine cubique par exemple.
  - Ca reste une structure souple, par exemple on est pas obligé de commencer tout de suite par un pre-run, on peut commencer par une phase de publication vide.



*Proposé par [Jean Baptiste Dallara](https://www.youtube.com/user/a46production)*
- **e** Un peu à la facemash, proposer des paires de propositions et demander à l'évaluateur celle qu'il trouve la plus pertinente.  

<a name="III.1.6"></a>
##### 6. L'édition collaborative des posts
*[proposé par hackedbrain17](https://www.youtube.com/user/hackedbrain17)*  
Avec notamment :
- **a** La proposition **1**
- **b** La possibiliter d'éditer collectivement les propositions (soumettre une édition à l'auteur du post, comme sur github^^)

**6.b** aussi proposé par [luffyetgaara](https://www.youtube.com/user/luffyetgaara)

<a name="III.1.7"></a>
##### **7** L'organisation une comunauté qui prémache le filtrage
*proposé par [pistachemolle](https://www.youtube.com/user/pistachemolle) et [cizalto](https://www.youtube.com/user/cizalto)*  
> Peut-être qu'un groupe de personnes plus ou moins en affinité avec la thématique de la question pourrait fouiller au fur et à mesure le fil des réponses et à partir de là éditer et remettre à jour en permanence une sorte de résumé des réponses des spectateurs. En les regroupant et classant par similarité, en prenant en compte leur récurrences et leur pertinence, (et surement plein d'autres facteurs) dans le but d'arriver à un schéma en ramifications. Il s'en dégagerait sûrement des axes principaux avec leur subdivision selon les variantes, et quelques pistes moins denses d'idées plus originales. Ce schéma, cet sorte "d'arbre scénaristique" serait accessible (pas au tout début du sondage bien sûr, après un premier tri) et remis à jour régulièment, ainsi les gens qui souhaitent répondre pourraient déjà voir comment s'organisent les idées autours du sujet et dans quelles branche ranger leur réponse, ou carrément en créer une nouvelle.
- Les premiers à répondre ne bénéficieraient donc pas du classement des réponses et se lanceraient donc un peu à l'aveugle comme actuellement sur les commentaires youtube.
- Cette organisation n'est pas du tout horizontale, voire même carrément pyramidale, et ça me chiffonne un peu (voire déprime carrément) de n'avoir que ça comme idée en tête à proposer comme réponse ! ^_^

<a name="III.2"></a>
#### **2** Espace Q&A

*proposé par [Frosty-Z](https://github.com/Frosty-Z)*

Inspiré de StackOverflow, Yahoo Q&A, Tricider... Où au moins la question principale (défi) serait posée.

Dès qu'il l'estime nécessaire, tout utilisateur pourrait créer une ou plusieurs sous-questions ("sous-défis"), permettant d'affiner les "propositions principales" (par ex. *"Quel est le meilleur système de propulsion pour une fusée ?"*).

<a name="III.3"></a>
#### **3** Espace d'écriture collaborative

*proposé par de nombreux intervenants*

Etherpad, Wiki, Github, "fait maison"...

Permet d'effectuer une synthèse et rassembler des références de manière collaborative sur chaque proposition offrant une réponse (même partielle) au défi.

*proposé par [Frosty-Z](https://github.com/Frosty-Z)*

Dans l'éventualité d'un *espace Q&A*, on peut envisager que chaque proposition (et sous-proposition) soit modifiable de manière collaborative. L'*espace Q&A* et l'*espace d'écriture collaborative* seraient donc confondus.



<a name="IV"></a>
## IV. On est des fous et on code le truc open source!

#### 1. Faire des suggestions sur l'application, pas besoin d'être dev'
*Sans nécessairement voir le projet se lancer, ça peut être une excellente expérience de pensée de se représenter l'application "idéale".*

- Consultez l'ébauche de spécifications : [THE_APP.MD](THE_APP.MD)
- Lisez [ce billet](https://github.com/sveinburne/lets-play-science/issues/11)
- Consulter les issues avec le [`label:enhancement`](https://github.com/sveinburne/lets-play-science/issues?q=label%3Aenhancement)



#### 2. Se signaler comme intéressé pour le developpement

Des développeurs qui ont signalé leur souhait de s'investir (merci de vous rajouter à la main avec votre lien github)

- [Jules Randolph](https://github.com/sveinburne/)
- [Julien Monnet](https://github.com/Roxtarmy)
- [François Samin](https://github.com/fsamin/)
- [Maxime Pacary](https://github.com/Frosty-Z)
- [Thibaud Chominot](https://github.com/Phacocherman/)
- [Aelerinya](https://github.com/Aelerinya)
- [Sylvain Berthaud](https://github.com/akrib/)
