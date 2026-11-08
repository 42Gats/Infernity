## 1. Objectif du système

Les passifs sont des améliorations qui modifient durablement ou temporairement les capacités de l'équipe pendant une run. Ils permettent de construire des synergies, de renforcer certaines stratégies et d'adapter le groupe aux défis rencontrés.

Le système repose sur deux mécanismes complémentaires :

- **Passifs de départ :** sélectionnés avant la run grâce à un budget commun à toute l'équipe.
- **Passifs obtenus pendant la run :** acquis au fil de la progression, notamment lors des transitions entre les étages.

Un passif découvert pendant une run peut également être acheté définitivement avec des pièces infernales afin de pouvoir le sélectionner au début des prochaines runs.

## 2. Raretés

Chaque passif possède une rareté qui représente son niveau de puissance général et détermine son coût dans le budget de départ.

|Rareté|Coût en points|
|---|---|
|Commun|1|
|Peu commun|2|
|Rare|3|
|Épique|4|
|Légendaire|5|

La rareté sert également à déterminer le prix de déblocage permanent et intervient dans la sélection des passifs proposés lors des transitions entre étages.

Les probabilités d'apparition de chaque rareté seront définies ultérieurement.

## 3. Passifs de départ

Avant chaque run, l'équipe sélectionne les passifs qu'elle souhaite emporter. Le budget est **commun à toute l'équipe**, et non individuel.

Le budget de départ est de **3 points**. Chaque passif sélectionné consomme un nombre de points correspondant à sa rareté.

Le budget peut être augmenté de manière permanente au hub grâce aux améliorations suivantes :

|Budget total|Coût en PI|
|---|---|
|3 points|Gratuit, valeur de base|
|4 points|20 PI|
|5 points|30 PI|
|6 points|45 PI|
|7 points|60 PI|
|8 points|80 PI|
|9 points|105 PI|
|10 points|130 PI|

Le budget limite le coût cumulé des passifs sélectionnés. Il ne correspond pas à une limite du nombre de passifs : plusieurs passifs peu coûteux peuvent être combinés tant que le budget le permet.

## 4. Obtention pendant une run

Lorsqu'un boss est vaincu et que l'équipe passe à l'étage suivant, elle choisit **un passif parmi trois propositions de même rareté**.

La rareté des passifs proposés dépend de l'étage atteint : plus l'équipe progresse profondément dans le donjon, plus elle a de chances d'accéder à des passifs rares et puissants. Les probabilités exactes seront définies ultérieurement.

Les passifs obtenus de cette manière s'appliquent pendant la run en cours. Ils ne sont pas automatiquement ajoutés à la collection permanente.

Les règles de sélection et de cumul des effets devront être précisées dans le catalogue des passifs lorsque des interactions particulières le nécessiteront.

## 5. Déblocage permanent

Un passif découvert pendant une run peut être acheté définitivement avec des pièces infernales. Une fois débloqué, il devient disponible pour les sélections de départ des runs suivantes.

| Rareté     | Coût de déblocage |
| ---------- | ----------------- |
| Commun     | 10 PI             |
| Peu commun | 20 PI             |
| Rare       | 35 PI             |
| Épique     | 55 PI             |
| Légendaire | 80 PI             |

Le déblocage permanent ne signifie pas que le passif est automatiquement équipé au début d'une run : il faut toujours le sélectionner, en respectant le budget de départ disponible.

Les passifs non débloqués définitivement restent utilisables lorsqu'ils sont obtenus pendant une run, selon les règles d'acquisition applicables.

## 6. Principes d'équilibrage

Le système doit respecter plusieurs principes :

- **Diversité des stratégies :** les passifs doivent encourager des compositions et des approches différentes plutôt qu'imposer une combinaison optimale unique.
- **Choix significatifs :** le budget de départ doit obliger l'équipe à arbitrer entre plusieurs passifs intéressants.
- **Progression maîtrisée :** les passifs les plus puissants doivent être plus coûteux à débloquer et moins accessibles au début d'une run.
- **Synergies contrôlées :** les interactions entre passifs, classes, équipements et artefacts doivent être surveillées afin d'éviter les combinaisons excessivement puissantes.
- **Valeur des choix en cours de run :** les trois propositions lors d'une transition de boss doivent offrir des options intéressantes, sans rendre systématiquement un choix évident.

Les coûts, les probabilités d'apparition et la puissance réelle des passifs sont des valeurs de prototype à ajuster lors des tests.

## Probabilités d'obtention

Après chaque boss vaincu, un tirage détermine la rareté des passifs proposés en récompense.

Les joueurs choisissent ensuite un passif parmi trois propositions de cette même rareté.

Les probabilités dépendent de l'étage du boss vaincu.

### Probabilités de référence

|Rareté|Étage 1|Étage 10|
|---|---|---|
|Commun|90 %|10 %|
|Peu commun|8 %|20 %|
|Rare|1,5 %|30 %|
|Épique|0,4 %|25 %|
|Légendaire|0,1 %|15 %|
|**Total**|**100 %**|**100 %**|

### Progression entre les étages

Les probabilités évoluent linéairement entre l'étage 1 et l'étage 10.

Pour chaque rareté, la probabilité d'un étage intermédiaire est calculée selon la formule :

`P(F) = P(1) + ((F - 1) / 9) × (P(10) - P(1))`

- `F` : étage du boss vaincu.
- `P(1)` : probabilité correspondante à l'étage 1.
- `P(10)` : probabilité correspondante à l'étage 10.

Les calculs utilisent les valeurs non arrondies afin de conserver un total de 100 %.

Toutes les raretés restent accessibles à chaque étage. Les raretés supérieures sont simplement beaucoup plus rares dans les premiers étages.
## 7. Catalogue des passifs

La liste complète des passifs, leurs effets précis, leurs conditions d'activation et leurs éventuelles interactions sont documentés séparément dans le [[Codex des passifs]].