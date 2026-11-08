## 1. Objectif du système

Les artefacts sont des objets magiques qui apportent des effets particuliers aux personnages ou à l'équipe pendant une run. Ils constituent un système de personnalisation permettant de varier les stratégies et les synergies d'une run à l'autre.

Le système repose sur trois principes :

- **Découverte :** trouver des artefacts dans le donjon.
- **Déblocage permanent :** sacrifier un artefact dans une salle spéciale pour l'ajouter définitivement au contenu disponible.
- **Préparation :** sélectionner des artefacts débloqués au hub avant de commencer une run, dans la limite des emplacements disponibles.

Les règles générales sont décrites dans cette fiche. La liste des artefacts et leurs effets détaillés se trouvent dans le codex dédié.

## 2. Raretés

Chaque artefact possède une rareté qui indique son niveau de puissance général et sa valeur potentielle pour une stratégie.

Les raretés prévues sont :

|Rareté|Principe général|
|---|---|
|Commune|Effet relativement simple ou spécialisé.|
|Peu commune|Effet plus intéressant ou possibilités de synergie supplémentaires.|
|Rare|Effet puissant pouvant influencer les choix du groupe.|
|Épique|Effet très puissant ou synergie particulièrement marquée.|
|Légendaire|Effet exceptionnel pouvant transformer une stratégie ou une partie de la run.|

La rareté doit servir de référence pour concevoir et équilibrer les artefacts, mais elle ne signifie pas que tous les artefacts d'une même catégorie auront exactement la même puissance.

Les probabilités d'apparition de chaque rareté et leur éventuelle évolution avec la progression dans le donjon seront définies dans les règles de génération du butin.

## 3. Obtention pendant une run

Les artefacts peuvent être obtenus au cours de l'exploration du donjon, selon les récompenses prévues par les salles et le système de butin.

Un artefact obtenu pendant une run peut être utilisé conformément à son effet. Son acquisition ne signifie pas nécessairement qu'il est débloqué de façon permanente.

Les artefacts non débloqués peuvent notamment servir à débloquer leur propre fiche en étant sacrifiés dans une salle spéciale.

Un même artefact ne peut être obtenu qu'en un seul exemplaire au cours d'une même run. Il peut toutefois réapparaître lors de runs ultérieures.

## 4. Déblocage permanent

Le déblocage permanent des artefacts ne s'effectue pas par un achat au hub.

Pour débloquer un artefact, les joueurs doivent trouver une **salle spéciale permettant de sacrifier un artefact** pendant une run.

Lorsqu'un artefact est sacrifié dans cette salle :

1. L'artefact sacrifié est consommé.
2. L'artefact correspondant est débloqué définitivement.
3. Il rejoint le catalogue des artefacts disponibles pour les runs suivantes.

Le déblocage permanent permet de sélectionner l'artefact au départ d'une future run ou de le retrouver dans le butin, sous réserve des règles de génération et des emplacements disponibles.

Cette mécanique fait de la découverte des artefacts un objectif à long terme : les joueurs doivent explorer le donjon et décider si un artefact vaut davantage par son utilisation immédiate ou par son sacrifice pour enrichir définitivement leur collection.

## 5. Artefacts de départ

Avant chaque run, les joueurs peuvent sélectionner des artefacts parmi ceux déjà débloqués.

Les artefacts de départ sont **partagés à l'échelle de l'équipe** : le nombre d'emplacements disponibles correspond à un budget collectif d'artefacts, et non à un nombre d'emplacements accordés individuellement à chaque personnage.

Le nombre d'emplacements de départ peut être augmenté grâce aux améliorations permanentes du hub. Les coûts et paliers de cette amélioration sont définis dans la fiche de progression permanente.

Les artefacts sélectionnés au départ sont exclus du butin potentiel de la run concernée. Cela évite de retrouver pendant la même run un artefact déjà choisi au départ.

Les artefacts débloqués mais non sélectionnés au départ restent éligibles au butin. Les règles limitant à un exemplaire chaque artefact par run continuent de s'appliquer.

## 6. Principes d'équilibrage

Le système d'artefacts doit encourager la diversité des stratégies sans rendre une combinaison unique systématiquement supérieure aux autres.

Les principes suivants guident leur conception :

- Les artefacts doivent proposer des effets suffisamment distincts pour favoriser différentes approches.
- La rareté doit fournir une indication cohérente de leur puissance générale.
- Les artefacts de départ doivent offrir un choix stratégique sans supprimer l'intérêt de l'exploration.
- Le sacrifice doit constituer un véritable compromis entre l'utilisation immédiate d'un artefact et son déblocage permanent.
- Les artefacts doivent être évalués en fonction de leurs synergies avec les classes, les personnages, les passifs et les autres artefacts.

Les probabilités d'apparition, la puissance des effets et la fréquence des salles de sacrifice restent des paramètres à tester et à ajuster.

## Probabilités d'obtention

Chaque salle de combat ordinaire effectue un unique tirage pour déterminer le résultat concernant les artefacts. Le résultat peut être l'absence d'artefact ou l'obtention d'un artefact de l'une des cinq raretés.

Les probabilités dépendent de l'étage et de la difficulté du combat.

### Probabilités de référence

**Étage 1**

|Résultat|Facile|Moyen|Difficile|
|---|---|---|---|
|Aucun artefact|60 %|50 %|40 %|
|Commun|30 %|32 %|32 %|
|Peu commun|9 %|14 %|20 %|
|Rare|0,9 %|3,5 %|6 %|
|Épique|0,09 %|0,45 %|1,8 %|
|Légendaire|0,01 %|0,05 %|0,2 %|
|**Total**|**100 %**|**100 %**|**100 %**|

**Étage 10**

|Résultat|Facile|Moyen|Difficile|
|---|---|---|---|
|Aucun artefact|20 %|12 %|5 %|
|Commun|25 %|22 %|15 %|
|Peu commun|25 %|25 %|25 %|
|Rare|18 %|23 %|27 %|
|Épique|9 %|13 %|18 %|
|Légendaire|3 %|5 %|10 %|
|**Total**|**100 %**|**100 %**|**100 %**|

### Progression entre les étages

Les probabilités évoluent linéairement entre l'étage 1 et l'étage 10.

Pour chaque résultat et chaque difficulté, la probabilité d'un étage intermédiaire est calculée selon la formule :

`P(F) = P(1) + ((F - 1) / 9) × (P(10) - P(1))`

- `F` : étage concerné.
- `P(1)` : probabilité correspondante à l'étage 1.
- `P(10)` : probabilité correspondante à l'étage 10.

Les calculs utilisent les valeurs non arrondies afin de conserver un total de 100 %.

Aucune rareté n'est inaccessible, quel que soit l'étage. Un artefact légendaire peut donc être obtenu dès le premier étage, même si sa probabilité est extrêmement faible.

## 7. Codex des artefacts

La liste détaillée des artefacts disponibles est regroupée dans une fiche dédiée :

- [[Codex des artefacts]] : catalogue des artefacts, classés par rareté, avec leur description, leurs effets et leurs éventuelles conditions particulières.

Cette séparation permet de conserver une fiche de règles concise tout en facilitant l'ajout, la modification et l'équilibrage des artefacts.