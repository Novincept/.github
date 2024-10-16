# 🛠️ Novincept - Hub d'Intégrations

Bienvenue sur l'organisation GitHub de **Novincept**, où nous développons et gérons des intégrations backend et frontend pré-dev et prête à personaliser selon les infrastructures demandées de nos clients. Ce README fournit une vue d'ensemble complète de la structure du projet, les instructions, ainsi que les workflows à suivre.

## 📂 Structure des Dépôts

Notre projet est organisé de manière modulaire en plusieurs dépôts et branches pour permettre la centralisation et la personnalisation des demandes des clients. Voici un récapitulatif :

### 1. **Dépôts Backend**

| Dépôt | Description |
|-------|-------------|
| **integration-dev** | Dépôt de développement où chaque intégration est développée. Chaque intégration est dans sa propre branche dédiée. |
| **integration-final** | Dépôt contenant les versions finales des intégrations prêtes à être branchées sur le hub backend. |
| **integration-custom** | Dépôt où les intégrations sont reliées pour chaque client. Chaque client a sa branche dédiée. |
| **hub-backend** | Dépôt du hub backend universel qui connecte les intégrations selon celles que le client demandera. Il est universel ce qui veux dire que les integrations seront créées selon un modèle universel pour se connecter au hub sans problème.  |

### 2. **Dépôts Frontend**

| Dépôt | Description |
|-------|-------------|
| **frontend-dev** | Dépôt de développement des pages frontend, avec une branche pour chaque intégration frontend. |
| **frontend-final** | Dépôt contenant les versions finales des intégrations frontend, prêtes à être adaptées aux demandes clients. |
| **frontend-custom** | Dépôt où les pages frontend sont reliées et personnalisées pour chaque client. Chaque client a sa branche dédiée. |
| **hub-frontend** | Dépôt du hub frontend universel qui relie les pages des intégrations demandées.|

## 🌲 Branches

### Dans les dépôts `dev`
Chaque intégration (backend ou frontend) a sa propre branche dédiée dans les dépôts `dev`. Les branches sont nommées selon l'intégration spécifique, par exemple :
- `integration-authentik`
- `integration-mailer`
- `integration-authentik`
- `integration-dashboard`
- `page-authentik`
- `page-dashboard`

### Dans les dépôts `custom`
Chaque client a sa propre branche dans les dépôts `custom`, où les intégrations sont reliées au hub principal et configurées selon les besoins du client, par exemple :
- `client-xyz` dans `integration-final`
- `client-xyz` dans `frontend-final`

## 🚀 Workflow de Développement

### 1. **Développement des Intégrations**
- Toutes les nouvelles intégrations sont développées dans les branches dédiées des dépôts `integration-dev` et `frontend-dev`.
- Utilisez toujours les branches spécifiques aux intégrations pour éviter les conflits.
- Testez les intégrations localement avant de les pousser dans les branches dev.

### 2. **Version Finalisée**
- Une fois l'intégration terminée et validée, elle est transférée dans le dépôt `integration-final` ou `frontend-final`.
- Créez une pull request pour valider et fusionner la branche vers `final`.

### 3. **Personnalisation Client**
- Pour chaque client, une nouvelle branche est créée dans les dépôts `integration-custom` et `frontend-custom`.
- Les intégrations finalisées sont reliées au hub universel backend dans ces branches.
- Les pages des intégrations finalisées sont reliées au hub universel frontend dans ces branches.
- Utilisez les fichiers `.env` pour configurer les informations spécifiques au client (nom de l'entreprise, paramètrage globaux pour le client, etc.). Les pages et intégrations doivent être au maximum parametrable depuis le `.env`.
- Le `integration-custom` et `frontend-custom` contiendront donc respectivement le backend et front-end du client qui seront séparés

## 🔄 Git Flow

### Processus de Pull Request (PR)
1. **Développement** : Créez une branche spécifique pour chaque fonctionnalité ou correction dans les dépôts `dev`.
2. **Pull Request** : Une fois l'intégration terminée, soumettez une PR pour fusionner la branche dans `integration-final` ou `frontend-final`.
3. **Validation** : *Un autre développeur doit valider la PR avant qu'elle ne soit fusionnée*.
4. **Merge** : Après validation, la branche est fusionnée et la version finale est prête à être utilisée en cas de demande.

# 📈 Suivi des Projets avec GitHub Projects

Nous utilisons GitHub Projects pour suivre l'avancement des tâches. Chaque projet est lié à un dépôt pour faciliter la gestion des issues et des pull requests.

## Projets à suivre
- Développement du Hub Universel ( Frontend et Backend )
- Intégrations ( Backend )
- Développement Frontend
- Personnalisation des Intégrations pour Client
- Tests et Qualité
- Maintenance et Améliorations
- Documentation

Chaque projet est divisé en étapes qui sont spécifiques aux projets en questions. Vous pourrez déplacer les cartes dans ces différentes étapes.

Lorsque qu'un bug est trouvé, notamment lors des tests, vous devrez créer une issue dans le dépôt concerné et ajouter une carte dans le projet concerné. Si le bug concerne une page dans le frontend, vous devrez créer une carte dans `Développement Frontend`


**Pour toute question, me joindre sur mon mail : renan.yhuel@novincept.com ou par message privé ( c'est plus simple ) par le biais de KSuite de Novincept.**
