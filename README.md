# 🖥️ Administration Active Directory — Windows Server 2022

### Projet technique — Administration systèmes Windows et gestion des identités

**Réalisé par : Matine Lolita GNAMKOULAMBA**

**Domaine :** Administration systèmes | Windows Server | Active Directory | Gestion des identités

**Technologies :** Windows Server 2022 • Active Directory Domain Services (AD DS) • GPO • DNS • PowerShell

---

## 📌 1. Présentation du projet

Ce projet documente la mise en place d'un laboratoire d'administration Active Directory sous Windows Server 2022.

Il s'inscrit dans une démarche de renforcement des compétences en administration des infrastructures Microsoft, notamment dans la gestion centralisée des utilisateurs, des groupes et des stratégies de sécurité.

L'objectif est de reproduire un environnement représentatif des opérations courantes d'administration systèmes en entreprise.

Ce laboratoire permet d'aborder les principales fonctionnalités d'Active Directory Domain Services (AD DS), de comprendre leur fonctionnement et de développer une méthodologie d'administration structurée.

---

## 🎯 2. Objectifs techniques

Les principaux objectifs du laboratoire sont :

- Installer et configurer Windows Server 2022.
- Déployer le rôle Active Directory Domain Services (AD DS).
- Comprendre l'architecture d'un domaine Active Directory.
- Administrer les comptes utilisateurs et les groupes de sécurité.
- Organiser les objets Active Directory dans des unités d'organisation (OU).
- Configurer et appliquer des stratégies de groupe (GPO).
- Comprendre le rôle du DNS dans le fonctionnement d'Active Directory.
- Vérifier le bon fonctionnement des services d'annuaire.
- Développer une méthodologie de diagnostic et de dépannage.

---

## 🏗️ 3. Environnement technique

| Composant | Technologie |
|---|---|
| Système serveur | Windows Server 2022 |
| Service d'annuaire | Active Directory Domain Services |
| Gestion des identités | Active Directory |
| Gestion des stratégies | Group Policy Management |
| Résolution de noms | DNS |
| Administration | Outils Windows Server |
| Automatisation | PowerShell — selon les opérations réalisées |
| Infrastructure | Laboratoire virtualisé |

### Architecture logique

Le laboratoire repose sur un environnement Windows Server permettant de centraliser l'administration des identités et des paramètres de configuration.

L'architecture comprend un serveur Windows destiné à héberger les services d'annuaire.

Les objets Active Directory sont organisés de manière à faciliter leur administration et l'application de stratégies de groupe.

---

## ⚙️ 4. Installation et configuration d'Active Directory

### 4.1 Préparation du serveur

La préparation d'un serveur Active Directory comprend notamment :

1. L'installation de Windows Server 2022.
2. La configuration des paramètres réseau.
3. La définition du nom du serveur.
4. La vérification de la connectivité réseau.
5. La préparation de la configuration DNS.

### 4.2 Installation du rôle AD DS

Le rôle Active Directory Domain Services permet de transformer un serveur Windows en contrôleur de domaine.

Il assure notamment :

- L'authentification des utilisateurs.
- La gestion centralisée des identités.
- L'organisation des ressources du domaine.
- L'application des politiques de sécurité.
- L'administration des comptes et groupes.

### 4.3 Configuration du domaine

La configuration du domaine constitue une étape essentielle du déploiement.

Elle permet de définir une infrastructure logique dans laquelle les utilisateurs, les ordinateurs et les groupes peuvent être administrés de manière centralisée.

---

## 👥 5. Administration des utilisateurs et des groupes

### Gestion des comptes utilisateurs

Active Directory permet de centraliser les opérations d'administration des comptes.

Les principales opérations étudiées comprennent :

- Création de comptes utilisateurs.
- Modification des propriétés des comptes.
- Gestion des mots de passe.
- Activation et désactivation des comptes.
- Organisation des utilisateurs dans des unités d'organisation.

### Gestion des groupes

Les groupes permettent de simplifier l'attribution et la gestion des autorisations.

L'utilisation de groupes de sécurité facilite notamment :

- La gestion des accès.
- L'administration des permissions.
- L'organisation des utilisateurs.
- L'application de règles cohérentes.

---

## 🗂️ 6. Organisation des unités d'organisation (OU)

Les unités d'organisation permettent de structurer les objets Active Directory.

Elles peuvent représenter :

- Des départements.
- Des services.
- Des équipes.
- Des catégories d'utilisateurs.
- Des groupes d'ordinateurs.

Cette organisation facilite l'administration du domaine et l'application ciblée des stratégies de groupe.

---

## 🔐 7. Configuration des stratégies de groupe (GPO)

Les stratégies de groupe constituent un mécanisme essentiel d'administration et de sécurisation des environnements Windows.

Elles permettent de centraliser la configuration des utilisateurs et des ordinateurs.

### Exemples de paramètres administrables

- Stratégies de mots de passe.
- Restrictions d'accès à certaines fonctionnalités.
- Paramètres de sécurité Windows.
- Configuration des postes de travail.
- Application de paramètres aux utilisateurs et ordinateurs.

### Objectif

Comprendre comment utiliser les GPO pour appliquer des configurations cohérentes et renforcer la sécurité d'un environnement Windows.

---

## 🔎 8. Vérifications techniques et diagnostic

L'administration d'un domaine Active Directory nécessite des contrôles réguliers.

Les vérifications peuvent notamment porter sur :

- La disponibilité du contrôleur de domaine.
- Le fonctionnement des services AD DS.
- La résolution DNS.
- L'accessibilité des objets Active Directory.
- L'application des stratégies de groupe.
- Les événements système liés aux services d'annuaire.

### Outils utiles au diagnostic

| Outil | Utilisation |
|---|---|
| Server Manager | Administration des rôles et fonctionnalités |
| Active Directory Users and Computers | Gestion des objets Active Directory |
| Group Policy Management | Administration des GPO |
| Event Viewer | Consultation des événements système |
| PowerShell | Administration et diagnostic |
| gpresult | Vérification des stratégies appliquées |
| dcdiag | Diagnostic du contrôleur de domaine |

---

## 📸 9. Captures d'écran et preuves techniques

Les captures d'écran du laboratoire seront regroupées dans le dossier `screenshots/`.

Elles permettront de documenter les configurations effectivement réalisées.

Les éléments pouvant être illustrés comprennent :

1. L'installation du rôle AD DS.
2. La configuration du contrôleur de domaine.
3. L'organisation des utilisateurs et des groupes.
4. La création des unités d'organisation.
5. La configuration des stratégies de groupe.
6. Les vérifications du fonctionnement du domaine.

Les captures seront accompagnées d'explications techniques précisant les opérations réalisées et les résultats observés.

---

## 🛠️ 10. Compétences développées

Ce laboratoire contribue au développement des compétences suivantes :

**Administration systèmes**
- Administration de Windows Server 2022.
- Gestion des services d'annuaire.
- Organisation des ressources informatiques.

**Gestion des identités**
- Administration des comptes utilisateurs.
- Gestion des groupes de sécurité.
- Structuration des unités d'organisation.

**Sécurité et configuration**
- Compréhension des stratégies de groupe.
- Gestion centralisée des paramètres Windows.
- Application des principes de gestion des accès.

**Diagnostic**
- Vérification des services Active Directory.
- Analyse des paramètres de configuration.
- Identification des anomalies de fonctionnement.

---

## 🚀 11. Perspectives d'amélioration

Le laboratoire pourra être enrichi par :

- L'intégration de postes clients Windows au domaine.
- L'automatisation des tâches administratives avec PowerShell.
- La mise en place de stratégies de sécurité supplémentaires.
- L'analyse d'incidents liés à l'authentification.
- La documentation de procédures de dépannage.
- La supervision des services Active Directory.

Ces éléments constituent des pistes d'évolution et ne sont pas présentés comme des réalisations déjà effectuées.

---

## 👩‍💻 12. À propos

Ce projet fait partie de mon portefeuille de réalisations techniques en administration systèmes, infrastructure informatique et cybersécurité.

Il vise à documenter mes travaux pratiques et à illustrer mes compétences dans la gestion des environnements Windows Server.

**Matine Lolita GNAMKOULAMBA**

Master Cybersécurité, Cloud & Systèmes

*Administration systèmes | Support informatique | Infrastructure IT*

---

**Projet personnel — Laboratoire Active Directory Windows Server 2022**
