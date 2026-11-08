## 1. Objectif

Chaque étage d'INFERNITY possède un parcours généré de manière procédurale. Celui-ci détermine les salles disponibles à chaque nœud, leurs connexions et les différents chemins possibles jusqu'au boss.

La génération doit produire des parcours variés, tout en respectant une structure commune :

- 10 nœuds de progression par étage.
- Entre 1 et 4 salles par nœud normal.
- Entre 1 et 3 connexions sortantes par salle.
- Chaque salle doit être accessible depuis au moins une salle du nœud précédent.
- Chaque salle doit être reliée à au moins une salle du nœud suivant.
- Toutes les salles du neuvième nœud doivent mener au boss du dixième nœud.

Le parcours est un graphe orienté organisé en couches successives. Les connexions vont toujours d'un nœud vers le nœud immédiatement suivant.

## 2. Structure du graphe

Un parcours est constitué de dix couches appelées nœuds.

Les nœuds 1 à 9 contiennent des salles normales. Le nœud 10 contient une unique salle : celle du boss.

Chaque salle représente un point de passage possible. Les connexions entre les salles déterminent les choix proposés aux joueurs lorsqu'ils terminent une salle.

Une connexion ne peut jamais :

- Revenir vers un nœud précédent.
- Sauter un nœud.
- Relier deux salles appartenant au même nœud.
- Mener à une salle qui ne sera jamais accessible depuis le parcours initial.

La progression est donc toujours orientée vers l'avant.

## 3. Nombre de salles par nœud

Chaque nœud normal contient entre une et quatre salles.

Le nombre de salles ne peut cependant pas être déterminé indépendamment pour chaque nœud : il dépend également des connexions disponibles depuis le nœud précédent.

Chaque salle du nœud précédent peut posséder entre une et trois connexions vers les salles du nœud suivant.

Par conséquent :

- Un nœud contenant une seule salle peut alimenter au maximum trois salles au nœud suivant.
- Un nœud contenant deux salles peut alimenter jusqu'à six connexions.
- Un nœud contenant trois salles peut alimenter jusqu'à neuf connexions.
- Un nœud contenant quatre salles peut alimenter jusqu'à douze connexions.

Le nombre de salles du nœud suivant doit respecter ces possibilités, tout en restant compris entre une et quatre.

Chaque salle du nouveau nœud doit être reliée à au moins une salle du nœud précédent.

## 4. Règles de connexion

Chaque salle normale possède :

- Au moins une connexion entrante depuis une salle du nœud précédent.
- Entre une et trois connexions sortantes vers des salles du nœud suivant.

Plusieurs salles d'un même nœud peuvent être reliées à une même salle du nœud suivant.

Inversement, une salle peut recevoir plusieurs connexions provenant de différentes salles du nœud précédent.

Cette possibilité permet aux parcours de se diviser puis de se rejoindre, créant des embranchements et des chemins alternatifs.

### Exemple

Un nœud contient trois salles : A, B et C.

Le nœud suivant contient quatre salles : D, E, F et G.

Les connexions peuvent être réparties ainsi :

- A → D, E
- B → E, F
- C → F, G

Chaque salle précédente possède entre une et trois sorties, et chaque salle suivante possède au moins une entrée.

Les joueurs qui choisissent A pourront atteindre D ou E, tandis que ceux qui choisissent C pourront atteindre F ou G.

## 5. Génération du parcours

La génération doit respecter les étapes suivantes.

### 5.1. Création du premier nœud

Le premier nœud contient entre une et quatre salles.

Le nombre de salles est déterminé aléatoirement.

Toutes les salles du premier nœud constituent les possibilités initiales proposées aux joueurs.

### 5.2. Génération des nœuds suivants

Pour chaque nœud suivant, le système détermine d'abord le nombre de salles possibles en fonction du nombre de connexions disponibles depuis le nœud précédent.

Le nombre de salles doit respecter les conditions suivantes :

- Il doit être compris entre une et quatre.
- Chaque salle doit recevoir au moins une connexion entrante.
- Chaque salle du nœud précédent doit avoir entre une et trois connexions sortantes.
- Toutes les connexions doivent mener à des salles du nœud immédiatement suivant.

Une fois le nombre de salles déterminé, les connexions sont réparties entre les salles afin de produire un parcours cohérent.

### 5.3. Vérification

Après la génération de chaque nœud, le système vérifie que :

- Aucune salle n'est isolée.
- Toutes les salles sont accessibles depuis le premier nœud.
- Chaque salle possède au moins une sortie vers le nœud suivant.
- Aucune connexion ne saute un nœud.
- Aucun chemin ne revient en arrière.

Si une génération ne respecte pas ces conditions, elle doit être corrigée ou recommencée.

## 6. Génération du nœud de boss

Le dixième nœud contient toujours une seule salle : le boss de l'étage.

Toutes les salles du neuvième nœud doivent posséder une connexion vers cette salle.

La salle du boss constitue donc le point de convergence de tous les chemins possibles de l'étage.

Il n'est pas possible de contourner le boss ou de terminer un étage sans l'affronter.

## 7. Attribution des types de salles

Une fois la structure et les connexions du parcours générées, les types de salles sont attribués aux différentes salles normales.

Les types de salles disponibles et leurs règles de fonctionnement sont définis dans [[Types de salles]].

La répartition doit permettre de varier les expériences d'une run à l'autre et éviter que les joueurs rencontrent systématiquement les mêmes combinaisons de salles.

Les règles précises de fréquence, de rareté et de répartition des types de salles pourront être définies dans la fiche correspondante.

## 8. Visibilité du parcours

Les joueurs ne connaissent pas nécessairement l'intégralité du parcours généré.

Ils voient :

- Les salles directement accessibles depuis leur position actuelle.
- Le type de chacune de ces salles.
- Les connexions visibles entre les salles connues.

Les salles plus éloignées restent inconnues tant qu'elles ne sont pas révélées par la progression normale ou par une capacité particulière.

L'Éclaireur peut étendre cette visibilité en révélant des salles supplémentaires en profondeur, selon le niveau de son camp.

La génération du parcours doit donc conserver les informations nécessaires à son affichage progressif, sans révéler automatiquement l'intégralité du donjon.

## 9. Principes de conception

La génération des parcours doit respecter les principes suivants :

- **Variété :** chaque étage doit proposer des embranchements et des possibilités différentes.
- **Cohérence :** aucune salle ne doit être inaccessible ou isolée.
- **Lisibilité :** les connexions doivent être compréhensibles pour les joueurs.
- **Progression :** tous les chemins doivent avancer vers le boss.
- **Choix significatifs :** les embranchements doivent proposer de véritables alternatives.
- **Équilibre :** la génération ne doit pas systématiquement favoriser un chemin ou une position particulière.
- **Reproductibilité :** une fois généré, le parcours d'un étage reste fixe pendant toute la run.

Les paramètres de génération pourront être ajustés à partir des tests de jeu, notamment le nombre moyen de salles par nœud, la densité des connexions et la fréquence des embranchements qui se rejoignent.