# Projet Novincept

## Mise en contexte
Le projet Novincept vise à développer diverses offres pour les entreprises, notamment dans le marketing, la communication et le développement d'infrastructures. Nous nous concentrerons sur la création d'infrastructures personnalisées à l'aide d'intégrations Open Source.

## Organisation des Projets
Pour gérer notre travail de manière efficace, nous avons divisé notre activité en plusieurs projets spécifiques, chacun axé sur un aspect particulier de notre développement :

### 1. Tâches
- **Description** : Gère toutes les tâches à accomplir, y compris la recherche d'intégrations et d'outils.
- **Vues** : 
  - **Board** : Suivi des Tâches (statuts : À faire, En cours, Terminé)
  - **Table** : Détails des Tâches.
- **Dépôt** : task
- **Explication** : Lors de la création d'une nouvelle tâche, vous pourrez créer dans *Tâches à faire* une nouvelle tâches qui sera insérée dans la première colonne *À faire*. Ensuite, vous pourrez créer une branche dans le dépôt *task* qui se nommera sous cette forme task-<index> vous pourrez trouver le numéro en regardant l'index de la dernière branche. L'index commencera à 0. Pour finir, vous créerez une nouvelle issue avec le label task. Toutes ces choses nous permettront de gérer l'avancer, de stocker les ressources ncéssaires aux tâches et d'en discuter en laissant une trâce bien rangée et retrouvable facilement.

### 2. Fonctionnalités
- **Description** : Regroupe les fonctionnalités à développer, en lien direct avec les tâches.
- **Vues** : 
  - **Board** : Fonctionnalités à venir (statuts : À venir, En développement, En test, Terminé)
  - **Table** : Liste des fonctionnalités avec détails.
- **Dépôt** : features
- **Explication** : Lors de la création d'une nouvelle tâche, vous pourrez créer dans *Tâches à faire* une nouvelle tâches qui sera insérée dans la première colonne *À faire*. Ensuite, vous pourrez créer une branche dans le dépôt *task* qui se nommera sous cette forme task-<index> vous pourrez trouver le numéro en regardant l'index de la dernière branche. L'index commencera à 0. Pour finir, vous créerez une nouvelle issue avec le label task. Toutes ces choses nous permettront de gérer l'avancer, de stocker les ressources ncéssaires aux tâches et d'en discuter en laissant une trâce bien rangée et retrouvable facilement.

### 3. Bugs
- **Description** : Gestion des bugs signalés durant le développement.
- **Vues** : 
  - **Board** : Suivi des Bugs (statuts : Bugs signalés, En cours de correction, Résolu)
  - **Table** : Détails des Bugs.

### 4. Évolutions et Améliorations
- **Description** : Suggestions d’évolutions et d’améliorations à apporter aux fonctionnalités existantes.
- **Vues** : 
  - **Table** : Liste des améliorations à envisager.
  - **Roadmap** : Plan d'amélioration.

### 5. Feedback des Clients
- **Description** : Retours des clients sur nos produits et services.
- **Vues** : 
  - **Table** : Retours Clients.
  - **Board** : Suivi des Retours Clients (statuts : À examiner, En cours d'analyse, Résolu).

## Fonctionnement Général
Voici comment nous gérons le flux de travail :

1. **Création d'une Tâche** : Lorsqu'une nouvelle tâche est identifiée, comme par exemple la recherche d'une nouvelle intégration ou un outils, vous pourrez la créer depuis une issue dans le dépôt `task` et une branche sera dévelopé, elle sera ensuite créée automatiquement dans le projet **Tâches**.
   
2. **Mise en Fonctionnalité** : Une fois que l'intégration est trouvée, elle est déplacée dans le projet **Fonctionnalités** sous "Fonctionnalités à venir" jusqu'au jour de son développement.

3. **Développement et Suivi des Bugs** : Quand le développement commence, la fonctionnalité passe à "En développement". Si des bugs sont identifiés, ils sont ajoutés au projet **Bugs** pour être corrigés.

4. **Améliorations et Feedback Client** : Les suggestions d'amélioration et les retours des clients sont traités de manière indépendante dans les projets **Évolutions et Améliorations** et **Feedback des Clients**, respectivement.


---

**Remarque** : Vos commentaires et suggestions sont toujours les bienvenus pour améliorer notre organisation et nos processus.
