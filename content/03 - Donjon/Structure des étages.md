## 1. Objectif

Le donjon d'INFERNITY est divisé en 10 étages successifs. Chaque étage constitue une étape de progression, avec ses propres salles, rencontres, récompenses et boss.

La structure repose sur un système de nœuds. À chaque nœud, les joueurs choisissent une salle parmi plusieurs possibilités, puis avancent vers le nœud suivant. Les salles ignorées sont définitivement abandonnées.

Cette organisation permet de proposer des parcours différents à chaque run tout en conservant une progression structurée et prévisible dans son fonctionnement général.

## 2. Organisation d'un étage

Chaque étage comporte **10 nœuds de progression**.

- Les nœuds 1 à 9 proposent des salles normales.
- Le nœud 10 contient l'unique boss de l'étage.
- Chaque nœud normal propose entre 1 et 4 salles disponibles.
- Les joueurs choisissent une seule salle parmi celles proposées.
- Toutes les salles du nœud 9 mènent à la salle du boss, située au nœud 10.

Les dix nœuds correspondent aux étapes de progression, et non au nombre total de salles générées.

Puisque plusieurs salles peuvent être proposées à chaque nœud normal, un étage contient généralement beaucoup plus de dix salles. Cependant, les joueurs n'en visitent que neuf avant le combat contre le boss.

### Exemple

Un étage peut proposer trois salles au nœud 1, deux au nœud 2, quatre au nœud 3, puis un nombre variable de salles aux nœuds suivants.

Les joueurs ne visitent qu'une salle par nœud. Les autres salles représentent des possibilités alternatives qui ne seront pas explorées pendant cette progression.

Le nombre total de salles générées dépend donc du nombre de possibilités proposées à chaque nœud.

## 3. Choix des salles

À chaque nœud normal, les joueurs découvrent les salles disponibles et choisissent celle qu'ils souhaitent explorer.

Le nombre de salles proposées est déterminé aléatoirement, entre une et quatre.

Le choix peut dépendre du type de salle, des récompenses potentielles, des risques identifiés ou des objectifs poursuivis par l'équipe.

Les types des salles directement accessibles sont connus des joueurs avant leur choix. En revanche, le contenu précis d'une salle n'est pas nécessairement connu avant d'y entrer.

La manière dont les salles sont générées, reliées et réparties entre les nœuds est détaillée dans [[Génération des parcours]].

## 4. Progression sans retour en arrière

La progression dans le donjon est strictement orientée vers l'avant.

Une fois qu'une salle a été choisie et explorée, les joueurs passent au nœud suivant. Ils ne peuvent pas revenir au nœud précédent pour visiter une autre salle.

Les salles qui n'ont pas été choisies sont définitivement abandonnées pour la run en cours.

Cette règle s'applique même si une salle ignorée semble particulièrement intéressante après la découverte d'un nouvel indice ou d'une nouvelle récompense.

Les joueurs doivent donc accepter de renoncer à certaines possibilités afin de poursuivre leur progression.

Les raccourcis éventuellement disponibles constituent des exceptions encadrées à la progression habituelle. Leurs conditions et leurs conséquences sont définies dans les fiches qui décrivent ces mécaniques.

## 5. Progression vers le boss

Le nœud 10 est réservé au boss de l'étage.

Après avoir exploré une salle au nœud 9, les joueurs accèdent obligatoirement à cette salle de boss. Toutes les salles proposées au nœud 9 convergent vers le même boss.

Le boss constitue l'épreuve finale de l'étage. Sa défaite permet à l'équipe de terminer l'étage et de poursuivre sa progression dans le donjon.

Les caractéristiques des boss, leurs capacités, leurs récompenses et les éventuelles particularités de leurs combats sont détaillées dans leurs fiches respectives.

## 6. Récompenses et progression

Les récompenses dépendent des salles explorées, des rencontres accomplies et de la progression de l'équipe.

Les salles ignorées ne donnent pas accès aux récompenses qui leur sont propres. Les joueurs ne peuvent donc pas obtenir les récompenses d'une salle simplement parce qu'elle était disponible à un nœud.

La progression générale et les récompenses de fin d'étage suivent les règles définies dans les fiches correspondantes :

- [[Économie et récompenses]]
- [[Progression des personnages]]
- [[Mort et recommencement]]
- [[Progression permanente]]

Les récompenses propres à une catégorie de salle sont précisées dans la fiche de cette salle.

## 7. Visibilité du parcours

Les joueurs connaissent les types des salles qui leur sont directement accessibles et peuvent ainsi choisir leur prochaine destination en connaissance de cause.

Ils ne connaissent pas nécessairement le type des salles situées plus loin dans le parcours.

L'Éclaireur peut étendre cette visibilité en révélant des salles supplémentaires en profondeur. Son fonctionnement est décrit dans [[Compagnons]].

La visibilité du parcours doit permettre aux joueurs de prendre des décisions stratégiques sans supprimer l'incertitude liée à l'exploration.

## 8. Principes de conception

La structure des étages repose sur les principes suivants :

- **Choix exclusifs :** les joueurs ne peuvent visiter qu'une salle par nœud.
- **Progression continue :** chaque choix fait avancer l'équipe vers le boss.
- **Conséquences des décisions :** choisir une salle signifie renoncer aux autres possibilités du même nœud.
- **Variété :** le nombre et la nature des salles disponibles peuvent varier d'un nœud à l'autre et d'une run à l'autre.
- **Convergence :** toutes les routes rejoignent le boss au nœud 10.
- **Lisibilité :** les joueurs disposent des informations nécessaires pour choisir entre les salles directement accessibles.
- **Incertitude maîtrisée :** les joueurs peuvent anticiper certains risques sans connaître l'intégralité du contenu à venir.

## 9. Articulation avec les autres fiches

Cette fiche définit l'organisation générale des étages et les règles de progression entre leurs nœuds.

Les fiches complémentaires précisent les éléments suivants :

- [[Génération des parcours]] : création des nœuds, génération des salles disponibles et connexions entre elles.
- [[Types de salles]] : catégories de salles et fonctionnement commun.
- Les fiches individuelles des salles : contenu, événements, conditions particulières et récompenses.
- Les fiches individuelles des boss : rencontres finales et conditions de victoire.