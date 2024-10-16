# Récapitulatif de l'Organisation des Dépôts GitHub

## Objectif
Créer une structure claire et modulable pour le développement des intégrations et du hub backend, tout en facilitant la personnalisation pour les clients.

## Dépôts Backend

- **`integration-dev`**
  - **Usage** : Développement actif des intégrations.
  
- **`integration-stable`**
  - **Usage** : Versions finales des intégrations prêtes à être déployées (sans personnalisation client).

- **`integration-custom`**
  - **Usage** : Intégrations personnalisées pour les clients, avec des branches par client.

- **`hub-backend`**
  - **Usage** : Contient uniquement le code du hub backend universel, sans intégrations.

## Dépôts Frontend

- **`frontend-dev`**
  - **Usage** : Développement actif des interfaces utilisateur.

- **`frontend-stable`**
  - **Usage** : Versions finales des interfaces prêtes à être déployées.

- **`frontend-custom`**
  - **Usage** : Pages personnalisées pour chaque client, avec des branches spécifiques.

## Autres Dépôts Recommandés

- **`documentation`**
  - **Usage** : Documentation des API, intégrations, guides d'utilisation, etc.

- **`tests`**
  - **Usage** : Tests unitaires et d'intégration pour le hub et les intégrations.

- **`utils`**
  - **Usage** : Scripts d'automatisation, de déploiement, ou tâches utilitaires.

- **`examples`**
  - **Usage** : Projets ou démonstrations d'intégrations et fonctionnalités.

## Gestion des Branches

- **Branches par Client dans `integration-custom` et `frontend-custom`**
  - Chaque branche contiendra les intégrations et pages personnalisées pour chaque client, reliées au hub.

- **Versions Stables**
  - `integration-stable` et `frontend-stable` contiendront des versions finales prêtes pour le déploiement.

## Prochaines Étapes
- Créer les dépôts selon la structure définie.
- Documenter les processus de développement et d'intégration.
- Prévoir des réunions régulières pour assurer la bonne progression des projets.

---

**Merci à tous pour vos efforts ! N'hésitez pas à poser des questions si quelque chose n'est pas clair.**

