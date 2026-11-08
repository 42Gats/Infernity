## 1. Principe général

La progression des personnages dans INFERNITY se divise en deux catégories :

- **Progression temporaire :** les niveaux et la puissance acquis pendant une run. Ils disparaissent à la fin de celle-ci.
- **Progression permanente :** les améliorations débloquées entre les runs. Elles permettent de renforcer les départs futurs et d'élargir les possibilités offertes aux joueurs.

La progression temporaire récompense les réussites au cours d'une run. La progression permanente valorise les ressources et les découvertes accumulées sur plusieurs tentatives.

## 2. Niveau de départ

Le niveau auquel les personnages commencent une run dépend des améliorations permanentes débloquées dans le hub.

Sans amélioration particulière, le niveau de départ est le niveau 1.

Une amélioration permanente peut permettre de commencer les runs suivantes à un niveau supérieur. Ce niveau de départ est déterminé avant le début de la run et s'applique à l'ensemble des personnages concernés.

Les modalités et le coût de ces améliorations sont définis dans [[Progression permanente]] et [[Économie et récompenses]].

## 3. Gain d'expérience

Les personnages gagnent de l'expérience en remportant des combats.

L'expérience dépend de deux facteurs :

- La difficulté de la rencontre.
- L'étage où se déroule le combat.

### Expérience de base

|Difficulté du combat|XP de base|
|---|---|
|Facile|1 XP|
|Moyen|2 XP|
|Difficile|3 XP|
|Boss|5 XP|

### Modificateur d'étage

L'expérience gagnée augmente avec le numéro de l'étage.

**Formule de prototype :**

`XP gagnée = XP de base + numéro de l'étage - 1`

Exemples :

| Rencontre                    | XP gagnée |
| ---------------------------- | --------- |
| Combat facile à l'étage 1    | 1 XP      |
| Combat moyen à l'étage 1     | 2 XP      |
| Combat difficile à l'étage 1 | 3 XP      |
| Boss de l'étage 1            | 5 XP      |
| Combat difficile à l'étage 3 | 5 XP      |
| Boss de l'étage 3            | 7 XP      |

Ces valeurs constituent une première base d'équilibrage. Elles pourront être ajustées selon la durée des runs, la fréquence des combats et la vitesse de montée en niveau souhaitée.

## 4. Montée de niveau

Les personnages accumulent de l'expérience jusqu'à atteindre le seuil nécessaire au niveau suivant.

Le seuil dépend du niveau actuel du personnage.

**Formule de prototype :**

`XP nécessaire = niveau actuel × 5`

|Passage de niveau|XP nécessaires|
|---|---|
|Niveau 1 → 2|5 XP|
|Niveau 2 → 3|10 XP|
|Niveau 3 → 4|15 XP|
|Niveau 4 → 5|20 XP|
|Niveau 5 → 6|25 XP|

Lorsqu'un personnage atteint le seuil requis, il monte immédiatement de niveau et applique les règles de progression de D&D 5e édition 2024, adaptées si nécessaire au format d'INFERNITY.

Le niveau atteint augmente le seuil nécessaire pour la prochaine montée de niveau.

## 5. Conservation de l'expérience excédentaire

L'expérience excédentaire est conservée après une montée de niveau.

Exemple : un personnage de niveau 2 possède 8 XP sur les 10 nécessaires pour atteindre le niveau 3. Il gagne 5 XP après un combat.

- Son total atteint 13 XP.
- Il dépense 10 XP pour passer au niveau 3.
- Il conserve 3 XP pour progresser vers le niveau 4.

Cette règle évite de perdre l'expérience acquise lorsqu'un gain dépasse le seuil nécessaire.

## 6. Répartition de l'expérience

Après la victoire d'un combat, tous les personnages du groupe reçoivent la même quantité d'expérience.

Cette règle s'applique également aux personnages gravement blessés, même s'ils n'ont pas pu participer au combat.

L'expérience récompense ainsi la progression collective plutôt que la participation individuelle à chaque rencontre.

Par défaut, les salles non combattantes ne donnent pas d'expérience. Elles peuvent toutefois fournir d'autres récompenses, comme de l'or, des artefacts, des informations ou des effets persistants.

## 7. Effets de la montée de niveau

La montée de niveau suit les règles de D&D 5e édition 2024, sous réserve d'adaptations nécessaires au format du jeu.

Elle peut notamment permettre d'obtenir :

- Des points de vie supplémentaires.
- De nouvelles capacités de classe.
- Des améliorations de caractéristiques ou des dons.
- Une progression des sorts et des ressources de classe.
## 8. Fin de run et réinitialisation

Les niveaux acquis pendant une run sont temporaires.

À la fin d'une run, les personnages perdent leur progression temporaire et retrouvent le niveau de départ déterminé par les améliorations permanentes du groupe.

L'expérience accumulée pendant la run n'est pas conservée pour la suivante.

Les améliorations permanentes, les déblocages et les connaissances acquises par les joueurs ne sont pas concernés par cette réinitialisation.

## 9. Limites de progression

Le niveau maximal théorique d'un personnage est le niveau 20, conformément à D&D 5e édition 2024.

Toutefois, le système d'INFERNITY n'est pas conçu pour que les personnages atteignent nécessairement ce niveau au cours d'une run ordinaire.

La vitesse de progression dépend notamment :

- Du nombre de combats rencontrés.
- De la difficulté des rencontres.
- Du numéro de l'étage.
- Des raccourcis empruntés.
- Du niveau de départ débloqué dans le hub.

Ces paramètres devront être évalués ensemble afin que la progression reste significative sans rendre les premiers étages insignifiants.

## 10. Principes de conception

Le système de progression doit respecter les principes suivants :

- **Récompense :** les combats victorieux contribuent directement à la progression.
- **Lisibilité :** les seuils d'expérience sont simples à calculer.
- **Progression croissante :** les étages avancés offrent davantage d'expérience.
- **Équité :** tous les personnages du groupe reçoivent la même expérience.
- **Réinitialisation :** les niveaux temporaires disparaissent à la fin de la run.
- **Continuité :** les améliorations permanentes rendent les futures tentatives différentes.
- **Équilibrage :** les valeurs d'expérience restent ajustables après les premiers tests.

## Liens associés

- [[Structure d'une run]]
- [[Exploration par nœuds]]
- [[Mort et recommencement]]
- [[Progression permanente]]
- [[Économie et récompenses]]