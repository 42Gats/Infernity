## 1. Objectif du système

Les compagnons sont des alliés que les joueurs peuvent recruter au cours de leurs explorations. Chacun apporte une capacité particulière qui influence la manière dont l'équipe progresse dans le donjon.

Contrairement aux personnages jouables, les compagnons ne participent pas directement aux combats. Ils apportent un soutien spécialisé dans l'exploration, la survie, la gestion des artefacts ou l'utilisation des relances.

Les compagnons découverts peuvent être améliorés de manière permanente au hub. Chaque amélioration renforce leur capacité et représente un investissement dans une stratégie particulière.

### Principes généraux

- L'équipe ne peut emmener qu'un seul compagnon par run.
- Les compagnons doivent être découverts et recrutés au cours de l'exploration.
- Les conditions exactes de découverte et de recrutement sont décrites dans la fiche de la salle correspondante.
- Une fois recruté, un compagnon reste disponible pour les runs suivantes.
- Les améliorations de son camp sont permanentes et achetées au hub.
- Chaque compagnon possède cinq niveaux d'amélioration.
- Les effets d'un compagnon ne s'appliquent que si celui-ci accompagne l'équipe pendant la run.

## 2. Améliorations des camps

Chaque compagnon possède un camp ou un espace dédié au hub. Ce lieu peut être amélioré afin de renforcer les capacités du compagnon.

|Niveau|Coût en PI|
|---|---|
|Niveau 1|25 PI|
|Niveau 2|50 PI|
|Niveau 3|85 PI|
|Niveau 4|125 PI|
|Niveau 5|175 PI|

Les coûts correspondent aux différents paliers d'amélioration. Ils ne sont pas cumulés : le coût d'un palier correspond au prix à payer pour passer au niveau indiqué depuis le niveau précédent.

Le premier niveau constitue le niveau de base du compagnon. Les améliorations suivantes renforcent progressivement sa spécialité.

---

## 3. L'Éclaireur

### 3.1. Identité et histoire

**Nom :** Bawky 
**Nature :** corbeau intelligent  
**Spécialité :** exploration et reconnaissance

L'Éclaireur est un corbeau particulièrement intelligent, habitué à se déplacer dans les passages étroits et les zones dangereuses du donjon. Il observe les embranchements, mémorise les chemins et revient transmettre ses découvertes au groupe.

Sa curiosité est presque maladive : il aime comprendre la structure du donjon et supporte mal de laisser une zone inexplorée. Il ne possède cependant aucune connaissance surnaturelle des dangers. Il observe ce qui est visible et rapporte uniquement les informations qu'il a pu recueillir.

### 3.2. Camp au hub

Son camp est un observatoire aménagé en hauteur, constitué de plateformes, de perchoirs et de cartes du donjon. Le corbeau y rassemble les objets qu'il rapporte de ses expéditions et organise ses itinéraires.

Les améliorations du camp lui permettent de mieux cartographier les embranchements et de transmettre des informations sur des salles plus éloignées.

### 3.3. Effet

L'Éclaireur révèle le type des salles situées plus loin sur le parcours, au-delà de la profondeur normalement visible par les joueurs.

La profondeur supplémentaire révélée dépend du niveau de son camp.

|Niveau du camp|Profondeur supplémentaire|
|---|---|
|Niveau 1|1 salle|
|Niveau 2|2 salles|
|Niveau 3|3 salles|
|Niveau 4|4 salles|
|Niveau 5|5 salles|

La profondeur est calculée à partir de la position actuelle du groupe dans le parcours. L'Éclaireur peut donc continuer à fournir des informations à mesure que l'équipe progresse.

### 3.4. Limites

- L'Éclaireur révèle les types de salles et leur position dans les embranchements, mais pas leur contenu détaillé.
- Il ne révèle pas à l'avance les ennemis précis, les récompenses, les pièges ou les événements qui attendent le groupe.
- Il ne permet pas de modifier les connexions entre les salles ni de revenir en arrière.
- La limite de cinq salles supplémentaires s'applique même si le camp atteint son niveau maximal.

---

## 4. Le Soigneur

### 4.1. Identité et histoire

**Nom :** Néli 
**Nature :** herboriste itinérante  
**Spécialité :** récupération et soins

Le Soigneur est une ancienne médecin de terrain qui a appris à traiter les blessures dans des conditions extrêmes. Elle connaît les plantes du donjon, prépare des remèdes et sait reconnaître les blessures qui risquent de mettre en danger un aventurier.

Elle a rejoint le hub afin de disposer d'un lieu où stocker ses ingrédients, perfectionner ses préparations et soigner les explorateurs qui reviennent blessés.

Sa priorité n'est pas de rendre les aventuriers invulnérables, mais de leur donner suffisamment de ressources pour poursuivre leur progression.

### 4.2. Camp au hub

Son camp est une infirmerie mêlant dispensaire, serre et laboratoire d'herboristerie. Les premières installations permettent de préparer des remèdes simples. Les améliorations suivantes apportent de meilleurs outils, des réserves d'ingrédients plus importantes et des préparations plus efficaces.

### 4.3. Effet

Après chaque combat remporté, le Soigneur produit un pool de soins commun que l'équipe peut répartir entre ses personnages.

Le nombre de dés de soins dépend du niveau moyen des personnages et du niveau du camp.

**Formule de base :**

$$
D = 1 + \left\lfloor \frac{N-1}{5} \right\rfloor + (C-1)
$$

Avec :

- (D) : nombre de dés de soins disponibles dans le pool.
- (N) : niveau personnages jouables.
- (C) : niveau du camp du Soigneur.
- Chaque dé est un d4.

Le pool permet de restaurer un total de points de vie correspondant au résultat des dés lancés. Les joueurs décident ensemble de la répartition des soins entre les personnages éligibles.

**Exemple :** une équipe de niveau moyen 6 accompagnée d'un Soigneur dont le camp est au niveau 2 dispose de :

$$
D=1+\left\lfloor\frac{6-1}{5}\right\rfloor+(2-1)=3  
$$

Elle récupère donc un pool de 3d4 points de vie après le combat.

### 4.4. Limites

- Les soins sont déclenchés après un combat remporté, pas après une fuite ou une défaite.
- Le pool est commun à toute l'équipe : chaque point de soin utilisé par un personnage ne peut pas être utilisé par un autre.
- Les soins ne peuvent pas dépasser les points de vie maximum d'un personnage.
- Le Soigneur ne ressuscite pas les personnages gravement blessés.
- Les soins inutilisés après leur attribution sont perdus : ils ne s'accumulent pas d'un combat à l'autre.
- Le niveau du camp et le niveau moyen des personnages déterminent le nombre de dés, mais les dés ne garantissent pas une quantité fixe de soins.

---

## 5. Le Forgeron

### 5.1. Identité et histoire

**Nom :**  Morith
**Nature :** artisan spécialisé dans les reliques  
**Spécialité :** transformation des artefacts

Le Forgeron est un artisan qui a consacré sa vie à l'étude des propriétés des artefacts du donjon. Il a découvert que certaines reliques peuvent être sacrifiées ensemble afin de concentrer leurs propriétés dans un nouvel objet plus puissant.

Cette technique reste imprévisible. Même avec une maîtrise parfaite de son art, le Forgeron ne peut pas garantir la nature exacte de l'artefact obtenu.

### 5.2. Camp au hub

Son camp est un atelier de forge alimenté par une source d'énergie étrange. Il comprend des enclumes gravées, des outils spécialisés et des dispositifs capables de contenir l'énergie des artefacts.

Les améliorations de l'atelier lui permettent de limiter les pertes lors des transformations et d'augmenter ses chances de produire un artefact exceptionnel.

### 5.3. Effet

Pendant une run, le Forgeron permet de sacrifier plusieurs artefacts de même rareté afin d'en obtenir un de rareté supérieure.

|Niveau du camp|Effet|
|---|---|
|Niveau 1|Sacrifier 3 artefacts de même rareté pour obtenir 1 artefact aléatoire de rareté supérieure|
|Niveau 2|Inchangé|
|Niveau 3|Sacrifier seulement 2 artefacts de même rareté|
|Niveau 4|30 % de chances d'obtenir un artefact de deux raretés supérieures au lieu d'une|
|Niveau 5|45 % de chances d'obtenir un artefact de deux raretés supérieures au lieu d'une|

Au niveau 1, la recette nécessite donc trois artefacts. À partir du niveau 3, elle n'en nécessite plus que deux.

À partir du niveau 4, le résultat peut bénéficier d'une amélioration supplémentaire de rareté selon la probabilité indiquée. Au niveau 5, cette probabilité passe à 45 %.

### 5.4. Rareté du résultat

Le résultat dépend de la rareté des artefacts sacrifiés.

- Le résultat normal possède une rareté supérieure d'un palier à celle des artefacts sacrifiés.
- Le résultat amélioré possède une rareté supérieure de deux paliers.
- La rareté maximale est légendaire.
- Si une amélioration de rareté dépasse le palier légendaire, le résultat est plafonné à légendaire.

Le Forgeron ne permet pas de transformer des artefacts de raretés différentes dans une même recette.

### 5.5. Limites

- Les artefacts sacrifiés sont définitivement perdus pour la run.
- Le nouvel artefact est tiré aléatoirement parmi les artefacts pouvant être obtenus selon les règles du système.
- La transformation ne garantit pas un artefact adapté à la composition de l'équipe.
- Les artefacts déjà équipés doivent être retirés avant de pouvoir être sacrifiés.
- Le Forgeron ne permet pas de débloquer définitivement un artefact : le déblocage permanent reste régi par les règles générales des artefacts.

---

## 6. Le Tricheur

### 6.1. Identité et histoire

**Nom :** Kruglo
**Nature :** gobelin joueur et escroc  
**Spécialité :** conservation des relances

Le Tricheur est un joueur professionnel dont la réputation repose sur sa capacité à manipuler les probabilités. Il prétend pouvoir influencer la chance elle-même, mais ses méthodes reposent surtout sur des dés truqués, des tours de passe-passe et une connaissance approfondie des comportements humains.

Il s'est installé au hub pour organiser des parties et perfectionner ses techniques. Il accompagne les aventuriers en espérant que leurs mésaventures lui fourniront de nouvelles occasions de tester ses méthodes.

### 6.2. Camp au hub

Son camp est une petite salle de jeu remplie de tables, de dés, de cartes et de mécanismes dissimulés. Les améliorations du camp lui permettent de perfectionner ses dés truqués et de mieux contrôler les probabilités.

### 6.3. Effet

Chaque fois que l'équipe utilise une relance, le Tricheur a une chance de permettre au groupe de la conserver.

|Niveau du camp|Chance de conserver la relance|
|---|---|
|Niveau 1|10 %|
|Niveau 2|15 %|
|Niveau 3|20 %|
|Niveau 4|25 %|
|Niveau 5|30 %|

Le jet de conservation est effectué immédiatement après l'utilisation de la relance.

- En cas de réussite, la relance n'est pas consommée.
- En cas d'échec, elle est consommée normalement.

### 6.4. Relances concernées

Le pouvoir du Tricheur s'applique aux différentes catégories de relances disponibles dans INFERNITY, notamment :

- Les relances de quêtes.
- Les relances de butin des coffres.
- Les relances de choix de passifs lors des transitions de boss.

Le Tricheur ne crée pas de relances supplémentaires : il permet uniquement de conserver une relance qui aurait autrement été consommée.

### 6.5. Limites

- Une seule tentative de conservation est effectuée par relance utilisée.
- Une relance conservée ne déclenche pas une nouvelle tentative.
- Le Tricheur n'influence pas le résultat de la relance elle-même.
- Ses chances de succès dépendent du niveau de son camp, et non du niveau des personnages.

---

## 7. Principes d'équilibrage

Les compagnons doivent proposer des avantages différents sans devenir indispensables à la réussite d'une run.

- **Spécialisation :** chaque compagnon doit apporter un avantage identifiable qui justifie de le choisir.
- **Choix significatif :** la limite d'un compagnon par run oblige l'équipe à privilégier une stratégie.
- **Progression permanente :** les améliorations doivent être utiles, mais ne doivent pas supprimer les risques fondamentaux du donjon.
- **Complémentarité :** les compagnons soutiennent les personnages sans remplacer leurs capacités de classe.
- **Cohérence :** chaque amélioration doit renforcer la spécialité du compagnon plutôt que lui donner un effet sans rapport.
- **Équilibrage évolutif :** les valeurs chiffrées restent des valeurs de prototype à ajuster lors des tests.

Les conditions précises de découverte et de recrutement sont documentées dans les fiches des salles correspondantes.