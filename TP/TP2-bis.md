### Scénario de TP : Développement Collaboratif de "TechStore"

**Contexte :**
Vous faites partie d'une équipe de développement web chargée de créer "TechStore", un site e-commerce. Le projet est divisé en plusieurs phases, chacune nécessitant l'utilisation de Git et Git Flow pour la collaboration et la gestion de version.

#### Phase 1: Initialisation et Planification

**Tâches :**

1. Un membre de l'équipe crée le dépôt sur GitHub et les autres membres le forkent.
2. L'équipe discute et assigne les sections du site web à chaque membre.

**Questions :**

- Comment allez-vous organiser et nommer vos branches selon Git Flow? (Vous pouvez proposer une alternative à Git Flow si vous le souhaitez, dans tous les cas un schema de branches doit être défini)
- Quels outils allez-vous utiliser pour planifier et suivre le progrès de votre projet? (cf consignes supplementaires)

#### Phase 2: Développement des Fonctionnalités

**Tâches :**

1. Chaque membre crée (au moins) une branche de fonctionnalité pour sa section du site.
2. Développez votre partie assignée en faisant des commits réguliers.

**Questions :**

- Comment avez-vous organisé vos commits pour maintenir un historique clair ?
- Comment gérez-vous les dépendances entre différentes parties du site?

#### Phase 3: Intégration et Tests

**Tâches :**

1. Chaque membre soumet une pull request de sa branche vers `develop`.
2. L'équipe passe en revue les pull requests, discute des changements, et fusionne dans `develop`.

**Questions :**

- Quels furent les défis rencontrés lors de la fusion des différentes fonctionnalités ?
- Comment avez-vous assuré que le site fonctionne de manière cohérente après les merges ?

#### Phase 4: Préparation de la Release

**Tâches :**

1. Créer une branche `release` et y effectuer des tests finaux (les tests seront simulés...).
2. Apporter des ajustements mineurs si nécessaire.

**Questions :**

- Quels types de tests avez-vous effectués avant la mise en production ?
- Avez-vous rencontré des problèmes pendant cette phase et comment les avez-vous résolus ?

#### Phase 5: Mise en Production et Maintenance

**Tâches :**

1. Mergez la branche `release` dans `main` et `develop`.
2. En cas de bugs, créez et gérez des branches `hotfix`.

**Questions :**

- Comment gérez-vous les retours et les bugs après la mise en production ?
- Quelles stratégies adoptez-vous pour la maintenance continue du site ?

#### Phase 6: Rétrospective et Documentation

**Tâches :**

1. Rédigez une documentation détaillée du processus de développement.
2. Effectuez une rétrospective de projet pour discuter des leçons apprises.

**Questions :**

- Quels sont les principaux enseignements tirés de ce projet ?
- Comment pourriez-vous améliorer vos pratiques de collaboration et de versioning pour des projets futurs ?

#### Phase 7: Rétrospective et Documentation

**Tâches :**

Reiterez le cycle pour aboutir a une seconde version du site, avec des fonctionnalites differentes ou des modifications significatives.

**Questions :**

- Quelles sont les principales différences entre la première et la seconde version du site ?
- Quels sont les principaux enseignements tirés de ce projet ?
- Comment pourriez-vous améliorer vos pratiques de collaboration et de versioning pour des projets futurs ?

Consignes supplementaires pour les étudiants :

- Présentez clairement votre systeme de versioning, utilisez des lib comme commitizen pour avoir des messages de commit clairs et cohérents. Generez des changelogs a chaque release pour documenter les changements.
- Utilisez les outils fournis par GitHub/GitLab pour la gestion de projet et la collaboration (issues, milestones, etc.).
- Utilisez des outils de CI/CD comme GitHub Actions/Github Pages pour automatiser le processus de build et de déploiement.
- Utilisez des outils de gestion de dépendances comme npm pour gérer les dépendances et les packages.
- L'historique des commits doit témoigner de la collaboration et de la répartition des tâches entre les membres de l'équipe.
- La documentation doit être claire et détaillée, et doit inclure des captures d'écran du site final.
