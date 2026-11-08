## 1. Objectifs économiques

L'économie d'INFERNITY repose sur une monnaie permanente : les **pièces infernales (PI)**.

Les pièces infernales permettent d'acheter les améliorations permanentes du hub. Elles sont conservées à la fin d'une run, même si celle-ci se termine par un échec.

Le système économique doit répondre à quatre objectifs :

- Récompenser la progression dans le donjon et l'accomplissement des quêtes.
- Permettre d'acheter régulièrement des améliorations, notamment au début de l'aventure.
- Créer des choix entre plusieurs améliorations intéressantes, plutôt que permettre de tout acheter immédiatement.
- Éviter que les joueurs soient obligés de répéter indéfiniment des salles faciles pour progresser.

Les valeurs de cette fiche constituent une première base d'équilibrage. Elles pourront être ajustées après plusieurs runs de test.

## 2. Règles générales

- Les pièces infernales sont une ressource collective appartenant à l'équipe.
- Elles sont conservées entre les runs.
- Les améliorations permanentes sont achetées au hub.
- Une amélioration achetée reste acquise définitivement.
- Les niveaux, les récompenses de combat et les autres ressources temporaires ne deviennent pas permanents simplement parce qu'ils ont été obtenus pendant une run.
- Les récompenses en pièces infernales sont attribuées à la fin de la run, en fonction de la progression et des objectifs accomplis.

## 3. Sources de pièces infernales

Les pièces infernales proviennent principalement de deux sources :

1. La progression dans le donjon.
2. Les quêtes collectives.

Ces deux sources récompensent des comportements complémentaires : avancer dans le donjon et remplir des objectifs spécifiques.

### 3.1. Récompense de progression

À la fin d'une run, l'équipe reçoit une récompense liée à sa progression dans le donjon.

La formule de base est :

`PI de progression = 15 × (F - 1) + S`

Avec :

- `F` : numéro du dernier étage atteint.
- `S` : numéro de la dernière salle terminée sur cet étage, de 1 à 10.

Une salle est considérée comme terminée lorsque son contenu a été résolu. Le simple fait d'y entrer ne suffit pas.

|Progression atteinte|Pièces infernales|
|---|---|
|Étage 1, salle 1|1 PI|
|Étage 1, salle 6|6 PI|
|Étage 1, salle 10|10 PI|
|Étage 2, salle 1|16 PI|
|Étage 2, salle 10|25 PI|
|Étage 3, salle 2|32 PI|
|Étage 3, salle 10|40 PI|
|Étage 4, salle 10|55 PI|
|Étage 5, salle 10|70 PI|

Cette formule valorise la progression vers les étages les plus profonds. Elle garantit également qu'une run qui échoue tôt rapporte tout de même quelques pièces infernales.

#### Cas particuliers

**Téléporteur**

Lorsqu'une run commence à un étage avancé grâce au téléporteur, la récompense de progression est calculée à partir de la position réellement atteinte, selon la formule générale.

Les salles ignorées ne donnent pas de récompense individuelle. Les récompenses de fin d'étage déjà acquises grâce aux boss vaincus restent applicables, conformément aux règles du téléporteur.

**Raccourcis**

Les raccourcis achetés pendant une run ne donnent pas de récompense pour les salles ignorées. La progression en pièces infernales est calculée à partir de la position réellement atteinte.

### 3.2. Récompenses des quêtes collectives

Les quêtes collectives constituent la deuxième source principale de pièces infernales.

Chaque quête possède un niveau de difficulté qui détermine sa récompense. Les pièces sont accordées une seule fois lorsque les conditions de réussite sont remplies.

|Difficulté de la quête|Récompense|
|---|---|
|Facile|5 PI|
|Moyenne|10 PI|
|Difficile|15 PI|

Les quêtes doivent encourager des choix et des comportements différents : explorer certaines salles, vaincre des adversaires, découvrir des informations ou accomplir des objectifs particuliers.

Leur récompense doit être suffisamment intéressante pour influencer les décisions de l'équipe, sans devenir la seule manière rentable de jouer.

Les conditions exactes de réussite et la génération des quêtes seront détaillées dans [[Quêtes]].

#### Relance de quête

Une relance permet de remplacer une quête proposée au début de la run par une nouvelle quête aléatoire.

La relance ne garantit pas une quête plus facile ni une récompense supérieure. Elle permet simplement de remplacer un objectif peu adapté aux intentions de l'équipe.

Les utilisations disponibles dépendent des améliorations permanentes achetées au hub.

### 3.3. Exemple de gains sur une run

Une équipe atteint l'étage 3, salle 6, et termine deux quêtes moyennes ainsi qu'une quête difficile.

- Progression : `15 × (3 - 1) + 6 = 36 PI`
- Deux quêtes moyennes : `2 × 10 = 20 PI`
- Une quête difficile : `15 PI`

**Total gagné : 71 PI.**

Les pièces infernales sont ajoutées au total permanent de l'équipe à la fin de la run.

## 4. Principes de tarification

Le prix d'une amélioration dépend de son impact sur les runs futures.

Trois catégories sont distinguées :

- **Améliorations accessibles :** petits gains réguliers, coût relativement faible.
- **Améliorations structurantes :** changements significatifs dans la préparation ou les possibilités de l'équipe.
- **Améliorations majeures :** avantages puissants ou progression vers des étages avancés, coût élevé.

Les coûts augmentent progressivement lorsque plusieurs améliorations d'une même catégorie sont achetées. Cette hausse doit limiter l'accumulation excessive d'avantages permanents, sans bloquer la progression.

Les prix sont collectifs : une équipe dépense ses pièces infernales pour améliorer son potentiel commun.

## 5. Coût des améliorations permanentes

### 5.1. Niveau de départ

Chaque achat augmente d'un niveau le niveau de départ des personnages pour les prochaines runs.

|Niveau de départ obtenu|Coût de l'amélioration|
|---|---|
|Niveau 2|35 PI|
|Niveau 3|60 PI|
|Niveau 4|90 PI|
|Niveau 5|130 PI|
|Niveau 6|175 PI|
|Niveau 7|225 PI|

Le coût correspond à l'achat du niveau indiqué, et non au coût cumulé depuis le niveau 1.

Le niveau 1 reste le niveau de départ initial. Les coûts augmentent progressivement, car les niveaux supplémentaires procurent un avantage significatif sur les combats.

Le niveau maximal éventuel reste à définir.

### 5.2. Bonus permanent d'expérience

Le bonus permanent comporte cinq paliers. Chaque achat augmente le bonus débloqué de +1 XP, jusqu'à +5 XP.

|Palier|Bonus permanent total|Coût|
|---|---|---|
|1|+1 XP|20 PI|
|2|+2 XP|30 PI|
|3|+3 XP|40 PI|
|4|+4 XP|55 PI|
|5|+5 XP|70 PI|

Les coûts sont ceux de chaque palier successif.

Le bonus effectivement appliqué reste limité à la moitié de l'expérience normale du combat, arrondie à l'entier inférieur.

`Bonus appliqué = min(bonus permanent débloqué, plancher(XP normale / 2))`

L'expérience normale inclut le modificateur lié à l'étage, mais exclut le bonus permanent.

### 5.3. Emplacements d'artefacts de départ

Les emplacements d'artefacts sont partagés par toute l'équipe.

Les artefacts doivent avoir été débloqués de manière permanente en les sacrifiant dans une salle spéciale du donjon. Ils ne sont pas achetés directement au hub.

|Emplacement supplémentaire obtenu|Coût|
|---|---|
|1er emplacement supplémentaire|30 PI|
|2e emplacement supplémentaire|50 PI|
|3e emplacement supplémentaire|75 PI|
|4e emplacement supplémentaire|105 PI|
|5e emplacement supplémentaire|140 PI|

Chaque achat augmente d'un emplacement le nombre total d'artefacts que l'équipe peut emporter au départ.

Aucun plafond définitif n'est fixé. Les coûts croissants servent de limite économique souple.

### 5.4. Budget de passifs de départ

Le budget de passifs détermine la valeur totale de passifs que l'équipe peut sélectionner avant une run.

Les coûts en points restent définis par rareté :

|Rareté|Coût en points|
|---|---|
|Commun|1|
|Peu commun|2|
|Rare|3|
|Épique|4|
|Légendaire|5|

Le budget initial est fixé à **3 points**.

Chaque amélioration augmente ce budget d'un point.

|Budget obtenu|Coût|
|---|---|
|4 points|20 PI|
|5 points|30 PI|
|6 points|45 PI|
|7 points|60 PI|
|8 points|80 PI|
|9 points|105 PI|
|10 points|130 PI|

Le budget est commun à l'équipe. Il s'applique aux passifs sélectionnés avant le départ, et non automatiquement aux récompenses temporaires obtenues après les combats de boss.

Un passif doit d'abord être découvert en run avant de pouvoir être acheté définitivement au hub. Le coût d'achat d'un passif découvert dépend de sa rareté :

|Rareté|Coût de déblocage permanent|
|---|---|
|Commun|10 PI|
|Peu commun|20 PI|
|Rare|35 PI|
|Épique|55 PI|
|Légendaire|80 PI|

L'achat rend le passif disponible pour les préparations futures, mais ne remplace pas le budget nécessaire pour l'équiper au départ.

### 5.5. Potions de soin

L'équipement de départ reste celui prévu par D&D 5e 2024. Le hub ne propose pas de réserve d'expédition ni de lots d'équipement.

Les seules améliorations permanentes liées à l'équipement concernent la quantité et la qualité des potions de soin emportées au départ.

#### Amélioration de la quantité

|Niveau|Potions de soin supplémentaires au départ|Coût|
|---|---|---|
|1|+1 potion|25 PI|
|2|+2 potions au total|40 PI|
|3|+3 potions au total|60 PI|
|4|+4 potions au total|85 PI|

Chaque palier remplace le précédent : les quantités indiquées sont le total supplémentaire accordé au départ, et non un bonus cumulatif entre les paliers.

#### Amélioration de la qualité

|Niveau|Qualité des potions de départ|Coût|
|---|---|---|
|1|Potions de soin normales|Inclus dans le départ initial|
|2|Potions de soins supérieurs|45 PI|
|3|Potions de soins suprêmes|80 PI|

La quantité et la qualité sont deux pistes indépendantes. Les joueurs peuvent donc choisir de transporter davantage de potions normales ou un nombre plus limité de potions plus puissantes.

Les quantités exactes, les dés de soin et les modalités de distribution entre les personnages seront précisés dans [[Équipement]].

Les potions sont consommées normalement pendant la run et ne sont pas automatiquement remplacées après utilisation.

### 5.6. Relances de quêtes

Chaque palier augmente d'une unité le nombre de relances de quêtes disponibles par run.

|Relances disponibles par run|Coût|
|---|---|
|1|15 PI|
|2|25 PI|
|3|40 PI|
|4|60 PI|
|5|85 PI|

Les utilisations sont restaurées au début de chaque nouvelle run.

### 5.7. Relances de butin

Chaque palier augmente d'une unité le nombre de relances de coffres disponibles par run.

|Relances disponibles par run|Coût|
|---|---|
|1|20 PI|
|2|35 PI|
|3|55 PI|
|4|80 PI|
|5|110 PI|

Une relance remplace le résultat du coffre par un nouveau résultat. L'équipe ne conserve pas le meilleur des deux tirages.

### 5.8. Relances de choix de passifs de boss

Chaque palier augmente d'une unité le nombre de relances de choix de passifs disponibles par run.

|Relances disponibles par run|Coût|
|---|---|
|1|35 PI|
|2|55 PI|
|3|80 PI|
|4|110 PI|
|5|145 PI|

Une relance remplace les trois options proposées, mais conserve la rareté déterminée initialement. Elle ne permet donc pas de relancer la rareté elle-même.

Cette catégorie est plus coûteuse, car elle permet de modifier un choix de récompense important après la défaite d'un boss.

### 5.9. Téléporteur

Le téléporteur doit d'abord être découvert pendant une run. Son amélioration permanente permet ensuite de commencer à un étage déjà terminé, à condition que le boss de cet étage ait été vaincu.

|Départ maximal autorisé|Coût|
|---|---|
|Étage 2|40 PI|
|Étage 3|65 PI|
|Étage 4|95 PI|
|Étage 5|130 PI|
|Étage 6|170 PI|
|Étage 7|215 PI|

Chaque palier augmente l'étage maximal accessible au départ. L'équipe ne peut jamais dépasser son record de progression en matière d'étages entièrement terminés.

Les récompenses de fin des étages ignorés restent acquises, mais les récompenses propres aux salles ignorées ne sont pas obtenues.

### 5.10. Amélioration des compagnons

Les compagnons sont découverts ou recrutés pendant une run. Ils ne sont pas achetés directement au hub.

Une fois un compagnon découvert, son installation ou son camp peut être amélioré de façon permanente pour renforcer ses capacités utilitaires.

|Niveau d'amélioration du compagnon|Coût|
|---|---|
|Niveau 1|25 PI|
|Niveau 2|50 PI|
|Niveau 3|85 PI|
|Niveau 4|125 PI|
|Niveau 5|175 PI|

Ces coûts constituent une base commune. Les effets exacts de chaque niveau dépendront du compagnon et seront détaillés dans [[Compagnons]].

L'équipe ne peut toujours emmener qu'un seul compagnon par run.

## 6. Priorités économiques et rythme de progression

Les coûts sont conçus pour permettre une première amélioration après une run courte ou moyenne, puis plusieurs choix d'investissement au fil des expéditions.

Les améliorations accessibles, comme le premier bonus d'XP ou une première relance, doivent être atteignables rapidement. Les améliorations structurantes, comme les niveaux de départ ou les emplacements d'artefacts supplémentaires, demandent davantage d'investissement.

Les joueurs ne sont pas censés acheter toutes les améliorations dans un ordre imposé. Ils doivent pouvoir privilégier :

- La puissance immédiate, grâce au niveau de départ.
- La régularité des runs, grâce aux potions de soin et aux relances.
- La diversité des stratégies, grâce aux artefacts et aux passifs.
- L'accès plus rapide aux étages avancés, grâce au téléporteur.
- Les capacités utilitaires des compagnons.

L'économie doit soutenir plusieurs styles de progression viables.